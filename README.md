# Vistrux WhatsApp Agent: releases

Update channel for the Vistrux WhatsApp Agent. The app reads from here; there is nothing to download by hand.

- **Releases**: full installers (`npm run release:shell`).
- **modules/**: signed module packages (`npm run release:modules`). `manifest.json` lists every module version and file hash; `manifest.sig` is its Ed25519 signature. The app refuses anything that does not verify against the key built into it.
