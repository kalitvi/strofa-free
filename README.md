<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/strofa-logo.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/strofa-logo.svg">
    <img alt="Strofa - Free Apigee Emulator IDE" src="assets/strofa-logo.svg" width="400">
  </picture>
</p>

<p align="center">
  <strong>The visual desktop IDE for local Apigee API proxy development and testing</strong>
</p>

<p align="center">
  <a href="#installation">Installation</a> &bull;
  <a href="#features">Features</a> &bull;
  <a href="#prerequisites">Prerequisites</a> &bull;
  <a href="#free-vs-pro">Free vs Pro</a> &bull;
  <a href="#contributing">Contributing</a> &bull;
  <a href="https://strofa.io">Website</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-macOS%20%7C%20Windows%20%7C%20Linux-blue" alt="Platform">
  <img src="https://img.shields.io/badge/license-Proprietary-red" alt="License">
  <img src="https://img.shields.io/badge/version-1.0.0-green" alt="Version">
  <img src="https://img.shields.io/badge/Electron-34-47848F?logo=electron" alt="Electron">
  <img src="https://img.shields.io/badge/React-19-61DAFB?logo=react" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript" alt="TypeScript">
</p>

---

## What is Strofa Free Edition?

Strofa Free Edition is a **fully offline desktop IDE** for building, testing, and debugging Apigee API proxies locally using the official [Apigee Emulator](https://cloud.google.com/apigee/docs/emulator). No cloud account required.

Built with love for the Apigee community by [KALITVI Software](https://kalitvi.com).

> **Note:** Strofa is an independent third-party product. It is NOT affiliated with, endorsed by, or officially connected with Google LLC, Google Cloud, or the Apigee team.

---

## Features

- **Visual Proxy Canvas** - Drag-and-drop editor with 45+ Apigee policy types. No XML editing required.
- **Docker-based Emulator** - Full container lifecycle management for the Apigee Emulator.
- **Local Deploy & Test** - Deploy proxy bundles to the emulator and test them instantly.
- **API Playground** - Built-in HTTP client for testing deployed proxies with custom headers, auth, and body.
- **Test Resources** - Manage Products, Developers, Apps, and KVMs for the emulator.
- **Developer Toolbox** - JWT Decoder, HMAC Generator, Hash Calculator, Base64, URL Encoder, Regex Tester, JSON/XML Formatter, UUID Generator, and more.
- **Proxy Templates** - Pre-built templates including Reverse Proxy, Mock API, Rate Limiting, and AI Gateway.
- **Import / Export** - Import and export proxy bundles as standard ZIP files.
- **Dark / Light Theme** - Full theme support with system preference detection.
- **Keyboard Shortcuts** - Extensive shortcut support with cross-platform keys.

---

## Prerequisites

| Requirement | Version | Notes |
|---|---|---|
| **Docker Desktop** | 4.0+ | Required for running the Apigee Emulator |
| **Operating System** | macOS 12+, Windows 10+, Ubuntu 20.04+ | 64-bit only |
| **Disk Space** | ~2 GB | For the app + emulator Docker image |
| **RAM** | 4 GB minimum | 8 GB recommended for smooth emulator performance |

> Docker Desktop must be **installed and running** before launching Strofa.
> Download Docker Desktop: [https://www.docker.com/products/docker-desktop](https://www.docker.com/products/docker-desktop)

---

## Installation

Download the installer for your platform from the [Releases](../../releases) page.

> **Important:** Strofa Free Edition is not code-signed. Your operating system may show a security warning on first launch — this is normal and expected for unsigned applications. Follow the platform-specific steps below to proceed.

### macOS

| File | Architecture |
|---|---|
| `Strofa-Free-x.x.x-arm64.dmg` | Apple Silicon (M1/M2/M3/M4) |
| `Strofa-Free-x.x.x-x64.dmg` | Intel |

1. Open the `.dmg` file and drag **Strofa** to your **Applications** folder.
2. On first launch, if macOS blocks the app:
   - Go to **System Settings > Privacy & Security**
   - Click **"Open Anyway"** next to the Strofa message
3. Launch Strofa from Applications.

### Windows

| File | Architecture |
|---|---|
| `Strofa-Free-x.x.x-Setup.exe` | x64 |

1. Run the installer and follow the setup wizard.
2. If Windows SmartScreen shows a warning:
   - Click **"More info"**
   - Click **"Run anyway"**
3. Launch Strofa from the Start Menu or Desktop shortcut.

### Linux

| File | Format |
|---|---|
| `Strofa-Free-x.x.x.AppImage` | All distros |

```bash
chmod +x Strofa-Free-x.x.x.AppImage
./Strofa-Free-x.x.x.AppImage
```

---

## Quick Start

1. **Install Docker Desktop** and make sure it's running.
2. **Launch Strofa** - the welcome wizard will guide you through setup.
3. **Create an Emulator Container** - click "New Container" on the Containers tab, pick a version, and click Create.
4. **Start the Container** - click the play button to start it.
5. **Create a Proxy** - go to the Canvas tab, use "New Proxy" or import a ZIP bundle.
6. **Deploy to Emulator** - click the deploy button to push your proxy to the running emulator.
7. **Test with Playground** - switch to the Playground tab and send requests to your deployed proxy.

---

## Free vs Pro

| Feature | Free Edition | Strofa Pro |
|---|:---:|:---:|
| Visual Proxy Canvas | Yes | Yes |
| 45+ Policy Types | Yes | Yes |
| Local Emulator (Docker) | Yes | Yes |
| API Playground | Yes | Yes |
| Developer Toolbox | Yes | Yes |
| Test Resources (Products, Devs, Apps, KVMs) | Yes | Yes |
| Proxy Templates | Yes | Yes |
| Import / Export ZIP | Yes | Yes |
| Dark / Light Theme | Yes | Yes |
| Keyboard Shortcuts | Yes | Yes |
| **Strofai AI Assistant** | - | Yes |
| **Cloud Apigee Connection** | - | Yes |
| **Deploy to Cloud Environments** | - | Yes |
| **Real-time Debug Sessions** | - | Yes |
| **DevOps Pipeline** | - | Yes |
| **Hybrid Manager** | - | Yes |
| **Cassandra Doctor** | - | Yes |
| **Git Integration** | - | Yes |
| **Analytics Dashboard** | - | Yes |
| **Shared Flows** | - | Yes |
| **Stub IDP (OAuth/OIDC)** | - | Yes |
| **Multi-Organization Support** | - | Yes |
| **Extensions System** | - | Yes |

> Interested in the full version? Visit [strofa.io](https://strofa.io) or contact us at [support@kalitvi.com](mailto:support@kalitvi.com).

---

## Reporting Bugs & Requesting Features

We use GitHub Issues for tracking bugs and feature requests.

### Bug Report

1. Go to the [Issues](../../issues) tab.
2. Click **"New Issue"**.
3. Select the **"Bug Report"** template.
4. Include:
   - Steps to reproduce
   - Expected vs actual behavior
   - OS and Docker version
   - Screenshots if applicable

### Feature Request

1. Go to the [Issues](../../issues) tab.
2. Click **"New Issue"**.
3. Select the **"Feature Request"** template.
4. Describe the feature and your use case.

### Before Reporting

- Search existing issues to avoid duplicates.
- Check that you're running the latest version.
- Verify Docker Desktop is running and responsive.

---

## License

Strofa Free Edition is proprietary software.
Copyright (c) 2023-2026 KALITVI Consulting and Development LTD. All Rights Reserved.

See [LICENSE.txt](LICENSE.txt) for the full license agreement.

**Summary:**
- Free to download and use for **personal, non-commercial purposes only**.
- You may NOT modify, redistribute, reverse engineer, or create derivative works.
- You may NOT use any component of this software in other products.
- You may NOT use this software for commercial purposes.
- Provided "as is" without warranty.

---

## Contact

| | |
|---|---|
| **Company** | KALITVI Consulting and Development LTD |
| **Product Website** | [strofa.io](https://strofa.io) |
| **Company Website** | [kalitvi.com](https://kalitvi.com) |
| **Email** | [support@kalitvi.com](mailto:support@kalitvi.com) |
| **Bug Reports** | [GitHub Issues](../../issues) |

---

<p align="center">
  <sub>Made with care for the API developer community.</sub>
</p>
