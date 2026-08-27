# Foto's — wat staat erop & waar hoort het

Alle beelden staan in `./images/`. Hieronder per bestand: wat erop staat en de
voorgestelde plek op de homepage. Dit is een leidraad — kijk zelf naar de foto
en beslis wat het mooiste werkt.

## Sfeer- & begeleidingsfoto's (leerlingen aan het werk)

| Bestand | Wat staat erop | Voorgestelde plek |
|---|---|---|
| `2_KLANTEN.jpg` | Liggend. Twee leerlingen op de roze bank met laptop en boek, plantje ernaast. | **Hero** (hoofdbeeld) of sfeerblok |
| `KLANTEN_2.jpg` | Liggend. Vergelijkbaar: twee leerlingen, laptop, telefoon, boek. | Alternatief hero / diensten-sfeer |
| `_STI8936.jpg` | Staand. Close-up van twee leerlingen die samen in een atlas wijzen. | **Hero-inset** (klein kader) of detailblok |
| `AEST.jpg` | Staand. Detailshot van handen met een boek. | Klein detail-/tussenbeeld |
| `AMIN_X_ENZO.jpg` | Staand. Begeleider (baard, navy trui) lacht naast leerling met laptop. | **Onze aanpak** (warm, 1‑op‑1) |
| `AMIN_X_HAITAM.jpg` | Staand. Twee personen staand met de Bosatlas. | Diensten / studiebegeleiding |
| `AMIN_X_KLANTEN.jpg` | Staand. Begeleider in gesprek met twee leerlingen op de bank. | **Over ons** / begeleiding in actie |
| `AMIN_X_KLANTEN_2.jpg` | Staand. Zelfde gesprek, andere hoek. | Aanpak / alternatief |

## Teamportretten (professioneel, egale achtergrond)

| Bestand | Wat staat erop |
|---|---|
| `Mo.jpg` | Jonge man, korte krul, cream/navy jack. |
| `Latta.jpg` | Man in pak met stropdas (formeel). |
| `PF_1_.jpg` | Man in zwart zip-jack, lachend. |
| `PF_4.jpg` | Man in navy trui, lachend. |
| `PF_5.jpg` | Man in navy trui, armen over elkaar, serieuzer. |

> Let op: `Latta`, `PF_1_`, `PF_4` en `PF_5` lijken (deels) dezelfde persoon in
> verschillende outfits; `Mo` is een ander persoon. **Namen en rollen door de
> klant laten bevestigen.** Gebruik voor de teamsectie de 2–4 sterkste portretten.

## Logo's

| Bestand | Gebruik |
|---|---|
| `logo-transparant.png` | Navigatiebalk, footer, op lichte/beige achtergrond. |
| `logo-beige.png` | Vierkant met beige achtergrond — social media / profielfoto. |

## Waar de placeholders nu zitten in `index.html`

De huidige pagina heeft nog placeholder-beeldvlakken (grijsgroene vlakken met een
klein lijntekeningetje). Deze herken je aan de klassen `.photo`, `.ph-motif`
(de SVG-tekening) en `.ph-label` (het tekstlabel). Vervang die door echte `<img>`.

1. **Hero hoofdbeeld** — `.photo.hero-main`
2. **Hero-inset** — `.photo.hero-inset`
3. **Aanpak-beeld** — `.approach-visual .photo` (met de "100% aandacht"-badge eroverheen)
4. **Team-avatar** in "Over ons" — `.team-av` (rond)
5. **Nieuw: volwaardige teamsectie** met de portretten hierboven.
