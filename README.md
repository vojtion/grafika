# Kompletní balíček – kurz designu (v4, Netlify-ready)

- `index.html` – opravený: SP obrázky (`SP1-100.png`, `SP2-101.png` atd.), fialový chip „SP“, robustní načítání `./data.json` + chybová hláška.
- `data.json` – vygenerováno z posledního Excelu, včetně prezentací a vazeb na materiály.
- `lekce_standard.csv`, `materialy_standard.csv` – exporty pro kontrolu.
- `logo-stepit.svg` (+ fallback `logo-stepit.png`).
- `images/` – složka pro náhledy.

Nasazení: nahraj obsah složky na Netlify tak, aby `index.html` a `data.json` byly vedle sebe. Po publishi zkontroluj v DevTools → Network, že `./data.json` vrací 200 OK.
