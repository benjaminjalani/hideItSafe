# hideItSafe

A lightweight, zero-server cryptographic application suite designed to protect personal text data and images using custom localized data processing arrays. All files are handled strictly within browser memory via the HTML5 `FileReader` and `Blob` structures, ensuring zero data leakage to external networks.

## 🌟 Key Features

* **Complete Privacy Assurance:** 100% serverless data pipeline. No backend processing, tracking, or cookie-based analytics.
* **Text Cryptography Layer:** Converts raw characters using high-speed multi-byte array transformations into clean `.bin` payload packages.
* **Image Compilation Workspace:** Ingests images (`.jpg`, `.png`, `.jpeg`), converts standard assets into raw operational binary maps, and packs them into compressed storage blocks.
* **Streamlined Decryption Engine:** Auto-detects custom file signatures (`TXT:` and `IMG:` blocks) to instantly restore payloads back to their original states.

## 📂 System File Architecture

```text
hideitsafe/
├── index.html           # Main dashboard interface and navigation hub
├── encrypt-text.html    # Client-side raw text compilation workspace
├── encrypt-image.html   # Local asset compilation module
└── decrypt.html         # Data block restoration engine
