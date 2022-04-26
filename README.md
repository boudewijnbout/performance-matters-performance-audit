# 📚 ScrollBook Performance Audit

<img width="800" src="https://github.com/boudewijnbout/performance-matters-performance-audit/blob/main/assets/Schermafbeelding%202022-04-25%20om%2012.55.06.png" />

Dit project omvat een performance audit, waarbij is gekeken hoe goed de performance is van een book preview pagina van de scrollbook applicatie.

- Link van de website: https://scrollbook.student.fdnd.nl/lotr/book/

## 🤘🏼 ContentAudit

<img width="800" src="https://github.com/boudewijnbout/performance-matters-performance-audit/blob/main/assets/Schermafbeelding%202022-04-25%20om%2012.53.07.png" />

- Omschrijving: Deze pagina toont een gedeelte van het geselecteerde boek vanuit de homepagina van scrollbook. Op deze pagina kan een kort gedeelte van het geselecteerde boek worden gelezen om een impressie te krijgen.

- Datum: 25 april 2022.

- Link van de website: https://scrollbook.student.fdnd.nl/lotr/book/

<hr>

### 🥇 First Contentful Paint (FCP)

<img width="500" src="https://github.com/boudewijnbout/performance-matters-performance-audit/blob/main/assets/Schermafbeelding%202022-04-25%20om%2013.12.21.png" />

De FCP test had een goed resultaat, alleen er was een `render-blocking` issue. Dit ging om een JavaScript bestand wat de rest van de pagina blokkeerde bij het laden.

<hr>

### ⏰ Time to Interactive (TTI)

<img width="300" src="https://github.com/boudewijnbout/performance-matters-performance-audit/blob/main/assets/foto-tti.PNG" />

Voor de TTI gaf lighthouse een score van boven de 90 terug terug zonder verbeterpunten.

<hr>

### 🏎️ Speed Index

<img width="300" src="https://github.com/boudewijnbout/performance-matters-performance-audit/blob/main/assets/foto-ssi.PNG" />

Voor de SSI gaf lighthouse een score van boven de 90 terug zonder verbeterpunten.

<hr>

### 🛑 Total Blocking Time (TBT)

<img width="300" src="https://github.com/boudewijnbout/performance-matters-performance-audit/blob/main/assets/foto-tbt.PNG" />

Voor de TBT gaf lighthouse een score van boven de 90 terug zonder verbeterpunten.

<hr>

### 🛳️ Largest Contentful Paint (LCP)

<img width="450" src="https://github.com/boudewijnbout/performance-matters-performance-audit/blob/main/assets/foto-lcp.PNG" />

<img width="450" src="https://github.com/boudewijnbout/performance-matters-performance-audit/blob/main/assets/foto-lcp-2.PNG" />

Zoals op bovenstaande foto's te zien is kan de LCP flink worden verbeterd. Dit komt voornamelijk, omdat er in het project hele grote foto's zijn gebruikt. Ook worden de foto's aangeleverd in PNG, iets wat lighthouse niet zo leuk vind die raad aan om webp en/of amf te gebruiken.

<hr>

### Cumulative Layout Shift (CLS)
_Beschrijf de uitslag van de CLS van de test en toon de resultaten. Beschrijf wat kan worden verbeterd als de score minder dan 90 is._



## Bronnen

## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
