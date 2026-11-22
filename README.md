# ZynCord releases

Downloads for [ZynCord](https://github.com/zyncord-app), a Discord client built for voice, in real stereo.

**[Download the latest version](https://github.com/zyncord-app/zyncord-releases/releases/latest)**: take `zyncord-rust.exe`.

Each release has three files:

| File | What it is |
|---|---|
| `zyncord-rust.exe` | The app, for Windows 10 and 11 |
| `zyncord-update.json` | Version, size and SHA-256 of the exe, and the release notes |
| `zyncord-update.json.sig` | The Ed25519 signature of that file |

ZynCord reads this repository to update itself. It installs a release only if the signature
matches the key built into the app and the exe matches the signed size and hash, so files
re-uploaded anywhere else, or changed here, are refused.

This repository only holds releases. Modified clients are against Discord's Terms of Service;
ZynCord is not affiliated with or endorsed by Discord Inc.
