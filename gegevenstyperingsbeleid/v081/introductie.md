# Introductie {#Intro}

In deze introductie worden de gemodelleerde begrippen in het JAGA [gegevenstyperingsbeleid](https://jenvgegevens.pleio.nl/page/view/2775c681-1f4a-4819-8776-d7d93e81ea90/gegevenstypering) verbonden in een verhaal, waardoor het model begrijpelijker wordt. De uitgangspunten die in dit informatiemodel worden gebruikt komen uit dat beleid.

## De context van de gegevens  {#IntroContext}

### Het beschouwingsdomein {#IntroBeschouwingsdomein}

Het primaire uitgangspunt U1 van het [gegevenstyperingsbeleid](#gegevenstyperingsbeleid) is dat inzicht in gegevens, allereerst inzicht in het [beschouwingsdomein](#beschouwingsdomein) vereist. Dit beschouwingsdomein betreft alle [objecten](#object) die we relevant vinden, de relevante [objectrelaties](#objectrelatie) tussen deze [objecten](#object), en alle eigenschappen van die objecten en objectrelaties waarover we [gegevens](#gegeven) vastleggen.

Een [gegeven](#gegeven) is een [vastgelegde uitspraak](#vastgelegde-uitspraak) over een eigenschap van een object of objectrelatie uit een bepaald beschouwingsdomein. Een gegeven heeft een beoogde menselijke betekenis. In het gegevenstyperingsbeleid beschouwen we overigens alleen getypeerde eigenschappen, d.w.z. eigenschappen die betrekking hebben op alle voorkomens van een bepaalde eigenschap op een object.

Hierbij is het belangrijk op te merken dat conform uitgangspunt U2 de objecten en hun objectrelaties en vervolgens de gegevens en gegevensobjecten met gegevens over die objecten en hun objectrelaties een eigen (en mogelijk van elkaar verschillende) levenscyclus kennen. De levensduur van de objecten en de relaties daartussen noemen we de [geldigheidstijd](#geldigheidstijd), de levensduur van de gegevens over die objecten en hun relaties noemen we de [registratietijd](#registratietijd).

Het beschouwingsdomein bepaalt hiermee het bereik van ons de in gegevens vastgelegde werkelijkheid, en ook van ons begrip van die werkelijkheid.

### De betekenis van gegevens {#IntroBetekenis}

Gegevens kunnen op meerdere manieren betekenis krijgen:

* De [normatieve betekenis](#normatieve-betekenis) volgt uit de definitie zoals vastgelegd in [wet- en regelgeving](#wet-en-regelgeving), uitvoeringsbeleid of andere normatieve kaderstelling;
* De [praktische betekenis](#praktische-betekenis) volgt uit het gebruik van de gegevens en de impact die dit gebruik met zich meebrengt. Het is de betekenis van een gegeven in een bepaalde context, dus in een specifieke situatie of beschouwingsdomein, die kan veranderen indien we van context veranderen. Bij het bepalen van de praktische betekenis van een gegeven zijn "wie, wat, waar, hoe en wanneer" belangrijke vragen.
* De [intrinsieke betekenis](#intrinsieke-betekenis) volgt uit de aard van de gegevens zelf, zoals de logische en technische vorm, structuur, en relatie met andere gegevens.

De betekenis van gegevens wordt conform uitgangspunt U3, uitgedrukt in een menselijke taal, als begrippen met een beoogde betekenis. Die leggen we vast in een [begrippenkader](#begrippenkader), wat bestaat uit de [begrippen](#begrip). Daarmee beschrijven we dus de objecten die samen het [beschouwingsdomein](#beschouwingsdomein) vormen, inclusief hun onderlinge relaties en hun eigenschappen.

Begrippen in een begrippenkader worden daarbinnen gekenmerkt door hun [voorkeursterm](#voorkeursterm), en beschreven door een [begripsbeschrijving](#begripsbeschrijving). Indien mogelijk wordt de definitie van een begrip uit een formele [definitiebron](#definitiebron) overgenomen, conform uitgangspunt U10.

Een vergelijkbaar begrip kan ook bestaan in een ander beschouwingsdomeinen of begrippenkader, maar  mogelijk met een andere voorkeursterm of afwijkende begripsbeschrijving. In dat geval kunnen we een [taalbinding](#taalbinding) aanleggen die aangeeft op welke manier je de twee begrippenkaders met elkaar kan verbinden. Begrippen hoeven niet één op één op elkaar te passen, zolang we maar kunnen bepalen hoe we van het ene begrippenkader naar het andere kunnen komen, zodat we de [semantische interoperabiliteit](#semantische-interoperabiliteit) van de domeinen kunnen borgen.

De [herleidbaarheid van de normatieve betekenis](#herleidbaarheid-normatieve-betekenis) van een begrip, evenals de [herleidbaarheid van de praktische betekenis](#herleidbaarheid-praktische-betekenis), wordt geborgd met verwijzingen naar de relevante administraties. De [herleidbaarheid van de intrinsieke betekenis](#herleidbaarheid-intrinsieke-betekenis) van gegevens wordt geborgd door een correcte [gegevensmodellering](#gegevensmodellering), in combinatie met verwijzingen naar de [normatieve](#normatieve-betekenis) en [praktische betekenis](#praktische-betekenis).

### Het verwerkingsdomein {#IntroVerwerkingsdomein}

Een [verwerkingsdomein](#verwerkingsdomein) is een afgebakend deel van de verwerking van gegevens binnen een organisatie. Het geeft de afbakening weer van de gegevens en hun verwerking (uitwisseling, registratie, creatie, gebruik, vernietiging). Het bestaat uit alle soorten gegevensverwerkingen, de [gegevensverwerkingstypen](#gegevensverwerkingstype), die binnen [organisatorische activiteiten](#organisatorische-activiteiten) gebeuren.

Dit verwerkingsdomein is belangrijk omdat binnen de gegevensverwerkingen die in het verwerkingsdomein plaatsvinden de [praktische betekenis](#praktische-betekenis) wordt bepaald van de gegevens die binnen het domein worden verwerkt, zoals ook gesteld in uitgangspunt U4: het gebruik van gegevens is bepalend voor de betekenis, omdat dit duidelijk maakt wat de gegevens daadwerkelijk voor impact hebben. Die impact is helder als iemand geen uitkering krijgt op grond van een foutief ingevoerd gegeven, of betaalde toeslagen worden teruggevorderd door een verkeerde interpretatie van de ingevoerde gegevens. Maar het gaat ook om bijvoorbeeld de manier waarop gegevens worden ingevoerd, of in welke vorm.

De [praktische betekenis](#praktische-betekenis) van gegevens volgt dus uit het gebruik van gegevens en de impact van dat gebruik in de verwerking van die gegevens binnen de organisatie. Aangezien die verwerkingen plaatsvinden binnen een [organisatorische activiteit](#organisatorische-activiteit) die ontstaan is om een reden, is de praktische betekenis van gegevens primair afgeleid van de grondslag van die [organisatorische activiteit](#organisatorische-activiteit), namelijk de [organisatorische doelstelling](#organisatorische-doelstelling) waarvoor die [organisatorische activiteit](#organisatorische-activiteit) wordt gestart of ingericht.

Een belangrijk onderdeel van de gegevenstypering is dus het relateren van de getypeerde gegevens aan het gebruik hiervan in de uitvoeringsprocessen, dus in de [organisatorische activiteiten](#organisatorische-activiteit), de [uitvoeringsregels](#uitvoeringsregel) en [algoritmen](#algoritme). Een [algoritme](#algoritme) is een reeks bij elkaar behorende uitvoeringsregels die dus gezamenlijk de praktische betekenis van de gebruikte gegevens bepalen.

### Verantwoordelijkheden

Omdat de impact van verkeerde omgang met gegevens zo groot is, stelt uitgangspunt U5 dat het beleggen van de verantwoordelijkheid voor de gegevenstypering noodzakelijk is voor een doelmatige en verantwoorde verwerking van gegevens, en uiteindelijk dus ook voor de rechtmatige verwerking van die gegevens. Er moet dus een eindverantwoordelijke zijn voor het beschrijven van de begrippen en (daarmee) het toekennen van betekenis aan de gegevens. Deze eindverantwoordelijke heeft de rol van [gegevensverantwoordelijke](#gegevensverantwoordelijke). Deze is verantwoordelijk voor de naleving van de [normatieve betekenis](#normatieve-betekenis) in de praktijk, dus de samenhang tussen de [normatieve betekenis](#normatieve-betekenis) en de [praktische betekenis](#praktische-betekenis). De eindverantwoordelijkheid voor gegevenstypering en het toeschrijven van betekenis aan gegevens ligt op bestuurlijk niveau bij de [gegevensverantwoordelijke](#gegevensverantwoordelijke), conform uitgangspunt U6.

Aangezien conform uitgangspunt U7 er continu beheer nodig is, is er ook een [gegevensmodelleur](#gegevensmodelleur) nodig die permanent bezig is met de gegevenstypering. De gegevensverantwoordelijke stelt daartoe iemand aan die de gegevenstypering uitvoert en beschrijft wat begrippen betekenen, bijvoorbeeld een [persoon in rol](#persoon-in-rol) in een [gegevenskwaliteit rol](#gegevenskwaliteit-rol) genaamd gegevensmodelleur. Hiermee wordt de samenhang met de [intrinsieke betekenis](#intrinsieke-betekenis) geborgd.

Een actuele en correct uitgevoerde [gegevenstypering](#gegevenstypering-0) is een voorwaarde om het [gegevenskwaliteitsproces](#gegevenskwaliteitsproces) uit te kunnen voeren. Als de normatieve en intrinsieke betekenis van gegevens niet bekend is, is het onmogelijk om te bepalen of de vastgelegde gegevens daarmee overeenstemmen en dus als correct kunnen worden beschouwd.

In het [gegevensbeleid](#gegevensbeleid) van een organisatie wordt in meer detail uitgewerkt hoe men de verantwoordelijkheid voor de omgang met gegevens (inclusief de [metadata](#metadata)) in de organisatie invult.

Organisaties die samenwerken met andere organisaties moeten onderling afspraken maken over hoe de gegevenstypering wordt ingevuld, conform uitgangspunt U8.

De gegevenstypering wordt openbaar gemaakt, conform uitgangspunt U9. Dit maakt het eenvoudiger voor andere organisaties om samen te werken. Publicatie mag alleen achterwege worden gelaten als de publicatie een onevenredige inspanning vereist of vanwege wettelijke beperkingen niet is toegestaan.

### organisatorische activiteiten en doelstellingen {#IntroDoelstellingen}

Een [organisatorische doelstelling](#organisatorische-doelstelling) is een doelstelling om te voldoen aan [wet- en regelgeving](#wet-en-regelgeving), of aan een andere eis die de omgeving of de eigen organisatie oplegt die niet voortkomt uit wet- en regelgeving, een [motivatie](#motivatie). Een [organisatorische doelstelling](#organisatorische-doelstelling) die gebaseerd is op een [motivatie](#motivatie) heet soms ook wel een gebruikersdoel of gebruikersdoeleind. Voorbeelden van [motivatie](#motivatie)s zijn bijvoorbeeld de wens om de reputatie van de organisatie te behouden en verbeteren, om marktaandeel te behouden of vergroten, of om de organisatie in stand te houden.

Een [organisatorische activiteit](#organisatorische-activiteit) die de overheid onderneemt is altijd verbonden met de relevante wet- en regelgeving:

* óf het is de aanleiding (via de organisatorische doelstelling, bijvoorbeeld omdat de organisatie de taakstelling heeft om een wet uit te voeren),
* óf het is van toepassing doordat we gegevens gaan verzamelen die onderhevig zijn aan bepaalde wet- en regelgeving.

Deze [wet- en regelgeving](#wet-en-regelgeving) leggen we vast. in de praktijk zal op één [organisatorische activiteit](#organisatorische-activiteit) meer dan één stuk [wet- en regelgeving](#wet-en-regelgeving) van toepassing zijn, bijvoorbeeld de [[AVG]] én de [[Archiefwet]].

De [wet- en regelgeving](#wet-en-regelgeving) die de aanleiding vormt of van toepassing is op een [organisatorische activiteit](#organisatorische-activiteit), bepaalt de [normatieve betekenis](#normatieve-betekenis) van de gegevens die onder die wet- en regelgeving wordt verwerkt.

## Gegevens, betekenis en typering {#introGegevenstypering}

### Gegevens en hun betekenis {#IntroGegevensbetekenis}

Een [gegeven](#gegeven) is een [vastgelegde uitspraak](#vastgelegde-uitspraak) over een eigenschap van een object of objectrelatie in een bepaald beschouwingsdomein, met een beoogde menselijke betekenis. De gedane uitspraken kunnen we vaak onderbrengen in categorieën met eigen regels en een eigen naam: we kunnen deze uitspraken dus gaan typeren.

Let op dat het typeren van *eigenschappen van objecten* iets anders is dan het typeren van de *uitspraken over eigenschappen van objecten*, dus de gegevens. Als we eigenschappen typeren, dan zeggen we bijvoorbeeld dat elk persoon een persoonsnaam heeft. Als we de uitspraken die we vast willen leggen gaan typeren, dan stellen we daarmee eisen aan de vastlegging van het begrip "persoonsnaam".

Uitgangspunt U4 stelt verder dat het gebruik van gegevens bepalend is voor de betekenis, omdat dit duidelijk maakt wat de gegevens daadwerkelijk voor impact hebben. Onderdeel van de gegevenstypering is dus het relateren van de getypeerde gegevens aan het gebruik hiervan in uitvoeringsprocessen, de [organisatorische activiteiten](#organisatorische-activiteit), [uitvoeringsregels](#uitvoeringsregel) en [algoritmen](#algoritme). Een [algoritme](#algoritme) is dan feitelijk een reeks bij elkaar behorende uitvoeringsregels die (vaak geautomatiseerd) gezamenlijk de praktische betekenis van de gebruikte gegevens bepalen.

Kortom, als we een [gegeven](#gegeven) typeren, dan kennen we dus een naam, betekenis, vorm en randvoorwaarden toe aan datgene wat wij typeren, en we geven aan hoe deze gegevens worden gebruikt in processen en (beleids)regels. Hoe deze [gegevenstypering](#gegevenstypering) vervolgens verloopt is het onderwerp van het [gegevenstyperingsbeleid](#gegevenstyperingsbeleid).

Het gegevenstyperingsbeleid heeft als doel om een gestructureerde en herhaalbare aanpak te bieden om te komen tot een beschrijving van de betekenis van [gegevens](#gegevens).

### Gegevenstypering en groepering {#IntroGegevenstypen}

Een [elementair gegeven](#elementair-gegeven) is een [vastgelegde uitspraak](#vastgelegde-uitspraak) over een [getypeerde eigenschap](#getypeerde-eigenschap) van een object of objectrelatie, bijvoorbeeld "de haarkleur van Joop is donkerblond."

Een [gegevenstype](#gegevenstype) is een typering van gelijksoortige [elementaire gegevens](#elementaire-gegevens) die voor een object van toepassing zijn. Elementaire gegevens met uitspraken over de haarkleur van personen leidt tot het gegevenstype "haarkleur" van een [objecttype](#objecttype) "persoon".

Een [objecttype](#objecttype) is een typering van een groep gelijksoortige [objecten] in de werkelijkheid die binnen een [beschouwingsdomein] relevant zijn.

Gegevens zijn óf [gestructureerde gegevens](#gestructureerde-gegevens) óf [ongestructureerde gegevens](#ongestructureerde-gegevens). Een groep gestructureerde gegevens bestaat uitsluitend uit elementaire gegevens. Een groep van elementaire gegevens die worden verwerkt als eenheid, noemen we een [gegevensobject](#gegevensobject).

Een groep ongestructureerde gegevens kan ook uit niet-elementaire gegevens bestaan. Elke groepering van gegevens, ongeacht structuur, is een [informatieobject](#informatieobject). Een gegevensobject is dus zelf ook een informatieobject.

Merk op dat een gegevensobject dus alleen gestructureerde gegevens bevat, terwijl een informatieobject zowel gestructureerde als ongestructureerde gegevens kan bevatten. De gestructureerde gegevens zijn dan weer gegevensobjecten.

Een gegevensobject kan een relatie hebben met een ander gegevensobject, bijvoorbeeld omdat het [metadata](#metadata) betreft over het andere gegevensobject, of omdat er een hiërarchische relatie bestaat. Zo is bijvoorbeeld een order een gegevensobject met een relatie met orderregels, die ook weer gegevensobjecten zijns. De samenstelling van de order en de orderregels is zelf een informatieobject, wat ook ongestructureerde gegevens zoals een logo of kleurgebruik kan omvatten.

De gegevens in een gegevensobject hoeven geen uitspraken te zijn die allemaal over hetzelfde object gaan. In een gegevensobject kun je dus indien gewenst zowel de gegevens over het object als over het gegevensobject zelf plaatsen.

### Gegevenssets en gegevenselementen {#IntroGegevenssets}

Als een groep gegevens in samenhang beheerd worden door één organisatie dan noemen we dat een [gegevensset](#gegevensset). Voor elke gegevensset is er een [gegevensverantwoordelijke](#gegevensverantwoordelijke) functionaris die de verantwoordelijkheid draagt voor het beheervan die gegevensset, en daarmee o.a. dus voor de kwaliteit, betrouwbaarheid, integriteit en veiligheid. De gegevensverantwoordelijke is ook eindverantwoordelijk voor een actuele, juiste en betrouwbare beschrijving van deze gegevenssets.

Een gegevensset bevat gegevenselementen. Een [gegevenselement](#gegevenselement) is een categorie van gegevens uit een gegevensset (bijv. persoonsgegevens), die in één of meer [organisatorische activiteiten](#organisatorische-activiteit) worden verwerkt. Een gegevenselement wordt gespecificeerd door één of meer gegevenstypen en gekenmerkt door de gegevenselementnaam.

Een [kritiek gegevenselement](#kritiek-gegevenselement) is een [gegevenselement](#gegevenselement) dat vanwege het gebruiksdoeleind of wettelijke vereisten van cruciaal belang is voor het functioneren, de besluitvorming of de strategische doelen van een organisatie of keten.

De gegevenselementen die nodig zijn voor een [gegevensverwerking](#gegevensverwerking) zijn (voor de [organisatorische activiteit](#organisatorische-activiteit) die die gegevens nodig heeft) dus kritieke gegevenselementen.

Iets anders geformuleerd is een kritiek gegevenselement dus een gegevenselement binnen een gegevensverwerking die nodig is voor het bereiken van een [organisatorische doelstelling](#organisatorische-doelstelling), door middel van een specifieke organisatorische activiteit, en alleen binnen de context van een [gegevensverwerking](#gegevensverwerking) voor die [organisatorische activiteit](#organisatorische-activiteit) is het een [kritiek gegevenselement](#kritiek-gegevenselement).

In het gegevenskwaliteitsbeleid wordt dieper ingegaan op kritieke gegevenselementen en hun relatie met gegevenskwaliteit.

### Gegevensmodellering

Een complete gegevensmodellering bestaat uit vier typen modellen:

* een [semantisch model](#semantisch-model), uitgedrukt in bijvoorbeeld [[W3C-SKOS]] of [[NL-SBB]];
* een [conceptueel model](#conceptueel-model), uitgedrukt in bijvoorbeeld [[MIM]] niveau 2, [Fact-based modeling](#fact-based-modeling), [Unified Modeling Language](#unified-modeling-language), [Entity-Relationship Modeling](#entity-relationship-modeling), [Web Ontology Language](#web-ontology-language), [Shapes Constraint Language](#shapes-constraint-language) et cetera.
* een [logisch gegevensmodel](#logisch-gegevensmodel), uitgedrukt in bijvoorbeeld [[MIM]] niveau 3, [Fact-based modeling](#fact-based-modeling), [Unified Modeling Language](#unified-modeling-language), [Entity-Relationship Modeling](#entity-relationship-modeling), [Web Ontology Language](#web-ontology-language), [Shapes Constraint Language](#shapes-constraint-language) et cetera.
* een [technisch gegevensmodel](#technisch-gegevensmodel), uitgedrukt in een vorm die afhankelijk is van de gekozen implementatie.

Hierin wordt de betekenis van gegevens als volgt vastgelegd:

* De [normatieve betekenis](#normatieve-betekenis) wordt geduid in het [semantisch model](#semantisch-model) en vaak gecommuniceerd met behulp van het [conceptueel model](#conceptueel-model).
* De [praktische betekenis](#praktische-betekenis) wordt geduid in de relatie tussen de verschillende gegevensmodellen en de bijbehorende [bedrijfsregelmodellen](#bedrijfsregelmodel) en [procesmodellen](#procesmodel).
* De [intrinsieke betekenis](#intrinsieke-betekenis) wordt nader gespecificeerd in een [logisch gegevensmodel](#logisch-gegevensmodel) en [technisch gegevensmodel](#technisch-gegevensmodel).
