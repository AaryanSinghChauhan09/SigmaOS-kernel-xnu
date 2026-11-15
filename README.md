# SigmaOS-kernel-xnu

> **SigmaOS Kernel — Xnu** — Kernel subsystem component for SigmaOS microkernel.

Part of the [SigmaOS](https://github.com/AaryanSinghChauhan09/SigmaOS) ecosystem.  
Kernel subsystem component for SigmaOS microkernel

## Quickstart

```bash
cargo test    # run deterministic AAA unit tests
cargo check   # verify compilation
```

## Component Role

This crate implements the `xnu` subsystem for SigmaOS:
- Fully real Rust implementation (no stubs)
- Fail-fast validation with typed errors
- Deterministic unit tests (Arrange-Act-Assert pattern)
- Single Responsibility, Modular, Zero-Copy where applicable

## API

```rust
use sigmaos_kernel_xnu::*;
// See src/lib.rs for full public API
```

## Documentation

Full documentation is in the [SigmaOS GitHub Wiki → Kernel-Architecture](https://github.com/AaryanSinghChauhan09/SigmaOS/wiki/Kernel-Architecture).

## License

GPL-2.0
