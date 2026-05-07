# XIRO Assistant Open Map Patch

An unofficial map patch for XIRO Assistant that replaces the legacy Google-dependent map page with an open-source mapping implementation.

## Unofficial Notice

This is an **unofficial XIRO-related project**.

- It is **not affiliated with, endorsed by, sponsored by, or approved by** XIRO, Zero Tech, or any official XIRO product owner.
- This repository is an independent compatibility patch only.
- No claim is made to ownership of the XIRO Assistant application, brand, or trademarks.

## What This Project Does

This patch replaces the outdated map HTML/JavaScript layer used by XIRO Assistant with a custom open-source alternative while preserving the app's existing JavaScript bridge behavior as closely as possible.

Current goals:

- remove the legacy Google API dependency
- keep the original XIRO Assistant map workflow functional
- preserve waypoint, plane, target, and route interactions
- provide a simple installer workflow for end users

## Original Code and Open-Source Components

The patch logic and Windows installer for this project are **original custom code** created for this patch.

This project also uses open-source mapping components, including:

- **Leaflet** for the browser-based interactive map layer
- **OpenStreetMap** map data / attribution model

This repository is intended to combine:

- original compatibility code written specifically for XIRO Assistant
- open-source SDK/library components used to render and control maps

## Repository Contents

- [`html/`](./html/)
  Replacement map assets used by the patch, including the custom map bridge and Leaflet-based implementation.

## Important Notes

- This project is designed as a **patch**, not a replacement for XIRO Assistant itself.
- XIRO Assistant binaries are **not included** in this repository.
- You must already have a legitimate XIRO Assistant installation to use this patch.
- Map tile availability depends on the configured tile source and network access unless tiles are already cached locally.

## Attribution

This patch uses or references open-source mapping technology that requires attribution.

### Leaflet

- Project: Leaflet
- License: BSD-2-Clause
- Website: [https://leafletjs.com/](https://leafletjs.com/)
- Source: [https://github.com/Leaflet/Leaflet](https://github.com/Leaflet/Leaflet)

### OpenStreetMap

- Attribution text: `(c) OpenStreetMap contributors`
- Copyright / attribution guidance: [https://www.openstreetmap.org/copyright](https://www.openstreetmap.org/copyright)
- Tile usage policy: [https://operations.osmfoundation.org/policies/tiles/](https://operations.osmfoundation.org/policies/tiles/)

## Disclaimer

This project is provided **as-is**, without warranty of any kind.

Use it at your own risk. Because XIRO Assistant is a legacy third-party application, behavior may vary by install, operating system, or runtime environment.

## Status

Current installer line: **v1.3**

If you publish releases from this repository, it is a good idea to keep the release notes aligned with the installer version shown to users.
