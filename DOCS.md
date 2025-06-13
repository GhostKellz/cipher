# Cipher Documentation

Welcome to the Cypher authoritative DNS server documentation.

## Overview
Cipher is a next-generation, high-performance authoritative DNS server written in Rust. It is designed for both home labs and professional DNS hosting, providing a modern web GUI, database-backed zone management, and robust API support.

## Key Features
- Multithreaded, high-performance DNS server
- Database backend for zone and record management
- WASM-powered web GUI for easy administration
- Secure, memory-safe, and reliable
- API for automation and integration

## Getting Started
- See the main [README.md](README.md) for installation and quick start instructions.
- Example configuration files are available in the `config/` directory.

## Configuration
Cipher uses TOML files for configuration. You can define database settings, DNS zones, and other options in your config file.

## Web GUI
The web GUI is powered by WebAssembly and allows you to manage zones, records, and server settings from your browser.

## API
Cipher exposes a REST API for automation and integration with other tools. See the API reference (coming soon) for details.

## Roadmap
- Database backend support (Postgres, SQLite)
- Web GUI (WASM)
- REST API
- Dynamic zone updates
- DNSSEC support

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on contributing to Cypher.

---

For more information, visit the project repository or open an issue for help.