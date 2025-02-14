# Theme JSON Generator

A web app built with Astro to create WordPress theme.json files via a user-friendly form.

## Overview

This project provides an easy-to-use interface to configure WordPress theme settings. Users can fill out form fields corresponding to theme.json options, see real-time JSON previews, and download the file using the browser’s Blob API.

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
```
git clone <https://github.com/yourusername/theme-json-generator.git>
cd theme-json-generator
```

 2. Install Dependencies:
```
npm install
```

 3. Run the Development Server:
```
npm run dev
```

## Deployment

Connect the repository to Netlify for automatic deployment. No special backend is needed since all functionality is client-side.

## File Structure
```
/src
  /components
    FormComponent.astro
    InputField.astro
  /pages
    index.astro
    preview.astro
/public
  favicon.ico
/theme.json       // Example output file
README.md
package.json
astro.config.mjs
```

## Usage
 1. Open the app in your browser.
 2. Fill out the form fields to configure your theme settings.
 3. Click the “Generate” button to preview your JSON.
 4. Click the “Download” button to save your theme.json file.

## Contribution Guidelines
 • Fork the repository.
 • Create a new branch for your feature or fix.
 • Ensure your code is modular and maintainable.
 • Submit a pull request with a detailed explanation of your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## AI Agent Instructions
 • Objective: Build an Astro web app for generating WordPress theme.json files.
 • Key Tasks:
 • Create a modular project structure with components for form inputs.
 • Implement real-time JSON generation and validation.
 • Integrate file download functionality using the Blob API.
 • Ensure code adheres to the WordPress theme.json schema.
 • Future Enhancements:
 • Session saving/loading.
 • Version control for theme changes.
 • Enhanced UI/UX improvements.


