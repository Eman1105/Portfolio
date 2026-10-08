# Responsive Portfolio

## Om projektet

Det här projektet är en personlig portfolio som jag har byggt i kursen **Webbutveckling nivå 2**. Syftet är att presentera mig själv, mina kunskaper och några projekt som jag har arbetat med under min utbildning.

Webbplatsen består av fyra sidor:

* **Hem** – kort presentation och introduktion.
* **Om mig** – information om mig och mina kunskaper.
* **Projekt** – visar några projekt och programmeringsuppgifter.
* **Kontakt** – kontaktinformation och kontaktformulär.

Jag har använt HTML och CSS och fokuserat på att sidan ska fungera på mobil, tablet och dator.

## Responsiv design och breakpoints

Jag började med en **mobile-first** layout. Det betyder att sidan först är byggd för små skärmar.

Jag använder främst två breakpoints:

* **700px** – navigationen ändras från en vertikal layout till en horisontell layout. Projekt och annat innehåll får också mer plats.
* **1050px** – projektkorten får plats i tre kolumner på större skärmar.

Jag valde dessa breakpoints eftersom layouten började behöva mer plats när skärmen blev bredare. Jag testade sidan genom att ändra fönstrets storlek och kontrollerade även mellanlägen.

## Flexbox

Jag använder **Flexbox** bland annat för navigationen. På mobil ligger länkarna under varandra och på större skärmar ligger de bredvid varandra.

Jag använder också Flexbox för att placera och anpassa vissa delar av innehållet.

## CSS Grid

Jag använder **Grid** framför allt på projektsidan. Projektkorten visas först i en kolumn på mindre skärmar. På större skärmar ändras layouten till två eller tre kolumner.

Det gör att projekten får en tydlig och responsiv layout.

## Två problem som jag löste

### Problem 1 – Navigationen passade inte på större skärmar

**Problem:** Navigationen blev lång och tog mycket plats när skärmen var bredare.

**Observation:** Jag såg att länkarna låg under varandra även när det fanns mycket plats på skärmen.

**CSS:** Jag använde Flexbox och en `min-width` media query.

**Ändring:** Vid 700px ändrade jag navigationen till en horisontell layout.

**Test:** Jag testade sidan genom att göra webbläsarfönstret större och mindre.

**Förklaring:** På mindre skärmar fungerar en vertikal navigation bättre, medan en horisontell navigation passar bättre på större skärmar.

### Problem 2 – Projektkorten blev för smala

**Problem:** Projektkorten fick för lite plats när flera kort låg bredvid varandra.

**Observation:** Jag såg att text och bilder blev för trånga.

**CSS:** Jag använde CSS Grid med olika antal kolumner vid olika bredder.

**Ändring:** På mobil används en kolumn, vid 700px används två kolumner och vid 1050px används tre kolumner.

**Test:** Jag testade projektkorten genom att ändra skärmens storlek.

**Förklaring:** På detta sätt får varje projekt tillräckligt med plats och sidan fungerar på olika skärmar.

## Tillgänglighet och testning

Jag har testat att:

* länkarna fungerar
* bilderna har `alt`-texter
* sidan fungerar på mobil och dator
* layouten inte skapar onödig horisontell scroll
* hover och focus syns på länkar
* formulärets fält har labels
* HTML och CSS är validerade
* navigationen fungerar på alla sidor

## Verktyg

Jag har använt:

* HTML5
* CSS3
* Flexbox
* CSS Grid
* Media Queries
* Visual Studio Code
* Chrome DevTools
* GitHub

## Slutsats

Målet med projektet var att skapa en enkel och responsiv portfolio. Under arbetet har jag fått mer förståelse för semantisk HTML, CSS, Flexbox, Grid och responsive design. Jag har också tränat på att hitta problem genom DevTools och lösa dem genom att testa och ändra koden.
