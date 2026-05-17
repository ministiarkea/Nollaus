# 🪺 Linnunpesä — Siivousrutiinit

Yksinkertainen, selainpohjainen siivousappi 56m² kotiin, 6 hengelle.

## Ominaisuudet

- **Päivittäinen lista** — Aamu / Päivä / Ilta / Yö -tehtävät aikamerkintöineen
- **Suursiivouslista** — Huoneittain jaoteltu kuukausittainen siivouslista
- **Edistyminen** — Prosenttiympyrä ja laskuri, motivoi tekemään!
- **Muisti** — Tallentuu automaattisesti selaimen localStorage:een
- **Nollaus** — Nollaa päivä tai kuukausi napista

## Käyttö

Avaa `index.html` suoraan selaimessa — ei asennusta, ei palvelinta.

## GitHub Pages -käyttöönotto

1. Luo uusi repo GitHubissa
2. Lisää tiedostot:
   ```
   git init
   git add index.html README.md
   git commit -m "Ensimmäinen versio"
   git remote add origin https://github.com/KÄYTTÄJÄNIMI/linnunpesa.git
   git push -u origin main
   ```
3. Mene Settings → Pages → Source: `main` branch → Save
4. Sovellus on käytettävissä osoitteessa `https://KÄYTTÄJÄNIMI.github.io/linnunpesa`

## Muokkaus

Kaikki tehtävät ovat `index.html`-tiedostossa muuttujissa `DAILY_TASKS` ja `MONTHLY_ROOMS`. Voit lisätä huoneita tai tehtäviä suoraan sinne.
