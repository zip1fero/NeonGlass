# NeonGlass

> A glassmorphism Discord theme with neon pink and neon petrol accents.

NeonGlass turns Discord into frosted, see-through glass panels lit by **neon pink** and **neon petrol (teal)**. The pink takes selections, mentions and highlights; the petrol takes hovers, links and accents.

Works with **BetterDiscord** and **Vencord** (and Vencord-based clients like Vesktop / Equicord). Supports Discord's dark, darker, midnight and the new visual refresh UI.

**Best for:** Cyberpunk / synthwave setups and RGB gaming desks.

---

## Colour palette

| Colour | Value | Used for |
|---|---|---|
| Neon pink | `#ff2bd6` | selected items, mentions, primary glow |
| Neon petrol | `#00e5d4` | hovers, links, accents |
| Deep petrol | `#06333d` | dark base tone |
| Glass | `rgba(10, 22, 32, 0.38)` | main panel glass |
| Strong glass | `rgba(8, 16, 26, 0.58)` | sidebar, modals, popouts |

## What it changes

- **Frosted glass panels.** Server list, channel list, chat, member list and user panel turn transparent, with an 18px `backdrop-filter` blur, a thin light border and 14px rounded corners.
- **Message box.** Glass input field with an accent glow when focused.
- **Channels and messages.** Coloured hover and selected states, highlighted mentions and accent-coloured links.
- **Server icons.** Neon glow on hover, a stronger glow on the active server, and a glowing selection pill.
- **Modals, popouts, menus and tooltips.** Darker "strong glass" so they stay readable over the chat.
- **Buttons, switches and inputs.** Recoloured in the theme accents.
- **Status, badges and voice.** Recoloured status indicators, unread badges and voice UI.
- **Animated Home button.** The Discord Home button becomes an animated GIF icon with a pulsing **neon pink** neon glow.
- **Optional wallpaper.** Put any image behind the glass, with adjustable blur.

## Installation

### BetterDiscord
1. Download [`NeonGlass.theme.css`](https://raw.githubusercontent.com/zip1fero/NeonGlass/main/NeonGlass.theme.css) (right-click → *Save link as…*).
2. Open **User Settings → BetterDiscord → Themes → Open Themes Folder**. On Windows this is `%AppData%\BetterDiscord\themes`.
3. Drop the file in that folder and turn **NeonGlass** on.

### Vencord / Vesktop
**Online (updates automatically):** open **Settings → Vencord → Themes → Online Themes** and paste:

```
https://raw.githubusercontent.com/zip1fero/NeonGlass/main/NeonGlass.theme.css
```

**Local:** put the file in the Vencord themes folder (**Themes → Open Themes Folder**) and enable it.

## Notes

- Blur needs a wallpaper or something behind the panels to look its best. With no wallpaper, the glass sits on Discord's dark base.
- If you turn on **window transparency** (Vencord or BetterDiscord), some Discord/Electron builds stop rendering `backdrop-filter` blur. If the glass loses its blur, turn transparency off.
- Discord updates often rename internal classes. If something looks off after an update, open an issue.

## More themes in the set

[AuroraGlass](https://github.com/zip1fero/AuroraGlass) · [ObsidianGlass](https://github.com/zip1fero/ObsidianGlass)

## Author

Made by **sakis** ([zip1fero](https://github.com/zip1fero)).

## License

All rights reserved. Copying, modifying or redistributing this theme is not allowed. See [LICENSE](LICENSE).
