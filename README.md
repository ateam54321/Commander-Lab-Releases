# Commander Lab Releases

Public Windows beta releases for **Commander Lab**. The application source code is maintained separately in the private development repository.

## Latest release — Beta 0.1.22

**[Get Commander Lab Beta 0.1.22](https://github.com/ateam54321/Commander-Lab-Releases/releases/tag/beta-0.1.22)**

- Windows installer: `CommanderLab-Beta-0.1.22-Setup.exe`
- Portable Windows app: `CommanderLab-Beta-0.1.22-Windows-Portable.zip`
- Integrity verification: `SHA256SUMS.txt`

This is a user-authorized **testing prerelease** focused on fixing the complete Guided deckbuilding workflow when **No AI** is selected. Commander-first Strategy Discovery, deterministic Blueprint/candidate selection, Brain-built provisional 99, and conservative Brain-only final review are available without an AI account.

Focused No-AI regressions, core smokes, Windows packaged-app startup, installer startup, and synthetic existing-profile preservation passed in [Windows run 38824261756](https://github.com/ateam54321/MTG-Deck-Builder/actions/runs/38824261756). The full repository-wide regression run had **not completed** at release time, and a real six-step No-AI deck build remains to be verified by the user. See the release notes for details.

For an existing installation, use Settings → Check for Updates or the installer above. Important local collections and saved decks should be backed up before updating. The installer is unsigned and may show a Microsoft SmartScreen warning. No private collections, card allocations, saved projects, or credentials are included in the installer.

## Previous releases

Earlier Windows beta versions remain available in [Releases](https://github.com/ateam54321/Commander-Lab-Releases/releases). Already-published tags and binaries are not overwritten.
