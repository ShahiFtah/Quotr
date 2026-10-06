# Quotr

Enkelt verktøy for tilbud og faktura med MVA. Ren HTML, CSS og JavaScript. Ingen server, ingen build, ingen eksterne avhengigheter.

## Filer
- `index.html` – salgsside
- `app.html` – selve verktøyet
- `vilkar.html` – vilkår og personvern
- `vendor/` – jsPDF (PDF), docx (Word), SheetJS (Excel)
- `assets/` – skrifttype (Bricolage Grotesque) og CSS for den

## Åpne lokalt
Dobbeltklikk `index.html`. Verktøyet fungerer også uten internett.

## Legg ut på GitHub Pages
1. Opprett et nytt repo på github.com (for eksempel `quotr`).
2. Last opp alle filene og mappene i denne mappen til repoet.
3. Gå til Settings → Pages. Velg «Deploy from a branch», branch `main` og mappe `/ (root)`. Trykk Save.
4. Etter ett til to minutter ligger siden på `https://BRUKERNAVN.github.io/quotr/`.
5. Eget domene: legg det inn under Settings → Pages → Custom domain, og pek DNS-oppføringen hos domeneleverandøren til GitHub.

## Før du deler den
- Skjemaet på salgssiden åpner e-postprogrammet til kunden (mailto). Endre adressen i `index.html` hvis du bytter e-post.
- Opplysningene lagres bare i brukerens egen nettleser. Det finnes ingen innlogging, og alle som har lenken kan bruke alt. Gratisgrense og Pro-funksjoner er ikke bygget inn.
- Les over `vilkar.html` og få den sjekket av en jurist før du tar betalt.

## Tredjepartsbiblioteker
jsPDF (MIT), docx (MIT), SheetJS Community Edition (Apache-2.0), Bricolage Grotesque (SIL Open Font License). Lisensteksten følger bibliotekene hos utgiverne.
