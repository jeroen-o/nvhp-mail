# NVHP Uitnodiging Generator

Tool om masterclass- en trainingsuitnodigingen in de NVHP-huisstijl op te maken
en te versturen. Werkt volledig in de browser — geen server of installatie nodig.

## Bestanden

- `index.html` — de generator (open dit bestand)
- `handleiding.html` — de handleiding (ook bereikbaar via de link in de tool)

Beide bestanden zijn standalone: alle opmaak, code en het logo zitten erin.
Ze werken ook offline door ze te dubbelklikken.

## Online zetten via GitHub Pages

1. Maak een nieuwe repository aan op github.com (bijv. `nvhp-uitnodiging`).
2. Upload `index.html`, `handleiding.html` en dit `README.md` (Add file → Upload files).
3. Ga naar **Settings → Pages**.
4. Kies bij *Source*: **Deploy from a branch**, branch **main**, map **/ (root)**. Save.
5. Na ongeveer een minuut staat de tool op:
   `https://<gebruikersnaam>.github.io/nvhp-uitnodiging/`

De handleiding is dan bereikbaar via `.../handleiding.html` en via de knop in de tool.

## Bijwerken

Wijzig de teksten of opmaak? Vervang `index.html` (en/of `handleiding.html`) in de
repository door de nieuwe versie. GitHub Pages werkt automatisch bij.
