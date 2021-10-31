# Webpack & Handlebars HTML Boilerplate

## Overview
HTML boilerplate. Uses Handlebars.js as the template language and Webpack 4 as the bundler.

<strong><a href="https://github.com/PixelRocket-Shop/boilerplate-html/archive/main.zip">Download ZIP</a></strong>

## Table of contents

- [Requirements](#requirements)
- [Quick Start](#quick-start)
- [Template Pages](#template-pages)
- [Template File Structure](#template-file-structure)
- [Handlebars](#handlebars)
- [Template JSON Data](#template-json-data)
- [Customise Template Styles](#customise-template-styles)
- [Create New Pages](#create-new-pages)
- [Contact Us](#contact-us)


## Requirements
Ensure that you have Node.js installed. [You can download it from here](https://nodejs.org/en/download/)


## Quick Start
- [Download the latest release](https://github.com/PixelRocket-Shop/boilerplate-html/archive/main.zip) OR clone the repo: `git clone https://github.com/PixelRocket-Shop/boilerplate-html.git`
- Install Node.js if you don't already have it on your system.
- Open the project root in your command line.
- run `npm install` in your command line.
- run `npm start` to start Webpack devserver.
- if you want to recompile the template files (which output to the dist folder), run `npm run build`


## Template Pages
The template consists of a single, barebones page:

* Homepage

To keep code repetition to a minimum, we've used Handlebars.js as the templating engine and partials to quickly add the same code to different pages. We also use a Handlebars plugin for JSON data - this allows us to use loops and output a single HTML code block instead of repeating the same HTML.


## Template File structure
📁 dist - Generated version of the template. Go here if you do not want to work with the template source code. But be warned: if you customise anything in this folder directly, and then later recompile the template using webpack, unless you move the dist folder out of the template, your changes will be overridden.

📁 node_modules - Directory where NPM installs dependancies. You will not see this folder until you complete the template installation. You do not need to create this folder.

📁 src - Template source code. Go here to customise your template.

📁 src/assets - Template assets such as CSS, JS, Images etc.

📁 src/data - Template JSON Data files. We use these JSON files to make your job easier to insert content into the template. 

📁 src/html - Template pages. Go here to edit existing pages or add new pages.

📁 src/partials - Handlebars partial templates. 


## Handlebars
Handlebars is a template engine that allows us to keep our template source code as organised and as clean as possible. It cuts down on code duplication and through the use of helper functions, allows template developers to very quickly output large amounts of data with minimal code. [You can read more about it here](https://handlebarsjs.com).


## Template JSON Data
The Webpack Handlebars plugin that we use comes with a utility that allows us to pass in JSON files as template data.

Please navigate to: src/data. Here is where our template data JSON files reside. You can edit, remove or add your own to this folder.


## Customise Template Styles
All of the template's source CSS/SASS files are kept inside the template's assets folder. Navigate to src/assets/scss. Open up theme.scss with your editor.

This is the main entry point for all other SASS/CSS files.


## Create New Pages
To create a new page, navigate in your code editor to: src/html. To make it easier to get the correct HTML in place, clone an existing page. Rename the newly-created file to whatever URL you require. And that's it. You are now free to open the new page with your code editor, make your changes, and then save the file. Quit Webpack devserver and restart it for the page to show up.

## Contact Us
You can find our website [here](https://www.pixelrocket.store) or you can email us at support@pixelrocket.store