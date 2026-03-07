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

Strofa Free Edition is a **free, fully offline showcase** of the Strofa platform — focused on **local Apigee API proxy development** using the official [Apigee Emulator](https://docs.cloud.google.com/apigee/docs/api-platform/local-development/overview). It includes the **complete Visual Proxy Canvas** with all 47 policy types, a local Docker-based emulator, and a developer toolbox. No cloud account required.

This is a taste of what Strofa can do. For the full platform — including AI assistance, cloud deployment, real-time debugging, Hybrid Manager, DevOps automation, and much more — see [Strofa Pro](https://strofa.io).

Built with love for the Apigee community by [KALITVI Software](https://kalitvi.com).

> **Note:** Strofa is an independent third-party product. It is NOT affiliated with, endorsed by, or officially connected with Google LLC, Google Cloud, or the Apigee team.

---

## Features

- **Visual Proxy Canvas** — Full drag-and-drop proxy editor with all 47 Apigee policy types, visual condition builder, script editor with Apigee auto-complete, fault rules, and resource management. No XML editing required.
- **Docker-based Emulator** — Complete container lifecycle management for the Apigee Emulator.
- **Local Deploy & Test** — Deploy proxy bundles to the emulator and test them instantly.
- **API Playground** — Built-in HTTP client for testing deployed proxies with custom headers, auth, and body.
- **Test Resources** — Manage Products, Developers, Apps, and KVMs for the emulator.
- **Developer Toolbox** — 16 standalone tools: JWT Decoder, HMAC Generator, Hash Calculator, Base64, URL Encoder, Regex Tester, JSON/XML Formatter, UUID Generator, HTTP Signature, Case Converter, Color Converter, Query String Parser, Text Diff, Timestamp Converter, and more.
- **Import / Export** — Import and export proxy bundles as standard Apigee ZIP files.
- **Dark / Light Theme** — Full theme support with system preference detection.
- **Keyboard Shortcuts** — Extensive shortcut support with cross-platform keys.

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

| File | Type |
|---|---|
| `Strofa-Free-x.x.x-x64-Setup.exe` | Installer (recommended) |
| `Strofa-Free-x.x.x-x64-Portable.exe` | Portable (no install needed) |

**Installer:** Run the setup wizard, then launch from the Start Menu or Desktop shortcut.
**Portable:** Just download and run — no installation required.

If Windows SmartScreen shows a warning:
- Click **"More info"**
- Click **"Run anyway"**

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

The Free Edition is a **local emulator showcase** with the full canvas. Strofa Pro is the **complete Apigee platform** with 180+ features.

### Local Development

| Feature | Free | Pro |
|---|:---:|:---:|
| Visual Proxy Canvas (all 47 policies) | Yes | Yes |
| Visual Condition Builder | Yes | Yes |
| Script Editor with Apigee Auto-complete | Yes | Yes |
| Fault Rules & Resource Management | Yes | Yes |
| Local Emulator (Docker) | Yes | Yes |
| Local Deploy & Test | Yes | Yes |
| API Playground (local) | Yes | Yes |
| Test Resources (Products, Devs, Apps, KVMs) | Yes | Yes |
| Import / Export ZIP Bundles | Yes | Yes |
| Developer Toolbox (16 tools) | Yes | Yes |
| Dark / Light Theme | Yes | Yes |
| Keyboard Shortcuts | Yes | Yes |

### AI Assistant

| Feature | Free | Pro |
|---|:---:|:---:|
| **Strofai AI Assistant** (126 tools, 27 categories) | - | Yes |
| Dual AI Provider (Gemini 3 + Claude Opus 4.6) | - | Yes |
| AI-Powered Proxy Building & Editing | - | Yes |
| 180+ Industry Use-Case Blueprints (Healthcare, Finance, etc.) | - | Yes |
| RAG Knowledge System (7 collections) | - | Yes |
| Task Decomposition & Planning Mode | - | Yes |
| AI-Assisted Debug Chat | - | Yes |
| Voice Input / Output (TTS/STT) | - | Yes |

### Cloud & Deployment

| Feature | Free | Pro |
|---|:---:|:---:|
| Cloud Apigee X Connection | - | Yes |
| Deploy to Cloud Environments | - | Yes |
| API Proxies CRUD (Cloud) | - | Yes |
| Shared Flows Management | - | Yes |
| Revision Comparison & Diff | - | Yes |
| Multi-Organization Support | - | Yes |
| Real-time Debug Sessions | - | Yes |
| Analytics Dashboard | - | Yes |
| Products, Developers & Apps Management (Cloud) | - | Yes |
| Environment Management | - | Yes |
| Key Value Maps (Cloud) | - | Yes |

### DevOps & Infrastructure

| Feature | Free | Pro |
|---|:---:|:---:|
| DevOps Promotion Pipeline (4-step wizard) | - | Yes |
| Hybrid Manager (full K8s console) | - | Yes |
| 10-Step Hybrid Installation Wizard | - | Yes |
| Cluster Dashboard & Network Topology | - | Yes |
| Cassandra Doctor (CQL console, health, schema) | - | Yes |
| Capacity Analysis & Troubleshooting Playbooks | - | Yes |
| Certificate & Helm Chart Management | - | Yes |
| Disaster Recovery | - | Yes |
| Pre-flight Checks & Diagnostics | - | Yes |

### Additional Pro Features

| Feature | Free | Pro |
|---|:---:|:---:|
| Proxy Templates (Reverse Proxy, Mock API, AI Gateway, etc.) | - | Yes |
| Sandbox Mock Servers (OpenAPI import, request logging) | - | Yes |
| Stub IDP (OAuth2/OIDC Identity Provider) | - | Yes |
| Git Integration (GitHub push/pull, backup) | - | Yes |
| Extensions System (.kpkg packages) | - | Yes |
| API Playground with Collections & Variables | - | Yes |
| Inspector (bundle inspection) | - | Yes |
| Apigee License Management | - | Yes |
| Command Center Dashboard | - | Yes |

> Interested in the full platform? Visit [strofa.io](https://strofa.io) or contact us at [info@kalitvi.com](mailto:info@kalitvi.com).

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
| **Email** | [info@kalitvi.com](mailto:info@kalitvi.com) |
| **Bug Reports** | [GitHub Issues](../../issues) |

---

<p align="center">
  <sub>Made with care for the API developer community.</sub>
</p>
