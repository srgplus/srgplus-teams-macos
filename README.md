# SRG+ Teams for Mac

The Mac app of SRG+ Teams, for download outside the App Store.

**Download:** [SRG-Plus-Teams.dmg](https://github.com/srgplus/srgplus-teams-macos/releases/latest/download/SRG-Plus-Teams.dmg)

Open the DMG and drag SRG+ Teams to Applications. The app updates itself (Sparkle): it checks once a day, and
**SRG+ Teams › Check for Updates…** checks at once. It needs macOS 26 or later.

This repository only hosts the releases (the DMG) and `appcast.xml`, the update feed the installed apps read
(GitHub Pages, `https://srgplus.github.io/srgplus-teams-macos/appcast.xml`). The app's code and the build script
(`apps/ios/scripts/mac-dmg.sh`) are in the private repository srgplus/srgplus-teams. Changes to `appcast.xml` go
through a pull request, never straight to `main`.
