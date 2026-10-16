# Commander Lab Releases

Public Windows beta releases for **Commander Lab**. The application source code is maintained separately in the private development repository.

## Latest release — Beta 0.1.25

**[Get Commander Lab Beta 0.1.25](https://github.com/ateam54321/Commander-Lab-Releases/releases/tag/beta-0.1.25)**

- Windows installer: `CommanderLab-Beta-0.1.25-Setup.exe`
- Portable Windows app: `CommanderLab-Beta-0.1.25-Windows-Portable.zip`
- Integrity verification: `SHA256SUMS.txt`

This user-authorized prerelease **rolls AI-assisted deckbuilding and review back to the qualified Beta 0.1.23 behavior** after the Beta 0.1.24 Edgar Markov Deep strategy-execution regression. It retains the Beta 0.1.23 No-AI Strategy Discovery and Brain-only improvements. The 0.1.24 Economy / Balanced / Deep optional critic setting is no longer present; AI usage may rise again.

The qualified source commit is `9231f335ea44acfbdc9290075ab6cc79b662ba88`. Full Windows release-critical tests, packaged app startup, installer startup, and synthetic existing-profile preservation passed in [run 38951972899](https://github.com/ateam54321/MTG-Deck-Builder/actions/runs/38951972899). The [public release publication and checksum verification](https://github.com/ateam54321/Commander-Lab-Releases/actions/runs/38952905128) also succeeded.

**Important:** This rollback does not establish that Edgar's strategy-to-final-99 problem is fixed. Test a new user-initiated deck and compare it independently before locking it.

For an existing installation, open **Settings → Check for Updates** or use the installer above. Back up important local app data before updating. The installer is unsigned and may show a Microsoft SmartScreen warning. No private collections, saved projects, protected allocations, or credentials are included.

## Previous releases

Prior versions remain available on the [Releases page](https://github.com/ateam54321/Commander-Lab-Releases/releases). Already-published versions and binaries are not overwritten.
