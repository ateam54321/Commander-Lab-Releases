# Commander Lab Releases

Public Windows beta releases for **Commander Lab**. The application source code lives in the separate development repository.

## Latest release — Beta 0.1.26

**[Download Commander Lab Beta 0.1.26](https://github.com/ateam54321/Commander-Lab-Releases/releases/tag/beta-0.1.26)**

- Windows installer: `CommanderLab-Beta-0.1.26-Setup.exe`
- Windows portable app: `CommanderLab-Beta-0.1.26-Windows-Portable.zip`
- Verification: `SHA256SUMS.txt`

This user-authorized hotfix corrects the **Manual Deck Editor exact-name lookup** when one card name has more than one Oracle record but only one of those identities is Commander-legal. For example, entering **Llanowar Elves** should now select the unique Commander-legal identity in such a catalog. The editor still blocks genuine multiple-legal-identity ambiguity instead of guessing.

The existing Beta 0.1.25 AI Brain behavior, protected collection/allocation checks and no-AI Strategy Discovery remain unchanged. The complete Windows regression suite, packaged application, installer, installed-app startup and synthetic existing-profile preservation passed in [Windows qualification run 39051631234](https://github.com/ateam54321/MTG-Deck-Builder/actions/runs/39051631234). The [public release verification](https://github.com/ateam54321/Commander-Lab-Releases/actions/runs/39052328890) succeeded and confirmed both published binaries' SHA-256 checksums.

For existing installations, use **Settings → Check for Updates** or run the installer above. Back up important local collections, saved decks, and settings before updating. The unsigned installer may show a Microsoft SmartScreen warning. No personal collection, saved deck, credential or protected allocation is bundled in the release.

## Previous releases

Older releases remain accessible from the [Releases page](https://github.com/ateam54321/Commander-Lab-Releases/releases). Public tags and binaries are immutable and never overwritten.
