# Simple Images Viewer

A tool to easily display a list of image URLs and local file paths from a text file in your browser.

## Features

- **Supports Multiple Sources**: Display both web image URLs and local image file paths.
- **Flexible Layout**: Freely adjust the number of grid columns with a slider.
- **Powerful Filtering**: Filter the display by conditions like "URL/File" or "Square Only".
- **Great Usability**: Supports dark mode and an image modal for enlarged views.
- **Standalone**: Works with a single `index.html` file. No server required.

## Usage

1. Open `index.html` directly in your browser (by double-clicking the file or dragging and dropping it into the browser window).
   - **Important**: To display local image files, the browser's address bar must start with `file:///...`. Local files cannot be displayed when served via a web server (`http://...`) due to browser security restrictions.
2. Load a text file (`.txt`, `.csv`, etc.) containing image paths (one per line) using the file selection button.
3. Use the controls at the top of the screen to customize the view.

## Supported Formats

Describe the image paths in the text file in the following formats. The tool will automatically extract URLs or paths even if they are mixed with other data.

```
https://example.com/image1.jpg
/Users/user/Pictures/photo.jpg
data,123,/Users/user/image.jpg,"description"
```
