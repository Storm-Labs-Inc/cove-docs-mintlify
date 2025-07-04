# Cove Documentation

This repository contains the official documentation for the Cove protocol and
ecosystem, built with [Mintlify](https://mintlify.com). It includes user
guides, technical references, protocol RFCs, and partner resources rendered as
`.mdx` pages.

## Repository structure

- `introduction.mdx` – Landing page for the docs
- `ecosystem/` – High-level overviews of Cove protocol, tokens, partners, and Boosties
- `technical/` – Deep-dive technical specs and architecture RFCs
- `how-to/` – Step-by-step user guides
- `security/` – Audits, bug-bounty, risk disclosures, and contract addresses
- `resources/` – Additional resources like media kit and privacy policy
- `images/` – All static assets referenced by the docs

## Getting started

### Prerequisites

- Node.js ≥ 18
- [pnpm](https://pnpm.io) ≥ 8
- Mintlify CLI (installed globally)

### Installation

```bash
pnpm install
pnpm i -g mintlify   # installs the Mintlify CLI
```

### Local development

```bash
mintlify dev
```

This launches a hot-reloading docs server at `http://localhost:3000`.

### Linting & formatting

```bash
pnpm format:check   # verify formatting
pnpm format         # apply Prettier formatting
```

## Contributing

Pull requests are welcome! Please ensure that new MDX files follow the writing
guidelines in `always_applied_workspace_rules` and that all code examples are
tested.

## License

Licensed under the [MIT License](LICENSE) © 2025 Storm Labs.
