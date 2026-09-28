# Auxo iOS

Native iOS WKWebView wrapper for the supplied `app.html`.

## Project
- Bundle ID: `com.auxo.cheat`
- Deployment target: iOS 15+
- HTML UI is bundled as `AuxoApp/app.html`.
- Native bridge name: `licenseStore`.
- `openGame` opens the configured Free Fire / Free Fire MAX URL scheme.

## GitHub
Upload the entire folder, keeping `codemagic.yaml` in the repository root.

## Codemagic
1. Connect the GitHub repository.
2. Scan the repository for `codemagic.yaml`.
3. Configure Apple signing for bundle ID `com.auxo.cheat`.
4. Start the `ios-native` workflow.

For App Store/TestFlight distribution, use an Apple Developer account and matching signing credentials.
