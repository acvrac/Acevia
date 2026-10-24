# AGENTS.md

## Project

- Single Rust binary crate (`Cargo.toml` package name `Acevia`), Rust **edition 2024** — requires a recent toolchain (1.85+).
- Early stage: only `src/main.rs` (currently a hello-world placeholder) and empty `docs/design/` and `docs/changelog/` directories. No CI workflows exist (`.github/` is empty) despite the conventional expectation of one.

## Commands

- Build: `cargo build`
- Run: `cargo run`
- Verify a change: `cargo build && cargo run` (no tests, lints, or CI configured yet — do not assume `cargo test` output covers anything).

## Conventions

- `.editorconfig`: 4-space indent, LF line endings, UTF-8, final newline; trailing whitespace is **not** trimmed (`trim_trailing_whitespace = false`).
