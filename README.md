# nymstr

> **messaging without surveillance**

Chat freely without giving up your phone number, email address, real name, or location. nymstr is a private messenger that doesn't track who you talk to, when you talk, or where you are.

## Why nymstr?

Privacy isn't about having something to hide - it's about having something to protect. nymstr ensures:

- **No personal info needed** - Create an account with just a username you choose. No phone number, no email, no real name required.
- **They can't see who you talk to** - Your conversations are private. No company or government can see who you message, when you message, or how often.
- **Your messages stay yours** - Messages are encrypted so only you and the person you're talking to can read them. Not even nymstr can see what you say.

## How we're different

| Feature | nymstr | Signal | Telegram | WhatsApp |
|---------|---------|---------|----------|----------|
| Works without phone number | ✓ | ✗ | ✗ | ✗ |
| Hides who you talk to | ✓ | partial | ✗ | ✗ |
| You can run your own server | ✓ | ✗ | ✗ | ✗ |
| Hides your location | ✓ | ✗ | ✗ | ✗ |
| Code anyone can inspect | ✓ | ✓ | partial | ✗ |
| No single company controls it | ✓ | ✗ | ✗ | ✗ |

## Technical architecture

Built on proven cryptographic foundations:

- **Rust implementation** - Memory-safe systems programming language prevents entire classes of vulnerabilities
- **MLS protocol** - IETF-standardized group messaging with tree-based Diffie-Hellman key agreement
- **PGP web of trust** - Decentralized identity verification through cryptographic signatures
- **Mixnet routing** - Sphinx packet format with layered encryption and random delays

## Repositories

- **[nymstr-app](https://github.com/nymstr/nymstr-app)** - Desktop client application (Rust TUI)
- **[nymstr-server](https://github.com/nymstr/nymstr-server)** - Discovery node and message relay service

## Development roadmap

- **Q4 2025**: Desktop launch - Native applications for Linux, macOS, and Windows
- **Q1 2026**: Mobile apps - Android and iOS applications with full feature parity
- **Q2 2026**: Federated network - Decentralized server federation allowing cross-server communication

## Contributing

Privacy is a fundamental human right. Help us build truly anonymous communication for everyone.

- **Report issues** - Found a bug? Have a feature request? [Open an issue](https://github.com/nymstr/nymstr-app/issues)
- **Contribute code** - Fork our repositories and submit pull requests
- **Security research** - Responsible disclosure of security vulnerabilities is welcome
- **Documentation** - Help improve our docs and guides

## License

This project is licensed under the GPL-3.0 License - see the individual repository LICENSE files for details.