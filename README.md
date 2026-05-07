# NL-Vapen

Een informatieve, Nederlandstalige single-page website over waarom vapen schadelijk is voor jongeren van 12-18 jaar.

## Inhoud

De website bevat onder andere:
- uitleg over gezondheidsrisico’s en verslaving;
- factoren die vapen aantrekkelijk maken voor jongeren;
- een interactieve kostenberekening per maand/jaar;
- een ingebouwde muziekspeler (flyout);
- verwijzingen naar gebruikte bronnen.

## Projectstructuur

- `index.html` – volledige pagina (layout, styling en JavaScript).
- `hero.png` – hero-afbeelding.
- `song.mp3` – audiobestand voor de speler.
- `favicon.ico` – favicon.
- `wrangler.jsonc` – Cloudflare-configuratie voor static assets.

## Lokaal bekijken

Omdat dit een statische pagina is, kun je `index.html` direct openen in je browser.

Voor een lokale server (optioneel):

```bash
python3 -m http.server 8080
```

Open daarna: `http://localhost:8080`

## Deploy

Deze repository bevat een `wrangler.jsonc` met:
- projectnaam: `nl-vapen`
- compatibiliteitsdatum: `2026-02-21`
- assets-map: `./`

Dat betekent dat de root van de repository als statische assets wordt gepubliceerd.

## Licentie

Dit project is gelicenseerd onder de **GNU General Public License v3.0**. Zie `LICENSE`.
