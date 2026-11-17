<div align="center">

# USB Loader GX

### Homebrew Game Loader for Nintendo Wii

A graphical game library manager and loader for Wii and GameCube titles stored on USB devices or SD cards.

[Official GitHub Repository](https://github.com/wiidev/usbloadergx) · [Latest Release](https://github.com/wiidev/usbloadergx/releases)

</div>

## Product Overview

USB Loader GX is an open-source homebrew application for Nintendo Wii. It provides a graphical interface for browsing and launching Wii and GameCube games from supported USB storage devices and SD cards.

The application includes cover artwork, configurable game settings, multiple display layouts, homebrew launching, and additional library-management features.

The current official repository is maintained by the wiidev project. The latest published release identified in the repository is **v4.0-r1283**.

## Technical Architecture

USB Loader GX operates as a homebrew application within the Wii environment.

Its main components include:

- **Application Interface:** Graphical interface for browsing games and configuring settings.
- **Storage Access:** Reads supported game files from USB storage and SD cards.
- **Game Launching:** Uses compatible cIOS components to launch supported Wii titles.
- **GameCube Integration:** Supports GameCube launching through compatible software such as Nintendont.
- **Metadata and Artwork:** Uses GameTDB-compatible metadata and downloadable cover artwork.
- **Configuration System:** Stores loader preferences, themes, and game-specific settings.

## Key Features

- Launch Wii games from USB storage and SD cards.
- Launch GameCube games through compatible Nintendont integration.
- Browse games using configurable interface layouts.
- Display downloadable game covers and disc artwork.
- Configure individual game settings.
- Apply supported video and language patches.
- Use custom themes and interface backgrounds.
- Access homebrew applications.
- Manage game lists and categories.
- Support compatible cIOS configurations.
- Configure supported cheat functionality.

## Module Overview

| Component | Function |
|---|---|
| Game Browser | Displays available Wii and GameCube titles |
| Storage Manager | Detects and accesses supported USB and SD storage |
| Game Launcher | Starts compatible games |
| Artwork Manager | Retrieves and displays game covers |
| Settings Interface | Configures global and per-game options |
| Theme Support | Applies compatible interface themes |
| Nintendont Integration | Provides GameCube game launching |

## Supported Platforms

- Nintendo Wii
- Nintendo Wii U in vWii mode
- Dolphin Emulator, subject to emulator compatibility

## Compatibility Information

USB Loader GX requires a homebrew-enabled environment.

Typical requirements include:

- Homebrew Channel.
- Compatible d2x cIOS installation for Wii game launching.
- SD card or supported USB storage device.
- Correct storage partition and file organization.
- Nintendont for GameCube launching.

Use the cIOS package intended for the specific platform. Wii and Wii U vWii installations are not interchangeable.

## Technical Specifications

| Specification | Details |
|---|---|
| Application | USB Loader GX |
| Latest identified release | v4.0-r1283 |
| Platform | Nintendo Wii |
| Additional platform | Wii U vWii |
| Architecture | PowerPC |
| Application type | Homebrew game loader |
| License | GPL-2.0 |
| Storage | USB and SD |
| Wii game support | Yes |
| GameCube support | Through Nintendont integration |
| Required environment | Homebrew Channel and compatible cIOS |

## Installation Guide

1. Prepare an SD card or compatible USB storage device.
2. Ensure the Homebrew Channel is installed on the console.
3. Install the appropriate d2x cIOS version for the target platform.
4. Download the latest USB Loader GX release from the official GitHub repository.
5. Extract the application files to the root of the SD card.
6. Confirm that the application folder is located at `/apps/usbloader_gx/`.
7. Insert the storage device into the console.
8. Launch USB Loader GX through the Homebrew Channel.
9. Configure storage, display, and game settings as required.

For GameCube titles, configure the compatible Nintendont environment separately.

## FAQ

### What is USB Loader GX?

USB Loader GX is a homebrew application that provides a graphical interface for launching Wii and GameCube games from supported storage devices.

### Does USB Loader GX support SD cards?

Yes. The current project includes support for launching Wii games from SD cards, in addition to supported USB storage.

### Does it support GameCube games?

Yes. GameCube launching is provided through Nintendont integration.

### Is cIOS required?

Compatible d2x cIOS is required for the standard Wii game-loading setup.

### Can I customize the interface?

Yes. USB Loader GX supports custom themes and multiple game-list display modes.

### Does it work on Wii U?

It supports the Wii U's vWii environment. It does not function as a native Wii U game loader.

### Where can I find the latest version?

The official releases are published on the project's GitHub page.

## SEO Keywords

USB Loader GX, Nintendo Wii homebrew, Wii USB loader, Wii game loader, GameCube loader, Wii SD card games, Wii homebrew applications, Nintendont integration, d2x cIOS, Wii game management, Wii homebrew software, USB Loader GX r1283

<div align="center">

---

**USB Loader GX** · Nintendo Wii Homebrew Software

[GitHub Repository](https://github.com/wiidev/usbloadergx)

</div>
