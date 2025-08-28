# Building Blocks for Agentic Platform Engineering 🦀

> Experimenting with Rust tools as foundations for autonomous platform systems

[![Rust](https://img.shields.io/badge/rust-1.70+-orange.svg)](https://www.rust-lang.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Experimental](https://img.shields.io/badge/Status-Experimental-yellow.svg)](#status)

## 🧪 What This Is

This repository explores how existing Rust platform tools could evolve into components for agentic systems. It's a collection of experiments, proof-of-concepts, and integration patterns - not a production platform.

## 🧰 Available Tools

### 🔐 Security Tools
- **[secretscan](https://github.com/marcuspat/secret-scan)** - Blazing fast secret scanner with 99% detection accuracy ([crates.io](https://crates.io/crates/secretscan))
- **[file-hasher](https://github.com/marcuspat/file-hasher)** - File integrity verification ([crates.io](https://crates.io/crates/file-hasher))
- **[cargocrypt](https://github.com/marcuspat/cargocrypt)** - Secure cryptographic utilities ([crates.io](https://crates.io/crates/cargocrypt))

### 🌐 Network Tools
- **[k8s-netinspect](https://github.com/marcuspat/k8s-netinspect)** - Kubernetes network inspection ([crates.io](https://crates.io/crates/k8s-netinspect))
- **[netrain](https://github.com/marcuspat/netrain)** - Matrix-style network packet monitor with real-time threat detection ([crates.io](https://crates.io/crates/netrain))

### 🛠️ Development Tools  
- **[cargo-forge](https://github.com/marcuspat/cargo-forge)** - Interactive Rust project generator with 7 specialized project types ([crates.io](https://crates.io/crates/cargo-forge))
- **[json-prettify](https://github.com/marcuspat/json-prettify)** - JSON formatting utility ([crates.io](https://crates.io/crates/json-prettify))

## 🔬 Experimental Integrations

These examples show how traditional CLI tools could be wrapped with agentic behavior:

## 🚀 Quick Start

### Prerequisites
```bash
# Install Rust (if not already installed)
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

# Install our tools
cargo install secretscan
cargo install k8s-netinspect
cargo install cargo-forge
cargo install file-hasher
cargo install netrain
cargo install cargocrypt
