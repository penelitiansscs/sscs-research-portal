# DESIGN.md - SSCS Brand & Design Tokens

## Brand Identity
- **Product**: SSCS (Smart Stunting Care System)
- **Logo**: `logo 2.jpeg` (icon stack, tanpa tagline teks)
- **Logo 1** hanya untuk full lockup (footer, kop dokumen, login page)

## Color Palette (extracted from logo)

### Primary
| Token | Hex | HSL | Usage |
|---|---|---|---|
| `--brand` | `#00B4D7` | `hsl(190, 100%, 42%)` | Icon S-S-C-S, accent utama, CTA |
| `--brand-dark` | `#009BB8` | `hsl(190, 100%, 36%)` | Hover states, emphasis |
| `--brand-light` | `#E6F8FB` | `hsl(190, 70%, 94%)` | Icon bg tint, highlight area |
| `--brand-muted` | `#B8E8F0` | `hsl(190, 55%, 83%)` | Borders on brand elements |

### Neutral (dari charcoal wordmark)
| Token | Hex | HSL | Usage |
|---|---|---|---|
| `--neutral-900` | `#1F2933` | `hsl(207, 25%, 16%)` | Heading teks utama |
| `--neutral-700` | `#414143` | `hsl(240, 1%, 26%)` | Body teks |
| `--neutral-500` | `#616E7C` | `hsl(209, 12%, 44%)` | Deskripsi, secondary text |
| `--neutral-300` | `#CBD2D9` | `hsl(210, 14%, 80%)` | Borders |
| `--neutral-200` | `#E4E7EB` | `hsl(214, 13%, 91%)` | Dividers |
| `--neutral-100` | `#F0F2F5` | `hsl(216, 16%, 95%)` | Page background |
| `--neutral-50`  | `#F7F8FA` | `hsl(220, 18%, 97%)` | Card background |
| `--white`       | `#FFFFFF` | `hsl(0, 0%, 100%)`   | Surface card |

## Rules

1. **JANGAN pakai warna kategori acak** (pelangi arbitrer untuk badge).
   Semua warna section badge diturunkan dari primary teal (tint/shade).
2. **JANGAN pure black (#000) atau pure gray (#808080)**.
   Selalu gunakan warm/cool-tinted neutral dari palette di atas.
3. **Icon stroke color**: gunakan `--brand` atau `--neutral-700`, BUKAN flat gray.
4. **Icon container background**: `--brand-light` (teal 10% opacity feel).
5. **Font**: DM Sans. Tidak boleh diganti ke Inter/Arial/system.
6. **Hierarchy**: section yang berbeda level harus punya bobot visual berbeda.
7. **Contrast minimum**: WCAG AA (rasio >= 4.5:1 untuk teks kecil).
