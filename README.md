# Magic Resume · Community-maintained Fork

Maintained and modified by [BinYuanc](https://github.com/BinYuanc), based on [JOYCEQL/magic-resume](https://github.com/JOYCEQL/magic-resume). This is not the upstream project's official distribution.

[简体中文](./README.zh-CN.md)

## Purpose

A browser-based resume editor with live preview, styling options and PDF export. The repository also includes AI-assisted editing code. Feature availability has not yet been verified end-to-end against the current revision.

## Quick start

Requires Node.js and pnpm.

```bash
git clone https://github.com/BinYuanc/magic_Resume.git
cd magic_Resume
pnpm install
pnpm dev
```

Open the local address shown in the terminal (typically http://localhost:3000). Windows launcher scripts and Docker Compose configuration are also included; their behavior depends on the local environment.

## Known limitations and verification status

- Full feature-by-feature regression testing is pending.
- AI integrations may require separately configured API credentials, network access and provider billing.
- PDF layout can vary by browser, font and print settings; inspect exports before use.
- Windows launchers depend on the local runtime and port availability; use `pnpm dev` to diagnose failures.
- No confirmed, reproducible bug inventory has yet been published. Please report issues with reproduction steps and redacted logs.

## Feedback

Use [this repository's Issues](https://github.com/BinYuanc/magic_Resume/issues). Do not post private resume details or API keys.

## Attribution and license

Original project: [JOYCEQL/magic-resume](https://github.com/JOYCEQL/magic-resume). Credit remains with the original author and contributors for their work. Upstream contact, donation and sponsor information does not represent this fork.

The repository's `LICENSE` contains Apache 2.0-related language plus additional commercial restrictions. Review the actual license and obtain appropriate legal/rights-holder guidance before commercial use or redistribution.
