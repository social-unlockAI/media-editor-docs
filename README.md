# Media Editor SDK Documentation

Official documentation for the `@distralabs/media-editor` SDK.

## 📚 Documentation

Visit **[docs.distralabs.com](https://docs.distralabs.com)** for the complete documentation.

## 🚀 Quick Links

- [Installation Guide](https://docs.distralabs.com/installation)
- [Quickstart](https://docs.distralabs.com/quickstart)
- [ImageEditor Integration](https://docs.distralabs.com/integration-guides/nextjs-image-editor)
- [VideoEditor Integration](https://docs.distralabs.com/integration-guides/nextjs-video-editor)
- [API Reference](https://docs.distralabs.com/api-reference/introduction)
- [FAQ & Troubleshooting](https://docs.distralabs.com/troubleshooting/faq)

## 📦 What is Media Editor SDK?

The Media Editor SDK is a powerful React-based library providing image and video editing capabilities for modern web applications. Built with:

- React 18 & TypeScript
- Konva.js for canvas manipulation
- FFmpeg WASM for video processing
- License-protected commercial SDK

## ✨ Features

### ImageEditor
- Image upload, resize, crop, rotate
- Filters & effects (grayscale, blur, brightness, etc.)
- Text overlays with Google Fonts
- Shapes and custom graphics
- Layer management
- Template system
- Export to PNG/JPG/WebP

### VideoEditor
- Video upload and trimming
- Timeline editing with multi-track support
- Text and subtitle overlays
- Effects and filters
- Audio control
- FFmpeg-powered export to MP4

## 🛠️ Installation

```bash
npm install @distralabs/media-editor@1.1.9
npm install next@14.2.15 react@18.2.0 react-dom@18.2.0
```

## 📖 Documentation Structure

This repository contains Mintlify-powered documentation:

```
media-editor-docs/
├── introduction.mdx          # SDK overview
├── quickstart.mdx            # 5-minute quickstart
├── installation.mdx          # Detailed installation
├── integration-guides/       # Next.js integration guides
│   ├── nextjs-image-editor.mdx
│   └── nextjs-video-editor.mdx
├── api-reference/            # Complete API docs
│   ├── introduction.mdx
│   ├── image-editor.mdx
│   └── video-editor.mdx
├── troubleshooting/          # FAQ and troubleshooting
│   └── faq.mdx
└── mint.json                 # Mintlify configuration
```

## 🔒 Security & IP Protection

This documentation repository is **separate** from the SDK source code:

- **SDK Source Code:** Private repository (protected IP)
- **Documentation:** Public repository (customer-facing only)
- **NPM Package:** Only ships compiled `dist/` folder

Users never get access to SDK source code - only the public API documentation.

## 🤝 Contributing to Documentation

To contribute to the documentation:

1. Clone this repository
2. Install Mintlify CLI: `npm install -g mintlify`
3. Run local preview: `mintlify dev`
4. Make changes to `.mdx` files
5. Submit a pull request

## 💬 Support

- **Email:** support@distralabs.com
- **Documentation:** https://docs.distralabs.com
- **Account Manager:** Contact your dedicated account manager

## 📄 License

The `@distralabs/media-editor` SDK is commercial software. This documentation is provided for licensed users.

See the main SDK package for license terms (EULA.md).

---

© 2025 DistraLabs. All rights reserved.
