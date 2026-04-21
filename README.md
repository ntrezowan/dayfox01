# Dayfox01 — Chrome Theme

A Chrome browser theme ported from [EdenEast/nightfox.nvim](https://github.com/EdenEast/nightfox.nvim) (dayfox style).

Brings the dayfox light colour palette to Chrome's tab strip, toolbar, bookmarks bar, and new tab page. Designed to pair with **Nightfox01** — use Nightfox01 at night, Dayfox01 during the day.

---

## Palette

| Role            | Hex       | RGB             |
|-----------------|-----------|-----------------|
| Frame (tab bar) | `#e0d8ce` | 224, 216, 206   |
| Toolbar         | `#f6f2ee` | 246, 242, 238   |
| Active tab bg   | `#f6f2ee` | 246, 242, 238   |
| Inactive tab bg | `#d4cabb` | ~212, 202, 187  |
| Tab text        | `#3c2c3e` | 60, 44, 62      |
| Muted text      | `#8a7a6c` | 138, 122, 108   |
| Blue (links)    | `#2848a9` | 40, 72, 169     |
| Cyan            | `#287980` | 40, 121, 128    |
| Omnibox bg      | `#ede8e2` | 237, 232, 226   |
| Omnibox text    | `#3c2c3e` | 60, 44, 62      |

---

## What it colours

- Tab strip / frame (warm parchment tones)
- Active and inactive tabs
- Toolbar (address bar row)
- Bookmarks bar
- New tab page background, text, and links
- Omnibox background and text
- Incognito window frame

## What it does NOT colour

Chrome's theme API does not expose: omnibox dropdown, tab hover states, active tab indicator line, context menus, or Settings page internals.

---

## Pairing with Nightfox01

Chrome does not support automatic light/dark theme switching — that is a Chrome platform limitation. To use both:

1. Install both **Nightfox01** and **Dayfox01** from the Chrome Web Store
2. Switch manually via `chrome://extensions` or through **Settings → Appearance → Themes**
3. Click the theme you want active — Chrome applies it instantly, no restart needed

---

## Install (unpacked / developer mode)

1. Download and unzip `dayfox01-chrome-theme.zip`
2. Go to `chrome://extensions`
3. Enable **Developer mode** (top right toggle)
4. Click **Load unpacked** → select the `dayfox01-chrome-theme` folder
5. Theme applies immediately

## Install (Chrome Web Store)

Search **Dayfox01** on the [Chrome Web Store](https://chromewebstore.google.com) and click **Add to Chrome**.

---

## Related ports

| App      | Theme / Port                              |
|----------|-------------------------------------------|
| Neovim   | [EdenEast/nightfox.nvim](https://github.com/EdenEast/nightfox.nvim) |
| VS Code  | keifererikson.nightfox (Marketplace)      |
| iTerm2   | dayfox extra in nightfox.nvim repo        |
| Obsidian | markmacode/obsidian-nightfox              |
| Chrome   | **Dayfox01** (this) + **Nightfox01**      |

---

## License

MIT — same as the upstream nightfox.nvim project.

Palette © EdenEast, used with permission under MIT.
