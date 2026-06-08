# Contributing to PatinaKey

Thanks for your interest! PatinaKey is an open project and contributions of all kinds are welcome : code, hardware review, documentation, or just thoughtful questions.

## Ways to help

- **Hardware review** - spot a footprint, routing, or design issue? Open an issue.
- **Firmware** - the Rust firmware is the next big milestone (see the `firmware` repo).
- **Documentation** - clarify the build process, the design choices, or the reproduction steps.
- **Reproduce it** - build the board, report what worked and what didn't.

## How to contribute

1. **Open an issue first** for anything non-trivial, so we can align before you spend time.
2. Fork the relevant repo and create a branch (`feature/...` or `fix/...`).
3. Keep changes focused and explained : *why*, not just *what*.
4. Open a pull request referencing the issue.

## Style

- **Firmware:** format in allman style, lint with `cargo clippy`, keep `no_std` discipline.
- **Hardware:** describe changes in plain language in the PR. Attach before/after renders when relevant.
- **Commits:** clear, present-tense messages (e.g. `Add SWD pogo header`, `Fix VDDA filter placement`).

## Security

Please **do not** report security vulnerabilities through public issues or PRs.
See [`SECURITY.md`](SECURITY.md) for responsible disclosure.

## License

By contributing, you agree your contributions are licensed under each repo's license
(CERN-OHL-S for hardware, GPL-3.0 for firmware, CC-BY for docs).
