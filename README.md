# Scalix Cloud CLI

Official command-line interface for [**Scalix Cloud**](https://scalix.world) — manage PostgreSQL databases (ScalixNova), serverless functions, containers (Scalix Run), AI inference, object storage, KV, and custom domains from your terminal with one API key.

> **Proprietary Binary Distribution**
> Scalix Cloud and the `scalix-cloud` Rust CLI are proprietary software owned by **Scalix World Pvt Ltd** (India) and licensed internationally via **Energy FW Ltd** (UK). Core CLI source code lives in the private Scalix Cloud monorepo; this repository hosts the verified prebuilt release binaries and `.sha256` checksums used by `npm`, Homebrew, and Scoop installers.

---

## Install

```bash
# npm (recommended)
npm install -g scalix-cloud

# Homebrew (macOS & Linux)
brew install scalixworld/tap/scalix-cloud

# Scoop (Windows)
scoop bucket add scalix https://github.com/scalixworld/scoop-bucket
scoop install scalix/scalix-cloud
```

*(Not to be confused with [`scalix`](https://www.npmjs.com/package/scalix) on npm, which is Scalix Coder, the AI coding agent.)*

---

## Quick Start

```bash
scalix-cloud --version
scalix-cloud login                         # API key from https://console.scalix.world
scalix-cloud whoami

scalix-cloud db query "SELECT 1"
scalix-cloud fn deploy ./my-function
scalix-cloud run deploy ./my-service
scalix-cloud ai --help
scalix-cloud storage --help
```

---

## Supported Platforms

Every binary in [Releases](https://github.com/scalixworld/scalix-cloud-cli/releases) is distributed alongside a `.sha256` checksum file verified automatically at install time:

| OS | Architectures |
|---|---|
| Linux | `x86_64`, `aarch64` |
| macOS | Apple Silicon (`aarch64`), Intel (`x86_64`) |
| Windows | `x86_64` |

---

## Links & SDKs

- **CLI Documentation:** [`https://docs.scalix.world/cli`](https://docs.scalix.world/cli)
- **Cloud Console:** [`https://console.scalix.world`](https://console.scalix.world)
- **Releases:** [`github.com/scalixworld/scalix-cloud-cli/releases`](https://github.com/scalixworld/scalix-cloud-cli/releases)
- **Official SDKs:** [`@scalix-world/sdk`](https://www.npmjs.com/package/@scalix-world/sdk) (TypeScript), [`scalix-sdk`](https://pypi.org/project/scalix-sdk/) (Python), [`@scalix-world/auth`](https://www.npmjs.com/package/@scalix-world/auth) (Auth) — [`scalixworld/scalix-world-sdk`](https://github.com/scalixworld/scalix-world-sdk)
- **Policies:** [Terms](https://scalix.world/terms) · [Privacy](https://scalix.world/privacy) · [Security](https://scalix.world/security)

---

**License:** `BUSL-1.1` (proprietary binary distribution).
© 2026 Scalix World Pvt Ltd · Licensed internationally via Energy FW Ltd.
