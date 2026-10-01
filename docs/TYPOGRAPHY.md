# Typography

**A premium celestial gaming brand that happens to be a Minecraft network** — not a Minecraft server website using a Minecraft font.

The Minecraft identity comes from the art: the pixel-art crown, pixel icons, stepped borders, gold UI details, illustrations and subtle block/grid patterns. It never comes from the type.

## Banned fonts

Never use Press Start 2P, Silkscreen, Minecraftia, or any 8-bit, pixel or blocky Minecraft-style font. Text is never pixelated.

## Families

| Role | Font | Weights | Used for |
| --- | --- | --- | --- |
| Display | **Sora** | 600, 700, 800 | DIVINE NETWORK / DIVINESMP, hero headings, section headings, large prices, major navigation labels |
| Text | **Manrope** | 400, 500, 600, 700 | Body, product descriptions, player names, statistics, navigation, form labels, buttons, FAQ, small UI text |

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Manrope:wght@400;500;600;700&family=Sora:wght@600;700;800&display=swap">
<link rel="stylesheet" href="styles/typography.css">
```

## Logo text

"DIVINE" / "DIVINE NETWORK" uses Sora 800, uppercase, large, with the gold gradient

`#FFF5C4 → #F5D875 → #E8C04F → #C99428`

and a subtle dark-gold drop shadow. Use `.logo-text` (or `.logo-text--sm` in the header). Always pair it with the **pixel-art** crown. The contrast between the crisp letterforms and the pixel crown is intentional.

## Classes (`styles/typography.css`)

| Class | Font / weight |
| --- | --- |
| `.logo-text` | Sora 800, gold gradient |
| `.hero-title` | Sora 800 |
| `.section-title`, `h1–h3` | Sora 700 |
| `.card-title` | Sora 600 |
| `.price` | Sora 800, tabular numbers |
| `.nav-primary` | Sora 600 (major nav) |
| `body`, `.faq-answer` | Manrope 400 |
| `.lead`, `.stat-label`, `.caption` | Manrope 500 |
| `.nav-link`, `.label`, `.faq-question` | Manrope 600 |
| `.btn`, `.player-name`, `.stat-value`, `.eyebrow` | Manrope 700 |

Open `index.html` for a live specimen.
