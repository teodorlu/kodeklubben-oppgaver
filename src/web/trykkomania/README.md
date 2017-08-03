# Om oppgaven {#om-oppgaven .activity}

Denne oppgaven viser deg hvordan du kan lage et spill med JavaScript og
dele det med vennene dine. Spillet kalles *Trykkomania* fordi det
handler om å trykke på en ball flest mulig ganger før tiden renner ut.

Oppgaven henter ideer fra utvikling av web-applikasjoner med bibliotek
som [React](https://facebook.github.io/react/) og
[Mithril](http://mithril.js.org/), der elementer i spillet lages som
inviduelle komponenter. Komponentene ligner på objektorientert
programmering, men bruker teknikken "closures" (funksjoner som husker
konteksten de ble laget i).

## Oppgaven passer til: {#oppgaven-passer-til .check}

**Fag**: Matematikk, Programmering, Informasjonsteknologi 2

**Trinn**: 4. trinn - VG3

**Tema**: JavaScript, web, variabler, closures, objektsorientering,
objekter, funksjoner, HTML, CSS

**Nivå**: Nybegynner

**Tidsbruk**: Dobbeltime eller mer.

## Kompetansemål {#kompetansemål .challenge}

-   \[ \] **Matematikk, 4. trinn**: bruke matematiske symboler og
    uttrykksmåter for å uttrykke matematiske sammenhenger i
    oppgaveløsning
-   \[ \] **Matematikk, 4. trinn**: tegne, bygge, utforske og beskrive
    geometriske figurer og modeller i praktiske sammenhenger, medregnet
    teknologi og design
-   \[ \] **Matematikk, 4. trinn**: lese av, plassere og beskrive
    posisjoner i rutenett, på kart og i koordinatsystemer, både med og
    uten digitale verktøy
-   \[ \] **Matematikk, 7. trinn**: beskrive plassering og flytting i
    rutenett, på kart og i koordinatsystem, med og uten digitale
    hjelpemidler, og bruke koordinater til å beregne avstander parallelt
    med aksene i et koordinatsystem

-   \[ \] **Programmering, 10. trinn**: dokumentere og forklare
    programkode gjennom å skrive hensiktsmessige kommentarer og ved å
    presentere egen og andres kode

-   \[ \] **Programmering, 10. trinn**: bruke grunnleggende prinsipper i
    programmering, slik som løkker, tester, variabler, funksjoner og
    enkel brukerinteraksjon

-   \[ \] **Programmering, 10. trinn**: overføre løsninger til nye
    problemer ved å generalisere og tilpasse eksisterende programkode og
    algoritmer.

-   \[ \] **Informasjonsteknologi 2, VG3**: utvikle og sette sammen
    delprogrammer

-   \[ \] **Informasjonsteknologi 2, VG3**: definere variabler og velge
    hensiktsmessige datatyper

-   \[ \] **Informasjonsteknologi 2, VG3**: tilordne uttrykk til
    variabler

-   \[ \] **Informasjonsteknologi 2, VG3**: lage egne og bruke egne og
    andres funksjoner eller metoder med parametere

-   \[ \] **Informasjonsteknologi 2, VG3**: planlegge og utvikle
    multimedieapplikasjoner ved å kombinere egne og andres
    multimedieelementer av typene tekst, bilde, lyd, video og
    animasjoner

-   \[ \] **Informasjonsteknologi 2, VG3**: bruke programmeringsspråk i
    multimedieapplikasjoner

-   \[ \] **Informasjonsteknologi 2, VG3**: programmere med valg og
    gjentakelser

## Forslag til læringsmål {#forslag-til-læringsmål .challenge}

-   \[ \] Eleven kan bruke enkle matematiske uttryksmåter for å øke
    eller minke variabler i JavaScript.
-   \[ \] Eleven kan bruke JavaScript til å tegne en sirkel.
-   \[ \] Eleven kan plassere et element i på en nettside ved hjelp av
    koordinater på x- og y-aksen.
-   \[ \] Eleven kan skrive kommentarer til sin egen kode i JavaScript.
-   \[ \] Eleven kan bruke variabler, løkker og funksjoner til å
    manipulere elementer i JavaScript.
-   \[ \] Eleven kan videreutvikle sitt ferdige produkt ved hjelp av
    egenprodusert JavaScript-kode.

## Forslag til vurderingskriterier {#forslag-til-vurderingskriterier .challenge}

Det er mange ulike måter en kan vurdere et programmeringsprosjekt, og
her må en selv vurdere hva som er den beste måten ut ifra hvilket fag
man jobber i, hvilken aldergruppe og hvilket nivå elevene er på, hva man
ønsker å teste og hvor mye tid man har til rådighet til å jobbe med
prosjektet. I vårt
[lærerdokument](../../pages/hvordan_bruke_lærerveiledning.html) har vi
blant annet beskrevet ulike måter dette kan gjøres på, tillegg til en
del andre nyttige tips til hvordan man underviser i programmering.

## Forutsetninger og utstyr {#forutsetninger-og-utstyr .challenge}

-   \[ \] **Forutsetninger**: Oppgaven er *kun* javascript, men det
    lønner seg å ha kjennskap til HTML og CSS.
-   \[ \] **Utstyr**: Datamaskin med internett.

## Konsepter brukt i oppgaven {#konsepter-brukt-i-oppgaven .challenge}

-   [](https://developer.mozilla.org/en-US/docs/Glossary/Variable)
-   [](https://developer.mozilla.org/en-US/docs/Glossary/Object)
-   [](https://developer.mozilla.org/en-US/docs/Glossary/Function)
-   [](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures),
    funksjoner som husker konteksten de ble laget i.
-   [](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement) via
    javascript
-   [](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/style)
    via javascript
-   [](https://developer.mozilla.org/en-US/docs/Web/API/GlobalEventHandlers/onclick)
-   [](https://developer.mozilla.org/en-US/docs/Web/API/WindowTimers/setInterval)

# Løsning {#løsning .challenge}

[Her er en full løsning av oppgaven.](løsning.js)

## Fremgangsmåte

Her kommer tips, erfaring og utfordringer til de ulike stegene i den
faktiske oppgaven. [Klikk her for å se
oppgaveteksten.](trykkomania.html){target="_blank"}

# Generelt i oppgaven {#generelt-i-oppgaven .activity}

-   \[ \] Elevene bør ha god og oversiktelig kode sånn at det er enkelt
    å finne feil. Dette oppnås ved å kommentere koden, samt bruke
    inntrykk og mellomrom mellom funksjoner og annen kode.
-   \[ \] Elevene må passe på at variabelnavn og tegnsetting er riktig.

# Steg 2: Lage en ball {#steg-2-lage-en-ball .activity}

-   \[ \] Elevene kjenner kanskje igjen CSS-elementer når de skal lage
    funksjonen `Ball()`. Her vises det at HTML og CSS kan programmeres
    gjennom JavaScript.

# Steg 3: Flytte ballen {#steg-3-flytte-ballen .activity}

-   \[ \] Elevene kan lure på hvor de skal legge til koden i dette
    steget, den skal legges til i funksjonen `Ball()` fordi `el` er en
    lokal varibel til funksjonen `Ball()`.

# Steg 4: Flytte ballen med en funksjon {#steg-4-flytte-ballen-med-en-funksjon .activity}

-   \[ \] Elevene kan være forvirret hva `x` og `y` er i denne oppgaven
    så her er det viktig å poengtere at dette er verdier som blir sendt
    inn senere i programmet, som vi ser rett før *Steg 5*.

# Steg 5: Velg en tilfeldig plassering {#steg-5-velg-en-tilfeldig-plassering .activity}

-   \[ \] Her ser vi at vi kan legge til *strenger* bak tall som er
    blitt regnet ut: `Math.random() * 100 + '%';`. Dette kan være svært
    nyttig for elevene å vite i senere oppgaver.
-   \[ \] Elever kan lure på hva `Math.random()` er. Og ved å si
    `Math.random()` så kaller vi på et bibliotek (*Math*), altså en
    innebygget JavaScript-fil, som inneholder funksjonen `random()`.

# Steg 7: Poeng {#steg-7-poeng .activity}

-   \[ \] Elevene må kopiere koden akkurat som den står oppført, hvis
    ikke blir det fort feil.

# Steg 8: Begrense tiden {#steg-8-begrense-tiden .activity}

-   \[ \] Elevene må kopiere koden akkurat som den står oppført, hvis
    ikke blir det fort feil.

# Steg 9: Omstarte spillet {#steg-9-omstarte-spillet .activity}

-   \[ \] Elevene må kopiere koden akkurat som den står oppført, hvis
    ikke blir det fort feil.

## Variasjoner {#variasjoner .challenge}

-   \[ \] *Vi har dessverre ikke noen variasjoner tilknyttet denne
    oppgaven enda.*

