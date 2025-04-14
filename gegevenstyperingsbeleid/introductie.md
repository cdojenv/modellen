# Introductie {#Intro}

In deze introductie worden de gemodelleerde begrippen in het JAGA [gegevenstyperingsbeleid](#gegevenstyperingsbeleid) verbonden in een verhaal, waardoor het model begrijpelijker wordt.

## De context van de gegevens  {#IntroContext}

### Het beschouwingsdomein {#IntroBeschouwingsdomein}

Het primaire uitgangspunt U1 van het [gegevenstyperingsbeleid](#gegevenstyperingsbeleid) is dat inzicht in gegevens, inzicht in het [beschouwingsdomein](#beschouwingsdomein) vereist. Dit beschouwingsdomein bestaat uit alle [objecten](#object) die we relevant vinden, de eigenschappen waarover we [gegevens](#gegeven) vastleggen, en de [objectrelaties](#objectrelatie) tussen deze [objecten](#object).

Een [gegeven](#gegeven) is een vastgelegde uitspraak over een (mogelijk ongetypeerde) eigenschap van een object of objectrelatie, met een beoogde menselijke betekenis.

Hierbij is het belangrijk op te merken dat conform uitgangspunt U2 de objecten, de objectrelaties en de gegevens over die objecten en objectrelaties een eigen (en mogelijk van elkaar verschillende) levenscyclus kennen. De levensduur van de objecten en de relaties daartussen noemen we de [geldigheidstijd](#geldigheidstijd), de levensduur van de gegevens over die objecten en hun relaties noemen we de [registratietijd](#registratietijd).

### Het begrip van ons beschouwingsdomein {#IntroBegrippenkader}

Conform uitgangspunt U3 zijn gegevens altijd uit te drukken in een menselijke taal, waarin begrippen voorkomen met een beoogde betekenis. Die begrippen en hun beoogde betekenis leggen we vast in een [begrippenkader](#begrippenkader), wat bestaat uit de [begrippen](#begrip) die deel uitmaken van dat begrippenkader. Daarmee beschrijven we dus het [beschouwingsdomein](#beschouwingsdomein).

Begrippen in het kader worden gekenmerkt door hun [voorkeursterm](#voorkeursterm), en beschreven door een [begripsbeschrijving](#begripsbeschrijving). Indien mogelijk wordt de definitie van een begrip uit een formele [definitiebron](#definitiebron) overgenomen, conform uitgangspunt U10.

Het kan zijn dat een begrip in een ander begrippenkader bekend staat onder een andere naam. In dat geval leggen we een [taalbinding](#taalbinding) aan die de twee begrippen met elkaar verbindt.

De begrippen worden beschreven door een [gegevensmodelleur](#gegevensmodelleur), in lijn met uitgangspunt U5: Verantwoordelijkheid voor gegevenstypering is belegd. Een gegevensmodelleur is een [persoon in de rol](#persoon-in-rol) in een [gegevenskwaliteit rol](#gegevenskwaliteit-rol) genaamd gegevensmodelleur.

### Het verwerkingsdomein {#IntroVerwerkingsdomein}

Een [verwerkingsdomein](#verwerkingsdomein) is een afgebakend deel van de verwerking van gegevens binnen een organisatie. Het geeft de afbakening weer van de gegevens en hun verwerking (uitwisseling, registratie, creatie, gebruik, vernietiging).

Een verwerkingsdomein bestaat uit alle soorten gegevensverwerkingen, de [gegevensverwerkingstypen](#gegevensverwerkingstype), die binnen [organisatorische activiteiten](#organisatorische-activiteiten) gebeuren.

Een [organisatorische activiteit](#organisatorische-activiteit) wordt gestart of ingericht om een [organisatorische doelstelling](#organisatorische-doelstelling) te behalen.

Een [organisatorische doelstelling](#organisatorische-doelstelling) is een doelstelling om te voldoen aan [wet- en regelgeving](#wet-en-regelgeving), of aan een andere eis die de omgeving of de eigen organisatie oplegt. Die laatste eisen kunnen voortkomen uit [motivatie](#motivatie)s als marktvraag, wensen van de directie, verbetersuggesties et cetera.

Een [organisatorische activiteit](#organisatorische-activiteit) die de overheid onderneemt is altijd *onderhevig* aan wet- en regelgeving:

* óf het is de aanleiding (via de organisatorische doelstelling, bijvoorbeeld omdat de organisatie de taakstelling heeft om een wet uit te voeren),
* óf het is van toepassing doordat we gegevens gaan verzamelen die onderhevig zijn aan bepaalde wet- en regelgeving.

Deze [wet- en regelgeving](#wet-en-regelgeving) leggen we vast. Het kan zijn dat op één [organisatorische activiteit](#organisatorische-activiteit) meer dan één stuk [wet- en regelgeving](#wet-en-regelgeving) van toepassing is, bijvoorbeeld de [[AVG]] én de [[Archiefwet]].

Een [organisatorische doelstelling](#organisatorische-doelstelling) die gebaseerd is op een [motivatie](#motivatie) heet soms ook wel een gebruikersdoel of gebruikersdoeleind. Voorbeelden van [motivatie](#motivatie)s zijn bijvoorbeeld de wens om de reputatie van de organisatie te behouden en verbeteren, om marktaandeel te behouden of vergroten, of om de organisatie in stand te houden.

De organisatorische activiteiten waarin de gegevensverwerkingen plaatsvinden, bepalen de [pragmatische betekenis](#pragmatische-betekenis) van de gegevens die worden verwerkt.

## Gegevens, betekenis en typering {#introGegevenstypering}

### Gegevens en hun betekenis {#IntroGegevensbetekenis}

Een [gegeven](#gegeven) is een vastgelegde uitspraak over een eigenschap van een object of objectrelatie in een bepaald beschouwingsdomein, met een beoogde menselijke betekenis. De gedane uitspraken kunnen we vaak onderbrengen in categorieën met eigen regels en een eigen naam: we kunnen deze uitspraken dus typeren.

Let op dat het typeren van eigenschappen van *objecten* iets anders is dan het typeren van de *uitspraken over hun eigenschappen* en dat we die twee niet mogen verwarren.

Als we een [gegeven](#gegeven) typeren, dan kennen we een naam, betekenis en regels toe aan datgene wat wij typeren. Hoe deze [gegevenstypering](#gegevenstypering) vervolgens verloopt is het onderwerp van het [gegevenstyperingsbeleid](#gegevenstyperingsbeleid).

Het gegevenstyperingsbeleid heeft als doel om een gestructureerde en herhaalbare aanpak te bieden om te komen tot een beschrijving van de betekenis van [gegevens](#gegevens).

De betekenis van gegevens kent meerdere vormen:

* De [normatieve betekenis](#normatieve-betekenis), zoals deze volgt uit wet- en regelgeving, uitvoeringsbeleid en andere normatieve kaderstelling.
* De [intrinsieke betekenis](#intrinsieke-betekenis), zoals deze volgt uit de aard van de gegevens zelf (vorm, structuur, relatie met ander gegevens).
* De [pragmatische betekenis](#pragmatische-betekenis), zoals deze volgt uit het gebruik van de gegevens en de impact die dit gebruik met zich meebrengt.

Uitgangspunt U4 stelt dat het gebruik van gegevens bepalend is voor de betekenis, omdat dit duidelijk maakt wat de gegevens daadwerkelijk voor impact hebben. De [uitvoeringsregels](#uitvoeringsregel) die gegevens gebruiken bepalen dus de pragmatische betekenis. Onderdeel van de gegevenstypering is dus het relateren van de getypeerde gegevens aan het gebruik hiervan in uitvoeringsprocessen, de [organisatorische activiteiten](#organisatorische-activiteit), [uitvoeringsregels](#uitvoeringsregel) en [algoritmen](#algoritme). Een [algoritme](#algoritme) is een reeks bij elkaar behorende uitvoeringsregels die dus gezamenlijk de pragmatische betekenis van de gebruikte gegevens bepalen.

De eindverantwoordelijkheid voor gegevenstypering ligt op bestuurlijk niveau bij de [gegevensverantwoordelijke](#gegevensverantwoordelijke), conform uitgangspunt U6. Aangezien conform uitgangspunt U7 er continu beheer nodig is, is er ook een [gegevensmodelleur](#gegevensmodelleur) nodig die permanent bezig is met de gegevenstypering.

Organisaties die samenwerken met andere organisaties moeten onderling afspraken maken over hoe de gegevenstypering wordt ingevuld, conform uitgangspunt U8.

De gegevenstypering wordt openbaar gemaakt, conform uitgangspunt U9.

### Gegevenstypering en groepering {#IntroGegevenstypen}

Een [elementair gegeven](#elementair-gegeven) is een [vastgelegde uitspraak](#vastgelegde-uitspraak) over een [getypeerde eigenschap](#getypeerde-eigenschap) van een object of objectrelatie, bijvoorbeeld "de haarkleur van Joop is donkerblond."

Een [gegevenstype](#gegevenstype) is een typering van gelijksoortige [elementaire gegevens](#elementaire-gegevens) die voor een object van toepassing zijn. Elementaire gegevens met uitspraken over de haarkleur van personen leidt tot het gegevenstype "haarkleur" van een [objecttype](#objecttype) "persoon".

Een [objecttype](#objecttype) is een typering van een groep gelijksoortige [objecten] in de werkelijkheid die binnen een [beschouwingsdomein] relevant zijn.

Gegevens zijn óf [gestructureerde gegevens](#gestructureerde-gegevens) óf [ongestructureerde gegevens](#ongestructureerde-gegevens). Een groep gestructureerde gegevens bestaat uitsluitend uit elementaire gegevens. Een groep van elementaire gegevens die worden verwerkt als eenheid, noemen we een [gegevensobject](#gegevensobject).

Een groep ongestructureerde gegevens kan ook uit niet-elementaire gegevens bestaan. Elke groepering van gegevens, ongeacht structuur, is een [informatieobject](#informatieobject). Een gegevensobject is dus zelf ook een informatieobject.

Merk op dat een gegevensobject dus alleen gestructureerde gegevens bevat, terwijl een informatieobject zowel gestructureerde als ongestructureerde gegevens kan bevatten. De gestructureerde gegevens zijn dan weer gegevensobjecten.

Een gegevensobject kan een relatie hebben met een ander gegevensobject, bijvoorbeeld omdat het metadata betreft over het andere gegevensobject, of omdat er een hiërarchische relatie bestaat. Zo is bijvoorbeeld een order een gegevensobject met een relatie met orderregels, die ook weer gegevensobjecten zijn. De samenstelling van de order en de orderregels is zelf een informatieobject, wat ook ongestructureerde gegevens zoals een logo of kleurgebruik kan omvatten.

De gegevens in een gegevensobject hoeven geen uitspraken te zijn die allemaal over hetzelfde object gaan. In een gegevensobject kun je dus indien gewenst zowel de gegevens over het object als over het gegevensobject zelf plaatsen.

### Gegevenssets en gegevenselementen {#IntroGegevenssets}

Als een groep gegevens in samenhang beheerd worden door één organisatie dan noemen we dat een [gegevensset](#gegevensset). Voor elke gegevensset is er een [gegevensverantwoordelijke](#gegevensverantwoordelijke) functionaris die de verantwoordelijkheid draagt voor het beheer op en de kwaliteit van die gegevensset. De gegevensverantwoordelijke is ook eindverantwoordelijk voor een actuele, juiste en betrouwbare beschrijving van deze gegevenssets.

Een gegevensset bevat gegevenselementen. Een [gegevenselement](#gegevenselement) is een categorie van gegevens uit een gegevensset (bijv. persoonsgegevens), die in één of meer [organisatorische activiteiten](#organisatorische-activiteit) worden verwerkt. Een gegevenselement wordt gespecificeerd door één of meer gegevenstypen en gekenmerkt door de gegevenselementnaam.

Een [kritiek gegevenselement](#kritiek-gegevenselement) is een [gegevenselement](#gegevenselement) dat vanwege het gebruiksdoeleind of wettelijke vereisten van cruciaal belang is voor het functioneren, de besluitvorming of de strategische doelen van een organisatie of keten.

De gegevenselementen die nodig zijn voor een [gegevensverwerking](#gegevensverwerking) zijn (voor de [organisatorische activiteit](#organisatorische-activiteit) die die gegevens nodig heeft) dus kritieke gegevenselementen.

Iets anders geformuleerd is een kritiek gegevenselement dus een gegevenselement binnen een gegevensverwerking die nodig is voor het bereiken van een [organisatorische doelstelling](#organisatorische-doelstelling), door middel van een specifieke organisatorische activiteit, en alleen binnen de context van een [gegevensverwerking](#gegevensverwerking) voor die [organisatorische activiteit](#organisatorische-activiteit) is het een [kritiek gegevenselement](#kritiek-gegevenselement).

In het gegevenskwaliteitsbeleid wordt dieper ingegaan op kritieke gegevenselementen en hun relatie met gegevenskwaliteit.
