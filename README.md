# 🍊 Citrus

### A fast, simple, open-source file converter for Linux.

**Convert files. Keep control. Stay local.**

Citrus is an open-source desktop application designed to make file conversion effortless. Built with Linux in mind, Citrus aims to bring documents, images, audio, video, and other file formats together in one clean, intuitive interface.

No juggling multiple applications. No complicated commands. Just select a file, choose a format, and convert.

> 🚧 **Status: Early development**
>
> Citrus is currently in the planning and development stage. Features listed below represent the project roadmap and may not be available yet.

---

## ✨ Vision

File conversion on Linux shouldn't require remembering commands, installing multiple graphical applications, or navigating complicated workflows.

Citrus aims to provide a unified conversion experience with:

- 🖱️ **Simple workflow:** Drag and drop files to get started.
- 🔄 **Multiple formats:** Convert documents, images, audio, video, and more.
- 📦 **Batch conversion:** Process multiple files in one workflow.
- ⚡ **Fast processing:** Use established conversion tools and libraries.
- 🔒 **Privacy first:** Prioritize local file processing without mandatory cloud uploads.
- 🎨 **Clean interface:** A modern desktop experience designed for simplicity.
- 🐧 **Linux first:** Build a reliable Linux application before expanding to other platforms.
- 🌍 **Open source:** Welcome community contributions, improvements, and new ideas.

## 🛠️ Technology Stack

Citrus is planned around the following technologies:

| Technology | Purpose |
|---|---|
| Python | Core application logic |
| PySide6 / Qt | Desktop graphical interface |
| FFmpeg | Audio and video conversion |
| LibreOffice | Office document conversion |
| Pandoc | Document format conversion |
| Pillow / ImageMagick | Image processing |
| Poppler / pypdf | PDF utilities |
| Git and GitHub | Version control and collaboration |
| pytest | Automated testing |

The exact dependencies may evolve as development progresses.

## 📂 Planned Format Support

### Documents
- PDF
- DOCX
- ODT
- TXT
- RTF
- HTML
- EPUB

### Images
- PNG
- JPG / JPEG
- WebP
- AVIF
- TIFF
- BMP
- SVG

### Audio
- MP3
- WAV
- FLAC
- OGG
- AAC

### Video
- MP4
- MKV
- WebM
- MOV
- AVI

### Archives
- ZIP
- TAR
- GZ
- 7Z

*Format support depends on the conversion route, installed backends, codecs, and licensing requirements. Not every format can be converted directly into every other format.*

## 🚀 Roadmap

- [ ] Establish the project architecture.
- [ ] Build the initial desktop interface.
- [ ] Implement file detection and format selection.
- [ ] Add drag-and-drop support.
- [ ] Implement initial image conversion routes.
- [ ] Add document conversion using LibreOffice.
- [ ] Integrate audio and video conversion.
- [ ] Add batch processing and progress tracking.
- [ ] Implement cancellation and error recovery.
- [ ] Add conversion presets and keyboard shortcuts.
- [ ] Explore contextual and radial format-selection menus.
- [ ] Add Linux packaging and installation options.
- [ ] Expand compatibility and automated test coverage.
- [ ] Explore Windows and macOS support.

## 💻 Development Setup

### Prerequisites

- Linux operating system.
- Python 3 and `venv`.
- Git.
- PySide6 and the conversion tools required for your chosen features.

### Clone the repository

```bash
git clone https://github.com/syuverse/citrus.git
cd citrus
```

### Create a virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### Install development dependencies

Once the project's dependency configuration is available:

```bash
pip install -e ".[dev]"
```

### Run Citrus

The launch command will be documented once the initial application entry point is implemented.

> **Note:** These are intended development instructions. Installation and launch commands may change while the project is being built.

## 🤝 Contributing

Citrus is being developed as an open-source project, and contributions will be welcome.

Potential contribution areas include:

- Conversion backends and new format support.
- User interface and accessibility.
- Linux desktop integration.
- Performance improvements.
- Automated testing and bug fixes.
- Documentation and translations.

Before contributing:

1. Check the existing issues and roadmap.
2. Discuss substantial changes before implementing them.
3. Create a feature branch.
4. Include relevant tests with your changes.
5. Submit a pull request with a clear description.

Contribution guidelines and the code of conduct will be added as the project takes shape.

## 🔐 Privacy and Security

Citrus aims to prioritize user privacy.

- Local processing wherever supported.
- No mandatory account for core functionality.
- No forced cloud uploads for local conversions.
- Safe handling of file paths and temporary files.
- Clear error reporting without unnecessarily exposing file contents.

Privacy and security claims will be finalized and verified as the implementation develops.

## 📜 License

The project's open-source license will be specified here once selected.

Third-party dependencies and bundled tools will retain their respective licenses.

## 🏢 About

**Citrus is an open-source project under SYUVERSE.**

We aim to make everyday file operations simpler, more accessible, and more enjoyable through thoughtful software design.

- Organization: [SYUVERSE](https://github.com/syuverse)
- Repository: [Citrus](https://github.com/syuverse/citrus)
- Issues and feature requests: [GitHub Issues](https://github.com/syuverse/citrus/issues)

## 🍊 Citrus

**Drop a file. Choose a format. Get it done.**

*Built for Linux. Open to everyone.*
