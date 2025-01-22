<p align="center"><img src="src/i/icon128.png"></p>


# SnapSearch Chrome Extension

SnapSearch is a Chrome extension that enhances your web browsing experience by enabling users to perform an inverse image search. It's designed to save time and improve efficiency by providing instant image search results without the need to manually copy and paste image links.

## Features

- **Inverse Image Search**: Right-click on any image in a webpage to perform an inverse image search.
- **Customizable Options**: Configure search engines and shortcuts to suit your preferences.
- **Context Menu Configuration**: Choose between a single button for the default search engine or a cascaded menu with all included search engines.
- **Add Custom Search Engines**: Users can add their own search engines (see below).
- **Lightweight and Fast**: Minimal impact on browser performance.
- **User-Friendly Interface**: Intuitive and easy to use.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Kathan2608/SnapSearch.git
   ```
2. Open Google Chrome and navigate to `chrome://extensions/`.
3. Enable "Developer Mode" (top-right corner).
4. Click "Load unpacked" and select the cloned project folder.
5. The SnapSearch extension will be added to your browser.

## How to Use

### Inverse Image Search
1. Right-click on any image in a webpage.
2. Select **"Search Image with SnapSearch"** from the context menu.
3. A new tab will open with the image search results in your configured search engine.

## Configuration

1. Go to the SnapSearch options page:
   - Right-click on the extension icon in the toolbar.
   - Select **"Options"**.
2. Configure the following settings:
   - **Default Search Engine**: Choose your preferred search engine (e.g., Google, Bing, DuckDuckGo).
   - **Shortcut Keys**: Set up custom keyboard shortcuts for quicker access.
   - **Context Menu Options**: Choose between a single button or a cascaded menu for search engines.
   - **Custom Search Engines**: Add your own search engines by specifying the name and URL template.

## Development

If you want to contribute or modify the extension:

1. Ensure you have [Node.js](https://nodejs.org/) installed.
2. Navigate to the project directory:
   ```bash
   cd SnapSearch
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Make your changes and reload the extension in Chrome.

## Folder Structure

```
SnapSearch/
|-- src/
|   |-- options.html    # Options page for customization
|   |-- popup.html      # Popup interface for the extension
|   |-- styles/         # CSS files for styling
|   |-- scripts/        # JavaScript files for functionality
|-- manifest.json       # Chrome extension manifest file
|-- README.md           # Project documentation (this file)
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature name"
   ```
4. Push your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.



## Contact

For any questions or feedback, feel free to reach out:

- **GitHub**: [Kathan Shah](https://github.com/Kathan2608)

