# GetUply — public assets and help

This repository holds everything GetUply publishes: the in-app **Help Center**,
the legal documents the app links to, and the assets it downloads on demand.

- **[Help Center](HELP.md)** — how every feature of the app works.
- **[Privacy Policy](legal/PRIVACY.md)** · **[Terms of Use](legal/TERMS.md)** ·
  **[Support](legal/SUPPORT.md)**

## On-demand alarm sounds and backdrops

`sounds/` and `backdrops/` are asset storage for the GetUply iOS app — **not a
sound library**. The audio files are processed derivatives (mono, looped/trimmed
to ≤29 s, normalized, IMA4 `.caf`) of recordings from Mixkit's free sound-effects
library, prepared exclusively for in-app consumption by GetUply. They are
downloaded on demand by the app and are not intended for standalone
redistribution or reuse.

Source licensing: Mixkit Sound Effects Free License
(https://mixkit.co/license/#sfxFree). Per-file provenance lives in the app
repository (`docs/SOUNDS_LICENSES.md`); `manifest.json` lists sha256/bytes for
upload verification.
