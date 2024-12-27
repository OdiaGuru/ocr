# OCR Web App

A browser-based Optical Character Recognition (OCR) application that supports multiple languages and image processing features.

## Features

- Multi-language OCR support:
  - Odia
  - English
  - Swedish
  - Hindi
- Image processing capabilities:
  - Crop images
  - Convert to grayscale
- Multiple input methods:
  - File upload
  - Drag and drop
  - Paste from clipboard
- Dark/Light theme toggle
- Copy results to clipboard
- Responsive design

## Technologies Used

- Tesseract.js v2.1.0 for OCR processing
- PDF.js 2.9.359 for PDF support
- Cropper.js 1.5.12 for image manipulation
- Font Awesome 5.15.4 for icons

## Usage

1. Select input method:
   - Click the paste zone to paste an image
   - Drag and drop an image
   - Use the file input button
2. Select the target language from the dropdown
3. Optional: Use image controls to crop or convert to grayscale
4. Click "Process" to perform OCR
5. Copy results using the "Copy to Clipboard" button

## Theme Support

Toggle between dark and light themes using the theme button in the top-right corner.

## Browser Compatibility

Works in modern browsers supporting:
- File API
- Canvas
- Clipboard API
- ES6+ JavaScript
