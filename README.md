# Commander Lab Releases

Public Windows beta releases for **Commander Lab**. Source code lives in the separate development repository.

## Latest release — Beta 0.1.27

**[Get Commander Lab Beta 0.1.27](https://github.com/ateam54321/Commander-Lab-Releases/releases/tag/beta-0.1.27)**

- Windows installer: `CommanderLab-Beta-0.1.27-Setup.exe`
- Portable Windows app: `CommanderLab-Beta-0.1.27-Windows-Portable.zip`
- Release verification: `SHA256SUMS.txt`

This user-requested hotfix fixes **Deck Import and Manual Deck Editor card/token name collisions**. Names such as **Starscape Cleric** may exist in both playable card records and offspring token records. Commander Lab now ignores token identities when choosing the one legal playable card. When more than one real legal identity remains, exact set and collector data can distinguish it, otherwise the app still reports ambiguity rather than guessing.

The Beta 0.1.26 AI Brain and no-AI Strategy Discovery behavior remains unchanged. All Windows release-critical source regressions, GUI/installer checks, clean-start tests, and synthetic existing-profile preservation passed in [qualification run 39056342294](https://github.com/ateam54321/MTG-Deck-Builder/actions/runs/39056342294). [Public publishing and release file checksum verification](https://github.com/ateam54321/Commander-Lab-Releases/actions/runs/39057164571) also succeeded.

To update an existing installation, open **Commander Lab → Settings → Check for Updates** and install **Beta 0.1.27**. If unavailable, use the installer linked above. Back up important local collections, saved decks, and settings before updating. The unsigned installer may trigger Microsoft SmartScreen. No personal collection or credentials are included.

## Previous releases

Prior beta versions remain available on the [Releases page](https://github.com/ateam54321/Commander-Lab-Releases/releases). Published binaries and tags are never overwritten.
