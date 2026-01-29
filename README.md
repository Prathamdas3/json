# JSON Viewer

A lightweight, real-time JSON validator and formatter with beautiful syntax highlighting and error detection.

## Features

- ✅ Real-time JSON validation (validates as you type)
- 🎨 Formatted JSON output with line numbers
- 🚨 Error highlighting with exact line & column detection
- 📋 One-click copy to clipboard
- 📱 Responsive design (works on desktop and mobile)
- ⚡ Zero dependencies - runs directly in the browser
- 🔒 Secure - no server required, all processing happens locally

## Screenshots

### Main Interface

```
[Add screenshot of the main interface with the two-pane layout showing input and output panels]
```

### Valid JSON Example

```
[Add screenshot showing valid JSON with formatted output and line numbers]
```

### Error Detection

```
[Add screenshot showing error message with line and column highlighting]
```

## Installation

No installation required! Simply:

1. Clone the repository:
   ```bash
   git clone https://github.com/Prathamdas3/json.git
   ```

2. Open `index.html` in your browser

That's it! The app works entirely in the browser with no build process.

## Deployment

This project can be easily deployed to GitHub Pages or any static hosting service.

### GitHub Pages

Simply push to your GitHub repository and enable GitHub Pages in your repository settings.

## Usage

### Example 1: Simple JSON Object
```json
{
  "name": "John Doe",
  "age": 30,
  "email": "john@example.com"
}
```

### Example 2: Nested Arrays and Objects
```json
{
  "users": [
    {
      "id": 1,
      "name": "Alice",
      "roles": ["admin", "user"],
      "address": {
        "street": "123 Main St",
        "city": "New York",
        "zip": "10001"
      }
    }
  ],
  "totalCount": 1
}
```

### Example 3: Common Errors
```json
{
  "name": "Test"
  "age": 25  // Missing comma above!
}
```

The app will highlight the error and show the exact line and column number.

## Tech Stack

- **HTML5** - Semantic markup
- **Tailwind CSS v4** - Utility-first CSS framework (via CDN)
- **Alpine.js v3** - Lightweight reactive framework (via CDN)
- **Vanilla JavaScript** - No build tools required

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

---

Made with ❤️ by [Pratham Das](https://github.com/Prathamdas3)
