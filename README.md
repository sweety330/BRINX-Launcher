BRINX Launcher

<p align="center">
  <img src="docs/media/android/joystick-fox.png" alt="BRINX Launcher gameplay preview" width="100%">
</p><h1 align="center">BRINX Launcher</h1><p align="center">
  **Your Minecraft. Your Experience.**
</p><p align="center">
  A native Android launcher for Minecraft Java Edition.
</p><p align="center">
  Android 9+ · Vulkan · Touch Controls · Native Rust Engine
</p>---

About BRINX

BRINX Launcher is an Android gaming platform designed to bring Minecraft Java Edition to mobile devices through a native experience.

Our goal is to build more than a launcher: a complete environment for playing, customizing, managing and enjoying Minecraft on Android.

BRINX is built around the Horizon Rust engine and its Android implementation, with an independent product identity and plans for an expanded set of mobile-first features.

«BRINX Launcher is an unofficial third-party project. It is not affiliated with, endorsed by, or associated with Mojang or Microsoft.»

Features

The following describes capabilities currently documented in the underlying Android codebase. BRINX-specific additions are being developed separately.

- Native Android launcher.
- Vulkan rendering.
- Four touch-control schemes.
- Customizable touch button positions, sizes and opacity.
- Joystick and D-pad controls.
- Java multiplayer support.
- Resource pack support.
- ".hmod" mod import.
- Resolution scaling and rendering modes.
- Android keyboard and clipboard support.
- Audio through AAudio.
- Phone vibration support.
- Android Keystore integration.

Minecraft Compatibility

The underlying engine currently targets Minecraft Java Edition 26.3.

Mod Support

BRINX's current engine foundation supports:

- Sandboxed ".hmod" code mods on 64-bit APKs.
- Resource packs.
- The engine's supported content formats.

Important compatibility notes:

- ".hnmod" source-only mods are not currently supported on Android.
- Forge and Fabric Java mods do not run directly.
- Java ".jar" mods cannot be converted simply by changing their file extension.
- Multiplayer and anti-cheat compatibility depend on the individual server and require testing.

Android Experience

Gameplay

Touch Controls| D-pad Controls
"Joystick controls" (docs/media/android/joystick-fox.png)| "D-pad controls" (docs/media/android/dpad-river.png)

Snowy World| Multiplayer
"Snowy biome" (docs/media/android/snow-landscape.png)| "Multiplayer gameplay" (docs/media/android/hypixel-arcade.png)

Third Person| Desert World
"Third person gameplay" (docs/media/android/third-person-desert.png)| "Desert gameplay" (docs/media/android/desert-panorama.png)

BRINX Roadmap

Our long-term goal is to expand BRINX into a complete Minecraft mobile platform.

Planned features include:

- BRINX Mod Store — Discover and manage compatible mods.
- Mod Importer — Import and analyze mod files.
- AI Mod Porting — Research and assist with adapting compatible Java mod functionality.
- Skin Studio — Create and edit Minecraft skins.
- Cape Studio — Design and customize capes.
- Resource Pack Manager — Organize resource packs.
- Advanced Game Settings — Graphics, resolution, FPS, controls and performance.
- Server Browser — Discover and manage multiplayer servers.
- BRINX Accounts — Account and profile management.
- BRINX Chat — Text messaging, friends and groups.
- World Manager — Manage and back up worlds.

These are planned features, not claims that they are already available.

Performance & Settings

The project aims to provide flexible settings for different Android devices.

Planned configuration options include:

- Render distance.
- Resolution scaling.
- FPS limit.
- Graphics quality.
- VSync.
- Particles and visual effects.
- Battery-saving mode.
- Performance mode.
- Touch sensitivity and button layout.
- Audio settings.

Actual availability depends on engine support and device compatibility.

Development

BRINX is an Android-focused project built on a Rust-based game engine.

The underlying Android implementation uses native Android integration and Vulkan rendering.

For the original engine and its development history, see:

- "Horizon Engine" (https://github.com/ludovic111/horizon)
- "Starling Android Project" (https://github.com/JuanLuci/starling)

Contributing

Contributions, bug reports and suggestions are welcome.

Before submitting changes:

1. Check the existing project structure.
2. Keep changes compatible with Android.
3. Test on a real device whenever possible.
4. Document new features and known limitations.
5. Preserve upstream copyright and license notices.

License & Credits

BRINX uses and builds upon open-source software, including the Horizon engine and its Android implementation.

The original Horizon project is distributed under the MIT License. Original copyright notices, license terms and third-party notices must remain included in redistributed copies and substantial portions of the original software.

See:

- "License" (LICENSE)
- "Third-party notices" (THIRD_PARTY_NOTICES.md)
- "Horizon" (https://github.com/ludovic111/horizon)
- "Starling" (https://github.com/JuanLuci/starling)

Minecraft is a trademark of Mojang Synergies AB. All Minecraft assets and trademarks remain the property of their respective owners.

---

<p align="center">
  **BRINX Launcher**Built for Android. Designed for Minecraft.

</p>
