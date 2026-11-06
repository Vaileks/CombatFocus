<div align="center">

# Combat Focus

**Keep the important parts of your HUD in focus.**

`FABRIC` · `MINECRAFT 1.21.11` · `CLIENT-SIDE`

[Download](https://github.com/Vaileks/CombatFocus/releases/latest) · [Report an issue](https://github.com/Vaileks/CombatFocus/issues)

</div>

---

Combat Focus is a client-side Fabric mod by **Vaileks**.

## Features

- Hides selected scoreboard, bossbar and held-item-name elements during recorded PvP combat.
- Optionally hides the vanilla effect overlay.
- Keeps critical alerts from this mod series visible.

## Installation

1. Use **Minecraft Java 1.21.11**, **Fabric Loader 0.19.2+** and **Java 21+**.
2. Download `combat-focus-1.0.0+1.21.11.jar` from [Releases](https://github.com/Vaileks/CombatFocus/releases/latest).
3. Put the JAR in your client `mods` folder and start the game.

No server installation or Fabric API is required. The shared runtime is already bundled in the JAR, so this mod can be installed on its own or alongside other mods in the series.

## Configuration

Press **F8** or use the mod's settings button in **Mod Menu**. Mod Menu is optional.

Adjust the available colors, thresholds and feature controls in the settings screen. HUD panels support scale, shadow, background, item names or icons, and mouse placement where applicable. Save changes with **Done / Готово**. The action key is unbound by default to avoid conflicts; assign one in **Functions / Функции**.

Settings are stored in `config/combat_focus.json`.

## Compatibility notes

Controls vanilla elements and compatible panels from this series. It does not manage arbitrary third-party HUD mods. Health and hunger remain visible. Automatic combat detection depends on player-attributed damage packets.

## Русский

Combat Focus скрывает выбранные второстепенные элементы HUD во время PvP. Настраиваются scoreboard, bossbar, имя предмета и иконки эффектов; тревоги остаются.

Установка: Fabric **1.21.11**, Java **21+**. Поместите JAR в клиентскую папку `mods`. Настройки — **F8** или Mod Menu. Fabric API не требуется.

## Build

With JDK 21–25 and Python 3 installed:

```sh
./gradlew packageMods
```

Output: `dist/mods/combat-focus-1.0.0+1.21.11.jar`.

## License

[MIT](LICENSE).
