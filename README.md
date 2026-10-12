# Commander Lab Releases

Public Windows beta releases for **Commander Lab**. The application source code is maintained separately in the private development repository.

## Latest release — Beta 0.1.15

**[Get Commander Lab Beta 0.1.15](https://github.com/ateam54321/Commander-Lab-Releases/releases/tag/beta-0.1.15)**

- Windows installer: `CommanderLab-Beta-0.1.15-Setup.exe`
- Portable Windows app: `CommanderLab-Beta-0.1.15-Windows-Portable.zip`
- Integrity verification: `SHA256SUMS.txt`

Beta 0.1.15 fixes two issues observed during the first real 0.1.14 Edgar test: repeated ChatGPT context-length errors in final AI critique, and a Guided Step 5/Step 6 mismatch where completed reviewed cards could be reopened after validated swaps. The hotfix adds a short-context retry, prevents Guided swap review resets, and provides a user-triggered **Restore previously completed review decisions** action that requires exact prior historical verdicts; it never fabricates approvals or changes protected allocations. The exact Windows-qualified build passed **1,600 tests**, packaged EXE, installer and synthetic existing-profile preservation checks in [run 38275916167](https://github.com/ateam54321/MTG-Deck-Builder/actions/runs/38275916167). Final deck strength remains unproven until another user trial.

For an existing installation, use the in-app updater or download the latest installer from the release page. Do not delete your collection or saved decks to update; keeping a normal backup is recommended.

The installer is unsigned and may show a **Microsoft SmartScreen Unknown Publisher** warning. No personal collections, deck allocations, authentication data or user profiles are included with the installer.

## Previous releases

Earlier Windows beta versions remain available in [Releases](https://github.com/ateam54321/Commander-Lab-Releases/releases). Already-published tags and binaries are not overwritten.
