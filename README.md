# Car dashboard redesign
Deze studie gaat over een vernieuwd dashboard ontwerp, die gebruik maakt van spraakherkenning, bedieningsknoppen, HUD (head-up-display) en een touchscreen dat wegklapt wanneer het voertuig in beweging komt.

*Projectteam: Viktor Coopman, Arne Slos*

2023 - 2024

## Samenvatting
Bestuurders van wagens worden geconfronteerd met allerlei bedieningsfuncties tijdens het rijden. Deze kunnen een risico vormen omdat er minder aandacht gaat naar de weg en naar andere weggebruikers. Een groot deel van deze afleidingen worden veroorzaakt door schermen in de wagens. Deze zitten niet in het directe gezichtsveld van de bestuurder maar ergens in het midden van het dashboard. Daarbovenop is er de interactie via touch technologie, wat een extra afleiding kan geven omdat de bestuurder het stuur niet meer met beide handen vasthoudt. 

Dit probleem is verder onderzocht. De gebruikte technieken zijn: design ethnography (shadowing) door de functies die het meest gebruikt worden te rangschikken, benchmarking met de SOTA te onderzoeken, een literature review en interviews.

De oplossing in deze studie is een dashboard waarbij het scherm verdwijnt en dus onbruikbaar wordt wanneer de wagen begint met rijden. Al de essentiële zaken zoals snelheid, GPS, radio, … worden dan geprojecteerd over de voorruit met een heads up display. In de wagen zijn er acht programmeerbare knoppen aanwezig waarmee al de functies bediend kunnen worden. Hierdoor kan de bestuurder zich beter focussen op de weg en het verkeer. Eventuele bedieningen kunnen via het scherm (bij stilstand) of met spraakherkenning (tijdens het rijden).

![image](https://github.com/arneslos/UCD_SEM1/assets/159801398/f0900578-0675-4d05-a614-5c61481174c1)

## Introductie
Uit een Britse studie (Nws, 2021b) blijkt dat schermen in het verkeer voor afleiding zorgen en dat het reactievermogen van een bestuurder hierdoor tot wel 3 keer trager is dan het reactievermogen van een dronken bestuurder. Dit komt doordat de bestuurder op dat moment niet naar de omgeving kijkt, maar zijn of haar ogen gericht zijn op de schermen in de auto. Een mogelijke oplossing is alle schermen in de auto die niet in het directe gezichtsveld van de bestuurder zijn, te verwijderen, met behoud van toegankelijkheid van alle functies.

Moderne auto's maken steeds minder gebruik van fysieke knoppen om functies aan te sturen, deze worden vervangen door een scherm met verschillende functies. Door deze schermen te verwijderen, moeten we een alternatieve manier vinden om deze functies aan te sturen.

We volgen een vooraf bepaalde tijdlijn met vier verschillende fases. Binnen deze fases zullen we zowel divergeren als convergeren. We adresseren verschillende problemen die zich voordoen met schermen en halen hieruit de meest noodzakelijke factoren om een diepgaande "how might we" vraag te formuleren. Aan de hand van deze "how might we" vraag bedenken we verschillende oplossingen en geven we vorm aan enkele ideeën met prototypes.

Aan het einde van dit eerste onderzoek streven we ernaar, aan de hand van deze prototypes, een eerste idee te hebben van hoe ons eindproduct eruit zou zien en waarom.

Het doel van dit eindonderzoek is het creëren van een simulatie van een veilige en aangename rijervaring, waarbij de reactiesnelheid van de bestuurder niet wordt verzwakt door de aanwezige technologie.

Dit onderzoek wordt uitgevoerd aan de UGent te Kortrijk in samenwerking met Granstudio.


## Methdologie
De toegepaste methodologie is gebaseerd op Roozenburg & Eekels (1995). 
Deze methodologie bestaat uit een aantal fasen. Tijdens de eerste fase wordt het probleem gedefinieerd. In dit onderzoek is het probleem: de aanwezigheid van aanraakschermen in wagens zorgt voor afleidingen. 
Gedurende de tweede fase wordt er op verschillende manieren informatie verzameld. Tijdens deze fase in het onderzoek zijn er gebruiker interviews, een design ethnography, een benchmarkstudie en een literatuurstudie uitgevoerd. 
In de derde fase wordt de informatie die verzameld is verwerkt. De antwoorden van het interview, opmerkingen bij het design ethnography worden geanalyseerd en omgezet naar potentiele verbeteteringen. 
De vierde fase is de fase waarin het probleem wordt geherdefinieerd aan de hand van de bekomen informatie. In het geval van dit project werd de geherdefinieerde probleemstelling: het gebruiken van aanraakschermen tijdens het rijden is gevaarlijk omdat het voor afleiding zorgt en de aandacht voor de weg verminderd. 
In de vijfde fase wordt er een programma van eisen opgesteld. In dit programma van eisen worden al de specificaties van het uiteindelijke product vastgelegd, dit gebeurde aan de hand van een PRD (Product Requirements Document) (bijlage 1).
De zesde fase is de idee generatie fase, hier worden al de mogelijke ideeën verzameld, deze ideeën kunnen van heel eenvoudig tot onmogelijk zijn. De vereiste is dat de ideeën een oplossing zijn voor het probleem. Dit gebeurde door verschillende dingen neer te schrijven en door schetsen te maken.
In de zevende fase worden er uit de gegenereerde oplossingen een paar gekozen met veel potentieel. Deze worden een verder uitgewerkt om de interessantste en haalbare oplossingen te kunnen selecteren.
In de achtste fase wordt er één concept gekozen als de oplossing. Deze wordt dan volledig uitgewerkt. In het geval van dit concept: een dashboard met een scherm dat wegklapt als de wagen begint met rijden.  Op dit moment wordt al de essentiële informatie op de voorruit geprojecteerd met een heads up display systeem. Er zijn enkele programmeerbare knoppen aanwezig om zelfgekozen functies te bedienen.
In de negende fase wordt de PRD verder uitgewerkt met de nieuwe informatie na het vastleggen van het concept.
De tiende fase dient om te bekijken hoe het concept getest kan worden.
In de elfde fase wordt het finaal concept getest.

![image](https://github.com/arneslos/UCD_SEM1/assets/159801398/60eb584d-cea4-4917-9a44-b1ac93a384aa)

![image](https://github.com/arneslos/UCD_SEM1/assets/159801398/17846809-09f6-46c9-b580-38bdf3dc47d9)


## Discovery
### Doelstellingen
Aan de hand van verschillende onderzoeksmethoden zoals interviews, design ethnography (shadowing) en benchmarking werden volgende zaken onderzocht:
- Waarom zijn schermen in het verkeer gevaarlijk?
- Wat zijn de gebruiksnoden van een bestuurder tijdens het rijden?
- Welke technologieën zijn er nu op de markt om de gevaren van schermen te verminderen?

### Materiaal & methoden
Om de problemen van gebruikers vast te stellen zijn er gebruikers geinterviewd, artikels opgezocht (literature review) en een design ethnography uitgevoerd (bijlage 2). Om te vergelijken wat er al op de markt is, is er een benchmark studie opgezet. De interviews en design ethnography werden elk bij twee personen afgenomen.

Bij het benchmark onderzoek werd er gekeken naar het dashboard die nu op de markt zijn van verschillende autofabrikanten. Er werd ook gekeken naar hoe de functies aangestuurd worden in deze interieurs.

Het doel van de interviews was om te achterhalen met welke problemen van afleiding en gebruiksgemak de bestuurder te maken krijgt. Dit gebeurde aan de hand van acht vragen die de personen moesten beantwoorden. De antwoorden werden rechtstreeks genoteerd en herhaald naar de geïnterviewde, op deze manier was er nog een mogelijkheid om hun antwoord te verbeteren/ te corrigeren.

Via design ethnography werd er onderzocht welke functies de bestuurder het vaakst gebruikt en hoe de bestuurder deze functies gebruikt. Dit gebeurde door bij twee personen in de wagen te stappen en een rit uit te voeren. Tijdens deze rit werd er niet met de bestuurder gecommuniceerd. De rit begon en eindigde in een willekeurig punt. De routebeschrijving gebeurde aan de hand van het navigatiesysteem in de wagen. Er werd gebruik gemaakt van een smartphone om de testrit te filmen, zodat de resultaten achteraf nog gebruikbaar zijn om te onderzoeken.

### Resultaten
Voor de literatuurstudie zijn er negen artikels en video’s gevonden die de gevaren van
schermen in wagens bespreken. Van de negen artikels is er één artikel die de stelling
“Schermen in wagens zijn slecht!” in vraag stelt. Een ander artikel ging over het feit dat
schermen niet de enige bron van afleiding zijn, maar dat de dingen die rondom de wagen
gebeuren ook voor afleiding zorgen.
Om te weten te komen hoe de huidige dashboards ingedeeld zijn werd er een
benchmarkstudie uitgevoerd. Uit deze studie blijkt dat fabrikanten vaak gebruik maken van
één groot scherm of meerdere kleine schermen. Deze schermen zijn meestal touchscreens,
de functies zijn terug te vinden in meerdere menu’s. Onder de schermen zijn er meestal nog
knoppen aanwezig om bepaalde functies uit te voeren, zodat er niet telkens in de menu’s
gezocht moet worden. In de middenconsole zijn er bij de meeste fabrikanten ook knoppen
aanwezig. Vaak zit hier ook de knop om de wagen te starten, een gear selector en een
handrem, dit kan een knop zijn of een hendel. 





De interviews werden afgenomen om beter te begrijpen wat de bestuurder belangrijk vindt in
een wagen, welke problemen er voorkomen en waarom deze er zijn. De veiligheidsfuncties
worden als de belangrijste ervaren. Bijvoorbeeld: een waarschuwing geven als er een ander
voertuig nadert. Op de tweede plaats kwamen functies die het rijden makkelijker maken, zoals
cruise control en lane keeping aid. De bestuurders vonden de entertainmentfuncties zoals de
radio of Android Auto/ Apple CarPlay om muziek af te spelen de nice to have functies. Ook de
navigatieapp werd ervaren als een belangrijke functie. De bestuurders gaven aan dat de
meeste afleiding ontstond bij het aanpassen van de entertainmentfuncties, het instellen van
het navigatiesysteem en het veranderen van de muziek. De bestuurders ondervonden
problemen bij functies die “een niveau dieper” in de menu’s zitten. Het gevolg hiervan is dat
de bestuurder langer is afgeleid. Bij sommige wagens is er geen feedback als er een functie
wordt aangklikt, dan moet de bestuurder naar het scherm of de knop kijken om te verifieren
dat de gewenste functie actief wordt.
Om te weten te komen hoe bestuurders de schermen in een wagen gebruiken werd er gebruik
gemaakt van shadowing. De bestuurder werd geobserveerd terwijl deze rond reed via een
parcours dat door de gps werd aangegeven. Tijdens deze observatie bleek dat de radio
slechts één keer werd bediend bij het begin van de rit. Tijdens het rijden werd er een paar
keer naar de gps gekeken en werd deze ook bediend, bijvoorbeeld in-/ uitzoomen. De
meestgebruikte knop was die om het volume harder en zachter te zetten. Beide bestuurders
maakten intensief gebruik van de middenconsole als opbergvak. 

### Conclusies & implicaties 
Uit het onderzoek kan geconcludeerd worden dat de afleidingen veroorzaakt worden door de
schermen in een wagen te bedienen. De bestuurders hechten vooral veel belang aan een
radio- en een navigatiesysteem. Deze moeten makkelijk en snel bedienbaar zijn. De navigatie
wordt vaak voor vertrek ingesteld voor het vertrek. Op dat moment is het geen probleem om te
werken met een scherm in het midden van de wagen. Vanaf het moment dat de wagen rijdt is
dit wel een gevaar, dan wordt de bestuurder afgeleid. De schermen zijn dus niet alleen het
gevaar, maar de plaats waar de informatie wordt weergegeven zorgt voor een grotere invloed
op de afleiding. Dit probleem kan worden opgelost door het scherm te doen wegklappen of
schuiven en de informatie te projecteren met een heads up display. Als de informatie met een
groot heads up display op een eenvoudige en ordelijke manier kan worden weergegeven voor
de bestuurder zal dit ervoor zorgen dat de bestuurder meer focus heeft op de weg. Het
scherm in een wagen wordt vaak gebruikt om de functies te bedienen. Als dit scherm niet
meer aanwezig is moet er een andere manier aangebracht worden om deze functies te
bedienen. Dit zal gebeuren aan de hand van programmeerbare knoppen. Door deze knoppen
is er ook een feedback die de bestuurder krijgt tijdens het bedienen van de functies.


## Definition
Max. 1000 woorden
### Doestellingen
Wat wilde je bereiken?
### Materiaal & methoden
Hoe onderzocht je dit? Wees volledig.
### Resultaten
Rapporteer over de resultaten (incl. foto's, quotes, analyseframeworks, ...)
### Conclusies & implicaties
Definieer de belangrijkste designbeslissingen

## Bill of materials
- Welk
- Materiaal
- Heb
- Je
- Nu
- Nodig
- Voor
- Je
- Prototype

## Kritische reflectie
Max. 500 woorden

## Bronnen
Voeg je volledige bibliografie toe van bronnen naarwaar je verwees.

## Bijlagen
