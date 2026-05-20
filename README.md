# zero-trace

zero-trace is a client-side Progressive Web App (PWA) that provides browser-based AES-GCM encryption and decryption with an immersive cyberpunk-inspired interface.

The app is built using modern web standards, including a service worker for offline caching, a web manifest for installability, and a responsive design with animated visual effects. It encrypts and decrypts text entirely in the browser using the Web Crypto API, so no sensitive data is sent to a server.

## Features

- AES-GCM encryption and decryption in the browser
- Passphrase-derived key generation with PBKDF2 and SHA-256
- URL-safe Base64 output option for better compatibility with links and copy/paste workflows
- Offline-capable PWA using a service worker and cache-first asset strategy
- Responsive neon-style UI with matrix-style animated background and 3D hover interactions
- Privacy-first behavior: no data is stored on a server or persisted by default

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript
- Web Crypto API
- Service Worker caching
- Web App Manifest
- GitHub Pages deployment

## Deployment

The project is deployed on GitHub Pages at:

https://parthji32.github.io/zero-trace/

## How to run locally

1. Open `index.html` in a browser.
2. Click **Encrypt** to reveal the encryption panel.
3. Enter plaintext or ciphertext with a passphrase.
4. Click **Encrypt** or **Decrypt** and copy the result.

## Notes

The app is designed for browser-based security experiments and convenience. Always use strong passphrases and never rely on client-side encryption alone for highly sensitive production data.
