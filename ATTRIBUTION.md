# Attribution and sources

Everything in `assets/` is self-contained: fonts and images are embedded as base64 data URIs, all artwork is drawn with inline SVG, and no file makes a network request when rendered.

## Fonts

| Family | Weights embedded | Licence | Licence file |
| --- | --- | --- | --- |
| Space Grotesk (display) | 400, 500, 700 | SIL Open Font License 1.1 | `licenses/OFL-SpaceGrotesk.txt` |
| JetBrains Mono (mono) | 400, 700 | SIL Open Font License 1.1 | `licenses/OFL-JetBrainsMono.txt` |

Both were fetched from the Google Fonts repository (`google/fonts`), instanced to static weights, subset to the glyphs used, and embedded as base64 WOFF2 inside each SVG.

## Brand marks

Icons are used to identify the technologies and platforms they belong to. Each remains the property of its owner.

| Icon | Colour used | Source |
| --- | --- | --- |
| Python | `#3776AB` | https://www.python.org/community/logos/ |
| C | `#A8B9CC` | https://commons.wikimedia.org/wiki/File:The_C_Programming_Language_logo.svg |
| C++ | `#00599C` | https://github.com/isocpp/logos/tree/64ef037049f87ac74875dbe72695e59118b52186 |
| C# | `#512BD4` | https://github.com/simple-icons/simple-icons/blob/12.4.0/icons/csharp.svg |
| HTML5 | `#E34F26` | https://www.w3.org/html/logo/ |
| CSS | `#663399` | https://github.com/CSS-Next/logo.css/blob/bacc20878227204b283c68a6b935f8279e06b0cd/css.svg |
| JavaScript | `#F7DF1E` | https://github.com/voodootikigod/logo.js/blob/1544bdeed6d618a6cfe4f0650d04ab8d9cfa76d9/js.svg |
| TypeScript | `#3178C6` | https://www.typescriptlang.org/branding |
| React | `#61DAFB` | https://github.com/facebook/create-react-app/blob/282c03f9525fdf8061ffa1ec50dce89296d916bd/test/fixtures/relative-paths/src/logo.svg |
| Next.js | `#000000` | https://vercel.com/design/brands#next-js |
| FastAPI | `#009688` | https://github.com/tiangolo/fastapi/blob/ffb4f77a11f83132b521ba0aac6c95792c19e797/docs/en/docs/img/icon-white.svg |
| PostgreSQL | `#4169E1` | https://wiki.postgresql.org/wiki/Logo |
| Supabase | `#3FCF8E` | https://github.com/supabase/supabase/blob/4031a7549f5d46da7bc79c01d56be4177dc7c114/packages/common/assets/images/supabase-logo-wordmark--light.svg |
| Redis | `#FF4438` | https://redis.io/brand-guidelines |
| Git | `#F03C2E` | https://git-scm.com/community/logos |
| GitHub | `#181717` | https://github.com/logos |
| WordPress | `#21759B` | https://wordpress.org/about/logos |
| Blynk | `#23C48E` | https://blynk.io — inline header logo mark, retrieved 2026-10-09 |
| Cloudinary | `#3448C5` | https://cloudinary.com |
| LinkedIn | `#0A66C2` | https://github.com/simple-icons/simple-icons/blob/13.21.0/icons/linkedin.svg (upstream source: https://brand.linkedin.com) |
| Instagram | `#FF0069` | https://about.meta.com/brand/resources/instagram |
| Facebook | `#0866FF` | https://about.meta.com/brand/resources/facebook/logo |

### Notes on two marks

- **C#** and **LinkedIn** were removed from current Simple Icons releases, so the pinned Simple Icons files above (v12.4.0 and v13.21.0) were used; LinkedIn’s upstream source is <https://brand.linkedin.com>.
- **Blynk** is not in Simple Icons, so the official mark was taken from the inline logo in the header of <https://blynk.io> (retrieved 2026-10-09).

## Photography

`assets/hero.svg` and `assets/id-dashboard.svg` embed a resampled (never redrawn or masked) copy of `id.png`; `assets/connect.svg` embeds a resampled copy of `right_pointing.png`. Alpha channels are preserved exactly as supplied.
