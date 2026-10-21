# Yealink Configuration File Generator

An open-source, interactive web utility for creating customized `.cfg` provision files for Yealink IP phones (T2X, T3X, T4X, and T5X series). Built with standard static web technologies and Tailwind CSS for speed, scannability, and ease of deployment.

![Yealink Config Generator](https://img.shields.io/badge/Yealink-Provisioning-blue.svg)
![License](https://img.shields.io/badge/License-Non--Commercial-orange.svg)

---

## Features

- **Multi-Model & Firmware Compatibility**: Supports modern syntax (`#!version:1.0.0.1` for V85+ / V8X), legacy V80 syntax, and standard V7X headers across popular Yealink hardware.
- **Interactive Security & Lock Controls**: Configure physical key lockouts, PIN codes, menu locks, and hardware reset disable flags (`OK` key long-press & factory password blocks).
- **SIP Account Provisioning**: Standard SIP server, port, credentials, display names, and preferred audio codec arrays.
- **Custom Parameters**: Dynamically add key-value pairs for any unlisted Yealink provisioning directives.
- **Live Preview & Syntax Highlighting**: Instant syntax update with inline comments explaining parameter behavior.
- **JSON Profile Templates**: Save your custom baseline configurations (e.g., *Hardened Call Center*, *Executive Desk*) as JSON files and restore them anytime with single-click importing.
- **One-Click Export**: Download compiled `.cfg` files directly to load into your provisioning server (TFTP/FTP/HTTP/HTTPS) or Yealink Auto-P module.

---

## Quick Start (Local)

Because this tool is built as a single static HTML application, no build steps, Node.js dependencies, or server setup are required.

## License

Distributed under a **Custom Non-Commercial License**. 

This project is free for personal, internal, and educational use. Commercial resale, monetization, or bundling into paid products without explicit permission is strictly prohibited. 
See the [`LICENSE`](LICENSE) file for full details and liability disclaimers.
