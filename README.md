# Scalix Cloud CLI — distribution

Public distribution of the **`scalix-cloud`** CLI (compiled binaries only; the
source lives in Scalix's private platform monorepo).

## Install

```bash
npm install -g scalix-cloud
scalix-cloud login <scalix_sk_…>   # key from https://console.scalix.world/org/keys
scalix-cloud --help
```

The npm package is a thin launcher that downloads the native binary for your
platform from this repo's releases (checksum-verified). Direct downloads:
`https://github.com/scalixworld/scalix-cli/releases`.

Platforms: Linux (x86_64, aarch64), macOS (Apple Silicon), Windows (x86_64).
Docs: https://docs.scalix.world · Made by [Scalix World](https://scalix.world).
