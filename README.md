<img width="550" height="36" alt="SOMEWHERE IN THE SOUTHWEST..." src="https://github.com/user-attachments/assets/fe88d0e6-128e-4a78-b573-138f98486eab" />

&nbsp;

This is a reimplementation of the classic game Interstate 76 in Godot engine.

[![I26 - Interstate '76 remastered (video)](https://img.youtube.com/vi/ph6Zrzbycx0/maxresdefault.jpg)](https://www.youtube.com/watch?v=ph6Zrzbycx0)

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/G4Q128JK2B)

# Features

* Modernized graphics
* 1997 mode - toggle the original graphics any time with F12
* Single player campaign, scenarios and auto melee
* Multiplayer with modern netcode
* Online coop mode for campaign and scenarios
* Easy to use 3D map editor
* 3D garage with respraying

## Optional
* Auto-reverse
* Mission checkpoints
* Botanically accurate vegetation
* Support for upscaled textures
* CB radio in multiplayer
* Car interiors

# Installation
Install the [GoG](https://www.gog.com/en/game/interstate76) version (and Nitro pack) from GoG Galaxy, and the game should find them automatically. If not, copy the Interstate 76 directory into the `i26` directory named `i76`, and/or the Nitro pack into the directory named `nitro`.

Alternatively, place the `setup_interstate_76_*.exe` offline backup installers into the `i26` directory and they will be unpacked automatically. If you're logged in to [gog.com](gog.com), the download links are: [Interstate 76](https://www.gog.com/downloads/interstate_76/en1installer1), [Nitro Pack](https://www.gog.com/downloads/interstate_76_nitro_pack/en1installer1)

On Linux, ensure Microsoft core fonts are installed for Impact and Arial.

# Source code
I26 is free software under the [GNU GPL v3](LICENSE). To build it, run the tests or contribute, see [DEVELOPMENT.md](DEVELOPMENT.md); [docs/playing.md](docs/playing.md) has the details for players (how the game finds your install, settings and saves, controls, custom maps, system requirements and status).

I26 contains no game data. It is an unofficial fan project and it needs your own legal copy of Interstate 76.

# Credits
Thanks to the Interstate 76 community for testing, ideas, and supporting this project.

---


# Android port

I26FORDroid is an unofficial Android port of I26, maintained by [tiagop91](https://github.com/tiagop91), based on the original project by [vahokif](https://github.com/vahokif/I26).

[![Watch the I26 Android port gameplay](https://i.ytimg.com/vi/566ZaqHka0E/maxresdefault.jpg)](https://youtu.be/566ZaqHka0E)

## Development acknowledgement

The Android port was developed with the assistance of **ChatGPT (OpenAI)**, which carried out the code changes, Android adaptations, build configuration and technical implementation.

The project was guided, tested and validated by myself, who provided feedback, refined the proposed changes and verified the results on real hardware.

In short, the implementation was AI-assisted, with human direction, testing and final validation.

**Please expect bugs and unfinished aspects. I'll do my best to maintain the port and improve it over time. Feedback, bug reports and suggestions are always welcome!**

### Important limitations

- Touchscreen controls are currently **not supported**.
- A physical gamepad or built-in handheld controls are required.
- Smartphone and tablet compatibility is not currently a target of this release, however it was tested on a Xiaomi 14T without gamepad and it launched the game.

This is an experimental release.

## Android installation

1. Download the I26FORDroid APK from the [GitHub Releases](https://github.com/tiagop91/I26FORDroid/releases) page.
2. Install the APK on your Android handheld.
3. Obtain your own legitimate GOG offline installer for Interstate '76.
4. Launch I26 and select the GOG installer using the Android file picker.
5. Wait for the game data extraction to complete.

The original game data is not included in this release. A legitimate GOG installer is required.

## Testing

**Tested device:**
- Retroid Pocket 5.

**Features tested:**
- Application installation and startup.
- GOG installer selection and extraction.
- Save games.
- Mission checkpoints.
- First campaign mission.

Compatibility with other Android handheld devices has not yet been verified.

## Android port credits

Android port and adaptations: [tiagop91](https://github.com/tiagop91).

Original I26 project: [vahokif/I26](https://github.com/vahokif/I26).

This is an unofficial community port. It is not affiliated with or endorsed by the original developers or rights holders.
