<p align="center"><img src="logo.png" width="160" alt="DraftDeck"></p>

# DraftDeck — downloads

*[Versão em português](README.md)*

DraftDeck is a presentation editor for macOS and Windows, made as a hobby.
**It is free and accepts no payment of any kind**: no sales, subscriptions, ads or donations.
It is not a commercial offering and is not in any app store.

Based on [DeckCraft](https://github.com/storytold/deckcraft) (MIT OR Apache-2.0), with its own
interface, icons and themes. License notices and attributions ship inside each package.

## Downloads

| System | File | Notes |
|---|---|---|
| macOS 11+ (Intel and Apple Silicon) | [`macOS/`](macOS/) — universal `.dmg` | Signed with a Developer ID and notarized by Apple: opens without warnings. Drag DraftDeck to Applications. |
| Windows 10/11 (x64) | [`windows/`](windows/) — `.exe` or portable `.zip` | No code-signing certificate: on first launch SmartScreen may warn; choose "More info › Run anyway". |

Each file has a `.sha256` next to it for verification.

## How to install

### macOS

1. Open the [`macOS/`](macOS/) folder, click the `.dmg` file, then the **Download** button.
2. Open the downloaded file. A window shows the DraftDeck icon next to the Applications folder.
3. Drag DraftDeck onto Applications.
4. Launch DraftDeck from Launchpad or the Applications folder. There is no warning: the app is notarized by Apple.
5. You can eject the "DraftDeck" disk and delete the `.dmg`.

### Windows

1. Open the [`windows/`](windows/) folder, click the `.exe` file, then the **Download** button.
2. If nothing shows up, check the browser's download list: Edge may hold the `.exe` because it has no paid certificate. Click the three dots next to the file and choose **Keep**. Chrome usually lets it through.
3. Double-click the downloaded file.
4. If the blue "Windows protected your PC" screen appears, click **More info**, then **Run anyway**. The button only shows after "More info". That is SmartScreen noting the app has no paid certificate; it happens on the first run only.
5. Follow the installer: accept the license, pick the folder, Install, Finish. It installs for your user only and does not ask for an administrator password.
6. DraftDeck is in the Start menu.

**Not allowed to install programs?** Download the portable `.zip`, unzip it into a folder of yours (Documents, for example) and open the `DraftDeck.exe` inside. Nothing is installed.

### Updating

Download the new version's file and install it over the old one. Your presentations stay where you saved them; the installation does not touch them.

## Current version

0.7.0-draftdeck.7 (October 16, 2026).

What's new: the Windows installer is now an `.exe`, which Edge accepts more readily than the `.msi` and installs without an administrator password. From .6: the missing-font notice now follows the interface language (one, two or more fonts). From .5: the notice for a file that didn't open (a OneDrive `.pptx` still in the cloud, for example) stays on screen until you close it. From .4: on the Mac, DraftDeck shows up in "Open With" for `.pptx` files and opens files by double-click or dropped on the Dock; files still in the cloud wait for the download and explain what to do if it doesn't finish. From .2: Manzana Line icons, dialogs that fit their content and more Portuguese text. The .1 release brought the Manzana interface in three looks, three languages, AutoSave and recovery, the Close button and `.pptx` support.

## Source code

DraftDeck's source lives in a private repository. This repository holds only the installers.
