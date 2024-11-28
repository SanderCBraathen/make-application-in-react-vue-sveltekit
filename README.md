# How to make an application using React/Vue/SvelteKit

## What you will learn
- How to install Node.js.
- Use npm for different packages.
- How to use the terminal and navigate around in your project.
- How to set up a new project using Vite and a framework (React, Vue, SvelteKit).
- How to install dependencies and run your application.
- How to make changes to your project using visual studio code.

---

## Intro

### Make a folder for your project
- Open **File Explorer**.
- Find out where you want to place your project.
- Right click,  **Ny fil** eller **Ny mappe**, og gi den et navn.

---

### Installer en pakkebehandler (Node.js)
For å bruke `npm` må du først installere **Node.js**, som inkluderer `npm` (Node Package Manager):
1. Gå til [Node.js sin offisielle nettside](https://nodejs.org/).
2. Last ned **LTS-versjonen** (Long Term Support) for stabilitet.
3. Kjør installasjonsfilen og følg instruksjonene.
4. Bekreft installasjonen:
   - Åpne terminalen og skriv:
```
node -v
npm -v
```
   - Du skal se versjonsnumre for både Node.js og npm.

---

### Åpne terminalen og naviger til mappen
- Åpne **Command Prompt** (Windows):
  - Trykk på **Start**, skriv inn "Command Prompt", og åpne programmet.
- Naviger til mappen du nettopp opprettet ved å skrive:
  bash
  cd <sti-til-mappen>
  Eksempel:
  bash
  `cd C:\Users\Pc\React`
- Hvis du får en feilmelding, sett stien i anførselstegn:
  `
  cd "C:\Users\Pc\React"
  `

---

## Oppsett

### Opprett prosjektet med Vite
- Når du er i riktig mappe i terminalen, skriv:
  bash
  `npm create vite@latest`
- Følg instruksjonene:
  - Du vil se:
    ```
    Project name: » vite-project
    ```
    Skriv inn et ønsket navn på prosjektet ditt og trykk **Enter**.
  - Deretter ser du:
    ```
    Package name:
    ```
    Trykk **Enter** for å godta standardverdien.
  - Velg rammeverk:
    - Du får en liste over alternativer som ser slik ut:
      ```
      Select a framework: » - Use arrow-keys. Return to submit.
        Vanilla
        Vue
        React
        Preact
        Lit
        Svelte
        Solid
        Qwik
        Angular
        Others
      ```
    - Bruk piltastene til å navigere og trykk **Enter** for å velge.
  - Avhengig av valget ditt, vil du få flere alternativer:
    - For eksempel, hvis du velger **React**, vil du se:
      ```
      Select a variant: » - Use arrow-keys. Return to submit.
      TypeScript
      TypeScript + SWC
      JavaScript
      JavaScript + SWC
      Remix
      ```

---

## Installering

### Installer prosjektet
- Etter å ha opprettet prosjektet, kopier og lim inn følgende kommandoer i terminalen:
  bash
  cd <prosjektmappe>
  bash
  npm install
  bash
  npm run dev

- Når du kjører `npm run dev`, vil terminalen vise noe slikt:
  `Local: http://localhost:3000/`
- Hold inne **Ctrl** og klikk på linken for å åpne applikasjonen i nettleseren.

---

## Endringer

### Rediger prosjektet
- Du kan bruke en kode-editor som **Visual Studio Code (VS Code)** for å redigere prosjektet.
- Åpne prosjektmappen i VS Code:
- Gå til `src`-mappen for å finne de viktigste filene, som:
  - `App.tsx` (React)
  - `App.vue` (Vue)
  - `App.svelte` (Svelte)
- Her kan du legge til eller endre komponenter, CSS-stiler og funksjonalitet.
- Hvis du vil stoppe serveren midlertidig, trykk `Ctrl + C` i terminalen og bekreft med `y`.

---

## Tips
- Ikke bekymre deg for filer i `node_modules`. Dette er avhengigheter som prosjektet bruker, og du trenger vanligvis ikke å endre noe her.
- Lagre ofte, og sjekk nettleseren for å se endringer live.
