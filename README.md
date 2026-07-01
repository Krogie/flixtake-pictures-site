# Flixtake Pictures — Prototyp (A24-Stil + Admin)

Editorial-minimalistischer Film-Auftritt im Stil von a24films.com + cleanes Admin-Dashboard.

## Seiten
- `index.html` — Startseite. **A24-Vollbild-Hero** (durchwechselnde Titel-Liste unten links,
  Hover/Auto-Cycle wechselt den Hintergrund), Logo „FLIXTAKE PICTURES" in cleaner Grotesk,
  darunter „Alle Filme"-Masonry-Raster mit Hover-Credits, Studio, Newsletter, Footer.
- `login.html` — Flixtake-Pictures-Konto-Login → Konto-Ansicht mit „Admin-Dashboard öffnen"-Button.
- `admin.html` — cleanes Wix-artiges Dashboard: Sidebar, Kennzahlen, Film-Tabelle mit
  Status-Badges, Bearbeiten-Drawer, „Veröffentlichen".

## Ansehen
- Launch-Preview-Panel, oder Server (`.claude/launch.json`, Node, Port 4321) → http://127.0.0.1:4321
- Oder Dateien direkt im Browser öffnen.

## WICHTIG: Status = Design-Prototyp
- **Login & Admin sind MOCKS** — keine echte Authentifizierung, keine Speicherung.
  Eingaben/„Speichern"/„Veröffentlichen" zeigen nur die UI, ändern die Website (noch) nicht.
- Film-Stills sind **CSS-Platzhalter** (Verlauf + Filmkorn) — für echte Stills/Key-Art gedacht.

## Nächster Schritt (um es echt zu machen)
Port nach **Next.js (App Router, Vercel)** + echte **Auth** (Login mit Flixtake-Konto, Rollen)
+ **Datenbank/CMS** (Filme im Admin bearbeiten → live auf der Website). Siehe `../RELAUNCH-PLAN.md`.

## Hinweise
- Fonts: Archivo (clean Grotesk). Kein `innerHTML`, `prefers-reduced-motion` respektiert.
- Titel/Format/Jahr aus Recherche; Credits nur wo belegt; „Viertel vor nach" weggelassen.
