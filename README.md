# Buttonize
Deze studie gaat over een vernieuwd dashboard ontwerp, die gebruik maakt van spraakherkenning, bedieningsknoppen, HUD (head-up display) en een touchscreen dat wegklapt wanneer het voertuig in beweging komt.

*Projectteam: Viktor Coopman, Arne Slos*

2023 - 2024

## Samenvatting
Bestuurders van wagens worden geconfronteerd met allerlei bedieningsfuncties tijdens het rijden. Deze kunnen een risico vormen omdat er minder aandacht gaat naar de weg en naar andere weggebruikers. Een groot deel van deze afleidingen worden veroorzaakt door schermen in de wagens. Deze zitten niet in het directe gezichtsveld van de bestuurder maar ergens in het midden van het dashboard. Daarbovenop is er de interactie via touch technologie, wat een extra afleiding kan geven, omdat de bestuurder het stuur niet meer met beide handen vasthoudt. 

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


## Metohdologie Sem. 1
De toegepaste methodologie tijdens het eerste semester is gebaseerd op Roozenburg & Eekels (1995). 
Deze methodologie bestaat uit een aantal fasen. Tijdens de eerste fase wordt het probleem gedefinieerd. In dit onderzoek is het probleem: de aanwezigheid van aanraakschermen in wagens zorgt voor afleidingen. 
Gedurende de tweede fase wordt er op verschillende manieren informatie verzameld. Tijdens deze fase in het onderzoek zijn er gebruiker een design ethnography (bijlage 4.1), een benchmarkstudie (bijlage 4.2), interviews (bijlage 4.3) en een literatuurstudie (bijlage 4.4) uitgevoerd. 
In de derde fase wordt de informatie die verzameld is verwerkt. De antwoorden van het interview, opmerkingen bij het design ethnography worden geanalyseerd en omgezet naar potentiële verbeteringen.
De vierde fase is de fase waarin het probleem wordt geherdefinieerd aan de hand van de bekomen informatie. In het geval van dit project werd de geherdefinieerde probleemstelling: het gebruiken van aanraakschermen tijdens het rijden is gevaarlijk omdat het voor afleiding zorgt en de aandacht voor de weg verminderd. 
In de vijfde fase wordt er een programma van eisen opgesteld. In dit programma van eisen worden al de specificaties van het uiteindelijke product vastgelegd, dit gebeurde aan de hand van een PRD (Product Requirements Document) (bijlage 1).
De zesde fase is de idee generatie fase, hier worden al de mogelijke ideeën verzameld, deze ideeën kunnen van heel eenvoudig tot onmogelijk zijn. De vereiste is dat de ideeën een oplossing zijn voor het probleem. Dit gebeurde door verschillende dingen neer te schrijven en door schetsen te maken.
In de zevende fase worden er uit de gegenereerde oplossingen een paar gekozen met veel potentieel. Deze worden een verder uitgewerkt om de interessantste en haalbare oplossingen te kunnen selecteren.
In de achtste fase wordt er één concept gekozen als de oplossing. Deze wordt dan volledig uitgewerkt. In het geval van dit concept: een dashboard met een scherm dat wegklapt als de wagen begint met rijden.  Op dit moment wordt al de essentiële informatie op de voorruit geprojecteerd met een head-up display systeem. Er zijn enkele programmeerbare knoppen aanwezig om zelfgekozen functies te bedienen.

In de negende fase wordt de PRD verder uitgewerkt met de nieuwe informatie na het vastleggen van het concept.

De tiende fase dient om te bekijken hoe het concept getest kan worden.

In de elfde fase wordt het finaal concept getest.

| Fase  | Action | Outcome  | 
| ------------- | ------------- |  ------------- | 
| 1 | define the problem statement | De aanwezigheid van aanraakschermen in wagens zorgt voor afleidingen. |
| 2 | collect information | Interviews, benchmarking, literature review en design ethnography (shadowing) afnemen  |
| 3 | analyse information | Interviews, benchmarking, literature review en design ethnography (shadowing) interpreteren |
| 4 | reformulate the problem statement | Het gebruiken van aanraakschermen tijdens het rijden is gevaarlijk omdat het voor afleiding zorgt en de aandacht voor de weg verminderd. |
| 5 | define first design requirements | Opstarten van een PRD (nog niet gedetailleerd). |
| 6 | generate ideas | Ideeen genereren op verschillende manieren. |
| 7 | develop ideas | De sterkste ideeen/ concepten uitkiezen om verder uit te werken |
| 8 | choose concept | Een ‘finaal’ concept kiezen, in dit geval: de interacties in een wagen laten verlopen met knoppen en een HUD, een aanraakscherm dat wegklapt al de wagen rijdt. |
| 9 | define secondarydesign requirements | De PRD verder uitwerken, zodat deze beter aansluit bij het gekozen concept. |
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
Om de problemen van gebruikers vast te stellen zijn er gebruikers geïnterviewd, artikels opgezocht (literature review) en een design ethnography uitgevoerd (bijlage 2). Om te vergelijken wat er al op de markt is, is er een benchmark studie opgezet. De interviews en design ethnography werden elk bij twee personen afgenomen.

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
worden als de belangrijkste  ervaren. Bijvoorbeeld: een waarschuwing geven als er een ander
voertuig nadert. Op de tweede plaats kwamen functies die het rijden makkelijker maken, zoals
cruisecontrol en lane keeping aid. De bestuurders vonden de entertainmentfuncties zoals de
radio of Android Auto/ Apple CarPlay om muziek af te spelen de nice to have functies. Ook de
navigatieapp werd ervaren als een belangrijke functie. De bestuurders gaven aan dat de
meeste afleiding ontstond bij het aanpassen van de entertainmentfuncties, het instellen van
het navigatiesysteem en het veranderen van de muziek. De bestuurders ondervonden
problemen bij functies die “een niveau dieper” in de menu’s zitten. Het gevolg hiervan is dat
de bestuurder langer is afgeleid. Bij sommige wagens is er geen feedback als er een functie
wordt aangeklikt, dan moet de bestuurder naar het scherm of de knop kijken om te verifiëren
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
schuiven en de informatie te projecteren met een head-up display. Als de informatie met een
groot head-up display op een eenvoudige en ordelijke manier kan worden weergegeven voor
de bestuurder zal dit ervoor zorgen dat de bestuurder meer focus heeft op de weg. Het
scherm in een wagen wordt vaak gebruikt om de functies te bedienen. Als dit scherm niet
meer aanwezig is moet er een andere manier aangebracht worden om deze functies te
bedienen. Dit zal gebeuren aan de hand van programmeerbare knoppen. Door deze knoppen
is er ook een feedback die de bestuurder krijgt tijdens het bedienen van de functies.


## Definition


### Doelstellingen
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
Om te onderzoeken hoe de lay-out van de head-up display ingedeeld moet worden zijn er
twee lay-outs uitgewerkt. De informatie die op de head-up display wordt geprojecteerd werd
bepaald aan de hand van de volgende vraag uit het interview: wat is de belangrijkste
informatie die moet aangegeven worden tijdens het rijden? De bestuurders ervaarden:
snelheidsaanduiding, richting aanwijzers, de afstand die nog gereden kan worden, de
hoeveelheid brandstof, de radio en muziek en de navigatie de belangrijkste zaken zijn die
weergegeven moeten worden. Om de ideale lay-out te testen wordt in een wagen al de
schermen afgedekt en wordt de lay-out met papier op de voorruit geplakt. Op deze manier kan
de bestuurder beter begrijpen hoe de lay-out werkt en kan opmerkingen meegeven.

![image](https://github.com/arneslos/UCD_SEM1/assets/159801398/a3d99b2e-aecf-4ee0-8fab-22de31ca4b8b)![image](https://github.com/arneslos/UCD_SEM1/assets/159801398/3da2839f-04ae-4302-97af-36077910331d)


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
knoppen wordt geconfigureerd worden er twee prototypes gebruikt, deze prototypes hebben
elk een verschillende lay-out maar beschikken over dezelfde functies bij benchmarking zijn
bepaald. Het enige grote verschil tussen beide opstellingen is dat er bij concept één gebruik
gemaakt word van een draaiknop en bij concept twee knoppen om het volume te verhogen.

![image](https://github.com/arneslos/UCD_SEM1/assets/159801398/726627ac-d046-4e1f-8918-09e73b7917ec) ![image](https://github.com/arneslos/UCD_SEM1/assets/159801398/79c66e82-f24b-4365-a45e-614a7639b413)

Om de gebruiker kennis te laten maken met de prototypes mag deze verschillende knoppen
aanwijzen en hier de functie van bepalen. Daarna wordt dit gecontroleerd en wordt er bekend
gemaakt of dit juist of fout was.
Vervolgens wordt de gebruiker gevraagd om een bepaalde knop in te drukken of functie te
activeren. De tijd werd geregistreerd. Dit werd voor beide opstellingen getest.
Deze tijdsindicaties geven een objectief beeld welke configuratie het snelst is bij gebruik en
dus ook voor een kortere periode een verminderde aandacht geven. Op het einde van het
onderzoek werd de mening van de gebruiker gevraagd over welke opstelling er verkozen
wordt en of er eventuele extra aanpassingen mogelijk zijn.

### Resultaten
De twee lay-outs zijn getest in een wagen waarbij al de instrumenten zijn afgedekt en de layouts met papier op de ruit zijn geplakt. De bestuurder gaf dan aan welke aanduidingen er ontbraken of niet goed werden weergegeven.

#### Testopstelling van lay-out 1

![image](https://github.com/arneslos/UCD_SEM1/assets/159801398/8bc53b4e-3e65-4af0-8875-578d692a0e01)


De eerste opstelling die getest werd, had als opmerking dat er geen plaats voorzien was voor een infotainment systeem om bijvoorbeeld Apple CarPlay op weer te geven. Ook werden zaken zoals de radio en de meldingen niet direct in het gezichtsveld en te klein weergegeven waardoor de bestuurder op zoek moet gaan waar deze zijn aangegeven.

#### Testopstelling van lay-out 2

![image](https://github.com/arneslos/UCD_SEM1/assets/159801398/49520551-feef-4c23-b339-bc45755d7863)


De tweede opstelling gaf een betere gebruikservaring. Er is meer overzicht door al de Informatie naar de kanten van de ruit te plaatsen. De positie van de meldingen en van de radio/ muziek vond de bestuurder 
beter in de eerste opstelling.
Hier was ook geen rekening gehouden met een plaats voor het infotainment systeem.

Bij de beide opstellingen was er een opmerking dat de vakken waarin de informatie wordt weergegeven klein en moeilijk leesbaar zijn. Dit kan worden opgelost door de vakken waar de bestuurder in wil ‘werken’ tijdelijk centraal en groter te projecteren. Bij de resultaten van de twee cardboard prototypes is er tussen de verschillende functies geen significante verschillen waargenomen in tijd. Bij de volumeknop was er wel een significant verschil in gemeten tijd tussen een drukknop dan en een draaiknop.

![image](https://github.com/arneslos/UCD_SEM1/assets/159801398/a69e4ea7-e598-486e-829e-cddb43040e23)

### Conclusies & implicaties
Om een goede en overzichtelijke head-up display te bekomen moet al de informatie op een
overzichtelijke manier worden weergegeven. De oplossing is door de informatie waneer deze niet wordt gebruikt
begruik klein en aan de buitenkanten weer te geven. Op het moment dat de bestuurder een
functie wil gebruiken wordt dit vak groter en komt centraal te staan.
Om een vlotte configuratie van knoppen en aanraakscherm te bekomen is het belangrijk dat
er een vaste draaiknop aanwezig is als volumeknop, uit het design ethnography onderzoek is
gebleken dat dit een functie is die heel vaak gebruikt wordt. Andere functies zoals de airco en
het aanpassen van de radio vergen ook vaste drukknoppen. Extra features zoals
zetelverwarming of verwarmd stuur kunnen bediend worden aan de hand van het
aanraakscherm of spraakherkenning.

## Bill of materials

- Plaat plexiglas om een head-up display te maken
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
concept, hierdoor kwamen er ook meer bevestiging van de gekozen oplossingen/ concept. 

## Methdologie semester 1 + 2

In het tweede semester is er ingezoomd in het project op de bediening van de functies
met de acht knoppen. Tijdens het eerste simester werd er gebruik gemaakt van de
methodologie van Roozenburg & Eekels. Deze methodologie heeft een grote
overeenkomst met de een dubble diamond methodologie waar er in de tweede en in de
zesde fase wordt gedivergeerd. In de zesde fase wordt er twee keer gedivergeerd over
twee aspecten van het ontwerp. In de vierde en achtste fase wordt geconvergeerd. In het
tweede semester wordt er nog een laatste maal gedivergeerd en geconvergeerd. Dit
gebeurt in drie develop fases waar er telkens naar een ander aspect gekeken wordt om
verbeteringen van het product te onderzoeken. In de eerste fase (bijlage 5.1) wordt de focus gelegd
op lichaamsgerelateerde parameters. In de tweede fase(bijlage 5.2) wordt er gefocust op de
gebruiksvriendelijkheid van het product. In de derde en laatste fase (bijlage 5.3) wordt er onderzocht
wat de verschillende mogelijke vormen van interactie zijn met het product. Het doel is
om na het doorlopen van deze laatste diamond een finaal concept te bekomen voor de
bediening van de functies in de wagen tijdens het rijden.

![Tijdlijn](https://github.com/arneslos/UCD_SEM1/assets/159801398/dfa6eb69-5282-438c-b359-6e149e888955)

## Develop 1: Human Body
### Doelstellingen
In het begin van de develop fase is er beslist om in te zoomen op het gebruik van de
knoppen tijdens het rijden. De knoppen zullen elk een vooraf vastgelegde functie
hebben. Tijdens de eerste develop fase is de positie en de grote van de knoppen
onderzocht. Het doel van dit onderzoek is om de ideale grote van de knoppen te
bepalen zodat deze niet te groot en afleidend zijn maar wel nog op een makkelijke
manier te bedienen zijn.

### Materiaal & methoden
Om de afstand van de knoppen tot de stoel te bepalen werd er eerst een theoretische
waarde berekend aan de hand van data die in de DiNed databank beschikbaar is. In
deze databank stonden niet precies de waarden die nodig waren dus werden er 2
waarden opgeteld met de nodige formules. De lengte van de arm werd opgeteld bij de
lengte van een gestrekt hand. Om de berekeningen te controleren werd een autostoel
op deze afstand van een dashboard gepositioneerd en nagegaan of een persoon het
dashboard op een comfortabele manier kon raken. Hierna is er ook een test uitgevoerd
om na te gaan hoe groot de knoppen moeten zijn zodat deze nog op een vlotte manier

ingedrukt kunnen worden. Dit is getest door de verschillende maten van de ge-3D-
printte knoppen op een karton “dashboard” te bevestigen en dan de “bestuurder” te

vragen om een bepaalde maat knop in te drukken. De bedoeling was dat de testpersoon
dit zo snel mogelijk deed en zo weinig mogelijk naar het dashboard keek. Er werd dan
genoteerd of de bestuurder erin slaagt om de knop in te drukken. Deze test werd 2 maal
uitgevoerd. De bestuurder zat op twee posities. De eerste positie was 10 centimeter
dichter bij het dashboard. De tweede testopstelling was 10 centimeter verder van het
dashboard dan de theoretisch berekende armlengte.

![439874530_1514420332621611_6437492890605404557_n (1)](https://github.com/arneslos/UCD_SEM1/assets/159801398/c72838c5-09a1-470e-ace3-2629abf582e7) ![442569339_373010415747788_6650690577631553502_n (1)](https://github.com/arneslos/UCD_SEM1/assets/159801398/86d519b4-7730-4df2-bdef-30aa3218ae4c)


### Resultaten
Na het berekenen van de waarde werd er een armlengte tot de vinger van 907
millimeter gevonden met een standaard deviatie van 47,59 millimeter volgens de
populatie van Nederlandse volwassenen, zowel man als vrouw, tussen 20 en 60 jaar. Bij
de eerste test werd er een probleem vastgesteld met de theoretische waarde. De
gegense uit de databank en de berekening is geanalyseerd. Er was een interpretatiefout:
de lengte van de handpalm was twee maal verrekend. Bij de tweede poging is een
aangepaste theoretische lengte van de handpalm toegepast. De afstand van de stoel
tot het dashboard werd verminderd met de lengte van de handpalm. Met deze
opstelling waren de testpersonen in staat om het dashboard aan te raken. Na het testen
van de knop grootte kan er besloten worden dat hoe groter de knop is hoe minder
fouten er worden gemaakt. De knoppen zouden nog groter gemaakt kunnen worden
maar dit kan dan weer voor meer afleiding zorgen aangezien het lcd knoppen zijn die
een beeld weergeven. De afstand van de persoon tot de knoppen had ook een invloed
op het aantal keer dat het gelukt was om de gevraagde maat van knop in te drukken.

**Mean**: 907 mm
**Sd**: 47.59 mm
**P5**: 796 mm
**P95**: 1018 mm
**Populatie**: Dutch Adults, 20-60, mixed


| knopgroote	| fouten bij berekende afstand | fouten bij	kortere afstand | fouten bij langere afstand |
| ------------- | ------------- |  ------------- |  ------------- | 
| XL |	 4 /40 |	4 /40 |	14 /40 |
| M |	 6 /40 |	5 /40 |	18 /40 |
| S |	 8 /40 |	6 /40 |	22 /40 |
| XS |	 15 /40 |	12 /40 |	25 /40 |


De afstand dat de persoon van de knoppen verwijderd is heeft invloed op de aantal
pogingen om de correcte knop in te drukken. Hoe korter de afstand hoe hoger de
kans dat een knop correct wordt ingedrukt.

### Conclusies & implicaties
De geteste theoretische afstand van de schouder tot de knoppen is een afstand die niet
vastgelegd kan worden. Er kan geen rekening gehouden worden met de hoogte van de
bestuurderszetel en het feit dat de bestuurder eventueel problemen kan hebben met de
aftand tot het stuur of tot de pedalen. Uit de resultaten van de testen blijkt dat de beste
keuze voor de maat van knop de XL knoppen zijn. Deze hebben bij een variatie van de
theoretisch berekende afstand die tussen de knoppen en de schouder zit nog steeds de
grootste kans om correct ingedrukt te worden. Bij het rijden zijn wagen en betuurder in
beweging, dit bemoeilijkt het precisie bij het gebruiken van de knoppen. De afmetingen
van de XL knop kunnen nog groter gemaakt worden, om een nog beter slaagpercentage
te krijgen dat de knop correct wordt ingedrukt. Een nog grotere knop kan als afleidend
ervaren worden en hierdoor komt de knop in de uiterste positie nog verder.

#### Product Requirements in verband met ergonomie
Dit onderzoek leid tot een paar product requirements:
- Astand van schouder tot elke knop Mean: 907 mm P5: 796 mm P95: 1018 mm  
- Astand van schouder tot draaiknop: Mean: 907 mm P5: 796 mm P95: 1018 mm 
- Afmetingen knop: h=32 mm, b=34.5 mm
- n=8
- 1 draaiknop dichtst bij de bestuurder: meest gebruikte functie


## Develop 2: Human Mind
### Doelstellingen
Het doel van de tweede develop fase is om een geoptimaliseerd ontwerp te bekomen
en deze in de finale fase te testen. Het geoptimaliseerd ontwerp is bekomen aan de
hand van een conceptueel model, expert reviews en usability tests.

### Materiaal & methoden
De eerste stap was het opstellen van een conceptueel model.

![conceptueel_model_1](https://github.com/arneslos/UCD_SEM1/assets/159801398/fbf1923e-998a-41ce-82c3-e2886aab2fcf)

Dit model werd gebruikt het onderzoek te verduidelijken en de functionaliteit van ons
product binnen het volledige dashboard van de wagen te duiden.

Om de testen in de tweede develop fase af te nemen is er gebruik gemaakt van een
prototype met figma en een 3D-print frame voor een GSM houder. De grote van de
knoppen is gebaseerd op de resultaten van de test van de vorige fase. Het figma
bestand heeft een standaard configuratie van interactieve knoppen. Door deze
standardisatie kan de test voor iedere gebruiker gelijk verlopen en kunnen de resultaten
objectief vergeleken worden. De gekozen functies voor de knoppen waren: de
zetelverwarming van de bestuurder/ passagier bedienen, de voor- of
achterruitverwarming bedienen, het dempen van rolggeluid van de wagen, de
spraakbediening activeren en de airco bedienen. De bediening van de airco werkt met
een menu dat opent als de knop wordt ingedrukt. Dan komt er de keuze om deze aan
of uit te zetten en het volume te bepalen. Om de gebruiker feedback te geven wordt er
gebruik gemaakt van geluiden die met een apparte computer worden weergegeven,
hiermee simuleren zoveel mogelijk een echte wagen.

![image](https://github.com/arneslos/UCD_SEM1/assets/159801398/894bc574-eab0-4b4e-ae51-aff1f3e054f7)

Als eerste stap zijn er twee expert reviews afgenomen. Na de uitleg van het concept
werd aan de experts gevraagd om het concept en het prototype te scores aan de hand
van de heuristieken van Nielsen. De heuristieken die vergeleken werden zijn op
voorhand bepaald. Alleen de meest relevante heuristieken passend bij dit project zijn
gekozen. De heuristieken kregen elk ook een doorslagscore om zo de belangrijkste
focuspunten harder door te laten wegen. 

Na het scoren hebben de experts ook een conceptuele schets van een dashboard
gemaakt. Ze de hebben knoppen getekend en opmerkingen over de functie
doorgegeven. De experts hebben zelf een voorstel van een dashboard met knoppen en
de functies gemaakt. Met de input van de experts is het prototype bijgewerkt en zijn er
verdere user tests uitgevoerd. Bij deze testen krijgt de gebruiker het prototype eerst te
zien. De user overloopt al de knoppen geeft een eigen interpretie van wat hij denkt dat
de functie van elke knop zou kunnen zijn. Tijdens het overlopen van de functies die de
knoppen hebben word de gebruiker telkens gezegd of deze goed of fout is en wat de
functie dan wel is. Na het overlopen word de gebruiker gevraagd om zich in te beelden
dat die aan het rijden is in een wagen. Tijdens de test word de gebruiker gevraagd om
verschillende functies uit te voeren. Er word gewerkt met een Wizard Of Oz methode
waarbij er verschillende geluiden worden afgespeeld als de gebruiker bepaalde
handelingen uitvoert. De handelingen die de gebruiker uitvoert worden ook getimed om
te ondervinden welke functie veel tijd inneemt en dus vereenvoudigd moet worden. Als
de test afgelopen is word de gebruiker bevraagd over hoe deze het prototype ervaren
heeft.

![image](https://github.com/arneslos/UCD_SEM1/assets/159801398/ff418ae2-82c3-4663-9edf-43e1b5ee1c00)


### Resultaten

( evaluatieschema Ruben Rimbout )

| heuristieken	| Score /10 | Doorslag score |
| ------------- | ------------- |  ------------- |
| Laat zien wat er gebeurt |	 6 |	1 x |
| Biedt zekerheid en controle |	 7.5 |	1.2 x |
| Foutpreventie |	 8 |	1 x |
| Flexibiliteit en efficiëntie van gebruik |	 7 |	1.2 x |
| Esthetisch en simpel design |	 6.5 |	1 x |
| Help de gebruiker met het herkennen, oplossen, ... van fouten |	 8 |	1 x |

Totale score: 7.65 / 10

( evaluatieschema Milan Berckmoes  )

| heuristieken	| Score /10 | Doorslag score |
| ------------- | ------------- |  ------------- |
| Laat zien wat er gebeurt |	 7 |	1 x |
| Biedt zekerheid en controle |	 7 |	1.2 x |
| Foutpreventie |	 8 |	1 x |
| Flexibiliteit en efficiëntie van gebruik |	 7.5 |	1.2 x |
| Esthetisch en simpel design |	 7 |	1 x |
| Help de gebruiker met het herkennen, oplossen, ... van fouten |	 7.5 |	1 x |

Totale score: 7.81667 / 10

Uit de expert reviews kwamen er werkpunten naar boven. De plaatsing van de knoppen
was niet logisch, de stoelverwarming van de bestuurder stond links onder en die van de
passagier stond links boven. De expert gaf advies om dit te veranderen. De bestuurder
zetelverwarming komt links boven en de passagier rechts boven. Voor beide experts was
het ook niet duidelijk dat er onderliggende menu’s waren, zoals bij de bediening van de
airco. Dit onderliggend menu maakt het mogelijk om andere functies aan te klikken en
werd ervaren als onoverzichtelijk. Dit kan worden opgelost door de niet gebruikte
knoppen te dimmen wanneer de gebruiker in een menu werkt. Er was ook geen
aanduiding over temperatuur of intensiteit van blazen. De experts merkten op dat
ondanks dat de airco een veelvuldig gebruikte functie is, er geen navigatie naar deze
airco functie aanwezig is. Tijdens het uitvoeren van de user tests bleek dat er veel
onduidelijkheid was rond het instellen van de gewenste temperatuur. Het duurt lang
alvorens je de instelling kan wijzigen omdat je moet doorklikken naar onderliggende
menu's. Voor sommige gebruikers was het sluiten van de menu's niet evident.

### Conclusies & implicaties
De bediening van de Airco was onduidelijk. De bediening met de knoppen ging niet
vlot. Een mogelijke oplossing kan zijn om de omstaande functies zwart te maken en de
bediening van de AC via de draaiknop te laten verlopen. Er moet ook een duidelijk
zichtbare temperatuur en blaasintensiteit aangegeven worden. Er kan ook een navigatie
functie toegevoegd naar de AC. Dit kan eventueel met vooraf ingestelde adressen die
dan op een knop in die menu geprogrammeerd staan. Verder willen we de locatie van de
knoppen op een logischere positie rangschikken. Ook de feedback moet duidelijker laten
verlopen.

![image](https://github.com/arneslos/UCD_SEM1/assets/159801398/d04bf094-b426-42df-b8e7-d7951fe5ada6)


#### Product Requirements ivm ergonomie met de knoppen
Dit onderzoek leid tot een paar product requirements:
- Diameter symbolen : 18 mm
- Bedienen airco < 1 sec
- Locatie knoppen volgens indeling wagen
- Functie draaiknop toevoegen 
- De knop oplichten wanneer de functie bediend is


## Develop 3: Human Senses
### Doelstellingen
Tijdens de laatste develop fase worden de laatste aanpassingen aan het prototype
gemaakt op basis van al de eerder verzamelde informatie uit de vorige fases. Tijdens
deze fase werd er gefocust op de verschillende manieren om een functie uit te voeren
en de feedback die een gebruiker krijgt bij het gebruiken ven functies. Dit gebeurde
door een hiërarchische taakanalyse op te stellen en een verbeterd prototype te maken
met protopie waarbij we opnieuw user tests afnemen. Het doel is om een finaal en
geoptimaliseerd prototype van de knoppen te bekomen.

### Materiaal & methoden
Als eerste stap werd er een functieboom gemaakt om de verschillende handelingen
in kaart te brengen in de verschillende situaties. Er is bij iedere handeling een
vorm van feedback voorzien die hiirbij past.

[Taakanalyse](https://lucid.app/lucidspark/a29f5345-b2c6-4360-82b3-dcbd95d4308d/edit?beaconFlowId=8583B9BEC7D35FA3&invitationId=inv_679c655a-8b6a-4bfd-9d54-b0bca86bb100&page=0_0#)
![Taakanalyse](https://github.com/arneslos/UCD_SEM1/assets/159801398/79563014-12a5-45b4-a089-6af5ac1e5729)

**De belangrijkste waarneming uit de functieboom:** 
Voor elke functie hebben we
minimaal 2 mogelijkheden hoe deze bediend kan worden. Door spraakherkenning of
door een fysieke knop in te drukken. Hiernaast is er ook na elke bediening of
statusverandering van de functie, een manier van feedback door een geluid en een
verandering van kleur.

![image](https://github.com/arneslos/UCD_SEM1/assets/159801398/3bacb924-593b-4120-9d00-ac40e758aa1c)

Om het aangepaste prototype te testen werd er gebruik gamaakt van een nieuw
prototype. Er werd een 3D-print frame gemaakt om een gsm in te monteren Bij dit
prototype werd er ook een draaiknop toegevoegd. Door met protopie zijn er meer
opties op het vlak van feedback en input. De layout van de knoppen werd aangepast op
basis van de feedback in de vorige fase. Er werd ook voor een visuele feedback en audio
gekozen. Daar de gebruikers hiermee moeite hadden in de vorige test. Ook een
navigatiefunctie is toegevoegd. Deze functie heeft een paar vooraf ingestelde adressen
om ze tijdens het rijden snel in te stellen, als de bestuurder een ander adres wilt berijken
kan deze dat ingeven aan de hand van de spraakbediening. De airco functie is ook
bijgewerkt zodat deze aan of uit gaat als de knop wordt ingerdukt en er er een menu
tevoorschijn komt als deze ingedrukt wordt gehouden. In deze menu krijgt de
bestuurder de opties om de blaas intensiteit te verhogen of te verlagen en ook om de
temperatuur te verhogen of te verlagen. De temperatuur wordt ook duidelijk
weergegeven. Dit concept wordt weer getest aan de hand van een wizard of ozz
scenario. De gebruiker wordt opnieuw gevraagd om zich in te beelden dat die aan het
rijden is met een auto en om dan verschillende functies uit te voeren. Dit wordt twee
keer gedaan, één keer waarbij de gebruiker de knoppen gebruikt om de functies te
activeren en één keer waarbij de bebruiker de spraakbediening gebruikt om de functies
te activeren. Bij beide testen wordt er bijgehouden hoeveel tijd de handeling in beslag
neemt om later te vergelijken met elkaar.

[Protopie](https://cloud.protopie.io/p/15cfd1d4a1dbf0fc98e03a7b)

![image](https://github.com/arneslos/UCD_SEM1/assets/159801398/b700a3a4-81bc-4a57-8edd-a3c2ba653c7c)


### Resultaten

Na het testen met dit prototype op de twee verschillende manieren van input werd er
waargenomen dat de test met de test spraakbediening merkelijk langer duurt dan de
test waarbij de knoppen gebruikt werden. Dit komt omdat een functie enkel met
spraakbediening gebruikt kan worden door eerst op de spreek knop te duwen en
daarna de boodschap in te spreken.

- De gemiddelde tijd nodig voor 1 functie te bedienen via een knop =	0.774 s 
- De gemiddelde tijd nodig voor 1 functie te bedienen via de spraakherkenning =	3.132 s 

Tijdens het testen met het prototype waren voor al de gebruikers de bediening van de
functies duidelijk. Behalve de bediening van de airco, hier was er verwarring toen deze
de blaasintensiteit of de temperatuur moesten aanpassen. Met een korte opleiding,
was het probleem weggewerkt.


### Conclusies & implicaties
Uit de test zien we dat de tijd die nodig is om een functie te bedienen aan de hand van
spraakherkenning 3 a 4 keer langer duurt dan via een knop. De feedback van de
testpersonen was het systeem veel gebruiksvriendelijker is als je de functie gebruikt via
stembediening. Om deze reden is er gekozen om de stembediening te behouden.

#### Product Requirements
Dit onderzoek leid tot een paar product requirements:
- Alle functies moeten bedienbaar zijn via je stem
- Alle functies moeten bedienbaar zijn via een knop


## Finale conclusie
Na onze afgelopen weg zijn we tevreden met het resultaat al zijn er hier en daar toch nog onduidelijkheiden. Het is moeilijk in te schatten hoe dit systeem zal samenwerken met de rest van het dashboardconcept. In theorie lijkt het zeker mogelijk uit te voeren en ziet het er een meerwaarde uit aan de rijervaring van zowel bestuurder als passagier, maar theorie is nooit werkelijkheid en zou dit volledig eerst moeten worden uitgewerkt worden om daarna te beslissen of dit een product is die al dan niet op de markt kan gelanceerd worden. 

Op vlak van vooronderzoek (sem.1) lijkt het ons zeker een goede en succesvolle manier om aan de hand van benchmarking, shadowing en interviews zelf het probleem dieper te onderzoeken. Hiermee krijg je naast een breder beeld over de problematiek ook een idee hoe andere ontwerpers en bedrijven hetzelfde idee op hun manier op te lossen. 
Onze gebruikerstesten (sem.2) konden zeker nog geoptimaliseerd worden. We hebben zoveelmogelijk de echte situatie proberen nabootsen met zowel geluid, maar om volledig zeker te kunnen zijn over onze testen zouden deze moeten worden uitgevoerd in een rijdende wagen wat toch moeilijk uit te voeren is. 
Ons product is zeker geen afgewerkt geheel, op vele gebieden kan er nog geoptimaliseerd worden zoals materiaal, interactie via fysieke knoppen wat initieel het doel was, samenwerking met HUD, etc.

Als laatste is het ook niet altijd zeker dat dit concept effectief iets dat toekomstige klanten verkiezen boven een groot scherm in het midden van het dashboard. Doodadat dit concept gestart is uit het probleem van afleiding tijdens het rijden, wat ontdekt is door een Brits onderzoek en niet door de gebruikers zelf, is dit moeilijker in te schatten. 

We willen ook graag iedereen bedanken die meegewerkt heeft bij dit onderzoek, zowel bij de testen als bij feedback. 

[Product Video](https://youtu.be/vIWIUqFRspU)

## Bronnen
(Nws, 2021b) : Nws, V. (2021, 11 maart). Aanraakschermen in je auto bedienen drie keer gevaarlijker dan rijden onder invloed: “Europese regels nodig”. vrtnws.be.

https://www.vrt.be/vrtnws/nl/2021/03/11/aanraakschermen-in-je-auto-bedienen-drie-keergevaarlijker-dan-r/#:~:text=%2D%2D%3A%2D%2D-,Aanraakschermen%20in%20je%20auto%20bedienen%20drie%20keer%20gevaarlijker%20dan%20rijden,het%20risico%20op%20een%20ongeval.

## Bijlagen
- 1 (Google drive): https://drive.google.com/drive/folders/1x8gPw4AJ5K4TxQPy2E_7yjYqFXD9Rf43?usp=sharing
- 2 Figma: https://www.figma.com/file/UazHZrtgUNHXp7b5WrkCnB/Untitled?type=design&nodeid=0%3A1&mode=design&t=L9cifeomLyC9PtCw-1
- 3 Miro: https://miro.com/welcomeonboard/aTl3Sm0yb1lUWmlzU3RwNUQ1ZjByam1nNVM3S0FTNWNCUkhjcFlodUZhdWphd0pWZUpiRG9HanNNSENxYWcwdnwzMDc0NDU3MzY0ODc4MTMxMTU4fDI=?share_link_id=531594994039 

- 4 Discovery
  - 4.1 Design Ethnography
  
    - 4.1.1 [protocol](https://drive.google.com/file/d/1AdVoeefTQNNnNY_dTrXtfLXoVZDjnzLm/view?usp=drive_link)
    
    - 4.1.2 [report](https://drive.google.com/file/d/19WuiClgjZXmVs2_SkV7SUFBsc1OCqoEU/view?usp=drive_link)

  - 4.2 Benchmarking
  
    - 4.2.1 [protocol](https://drive.google.com/file/d/1jO9PHBk6aOt327gKf3AhZUQNIHvjKzZq/view?usp=drive_link)
    
    - 4.2.2 [report](https://drive.google.com/file/d/1wbz_NgpH3xfFmPYBghqxKPV7KHRvV22M/view?usp=drive_link)

  - 4.3 Gebruiker Interviews
    - 4.3.1 [protocol](https://docs.google.com/document/d/1e-_irgPuqvijx_TaQfB4gYeBgC1f_Bq4/edit?usp=drive_link&ouid=107004077216728895200&rtpof=true&sd=true)
    - 4.3.2 [report](https://docs.google.com/document/d/1I5jWhQwQX3hNxWR-BSMEjLxwbaMzzTg465A3xy4uzbk/edit?usp=drive_link)

  - 4.4 Literatuurstudie
    - 4.4.1 [protocol](https://docs.google.com/document/d/1D-tIVRQHIYy5RQ8UibK9qkT87JWk0X5guj7h21v80LQ/edit?usp=drive_link)
    - 4.4.2 [report](https://docs.google.com/document/d/1qE0ca6DeLKIPyJ-GtrByASsIhslU_8xGCBJSwTPISm0/edit?usp=drive_link)

- 5 Definition
  - 5.1 Carboard Prototyping **Develop 1**
    - 5.1.1 [protocol](https://docs.google.com/document/d/1Lanw6UmlXtbWzeWdgII5X2cL_mVmAvAt/edit?usp=drive_link&ouid=107004077216728895200&rtpof=true&sd=true)
    - 5.1.2 [report](https://docs.google.com/document/d/1OMOw0FYqmWkzoKu3faw7BCcyv77aLKBJ/edit?usp=drive_link&ouid=107004077216728895200&rtpof=true&sd=true)

  - 5.2 Figma Prototyping 2 **Develop 2**
    - 5.2.1 [protocol](https://docs.google.com/document/d/1gLTyk-VorgkXucT1mm6HlvAcxBBp0_n8xbfEttkN8yQ/edit?usp=sharing)
    - 5.2.2 [report](https://docs.google.com/document/d/1x4qKzblOtoCEeaBQFFDr1XIEqbnUMAGk/edit?usp=sharing&ouid=116869399543497488712&rtpof=true&sd=true)

  - 5.3 Protopie Prototyping **Develop 3**
    - 5.3.1 [protocol](https://docs.google.com/document/d/1J2uT2bz0IiTtfkOOzEpJFHWi2FQ4PWFlR1IyTbEtWrE/edit?usp=sharing)
    - 5.3.2 [report](https://docs.google.com/document/d/1YVlJD95k1_EuGTGHB7vhReXmIWZ4h71dN8CKy2xkBy4/edit?usp=sharing)
    - 5.3.3 [Taakanalyse](https://lucid.app/lucidspark/a29f5345-b2c6-4360-82b3-dcbd95d4308d/edit?beaconFlowId=8583B9BEC7D35FA3&invitationId=inv_679c655a-8b6a-4bfd-9d54-b0bca86bb100&page=0_0#)
    - 5.3.4 [Protopie](https://cloud.protopie.io/p/15cfd1d4a1dbf0fc98e03a7b)
  - 5.4 Eind Ontwerp
    - 5.4.1 [Product Video](https://youtu.be/vIWIUqFRspU)
