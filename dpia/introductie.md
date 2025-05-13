# Introductie

In deze introductie worden de gemodelleerde gegevens verbonden in een verhaal, waardoor het model begrijpelijker wordt. Dit wordt gedaan voor de [DPIA](#IntroDPIA) en de [pre-scan DPIA](#IntroPre-scanDPIA).

## DPIA {#IntroDPIA}

Een Data Protection Impact Assessment ([DPIA](#dpia)) is een vastlegging van de impact die een bepaalde [gegevensverwerking](#gegevensverwerking) heeft of kan hebben op de rechten en vrijheden van natuurlijke personen, waaronder het recht op privacy.

In deze specificatie wordt beschreven uit welke gegevens een DPIA is opgebouwd, en hoe deze zich onderling verhouden, op het conceptuele en semantische niveau. De beschrijving zal per paragraaf gebeuren, conform de indeling in het [[ModelDPIARijksdienst]].

### 00. Algemeen {#IntroAlgemeen}

Een [DPIA](#dpia) omvat altijd een aantal gemeenschappelijke elementen, die hier worden beschreven. Deze gegevens worden vaak op de omslag of in het eerste deel van de DPIA geplaatst.

Een DPIA wordt uniek gekenmerkt door een [DPIA-code](#DPIA-code).

Een DPIA heeft:

* Een [DPIA inleiding](#dpia-inleiding) met een inleiding over het hoe en waarom van de DPIA.
* Een [DPIA managementsamenvatting](#dpia-managementsamenvatting).

Verder omvat de DPIA informatie over:

* De [Organisatorische Activiteit](#organisatorische-activiteit) waar de DPIA betrekking op heeft.
* De [DPIA opslaglocatie](#dpia-opslaglocatie) waar de DPIA zelf wordt opgeslagen.
* De [Versie](#versie) van de DPIA.
* Een [DPIA status](#dpia-status) die aangeeft of de verwerkingsverantwoordelijke(n) wel of niet akkoord zijn gegaan met de DPIA. Het akkoord gaan van een verwerkingsverantwoordelijke met de DPIA wordt aangegeven door de aanwezigheid van een ondertekende [akkoordverklaring](#akkoordverklaring) met een geldige [datum akkoordverklaring](#datum-akkoordverklaring).
* Een [DPIA dossier](#dpia-dossier) met de documenten die betrekking hebben op de DPIA.

Een  [DPIA dossier](#dpia-dossier) omvat mogelijk vele documenten. Van documenten leggen we een aantal zaken vast:

* De [documentcode](#documentcode) die een document uniek identificeert.
* De [document naam](#document-naam), [document versie](#document-versie) en [document soort](#document-soort) zijn verplicht.
* Indien bekend wordt de [document locatie](#document-locatie) van documenten in het dossier vastgelegd, voor zover dit niet de [DPIA opslaglocatie](#dpia-opslaglocatie) is.

Er zijn vele partijen betrokken bij het opstellen van de DPIA. Deze worden ook benoemd in de DPIA. Het gaat met name om de volgende partijen en functies:

* Een [verwerkingsverantwoordelijke die DPIA opstelt](#verwerkingsverantwoordelijke-die-dpia-opstelt). 
* De [verwerkingsverantwoordelijke](#verwerkingsverantwoordelijke) heeft een [documentbeheerder](#documentbeheerder).
* Daarnaast heeft deze [partij](#partij) vaak (maar niet altijd) een [functionaris voor gegevensbescherming](#functionaris-voor-gegevensbescherming). 
* Een [functionaris voor gegevensbescherming](#functionaris-voor-gegevensbescherming) is een [persoon](#persoon) die werkt voor een [partij](#partij) die betrokken is bij de [DPIA](#dpia) in de rol van functionaris voor gegevensbescherming, waarvan mogelijk de [organisatorische eenheid](#organisatorische-eenheid) bekend is. Een [functionaris voor gegevensbescherming](#functionaris-voor-gegevensbescherming) stelt een [advies FG](#advies-fg) op.
* De overige [verwerkingsverantwoordelijken bij de DPIA](#verwerkingsverantwoordelijke-bij-dpia).
* De [betrokken functies bij opstellen DPIA](#betrokken-functies-bij-opstellen-dpia).
* De genoemde functies zijn [functies in de organisatorische eenheid van een partij](#functie-in-organisatorische-eenheid-van-partij). Dat is dus een functie bij een team of afdeling van een organisatie.
* Voor al die functies is er mogelijk een [persoon](#persoon) bekend die die functie bekleed, de [persoon in functie](#persoon-in-functie).

Voor elke [partij](#partij) wordt ook de [naam](#partij-naam) vastgelegd.

### 01. Voorstel {#IntroVoorstel}

Paragraaf 1 van het rijksmodel voor de [DPIA](#dpia) bevat het voorstel. Een [voorstel](#voorstel) beschrijft waar een [DPIA](#dpia) over gaat, op hoofdlijnen, hoe het voorstel tot stand is gekomen en wat de beweegredenen zijn achter de totstandkoming van het voorstel.

### 02. Persoonsgegevens {#IntroPersoonsgegevens}

Paragraaf 2 van het rijksmodel voor de [DPIA](#dpia) bevat een beschrijving van de [persoonsgegevens die onderdeel zijn van de DPIA](#persoonsgegeven-is-onderdeel-van-dpia). Deze zijn betrokken bij de gegevensverwerkingen in de DPIA.

Daarnaast bevat elke DPIA de [categorieën betrokkenen in de DPIA](#categorie-betrokkenen-in-dpia). Dit zijn bijvoorbeeld medewerkers, slachtoffers, verdachten etc. die als categorie worden beschreven. Indien ze kwetsbaar zijn, wordt dit vastgelegd in de [kwetsbaarheid categorie betrokkenen](#kwetsbaarheid-categorie-betrokkenen).

Een [persoonsgegeven](#persoonsgegeven) wordt uniek gekenmerkt door een [persoonsgegeven naam](#persoonsgegeven-naam).

Verder leggen we in een DPIA over een [persoonsgegeven](#persoonsgegeven) altijd de volgende gegevens vast:

* De bijbehorende [categorie betrokkenen](#persoonsgegeven-van-categorie-betrokkenen).
* De [categorie van persoonsgegevens](#categorie-van-persoonsgegevens).
* Of de [bron persoonsgegevens](#bron-persoonsgegevens) de betrokkene zelf is, of dat deze van een andere partij afkomstig zijn.
* Het [type persoonsgegeven](#type-persoonsgegeven) op basis van de [classificatie](#classificatie)s.
* In de context van een DPIA kan het type anders zijn dan in een andere context. Daarom leggen we ook het [type persoonsgegeven in de context van de DPIA](#type-persoonsgegeven-in-context-van-dpia) vast.
* Het [oorspronkelijk verwerkingsdoeleinde](#oorspronkelijk-verwerkingsdoeleinde).

Een [gegevenstype](#gegevenstype) heeft een [classificatie](#classificatie) die aangeeft of het gegevenstype een persoonsgegeven is. Indien een gegevenstype persoonsgegevens betreft geven we dat aan middels een [classificatie persoonsgegevens](#classificatie-persoonsgegevens) met waarde 'bevat persoonsgegevens'. 

Een [classificatie persoonsgegevens](#classificatie-persoonsgegevens) met waarde 'bevat persoonsgegevens' kan verder worden getypeerd door een [classificatie type persoonsgegevens](#classificatie-type-persoonsgegevens) die aangeeft of het gaat om bijzondere, gevoelige, strafrechtelijke, gewone persoonsgegevens, of om nationale identificatienummers. Deze classificatie kan voor hetzelfde gegevenstype per DPIA verschillend zijn, omdat de context anders is. Een BSN in een lijst met gedetineerden heeft een andere lading en gevoeligheid dan hetzelfde BSN in een lijst met winnaars van de WK-poule op kantoor.

Indien de [persoonsgegevens via een betrokken partij](#persoonsgegeven-via-betrokken-partij) zijn gekomen, leggen we ook de volgende gegevens vast:

* De [partij](#persoonsgegeven-via-betrokken-partij) die de persoonsgegevens levert.
* Het daarbij betrokken [brontool- en/of platform](#bron-tool-platform).
* De [rechtsgrond verstrekking](#rechtsgrond-verstrekking) op basis waarvan de verstrekking plaatsvindt.

### 03. Gegevensverwerkingen {#IntroGegevensverwerkingen}

Paragraaf 3 van het rijksmodel voor de [DPIA](#dpia) bevat een beschrijving van de manier waarop de gegevensverwerkingen verlopen. Elke [DPIA heeft betrekking op gegevensverwerking](#dpia-heeft-betrekking-op-gegevensverwerking)en. Een [gegevensverwerking](#gegevensverwerking) wordt gekenmerkt door een unieke [code](#gegevensverwerking-code).

Bij de DPIA leggen we de manier waarop de gegevensverwerkingen verlopen schematisch vast in (mogelijk meerdere) [stroomschema gegevensverwerkingen](#stroomschema-gegevensverwerkingen).

Over een [gegevensverwerking](#gegevensverwerking) leggen we het volgende vast in de DPIA:

* Een [gegevensverwerking naam](#gegevensverwerking-naam)
* Een [gegevensverwerking beschrijving](#gegevensverwerking-beschrijving)
* De [gegevenssetspecificatie](#gegevenssetspecificatie) van alle [gegevenstype](#gegevenstype)n die worden verwerkt.

Indien een Persoonsgegeven wordt verwerkt in de gegevensverwerking, is dat (ook) een [gegevensverwerking persoonsgegevens](#gegevensverwerking-persoonsgegevens). De gegevensverwerkingen persoonsgegevens waar een DPIA betrekking op heeft, worden vastgelegd bij de DPIA.

Een [organisatorische activiteit](#organisatorische-activiteit) met een gegevensverwerking persoonsgegevens is een [organisatorische activiteit persoonsgegevens](#organisatorische-activiteit-persoonsgegevens). Elke [organisatorische activiteit persoonsgegevens](#organisatorische-activiteit-persoonsgegevens) hoort bij (maximaal) één [DPIA](#dpia).

### 04. Technieken en methoden van gegevensverwerking {#IntroTechniekenEnMethoden}

Paragraaf 4 van het rijksmodel voor de [DPIA](#dpia) bevat een beschrijving van de verschillende [technieken en methoden van gegevensverwerking](#technieken-en-methoden-van-gegevensverwerking) die worden ingezet bij  de gegevensverwerkingen in de [DPIA](#dpia). Deze worden beschreven in een toelichting.


Sommige technieken en methoden vereisen dat er extra gegevens worden vastgelegd. Dat gebeurt in de volgende gevallen:

* Indien er sprake is van de inzet van een [algoritme](#algoritme), dan is de DPIA een [DPIA met algoritme](#dpia-met-algoritme). Daarbij wordt een [algoritme toelichting](#algoritme-toelichting) vastgelegd, evenals een aanduiding of er sprake is van inzet van een [AI-systeem](#ai-systeem).
* Indien er sprake is van een [Big data-verwerking](#big-data-verwerking), dan is de DPIA dus een [DPIA met big data-verwerking](#dpia-met-big-data-verwerking) en wordt er een [Big data-verwerking toelichting](#big-data-verwerking-toelichting) vastgelegd.
* Indien er sprake is van een [Cloudoplossing](#cloudoplossing), dan is de DPIA dus een [DPIA met cloudoplossing](#dpia-met-cloudoplossing) en wordt er een [Cloudoplossing toelichting](#cloudoplossing toelichting) vastgelegd.
* Indien er sprake is van [geautomatiseerde besluitvorming](#geautomatiseerde besluitvorming), dan is de DPIA dus een [DPIA met geautomatiseerde besluitvorming](#dpia-met-geautomatiseerde-besluitvorming) en wordt er een [geautomatiseerde besluitvorming toelichting](#geautomatiseerde-besluitvorming-toelichting) vastgelegd.
* Indien er sprake is van [profilering](#profilering), dan is de DPIA dus een [DPIA met profilering](#dpia-met-profilering) en wordt er een [Profilering toelichting](#profilering-toelichting) vastgelegd.

Er kan sprake zijn van de gelijktijdige inzet van meerdere technieken en methoden.

### 05. Verwerkingsdoeleinden {#IntroVerwerkingsdoeleinden}

Paragraaf 5 van het rijksmodel voor de [DPIA](#dpia) bevat een beschrijving van het [verwerkingsdoeleinde gegevensverwerking](#verwerkingsdoeleinde-gegevensverwerking) voor elke [gegevensverwerking](#gegevensverwerking) in de DPIA.

### 06. Betrokken partijen {#IntroBetrokkenPartijen}

Paragraaf 6 van het rijksmodel voor de [DPIA](#dpia) bevat voor de gegevensverwerkingen waar de DPIA betrekking op heeft, een overzicht van de [betrokken partij bij gegevensverwerking](#betrokken-partij-bij-gegevensverwerking) voor elke [gegevensverwerking personengegevens] in de DPIA. 

Een [partij](#partij) kan voorkomen in meerdere rollen, soms tegelijkertijd en soms exclusief. Voor elke partij wordt de [partij naam](#partij-naam) vastgelegd.

De primaire rollen vanuit de AVG zijn de volgende:

* [Verwerkingsverantwoordelijke](#verwerkingsverantwoordelijke)
* [gezamenlijke verwerkingsverantwoordelijke](#gezamenlijke-verwerkingsverantwoordelijke)
* [Verwerker](#verwerker) of [Sub-verwerker](#sub-verwerker)
* [Derde](#derde)

Daarnaast kan een partij een rol spelen in het proces van ontvangen en leveren van gegevens:

* [Verstrekker](#verstrekker)
* [Ontvanger](#ontvanger).

Hierbij gelden de volgende regels:

* Een [verwerker](#verwerker) kan niet tegelijkertijd [sub-verwerker](#sub-verwerker) zijn, daarom is bij die rol een keuze te maken voor één van die rollen.
* Een [gezamenlijke verwerkingsverantwoordelijke](#gezamenlijke-verwerkingsverantwoordelijke) kan alleen een partij zijn die al
* Alleen een [verwerkingsverantwoordelijke](#verwerkingsverantwoordelijke) kan een [verstrekker](#verstrekker) zijn.
* Iedereen kan ook [ontvanger](#ontvanger) zijn.

Bij een [betrokken partij bij gegevensverwerking](#betrokken-partij-bij-gegevensverwerking) wordt vastgelegd of de [Functie/afdeling met toegang tot persoonsgegevens bekend](#functie-afdeling-met-toegang-tot-persoonsgegevens-bekend) is.

De in de gegevensverwerkingen verwerkte persoonsgegevens worden ook beschreven, samen met de [partij bij gegevensverwerking met toegang tot persoonsgegeven](#partij-bij-gegevensverwerking-met-toegang-tot-persoonsgegeven). 

Indien de [Functie/afdeling met toegang tot persoonsgegevens bekend](#functie-afdeling-met-toegang-tot-persoonsgegevens-bekend) is, dan is de partij bij de gegevensverwerking een [partij bij gegevensverwerking met functie/afdeling met toegang tot persoonsgegevens bekend](#partij-bij-gegevensverwerking-met-functie-afdeling-met-toegang-tot-persoonsgegevens-bekend) en wordt de betrokken [functie/afdeling met toegang tot persoonsgegevens in gegevensverwerking](#functie-afdeling-met-toegang-tot-persoonsgegevens-in-gegevensverwerking) beschreven.

### 07. Belangen {#IntroBelangen}

Paragraaf 7 van het rijksmodel voor de [DPIA](#dpia) bevat een beschrijving van de [belangen](#belang-van-betrokken-partij) van elke in paragraaf 6 beschreven [betrokken partij bij gegevensverwerking](#betrokken-partij-bij-gegevensverwerking).

Elke [betrokken partij bij gegevensverwerking](#betrokken-partij-bij-gegevensverwerking) is een [betrokken partij bij DPIA](#betrokken-partij-bij-dpia). Voor elke genoemde [partij](#partij) wordt het [belang van betrokken partij](#belang-van-betrokken-partij) beschreven, zodat een [belangenafweging](#belangenafweging) kan worden gemaakt.

Er vindt ook een [consultatie van betrokkenen](#consultatie-van-betrokkenen) plaats, en eventueel worden hun vertegenwoordigers gevraagd naar hun mening over de gegevensverwerking. Bij de [DPIA](#dpia) legggen we dus ook een [toelichting consultatie betrokkenen DPIA](#toelichting-consultatie-betrokkenen-dpia) vast.

### 08. Verwerkingslocaties {#IntroVerwerkingslocaties}

Paragraaf 8 van het rijksmodel voor de [DPIA](#dpia) bevat informatie over de [verwerkingslocatie van gegevensverwerking](#verwerkingslocatie-van-gegevensverwerking) voor elke [gegevensverwerking persoonsgegevens](#gegevensverwerking-persoonsgegevens) waar de DPIA betrekking op heeft.

Hierbij wordt voor elke gegevensverwerking het [Land](#land) benoemd waar de verwerking plaatsvindt. Indien dit een [derde land](#derde-land) betreft, is er sprake van een [verwerkingslocatie buiten de EER](#verwerkingslocatie-buiten-de-eer) en dus van [internationale doorgifte](#internationale-doorgifte). In dat geval moet het [doorgiftemechanisme](#doorgiftemechanisme) worden beschreven.

Als er sprake is van een [verwerkingslocatie buiten de EER](#verwerkingslocatie-buiten-de-eer) dan is er ook sprake van een [risico op basis van doorgifte](#risico-op-basis-van-doorgifte) als een [inherent risico voor betrokkenen](#inherent-risico-voor-betrokkenen). Eventuele genomen [maatregelen tegen risico op basis van doorgifte](#maatregel-tegen-risico-op-basis-van-doorgifte) worden daarbij vastgelegd.

### 09. Juridisch/Beleidsmatig kader {#IntroJuridischBeleidsmatigKader}

Paragraaf 9 van het rijksmodel voor de [DPIA](#dpia) bevat per [gegevensverwerking persoonsgegevens](#gegevensverwerking-persoonsgegevens) in de DPIA een beschrijving van het [juridisch kader](#juridisch-kader) en [beleidsmatig kader](#beleidsmatig-kader) wat van invloed is op de gegevensverwerkingen in de DPIA.

Het juridisch kader verwijst daarbij naar alle relevante [wet- en regelgeving](#wet-en-regelgeving), (waarbij de AVG en de Richtlijn niet hoeven te worden benoemd). Het beleidsmatig kader is een opsomming van al het [beleid](#beleid) wat van toepassing is op de gegevensverwerkingen in de DPIA.

### 10. Bewaartermijnen {#IntroBewaartermijnen}

Paragraaf 10 van het rijksmodel voor de [DPIA](#dpia) bevat per [gegevensverwerking persoonsgegevens](#gegevensverwerking-persoonsgegevens) in de DPIA een beschrijving van de [persoonsgegevens](#persoonsgegeven) in de verwerking, evenals hun [bewaartermijn](#bewaartermijn). Voor elk persoonsgegeven met een bewaartermijn wordt beschreven wat de [motivatie van de bewaartermijn](#motivatie-bewaartermijn) is, en wie daarop de [toezichthouder op de bewaartermijn](#toezichthouder-bewaartermijn) is, en specifiek welke [afdeling](#afdeling) binnen een [partij](#partij) die verantwoordelijkheid heeft.

### 11. Rechtsgronden {#IntroRechtsgronden}

Paragraaf 11 van het rijksmodel voor de [DPIA](#dpia) bevat per [gegevensverwerking persoonsgegevens](#gegevensverwerking-persoonsgegevens) in de DPIA een beschrijving van elke [rechtsgrond](#rechtsgrond) die van toepassing is op de gegevensverwerking. Hierbij kan de gegevensverwerking één van de volgende rechtsgronden hebben:

* [Rechtsgrond toestemming](#rechtsgrond-toestemming), toegelicht in de [rechtsgrond toestemming toelichting](#rechtsgrond-toestemming-toelichting). Daarbij moet verder worden toegelicht dat de [toestemming ondubbelzinnig](#toestemming-ondubbelzinnig) is, dat de [toestemming specifiek en geïnformeerd](#toestemming-specifiek-en-geïnformeerd) is gegeven, en dat de [toestemming vrij gegeven](#toestemming-vrij-gegeven) is.
* [rechtsgrond noodzakelijk voor de uitvoering van een overeenkomst](#rechtsgrond-noodzakelijk-voor-de-uitvoering-van-een-overeenkomst). In dat geval moet de naam van de [overeenkomst als basis voor rechtsgrond](#overeenkomst-als-basis-voor-rechtsgrond) worden vermeld.
* [rechtsgrond vitaal belang](#rechtsgrond-vitaal-belang). Hierbij dient een [rechtsgrond vitaal belang toelichting](#rechtsgrond-vitaal-belang-toelichting) te worden gegeven.
* [rechtsgrond gerechtvaardigd belang](#rechtsgrond-gerechtvaardigd-belang). Hierbij dient de [partij](#partij) die betrokken is als [verwerkingsverantwoordelijke of derde met gerechtvaardigd belang](#verwerkingsverantwoordelijke-of-derde-met-gerechtvaardigd-belang), te worden genoemd, samen met de rol die deze partij speelt. Hierbij geldt natuurlijk wel dat het gerechtvaardigd belang bij een gegevensverwerking van een verwerkingsverantwoordelijke of derde bij diezelfde gegevensverwerking moet zijn.
* [rechtsgrond wettelijke verplichting](#rechtsgrond-wettelijke-verplichting) en [rechtsgrond taak van algemeen belang](#rechtsgrond-taak-van-algemeen-belang) worden samengevoegd. In het geval van een rechtsgrond die is gebaseerd op een wettelijke verplichting of taak van algemeen belang, dient de [wet- en regelgeving](#wet-en-regelgeving) die daaraan ten grondslag ligt, te worden beschreven.

### 12. Bijzondere persoonsgegevens {#IntroBijzonderePersoonsgegevens}

Paragraaf 12 van het rijksmodel voor de [DPIA](#dpia) is van toepassing indien er [bijzondere persoonsgegevens](#bijzonder-persoonsgegeven), [strafrechtelijke persoonsgegevens](#strafrechtelijk-persoonsgegeven) of [nationale identificatienummers](#nationaal-identificatienummer) worden verwerkt. De verwerking daarvan is in principe verboden, dus in dat geval moet worden gemotiveerd op welke grond de verwerking alsnog mag plaatsvinden.

Hierbij wordt elk [persoonsgegeven](#persoonsgegeven) beschreven, met de [naam persoonsgegeven](#naam-persoonsgegeven) en de [categorie betrokkenen](#categorie-betrokkenen) van wie de gegevens worden verwerkt.

Voor [bijzondere persoonsgegevens](#bijzonder-persoonsgegeven) wordt beschreven welk [categorie bijzondere persoonsgegevens](#categorie-bijzondere-persoonsgegevens) er worden verwerkt. Voor elke [categorie bijzondere persoonsgegevens](#categorie-bijzondere-persoonsgegevens) wordt een [doorbrekingsgrond](#doorbrekingsgrond) vastgelegd, en de [wet- en regelgeving](#wet-en-regelgeving) die de doorbrekingsgrond beschrijft.

Voor een gegevensverwerking van [strafrechtelijke persoonsgegevens](#strafrechtelijk-persoonsgegeven) wordt vastgelegd welke [uitzonderingsgrond](#uitzonderingsgrond) wordt gehanteerd, en op basis van welke [wet- en regelgeving](#wet-en-regelgeving) dat gebeurd.

Voor een gegevensverwerking van [nationale identificatienummers](#nationaal-identificatienummer) wordt eveneens vastgelegd welke [uitzonderingsgrond](#uitzonderingsgrond) wordt gehanteerd, en op basis van welke [wet- en regelgeving](#wet-en-regelgeving) dat gebeurd.

### 13. Doelbinding {#IntroDoelbinding}

Paragraaf 13 van het rijksmodel voor de [DPIA](#dpia) is van toepassing indien het [verwerkingsdoeleinde](#verwerkingsdoeleinde) van een [gegevensverwerking persoonsgegevens](#gegevensverwerking-persoonsgegevens) in de DPIA verschilt van het [oorspronkelijk verwerkingsdoeleinde] van een [persoonsgegeven](#persoonsgegeven) in die verwerking.

In dat geval beschrijven we voor elk [persoonsgegeven in gegevensverwerking met nieuw en oorspronkelijk verwerkingsdoeleinde](#persoonsgegeven-in-gegevensverwerking-met-nieuw-en-oorspronkelijk-verwerkingsdoeleinde) minimaal één van de volgende zaken:

* [Conclusie toelaatbaarheid hergebruik](#conclusie-toelaatbaarheid-hergebruik), met een bijbehorende [toelichting](#toelichting-op-conclusie-toelaatbaarheid-hergebruik).
* [Conclusie verenigbaarheidstoets](#conclusie-verenigbaarheidstoets), met een bijbehorende [toelichting](#toelichting-op-conclusie-verenigbaarheidstoets).

Als het persoonsgegeven in de verwerking een persoonsgegeven is waarvoor geldt dat [hergebruik toelaatbaar o.b.v. Unie- of lidstaatrechtelijk recht](#hergebruik-toelaatbaar-o-b-v-unie-of-lidstaatrechtelijk-recht) is, dan leggen we de bijbehorende [wet- en regelgeving](#wet-en-regelgeving) vast die daarvoor als basis dient. De [conclusie toelaatbaarheid hergebruik](#conclusie-toelaatbaarheid-hergebruik) wordt dan "toelaatbaar o.b.v. Unie- of lidstaatrechtelijk recht".

### 14. Noodzaak en evenredigheid {#IntroNoodzaakEnEvenredigheid}

Paragraaf 14 van het rijksmodel voor de [DPIA](#dpia) bevat een [proportionaliteitsbeoordeling](#proportionaliteitsbeoordeling) van de [proportionaliteit](#proportionaliteit), waarmee de evenredigheid van het totaal aan verwerkingen in de DPIA wordt beoordeeld.

Verder wordt er een [subsidiariteitsbeoordeling](#subsidiariteitsbeoordeling) van de [subsidiariteit](#subsidiariteit) vastgelegd, waarmee de noodzaak van het totaal aan verwerkingen in de DPIA wordt beoordeeld.

### 15. Rechten van de betrokkene {#IntroRechtenVanDeBetrokkene}

Paragraaf 15 van het rijksmodel voor de [DPIA](#dpia) beschrijft voor elk [recht van de betrokkene](#recht-van-de-betrokkene) de [procedure ter invulling van het recht van de betrokkene](#procedure-ter-invulling-van-het-recht-van-de-betrokkene) waarmee dat recht van de betrokkene wordt geborgd.

Indien er een [beperking op recht van de betrokkene](#beperking-op-recht-van-de-betrokkene) op het [recht van de betrokkene](#recht-van-de-betrokkene) wordt geplaatst, wordt ook de [rechtsgrond voor beperking op recht van de betrokkene](#rechtsgrond-voor-beperking-op-recht-van-de-betrokkene) vastgelegd. Deze rechtsgrond is een [wetsartikel over beperking op recht van de betrokkene](#wetsartikel-over-beperking-op-recht-van-de-betrokkene). Dit is specifieke [wet- en regelgeving over beperking op recht van de betrokkene](#wet-en-regelgeving-over-beperking-op-recht-van-de-betrokkene).

### 16. Risico's voor betrokkenen {#IntroRisicosVoorBetrokkenen}

Paragraaf 16 van het rijksmodel voor de [DPIA](#dpia) beschrijft elk mogelijk [inherent risico voor betrokkenen](#inherent-risico-voor-betrokkenen) voor de rechten en vrijheden van de betrokkenen, zoals het recht op privacy en het verbod op discriminatie, van de gegevensverwerkingen waar de DPIA betrekking op heeft. 

Voor elk [inherent risico voor betrokkenen](#inherent-risico-voor-betrokkenen) wordt de [oorsprong risico voor betrokkenen](#oorsprong-risico-voor-betrokkenen) vastgelegd.

Elk [inherent risico voor betrokkenen](#inherent-risico-voor-betrokkenen) is een [risico voor betrokkenen](#risico-voor-betrokkenen). Voor elk [risico voor betrokkenen](#risico-voor-betrokkenen), zowel inherent als resterend, wordt vastgelegd wat de [kans op optreden risico voor betrokkenen](#kans-op-optreden-risico-voor-betrokkenen) is, wat de [impact van optreden risico voor betrokkenen](#impact-van-optreden-risico-voor-betrokkenen) is, en wat het bijbehorende [risiconiveau](#risiconiveau) is. Bij kans, impact en risiconiveau wordt ook telkens een motivatie vastgelegd waarom die inschatting op dat niveau is gemaakt.

Verder wordt de vraag gesteld of er [mogelijk sprake van discriminatie](#mogelijk-sprake-van-discriminatie) is. Als dat zo is, dan is er sprake van een  [risico op discriminatie](#risico-op-discriminatie) en is de DPIA een [DPIA met mogelijk sprake van discriminatie](#DPIA-met-mogelijk-sprake-van-discriminatie) en dient er een [anti-discriminatietoets](#anti-discriminatietoets) te worden uitgevoerd, waarvan de uitslag wordt vastgelegd.

Als er sprake is van een [verwerkingslocatie buiten de EER](#verwerkingslocatie-buiten-de-eer) zoals eerder besproken in paragraaf 8 - [Verwerkingslocaties](#IntroVerwerkingslocaties), dan is er ook sprake van een [risico op basis van doorgifte](#risico-op-basis-van-doorgifte). 

### 17. Maatregelen {#IntroMaatregelen}

Paragraaf 17 van het rijksmodel voor de [DPIA](#dpia) bevat de in de vorige paragraaf vastgelegde inherente risico's, maar nu uitgebreid met de informatie over de genomen [maatregel](#maatregel)en.

Voor een [DPIA](#dpia) beschrijven we hier o.a.:

* de [locatie monitoring en evaluatie maatregelen](#locatie-monitoring-en-evaluatie-maatregelen). 
* de eerder geïdentificeerde [inherente risico's voor betrokkenen](#inherent-risico-voor-betrokkenen) 

Bij een [inherent risico voor betrokkenen](#inherent-risico-voor-betrokkenen) leggen we de volgende zaken vast:

* het [effect van de maatregelen op het risico](#effect-maatregelen)
* minimaal één [maatregel](#maatregel)
* een [functie in organisatorische eenheid van partij](#functie-in-organisatorische-eenheid-van-partij) die optreedt als [beheerder van maatregelen](#beheerder-van-maatregelen) 
* een [resterend risico voor betrokkenen](#resterend-risico-voor-betrokkenen)

Als het [inherent risico voor betrokkenen](#inherent-risico-voor-betrokkenen) een [risico op basis van doorgifte](#risico-op-basis-van-doorgifte) is, leggen we minimaal één [maatregel doorgifte](#maatregel-doorgifte) vast.

Voor alle resterende [risico's voor betrokken](#risico-voor-betrokkenen) leggen we, net als voor de inherente risico's, het volgende vast:

* een [risicobeschrijving](#risicobeschrijving)
* [kans op optreden risico voor betrokkenen](#kans-op-optreden-risico-voor-betrokkenen) en bijbehorende [motivatie](#motivatie-kans-risico-voor-betrokkenen)
* [impact van optreden risico voor betrokkenen](#impact-van-optreden-risico-voor-betrokkenen) en bijbehorende [motivatie](#motivatie-impact-risico-voor-betrokkenen)
* [risiconiveau van optreden risico voor betrokkenen](#risiconiveau-van-optreden-risico-voor-betrokkenen) en bijbehorende [motivatie](#motivatie-risiconiveau-risico-voor-betrokkenen)

Iedere [DPIA](#dpia) met een [inherent risico voor betrokkenen](#inherent-risico-voor-betrokkenen) is een [DPIA met resterende risico's](#dpia-met-resterende-risico-s). Hiervoor is een [onderbouwing acceptatie resterende risico's](#onderbouwing-acceptatie-resterende-risico-s) verplicht.

Een [DPIA met resterend hoog risico](#dpia-met-resterend-hoog-risico) bevat verder:

* een beschrijving van het [advies AP](#advies-ap), indien er een (verplichte) [voorafgaande raadpleging AP](#voorafgaande-raadpleging-ap) is geweest.

## Pre-scan DPIA {#IntroPre-scanDPIA}

Een [Pre-scan DPIA](#pre-scan-dpia-0) is een vastlegging van de impact die een bepaalde [gegevensverwerking](#gegevensverwerking) heeft of kan hebben op de privacy van burgers.

In deze specificatie wordt beschreven uit welke gegevens een pre-scan DPIA is opgebouwd, en hoe deze zich onderling verhouden, op het conceptuele en semantische niveau. De beschrijving zal gebeuren aan de hand van de indeling van de pre-scan DPIA, conform de indeling in de [[HandreikingPre-scanDPIA]]. Hierbij zijn paragraaf I en J buiten beschouwing gelaten, aangezien deze paragrafen niet relevant zijn voor de vraag of er een DPIA of IAMA moet worden uitgevoerd. Ook uit de overige paragrafen zijn zaken weggelaten die niet relevant zijn voor de vraag of er een instrument als de DPIA moet worden ingezet.

### Pre-scan DPIA - A. Inleiding/algemeen {#IntroPre-scanDPIA_A_Inleiding_algemeen}

De vastlegging van de pre-scan DPIA wordt gekenmerkt door de [pre-scan DPIA code](#pre-scan-dpia-code).

In de inleiding wordt de [organisatorische activiteit](#organisatorische-activiteit) beschreven waarvoor de pre-scan DPIA wordt uitgevoerd, in een [organisatorische activiteit beschrijving](#organisatorische-activiteit-beschrijving). Deze omvat een beschrijving van de verwerking of het geheel van verwerkingen, waarin wordt aangegeven om welke processen, systemen en applicaties het gaat, wat de context van de verwerking is (door wie, waar, waarom en hoe), en hoeveel gegevens over wie wordt vastgelegd met welk doel.

Vervolgens wordt vastgesteld of de [organisatorische activiteit](#organisatorische-activiteit) persoonsgegevens verwerkt, wat kan worden vastgelegd in een [classificatie persoonsgegevens](#classificatie-persoonsgegevens). Indien er geen persoonsgegevens worden verwerkt, hoeven er verder geen vragen te worden beantwoord.

Als na invullen van de pre-scan DPIA blijkt dat er een DPIA nodig is, dan is de [organisatorische activiteit](#organisatorische-activiteit) een [organisatorische activiteit met DPIA-verplichting](#organisatorische-activiteit-met-dpia-verplichting).

### Pre-scan DPIA - B. Gegevensverwerkingen {#IntroPre-scanDPIA_B_Gegevensverwerkingen}

Indien een [organisatorische activiteit persoonsgegevens](#organisatorische-activiteit-persoonsgegevens) niet meteen een DPIA-verplichting krijgt door een gegevensverwerking op de [lijst AP](#lijst-ap) of [lijst EPDB](#lijst-epdb), dan spreken we van een [organisatorische activiteit zonder DPIA-verplichting o.b.v. lijst AP of EDPB](#organisatorische-activiteit-zonder-dpia-verplichting-o-b-v-lijst-ap-of-edpb).

Daarbij leggen we een aantal gegevens vast die uitsluitsel kunnen geven over de vraag of er alsnog een DPIA-verplichting ontstaat.

Indien er een  [classificatie persoonsgegevens aanwezig](#classificatie-persoonsgegevens-aanwezig) is met waarde [bevat persoonsgegevens](#classificatie-persoonsgegevens-bevat-persoonsgegevens), dan wordt vastgelegd in de [classificatie type persoonsgegevens](#classificatie-type-persoonsgegevens) of er sprake is van:

* [gewoon persoonsgegeven](#gewoon-persoonsgegeven)
* [gevoelig persoonsgegeven](#gevoelig-persoonsgegeven)
* [bijzonder persoonsgegeven](#bijzonder-persoonsgegeven)
* [strafrechtelijk persoonsgegeven](#strafrechtelijk-persoonsgegeven)
* [nationaal identificatienummer](#nationaal-identificatienummer)

Voor de pre-scan DPIA beschouwen we strafrechtelijke persoonsgegevens en nationale identificatienummers als gevoelige gegevens.

Bij een verwerking van persoonsgegevens is er sprake van een [organisatorische activiteit persoonsgegevens](#organisatorische-activiteit-persoonsgegevens). 

Er is sprake van een [organisatorische activiteit gewone persoonsgegevens](#organisatorische-activiteit-gewone-persoonsgegevens) als de organisatorische activiteit een [classificatie type persoonsgegevens](#classificatie-type-persoonsgegevens) heeft, met als waarde "bevat gewone persoonsgegevens". In dat geval wordt bij die organisatorische activiteit de [categorie gewone persoonsgegevens](#categorie-gewone-persoonsgegevens) vastgelegd. Het gaat om de volgende categorieën:

* [Categorie gewone persoonsgegevens: Apparaat- en internetgegevens](#categorie-gewone-persoonsgegevens-apparaat-en-internetgegevens)
* [Categorie gewone persoonsgegevens: Content](#categorie-gewone-persoonsgegevens-content)
* [Categorie gewone persoonsgegevens: Demografische gegevens](#categorie-gewone-persoonsgegevens-demografische-gegevens)
* [Categorie gewone persoonsgegevens: Diagnostische gegevens of telemetrie](#categorie-gewone-persoonsgegevens-diagnostische-gegevens-of-telemetrie)
* [Categorie gewone persoonsgegevens: Gegevens verzameld via een website](#categorie-gewone-persoonsgegevens-gegevens-verzameld-via-een-website)
* [Categorie gewone persoonsgegevens: Helpdeskgegevens](#categorie-gewone-persoonsgegevens-helpdeskgegevens)
* [Categorie gewone persoonsgegevens: Logging](#categorie-gewone-persoonsgegevens-logging)
* [Categorie gewone persoonsgegevens: Naam, contactgegevens](#categorie-gewone-persoonsgegevens-naam-contactgegevens)
* [Categorie gewone persoonsgegevens: Overige](#categorie-gewone-persoonsgegevens-overige)

Als er een [categorie gewone persoonsgegevens: Overige](#categorie-gewone-persoonsgegevens-overige) aanwezig is, dan is de organisatorische activiteit een [organisatorische activiteit overige gewone persoonsgegevens](#organisatorische-activiteit-overige-gewone-persoonsgegevens) en leggen we de desbetreffende beschrijving van die [categorie persoonsgegevens](#categorie-persoonsgegevens) vast.

Er is sprake van een [organisatorische activiteit gevoelige persoonsgegevens](#organisatorische-activiteit-gevoelige-persoonsgegevens) als de organisatorische activiteit een [classificatie type persoonsgegevens](#classificatie-type-persoonsgegevens) heeft, met als waarde [Classificatie type persoonsgegevens: Gevoelig](#classificatie-type-persoonsgegevens-gevoelig). In dat geval wordt bij die organisatorische activiteit de [categorie gevoelige persoonsgegevens](#categorie-gevoelige-persoonsgegevens) vastgelegd. Het gaat om de volgende categorieën:

* [Categorie gevoelige persoonsgegevens: Andere gegevens die kunnen leiden tot stigmatisering of uitsluiting van de betrokkene](#categorie-gevoelige-persoonsgegevens-andere-gegevens-die-kunnen-leiden-tot-stigmatisering-of-uitsluiting-van-de-betrokkene)
* [Categorie gevoelige persoonsgegevens: Communicatie- en locatiegegevens](#categorie-gevoelige-persoonsgegevens-communicatie-en-locatiegegevens)
* [Categorie gevoelige persoonsgegevens: Gebruikersnamen, wachtwoorden en andere inloggegevens](#categorie-gevoelige-persoonsgegevens-gebruikersnamen-wachtwoorden-en-andere-inloggegevens)
* [Categorie gevoelige persoonsgegevens: Gegevens die betrekking hebben op kwetsbare groepen](#categorie-gevoelige-persoonsgegevens-gegevens-die-betrekking-hebben-op-kwetsbare-groepen)
* [Categorie gevoelige persoonsgegevens: Gegevens die kunnen worden gebruikt voor fraude](#categorie-gevoelige-persoonsgegevens-gegevens-die-kunnen-worden-gebruikt-voor-fraude)
* [Categorie gevoelige persoonsgegevens: Gegevens over de financiële situatie van de betrokkene](#categorie-gevoelige-persoonsgegevens-gegevens-over-de-financiele-situatie-van-de-betrokkene)
* [Categorie gevoelige persoonsgegevens: Nationale identificatienummers](#categorie-gevoelige-persoonsgegevens-nationale-identificatienummers)
* [Categorie gevoelige persoonsgegevens: Strafrechtelijke gegevens](#categorie-gevoelige-persoonsgegevens-strafrechtelijke-gegevens)
* [Categorie gevoelige persoonsgegevens: Surfgedrag](#categorie-gevoelige-persoonsgegevens-surfgedrag)

Er is sprake van een [organisatorische activiteit bijzondere persoonsgegevens](#organisatorische-activiteit-bijzondere-persoonsgegevens) als de organisatorische activiteit een [classificatie type persoonsgegevens](#classificatie-type-persoonsgegevens) heeft, met als waarde [Classificatie type persoonsgegevens: Bijzonder](#classificatie-type-persoonsgegevens-bijzonder). In dat geval wordt vastgelegd om welk [classificatie type bijzondere persoonsgegevens](#type-bijzondere-persoonsgegevens) het gaat. Het gaat daarbij om de volgende categorieën:

* [Type bijzondere persoonsgegevens: Biometrische gegevens met het oog op de unieke identificatie van een persoon](#type-bijzondere-persoonsgegevens-biometrische-gegevens-met-het-oog-op-de-unieke-identificatie-van-een-persoon)
* [Type bijzondere persoonsgegevens: Gegevens met betrekking tot iemands seksueel gedrag of seksuele gerichtheid](#type-bijzondere-persoonsgegevens-gegevens-met-betrekking-tot-iemands-seksueel-gedrag-of-seksuele-gerichtheid)
* [Type bijzondere persoonsgegevens: Gegevens over gezondheid](#type-bijzondere-persoonsgegevens-gegevens-over-gezondheid)
* [Type bijzondere persoonsgegevens: Genetische gegevens](#type-bijzondere-persoonsgegevens-genetische-gegevens)
* [Type bijzondere persoonsgegevens: Persoonsgegevens waaruit het lidmaatschap van een vakbond blijkt](#type-bijzondere-persoonsgegevens-persoonsgegevens-waaruit-het-lidmaatschap-van-een-vakbond-blijkt)
* [Type bijzondere persoonsgegevens: Persoonsgegevens waaruit politieke opvattingen blijken](#type-bijzondere-persoonsgegevens-persoonsgegevens-waaruit-politieke-opvattingen-blijken)
* [Type bijzondere persoonsgegevens: Persoonsgegevens waaruit ras of etnische afkomst blijkt](#type-bijzondere-persoonsgegevens-persoonsgegevens-waaruit-ras-of-etnische-afkomst-blijkt)
* [Type bijzondere persoonsgegevens: Persoonsgegevens waaruit religieuze of levensbeschouwelijke overtuigingen blijken](#type-bijzondere-persoonsgegevens-persoonsgegevens-waaruit-religieuze-of-levensbeschouwelijke-overtuigingen-blijken)

Er wordt ook vastgelegd welke [categorie betrokkenen](#categorie-betrokkenen) onderwerp zijn van de gegevens die worden verwerkt, evenals het [aantal betrokkenen in die categorie](#-antal-betrokkenen-van-categorie).

Het gaat om de volgende [categorie betrokkenen in organisatorische activiteit](#categorie-betrokkenen-in-organisatorische-activiteit):

* [Categorie betrokkenen: Andere kwetsbare groepen](#categorie-betrokkenen-andere-kwetsbare-groepen)
* [Categorie betrokkenen: Burgers](#categorie-betrokkenen-burgers)
* [Categorie betrokkenen: Kinderen jonger dan 16 jaar](#categorie-betrokkenen-kinderen-jonger-dan-16-jaar)
* [Categorie betrokkenen: Medewerkers/bewindspersonen](#categorie-betrokkenen-medewerkers-bewindspersonen)

Als het om een categorie betrokkenen gaat die niet in de bovenstaande lijst staat, moet deze worden gespecificeerd. In dat geval wordt gekozen voor:

* [Categorie betrokkenen: Specificatie categorie betrokkenen](#categorie-betrokkenen-specificatie-categorie-betrokkenen)

Als die categorie wordt gekozen, is de organisatorische activiteit een [organisatorische activiteit met specificatie categorie betrokkenen](#organisatorische-activiteit-met-specificatie-categorie-betrokkenen) en moet er een [specificatie categorie betrokkenen](#specificatie-categorie-betrokkenen) worden vastgelegd waarin de groep wordt benoemd.

Verder wordt vastgelegd wat de verwachte [frequentie van verwerking](#frequentie-van-verwerking) zal zijn. Hierbij kan worden gekozen uit de volgende frequenties:

* [Frequentie van verwerking: Continu](#frequentie-van-verwerking-continu)
* [Frequentie van verwerking: Eenmalig](#frequentie-van-verwerking-eenmalig)
* [Frequentie van verwerking: Minstens jaarlijks](#frequentie-van-verwerking-minstens-jaarlijks)
* [Frequentie van verwerking: Minstens maandelijks](#frequentie-van-verwerking-minstens-maandelijks)
* [Frequentie van verwerking: Onregelmatig](#frequentie-van-verwerking-onregelmatig)
* [Frequentie van verwerking: Vaker dan maandelijks](#frequentie-van-verwerking-vaker-dan-maandelijks)

Daarnaast wordt de [bewaartermijn](#bewaartermijn) van de gegevens beschreven. Hierbij kan worden gekozen uit:

* [Bewaartermijn: Aantal jaren](#bewaartermijn-aantal-jaren)
* [Bewaartermijn: Jaar](#bewaartermijn-jaar)
* [Bewaartermijn: Minder dan 1 maand](#bewaartermijn-minder-dan-1-maand)
* [Bewaartermijn: Minder dan 1 week](#bewaartermijn-minder-dan-1-week)
* [Bewaartermijn: Minder dan 24 uur](#bewaartermijn-minder-dan-24-uur)

### Pre-scan DPIA - C. Internationale doorgiften {#IntroPre-scanDPIA_C_Internationale_doorgiften}

Bij de [organisatorische activiteit persoonsgegevens](#organisatorische-activiteit-persoonsgegevens) wordt vastgelegd of er sprake is van een [internationale doorgifte](#internationale-doorgifte). Als er sprake is van zo'n internationale doorgifte, dan is er sprake van een [organisatorische activiteit met internationale doorgifte](#organisatorische-activiteit-met-internationale-doorgifte).

Bij zo'n activiteit leggen we vervolgens vast waar de [opslag van gegevens](#opslag-van-gegevens) plaatsvindt:

* [Opslag van gegevens: on premise](#opslag-van-gegevens-on-premise)
* [Opslag van gegevens: datacenter EER](#opslag-van-gegevens-datacenter-eer)
* [Opslag van gegevens: buiten EER](#opslag-van-gegevens-buiten-eer)

Indien de [organisatorische activiteit persoonsgegevens](#organisatorische-activiteit-persoonsgegevens) een [organisatorische activiteit bijzondere persoonsgegevens](#organisatorische-activiteit-bijzondere-persoonsgegevens) is, omdat er [bijzondere persoonsgegevens](#bijzonder-persoonsgegeven) in de [internationale doorgifte](#internationale-doorgifte) zitten, dan wordt de activiteit ook een [organisatorische activiteit met internationale doorgifte bijzondere persoonsgegevens](#organisatorische-activiteit-met-internationale-doorgifte-bijzondere-persoonsgegevens).

Voor een [organisatorische activiteit met internationale doorgifte](#organisatorische-activiteit-met-internationale-doorgifte) wordt ook vastgelegd volgens welk [doorgiftemechanisme](#doorgiftemechanisme) wordt gewerkt, conform artikel 45, 46, 48 en 49 van de [[AVG]]. Het gaat om de volgende doorgiftemechanismen:

* [Doorgiftemechanisme: adequaatheidsbesluit](#doorgiftemechanisme-adequaatheidsbesluit)
* [Doorgiftemechanisme: bindend bedrijfsvoorschrift](#doorgiftemechanisme-bindend-bedrijfsvoorschrift)
* [Doorgiftemechanisme: goedgekeurd certificeringsmechanisme](#doorgiftemechanisme-goedgekeurd-certificeringsmechanisme)
* [Doorgiftemechanisme: goedgekeurde gedragscode](#doorgiftemechanisme-goedgekeurde-gedragscode)
* [Doorgiftemechanisme: juridisch bindend en afdwingbaar instrument](#doorgiftemechanisme-juridisch-bindend-en-afdwingbaar-instrument)
* [Doorgiftemechanisme: standaard contractsbepaling](#doorgiftemechanisme-standaard-contractsbepaling)
* [Doorgiftemechanisme: uitzondering artikel 49 AVG](#doorgiftemechanisme-uitzondering-artikel-49-avg)
* [Doorgiftemechanisme: overig mechanisme](#doorgiftemechanisme-overig-mechanisme)

Bij een keuze voor een [doorgiftemechanisme](#doorgiftemechanisme) dat anders is dan een [doorgiftemechanisme: adequaatheidsbesluit](#doorgiftemechanisme-adequaatheidsbesluit) ontstaat er een [organisatorische activiteit met DTIA-verplichting](#organisatorische-activiteit-met-dtia-verplichting). Indien het doorgiftemechanisme een [doorgiftemechanisme: overig mechanisme](#doorgiftemechanisme-overig-mechanisme) is, ontstaat er een [organisatorische activiteit met DTIA-verplichting en overig doorgiftemechanisme](#organisatorische-activiteit-met-dtia-verplichting-en-overig-doorgiftemechanisme). In dat geval moet daarbij een [specificatie doorgiftemechanisme](#specificatie-doorgiftemechanisme) worden vastgelegd.

### Pre-scan DPIA - D. Lijst AP {#IntroPre-scanDPIA_D_Lijst_AP}

Bij de [organisatorische activiteit persoonsgegevens](#organisatorische-activiteit-persoonsgegevens) moet worden aangegeven of er sprake is van [gegevensverwerking](#gegevensverwerking)en conform de [lijst AP](#lijst-ap). De Lijst AP is een lijst met soorten gegevensverwerkingen van de [[AP]] waarvoor een [DPIA](#dpia) verplicht is.

Het gaat om de volgende soorten gegevensverwerkingen:

* [Lijst AP: Biometrische gegevens](#lijst-ap-biometrische-gegevens)
* [Lijst AP: Cameratoezicht](#lijst-ap-cameratoezicht)
* [Lijst AP: Communicatiegegevens](#lijst-ap-communicatiegegevens)
* [Lijst AP: Controle werknemers](#lijst-ap-controle-werknemers)
* [Lijst AP: Creditscores](#lijst-ap-creditscores)
* [Lijst AP: Financiële situatie](#lijst-ap-financiele-situatie)
* [Lijst AP: Flexibel cameratoezicht](#lijst-ap-flexibel-cameratoezicht)
* [Lijst AP: Fraudebestrijding](#lijst-ap-fraudebestrijding)
* [Lijst AP: Genetische persoonsgegevens](#lijst-ap-genetische-persoonsgegevens)
* [Lijst AP: Gezondheidsgegevens](#lijst-ap-gezondheidsgegevens)
* [Lijst AP: Heimelijk onderzoek](#lijst-ap-heimelijk-onderzoek)
* [Lijst AP: Internet of things](#lijst-ap-internet-of-things)
* [Lijst AP: Locatiegegevens](#lijst-ap-locatiegegevens)
* [Lijst AP: Observatie en beïnvloeding van gedrag](#lijst-ap-observatie-en-beinvloeding-van-gedrag)
* [Lijst AP: Profilering](#lijst-ap-profilering)
* [Lijst AP: Samenwerkingsverbanden](#lijst-ap-samenwerkingsverbanden)
* [Lijst AP: Zwarte lijsten](#lijst-ap-zwarte-lijsten)

Deze worden vastgelegd in de [gegevensverwerking lijst AP](#gegevensverwerking-lijst-ap)

Indien er een gegevensverwerking is van het soort zoals hierboven vermeld, ontstaat er een [Organisatorische activiteit met DPIA-verplichting o.b.v. lijst AP of EDPB](#organisatorische-activiteit-met-dpia-verplichting-o-b-v-lijst-ap-of-edpb).

Indien dit niet het geval is, en er ook niet minimaal twee soorten gegevensverwerking uit de [lijst EDPB](#lijst-epdb) worden uitgevoerd, ontstaat er een [Organisatorische activiteit zonder DPIA-verplichting o.b.v. lijst AP of EDPB](#organisatorische-activiteit-zonder-dpia-verplichting-o-b-v-lijst-ap-of-edpb).

### Pre-scan DPIA - E. Lijst EDPB {#IntroPre-scanDPIA_E_Lijst_EDPB}

Bij de [organisatorische activiteit persoonsgegevens](#organisatorische-activiteit-persoonsgegevens) moet worden aangegeven of er sprake is van [gegevensverwerking](#gegevensverwerking)en conform de [lijst EDPB](#lijst-edpb). De Lijst EDPB is een lijst met soorten gegevensverwerkingen van de [[EDPB]] waarvoor mogelijk een [DPIA](#dpia) verplicht is.

Het gaat om de volgende soorten gegevensverwerkingen:

* [Lijst EDPB: Bijzondere persoonsgegevens of zeer gevoelige persoonsgegevens](#lijst-edpb-bijzondere-persoonsgegevens-of-zeer-gevoelige-persoonsgegevens)
* [Lijst EDPB: Blokkering van een dienst, recht of contract](#lijst-edpb-blokkering-van-een-dienst-recht-of-contract)
* [Lijst EDPB: Geautomatiseerde besluitvorming](#lijst-edpb-geautomatiseerde-besluitvorming)
* [Lijst EDPB: Gebruik van nieuwe technologieën](#lijst-edpb-gebruik-van-nieuwe-technologieen)
* [Lijst EDPB: Grootschalige gegevensverwerkingen](#lijst-edpb-grootschalige-gegevensverwerkingen)
* [Lijst EDPB: Koppelen van datasets](#lijst-edpb-koppelen-van-datasets)
* [Lijst EDPB: Mensen beoordelen met persoonskenmerken (evaluatie of scoring)](#lijst-edpb-mensen-beoordelen-met-persoonskenmerken-evaluatie-of-scoring)
* [Lijst EDPB: Stelselmatige en grootschalige monitoring](#lijst-edpb-stelselmatige-en-grootschalige-monitoring)
* [Lijst EDPB: Verwerking van persoonsgegevens over kwetsbare groepen of personen](#lijst-edpb-verwerking-van-persoonsgegevens-over-kwetsbare-groepen-of-personen)

Deze worden vastgelegd in de [criteria lijst EDPB](#criteria-lijst-edpb). 

Indien er minimaal twee gegevensverwerkingen zijn van het soort zoals hierboven vermeld, ontstaat er een [Organisatorische activiteit met DPIA-verplichting o.b.v. lijst AP of EDPB](#organisatorische-activiteit-met-dpia-verplichting-o-b-v-lijst-ap-of-edpb).

Indien dit niet het geval is, en er ook geen [gegevensverwerking](#gegevensverwerking) uit de [lijst AP](#lijst-ap) wordt uitgevoerd, ontstaat er een [Organisatorische activiteit zonder DPIA-verplichting o.b.v. lijst AP of EDPB](#organisatorische-activiteit-zonder-dpia-verplichting-o-b-v-lijst-ap-of-edpb).

### Pre-scan DPIA - F. Basisregistraties {#IntroPre-scanDPIA_F_Basisregistraties}

Bij de [organisatorische activiteit persoonsgegevens](#organisatorische-activiteit-persoonsgegevens) moet, indien er sprake is van [gegevensverwerking](#gegevensverwerking)en die gebruik maken van een [basisregistratie](#basisregistratie), worden aangegeven van welke basisregistratie gebruik wordt gemaakt.

Het gaat om de volgende soorten basisregistraties:

* [Basisregistratie: Basisregistratie Grootschalige Topografie](#basisregistratie-basisregistratie-grootschalige-topografie)
* [Basisregistratie: Basisregistratie Inkomen](#basisregistratie-basisregistratie-inkomen)
* [Basisregistratie: Basisregistratie Kadaster](#basisregistratie-basisregistratie-kadaster)
* [Basisregistratie: Basisregistratie Ondergrond](#basisregistratie-basisregistratie-ondergrond)
* [Basisregistratie: Basisregistratie Personen](#basisregistratie-basisregistratie-personen)
* [Basisregistratie: Basisregistratie Topografie](#basisregistratie-basisregistratie-topografie)
* [Basisregistratie: Basisregistratie Voertuigen](#basisregistratie-basisregistratie-voertuigen)
* [Basisregistratie: Basisregistratie Waarde Onroerende Zaken](#basisregistratie-basisregistratie-waarde-onroerende-zaken)
* [Basisregistratie: Handelsregister](#basisregistratie-handelsregister)

### Pre-scan DPIA - G. Algoritmes/AI {#IntroPre-scanDPIA_G_Algoritmes_AI}

Bij de [organisatorische activiteit persoonsgegevens](#organisatorische-activiteit-persoonsgegevens) kan er sprake zijn van het gebruik van een [algoritme](#algoritme). Indien er [sprake van een algoritme](#algoritme-sprake-van-een-algoritme) is, dan is de organisatorische activiteit een [organisatorische activiteit met algoritme](#organisatorische-activiteit-met-algoritme). Daarbij wordt een aanduiding of er sprake is van inzet van een [AI-systeem](#ai-systeem) vastgelegd.

Als er [sprake (is) van een algoritme dat kwalificeert als een AI-systeem](#ai-systeem-sprake-van-een-algoritme-dat-kwalificeert-als-een-ai-systeem), dan is de organisatorische activiteit een [Organisatorische activiteit met IAMA-verplichting](#organisatorische-activiteit-met-iama-verplichting).

### Pre-scan DPIA - J. Kinderrechten {#IntroPre-scanDPIA_J_Kinderrechten}

Bij de [organisatorische activiteit persoonsgegevens](#organisatorische-activiteit-persoonsgegevens) kan er sprake zijn van een [digitale dienst voor personen jonger dan 18 jaar](#digitale-dienst-voor-personen-jonger-dan-18-jaar). Als er sprake is van [digitale dienst voor personen jonger dan 18 jaar: een digitale dienst aangeboden die primair bedoeld is voor gebruik door personen jonger dan 18 jaar](#digitale-dienst-voor-personen-jonger-dan-18-jaar-een-digitale-dienst-aangeboden-die-primair-bedoeld-is-voor-gebruik-door-personen-jonger-dan-18-jaar), dan geldt er een [KIA-verplichting](#kia-verplichting), waarbij er een [Kinderrechten Impact Assessment](#kinderrechten-impact-assessment) moet worden gemaakt, en is er dus sprake van een [organisatorische activiteit met KIA-verplichting](#organisatorische-activiteit-met-kia-verplichting).