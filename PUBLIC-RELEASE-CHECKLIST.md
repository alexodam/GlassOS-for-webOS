# First public beta release checklist

Starting point: the local pre-release GlassOS source copy.

## Before publishing

- [x] Rebuild the IPK from a clean staging copy without device-generated app icons or app/input data. The legacy local package contains personal TV settings; do not publish it.
- [x] Generate and verify a SHA-256 checksum for the rebuilt package (see RELEASE-SHA256SUMS.txt).
- [x] Confirm the package contains the canonical icon and regenerated webOS icon sizes (80×80 and 130×130).
- [x] Inspect the package archive and confirm device-generated app icons and macOS metadata are absent.

- [x] Review bundled app icons, artwork, ambient music and font notices; project owner confirms the assets are cleared for public distribution, and font notices are included.
- [x] Finalize first-beta release notes.
- [x] Record the verified TV combination: LG OLED48C26LB, firmware 23.25.55 (webOS CLI SDK version 9.2.2). Additional combinations remain unverified.
- [x] Review the final repository contents for pairing keys, local network details, generated app lists, and other personal data. Starter app data is empty, TV icons and IPKs are ignored, and no pairing key is in the release folder.
- [ ] Confirm the GitHub repository is named GlassOS (for webOS), while the app shown on the TV remains GlassOS and the internal app ID stays unchanged.
