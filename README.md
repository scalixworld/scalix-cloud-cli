# Scalix Cloud CLI — binary distribution

This repo hosts the **prebuilt binaries** the `scalix-cloud` npm package downloads at install time. There is nothing to do here as a user — install the CLI the normal way:

```bash
npm install -g scalix-cloud
scalix-cloud login        # API key from https://console.scalix.world
```

- **Docs**: https://docs.scalix.world/cli
- **Release notes**: the [Releases](https://github.com/scalixworld/scalix-cloud-cli/releases) tab
- **Platforms**: Linux (x86_64, aarch64) · macOS (Apple Silicon) · Windows (x86_64)
- Every binary ships with a `.sha256` checksum, verified automatically by the npm installer.

Source code lives in the private Scalix Cloud platform monorepo. The SDKs are separate packages: [`@scalix-world/sdk`](https://www.npmjs.com/package/@scalix-world/sdk) (npm) and [`scalix-sdk`](https://pypi.org/project/scalix-sdk/) (PyPI).

© Scalix World Pvt Ltd · https://scalix.world
