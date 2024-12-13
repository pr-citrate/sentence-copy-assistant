# Sentence Copy Assistant

This project provides a single HTML file that allows users to input multiple lines of text, then easily copy each line (sentence) and navigate between lines. It embeds favicon, includes automatic scrolling, and uses a light-green-themed design, all without external CSS or JavaScript files.

## Key Features

- **Multi-line Input**: Enter multiple lines of text in the `textarea`.
- **Line-based Management**: Each line is treated as a separate sentence, trimmed of leading and trailing spaces.
- **Copy Function**: Copy the currently selected line to the clipboard with a single click.
- **Auto Navigation**: Automatically move to the next line after copying.
- **Previous/Next Line**: Easily move to previous or next lines using dedicated buttons.
- **Auto Scrolling**: The display scrolls automatically to the selected line, allowing you to track your position.
- **Improved UI/UX**: Utilizes a light-green color scheme, styled WebKit scrollbar, and responsive buttons for a cleaner and more intuitive interface.
- **Embedded Favicon**: The favicon is embedded directly in the HTML as a Base64-encoded image.

## How to Use

1. Open the single HTML file in your web browser.
2. Enter the text you want to copy in multiple lines within the `textarea`.
3. Each line will appear in the scrollable area below, with the currently selected line highlighted.
4. Use the "Copy" button to copy the selected line to your clipboard.
5. Navigate through lines using the "Previous" and "Next" buttons as needed.
6. Everything works directly in your browser without requiring a server.

## Browser Compatibility

Works with most modern browsers (Chrome, Firefox, Edge, Safari). Clipboard access typically requires HTTPS or local execution.

## License

This project is distributed under the MIT License. See [LICENSE](LICENSE) for details.
