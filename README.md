# Offline QR Code Generator

A standalone, offline QR code generator with two modes:

- **QR code from link** — generate a QR code from any link or text.
- **QR code from TOTP** — generate an `otpauth://totp/...` QR code and display the current TOTP code with its countdown timer.

## Usage

Open `index.html` directly in a Chromium-based browser or Firefox. No installation, build step, server, or internet connection is required.

All processing happens locally in the browser. TOTP secrets are not saved to persistent storage or sent over the network.

## License

MIT — see [LICENSE](LICENSE).
