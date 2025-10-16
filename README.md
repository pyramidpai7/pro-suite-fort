# Fortnite Toolkit — Advanced C++ tool

![release image](assets/release.png)

## Overview

Fortnite Pro Suite — silent aimbot, multi-mode ESP, ragebot modules, and skin changer. Regular updates, low latency, and performance-tuned for competitive play. Download demo & patch notes.

> ⚠️ This project is provided **for educational and research purposes only**. Using runtime modification tools in live, competitive, or commercial environments may violate terms of service and can result in account sanctions. Do not use these tools to gain unfair advantage in online games.

---

## What’s inside

- **Fortnite Aimbot**: Smooth aiming with customizable FOV, bone targeting (head, body), and prediction for moving targets. Undetected against Epic's anti-cheat.
- **Fortnite Wallhack**: See enemies through walls with color-coded outlines (red for enemies, blue for teammates).
- **Fortnite ESP**: Displays player info like health, distance, weapons, and items in real-time overlays.
- **Fortnite Triggerbot**: Auto-fires when crosshair is on an enemy.
- **Recoil Control & No-Spread**: Eliminates weapon recoil and bullet spread.
- **Skin Changer & Radar Hack**: Customize character skins and get a mini-map radar for enemy positions.
- **Bypass Anti-Cheat**: Methods to evade Epic's anti-cheat system (e.g., kernel-level injection).
---

## Screenshots

![screenshot 1](assets/image.png)

![screenshot 2](assets/image2.png)

![screenshot 3](assets/image3.png)

---

## Quick start

1. ✅ **Download the latest release** from the [Releases](../../releases).
2. 📁 **Extract Files**: Unzip the archive to a secure folder.
3. 🟢 **Run Loader**: Launch `Loader.exe` as administrator.
4. 🔄 **Wait for Injection**: Listen for a confirmation beep.

---

## Example configuration

A simple `config.ini` used by the toolkit to persist tuning values:

```ini
[Aimbot]
Enabled = true
FOV = 90
Smoothness = 5.0
TargetBone = head

[ESP]
Enabled = true
EnemyColor = red
TeamColor = blue
MaxDistance = 500

[WallVisualization]
Enabled = true
GlowIntensity = 2.0
```

## Project scope & ethics

This repository aims to be a learning resource for developers interested in real-time rendering overlays, input sampling, and experimentation with predictive smoothing algorithms. The maintainers ask contributors and users to act responsibly:

* Respect game and platform terms of service.
* Do not use research code to gain an unfair advantage on public or competitive servers.
* Use the codebase for education, security research, or UX prototyping only.

---

## License

This project is distributed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## Contact / Support

If you have questions about experiments, need help building the code, or want to propose improvements focused on research or education, open an issue or submit a pull request with a clear description of goals and test methodology.
