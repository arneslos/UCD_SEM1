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

| Fase  | Action | Outcome  | 
| ------------- | ------------- |  ------------- | 
| 1 | define the problem statement | De aanwezigheid van aanraakschermen in wagens zorgt voor afleidingen. |
| 2 | collect information | Interviews, benchmarking, literature review en design ethnography (shadowing) afnemen  |
| 3 | analyse information | Interviews, benchmarking, literature review en design ethnography (shadowing) interpreteren |
| 4 | reformulate the problem statement | Het gebruiken van aanraakschermen tijdens het rijden is gevaarlijk omdat het voor afleiding zorgt en de aandacht voor de weg verminderd. |
| 5 | define first design requirements | Opstarten van een PRD (nog niet gedetaileerd). |
| 6 | generate ideas | Ideeen genereren op verschillende manieren. |
| 7 | develop ideas | De sterkste ideeen/ concepten uitkiezen om verder uit te werken |
| 8 | choose concept | Een ‘finaal’ concept kiezen, in dit geval: de interacties in een wagen laten verlopen met knoppen en een HUD, een aanraakscherm dat wegklapt al de wagen rijdt. |
| 9 | define secondarydesign requirements | De PRD verder uitwerken zodat deze beter aansluit bij het gekozen concept. |
| 10 | detailed development of concept | Kiezen hoe de concepten gemaakt en getest kunnen worden. |
| 11 | testing concepts against design requirements | De concepten testen. |


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

![image](https://github.com/arneslos/UCD_SEM1/assets/159801398/88b8b6a3-233e-4fbb-8c17-cd817d47e3d0)![image](https://github.com/arneslos/UCD_SEM1/assets/159801398/0820dff3-4afd-4f14-9408-f4e671c19aea)

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


### Doestellingen
In de definition fase van het dashboard design worden twee aspecten van het nieuwe
dashboard onderzocht:

- Volgens welke indeling moet de informatie op ons HUD geprojecteerd worden?
- Welke configuratie van aanraakscherm en knoppen is het snelst in gebruik volgens de
gebruiksnoden?

Het doel is om zo een duidelijk overzicht te hebben van de belangrijkste informatie die moet
geprojecteerd worden op het Heads Up Display. Hierbij is het noodzakelijk dat de informatie
overzichtelijk en beperkt is, maar toch voldoende om niet steeds op zoek te moeten gaan naar
verdere informatie.
Ook werd er onderzocht op welke manier de interactie met het aanraakscherm, wanneer de
wagen in stilstand is, op een zo vlot mogelijke manier kan gebeuren.

### Materiaal & methoden
Om te onderzoeken hoe de lay-out van de heads up display ingedeeld moet worden zijn er
twee lay-outs uitgewerkt. De informatie die op de heads up display wordt geprojecteeerd werd
bepaald aan de hand van de volgende vraag uit het interview: wat is de belangrijkste
informatie die moet aangegeven worden tijdens het rijden? De bestuurders ervaarden:
snelheidsaanduiding, richting aanwijzers, de afstand die nog gereden kan worden, de
hoeveelheid brandstof, de radio en muziek en de navigatie de belangrijkste zaken zijn die
weergegeven moeten worden. Om de ideale lay-out te testen wordt in een wagen al de
schermen afgedekt en wordt de lay-out met papier op de voorruit geplakt. Op deze manier kan
de bestuurder beter begrijpen hoe de lay-out werkt en kan opmerkingen meegeven.

![image](https://github.com/arneslos/UCD_SEM1/assets/159801398/a3d99b2e-aecf-4ee0-8fab-22de31ca4b8b)! [image](https://github.com/arneslos/UCD_SEM1/assets/159801398/29571fcd-5921-4764-9b34-eab3a2126fd1)

De eerste lay-out heeft aan de linkerkant een kaart voor navigatie met daarboven de snelheid
die de wagen rijdt en de richtingaanwijzers. Onder de kaart is het uur te vinden met daarnaast
de afstand die de wagen nog kan rijden. Naast de kaart is de hoeveelheid brandstof te vinden.
Aan de rechterkant staat de informatie over de radio/ muziek en daarboven verschijnen de
meldingen over problemen met de wagen.

Bij de tweede lay-out zijn de richtingaanwijzers aangegeven aan beide kanten van de voorruit.
Bij deze lay-out is al de informatie meer verspreid over de ruit. Linksboven wordt de tijd
aangegeven, rechtsboven de informatie over de radio en de afgespeelde muziek. Aan de
onderkant zijn rechts de meldingen over de wagen weergegeven en link de hoeveelheid
kilometers die nog gereden kunnen worden en de hoeveelheid brandstof er nog over is. In het
midden van het scherm wordt de navigatie weergegeven aan de hand van een pijl die boven
de weg zweeft en in de juiste richting wijst. Op deze pijl wordt ook de snelheid weergegeven.

Om te onderzoeken op welke manier de standaard configuratie van het aanraakscherm en de
knoppen wordt geconfigureert worden er twee prototypes gebruikt, deze prototypes hebben
elk een verschillende layout maar beshikken over dezelfde functies bij benchmarking zijn
bepaald. Het enige grote verschil tussen beide opstellingen is dat er bij concept één gebruik
gemaakt word van een draaiknop en bij concept twee knoppen om het volume te verhogen.

![image](https://github.com/arneslos/UCD_SEM1/assets/159801398/726627ac-d046-4e1f-8918-09e73b7917ec) ![image](https://github.com/arneslos/UCD_SEM1/assets/159801398/79c66e82-f24b-4365-a45e-614a7639b413)

Om de gebuiker kennis te laten maken met de prototypes mag deze verschillende knoppen
aanwijzen en hier de functie van bepalen. Daarna word dit gecontroleerd en word er bekend
gemaakt of dit juist of fout was.
Vervolgens wordt de gebruiker gevraagd om een bepaalde knop in te drukken of funcite te
activeren. De tijd werd geregistreed. Dit werd voor bijde opstellingen getest.
Deze tijdsindicaties geven een objectief beeld welke configuratie het snelst is bij gebruik en
dus ook voor een kortere periode een verminderde aandacht geven. Op het einde van het
onderzoek werd de mening van de gebruiker gevraagd over welke opstelling er verkozen
wordt en of er eventuele extra aanpassingen mogelijk zijn.

### Resultaten
De twee lay-outs zijn getest in een wagen waarbij al de instrumenten zijn afgedekt en de layouts met papier op de ruit zijn geplakt. De bestuurder gaf dan aan welke aanduidingen er ontbraken of niet goed werden weergegeven.
Testopstelling van lay-out 1
De eerste opstelling die getest
werd, had als opmerking dat er
geen plaats voorzien was voor een
infotainment systeem om
bijvoorbeeld Apple CarPlay op weer
te geven. Ook werden zaken zoals
de radio en de meldingen niet direct
in het gezichtsveld en te klein
weergegeven waardoor de
bestuurder op zoek moet gaan
waar deze zijn aangegeven.
Testopstelling van lay-out 2
De tweede opstelling gaf een betere
gebruikservaring.
Er is meer overzicht door al de
Informatie naar de kanten van de ruit
te plaatsen. De positie van de
meldingen en van de radio/ muziek vond
de bestuurder beter in de eerste opstelling.
Hier was ook geen rekening gehouden
met een plaats voor het infotainment
systeem.
Bij de beide opstellingen was er een opmerking dat de vakken waarin de informatie wordt
weergegeven klein en moeilijk leesbaar zijn. Dit kan worden opgelost door de vakken waar de
bestuurder in wil ‘werken’ tijdelijk centraal en groter te projecteren.
Bij de resultaten van de twee cardboard prototypes is er tussen de verschillende functies geen
significante verschillen waargenomen in tijd. Bij de volumeknop was er wel een significant
verschil in gemeten tijd tussen een drukknop dan en een draaiknop.

### Conclusies & implicaties
Om een goede en overzichtelijke heads up display te bekomen moet al de informatie op een
overzichtelijke manier worden weergegeven. De oplossing is door de informatie bij niet
begruik klein en aan de buitenkanten weer te geven. Op het moment dat de bestuurder een
functie wil gebruiken wordt dit vak groter en komt centraal te staan.
Om een vlotte configuratie van knoppen en aanraakscherm te bekomen is het belangrijk dat
er een vaste draaiknop aanwezig is als volumeknop, uit het design ethnography onderzoek is
gebleken dat dit een functie is die heel vaak gebruikt wordt. Andere functies zoals de airco en
het aanpassen van de radio vergen ook vaste drukknoppen. Extra features zoals
zetelverwarming of verwarmd stuur kunnen bediend worden aan de hand van het
aanraakscherm of spraakherkenning.

## Bill of materials

- Plaat plexiglas om een heads up display te maken
- Knoppen voor de programmeerbare functies
- Spraak sensor om de stembediening te doen werken
- ProtoPie
- Aanraakscherm (ipad of gsm)
- Arduino om input van knoppen te verwerken
- Een materiaal om vorm te geven aan het dashboard
- Display om HUD te projecteren op plexiplaat (GSM)
- Eventueel stuur om de stuurknoppen te simuleren

## Kritische reflectie
Tijdens het uitvoeren van dit onderzoek werd er kennis gemaakt met nieuwe
onderzoeksmethoden zoals design ethnography en wizard of Oz. Ook eerder aangeleerde
technieken zoals literatuur review en interviews zijn toegepast.
Na het samenvoegen van beide vooronderzoeken, waar het ene onderzoek een
interviewtechniek en het andere een design ethnography had toegepast viel het op dat de er
gelijkaardige resultaten bekomen waren. Bij een interview denkt de persoon na over een
antwoord. Het is bewust, de persoon denkt niet of juist te veel na over details in de
antwoorden. Bij een observatie worden heel wat onbewuste
handelingen waargenomen waarover de persoon niet meer nadenkt. Interview geeft beter
een gevoel van de gebruiker weer zoals welke knop vind je goed en waarom. Design
ethnography is een observatie waarbij de hoeveelheid en hoe de knop gebruikt wordt
waarneembaar wordt. Door de combinatie van de verschillende technieken ontstaat er een
completer beeld.
Met dit project is meer inzicht gekomen in de interviewtechniek. Het is niet voldoende om te
vragen wat het probleem is. Door te blijven doorvragen waarom het probleem er is, wordt er
meer inzicht over de oorzaak bekomen. Het probleem kan pas aangepakt worden als de
oorzaak bekend is.
Door de individueel onderzoeken samen te voegen ontstonden er meer invalshoeken over het
concept hierdoor kwamen er ook meer bevestiging van de gekozen oplossingen/ concept. 

## Bronnen
(Nws, 2021b) : Nws, V. (2021, 11 maart). Aanraakschermen in je auto bedienen drie keer
gevaarlijker dan rijden onder invloed: “Europese regels nodig”. vrtnws.be.
https://www.vrt.be/vrtnws/nl/2021/03/11/aanraakschermen-in-je-auto-bedienen-drie-keergevaarlijker-dan-r/#:~:text=%2D%2D%3A%2D%2D-
,Aanraakschermen%20in%20je%20auto%20bedienen%20drie%20keer%20gevaarlijker%20d
an%20rijden,het%20risico%20op%20een%20ongeval.

## Bijlagen
(Google drive):
https://drive.google.com/drive/folders/1x8gPw4AJ5K4TxQPy2E_7yjYqFXD9Rf43?usp=sharing
Figma:
https://www.figma.com/file/UazHZrtgUNHXp7b5WrkCnB/Untitled?type=design&nodeid=0%3A1&mode=design&t=L9cifeomLyC9PtCw-1
Miro:
https://miro.com/welcomeonboard/aTl3Sm0yb1lUWmlzU3RwNUQ1ZjByam1nNVM3S0FTNW
NCUkhjcFlodUZhdWphd0pWZUpiRG9HanNNSENxYWcwdnwzMDc0NDU3MzY0ODc4MTMx
MTU4fDI=?share_link_id=531594994039 
