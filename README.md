# CMW-Library

Shared asset library for the [CMW-Maps](https://github.com/SageFlare/CMW-Maps) ports: Chivalry: Medieval Warfare maps rebuilt for Chivalry 2 Unchained.

The maps keep their own layout and lighting in their own PAKs. Everything they share is in this one PAK: meshes, materials, textures, sounds and effects from CMW's asset packages. Each CMW asset exists once, at a fixed path under `/Game/Mods/AgMods/CMW_Library/`, so maps never carry copies of each other's assets.

## Installation

1. Download `CMW_Library.pak` from the [latest release](https://github.com/SageFlare/CMW-Library/releases/latest).
2. Download the map PAKs you want from the [CMW-Maps releases](https://github.com/SageFlare/CMW-Maps/releases/latest).
3. Copy all of them into `Chivalry 2/TBL/Content/Paks/`.
4. Launch through the [Unchained Launcher](https://github.com/Chiv2-Community/UnchainedLauncher).

Every CMW map needs this library. The library on its own adds no map.

Each release lists the SHA256 of its PAK (`CMW_Library.pak.sha256`).

## Status

**Dev/test build (0.x), not a public release.** Shared with the Unchained developers for testing, including mod-loading time. The ports are made with an automated converter and are still being checked in game. See [CMW-Maps](https://github.com/SageFlare/CMW-Maps) for the map list and known issues.

This build is the full library, the same set we test with. It also holds assets used by maps that are not in CMW-Maps yet.

The library only grows: a new map adds assets but never moves or renames existing ones, so older map releases keep working with a newer library.

## Credits

- Original assets: Chivalry: Medieval Warfare by Torn Banner Studios.
- Port: SageFlare.
- Modding toolchain: the Chivalry 2 Unchained community (Unchained Launcher, ArgonSDK).

See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for what the license covers.
