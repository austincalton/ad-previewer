# Chrome Side Panel Ad Previewer

This Chrome extension provides a convenient side panel for previewing and managing ad sources. It allows users to quickly load and preview ads via URL or file upload.

## Features

- Side panel integration with Chrome
- Two input methods for ad sources:
  - URL input
  - File upload
- Real-time ad preview

## Demos

- View videos here: https://go-sokal.notion.site/Ad-Previewer-Chrome-Extension-1d8a519dc946801ebcebeeb70bcfe64c?pvs=4

## Installation

1. Clone the repository
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable "Developer mode"
4. Click "Load unpacked" and select the project directory

- A detailed install with screenshots is available here: https://go-sokal.notion.site/Quick-Install-1d8a519dc94680c8b762e5fecfbedb17?pvs=4

## Usage

1. Open the side panel from Chrome's toolbar
2. Choose between "URL" or "Upload" tabs
3. Paste a URL or upload an image file
4. Click "Replace Ads"

## Development

### Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Chrome Extension API

### Design

- Tabs: https://www.w3schools.com/howto/howto_js_tabs.asp
- Buttons: https://copy-paste-css.com/
- Gradients: https://cssgradient.io/
- Icons: https://icons.relume.io/

### Project Structure

- `sidepanel.html`: Main side panel interface
- `sidepanel.js`: Connects events triggered by the side panel to modules that update the content of the webpage
- `service-worker.js`: Establishes a chrome context menu (opened via right-clicking on webpage content)
