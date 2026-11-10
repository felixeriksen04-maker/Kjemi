# Kjemiruta

Læringssti gjennom hele pensum i Kjemi for navigatører. Pensum er delt i 14 veipunkter, fra atomet til sikkerhet om bord, der hvert veipunkt bygger på det forrige.

Kjemiruta er et uoffisielt studiehjelpemiddel. Det er ikke laget eller godkjent av skolen. Står noe her i strid med kompendiet eller faglæreren, er det de som gjelder.

## Innhold

- **Veipunktene** starter med «Kort fortalt», og forklarer med hverdagsbilder og regneeksempler steg for steg.
- **Oppgaver** fra grunnleggende til utfordring. Tallsvar sjekkes med en gang, og alle oppgavene har hint og løsning.
- **Generalprøve:** en hel prøveeksamen med løsningsforslag, sensorveiledning og poengteller.
- **Verktøy:** pugg-kort, jukselapp, periodesystem med kalkulator for molar masse, verksted for å balansere reaksjoner og en interaktiv spenningsrekke.
- **App på mobilen:** siden kan legges til på hjemskjermen og virker uten nett etter første besøk.

## Publiser med GitHub Pages

1. Lag et nytt, offentlig repository på GitHub.
2. Last opp alle filene i denne mappen. På github.com velger du «Add file» og så «Upload files». Du kan også pushe med git, se under.
3. Gå til «Settings» og så «Pages». Under «Build and deployment» velger du «Deploy from a branch», branch `main` og mappen `/ (root)`. Trykk «Save».
4. Etter et par minutter ligger appen på `https://BRUKERNAVN.github.io/REPONAVN/`.

Med git, fra denne mappen:

```bash
git init
git add .
git commit -m "Kjemiruta"
git branch -M main
git remote add origin https://github.com/BRUKERNAVN/REPONAVN.git
git push -u origin main
```

## Kjør lokalt

Åpne `index.html` i nettleseren. Installasjon som app og bruk uten nett virker bare når siden ligger på en ekte nettadresse, som GitHub Pages.

## Personvern

Ingen sporing og ingen innlogging. Framdrift, svar og poeng lagres bare i nettleseren til den som bruker siden. Skriftene lastes fra Google Fonts.

## Filer

| Fil | Innhold |
| --- | --- |
| `index.html` | Hele appen: HTML, CSS og JavaScript i én fil |
| `manifest.webmanifest` | Navn, farger og ikoner når appen installeres |
| `sw.js` | Lagrer appen slik at den virker uten nett |
| `icon.svg`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` | Ikoner |
