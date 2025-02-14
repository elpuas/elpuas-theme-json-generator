# Theme JSON Generator

A web app built with Astro to create WordPress theme.json files via a user-friendly form.

## Overview

This project provides an easy-to-use interface to configure WordPress theme settings. Users can fill out form fields corresponding to theme.json options, see real-time JSON previews, and download the file using the browser’s Blob API.

## The Theme.json Schema

The theme.json schema is a JSON object that defines the structure of the theme.json file. It is used to validate the theme.json file and to provide a list of possible values for the theme.json file.

[https://schemas.wp.org/trunk/theme.json](https://schemas.wp.org/trunk/theme.json)

## Features

• Form-based Interface: Easily input settings for colors, typography, spacing, etc.
• Live JSON Preview: See the generated JSON update in real time.
• Client-side Validation: Validate against the official WordPress theme.json schema.
• Downloadable Output: Use the Blob API to download the generated file.
• Netlify-ready: Designed for easy deployment on Netlify.

## Getting Started

### Prerequisites

• Node.js (v14+)
• npm or yarn

### Installation

1. Clone the Repository:

```bash
git clone <https://github.com/elpuas/elpuas-theme-json-generator.git>
cd theme-json-generator
```

2. Install Dependencies:

```bash
npm install
```

3. Run the Development Server:

```bash
npm run dev
```

## Deployment

Connect the repository to Netlify for automatic deployment. No special backend is needed since all functionality is client-side.

## File Structure

```bash
/src
  /pages
    index.astro
    preview.astro
  /components
    FormComponent.astro
    /ui
      Button.astro
      Input.astro
      Select.astro
      Textarea.astro
  /layouts
    Layout.astro
  /styles
    global.css
    components.css
  /utils
    themeJsonUtils.ts
  /types
    themeJsonTypes.ts
/public
  favicon.ico
/theme.json       // Example output file
/theme-json-schema.json // The theme.json schema
README.md
package.json
astro.config.mjs
tsconfig.json
```

## Usage

1. Open the app in your browser.
2. Fill out the form fields to configure your theme settings.
3. Click the “Generate” button to preview your JSON.
4. Click the “Download” button to save your theme.json file.

## Contribution Guidelines

- Fork the repository.
- Create a new branch for your feature or fix.
- Ensure your code is modular and maintainable.
- Submit a pull request with a detailed explanation of your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## AI Agent Instructions

- Objective: Build an Astro web app for generating WordPress theme.json files.
- Key Tasks:
- Create a modular project structure with components for form inputs.
- Implement real-time JSON generation and validation.
- Integrate file download functionality using the Blob API.
- Ensure code adheres to the WordPress theme.json schema.
- Future Enhancements:
- Session saving/loading.
- Version control for theme changes.
- Enhanced UI/UX improvements.
