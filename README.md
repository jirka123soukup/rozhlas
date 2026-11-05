# Rozhlas stahovač

Webová aplikace pro stahování pořadů Českého rozhlasu (rozhlas.cz i mujrozhlas.cz) přímo do telefonu.
Je to jen statická stránka: bez serveru, bez účtů, všechno běží v prohlížeči.

## Nasazení na GitHub Pages (zdarma, ~5 minut)

1. Na <https://github.com/new> vytvoř repozitář, např. `rozhlas` (Public).
2. Na stránce repozitáře klikni **Add file → Upload files** a nahraj všechny soubory z této složky
   (`index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`). Potvrď **Commit changes**.
3. **Settings → Pages** → *Source: Deploy from a branch*, *Branch: `main` / `(root)`* → **Save**.
4. Za minutu je aplikace na `https://<tvé-jméno>.github.io/rozhlas/`.

## Instalace do telefonu (Chrome na Androidu)

1. Otevři adresu z kroku 4.
2. Menu ⋮ → **Přidat na plochu** → **Instalovat**.
3. Hotovo. Aplikace je na ploše a v nabídce **Sdílet** (např. z aplikace mujRozhlas) se objeví jako **Rozhlas**.

Stažené díly najdeš ve **Stažených souborech** (`Download`).

## Úpravy

Při změně souborů je stačí znovu nahrát na GitHub. Aplikace si novou verzi načte sama při příštím otevření s připojením.
Lokální test na Macu: `python3 -m http.server 8765` v této složce a otevřít <http://localhost:8765>.
