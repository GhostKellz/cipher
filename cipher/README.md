# Cipher: Next-Gen Authoritative DNS Server

[![Build Status](https://img.shields.io/github/actions/workflow/status/your-org/cypher/ci.yml?branch=main)](https://github.com/your-org/cypher/actions)
[![Crates.io](https://img.shields.io/crates/v/cypher-dns.svg)](https://crates.io/crates/cypher-dns)
[![Docs](https://img.shields.io/badge/docs-online-blue.svg)](https://your-org.github.io/cypher)
[![Code Coverage](https://img.shields.io/codecov/c/github/your-org/cypher)](https://codecov.io/gh/your-org/cypher)

---

Cypher is a modern, high-performance authoritative DNS server designed to rival PowerDNS, Technitium, and Cloudflare. Built in Rust for safety, speed, and reliability, Cypher features a database backend, web GUI (WASM-powered), and is easy to deploy for both home labs and professional DNS hosting.

## Features
- Blazing fast, multithreaded DNS server
- Database-backed zone and record management
- Modern web GUI (WASM frontend)
- Easy configuration and packaging
- Secure, memory-safe, and reliable
- API for automation and integration

## Getting Started

1. **Install Rust:**
   ```sh
   curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
   ```
2. **Clone the repo:**
   ```sh
   git clone https://github.com/your-org/cypher.git
   cd cypher
   ```
3. **Build Cypher:**
   ```sh
   cargo build --release
   ```
4. **Run Cypher:**
   ```sh
   ./target/release/cypher
   ```

## Documentation
See [docs/](docs/) for more details and usage guides.

## Contributing
Pull requests and issues are welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## Roadmap
- [ ] Database backend support (Postgres, SQLite)
- [ ] Web GUI (WASM)
- [ ] REST API
- [ ] Dynamic zone updates
- [ ] DNSSEC support

---

© 2024 Cypher DNS Project

