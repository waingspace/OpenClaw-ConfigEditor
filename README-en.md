# OpenClaw JSON Config Editor

OpenClaw JSON Config Editor is a single-file HTML application for visual editing of JSON configuration files. This tool converts complex JSON structures into intuitive form interfaces, allowing users to easily edit configurations without manually writing JSON.

## Features

- **Three-step workflow**: Import → Edit → Export, with a progress indicator at the top
- **Smart form recognition**: Boolean values → capsule toggles, enum strings → dropdowns, simple arrays → checkboxes (dynamically add/remove), nested objects → collapsible cards
- **Three output modes**: Formatted / Minified / Syntax highlighted (keyword coloring)
- **One-click copy & download**: Copy JSON to clipboard or download as .json file with one click
- **Dark theme**: Beautiful dark interface using Syne + DM Mono fonts, requires internet to load Google Fonts (still functional offline with fallback fonts)

## Usage

1. **Import**: Paste your JSON configuration into the input area and click "Parse and Generate Form"
2. **Edit**: Edit various configurations through the visual form
3. **Export**: View the generated JSON, select output format, copy or download

## Technical Features

- Single-file HTML, just double-click to open in browser, no dependencies or server required
- Support for nested objects and array visualization
- Smart recognition of common configuration item types (booleans, enums, etc.)
- Real-time statistics of field counts and type distribution
- Syntax highlighting for better readability

## Supported Data Types

- **String**: Regular text input
- **Number**: Numeric input field
- **Boolean**: True/False radio buttons
- **Enum**: Dropdown selection (with custom options support)
- **Array**: Checkbox groups (simple values) or text areas (complex values)
- **Object**: Collapsible nested forms

## System Requirements

- Modern browser (Chrome, Firefox, Edge, Safari)
- No special hardware requirements
- No network connection required (except for initial Google Fonts loading)

## Privacy Notice

All data processing occurs locally in your browser, no data is uploaded to any server.