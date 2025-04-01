# Electron File Explorer

A full-featured desktop file explorer application built with Electron, React, and Node.js.

## Features

- Directory Tree View with recursive folder listing
- File Preview Panel with support for text, code, images, and PDFs
- Advanced Search Capability
- File Editing with syntax highlighting
- Drag & Drop Support
- File Operations (rename, delete, create)
- Dark Mode Toggle
- Cross-platform Support (macOS, Windows, Linux)

## Tech Stack

- Electron for desktop application
- React with Chakra UI for frontend
- Node.js + Express for backend
- Native fs and path modules for file operations

## Development Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## Building for Production

To create a production build:

```bash
npm run build
```

This will create platform-specific installers in the `dist` folder.

## Project Structure

```
/client         # React frontend application
/server         # Express backend for filesystem operations
/electron       # Electron main process and preload scripts
/assets         # Static assets
```

## Environment Variables

Create a `.env` file in the root directory with the following variables:

```
DEFAULT_ROOT_FOLDER=/path/to/default/folder
```

## License

ISC 
