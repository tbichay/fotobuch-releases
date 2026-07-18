# FOTOBUCH — Releases

Public download + auto-update host for [FOTOBUCH](https://github.com/tbichay/FOTOBUCH),
a native macOS photo-book maker.

- **Download the current version**: <https://tbichay.github.io/fotobuch-releases/>
- **Sparkle appcast** (referenced by the app for auto-updates):
  <https://tbichay.github.io/fotobuch-releases/appcast.xml>

Source code lives in a separate private repository. This repo hosts only
the built binary + the Sparkle feed so recipients can install and
auto-update without needing an Apple Developer account on either side.

Every release is EdDSA-signed with a key held in the developer's macOS
Keychain; Sparkle verifies the signature before installing.
