# Asteroid Spawn Limiter

Asteroid Spawn Limiter is a simple mod for [Kerbal Space Program (KSP)](https://kerbalspaceprogram.com) that prevents the game from spawning excessive asteroids. It ensures a cleaner solar system and helps reduce performance impact by capping the number of untracked asteroids generated over time.

Ideal for [Luna Multiplayer](https://lunamultiplayer.com/), this mod helps you completely suppress uninvited rock visitors.

## 📦 Features

- Cleanup on Awake: Excess untracked asteroids and comets are now automatically removed when the game starts.
- Limits random asteroid generation to 3 asteroids and 2 comets
- Lightweight, non-invasive plugin
- Compatible with KSP 1.12.x
- Designed for use with stock and modded games


## ⚙️ Dependencies

- **Harmony** — Required for patching game methods to limit asteroid and comet spawning.  

> **Note:**  
> Harmony is typically installed automatically by CKAN or mod managers.  

## 🔧 Installation

1. Download the latest release from the [GitHub Releases page](https://github.com/kevnokeeffe/AsteroidSpawnLimiter/releases/tag/v1.0.0).
2. Extract the ZIP file.
3. Copy the `GameData/AsteroidSpawnLimiter/` folder into your KSP `GameData/` directory.

## 🤝 Works Well With
[AsteroidCleaner](https://github.com/kevnokeeffe/AsteroidCleaner) — This mod complements Asteroid Spawn Limiter by continuously cleaning up excess untracked asteroids and comets during gameplay, ensuring your game stays performant and tidy even after spawning is limited.

## 🔄 Compatibility

- Tested on KSP 1.12.5
- Compatible with most mods

## 📜 License

This mod is licensed under the MIT License. See [LICENSE](./License.md) for details.

## 💬 Feedback & Contributions

Bug reports, feature requests, and pull requests are welcome!  
Visit the [GitHub repo](https://github.com/kevnokeeffe/AsteroidSpawnLimiter) to contribute or report an issue.
