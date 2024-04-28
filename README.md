# Indivuduell Examination Frontendramverk - Where It's @

## Uppdrag
Ditt uppdrag är att koda ihop en frontend till biljettjänsten *Where its @*. Den ska se ut enligt nedan mockup. Du har också tillgång till [Figma-länk](https://www.figma.com/file/vcgWPPy2q44oZZ2eORL1wB/Where-its-light?node-id=0%3A1) för exportering av assets, färger, kika fonter etc.

![screen](./screen.png)

## Tekniska krav för godkänt
Du skall i denna uppgift för att få godkänt visa att du behärskar följande tekniker och delar inom React:
- Pages & Components
- useState & useEffect
- Props
- API-hantering
- Routing mellan Pages
- Avancerad statehantering med externt bibliotek (ex Zustand)

## Krav för väl godkänt
Du skall välja ut ytterligare 2 st React Hooks, alt. 2 st externa bibliotek (eller en av varje), som vi inte gått igenom i klassen och som du läser på om och implementerar i din applikation. Utöver detta så beskriver du i din *README.md*-fil, hur dessa hookar/bibliotek fungerar, samt varför du tycker att de passar just din applikation. För VG måste du även ha en god struktur på din applikation, med god uppdelning i Pages och Komponenter.

## Övriga krav
- Er app måste inte vara pixel-perfekt mot skissen, men ni måste ha en enhetlig, responsiv design
- Appen skall se bra ut på alla skärmstorlekar mellan 375px - 500px
- Sidan får aldrig krascha
- När en beställing gjorts skall en biljett skapas där ni genererar fram ett biljettID på 5 tecken (endast STORA BOKSTÄVER och siffror tillåtna), en Sektion och en sittplats. Vid köp av flera biljetter till ett och samma evenemang skall Sektionen vara samma på alla biljetter, och sittplatserna skall vara bredvid varandra.

## Övrig info
Figma-skissen ger inte en fullständig överblick över hur projektet bör byggas. [Se tillhörande introduktionsfilm](https://vimeo.com/manage/videos/940396692/46ea16e4b9) där det förklaras vilka tolkningar ni kan få lov att göra.

## Resurser
- Figma-skissen [hittar ni här](https://www.figma.com/file/vcgWPPy2q44oZZ2eORL1wB/Where-its-light?node-id=0%3A1)

- Ett av typsnitten som används i skissen, Sansita One, [hittar ni här](https://www.1001fonts.com/sansita-one-font.html)

- Som vanligt har ni tillgång till datan i mitt API genom nedanstående anrop:

```
GET https://santosnr6.github.io/Data/events.json
```

## Inlämning
Inlämning sker som vanligt i form av att en länk till ditt gitrepo laddas up på Azomo, senast kl 23:59 den 12/5.

