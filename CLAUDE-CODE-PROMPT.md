# Prompt voor Claude Code

> Open deze map (`deleervrienden/`) in Claude Code en plak de tekst hieronder.
> Alles wat Claude Code nodig heeft — `index.html`, de map `images/` en
> `FOTO-PLAATSING.md` — staat er al.

---

Dit is de homepage van **De Leer Vrienden** (studiebegeleiding, Cito- en
examentraining in Ridderkerk). De pagina staat in `index.html` — één bestand met
alle CSS en JS erin. De huisstijl is **beige `#FFFAE2`** als achtergrond en
**groen `#27953A`** als accent; die blijven ongewijzigd.

In de map `images/` staan de echte foto's en de logo's. In `FOTO-PLAATSING.md`
staat per foto beschreven wat erop staat en waar het ongeveer hoort.

**Wat ik van je wil:**

1. **Bekijk elke foto in `images/` daadwerkelijk** (open ze) en bepaal op basis
   van de inhoud de beste plek. Gebruik `FOTO-PLAATSING.md` als leidraad, maar
   denk zelf mee — kies de sterkste foto per plek.

2. **Vervang alle placeholder-beeldvlakken door echte foto's.** De placeholders
   herken je aan de klassen `.photo`, `.ph-motif` (een klein SVG-lijntekeningetje)
   en `.ph-label` (tekstlabel). Verwijder die SVG's en labels en zet er `<img>`
   in. Concreet:
   - **Hero hoofdbeeld** (`.photo.hero-main`) → een sterke sfeerfoto van
     leerlingen aan het werk (bijv. `2_KLANTEN.jpg` of `AMIN_X_KLANTEN.jpg`).
   - **Hero-inset** (`.photo.hero-inset`) → een detailfoto (bijv. `_STI8936.jpg`).
   - **Aanpak-beeld** (`.approach-visual .photo`) → een warme 1‑op‑1 begeleidings-
     foto (bijv. `AMIN_X_ENZO.jpg`). Laat de groene **"100% aandacht"-badge**
     eroverheen staan.
   - **Team-avatar** (`.team-av`, het ronde vlakje in "Over ons") → een passend
     portret of begeleidingsfoto.

3. **Bouw een echte teamsectie.** Er zijn professionele portretten
   (`Mo.jpg`, `Latta.jpg`, `PF_1_.jpg`, `PF_4.jpg`, `PF_5.jpg`). Maak een nette,
   responsieve "Ons team"-sectie (kaartjes met foto, naam, rol) in dezelfde
   huisstijl, en plaats die logisch tussen "Over ons" en "Ervaringen". Gebruik de
   2–4 sterkste portretten. Zet **naam en rol als duidelijke placeholder** met een
   `<!-- TODO: naam/rol bevestigen -->` erbij, want die moeten door de klant
   bevestigd worden (`Mo` en `Latta` zijn losse personen; `PF_*` lijkt dezelfde
   persoon in andere outfits).

4. **Logo's:** gebruik `images/logo-transparant.png` in de navigatiebalk en de
   footer (het staat er nu als base64 in — vervang dat gerust door een verwijzing
   naar dit bestand zodat het onderhoudbaar wordt).

**Technische eisen:**
- Alle foto's met `object-fit: cover` binnen hun kader, zodat niets vervormt.
- Behoud de bestaande beeldverhoudingen van de kaders (hero 4/5, inset 1/1,
  aanpak 3/4). Pas desnoods de CSS licht aan voor een mooie uitsnede.
- `loading="eager"` voor het hero-beeld, `loading="lazy"` voor de rest;
  `decoding="async"`; zinnige `width`/`height` om layout shift te voorkomen.
- Nederlandse, beschrijvende `alt`-teksten.
- **Raak de rest niet aan:** teksten, de meerstaps-vragenlijst (met de
  branchende logica), de FAQ-accordion en de testimonial-carousel blijven werken
  zoals ze zijn.
- Houd het volledig responsive (mobiel + desktop) en toegankelijk (zichtbare
  focus, `prefers-reduced-motion` gerespecteerd).

**Werkwijze:** loop eerst kort de foto's langs en vertel welke foto je op welke
plek zet (korte lijst). Pas daarna `index.html` aan. Laat aan het eind zien wat
je gewijzigd hebt en hoe ik het lokaal kan bekijken.
