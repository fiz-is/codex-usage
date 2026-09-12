# Codex Usage

[Codex Usage](https://www.codexusage.dev) is a free local monitor for OpenAI Codex usage, remaining limits, and reset times.

It works with your existing authenticated Codex CLI session and can show usage in the terminal or a local browser dashboard.

## Quick start

Run directly with npm:

```sh
npx @codex-usage/codex-usage
```

Or install the CLI:

```sh
curl -fsSL https://www.codexusage.dev/install.sh | sh
```

Then run:

```sh
codex-usage
```

For the local browser dashboard and full installation instructions:

https://www.codexusage.dev/install

## Requirements

- macOS
- Python 3
- OpenAI Codex CLI installed and available as `codex`
- An authenticated Codex account

## What it shows

- Current 5-hour usage
- Current weekly usage
- Reset times
- Remaining allowance
- Local browser dashboard
- Session usage and pacing information when available

Codex Usage also provides machine-readable usage output, privacy-safe diagnostics, and version information through its CLI.

## Privacy

Codex Usage runs locally and uses your existing authenticated Codex client.

It does not ask you to paste account credentials into the tool and does not add telemetry or analytics.

## macOS companion

A native macOS menu bar companion is also available.

Installation details and downloads:

https://www.codexusage.dev/install


## Source and distribution

This repository contains the public distribution files for Codex Usage.

Codex Usage is an independent project and is not affiliated with or endorsed by OpenAI.

## License

Codex Usage is proprietary software and is not open source.

Personal and internal business use of unmodified copies is permitted. Redistribution, modification, sublicensing, sale, and derivative works require prior written permission.

See [LICENSE](LICENSE).
