# DiffSpot

## Overview

**DiffSpot** is a web-based tool hosted at [diffspot.pawix.tech](https://diffspot.pawix.tech) that enables users to compare two blocks of text and highlight the differences in an intuitive, visual format. Whether you're a developer reviewing code changes, or an editor tracking revisions, DiffSpot helps you easily spot the differences between text versions. It leverages `jsdiff` for performing text comparisons and `Prism.js` for syntax highlighting, making it an essential tool for text and code comparison.

## Features

- **Text Comparison:** Quickly and accurately compare two blocks of text line by line.
- **Visual Highlights:** Differences are clearly marked—text additions are highlighted in green, while deletions are highlighted in red.
- **Syntax Highlighting:** Automatically applies syntax highlighting to HTML content, making code comparisons clear and easy to understand.
- **Reset Functionality:** Instantly clear both input fields and reset the comparison results with a single click.
- **Responsive Design:** The interface is fully responsive, ensuring an optimal experience on both desktop and mobile devices.

## Technologies Used

- **HTML5:** Structure and layout of the web page.
- **CSS3 (Tailwind CSS):** Tailwind CSS framework for styling and responsive design.
- **JavaScript:** Core scripting for handling text comparison and UI interactions.
- **jsdiff:** A JavaScript library used to compute the differences between two texts.
- **Prism.js:** A lightweight syntax highlighter used to enhance the readability of HTML code.

## Getting Started

### Prerequisites

You only need a modern web browser with JavaScript enabled to use DiffSpot. No additional software or installation is required.

### Accessing DiffSpot

Simply visit [diffspot.pawix.tech](https://diffspot.pawix.tech) to start using the tool.

### Usage

1. **Input Texts:**
   - Enter the first text into the "Text 1" field.
   - Enter the second text into the "Text 2" field.

2. **Compare:**
   - Click the "Compare" button to generate a side-by-side comparison.
   - The differences between the texts will be displayed, with additions and deletions clearly highlighted.

3. **Reset:**
   - Click the "Reset" button to clear both text fields and remove the comparison results.