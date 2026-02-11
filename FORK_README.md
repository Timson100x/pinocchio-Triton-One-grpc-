# Pinocchio Fork - pinocchio-Triton-One-grpc-

This is a fork of the [Pinocchio](https://github.com/anza-xyz/pinocchio) library by Timson100x.

## About Pinocchio

Pinocchio is a *no external dependencies* library to create Solana programs in Rust. This library optimizes both compute units consumption and binary size.

## Repository Setup

This repository has been successfully cloned and verified. All components are working correctly:

- ✅ Rust toolchain (1.84.1) installed
- ✅ Node.js and pnpm package manager installed
- ✅ All dependencies installed
- ✅ Project builds successfully
- ✅ All tests pass
- ✅ Linting and formatting tools configured

## Quick Start

### Prerequisites

- Rust 1.84.1 or later
- Node.js v20.0.0 or later
- pnpm 9.1.0

### Build

```bash
cargo build
```

### Test

```bash
# Test the entire workspace
cargo test --workspace --all-features

# Test a specific package
pnpm test sdk
pnpm test programs/token
```

### Format

```bash
pnpm format sdk
```

### Lint

```bash
pnpm clippy sdk
```

## Original Documentation

For complete documentation about the Pinocchio library, please refer to [README.md](./README.md).

## License

Apache License Version 2.0 - See [LICENSE](./LICENSE) file for details.
