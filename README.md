# BomenMon

Statische one-page website voor BomenMon, gehost op GitHub Pages.

- `index.html` – de volledige pagina (HTML + CSS)
- `assets/` – logo en iconen (SVG)

## Lokaal bekijken

```bash
python3 -m http.server 8766
```

Open daarna http://localhost:8766.

## Publiceren op GitHub Pages

1. Push deze map naar een GitHub-repository.
2. Ga naar **Settings → Pages**, kies **Deploy from a branch**, branch `main`, map `/ (root)`.
3. De site staat na een minuutje op `https://<gebruikersnaam>.github.io/<repo>/`.

Eigen domein (bomenmon.be): vul het in onder **Settings → Pages → Custom domain** en zet bij de domeinprovider een `CNAME`-record voor `www` naar `<gebruikersnaam>.github.io`.
