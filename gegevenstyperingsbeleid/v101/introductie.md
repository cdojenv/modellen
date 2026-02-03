# Introductie {#Intro}

Het gegevenstyperingsbeleid heeft als doel om een gestructureerde en herhaalbare aanpak te bieden om te komen tot een beschrijving van de betekenis van [gegevens](#gegevens), door deze te benoemen en structureren. Daarom wordt dit begrippenkader en informatiemodel voor de gegevenstypering aangeboden.

In deze introductie worden de gemodelleerde begrippen in het JAGA [gegevenstyperingsbeleid](https://jenvgegevens.pleio.nl/page/view/2775c681-1f4a-4819-8776-d7d93e81ea90/gegevenstypering) verbonden in een verhaal, waardoor het model begrijpelijker wordt. Hiermee hopen we de begrippen die we gebruiken zodanig te verduidelijken dat deze, samen met de handreiking, zorgen dat gegevenstypering uitvoerbaar wordt.

## De context van de gegevens  {#IntroContext}

De modellering van het gegevenstyperingsbeleid en de onderwerpen die daarin worden behandeld hebben een bepaalde samenhang. Deze samenhang wordt hieronder getoond. In de daaropvolgende paragrafen worden die onderdelen en hun onderlinge samenhang besproken.

Hierbij merken we op dat de grijze gedeeltes zijn gemodelleerd om de begrijpelijkheid van het model te verhogen, maar niet bedoeld zijn om op te nemen in een administratie. Vanuit hun aard is dat niet mogelijk.

![Overzicht samenhang onderdelen](diagram6blokken.svg "Samenhang onderdelen gegevenstyperingsbeleid")

### De werkelijkheid en het beschouwingsdomein {#IntroBeschouwingsdomein}

Het primaire uitgangspunt U1 van het [gegevenstyperingsbeleid](#gegevenstyperingsbeleid) is dat inzicht in gegevens, allereerst inzicht in het [beschouwingsdomein](#beschouwingsdomein) vereist. Dit beschouwingsdomein betreft alle "dingen in het domein" die we relevant vinden. Een [beschouwingsdomein](#beschouwingsdomein) kent een naam en een beschrijving. Dit is bij voorkeur in een verhalende vorm, het narratief. Deze introductie is daarvan een voorbeeld. Daarnaast worden alle begrippen die in dat verhaal worden gebruikt in een begrippenkader gebundeld. Elk begrip in het beschouwingsdomein is eenduidig beschreven en is dus uniek binnen het domein.

Het deel van de werkelijkheid wat wij zien als een beschouwingsdomein bestaat zelf uit de [domeinobjecten](#domeinobject), de relevante [domeinrelaties](#domeinrelatie) tussen deze [domeinobjecten](#domeinobject), en alle [kenmerken](#kenmerk) van die domeinobjecten en domeinrelaties die wij op enige manier belangrijk vinden.

Een [kenmerk](#kenmerk) van een domeinobject kan een bepaalde [waarde](#waarde) hebben.
<!-- Daardoor ontstaan [feiten over eigenschappen van domeinobjecten](#feit-over-eigenschap-van-domeinobject) en [feiten over categorische kenmerken van domeinobjecten](#feit-over-categorisch-kenmerk-van-domeinobject). Een feit over een eigenschap van een domeinobject geeft een [letterlijke waarde](#letterlijke-waarde) aan een [eigenschap](#eigenschap) van een domeinobject, zoals bijvoorbeeld de lengte. Een letterlijke waarde heeft geen bijbetekenis. -->

<!-- Een feit over een categorisch kenmerk van een domeinobject geeft een [categorie](#categorie) of categorische waarde aan een [categorisch kenmerk](#categorisch-kenmerk) van een domeinobject. -->
Dit kan een eenvoudige letterlijke waarde zijn (bijvoorbeeld de waarde 26 voor de leeftijd van een persoon) of een [complexe waarde](#complexe-waarde) zijn, die weer bestaat uit andere waarden. Een voorbeeld is "100 meter", die bestaat uit twee waarden, waarvan één letterlijk en één die een [categorie](#categorie) aangeeft.

Er kunnen ook relaties tussen domeinobjecten bestaan, en als we specifiek die [domeinrelaties](#domeinrelatie) willen beschouwen als zelfstandige objecten met kenmerken, dan is zo'n relatie zelf ook een bepaald soort domeinobject, een [relatiedomeinobject](#relatiedomeinobject). Een concreet voorbeeld is een huwelijk, geboorte of een arbeidsrelatie, die (los van de daarin verbonden domeinobjecten) zelfstandige ook aspecten kunnen hebben waarover we iets willen weten of zeggen.

#### Conceptualisatie van het beschouwingsdomein {#IntroConceptualisatie}

Om over de feiten in het beschouwingsdomein te kunnen praten, hebben we kenmerken geïntroduceerd. Dit zijn op zichzelf geen zaken in het domein, maar deze benoemen de aspecten van domeinobjecten waar we over kunnen praten. Ze liggen dus tussen de werkelijkheid en het conceptuele model in, en maken de beschouwing van het beschouwingsdomein mogelijk.

Een [kenmerk](#kenmerk) is óf een [inherent kenmerk](#inherent-kenmerk), of een [rol](#rol). Een rol is de manier waarop een domeinobject is verbonden met een ander domeinobject: zo kan bijvoorbeeld een Persoon verbonden zijn met een Organisatie in de rol van medewerker, maar tegelijkertijd (in een andere domeinrelatie) ook als klant.

Een inherent kenmerk is onlosmakelijk verbonden met het domeinobject zelf. Hierin onderkennen we twee smaken: een [categorisch kenmerk](#categorisch-kenmerk) waarvan de waarde verwijst naar een categorie met een specifieke betekenis (zoals: beroep), en een [eigenschap](#eigenschap) waarvan de waarde letterlijk genomen mag worden (zoals lengte, geboortedatum of leeftijd).

<!-- Een kenmerk bestaat pas in de werkelijkheid als we er ook een waarde aan kunnen geven, waarover later meer. -->

### Verslaglegging over de werkelijkheid door gegevens {#IntroGegevens}

De werkelijkheid kunnen we beschouwen door uitspraken te doen over de waarde van kenmerken van domeinobjecten. Zodra we die gaan vastleggen in een administratie, ontstaan er [elementaire gegevens](#elementair-gegeven).

Een [elementair gegeven](#elementair-gegeven) is een [vastgelegde uitspraak](#vastgelegde-uitspraak) over (de waarde van) een kenmerk van een domeinobject of domeinrelatie uit een bepaald beschouwingsdomein, met een beoogde menselijke betekenis. Een gegeven kent een [gegevensbron](#gegevensbron) waarvan de uitspraak afkomstig is.

Gegevens kunnen ook over andere gegevens gaan. Het moment dat een bepaald gegeven is vastgelegd is bijvoorbeeld een uitspraak over de letterlijke waarde van het kenmerk "registratiedatum" voor het elementair gegeven "de geboortedatum van Jan is 1 januari 2021". Gegevens die iets zeggen over andere gegevens noemen we [metadata](#metadata).

Zoals gesteld in uitgangspunt U2 kennen de domeinobjecten en hun domeinrelaties en vervolgens de gegevens en gegevensobjecten met gegevens over die domeinobjecten en hun relaties een eigen (en mogelijk van elkaar verschillende) levenscyclus.

<!-- De levensduur van de domeinobjecten en de relaties daartussen noemen we de [geldigheidstijd](#geldigheidstijd), de levensduur van de gegevens over die domeinobjecten en hun relaties noemen we de [registratietijd](#registratietijd). in principe is de tijdslijn van een gegeven metadata, maar we benoemen deze expliciet vanwege het grote belang van deze specifieke soort metadata. -->

Een elementair gegeven kan onderdeel zijn van een groep elementaire gegevens, een [gegevensobject](#gegevensobject). Zo'n gegevensobject is de kleinste groep van elementaire gegevens die nog als eenheid wordt verwerkt. Het hoofdonderwerp van een gegevensobject is het domeinobject waarover de gegevens uit dit gegevensobject in hoofdzaak gaan.

<!--Een groep elementaire gegevens en/of gegevensobjecten kan worden gebundeld in een [informatieobject](#informatieobject). Een informatieobject heeft altijd een eigen identiteit, maar niet noodzakelijk een enkel domeinobject als hoofdonderwerp.-->

Een groep elementaire gegevens kan als een [gegevensset](#gegegensset) worden aangemerkt. Het gaat daarbij om gegevens die in samenhang worden beheerd door één organisatie. Met gegevenssets wordt de verantwoordelijkheid voor deze groep van gegevens toegewezen aan een [gegevensverantwoordelijke](gegevensverantwoordelijke). Een gegevensset zit altijd in een [gegevensopslag](#gegevensopslag).

### De betekenis van gegevens {#IntroBetekenis}

Gegevens kunnen op meerdere manieren betekenis krijgen:

* De [normatieve betekenis](#normatieve-betekenis) volgt uit de definitie zoals vastgelegd in [wet- en regelgeving](#wet-en-regelgeving), uitvoeringsbeleid of andere normatieve kaderstelling en wordt geformaliseerd in het [conceptueel informatiemodel](#onceptueel-informatiemodel);
* De [pragmatische betekenis](#pragmatische-betekenis) volgt uit het gebruik van de gegevens en de impact die dit gebruik met zich meebrengt. Het is de betekenis van een gegeven in een verwerkingscontext, dus in een specifieke situatie of verwerkingsdomein, die kan veranderen indien we van context veranderen. Bij het bepalen van de pragmatische betekenis van een gegeven zijn "wie, wat, waar, hoe en wanneer" belangrijke vragen. Voor de pragmatische betekenis is de verbinding met het [procesmodel](#procesmodel) relevant;
* De [intrinsieke betekenis](#intrinsieke-betekenis) volgt uit de aard van de gegevens zelf, zoals de logische en technische vorm, structuur, en relatie met andere gegevens. Deze is dus vooral terug te vinden in het [logisch gegevensmodel](#logisch-gegevensmodel) en [technische datamodel](#technisch-gegevensmodel).

De betekenis van gegevens wordt conform uitgangspunt U3, uitgedrukt in een menselijke taal, als begrippen met een beoogde betekenis. Die leggen we vast in een [begrippenkader](#begrippenkader), wat bestaat uit de [begrippen](#begrip). Daarmee beschrijven we de terminologie waarmee we over het [beschouwingsdomein](#beschouwingsdomein) kunnen praten. Een begrippenkader wordt gekenmerkt door de naam, en heeft een versie met versiedatum, en een toelichting die beschrijft waar het begrippenkader over gaat.

Begrippen worden binnen een begrippenkader gekenmerkt door hun [voorkeursterm](#voorkeursterm), en beschreven door een begripsdefinitie. Een begrip wordt verder voorzien van een aantal beschrijvende onderdelen. Dit zijn de unieke code van een begrip (indien relevant), eventuele alternatieve termen en zoektermen, een toelichting zoals deze, voorbeelden, een redactionele notitie, en een [juridische classificatie](#juridische-classificatie) van het begrip als het om een juridisch begrip gaat.

Indien mogelijk wordt de definitie van een begrip uit een formele [kennisbron](#kennisbron) overgenomen, conform uitgangspunt U10. Een kennisbron wordt gekenmerkt door de naam, krijgt een toelichting, en kan worden gevonden middels een URL of bronverwijzing.

Een vergelijkbaar begrip kan ook bestaan in een ander beschouwingsdomeinen of begrippenkader, maar  mogelijk met een andere voorkeursterm of afwijkende begripsbeschrijving. In dat geval kunnen we een [taalbinding](#taalbinding) aanleggen die aangeeft op welke manier je de twee begrippenkaders met elkaar kan verbinden. Begrippen hoeven niet één op één op elkaar te passen, zolang we maar kunnen bepalen hoe we van het ene begrippenkader naar het andere kunnen komen, zodat we de [semantische interoperabiliteit](#semantische-interoperabiliteit) van de domeinen kunnen borgen.

De [herleidbaarheid van de normatieve betekenis](#herleidbaarheid-normatieve-betekenis) van een begrip wordt geborgd met verwijzingen naar de relevante kennisbron(nen) voor dat begrip. De [herleidbaarheid van de pragmatische betekenis](#herleidbaarheid-pragmatische-betekenis) ligt in de opsomming van de gegevenstypen die worden verwerkt in een gegevensverwerking. De [herleidbaarheid van de intrinsieke betekenis](#herleidbaarheid-intrinsieke-betekenis) van gegevens wordt geborgd door een correcte [gegevensmodellering](#gegevensmodellering), in combinatie met verwijzingen naar de [normatieve](#normatieve-betekenis) en [pragmatische betekenis](#pragmatische-betekenis).

### Modellering en typering van de gegevens {#IntroGegevensmodellering}

De gedane uitspraken kunnen we vaak onderbrengen in categorieën met eigen regels en een eigen naam: we kunnen deze uitspraken dus gaan typeren. Daarmee stellen we eisen aan de vastlegging van uitspraken over bijvoorbeeld het begrip "persoonsnaam". Dat is iets anders dan het typeren van *kenmerken van domeinobjecten*, waarbij we bijvoorbeeld zeggen dat elke Persoon een naam heeft.

Een samenhangende modellering van alle gegevens waar men eisen aan wil stellen noemen we een [logisch gegevensmodel](#logisch-gegevensmodel). Een logisch model beschrijft een (deel van een) [verwerkingsdomein](#verwerkingsdomein).

In een verwerkingsdomein verwerken we gegevenssets. Deze worden beschreven of gespecificeerd in een [gegevenssetspecificatie](#gegevenssetspecificatie) die belangrijk is voor de verwerking. Deze bestaat uit een logisch model en een inhoudelijke beschrijving van de gegevens, de populatiebeschrijving.

Een logisch model wordt opgebouwd uit [gegevensobjecttypen](#gegevensobjecttype). Deze typeren een groep gelijksoortige gegevensobjecten. Gegevensobjecten met informatie over de persoon "Marco", "Mohammed" en "Ronald" kunnen bijvoorbeeld worden getypeerd door een gegevensobjecttype "Persoon". Er zijn twee soorten gegevensobjecttypen: [gegevensobjecttype met domeinobjecttype als hoofdonderwerp](#gegevensobjecttype-met-domeinobjecttype-als-hoofdonderwerp) en [gegevensobjecttype met domeinrelatietype als hoofdonderwerp](#gegevensobjecttype-met-domeinrelatietype-als-hoofdonderwerp).

Een gegevensobjectype bestaat uit alle [gegevenstypen](#gegevenstype) waarvan de gegevens relevant zijn voor de beschrijving van een domeinobject. Uit die gegevenstypen worden degene gekozen die samen een uniek gegevensobject identificeren. Deze gegevenstypen vormen samen de sleutel van het gegevensobjecttype. De sleutel gebruiken we om de gegevensobjecten die we typeren uit elkaar te kunnen houden. Sommige gegevenstypen verwijzen naar andere [gegevensobjecttypen](#gegevensobjecttype), en daarmee worden relaties ingevuld.

Een [gegevenstype](#gegevenstype) benoemt en structureert gelijksoortige [elementaire gegevens](#elementair-gegeven). Elementaire gegevens met uitspraken over de haarkleur van personen leidt tot het gegevenstype "haarkleur". Als we een [elementair-gegeven](#elementair-gegeven) typeren, dan kennen we een naam, betekenis, vorm, eventueel een code en mogelijke voorwaarden of condities voor de invulling of het gebruik. Een gegevenstype kan worden onderverdeeld in twee soorten: een [relatiegegevenstype](#relatiegegevenstype) of een [waardegegevenstype](#waardegegevenstype).

Een relatiegegevenstype heeft geen eigen datatype, maar verwijst naar de sleutel van een [gegevensobjecttype](#gegevensobjecttype) en heeft als hoofdonderwerp een enkele [domeinrelatieverbintenis](#domeinrelatieverbintenis) uit het conceptuele informatiemodel.

Een waardegegevenstype verwijst niet naar een ander gegevensobjecttype, maar gegevens van dat type worden gevuld met [letterlijke waardetypen](#letterlijk-waardetype) of [categorische waardetypen](#categorisch-waardetype) en verwijst dus naar een [attribuuttype](#attribuuttype) in het conceptueel informatiemodel. Een waardegegevenstype wordt beperkt in haar invulling door een [datatype](#datatype). Dit typeert de mogelijke waarden die het gegevenstype als invulling kan krijgen, zoals bijvoorbeeld "datum". Een waardetype kan een [primitief datatype](#primitief-datatype) zijn, zoals Getal, Tekst, Datum, etc. of een combinatie van meerdere primitieve datatypen in een [gestructureerd datatype](#gestructureerd-datatype) zoals bijvoorbeeld een afstand die uiteenvalt in een eenheid en een maat: "10 kilometer" valt uiteen in "10" en "kilometer", indien dat voor het verwerkingsdomein relevant is.

### Modellering en typering van de concepten {#IntroConceptmodellering}

De werkelijkheid waarin "dingen" een rol spelen en waarvan we iets willen weten van of zeggen over de aspecten van die dingen die we belangrijk vinden, vormen samen het [beschouwingsdomein](#beschouwingsdomein). De dingen in dat beschouwingsdomein, hun onderlinge relaties en de aspecten waar we iets over willen zeggen, kunnen we in hun onderlinge samenhang modelleren in een [conceptueel informatiemodel](#conceptueel-informatiemodel).

De [conceptuele informatiemodelelementen](#conceptueel-informatiemodelelement) zijn de [domeinobjecttypen](#domeinobjecttype), hun [attribuuttypen](#attribuuttype) en de [domeinrelatietypen](#domeinrelatietype) die de relaties tussen de domeinobjecttypen weergeven.

Een [domeinobjecttype](#domeinobjecttype) typeert gelijksoortige domeinobjecten en benoemt de kenmerken die deze domeinobjecten gemeenschappelijk hebben. Een domeinobjecttype groepeert de [inherente kenmerken](#inherent-kenmerk) die relevant zijn voor elk domeinobject van dat type. Dit zijn de aan een domeinobject geattribueerde getypeerde inherente kenmerken, kortweg de [attribuuttypen](#attribuuttype). Bepaalde geattribueerde inherente kenmerken vormen samen een manier om het ene getypeerde domeinobject van het andere te onderscheiden, de identificator.

De [attribuuttypen](#attribuuttype) vallen uiteen in twee verschillende soorten: de [concrete attribuuttypen](#concreet-attribuuttype), die soortgelijke onvervreemdbare eigenschappen van een domeinobject typeren zoals bijvoorbeeld de geboortedatum, de naam of het BSN, en de [classificerende attribuuttypen](#classificerend-attribuuttype), die een soortgelijk categorisch kenmerk van een domeinobject typeert zoals de functie of de biologische soort. Deze verwijzen naar een categorie.

Aan een attribuuttype kan een conditie worden toegekend in het model, die een beperking oplegt aan het attribuuttype. Zo kan bijvoorbeeld de cardinaliteit van het attribuuttype in het domeinobject worden begrensd.

Een attribuuttype kan uitsluitend bepaalde waarden aannemen. Deze soortgelijke waarden worden getypeerd door een [waardetype](#waardetype). Dit kan een [letterlijk waardetype](#letterlijk-waardetype) zijn voor een concreet attribuuttype, waarin alleen soortgelijke letterlijke waarden passen, of een [categorisch waardetype](#categorisch-waardetype) voor een classificerend attribuuttype, dat verwijst naar een [categorie](#categorie).

Een attribuuttype kan waarden aannemen die getypeerd worden door een [complex waardetype](#complex-waardetype), wat zelf bestaat uit een combinatie van letterlijke en categorische waardetypen, zoals bijvoorbeeld "100 euro", wat uiteenvalt in een bedrag (letterlijk waardetype) met een valuta (categorisch waardetype). Er is dus niet altijd een één op één correspondentie tussen een concreet attribuuttype en een letterlijk waardetype, al zal dat wel vaak voorkomen.

De [domeinrelatietypen](#domeinrelatietype) typeren soortgelijke [domeinrelaties](#domeinrelatie) tussen de domeinobjecten. Een domeinrelatieverbintenis kan worden gezien als één poot van een relatie. Er zijn er minimaal twee nodig om een relatie tussen twee domeinobjecten te leggen,daarom bestaat een domeinrelatietype uit minimaal twee [domeinrelatieverbintenissen](#domeinrelatieverbintenis).

Een domeinrelatieverbintenis verbind een domeinobjecttype met een rol die dat domeinobjecttype speelt, in een domeinrelatietype. De verbintenis heeft een minimale en maximale cardinaliteit in het domeinrelatietype. Er kunnen in principe een onbeperkt aantal domeinrelatieverbintenissen meedoen in een domeinrelatietype, maar deze zullen in de regel niet verder gaan dan (bij hoge uitzondering) vier domeinrelatieverbintenissen.

Een domeinrelatietype waarbij men over de aspecten van dat type weer aspecten wil modelleren, wordt verzelfstandigt tot een eigen domeinobjecttype, een [relatiedomeinobjecttype](#relatiedomeinobjecttype). Dit is zowel een domeinobjecttype als een domeinrelatietype.

<!-- Een relatiedomeinobjecttype typeert gelijksoortige [relatiedomeinobjecten](#relatiedomeinobject) uit het beschouwingsdomein. -->

### Het verwerkingsdomein {#IntroVerwerkingsdomein}

We hebben het gehad over de betekenis van gegevens, en hoe de [normatieve betekenis](#normatieve-betekenis) volgt uit [wet- en regelgeving](#wet-en-regelgeving), uitvoeringsbeleid of andere normatieve kaderstelling, en de [pragmatische betekenis](#pragmatische-betekenis) volgt uit het gebruik van de gegevens en de impact die dit gebruik met zich meebrengt. Uitgangspunt U4 stelt dan ook: het gebruik van gegevens is bepalend voor de betekenis, omdat dit duidelijk maakt wat de gegevens daadwerkelijk voor impact hebben. Die impact is helder als iemand geen uitkering krijgt op grond van een foutief ingevoerd gegeven, of betaalde toeslagen worden teruggevorderd door een verkeerde interpretatie van de ingevoerde gegevens. Maar het gaat ook om bijvoorbeeld de manier waarop gegevens worden ingevoerd, of in welke vorm.

Gegevensgebruik vind plaats binnen een afgebakend deel van de organisatie, het [verwerkingsdomein](#verwerkingsdomein). Een [verwerkingsdomein](#verwerkingsdomein) geeft de afbakening weer van de gegevens en hun verwerking (uitwisseling, registratie, creatie, gebruik, vernietiging). Het bestaat uit alle soorten gegevensverwerkingen, de [gegevensverwerkingstypen](#gegevensverwerkingstype), die binnen [organisatorische activiteiten](#organisatorische-activiteiten) gebeuren.
De normatieve en pragmatische betekenis van de daarin gebruikte gegevens vloeien voort uit de manier waarop het verwerkingsdomein is ingericht. Daarom is kennis daarover relevant voor gegevenstypering.

Aangezien die verwerkingen plaatsvinden binnen een [organisatorische activiteit](#organisatorische-activiteit) die ontstaan is om een reden, is de pragmatische betekenis van gegevens primair afgeleid van de grondslag van die [organisatorische activiteit](#organisatorische-activiteit), namelijk de [organisatorische doelstelling](#organisatorische-doelstelling) waarvoor die [organisatorische activiteit](#organisatorische-activiteit) wordt gestart of ingericht.

Een [organisatorische doelstelling](#organisatorische-doelstelling) is een doelstelling om te voldoen aan [wet- en regelgeving](#wet-en-regelgeving), of aan een andere eis die de omgeving of de eigen organisatie oplegt die niet voortkomt uit wet- en regelgeving, een [motivatie](#motivatie). Een [organisatorische doelstelling](#organisatorische-doelstelling) die gebaseerd is op een [motivatie](#motivatie) heet soms ook wel een gebruikersdoel of gebruikersdoeleind. Voorbeelden van [motivatie](#motivatie)s zijn bijvoorbeeld de wens om de reputatie van de organisatie te behouden en verbeteren, om marktaandeel te behouden of vergroten, of om de organisatie in stand te houden.

Een [organisatorische activiteit](#organisatorische-activiteit) die de overheid onderneemt is altijd verbonden met de relevante wet- en regelgeving:

* óf het is de aanleiding (via de organisatorische doelstelling, bijvoorbeeld omdat de organisatie de taakstelling heeft om een wet uit te voeren),
* óf het is van toepassing doordat we gegevens gaan verzamelen die onderhevig zijn aan bepaalde wet- en regelgeving.

Deze [wet- en regelgeving](#wet-en-regelgeving) leggen we vast. in de praktijk zal op één [organisatorische activiteit](#organisatorische-activiteit) meer dan één stuk [wet- en regelgeving](#wet-en-regelgeving) van toepassing zijn, bijvoorbeeld de [[AVG]] én de [[Archiefwet]]. De [wet- en regelgeving](#wet-en-regelgeving) die de aanleiding vormt of van toepassing is op een [organisatorische activiteit](#organisatorische-activiteit), bepaalt de [normatieve betekenis](#normatieve-betekenis) van de gegevens die onder die wet- en regelgeving wordt verwerkt.

De [organisatorische activiteiten](#organisatorische-activiteit) die vervolgens op grond van de grondslagen worden ingericht en uitgevoerd zijn onderhevig aan [uitvoeringsregels](#uitvoeringsregel). De uitvoeringsregels worden afgeleid van de organisatorische doelstellingen, en zijn dus mede bepalend voor de normatieve betekenis van de daarin gebruikte gegevens. Die uitvoeringsregels kunnen worden gebundeld of gebruikt in [algoritmen](#algoritme) of werkinstructies. Deze laatste zijn dus mede bepalend voor de pragmatische betekenis van de gebruikte gegevens.

Een organisatorische activiteit kan niet worden uitgevoerd zonder gegevens te verwerken. Vergelijkbare gegevensverwerkingen die dagelijks worden uitgevoerd kunnen worden getypeerd in een [gegevensverwerkingstype](#gegevensverwerkingstype) zoals "Raadplegen externe gegevensbron" of "inscannen gegevens op binnengekomen formulier". De gegevensverwerkingstypen zijn bepalend voor de omvang van het [verwerkingsdomein](#verwerkingsdomein): alle gegevens die worden verwerkt in de gegevensverwerkingstypen vallen binnen het verwerkingsdomein.

Elk gegevensverwerkingstype specificeert de daarbinnen gebruikte gegevens in [gegevenssetspecificaties](#gegevenssetspecificatie). Deze beschrijven de structuur van de gegevens middels een logisch gegevensmodel, en de inhoud van de gegevens aan de hand van een populatiebeschrijving. Zo wordt duidelijk dat een lijst met adresgegevens (structuur) gaat over adressen van verdachten (inhoud). Samen zijn ze nodig voor bijvoorbeeld de inschatting van privacyrisico's en te nemen maatregelen.

Sommige gegevenstypen die in een gegevensverwerkingstype worden gebruikt zijn [kritieke gegevenselementen](#kritiek-gegevenselement), die bepalend zijn voor de betrouwbare uitvoering van de verwerking. Deze worden apart beschouwd omdat het [[Gegevenskwaliteitsbeleid]] zich met name op die gegevenstypen in de gegevensverwerkingen richt.

### Verantwoordelijkheden

Voor elke gegevensset is er een [gegevensverantwoordelijke](#gegevensverantwoordelijke) functionaris die de verantwoordelijkheid draagt voor het beheer van die gegevensset, en daarmee o.a. dus voor de kwaliteit, betrouwbaarheid, integriteit en veiligheid. De gegevensverantwoordelijke is ook eindverantwoordelijk voor een actuele, juiste en betrouwbare beschrijving van deze gegevenssets door middel van gegevenstypering.

Omdat de impact van verkeerde omgang met gegevens zo groot is, stelt uitgangspunt U5 dat het beleggen van de verantwoordelijkheid voor de gegevenstypering noodzakelijk is voor een doelmatige en verantwoorde verwerking van gegevens, en uiteindelijk dus ook voor de rechtmatige verwerking van die gegevens. Er moet dus een eindverantwoordelijke zijn voor het duiden van de betekenis(sen) van gegevens door het beschrijven van de begrippen en (daarmee) het toekennen van betekenis aan de gegevens. Deze eindverantwoordelijke heeft de rol van [gegevensverantwoordelijke](#gegevensverantwoordelijke). Deze is verantwoordelijk voor de naleving van de [normatieve betekenis](#normatieve-betekenis) in de praktijk, dus de samenhang tussen de [normatieve betekenis](#normatieve-betekenis) en de [praktische betekenis](#praktische-betekenis).

De eindverantwoordelijkheid voor gegevenstypering en het toeschrijven van betekenis aan gegevens ligt op bestuurlijk niveau bij de [gegevensverantwoordelijke](#gegevensverantwoordelijke), conform uitgangspunt U6. De gegevensverantwoordelijke is altijd een medewerker van de [partij](#partij) die verantwoordelijk is voor de uitvoering van een bepaald soort organisatorische activiteit.

Aangezien conform uitgangspunt U7 er continu beheer nodig is, is er iemand nodig die permanent bezig is met de gegevenstypering en begripsbeschrijving. De gegevensverantwoordelijke stelt daartoe een [persoon](#persoon) aan in een [gegevenskwaliteit rol](#gegevenskwaliteit-rol) genaamd [gegevensmodelleur](#gegevensmodelleur) cq. kennismodelleur. Hiermee wordt de samenhang met de [intrinsieke betekenis](#intrinsieke-betekenis) geborgd.

Een actuele en correct uitgevoerde [gegevenstypering](#gegevenstypering-0) is een voorwaarde om het [gegevenskwaliteitsproces](#gegevenskwaliteitsproces) uit te kunnen voeren. Als de normatieve en intrinsieke betekenis van gegevens niet bekend is, is het onmogelijk om te bepalen of de vastgelegde gegevens daarmee overeenstemmen en dus als correct kunnen worden beschouwd.

In het [gegevensbeleid](#gegevensbeleid) van een organisatie wordt in meer detail uitgewerkt hoe men de verantwoordelijkheid voor de omgang met gegevens (inclusief de [metadata](#metadata)) in de organisatie invult.

Organisaties die samenwerken met andere organisaties moeten onderling afspraken maken over hoe de gegevenstypering wordt ingevuld, conform uitgangspunt U8. De in de organisatie aanwezige gegevenstypering wordt openbaar gemaakt, conform uitgangspunt U9. Dit maakt het eenvoudiger voor andere organisaties om samen te werken. Publicatie mag alleen achterwege worden gelaten als de publicatie een onevenredige inspanning vereist of vanwege wettelijke beperkingen niet is toegestaan.

### Modelsoorten

Een complete gegevensmodellering bestaat uit vier typen modellen:

* een [semantisch model](#semantisch-model) conform [[NL-SBB]], uitgedrukt in bijvoorbeeld [[W3C-SKOS]];
* een [conceptueel model](#conceptueel-model), conform [[MIM]] niveau 2, uitgedrukt in bijvoorbeeld [Fact-based modeling](#fact-based-modeling), [Unified Modeling Language](#unified-modeling-language), [Entity-Relationship Modeling](#entity-relationship-modeling), [Web Ontology Language](#web-ontology-language), [Shapes Constraint Language](#shapes-constraint-language) et cetera.
* een [logisch gegevensmodel](#logisch-gegevensmodel), conform [[MIM]] niveau 3, uitgedrukt in bijvoorbeeld [Fact-based modeling](#fact-based-modeling), [Unified Modeling Language](#unified-modeling-language), [Entity-Relationship Modeling](#entity-relationship-modeling), [Web Ontology Language](#web-ontology-language), [Shapes Constraint Language](#shapes-constraint-language) et cetera.
* een [technisch gegevensmodel](#technisch-gegevensmodel), uitgedrukt in een vorm die afhankelijk is van de gekozen implementatie.

Hierin wordt de betekenis van gegevens als volgt vastgelegd:

* De [normatieve betekenis](#normatieve-betekenis) wordt geduid in het [semantisch model](#semantisch-model) en vaak gecommuniceerd met behulp van het [conceptueel model](#conceptueel-model).
* De [praktische betekenis](#praktische-betekenis) wordt geduid in de relatie tussen de verschillende gegevensmodellen en de bijbehorende [bedrijfsregelmodellen](#bedrijfsregelmodel) en [procesmodellen](#procesmodel).
* De [intrinsieke betekenis](#intrinsieke-betekenis) wordt nader gespecificeerd in een [logisch gegevensmodel](#logisch-gegevensmodel) en [technisch gegevensmodel](#technisch-gegevensmodel).

Voor de modellering van het verwerkingsdomein en de organisatorische verantwoordelijkheden is de meest voorkomende modellering die van een bedrijfsarchitectuurmodel conform TOGAF, bijvoorbeeld uitgedrukt in een grafische notatie zoals bijvoorbeeld Archimate.
