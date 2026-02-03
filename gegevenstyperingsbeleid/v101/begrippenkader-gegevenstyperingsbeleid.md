# Begrippen

## Begrippenkader Gegevenstypering

### Administratie

> Elk systeem, applicatie, proces of andere bewaarplaats waarin gegevens worden bewaard, met de bedoeling om te allen tijde de rechten en verplichtingen van de rechtspersoon te kunnen kennen.

Toelichting: Het is een wettelijke verplichting dat binnen een organisatie of extern daaraan alle gegevens die nodig zijn om de rechten en plichten van de organisatie te kunnen kennen, worden bewaard. Het administreren omvat zowel de opslag en bewaking van de gegevens, als de processen om die gegevens heen om deze actueel en correct te houden.

Bron: Titel 1, artikel 10, [[BW2]]

Voorbeeld(en): De basisregistraties uit het stelsel basisregistraties vormen administraties over de gegevens die betrekking hebben op een bepaald onderwerp.

### Algoritme

> Een algoritme is een set van [uitvoeringsregels](#uitvoeringsregel) die (eventueel non-deterministisch) wordt gevolgd bij het maken van berekeningen om een probleem op te lossen of een vraag te beantwoorden.

Toelichting: Algoritmen bestaan uit een reeks, meestal wiskundige, instructies of uitvoeringsregels. Wanneer deze instructies een bepaalde input krijgen, dan gaat deze door deze instructies heen en er volgt een output op basis van die instructies. 

Afzonderlijke uitvoeringsregels die volgordelijk en deterministisch worden uitgevoerd, kunnen we in het verwerkingsdomein groeperen tot algoritmen.

Ook "kunstmatige intelligentie" noemen we algoritmen. Dit zijn algoritmen die op grond van statistiek en wiskundige redeneringen antwoorden geven die niet per sé deterministisch zijn (dus waarbij de uitkomst niet altijd precies gelijk is als de input wel gelijk blijft) en daardoor meer risico's kennen dan deterministische regels als "wanneer iemand door rood licht rijd, krijgt men een boete."

*De definitie is een synthese van de definitie in het algoritmeregister, de AI Act en het gegevenstyperingsbeleid.*

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]], Het Algoritmeregister van de Nederlandse overheid [[Algoritmeregister]], Verordening (EU) 2024/1689 van het Europees parlement en de raad van 13 juni 2024, verordening artificiële intelligentie [[AIAct]]

Gerelateerd: [Uitvoeringsregel](#uitvoeringsregel)

Voorbeeld(en): Voorbeelden van algoritmes zijn bijvoorbeeld ChatGPT, het bepalen van de hoogte van een boete, of de manier waarop men twee getallen deelt.

### Attribuut

> Een attribuut is een [eigenschap](#eigenschap) van een [domeinobject](#domeinobject).

Toelichting: Haarkleur is een eigenschap in de realiteit. Maar de haarkleur van een cavia of paard heeft andere benamingen dan de haarkleur van een mens. Iemand met grijswit haar noemen we geen schimmel, bijvoorbeeld. Dus de toekenning van een eigenschap aan de domeinobjecten waar we over willen praten verandert de betekenis. De combinatie van een eigenschap zoals haarkleur /rood/ en een domeinobject als /Kees/

Gerelateerd: [Eigenschap](#eigenschap), [Domeinobject](#domeinobject)

### Attribuuttype

> Een attribuuttype typeert gelijksoortige attributen. Het attribuuttype wordt gevormd door een [eigenschap](#eigenschap) die wordt toegekend (geattribueerd) aan een [domeinobjecttype](#domeinobjecttype).

Toelichting: De eigenschap "naam" heeft voor een domeinobjecttype Persoon een andere lading dan voor domeinobjecttype Huisdier. Daarom verschillen de attribuuttypen.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]], MIM - Metamodel Informatie Modellering v1.2 (juni 2024) [[MIM]]

Gerelateerd: [Domeinobjecttype](#domeinobjecttype), [Eigenschap](#eigenschap)

Voorbeeld(en): Persoonsnaam is een attribuuttype dat eigenschaptype "naam" koppelt aan domeinobjecttype "persoon".

### Begrip

> Een begrip is een eenheid van denken - een idee, betekenis of categorisering. Een begrip wordt binnen een begrippenkader uniek geïdentificeerd door een [term](#term), die wordt voorzien van een definitie en gebundeld in een [begrippenkader](#begrippenkader) met andere termen die gezamenlijk de concepten in een [beschouwingsdomein](#beschouwingsdomein) beschrijven.

Toelichting: Begrippen worden weergegeven door termen die worden voorzien van een definitie. Elke term in een thesaurus moet een enkel begrip (of denkeenheid) vertegenwoordigen. Begrippen kunnen variëren van eenvoudig (bijv. katten) tot zeer complex (bijv. onderwerpen uit de wetenschap). Samengestelde termen of zinsdelen zijn over het algemeen nodig om de meer complexe begrippen uit te drukken.

Een begrip is feitelijk nooit los te zien van zijn context, dus het begrippenkader waarin het begrip dat bij een voorkeursterm hoort, wordt gedefinieerd, en het bijbehorende beschouwingsdomein. Daarom verwijzen gegevenselementen uitsluitend naar begrippen in een begrippenkader, dus ingebed in hun context.

De primaire taak van de gegevenstypering is het komen tot een beschrijving van de begrippen die gebruikt worden in gegevens: hun definitie, onderlinge relaties en grondslag voor de beoogde betekenis.

Een begrip wordt voorzien van een aantal beschrijvende onderdelen. Dit zijn de term waaronder het begrip bekend is, de unieke code van een begrip (indien relevant), en eventuele alternatieve termen en zoektermen, een toelichting zoals deze, voorbeelden, een redactionele opmerking, en een juridische classificatie van het begrip als het om een juridisch begrip gaat.

Bron: Begrip, [[NL-SBB]]

Gerelateerd: [Term](#term), [Beschouwingsdomein](#beschouwingsdomein), [Begrippenkader](#begrippenkader)

Voorbeeld(en): Voorraad in een begrippenkader over financiële administratie heeft een andere betekenis dan voorraad in een begrippenkader over magazijnbeheer, en is dus een ander begrip met dezelfde term: iets kan financieel in de voorraad vallen zonder fysiek aanwezig te zijn.

### Begrippenkader

Alternatieve aanduiding: *Thesaurus*

> Een begrippenkader is een verzameling van [begrippen]() die in een bepaalde context of [beschouwingsdomein](#beschouwingsdomein) relevant zijn.

Toelichting: Een begrippenkader is een taalgebaseerd model van begrippen dat helpt om een beter inzicht te krijgen in wat er wordt bedoeld met de termen in het begrippenkader. Een begrippenkader beschrijft de begrippen uit een beschouwingsdomein in hun onderlinge samenhang, dus in context. Begrippenkaders ordenen kennis om deze later eenvoudig te kunnen gebruiken, bijvoorbeeld in indexeringsschema's, thesauri, taxonomieën en andere kennisorganisatiesystemen.

Begrippenkaders verplichten het gebruik van vooraf gedefinieerde, geautoriseerde termen die zijn geselecteerd door de ontwerpers ervan, in tegenstelling tot natuurlijke taalvocabulaires,die een dergelijke beperking niet hebben.

Begrippenkaders zoals dit begrippenkader zelf, structureren we zoveel mogelijk in de vorm die de NL-SBB standaard voorschrijft.

Een begrippenkader heeft zelf minimaal een code, naam, toelichting, versie en versiedatum.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]], Kerndepartement J&V [[KDJV]], NL-SBB - Standaard voor het beschrijven van begrippen [[NL-SBB]]

Gerelateerd: [begrippen](#begrippen), [Beschouwingsdomein](#beschouwingsdomein)

Voorbeeld(en): Een voorbeeld is het begrippenkader voor de Gegevenstypering waar dit voorbeeld deel van uitmaakt.

### Benoemd conceptueel modelelement

> Een benoemd conceptueel modelelement is een bouwblok van een [conceptueel informatiemodel](#conceptueel-informatiemodel), wat is voorzien van een eigen naam. Het is of een [domeinobjecttype](#domeinobjecttype), een [attribuuttype](#attribuuttype) of een [domeinrelatietype](#domeinrelatietype).

Toelichting: De onderliggende elementen van die modelelementen zoals condities, rollen, identificatoren en dergelijke zitten natuurlijk ook in het conceptueel informatiemodel, maar deze krijgen geen eigen naam. We bedoelen hier de echte bouwblokken van een conceptueel informatiemodel.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Domeinrelatietype](#domeinrelatietype), [Attribuuttype](#attribuuttype), [Conceptueel informatiemodel](#conceptueel-informatiemodel), [Domeinobjecttype](#domeinobjecttype)

### Beschouwingsdomein

Alternatieve aanduiding: *Universe of Discourse*

> Een beschouwingsdomein is een afgebakend deel van de werkelijkheid dat wordt beschouwd. Het geeft de afbakening van zowel de fysieke, maatschappelijke, organisatorische als juridische zaken die van belang zijn.

Een beschouwingsdomein wordt (in de context van dit beleid) beschreven in een [begrippenkader](#begrippenkader), en de onderlinge samenhang van het domein wordt gemodelleerd in een [conceptueel informatiemodel](#conceptueel-informatiemodel).

Toelichting: Het beschouwingsdomein bestaat uit de domeinobjecten die we relevant achten en de eigenschappen van deze domeinobjecten en de relaties tussen deze domeinobjecten waarin we geïnteresseerd zijn.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Conceptueel informatiemodel](#conceptueel-informatiemodel), [Begrippenkader](#begrippenkader)

### Binaire domeinrelatie

> Een binaire domeinrelatie is een benoemde [domeinrelatie](#domeinrelatie) in een [beschouwingsdomein](#beschouwingsdomein) tussen precies twee [domeinobjecten](#domeinobject), die ieder een eigen [rol](#rol) spelen in die relatie.

Toelichting: Als Marco en Ronald met elkaar trouwen, dan krijgen ze een formele relatie met een naam en een status. Maar als ze samenwerken als collega bestaat er ook een relatie. We houden deze relaties uit elkaar door ze een naam te geven.

*Relaties kunnen natuurlijk ook tussen meer dan twee domeinobjecten tegelijk worden gevormd (ternaire, quaternaire etc. relaties), maar deze zijn niet noodzakelijk voor verder begrip van de materie en worden hier dus niet verder uitgewerkt.*

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Domeinobject](#domeinobject), [Beschouwingsdomein](#beschouwingsdomein), [Rol](#rol), [Domeinrelatie](#domeinrelatie)

### Categorie

Alternatieve aanduiding: *Categorische waarde*

> Een categorie is een groepering van [domeinobjecten](#domeinobject) met een gemeenschappelijke kwaliteit.

Toelichting: Een domeinobjecttype of categorie zijn soms lastig van elkaar te onderscheiden, omdat elk domeinobjecttype óók een categorie vormt. Maar we doelen hier met name op categorieën van domeinobjecten die niet per sé al hun kenmerken met elkaar delen, of waar de kenmerken niet relevant zijn voor het beschouwingsdomein.

Een categorie kan een subcategorie vormen van een andere categorie. De indeling van categorieën in een onderling verband kan een classificatieschema vormen.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Domeinobject](#domeinobject)

Voorbeeld(en): "Rood", "groen" en "oranje" zijn categorieën als ze betrekking hebben op een categorisch kenmerk "kleur verkeerslicht".

### Categorisch kenmerk

> Een categorisch kenmerk is een [kenmerk](#kenmerk) van iets in het domein waar een [categorie](#categorie) aan kan worden toegekend.

Toelichting: Een categorisch kenmerk is bijvoorbeeld "biologische soort". Deze kan bijvoorbeeld de categorische waarde "homo sapiens" hebben, indien het categorisch kenmerk geattribueerd is aan domeinobject Ronald.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Categorie](#categorie), [Kenmerk](#kenmerk)

Voorbeeld(en): "Biologische soort" is een categorisch kenmerk, omdat het verwijst naar een categorie.

### Categorisch waardetype

> Een categorisch waardetype is een [waardetype](#waardetype) waarmee gelijksoortige [categorische waarden]() worden getypeerd. Een categorisch waardetype betreft altijd een specifieke [categorie](#categorie).

Toelichting: Een categorisch waardetype is bijvoorbeeld "biologische soort", omdat deze alle categoriën typeert die een biologische soort aangeven. Deze kan bijvoorbeeld de categorie "homo sapiens" bevatten, indien het categorisch kenmerk geattribueerd is aan een menselijk domeinobject.

Een categorisch waardetype geeft aan welke mogelijke waarden een waardetype aan kan nemen.

*Een categorisch waardetype typeert categorieën van hetzelfde type. Het verschilt daarmee van een categorisch kenmerk dat categorieën die bij dat kenmerk horen toewijst aan een domeinobject .*

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Categorie](#categorie), [Waardetype](#waardetype), [categorische waarden](#categorische-waarden)

Voorbeeld(en): "Biologische soort" is een categorisch waardetype waar alle biologische soorten toe behoren.

### Citeertitel

> Een citeertitel is de naam waaronder een kennisbron extern bekend staat en waarmee daar naar kan worden verwezen. Voor formele kennisbronnen zoals wetgeving wordt vaak in de bron zelf een citeertitel opgenomen.

Toelichting: Een bronverwijzing naar een wet of ander gepubliceerd stuk zoals een boek of artikel wordt vaak gedaan door citeertitel te benoemen. Deze kan heel eenvoudig zijn (Wet bewaarplicht telecommunicatiegegevens) of heel uitgebreid, als daarbij het blad, de editie van het blad en zelfs de pagina's nodig zijn om eenduidig aan te geven wat nu precies wordt geciteerd is.

Een bronverwijzing kan een citeertitel zijn, maar dat hoeft niet. In NL-SBB is het wel zo dat voor wetgeving de citeertitel als bronverwijzing wordt gebruikt.

Bron: , NL-SBB - Standaard voor het beschrijven van begrippen [[NL-SBB]]

Voorbeeld(en): De "Wet van 18 juli 2009 tot wijziging van de Telecommunicatiewet en de Wet op de economische delicten in verband met de implementatie van Richtlijn 2006/24/EG van het Europees Parlement en de Raad van de Europese Unie betreffende de bewaring van gegevens die zijn verwerkt in verband met het aanbieden van openbare elektronische communicatiediensten en tot wijziging van Richtlijn 2002/58/EG (Wet bewaarplicht telecommunicatiegegevens)", wordt conform artikel VI als volgt aangeduid: "Wet bewaarplicht telecommunicatiegegevens".

### Classificatie

> Een classificatie is een indeling of groepering van objecten, gegevens of waarden in categorieën of klassen op basis van gedeelde kenmerken of criteria.

Toelichting: Een classificatie wordt gekenmerkt door een naam (of onderwerp), de categorie en een vastgestelde definitie (het is niet slechts een lijstje met waarden).

Bron: Kerndepartement J&V [[KDJV]]

### Classificatieschema

Alternatieve aanduiding: *taxonomie*

> Een classificatieschema is een systematische ordening van [categorische waarden]() in [categorieën](#categorie).

Toelichting: Elke systematische ordening van "dingen" in bij elkaar behorende groepen op grond van een gemeenschappelijk kenmerk of "kwaliteit" is een classificatieschema. Linnaeus heeft bijvoorbeeld een classificatieschema gemaakt voor alle biologische wezens, waarbij "homo sapiens" een categoriewaarde vormt van de categorie "biologische soort".

Een classificatieschema bevat benoemde categorieën en per benoemde categorie de criteria waaraan iets moet voldoen om tot die categorie te behoren. Vaak beschrijft een classificatieschema ook de onderlinge relaties tussen de categorieën (bijvoorbeeld: de soort "homo sapiens" is onderdeel van de klasse "zoogdier", omdat de categorie "biologische soort" onderdeel is van de categorie "biologische klasse"). Dit verduidelijkt de betekenis van de categorieën en maakt het beter mogelijk om deze automatisch te verwerken (bijvoorbeeld om af te leiden dat elke mens ook een zoogdier is).

Bron: classificatieschema, [[NA]]

Gerelateerd: [categorische waarden](#categorische-waarden), [Categorie](#categorie)

Voorbeeld(en): De taxonomie van Linnaeus om alle biologische wezens te classificeren is een bekend voorbeeld van een classificatieschema.

### Classificatiesoort

> De classificaties kunnen worden ingedeeld in drie soorten:
- Gegevensclassificatie,
- Gegevenskenmerk,
- Verwerkingsbelang.

Toelichting: We verdelen de classificaties verder onder in drie soorten, om deze eenvoudiger te kunnen hanteren in documentatie en administratie. De gegevensclassificaties omvatten de BBN en BIV-classificaties. De verwerkingsbelangen omvatten het rubriceringsniveau (i.v.m. de relatie met te beschermen belangen), het verantwoordingsbelang, het vitaal belang en het continuïteitsbelang. De overige classificaties zijn ondergebracht bij de gegevenskenmerken.

Bron: Kerndepartement J&V [[KDJV]]

Voorbeeld(en): Gegevenskenmerk, Verwerkingsbelang, Gegevensclassificatie.

### Classificatiesoort: gegevensclassificatie

> Een gegevensclassificatie is een [classificatiesoort](#classificatiesoort) die iets zegt over de risico's die van toepassing zijn op gegevens en informatie.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Classificatiesoort](#classificatiesoort)

Voorbeeld(en): De gegevensclassificaties omvatten voor nu vooral de BBN en BIV-classificaties.

### Classificatiesoort: gegevenskenmerk

> Een gegevenskenmerk is een [classificatiesoort](#classificatiesoort) die iets zegt over de inhoud van gegevens en informatie.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Classificatiesoort](#classificatiesoort)

Voorbeeld(en): De gegevenskenmerken omvatten voor nu vooral de aanduidingen voor persoonsgegevens, politiegegevens, strafvorderlijke gegevens e.d.

### Classificatiesoort: verwerkingsbelang

> Een verwerkingsbelang is een [classificatiesoort](#classificatiesoort) die (voornamelijk of uitsluitend) van toepassing is op de omgang met de gegevens en informatie waarop de classificatie van toepassing is.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Classificatiesoort](#classificatiesoort)

Voorbeeld(en): De verwerkingsbelangen omvatten voor nu vooral het verantwoordingsbelang, vitaal belang, rubriceringsniveau en continuïteitsbelang

### Classificatietype

> Een classificatietype is een naam van een [classificatie](#classificatie) zoals beschreven in dit begrippenkader.

*Het classificatietype is noodzakelijk om de verschillende subtypes van classificaties van elkaar te onderscheiden in het informatiemodel.*

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Classificatie](#classificatie)

Voorbeeld(en): Classificatie Tenuitvoerleggingsgegevens, Classificatie AKI-gegevens, etc.

### Classificerend attribuuttype

> Een classificerend attribuuttype is een [attribuuttype](#attribuuttype) dat verwijst naar een [categorisch waardetype](#categorisch-waardetype).

Toelichting: Sommige kenmerken van een domeinobjecttype zijn letterlijk, maar er zijn ook kenmerken die verwijzen naar iets met een eigen betekenis, zoals "homo sapiens" of "man". In dat geval is niet de letterlijke waarde (de letters) belangrijk, maar de categorie waar die waarde naar verwijst. Daarom onderkennen we een categorische waarde.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Categorisch waardetype](#categorisch-waardetype), [Attribuuttype](#attribuuttype)

Voorbeeld(en): "Persoon.Biologische soort" is een classificerend attribuuttype.

### Complex Waardetype

> Een complex waardetype is een [waardetype](#waardetype) dat is opgebouwd uit meerdere onderliggende [waardetypen](#waardetype).

Toelichting: Een waardetype voor het gegevenstype "lengte" zal bestaan uit zowel een (letterlijk) waardetype voor het aantal, als een categorisch waardetype voor de maatvoering.

Gerelateerd: [Waardetype](#waardetype)

Voorbeeld(en): Complex waardetype "afstand" is opgebouwd uit letterlijk waardetype "aantal" en categorisch waardetype "maateenheid". Een complexe waarde voor waardetype "afstand" is bijvoorbeeld "10 kilometer".

### Complexe waarde

> Een complexe waarde is een [waarde](#waarde) die zelf is opgebouwd uit meerdere onderliggende [waarden](#waarde).

Toelichting: Een complexe waarde bestaat vaak uit een complexe tekenreeks, die meerdere waarden (mogelijk van verschillende soorten) bevat, zoals de combinatie van een letterlijke waarde en een categorische waarde: 100 meter, 37 graden Celsius, etc.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Waarde](#waarde)

Voorbeeld(en): Een waarde als "100 meter" is opgebouwd uit twee verschillende losse waarden: de letterlijke waarde "100" en de categorische waarde "meter", die verwijst naar de categorie van alle aanduidingen van afstanden.

### Conceptueel informatiemodel

Alternatieve aanduiding: *Conceptueel gegevensmodel*

> Een conceptueel informatiemodel beschrijft de informatie (data met betekenis en structuur) die een rol speelt in de werkelijkheid binnen het beschouwde domein. Het model is hierbij onafhankelijk van het ontwerp van (en de implementatie in) systemen. Het geeft een zo getrouw mogelijke beschrijving van die werkelijkheid en is in natuurlijke taal geformuleerd.

Toelichting: Een conceptueel informatiemodel richt zich specifiek op de semantiek van dingen en hun eigenschappen. Het definieert het ‘wat’: welke 'onderwerpen van gesprek' ('concepten', 'dingen’) worden onderscheiden in de beschouwde werkelijkheid, wat betekenen zij, hoe verhouden ze zich tot elkaar en welke informatie is daarvan relevant. Deze informatie wordt gemodelleerd als informatieobjecten met eigenschappen/kenmerken, oftewel waarover data beschikbaar is (of zal zijn) en wordt ondergebracht in een informatiemodel. Dit informatiemodel dient als taal waarmee domeinexperts kunnen communiceren met informatieanalisten en verschaft een eenduidige interpretatie van die werkelijkheid ten behoeve van deze communicatie.

Met conceptueel wordt niet bedoeld abstract of hoog over, de beschrijvingen van de informatie die beschikbaar is zijn heel precies en concreet. 

Indien het begrippenkader apart wordt opgenomen, is het conceptueel informatiemodel verbonden met de beschreven begrippen en geeft het duiding aan de onderlinge relaties van die begrippen.

Bron: conceptueel informatiemodel, [[MIM]]

### Conceptueel informatiemodelelement

> Een conceptueel informatiemodelelement is een [benoemd conceptueel modelelement](#benoemd-conceptueel-modelelement) dat een onderdeel is van een [conceptueel informatiemodel](#conceptueel-informatiemodel).

Toelichting: De conceptuele modelelementen worden apart benoemd om aan te geven welke onderdelen een conceptueel informatiemodel minimaal heeft. Voor een volledig overzicht van de mogelijke modelelementen in een conceptueel model is aan te raden de MIM-standaard te lezen.

Bron: MIM - Metamodel Informatie Modellering v1.2 (juni 2024) [[MIM]], Kerndepartement J&V [[KDJV]]

Gerelateerd: [Conceptueel informatiemodel](#conceptueel-informatiemodel), [Benoemd conceptueel modelelement](#benoemd-conceptueel-modelelement)

### Conceptueel model

> Een specificatie van de [gegevenstypegroepen](#gegevenstypegroep), [gegevenstypen](#gegevenstype) en hun onderlinge relaties binnen een [beschouwingsdomein](#beschouwingsdomein), onafhankelijk van zowel technische implementatie als specifieke gebruiksscenario’s.

Toelichting: Het conceptueel model richt zich op het creëren van een gedeelde, abstracte weergave van de werkelijkheid, bedoeld als communicatiemiddel tussen betrokkenen en als uitgangspunt voor het uitwerken van zowel logische als technische modellen. Het conceptuele model is vooral gericht op het modelleren van de informatie die door de gegevens wordt gedragen en dus feitelijk meer een informatiemodel dan een gegevensmodel.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Beschouwingsdomein](#beschouwingsdomein), [Gegevenstype](#gegevenstype), [Gegevenstypegroep](#gegevenstypegroep)

### Concreet Attribuuttype

> Een concreet attribuuttype is een aan een [domeinobjecttype](#domeinobjecttype)geattribueerde (toegekende) [eigenschap](#eigenschap).

Toelichting: Een concreet attribuuttype kan alleen letterlijke waarden bevatten, omdat het gaat om intrinsieke eigenschappen van een domeinobjecttype die niet verwijzen naar een categorie of ander domeinobject.

Gerelateerd: [Domeinobjecttype](#domeinobjecttype), [Eigenschap](#eigenschap)

### Conditie op attribuuttype

> Een conditie op een [attribuuttype](#attribuuttype) is een beperking die we opleggen aan de mogelijke invulling van de [waarde](#waarde) die dat [attribuuttype](#attribuuttype) kan aannemen.

Toelichting: Meestal worden de waarden op een attribuuttype beperkt tot bijvoorbeeld datums, of tekenreeksen van een bepaalde lengte. Complexere condities dan diegene die in een standaard database worden ondersteund zijn ook mogelijk in een conceptueel informatiemodel.

Bron: MIM - Metamodel Informatie Modellering v1.2 (juni 2024) [[MIM]], Kerndepartement J&V [[KDJV]]

Gerelateerd: [Attribuuttype](#attribuuttype), [Waarde](#waarde)

Voorbeeld(en): De cardinaliteit van Persoon.geboortedatum is minimaal 1 en maximaal 1.

Persoon.geboortedatum bestaat uit een geldige datum.

Postcode.postcode_numeriek moet precies 4 cijfers bevatten.

### Data Steward

> Data Steward is een rol binnen gegevensmanagement.

Toelichting: Een Data Steward is verantwoordelijk voor het beheer en de kwaliteit van gegevens binnen een specifieke domein of afdeling van een JenV-organisatie. Deze rol omvat het waarborgen van de nauwkeurigheid, consistentie, en integriteit van gegevens, het implementeren van gegevensmanagement richtlijnen, en het oplossen van gegevens gerelateerde issues.

Bron: JAGA Gegevenskwaliteitsbeleid [[Gegevenskwaliteitsbeleid]], JAGA Handreiking Organisatieinrichting Gegevensmanagement [[JAGA_OIGM]]

### Datatype

> Een datatype is een beschrijving van de structuur waar een waarde, oftewel de data zelf, aan moet voldoen.

Deze structuur wordt toegekend aan een [waardegegevenstype](#waardegegevenstype), waarbij we daarmee vooral kijken naar de eisen die we opleggen aan die waarden.

Toelichting: Een datatype is bedoeld om beperkingen op te leggen aan de mogelijke waarden in een waardegegevenstype, en het gebruik daarvan. 

Het datatype wordt gebruikt als type van een gegevenstype. Datatypen zijn veelal op vele plekken (her)bruikbaar en kunnen daarom gespecificeerd worden bij diverse gegevenstypen.

Bron: MIM - Metamodel Informatie Modellering v1.2 (juni 2024) [[MIM]], Kerndepartement J&V [[KDJV]]

Gerelateerd: [Waardegegevenstype](#waardegegevenstype)

Voorbeeld(en): Het datatype "geheel getal (integer)" mag alleen gehele getallen bevatten waarmee ook kan worden gerekend. Het datatype "tekenreeks (string)" geeft aan dat met de inhoud niet kan worden gerekend, ook niet als de inhoud uit getallen bestaat.

### Domeinobject

Alternatieve aanduiding: *Object*

> Een domeinobject is een onderscheidbaar iets in het beschouwde domein.

Toelichting: Met 'iets in het beschouwde domein' wordt bedoeld dat het om een onderwerpvan gesprek (een ding, een iets) gaat binnen een discipline of beschouwingsdomein. Een domeinobject is daarbij niet altijd fysiek, het kunnen ook digitale, virtuele en conceptuele dingen zijn zoals kadastrale percelen, (maatschappelijke) activiteiten en processen. Hoe een 'onderscheidbaar iets' als een domeinobject beschouwd wordt, hangt af van het beschouwingsdomein waarvoor het relevant is. Zo wordt de gebouwde omgeving in het ene domein beschouwd als een verzameling gebouwen terwijl een ander domein daarin panden onderscheidt. Een domeinobject is voor een domein relevant als eigenschappen (kenmerken) daarvan van belang zijn voor het functioneren van dat domein.

Een domeinobject wordt ook wel een exemplaar of instantie van een domeinobjecttype genoemd (vele soortgelijke exemplaren samen zijn getypeerd naar een domeinobjecttype).

*Een domeinobject is geen modelelement in een conceptueel informatiemodel. Een domeinobjecttype is wel een modelelement in een conceptueel informatiemodel.*

Bron: MIM - Metamodel Informatie Modellering v1.2 (juni 2024) [[MIM]]

### Domeinobject in een Rol in een relatie

> Een Domeinobject in een Rol in een relatie definieert een relatie tussen een specifiek [domeinobject](#domeinobject) die onderdeel is van een [domeinrelatie](#domeinrelatie), en de [rol](#rol) van dat domeinobject in die domeinrelatie. Dit geheel is één onderdeel van een relatie.

Toelichting: Een domeinobject in een relatie komt altijd voor in een bepaalde rol in die relatie. Een relatie wordt gevormd tussen minimaal twee domeinobjecten, elk in een eigen rol.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Domeinrelatie](#domeinrelatie), [Domeinobject](#domeinobject), [Rol](#rol)

Voorbeeld(en): Domeinobject Joop vervult de rol van Medewerker in de relatie "arbeidsrelatie met MinJenV van januari 2025 tot december 2025".

### Domeinobjectlevensduur

> Een domeinobjectlevensduur is de levensduur waarin een domeinobject bestaat in het domein, aangeduid door een beginmoment en eindmoment (indien bekend).

Toelichting: Een domeinobject heeft altijd een eindige levensduur, ook al is dat soms erg lang. De levensduur van de concepten in het beschouwingsdomein zijn vaak relevant om vast te leggen, ook (of juist) als dat nog niet wordt onderkend.

Bron: Kerndepartement J&V [[KDJV]]

Voorbeeld(en): Snuifje bestaat in het beschouwingsdomein "huisdieren" van 1 september 1987 tot 1 september 1997. Joop bestaat in het beschouwingsdomein "werkelijke wereld" sinds 1-1-2000.

### Domeinobjectrelatielevensduur

> Een domeinobjectrelatielevensduur is de levensduur waarin een domeinobjectrelatie bestaat in het domein, aangeduid door een beginmoment en eindmoment (indien bekend).

Bron: Kerndepartement J&V [[KDJV]]

Voorbeeld(en): Op 2-2-2002 ontstond er een familierechtelijke verbintenis tussen Koning Willem Alexander en Máxima Zorreguita Cerruti.

### Domeinobjecttype

Alternatieve aanduiding: *Objecttype*

> Een domeinobjecttype is een typering van gelijksoortige [domeinobjecten](#domeinobject). Het is de typering van een groep [domeinobjecten](#domeinobject) in de werkelijkheid die binnen een [beschouwingsdomein](#beschouwingsdomein) relevant zijn en als gelijksoortig worden beschouwd.

Toelichting: In het gegevenstyperingsbeleid beschouwen we tastbare zaken als objecten. ‘Tastbaar’ moet hierbij ruim geïnterpreteerd worden. Het gaat niet alleen om fysiek herkenbare domeinobjecten zoals auto’s, gebouwen of personen, maar ook om zogenaamde virtuele domeinobjecten waarover binnen het domein door betrokkenen gecommuniceerd wordt zoals kadastrale percelen, (maatschappelijke) activiteiten, processen en niet-natuurlijke personen. Hoe een ‘tastbaar iets’ als een domeinobject beschouwd wordt, hangt af van het domein waarvoor dat ‘tastbaar iets’ relevant is, het beschouwingsdomein. Zo wordt de gebouwde omgeving in het ene domein beschouwd als een verzameling gebouwen terwijl een ander domein daarin panden onderscheidt. Een domeinobject is voor een domein relevant als eigenschappen (kenmerken) daarvan van belang zijn voor het functioneren van dat domein.

Bron: MIM - Metamodel Informatie Modellering v1.2 (juni 2024) [[MIM]]

Gerelateerd: [Beschouwingsdomein](#beschouwingsdomein), [Domeinobject](#domeinobject)

Voorbeeld(en): Als Marco en Ronald domeinobjecten zijn, dan is een mogelijke domeinobjecttypering die van een natuurlijk persoon. Afhankelijk van het beschouwingsdomein is medewerker, verdachte of slachtoffer ook allemaal een optie. De keuze is afhankelijk van wat er precies door wie wordt beschouwd, en dat wordt weer bepaald door de keuze van het beschouwingsdomein.

### Domeinrelatie

Alternatieve aanduiding: *Relatie*

> Een domeinrelatie is een benoemde verbinding (relatie) tussen twee of meer [domeinobjecten](#domeinobject), elk in een eigen [rol](#rol) in die relatie.

Toelichting: Veel relaties bestaan uit twee domeinobjecten in een bepaalde rol, maar er kunnen in principe oneindig veel domeinobjecten meedoen in een relatie. De meest voorkomende relaties zijn binair, een klein percentage is ternair en de rest bestaat uit domeinrelaties met wisselende cardinaliteit.

We benoemen de relaties om er over te kunnen praten en te kunnen aanwijzen in welke relatie de domeinobjecten precies meedoen. Indien we eigenschappen aan de relatie willen toekennen, wordt de domeinrelatie verzelfstandigt in een eigen relatiedomeinobject. Zo kan een domeinrelatie tussen domeinobject Joop en domeinobject Politie worden verzelfstandigt in een arbeidscontract ACPOL202501012223, waar ook weer eigenschappen aan kunnen worden toegekend en wat een eigen levensduur kan hebben.

*Merk op dat de typering van de rol en de instantie van de rol in een roltype soms lastig te onderscheiden zijn, met name als niet heel strikt wordt gelet op het onderscheid tussen de geconstateerde werkelijke feiten (Joop is modelleur 1e klasse bij de Politie) versus een uitspraak waarin eigenlijk al is getypeerd (Joop is medewerker van de Politie).*

Bron: MIM - Metamodel Informatie Modellering v1.2 (juni 2024) [[MIM]], Kerndepartement J&V [[KDJV]]

Gerelateerd: [Domeinobject](#domeinobject), [Rol](#rol)

Voorbeeld(en): De relatie "arbeidsrelatie van Joop met MinJenV van 1-1-2024 t/m 1-1-2025" relateert een domeinobject Joop in de rol van medewerker, met een domeinobject Ministerie van Justitie en Veiligheid in de rol van werkgever, voor een bepaalde levensduur van die relatie.

### Domeinrelatietype

Alternatieve aanduiding: *Relatiesoort; Relatietype*

> Een domeinrelatietype is een typering van het structurele verband tussen een object van een [domeinobjecttype](#domeinobjecttype) en één of meer andere objecten van andere (of dezelfde) [domeinobjecttypen](#domeinobjecttype).

Een domeinrelatietype bestaat uit minimaal twee [domeinrelatieverbintenissen](#domeinrelatieverbintenis) en heeft geen eigen [kenmerken](#kenmerk).

Toelichting: Als Marco en Ronald collega's zijn, en Erik en Mohammed ook, dan zijn er meerdere gelijksoortige relaties. Deze kunnen we typeren onder de typenaam "collega".

Een domeinrelatietype waarover we eigen kenmerken willen vastleggen, wordt een relatiedomeinobjecttype.

*In MIM 1.2 heet dit nog relatiesoort, in MIM 2.0 zal de naam wijzigen naar relatietype.*

Bron: Kerndepartement J&V [[KDJV]], MIM - Metamodel Informatie Modellering v1.2 (juni 2024) [[MIM]]

Gerelateerd: [Domeinrelatieverbintenis](#domeinrelatieverbintenis), [Kenmerk](#kenmerk), [Domeinobjecttype](#domeinobjecttype)

Voorbeeld(en): "Huwelijk", "vriendschap", "studeert aan", "is eigenaar" zijn voorbeelden van mogelijke domeinrelatietypen.

### Domeinrelatieverbintenis

> Een domeinrelatieverbintenis wordt gevormd door een [domeinobjecttype](#domeinobjecttype) in een [roltype]() op een [domeinrelatietype](#domeinrelatietype). Een domeinrelatieverbintenis heeft zowel een [minimale cardinaliteit](#minimale-cardinaliteit) als een [maximale cardinaliteit](#maximale-cardinaliteit).

Toelichting: Een domeinrelatieverbintenis op een domeinrelatietype geeft aan dat een bepaald domeinobjecttype in een bepaalde rol meedoet op dat domeinrelatietype, met een bepaalde cardinaliteit. Een domeinrelatietype moet minimaal twee domeinrelatieverbintenissen omvatten.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [roltype](#roltype), [Minimale cardinaliteit](#minimale-cardinaliteit), [Domeinobjecttype](#domeinobjecttype), [Domeinrelatietype](#domeinrelatietype), [Maximale cardinaliteit](#maximale-cardinaliteit)

Voorbeeld(en): Op het domeinrelatietype "collega" doet domeinobjecttype "medewerker" mee in de rol "eerste collega" met cardinaliteit van 1 t/m N. Domeinobjecttype "medewerker" doet ook mee op hetzelfde domeinrelatietype met de rol "tweede collega" met opnieuw een cardinaliteit van minimaal 1 en maximaal N. Een eerste collega heeft in dit voorbeeld dus altijd minimaal een andere collega, en mogelijk zijn alle medewerkers in het bedrijf collega's van elkaar.

### Eigenschap

> Een eigenschap is een bepaalde kwaliteit waarmee een [domeinobject](#domeinobject) kan worden gekarakteriseerd en die ook voorkomt op concrete domeinobjecten. Een eigenschap is een [inherent kenmerk](#inherent-kenmerk) van een [domeinobject](#domeinobject).

Toelichting: We onderscheiden eigenschappen van categorische kenmerken en rollen, omdat een eigenschap een waardetype met letterlijke waarden heeft, terwijl de andere soorten kenmerken vooral verwijzen naar domeinobjecttypen en categorieën.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Domeinobject](#domeinobject), [Inherent kenmerk](#inherent-kenmerk)

Voorbeeld(en): Roodheid is een eigenschap van een domeinobject , bijvoorbeeld een specifieke brandweerauto met nummerbord "11-VUUR-11".

### Elementair gegeven

Alternatieve aanduiding: *Uitspraak*

> Een elementair gegeven is een [vastgelegde uitspraak](#vastgelegde-uitspraak) over hetzij een [getypeerde eigenschap](#getypeerde-eigenschap) van een [domeinobject](#domeinobject) dan wel een getypeerde relatie tussen [domeinobjecten](#domeinobject).

Toelichting: Kenmerkend aan een elementair gegeven zijn dan ook de volgende eigenschappen:

* Het is vastgelegd (in steen, papier, digitaal);
* Het is een uitspraak (gedaan door iemand, gemeten door een sensor, etc);
* Het gaat over een eigenschap van een object (of relatie daartussen), met andere woorden: gegevens gaan over iets anders.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Getypeerde eigenschap](#getypeerde-eigenschap), [Domeinobject](#domeinobject), [Vastgelegde uitspraak](#vastgelegde-uitspraak)

Voorbeeld(en): Joop is geboren op 12 januari 1950. Ronald heeft blauwe ogen. Ronald is de collega van Mohammed.

### Entity-Relationship Modeling

> Een entiteit-relatiemodel (of ER-model) beschrijft onderling gerelateerde zaken die van belang zijn binnen een specifiek kennisdomein.

Toelichting: Een basis ER-model bestaat uit entiteitstypen (die de zaken van belang classificeren) en specificeert de relaties die tussen entiteiten (instanties van die entiteitstypen) kunnen bestaan.

Bron: ERM (Wikipedia) [[WikipediaERM]], JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

### Fact-based Modeling

> Fact-Based Modelling is een type conceptuele modellering waarbij de belangrijkste datastructuur, het facttype, over feiten werkt.

Toelichting: Er zijn typen Fact-Based Modelling die van nature grafisch zijn en anderen die tekstgebaseerd zijn.

Grafische Fact-Based Modelling-methodologieën omvatten Object-Role Modeling (ORM), Fully Communication Oriented Information Modeling (FCO-IM) en CogNIAM. Tekstgebaseerde Fact-Based Modelling omvat de Constellation Query Language.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]], Fact Based Modeling (Medium) [[MediumFBM]]

### Feit over categorisch kenmerk van domeinobject

> Een feit over een [categorisch kenmerk](#categorisch-kenmerk) van een domeinobject is een toekenning van een specifieke [categorie](#categorie) met een specifieke aanduiding of naam aan een specifiek [domeinobject](#domeinobject).

Toelichting: Een categorisch kenmerk met toegekende categorie voor een specifiek domeinobject zegt iets over de specifieke categorie waar een aangewezen domeinobject toe behoort. Iets is pas een feit als alle drie de onderdelen (categorie, categorisch kenmerk en domeinobject) bekend zijn.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Categorie](#categorie), [Categorisch kenmerk](#categorisch-kenmerk), [Domeinobject](#domeinobject)

Voorbeeld(en): Het categorisch kenmerk genaamd "biologische soort" van het domeinobject aangeduid als Ronald heeft de categorische waarde "homo sapiens".

### Feit over eigenschap van domeinobject

> Een feit over een [eigenschap](#eigenschap) van een domeinobject is een toekenning van een specifieke [waarde](#waarde) met een specifieke aanduiding of naam aan een specifiek [domeinobject](#domeinobject).

Toelichting: Een eigenschap met toegekende (letterlijke) waarde voor een specifiek domeinobject zegt iets over de letterlijke waarde van een eigenschap van een aangewezen domeinobject. Iets is pas een feit als alle drie de onderdelen (waarde, eigenschap en domeinobject) bekend zijn.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Waarde](#waarde), [Eigenschap](#eigenschap), [Domeinobject](#domeinobject)

Voorbeeld(en): De eigenschap genaamd lengte van het domeinobject aangeduid als Ronald heeft de letterlijke waarde "180 centimeter".

### Gegevensbeleid

> Gegevensbeleid omvat het vaststellen van duidelijke richtlijnen en procedures voor het verzamelen, opslaan, verwerken en delen van gegevens, evenals het implementeren van technologische oplossingen en controles om o.a. de nauwkeurigheid, consistentie en integriteit van de gegevens te waarborgen.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Voorbeeld(en): Gegevenstyperingsbeleid, gegevenskwaliteitsbeleid en gegevensdelingsbeleid zijn voorbeelden van gegevensbeleid.

### Gegevenskwaliteit Rol

> De gegevenskwaliteit rol is een rol die een [persoon](#persoon) kan hebben in het [gegevenskwaliteitsproces](#gegevenskwaliteitsproces).

Toelichting: De volgende rollen zijn gegevenskwaliteitsrollen:

* gegevensverantwoordelijke
* gegevensmodelleur
* gegevensmanager
* gegevenskwaliteitscontroleur
* data steward

Deze rollen worden verder uitgewerkt in het gegevenskwaliteitsbeleid.

Bron: JAGA Gegevenskwaliteitsbeleid [[Gegevenskwaliteitsbeleid]]

Gerelateerd: [Gegevenskwaliteitsproces](#gegevenskwaliteitsproces), [Persoon](#persoon)

### Gegevenskwaliteitscontroleur

> Gegevenskwaliteitscontroleur is een rol binnen gegevensmanagement.

Toelichting: Een gegevenskwaliteitscontroleur heeft als primair doel het monitoren, analyseren en verbeteren van de algehele kwaliteit van gegevens binnen een JenV-organisatie over gegevensgebieden heen. 

De gegevenskwaliteitscontroleur is verantwoordelijk voor de gegevenskwaliteitsmetingen, dus zowel de definitie, de uitvoering van en de rapportage over de metingen. De gegevenskwaliteitscontroleur is verantwoordelijk voor het opstellen van de gegevenskwaliteitsrapporten over die metingen. Deze rapporten worden beschikbaar gesteld aan de data stewards, gegevensmanagers en gegevensverantwoordelijken.

Bron: JAGA Handreiking Organisatieinrichting Gegevensmanagement [[JAGA_OIGM]], JAGA Gegevenskwaliteitsbeleid [[Gegevenskwaliteitsbeleid]]

### Gegevenskwaliteitsproces

> Een proces waarin de kwaliteit van de [gegevenstypering](#gegevenstypering) wordt gemeten en zo nodig verbeterd. De [gegevenstypering](#gegevenstypering) wordt gevalideerd op juistheid door kennishouders en geverifieerd op consistentie door een afzonderlijke kwaliteitsbewaker.

Toelichting: Omdat het gebruik van gegevens voortdurend verandert en evolueert is voortdurende monitoring (en mogelijk aanpassing) nodig. Daarom wordt daarvoor een proces ingericht. Dit impliceert dat er medewerkers zijn, die toegewijd zijn aan de gegevenstypering. 

De juiste (waar mogelijk geautomatiseerde) technieken kunnen worden ingezet om de gegevenstypering actueel, betrouwbaar en consistent te houden met het daadwerkelijke gegevensgebruik.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Gegevenstypering](#gegevenstypering)

### Gegevensmanager

> Gegevensmanager is een rol binnen gegevensmanagement. De gegevensmanager werkt samen met de [data steward](#data-steward)s en de [gegevensverantwoordelijke](#gegevensverantwoordelijke) om de kwaliteit van een verwerkingsdomein te borgen.

Toelichting: De persoon met de rol van gegevensmanager is verantwoordelijk voor de inhoudelijke aansturing van de data stewards op een bepaald verwerkingsdomein en daarmee verantwoordelijk voor de gegevenskwaliteit van de gegevens in een verwerkingsdomein onder aansturing van een gegevensverantwoordelijke.

Bron: JAGA Gegevenskwaliteitsbeleid [[Gegevenskwaliteitsbeleid]], JAGA Handreiking Organisatieinrichting Gegevensmanagement [[JAGA_OIGM]]

Gerelateerd: [Gegevensverantwoordelijke](#gegevensverantwoordelijke), [Data Steward](#data-steward)

### Gegevensmodelleur

> Gegevensmodelleur is een rol binnen gegevensmanagement en samen met de [gegevensverantwoordelijke](#gegevensverantwoordelijke) een noodzakelijke rol om de gegevenstypering uit te kunnen voeren.

Toelichting: De functionaris met de rol van gegevensmodelleur is verantwoordelijk voor de borging van het begrip van het beschouwingsdomein in formele begrippenkaders, de gegevenstypering van de gegevenssets in het verwerkingsdomein, en de koppeling tussen de begrippen van het beschouwingsdomein en de gegevenstypering in het verwerkingsdomein.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Gegevensverantwoordelijke](#gegevensverantwoordelijke)

### Gegevensobject

> Een gegevensobject is de kleinste groep van [elementaire gegevens](#elementair-gegeven) die als enkelvoudige eenheid wordt verwerkt.

Toelichting: Een gegevensobject kan niet verder worden gesplitst in kleinere objecten zonder de betekenis van het gegevensobject te verliezen. Vaak zal een gegevensobject elementaire gegevens groeperen die gaan over hetzelfde object, bijvoorbeeld de persoonsgegevens van John Doe: gegevens over de persoon John Doe.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Elementair gegeven](#elementair-gegeven)

Voorbeeld(en): Persoonsgegevens of adresgegevens van een enkel persoon (object).

### Gegevensobjecttype

> Een gegevensobjecttype is een typering van een groep gelijksoortige [gegevensobjecten]().

Toelichting: Als we iets over een gegevensobject willen zeggen, moeten we dat gegevensobject eerst beschrijven. Dat wil zeggen, we typeren het gegevensobject in een gegevensobjecttype en beschrijven alle kenmerken die een instantie van dat type kan hebben.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [gegevensobjecten](#gegevensobjecten)

Voorbeeld(en): Het gegevensobjecttype "Persoon" bevat de gemeenschappelijke kenmerken van alle gegevensobjecten in een gegevensset die gegevens over een Persoon bevatten.

### Gegevensobjecttype met domeinobjecttype als hoofdonderwerp

Alternatieve aanduiding: *Relatiegegevensobjecttype*

> Een gegevensobjecttype met domeinobjecttype als hoofdonderwerp is een [gegevensobjecttype](#gegevensobjecttype) dat de [gegevenstypen](#gegevenstype) omvat die een [domeinobjecttype](#domeinobjecttype) als hoofdonderwerp hebben.

*Voor deze specialisatie van gegevensobjecttype is gekozen om aan te kunnen geven dat een relatiegegevenstype alleen verwijst naar dit gegevensobjecttype en niet naar een gegevensobjecttype wat als hoofdonderwerp een domeinrelatietype heeft, want die heeft zelf kenmerken heeft en daarover kunnen we dus geen gegevens vastleggen.*

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Gegevensobjecttype](#gegevensobjecttype), [Gegevenstype](#gegevenstype), [Domeinobjecttype](#domeinobjecttype)

### Gegevensobjecttype met domeinrelatietype als hoofdonderwerp

Alternatieve aanduiding: *Domeinobjectgegevensobjecttype*

> Een gegevensobjecttype met domeinrelatietype als hoofdonderwerp is een [gegevensobjecttype](#gegevensobjecttype) dat de [gegevenstypen](#gegevenstype) omvat die een [relatiedomeinobjecttype](#relatiedomeinobjecttype) als hoofdonderwerp hebben.

*Voor deze specialisatie van gegevensobjecttype is gekozen om aan te kunnen geven dat we naar gegevensobjecttypen die bijvoorbeeld een N:N-relatie uitdrukken, niet zomaar kunnen verwijzen met een relatiegegevenstype. Als we willen verwijzen moeten we het domeinrelatietype eerst verzelfstandigen in een nieuw relatiedomeinobjecttype, en deze kunnen we dan zien als een domeinobjecttype dat het hoofdonderwerp vormt van een gegevensobjecttype.*

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Gegevenstype](#gegevenstype), [Gegevensobjecttype](#gegevensobjecttype), [Relatiedomeinobjecttype](#relatiedomeinobjecttype)

### Gegevensopslag

> Een gegevensopslag is de plek waar een specifieke [gegevensset](#gegevensset) in principe wordt vastgelegd.

Toelichting: Het gaat hier niet om het gegevensmiddel (bestand, CSV, etc.) maar om de locatie waar de gegevensset fysiek danwel electronisch kan worden teruggevonden. Bij voorkeur is er op elk moment maar één locatie voor een specifieke gegevensset.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Gegevensset](#gegevensset)

Voorbeeld(en): Gegevensset KDF1002.XML is primair opgeslagen in C:\Public\Datadumps\20240101.

### Gegevensset

Alternatieve aanduiding: *Gegevensverzameling; dataset*

> Een gegevensset is een verzameling samenhangende gegevens die beheerd wordt door één organisatie en toegankelijk is via een daarvoor ingerichte voorziening.

Toelichting: Een geldige gegevensset of gegevensverzameling heeft goed omschreven grenzen. Een gegevensset kan zelf ook weer bestaan uit andere gegevenssets, of opgaan in een grotere gegevensset. Er kunnen dus relaties bestaan tussen gegevenssets.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

### Gegevenssetspecificatie

> Een gegevenssetspecificatie is een specificatie van een [gegevensset](#gegevensset) die zowel de gegevenstypering in de vorm van een [logisch gegevensmodel](#logisch-gegevensmodel) omvat, als een populatiebeschrijving voor de inhoud van de gegevenssets die voldoen aan de specificatie.

Toelichting: Een logisch model kan een gegevensset niet volledig specificeren, omdat twee sets aan hetzelfde model kunnen voldoen maar toch een hele andere lading krijgen door de gegevens in die gegevensset. Daarom wordt een beschrijving van de populatie toegevoegd om de gegevensset volledig te specificeren. Een gegevensset met een inhoud die aanleiding geeft tot andere classificaties, autorisaties of risico-analyses dan andere gegevenssets met hetzelfde logische gegevensmodel zal op basis daarvan een andere gegevensspecificatie krijgen.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Gegevensset](#gegevensset), [Logisch gegevensmodel](#logisch-gegevensmodel)

Voorbeeld(en): Een lijst van persoonsgegevens van de klaverjasclub heeft niet dezelfde lading qua risico's en te nemen maatregelen voor de bescherming van die gegevens, als een lijst van verdachten van zware criminaliteit.

### Gegevenssetspecificatie voor Gegevensverwerkingstype

> Een [gegevenssetspecificatie](#gegevenssetspecificatie) voor een [gegevensverwerkingstype](#gegevensverwerkingstype) is een [gegevenssetspecificatie](#gegevenssetspecificatie) die aangeeft welke [gegevenstypen](#gegevenstype) actief zijn betrokken bij een bepaald [gegevensverwerkingstype](#gegevensverwerkingstype).

Toelichting: We willen de kwaliteit bewaken van de gegevenssets die worden verwerkt, en om die kwaliteit te kunnen beheersen moeten we weten welke gegevenssets en gegevenstypen in welke gegevensverwerkingstypen worden gebruikt. Vervolgens kunnen we dan het gegevenskwaliteitsbeleid volgen voor die gegevenstypen.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Gegevensverwerkingstype](#gegevensverwerkingstype), [Gegevenssetspecificatie](#gegevenssetspecificatie), [Gegevenstype](#gegevenstype)

### Gegevenstype

> Een gegevenstype is een typering van gelijksoortige [elementaire gegevens](#elementair-gegeven) die voor een [domeinobject](#domeinobject) van toepassing zijn.

Toelichting: Hiermee bedoelen we dat we elk gelijksoortig elementair gegeven dat voor een object van toepassing is, op dezelfde manier beschouwen en benoemen. 

Er kan sprake zijn van gelijksoortige gegevens, als deze gegevens over dezelfde eigenschap van gelijksoortige domeinobjecten gaat, bijvoorbeeld bij gegevenstypen die gaan over de eigenschap geboortedatum van een objecttype persoon. Er is sprake van een ander gegevenstype, als de eigenschap verschilt, of als het over een ander objecttype gaat.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Elementair gegeven](#elementair-gegeven), [Domeinobject](#domeinobject)

Voorbeeld(en): In de uitspraak "Marco is een persoon" en de uitspraak "Ronald is een persoon" zit een gelijksoortig gegeven, namelijk de voornaam van een object met objecttype persoon. Dat is dus het gegevenstype.

### Gegevenstypegroep

> Een gegevenstypegroep is een groepering van één of meer [gegevenstypen](#gegevenstype).

Toelichting: Gegevenstypen zelf kun je groeperen. Bijvoorbeeld als je het wilt hebben over alle gegevenstypen die "geheim" zijn. Het is nu niet dat we deze gegevens als groep bij elkaar willen zetten, om ze vervolgens (als groep) te typeren. In dit geval willen we juist de gegevenstypen zelf groeperen.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Gegevenstype](#gegevenstype)

### Gegevenstypering

> Een gestructureerde en herhaalbare aanpak om te komen tot een beschrijving van de betekenis van gegevens.

Toelichting: In deze definitie verstaan we onder de betekenis van gegevens de volgende drie-eenheid:

* De normatieve betekenis, zoals deze volgt uit wet- en regelgeving, uitvoeringsbeleid en andere normatieve kaderstelling.
* De intrinsieke betekenis, zoals deze volgt uit de aard van de gegevens zelf (vorm, structuur, relatie met ander gegevens).
* De pragmatische betekenis, zoals deze volgt uit het gebruik van de gegevens en de impact die dit gebruik met zich meebrengt.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

### Gegevenstyperingsbeleid

> Gegevenstyperingsbeleid is [gegevensbeleid](#gegevensbeleid), gericht op het geven van regels voor de [gegevenstypering](#gegevenstypering), waarmee JenV-organisaties kunnen borgen dat de gegevens die zij verwerken de beoogde betekenis hebben, met als uiteindelijk doel het waarborgen van de veiligheid, rechten en welzijn van burgers.

Toelichting: We geven in het gegevenstyperingsbeleid dus de regels voor de gegevenstypering.

*Gegevenstypering binnen een organisatie kan niet losgezien worden van de manier waarop een organisatie is ingebed in zowel de horizontale samenwerking (tussen organisaties tijdens de uitvoering) als verticale samenwerking (tussen beleid en uitvoering).

Daarom moeten tussen organisaties nadere afspraken worden gemaakt over hoe de gegevenstypering wordt ingevuld en hoe daarbij multidisciplinair wordt samengewerkt.*

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Gegevenstypering](#gegevenstypering), [Gegevensbeleid](#gegevensbeleid)

### Gegevensverantwoordelijke

> Een functionaris binnen een organisatie die de formele eindverantwoordelijkheid draagt voor de naleving van wet- en regelgeving evenals het beleid rond (en de toegankelijkheid, betekenis en kwaliteit van) een specifieke [gegevensset](#gegevensset).

Toelichting: Voor elke gegevensset wordt een gegevensverantwoordelijke benoemd die de formele eindverantwoordelijkheid draagt. Deze ziet toe op de toegankelijkheid, betekenis en kwaliteit van de gegevens binnen de gegevenssets waar deze voor verantwoordelijk is. In beginsel is de gegevensverantwoordelijke een rol en geen functie. De rol wordt doorgaans vervuld door een leidinggevende binnen het betreffende organisatieonderdeel.

Een functionaris is binnen de organisatie altijd een persoon, geen organisatieonderdeel. Daarbij kan de verantwoordelijkheid in formele stukken aan de titel van de functionaris gekoppeld zijn (bv: “afdelingshoofd ABC”), waaruit de feitelijke verantwoordelijke persoon volgt. Volgens uitgangspunt U6 zal de gegevensverantwoordelijke werkzaam zijn binnen het primaire proces van de organisatie.

De eindverantwoordelijke moet iemand zijn met het mandaat, de mensen en de middelen om het proces waar de gegevensset in wordt verwerkt ook te kunnen beheersen.

Bron: JAGA Gegevenskwaliteitsbeleid [[Gegevenskwaliteitsbeleid]], JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Gegevensset](#gegevensset)

### Gegevensverwerking

> Een gegevensverwerking is een bewerking of een geheel van bewerkingen met betrekking tot gegevens of een geheel van gegevens.

Toelichting: De bewerking of het geheel van bewerkingen wordt al dan niet uitgevoerd via geautomatiseerde procedés. Voorbeelden zijn het verzamelen, vastleggen, ordenen, structureren, opslaan, bijwerken of wijzigen, opvragen, raadplegen, gebruiken, verstrekken door middel van doorzending, verspreiden of op andere wijze ter beschikking stellen, aligneren of combineren, afschermen, wissen of vernietigen van gegevens.

*In de scope van het gegevenstyperingsbeleid bedoelen we hiermee een enkele verwerking, dus bijvoorbeeld het ontvangen van een enkel poststuk en het registreren van de afzender.*

Bron: 

### Gegevensverwerkingstype

> Een gegevensverwerkingstype is een groepering van gelijksoortige [gegevensverwerkingen](#gegevensverwerking).

Toelichting: Het verwerken van de adresgegevens van een enkele persoon is een gegevensverwerking. Als we iets willen zeggen over al die gegevensverwerkingen tegelijk, dan hebben we het over het gegevensverwerkingstype.

*In de scope van het gegevenstyperingsbeleid bedoelen we hiermee de hele reeks van gelijksoortige gegevensverwerkingen, dus bijvoorbeeld het ontvangen van poststukken en het registreren van de afzenders voor al die poststukken.*

Bron: 

Gerelateerd: [Gegevensverwerking](#gegevensverwerking)

Voorbeeld(en): Het verwerken van adresgegevens is een gegevensverwerkingstype. Het verwerken van de adresgegevens van R. Kunenborg is een enkele gegevensverwerking.

### Geldigheidstijd

Alternatieve aanduiding: *Objectgeldigheidstijd; Objectrelatie geldigheidstijd; valid time*

> Met de geldigheidstijd bedoelen we het tijdsinterval vanaf een startdatum waarop een [domeinobject](#domeinobject) of [domeinrelatie](#domeinrelatie) ontstaat in de werkelijke wereld, tot de einddatum waarop dat domeinobject of de domeinrelatie ophoud te bestaan.

Toelichting: Vrijwel elk domeinobject (of relatie tussen de domeinobjecten) in de werkelijke wereld heeft een levensduur. Deze noemen we de geldigheidstijd(slijn). Deze geldigheidstijd(slijn) wijkt af van de levensduur van de uitspraken over de eigenschappen van dat object, de registratietijd(slijn).

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Domeinrelatie](#domeinrelatie), [Domeinobject](#domeinobject)

### Gestructureerd datatype

> Een gestructureerd datatype is een specifiek benoemd datatype dat de structuur van een gegeven beschrijft, samengesteld uit minimaal twee elementen die in samenhang betekenisvol zijn.

Toelichting: De waarde van het attribuutsoort verkoopprijs met gestructureerd datatype bedrag is uitgedrukt in een combinatie van een som en valuta zoals 35 euro. De introductie van één datatype Bedrag, uitgedrukt in som en valuta, legt dus vast dat som en valuta onlosmakelijk met elkaar zijn verbonden. 

De eigenschappen in het Gestructureerd datatype tezamen zijn identificerend (een Gestructureerd datatype “identificeert zichzelf”, zoals er maar per definitie één '1 liter' bestaat, één '35 euro' en één datum '6 april 2017', met per definitie altijd dezelfde betekenis:

* Een blik olie heeft een inhoud van "7 liter", kost "35 euro", en is verkocht op "6 april 2017".
* Piet heeft "1 liter" bloed gedoneerd, daarvoor "35 euro" vergoeding gekregen, op "6 april 2017".

Het identificerend zijn geldt bijvoorbeeld niet voor Jan Jansen. Er zijn meerdere personen met deze naam en dat zijn verschillende personen.

Bron: MIM - Metamodel Informatie Modellering v1.2 (juni 2024) [[MIM]]

Voorbeeld(en): aantal en afstandsmaat, getal en litermaat, getal en valutacode

### Getypeerde eigenschap

> Een getypeerde eigenschap van een [domeinobject](#domeinobject) of [domeinrelatie](#domeinrelatie) is een eigenschap waaraan we een naam, betekenis en regels hebben toegekend.

Toelichting: Als we over een persoon een uitspraak doen als "Hannie heeft rood haar" dan is dat op zich nog geen typering. Als we vervolgens over alle personen uitspraken gaan doen over de haarkleur, dan kunnen we die uitspraken onder dezelfde noemer scharen, zodat we daar betekenis aan kunnen gaan hechten, en regels voor op kunnen stellen. Wat bedoelen we met "haarkleur" en welke haarkleuren vinden we handig om te weten? Is "lichtgeel met blauwe stipjes" een geldige haarkleur? Het beschrijven van die regels en betekenis en dat onder één noemer brengen, is het typeren.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Domeinobject](#domeinobject), [Domeinrelatie](#domeinrelatie)

### Herleidbaarheid intrinsieke betekenis

> De herleidbaarheid van de [intrinsieke betekenis](#intrinsieke-betekenis) van gegevens wordt geborgd door de verwijzing naar de [normatieve betekenis](#normatieve-betekenis) en de [praktische betekenis]() van de gegevens, en een correcte [gegevensmodellering]().

Toelichting: In principe is de intrinsieke betekenis van gegevens afleidbaar uit de typering van de gegevens zelf, maar als we willen herleiden waarom die betekenis en bijbehorende typering op deze manier tot stand is gekomen, is een relatie met de normatieve en praktische betekenis noodzakelijk.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [gegevensmodellering](#gegevensmodellering), [Normatieve betekenis](#normatieve-betekenis), [praktische betekenis](#praktische-betekenis), [Intrinsieke betekenis](#intrinsieke-betekenis)

### Herleidbaarheid normatieve betekenis

> De herleidbaarheid van de [normatieve betekenis](#normatieve-betekenis) van gegevens wordt geborgd met een verwijzing naar de relevante [wet- en regelgeving](#wet-en-regelgeving) waarin die betekenis wordt beschreven, d.w.z. het specifieke [informatieobject](#informatieobject) waarin dat staat.

Toelichting: Het gaat dus om een verwijzing naar de tekst van de wet- of regelgeving waarin de normatieve betekenis wordt beschreven, in de vorm van een document, website of andere vorm met eigen identiteit waarnaar kan worden verwezen. Zolang deze tekst op zichzelf eenvoudig te vinden is, is het noemen van de wet, het artikel, het lid en het subnummer in principe afdoende. Zo niet, dan moet er ook naar de representatie worden verwezen, bijvoorbeeld de website of bijlage.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Informatieobject](#informatieobject), [Normatieve betekenis](#normatieve-betekenis), [Wet- en Regelgeving](#wet-en-regelgeving)

Voorbeeld(en): Een verwijzing naar artikel 9, lid 1 van de AVG geeft aan welke categorieën van persoonsgegevens bijzondere categorieën zijn, en dat het verboden is om die te verwerken.

### Herleidbaarheid pragmatische betekenis

> De herleidbaarheid van de [pragmatische betekenis](#pragmatische-betekenis) van gegevens wordt geborgd met een verwijzing naar de [organisatorische activiteit](#organisatorische-activiteit) en de [uitvoeringsregels](#uitvoeringsregel) waarin die betekenis wordt beschreven, d.w.z. het specifieke [informatieobject](#informatieobject) waarin dat staat.

Toelichting: We doelen hier dus op de onderliggende wetsteksten, het beleidsdocument, de NEN-standaard etc. die is gebruikt om de praktische betekenis van gegevens van af te leiden en vast te leggen in bedrijfsregelmodellen en procesmodellen. Hoe specifieker die verwijzing is, hoe bruikbaarder.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Informatieobject](#informatieobject), [Pragmatische betekenis](#pragmatische-betekenis), [Uitvoeringsregel](#uitvoeringsregel), [Organisatorische activiteit](#organisatorische-activiteit)

### Identificator voor Domeinobjecttype

> Eén of meer [inherente kenmerken](#inherent-kenmerk)vormen een Identificator voor een [domeinobjecttype](#domeinobjecttype) als met die kenmerken elk [domeinobject](#domeinobject) van dat [domeinobjecttype](#domeinobjecttype) kan worden onderscheiden van elk ander [domeinobject](#domeinobject) van datzelfde type.

Toelichting: Het is dus de verzameling attribuuttypen waarmee je elk domeinobject van dat type kan onderscheiden van een ander domeinobject van dat type.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Inherent kenmerk](#inherent-kenmerk), [Domeinobjecttype](#domeinobjecttype), [Domeinobject](#domeinobject)

Voorbeeld(en): De attribuuttypen Postcode en Huisnummer zijn een identificator voor Nederlands Adres. Burgerservicenummer is een identificator voor een burger met een verzoek aan de overheid.

### Informatieobject

> Een informatieobject is een op zichzelf staand geheel van gegevens met een eigen identiteit.

Toelichting: Waar gegevens productiemiddelen zijn die worden verwerkt, zijn informatieobjecten het (tussen)resultaat van deze verwerking. Met andere woorden: informatieobjecten ontstaan door de verwerking van gegevens, en bestaan uit gegevens. Voor zover deze gegevens gestructureerd zijn, betreffen dit gegevensobjecten.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Voorbeeld(en): Een document, een databaserecord, een boek, een poster of een film zijn allemaal informatieobjecten.

### Inherent kenmerk

> Een inherent kenmerk is een [kenmerk](#kenmerk) wat inherent is aan het [domeinobject](#domeinobject) zelf en in een andere situatie dus niet zomaar wijzigt zonder het domeinobject zelf te wijzigen.

Zowel een [categorisch kenmerk](#categorisch-kenmerk) als een [eigenschap](#eigenschap) zijn een inherent kenmerk.

Toelichting: Een voorbeeld van een kenmerk dat niet inherent is, is een Rol die door een domeinobject wordt gespeeld. Deze kan telkens anders zijn, ook als het domeinobject gelijk blijft.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Categorisch kenmerk](#categorisch-kenmerk), [Domeinobject](#domeinobject), [Kenmerk](#kenmerk), [Eigenschap](#eigenschap)

### Intrinsieke betekenis

> De intrinsieke betekenis van gegevens is de betekenis zoals deze volgt uit de aard van de gegevens zelf, inclusief hun vorm, structuur en relatie met andere gegevens.

De intrinsieke betekenis is verwant aan de [pragmatische betekenis](#pragmatische-betekenis) en de [normatieve betekenis](#normatieve-betekenis).

Toelichting: Gegevens als "5,4" of "21" zijn getallen en "5 mei 1945" is een datum. Dat is de intrinsieke betekenis van het gegeven zelf, zonder interpretatie of waardeoordeel. De intrinsieke betekenis moet bekend zijn voordat men betekenis aan die gegevens kan toekennen in een bepaalde context (zoals in systemen, beleid of rapportages).

De intrinsieke betekenis dient de normatieve betekenis te ondersteunen, en daarmee te zorgen dat de pragmatische betekenis zoveel als mogelijk is de normatieve betekenis volgt.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Normatieve betekenis](#normatieve-betekenis), [Pragmatische betekenis](#pragmatische-betekenis)

### Juridische classificatie

> Een juridische classificatie is een classificatie die aangeeft bij een [begrip](#begrip) welk soort rechtsbegrip bedoeld wordt.

Toelichting: De rechtsbegrippen zijn o.a.:
- Rechtsfeit
- Rechtsgevolgen
- Rechtsobject
- Rechtssubject
- Rechtsbetrekking
- Voorwaarde
- Variabele
- Parameter
- Waarde
- Afleidingsregel
- Tijdsaanduiding
Deze worden hier niet verder uitgewerkt, zie de bronnen voor meer informatie.

Bron: , 

Gerelateerd: [Begrip](#begrip)

### Kenmerk

> Een kenmerk is een aanduiding van een bepaalde kwaliteit die een domeinobject wel of niet bezit.

Toelichting: Elke kwaliteit waarvan we kunnen zeggen of deze aanwezig of afwezig is op een specifiek domeinobject, kan een kenmerk zijn van dat domeinobject.

*In de MIM is een kenmerk een eigenschap van een domeinobject. In het gegevenstyperingsbeleid reserveren we eigenschappen voor letterlijke waarden van kwaliteiten die inherent zijn aan een domeinobject, dus een nauwere betekenis dan in de MIM.*

Bron: MIM - Metamodel Informatie Modellering v1.2 (juni 2024) [[MIM]], JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Voorbeeld(en): Domeinobject Ronald heeft kenmerk "is roodharig" met als letterlijke waarde "nee".

### Kennisbron

> Een kennisbron is een autoritaire en vaak formele bron voor de definitie van een [term](#term). Het bevat de autoritaire kennis over de betekenis van de [term](#term).

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Term](#term)

Voorbeeld(en): De NORA bevat autoritaire definities voor begrippen die gerelateerd zijn aan de bedrijfsarchitectuur van de overheid. Het Wetboek van Strafrecht bevat autoritaire definities voor (een aantal) termen die we gebruiken in het strafrecht.

### Kritiek gegevenselement

> Een kritiek gegevenselement is een categorie van gegevens uit één of meerdere [gegevenssets](#gegevensset) zoals verwerkt binnen een [organisatorische activiteit](#organisatorische-activiteit) die vanwege het gebruiksdoeleind of wettelijke vereisten van cruciaal belang is voor het functioneren, besluitvorming of strategische doelen van een organisatie of keten. 

Een kritiek gegevenselement of KGE wordt gespecificeerd door een [gegevenstypegroep](#gegevenstypegroep).

Toelichting: Bij de verwerking van persoonsgegevens en voertuiggegevens voor de APK-regeling kunnen we enkele KGE's vaststellen. Vanuit de AVG is elk persoonsgegeven een kritiek gegevenselement, dus beschouwen we de gegevenstypegroep "tenaamstelling" als KGE. Verder beschouwen we "voertuigidentificatie" als KGE, samen met de gegevenstypegroep die bestaat uit de gegevenstypen ("laatste keuringsdatum", "eerste tenaamstellingsdatum"), genaamd "relevante datums".

Merk op dat het mogelijk is dat gegevenstypegroep en gegevensobjecttypen samenvallen, maar dat dat niet per sé het geval is.

*Een kritiek gegevenselement is te zien als een subtype van gegevenstypegroep.*

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Gegevensset](#gegevensset), [Organisatorische activiteit](#organisatorische-activiteit), [Gegevenstypegroep](#gegevenstypegroep)

Voorbeeld(en): De gegevenstypen voornaam, achternaam, BSN, straatnaam, huisnummer, postcode en geboortedatum vormen in dit gegevensmodel samen het kritieke gegevenselement "Persoonsgegeven".

### Letterlijk waardetype

> Een letterlijk waardetype is een typering van gelijksoortige [letterlijke waarden](#letterlijke-waarde) die een [letterlijk attribuuttype]() kan aannemen.

Toelichting: Als we de eigenschap "geboortedatum" herkennen, dan hoort daarbij dat we ook zien dat de waarde die we daar invullen telkens dezelfde vorm heeft. Die vorm is het waardetype. Bij een letterlijk attribuuttype hoort ook een letterlijk waardetype.

Gerelateerd: [letterlijk attribuuttype](#letterlijk-attribuuttype), [Letterlijke waarde](#letterlijke-waarde)

Voorbeeld(en): Datum, tekenreeks, ordinaal nummer.

### Letterlijke waarde

> Een letterlijke waarde is een [waarde](#waarde) die niets meer is dan wat er staat, en dus letterlijk zo moet worden opgevat.

Toelichting: Een letterlijke waarde is iets wat niet verwijst naar iets anders, en intrinsiek behoort bij een bepaalde eigenschap op een specifiek domeinobject. Een letterlijke waarde heeft geen eigen identiteit, anders dan de waarde zelf.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Waarde](#waarde)

Voorbeeld(en): 10, "Jan Janssen", 15-5-2000.

### Logisch gegevensmodel

> Een specificatie van de [intrinsieke betekenis](#intrinsieke-betekenis) van de [gegevenstypen](#gegevenstype) en hun onderlinge relaties binnen een [beschouwingsdomein](#beschouwingsdomein).

Toelichting: In een logisch gegevensmodel vinden we de intrinsieke betekenis van gegevens. De intrinsieke betekenis is de betekenis van het gegeven zelf, zonder interpretatie of waardeoordeel. Het is meestal het startpunt vóór men betekenis gaat toekennen in een bepaalde context (zoals in systemen, beleid of rapportages). 

De intrinsieke betekenis van "5,4" is dat het een getal is. De normatieve betekenis kan echter zijn dat dit een onvoldoende is als examencijfer, dat het buiten koud is, of dat binnenschepen met normale belading de Rijn mogen bevaren. De intrinsieke betekenis wordt nader gedetailleerd in een technisch gegevensmodel.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Gegevenstype](#gegevenstype), [Intrinsieke betekenis](#intrinsieke-betekenis), [Beschouwingsdomein](#beschouwingsdomein)

### Maximale cardinaliteit

> Een maximale cardinaliteit geeft aan hoeveel instanties de [domeinrelatieverbintenis](#domeinrelatieverbintenis) waarop de cardinaliteit geldig is maximaal mag hebben.

Toelichting: Het gaat er dus om hoeveel domeinrelatieverbintenissen van dat type maximaal mogen worden vastgelegd om de domeinrelatieverbintenis geldig te laten zijn.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Domeinrelatieverbintenis](#domeinrelatieverbintenis)

### Metadata

> Gegevens over gegevens.

Toelichting: Elk gegeven dat een uitspraak doet over een ander gegeven, is een metagegeven.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Voorbeeld(en): Invoerdatum, wijzigingsdatum, gebruikers-ID van de wijzigende partij, etc.

### Metadatamanagement

> De beheersing van de metadata.

Toelichting: Dit omvat de organisatie, sturing, taken, rollen en verantwoordelijkheden die nodig zijn om de metadata goed te beheersen.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

### Metamodel Informatie Modellering

> Het Metamodel Informatie Modellering (MIM) is een metamodel waarmee [conceptuele informatiemodellen](#conceptueel-informatiemodel) en [logische gegevensmodellen](#logisch-gegevensmodel) kunnen worden uitgewisseld tussen verschillende partijen.

Toelichting: De MIM is één van de standaarden die door de overheid worden gebruikt.

Bron: MIM - Metamodel Informatie Modellering v1.2 (juni 2024) [[MIM]]

Gerelateerd: [Logisch gegevensmodel](#logisch-gegevensmodel), [Conceptueel informatiemodel](#conceptueel-informatiemodel)

### Minimale cardinaliteit

> Een minimale cardinaliteit geeft aan hoeveel instanties de [domeinrelatieverbintenis](#domeinrelatieverbintenis) waarop de cardinaliteit geldig is minimaal moet hebben.

Toelichting: Het gaat er dus om hoeveel domeinrelatieverbintenissen van dat type minimaal moeten worden vastgelegd voordat de domeinrelatieverbintenis geldig is.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Domeinrelatieverbintenis](#domeinrelatieverbintenis)

### Motivatie

> Een motivatie is een reden die de organisatie zelf heeft om een bepaalde [organisatorische activiteit](#organisatorische-activiteit) uit te voeren.

Toelichting: Het gaat hierbij vooral om activiteiten die niet zijn voorgeschreven vanuit de wet, maar wel belangrijk zijn voor het resultaat wat men wil behalen.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Organisatorische activiteit](#organisatorische-activiteit)

Voorbeeld(en): Huisvesting, interne verwerkingen, het sollicatieproces, etc.

### Normatieve betekenis

> De normatieve betekenis van gegevens is de betekenis zoals deze volgt uit [wet- en regelgeving](#wet-en-regelgeving), uitvoeringsbeleid en andere kaderstelling die beoogt om normen te stellen aan gedrag.

De normatieve betekenis is verwant aan de [pragmatische betekenis](#pragmatische-betekenis) en de [intrinsieke betekenis](#intrinsieke-betekenis).

Toelichting: In beleid, administratie of besluitvorming krijgt een gegeven vaak een normatieve lading:

* een inkomen onder de €1.200 per maand wordt normatief gezien als onder de armoedegrens.
* een CO₂-uitstoot van X ton per jaar wordt beoordeeld t.o.v. klimaatdoelen.
* een geboortedatum bepaalt of iemand volgens de wet meerderjarig is.
* een cijfer "5,4" op een examen is volgens de norm een onvoldoende.

De normatieve betekenis van gegevens is dus de manier waarop we aan gegevens een oordeel of waarde hechten, vaak op basis van wetgeving, beleid, normen of maatschappelijke opvattingen.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Intrinsieke betekenis](#intrinsieke-betekenis), [Pragmatische betekenis](#pragmatische-betekenis), [Wet- en Regelgeving](#wet-en-regelgeving)

### Normatieve betekenis van Gegevenstype (U3)

> De normatieve betekenis van een gegevenstype is de [normatieve betekenis](#normatieve-betekenis) die door een [gegevensmodelleur](#gegevensmodelleur) wordt toegekend aan een [gegevenstype](#gegevenstype).

Toelichting: De normatieve betekenis is een interpretatie van de betekenis die de kaderstelling geeft aan een bepaald begrip. Tijdens het opstellen van het begrippenkader wordt bij een begrip daarom uitgelegd hoe dat tot stand komt en vanuit welke kennisbronnen. De koppeling tussen begrip en gegevenstype verklaart dan de normatieve betekenis van het gegevenstype.

De gegevensmodelleur is verantwoordelijk voor de toekenning (en vastlegging) van de normatieve betekenis van elk gemodelleerd gegevenstype.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Gegevensmodelleur](#gegevensmodelleur), [Normatieve betekenis](#normatieve-betekenis), [Gegevenstype](#gegevenstype)

Voorbeeld(en): BSN verwijst naar het begrip Nationaal identificatienummer in een begrippenkader over de DPIA. Gegevenstype verwijst naar het begrip Gegevenstype zoals gedefinieerd in het JAGA Gegevenstyperingsbeleid en bijbehorende begrippenkader.

### Organisatorische activiteit

> Een organisatorische activiteit is een typering van een activiteit die een organisatie uitvoert of uit moet voeren.

Toelichting: Het gaat hier om zaaktypen en bedrijfsprocestypen, dus niet om de instanties van elke keer dat een bedrijfsprocestype of zaaktype wordt uitgevoerd.

Bron: Kerndepartement J&V [[KDJV]]

### Organisatorische doelstelling

Alternatieve aanduiding: *Gebruikersdoel; gebruikersdoeleind*

> Een organisatorische doelstelling is een doelstelling van de organisatie om te voldoen aan [wet- en regelgeving](#wet-en-regelgeving), of aan een andere eis die de omgeving of de eigen organisatie oplegt (een [motivatie](#motivatie)). Het is het doel waarvoor een organisatie een [organisatorische activiteit](#organisatorische-activiteit) onderneemt en beschrijft het resultaat wat men daarmee wil ([motivatie](#motivatie)) of moet ([wet- en regelgeving](#wet-en-regelgeving)) bereiken.

Toelichting: Gebruikersdoeleinden ontstaan primair vanuit wet- en regelgeving. maar kunnen ook ontstaan uit een andere motivatie, zoals een taakstelling, marktwerking, het willen standaardiseren of vanuit andere externe en interne factoren die bepalen waar een organisatie mee bezig is.

Bron: Archiefwet 1995 [[Archiefwet]], Kerndepartement J&V [[KDJV]]

Gerelateerd: [Wet- en Regelgeving](#wet-en-regelgeving), [Motivatie](#motivatie), [Organisatorische activiteit](#organisatorische-activiteit)

Voorbeeld(en): Voldoen aan de Archiefwet en AVG, terugdringen criminaliteit onder jongeren, verhoging naamsbekendheid, etc.

### Organisatorische doelstelling o.b.v. motivatie

> Een organisatorische doelstelling o.b.v. motivatie is een [organisatorische doelstelling](#organisatorische-doelstelling) op basis van een [motivatie](#motivatie) die niet in bovenliggende kaders is vastgesteld.

Toelichting: Een motivatie is vaak intern, tenzij er vanuit een belangrijke stakeholder druk is uitgeoefend om deze motivatie prioriteit te geven.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Motivatie](#motivatie), [Organisatorische doelstelling](#organisatorische-doelstelling)

Voorbeeld(en): Klanttevredenheid verhogen, efficiency verhogen, medewerkerstevredenheid verhogen.

### Organisatorische doelstelling o.b.v. wet- en regelgeving

> Een organisatorische doelstelling o.b.v. wet- en regelgeving is een [organisatorische doelstelling](#organisatorische-doelstelling) op basis van [wet- en regelgeving](#wet-en-regelgeving), dus op basis van een dwingend bovenliggend kader.

Toelichting: De meeste doelstellingen op deze basis zullen aan de organisatie worden opgelegd door anderen.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Wet- en Regelgeving](#wet-en-regelgeving), [Organisatorische doelstelling](#organisatorische-doelstelling)

Voorbeeld(en): Voldoen aan de Archiefwet en AVG, het uitvoeren van een wettelijke taak of taak van algemeen belang, het volgen van het beleid van het Ministerie van Binnenlandse Zaken, etc.

### Partij

> Een natuurlijk persoon of rechtspersoon, een overheidsinstantie, een dienst of een ander orgaan, al dan niet een derde, die zichzelf rechtsgeldig kan vertegenwoordigen.

Bron: JAGA Gegevensdelingsbeleid [[Gegevensdelingsbeleid]]

### Persoon

> Een persoon in de context van dit begrippenkader is een natuurlijke persoon.

Toelichting: Het gaat hier om mensen die een rol kunnen vervullen in het uitvoeren van het gegevenstyperingsbeleid.

Bron: Kerndepartement J&V [[KDJV]]

### Pragmatische betekenis

Alternatieve aanduiding: *contextuele betekenis*

> De pragmatische betekenis van gegevens is de betekenis zoals deze volgt uit (de context van) het gebruik van de gegevens en de impact die dit gebruik met zich meebrengt. Deze wordt geformaliseerd in de verbinding tussen aan de ene kant de [logische gegevensmodellen](#logisch-gegevensmodel) en [technische gegevensmodellen](#technisch-gegevensmodel), en aan de andere kant de procesmodellen en bedrijfsregelmodellen.

De pragmatische betekenis is verwant aan de [normatieve betekenis](#normatieve-betekenis) en de [intrinsieke betekenis](#intrinsieke-betekenis).

Toelichting: De pragmatische betekenis is de betekenis die mensen hechten aan de gegevens, en wat de impact van die gegevens is:

* wel of geen inkomenssteun bij een bepaald inkomen.
* het examen moet opnieuw worden afgelegd, omdat een onvoldoende werd behaald.
* de persoon mag een rijexamen afleggen.

Deze betekenis ontstaat in de praktijk in een context die wordt bepaald door de organisatorische activiteit waar de gegevens in worden vastgelegd. Die context is medebepalend voor de betekenis. Een getal "5,4" dat is toegekend door een docent na het nakijken van een examen, is een ander gegeven dan een "5,4" die wordt gemeten met een gecalibreerde buitenthermometer om 08:00 uur in De Bilt, of dat als waterpeil wordt gemeten in de Rijn bij Lobith.

De pragmatische betekenis heeft een relatie met de normatieve of bedoelde betekenis, in de zin dat deze zoveel mogelijk overeen zouden moeten komen. De relatie met de intrinsieke betekenis is dat deze de pragmatische betekenis zoveel mogelijk moet helpen om overeen te komen met de normatieve betekenis.

*Bij het bepalen van de praktische betekenis van een gegeven zijn "wie, wat, waar, hoe en wanneer" belangrijke vragen.*

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Technisch gegevensmodel](#technisch-gegevensmodel), [Intrinsieke betekenis](#intrinsieke-betekenis), [Normatieve betekenis](#normatieve-betekenis), [Logisch gegevensmodel](#logisch-gegevensmodel)

### Primitief datatype

> Een [datatype](#datatype) met een eenvoudige basisstructuur, oftewel enkelvoudig en zonder gelaagdheid.

Toelichting: : Een primitief datatype is een datatype zonder verdere specificatie over de structuur. Dit datatype is enkelvoudig, oftewel niet samengesteld en wordt ook wel simpel datatype genoemd. Dit datatype kent daarom zelf geen eigen modelelementen. Ook is er geen sprake van een gelaagdheid, ook wel nesting genoemd. Een primitief datatype kan wel een (formeel) patroon hebben, die een nadere beperking oplegt aan de mogelijke invulling.

Bron: MIM - Metamodel Informatie Modellering v1.2 (juni 2024) [[MIM]]

Gerelateerd: [Datatype](#datatype)

Voorbeeld(en): Integer, String, DateTime

### Procesmodel

> Een procesmodel is een gestructureerde weergave van de stappen, beslispunten en samenhangen die nodig zijn om een bepaald bedrijfs­proces uit te voeren. Het formaliseert de volgorde, besluit­logica, betrokken rollen en benodigde resources van een bedrijfsproces, zodat zowel functionele experts als IT‑systemen eenduidig begrijpen hoe, wanneer en door wie elke stap moet worden uitgevoerd.

Bron: Kerndepartement J&V [[KDJV]]

### Regelgeving

> Regelgeving omvat alle regels en voorschriften die door verschillende overheidsinstanties zijn vastgesteld om de uitvoering van [wetgeving](#wetgeving) te specificeren en te operationaliseren.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Wetgeving](#wetgeving)

### Registratietijd

Alternatieve aanduiding: *transaction time*

> Met de registratietijd bedoelen we het tijdsinterval vanaf een startdatum waarop gegevens over een [domeinobject](#domeinobject) of [domeinrelatie](#domeinrelatie) worden vastgelegd, tot het moment dat die gegevens niet langer actief zijn in onze [administratie](#administratie).

Toelichting: De levensduur van de uitspraken over eigenschappen van objecten of relaties tussen objecten noemen we de registratietijd(slijn).

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Administratie](#administratie), [Domeinobject](#domeinobject), [Domeinrelatie](#domeinrelatie)

### Relatiedomeinobject

> Een relatiedomeinobject is een verzelfstandiging van een [domeinrelatie](#domeinrelatie) in een eigen [domeinobject](#domeinobject) waarvan we de [kenmerken](#kenmerk) willen vastleggen.

Toelichting: Een domeinrelatie kent geen eigenschappen, maar een domeinobject wel. Een domeinrelatie die zelfstandig bestaat (zoals een arbeidsrelatie X21012 tussen Joop en het ministerie van J&V waar een arbeidscontract genaamd X214444 bij hoort) heeft zelf ook eigenschappen en is dus (ook) een domeinobject.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Domeinobject](#domeinobject), [Domeinrelatie](#domeinrelatie), [Kenmerk](#kenmerk)

Voorbeeld(en): Een arbeidsrelatie met een start- en eindtijd. Een huwelijk tussen Jan en Marie van 1-1-2020 tot en met 1-2-2020.

### Relatiedomeinobjecttype

> Een relatiedomeinobjecttype is een verzelfstandiging van een [domeinrelatietype](#domeinrelatietype) in een eigen [domeinobjecttype](#domeinobjecttype) waarvan we kenmerken willen vastleggen.

Toelichting: Een domeinrelatietype kent geen eigenschappen, maar een domeinobjecttype wel. Een domeinrelatietype dat zelfstandig bestaat (zoals het type "arbeidsrelatie" waar voor elke arbeidsrelatie ook een arbeidscontract bestaat) heeft zelf ook eigenschappen en is dus (ook) een domeinobjecttype.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Domeinobjecttype](#domeinobjecttype), [Domeinrelatietype](#domeinrelatietype)

Voorbeeld(en): Arbeidsrelaties waarvan we de start- en eindtijd willen vastleggen, of huwelijken waarbij we ook een relatie willen leggen met eventuele kinderen die uit het huwelijk voortkomen. De relatie tussen begrippen onderling die voorzien worden van een classificerend attribuuttype voor het soort relatie.

### Relatiegegevenstype

Alternatieve aanduiding: *Foreign key*

> Een relatiegegevenstype is een [gegevenstype](#gegevenstype) dat een [domeinrelatieverbintenis](#domeinrelatieverbintenis) als onderwerp heeft, en daarmee een [gegevensobjecttype](#gegevensobjecttype) in een [rol](#rol) op een [gegevensobjecttype](#gegevensobjecttype) aanduid.

Toelichting: De naam van het relatiegegevenstype zal dus vaak de rol zijn die het gegevensobjecttype aanneemt in de kant van de relatie die hier wordt getypeerd.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Gegevensobjecttype](#gegevensobjecttype), [Gegevenstype](#gegevenstype), [Rol](#rol), [Domeinrelatieverbintenis](#domeinrelatieverbintenis)

Voorbeeld(en): medewerker, woonadres, postadres, betrokken begrippenkader, etc.

### Rol

Alternatieve aanduiding: *Relatierol*

> De benaming van de manier waarop een [domeinobject](#domeinobject) deelneemt aan een [domeinrelatie](#domeinrelatie) met een ander [domeinobject](#domeinobject).

Bron: MIM - Metamodel Informatie Modellering v1.2 (juni 2024) [[MIM]]

Gerelateerd: [Domeinrelatie](#domeinrelatie), [Domeinobject](#domeinobject)

Voorbeeld(en): Een domeinobject Ronald kan deelnemen in een domeinrelatie in de rol van Gegevensmodelleur voor het Gegevenstyperingsbeleid.

### Semantisch model

> Een specificatie van de [normatieve betekenis](#normatieve-betekenis) van de [gegevenstypen](#gegevenstype) en hun [praktische betekenis]() binnen een [beschouwingsdomein](#beschouwingsdomein), waarbij vastgelegd wordt hoe gegevens geïnterpreteerd worden in termen van [wet en regelgeving](#wet-en-regelgeving), [uitvoeringsregels](#uitvoeringsregel) en organisatorische doelstellingen.

Toelichting: Het semantisch model legt de normatieve betekenislaag vast: het beschrijft wát de gegevens in een gegeven context betekenen, binnen een bepaald beschouwingsdomein. Dit staat los van hun fysieke opslag of technische representatie. We modelleren dus niet de gegevens, maar het begrip van de gegevens. Feitelijk is een semantisch model dus een begripsmodel en geen gegevensmodel.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [praktische betekenis](#praktische-betekenis), [Beschouwingsdomein](#beschouwingsdomein), [Normatieve betekenis](#normatieve-betekenis), [wet en regelgeving](#wet-en-regelgeving), [Uitvoeringsregel](#uitvoeringsregel), [Gegevenstype](#gegevenstype)

### Semantische interoperabiliteit

> Semantische interoperabiliteit onstaat wanneer partijen de betekenis van begrippen onderling harmoniseren, zodat vastgelegde gegevens over dat begrip voor alle betrokken partijen dezelfde beoogde betekenis hebben.

Bron: New European Interoperability Framework (ISA2) [[NewEUInterop]], JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

### Shapes Constraint Language

> Shapes Constraint Language of SHACL is een World Wide Web Consortium (W3C) standaard taal om Resource Description Framework (RDF) grafen te beschrijven.

Toelichting: SHACL is ontworpen om de semantische en technische interoperabiliteitslagen van ontologieën die als RDF graaf worden uitgedrukt, te kunnen beschrijven.

Bron: Shapes Constraint Language (SHACL) [[W3C-SHACL]]

### Taalbinding

Alternatieve aanduiding: *Eenheid van taal*

> Een taalbinding is een verbinding tussen verschillende begrippenkaders, waarbij wordt aangegeven hoe de termen in het ene [begrippenkader](#begrippenkader) zich verhouden tot de termen uit een ander [begrippenkader](#begrippenkader).

Toelichting: Binnen het gegevenstyperingsbeleid, met name uitgangspunt 11, wordt met een taalbinding bedoeld dat alternatieve gegevensmodelleringen (zoals FCO-IM, E-R of UML) of methodieken voor gegevensbeheersing (zoals DM-BOK) alternatieve namen kunnen gebruiken voor de begrippen die wij in het gegevenstyperingsbeleid hebben opgenomen. In dat geval is het de bedoeling dat de strekking van de definitie die wij hanteren in het beleid wordt overgenomen, ongeacht de terminologie in andere begrippenkaders en modelleringsmethodieken.

Bij een taalbinding hoeft niet elk begrip rechtstreeks te kunnen worden vertaald, maar er moet wel een manier zijn waarop je van het ene naar het andere begrippenkader kan komen.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Begrippenkader](#begrippenkader)

Voorbeeld(en): In het gegevenstyperingsbeleid zelf worden begrippen gebruikt met een Nederlandse term als voorkeursterm. De Engelse term staat waar nodig dan tussen haakjes erachter.

### Technisch gegevensmodel

> Een specificatie van de neerslag in een fysiek opslagmedium van het [logisch gegevensmodel](#logisch-gegevensmodel).

Toelichting: Een technisch model is dus een weergave van (en verbonden met) een logisch gegevensmodel, gericht op de technische werkelijkheid. De vorm kan dus anders zijn dan die van het logisch model, zolang de semantiek, gegevenstypering en de overige beperkingen die het logisch model oplegt maar intact blijven. In een technisch gegevensmodel vinden we de intrinsieke betekenis van gegevens.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Logisch gegevensmodel](#logisch-gegevensmodel)

### Term

Alternatieve aanduiding: *Voorkeursterm*

> Een woord dat (of woordcombinatie die) wordt gebruikt in een beschouwings- of kennisdomein, waarbij we met dat woord verwijzen naar de betekenis voor de gebruikers in de context van dat domein, het [begrip in begrippenkader]().

Toelichting: Een term is de naam van een begrip, als onderdeel van een begrippenkader. We (her)gebruiken waar mogelijk formele begrippen, zoals bijvoorbeeld de begrippen uit de NORA. We verwijzen naar een begrip met een voorkeursterm, om de eenheid van taal te borgen.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]], 

Gerelateerd: [begrip in begrippenkader](#begrip-in-begrippenkader)

### Uitvoeringsregel

> Een regel waaraan de uitvoerende organisatie moet gehoorzamen bij het uitvoeren van een [organisatorische activiteit](#organisatorische-activiteit) zoals een bedrijfsproces.

Toelichting: Een verzameling uitvoeringsregels noemen we ook wel een algoritme.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Organisatorische activiteit](#organisatorische-activiteit)

### Unified Modeling Language

> De Unified Modeling Language (UML) is een algemene visuele modellerings-taal die bedoeld is om een standaard manier te bieden om het ontwerp van een systeem te visualiseren.

Toelichting: Onderdeel van UML is een notatie voor gegevensmodellen.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]], UML (Wikipedia) [[WikipediaUML]]

### Vastgelegde uitspraak

> Een vastgelegde uitspraak is een uitspraak over een eigenschap van een [domeinobject](#domeinobject), die is vastgelegd in een medium.

Toelichting: Het medium waar uitspraken in worden vastgelegd is niet belangrijk, of het nu steen, klei, papier, digitaal of een geluidsdrager o.i.d. is.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

Gerelateerd: [Domeinobject](#domeinobject)

### Verwerkingsdomein

Alternatieve aanduiding: *Data Processing Area; Gegevensgebied*

> Een verwerkingsdomein is een afgebakend deel van de verwerking van gegevens binnen een organisatie. Het beschrijft de afbakening van de gegevens binnen de verwerking van die gegevens (uitwisseling, registratie, creatie, gebruik, vernietiging).

Toelichting: Een verwerkingsdomein bestaat uit (en geeft daarmee de samenhang weer van) één of meer gegevensverwerkingstypen. Een verwerkingsdomein geeft daarmee ook de samenhang weer van de gegevenstypen die in die gegevensverwerkingstypen worden verwerkt.

Bron: JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

### Voorkeursterm

> De voorkeursterm is de [term](#term) waaronder een [begrip](#begrip) bekend is en indien mogelijk wordt gebruikt.

Toelichting: Het kan zijn dat er in het verleden alternatieve termen zijn gehanteerd, of dat er een andere reden is geweest om andere termen te hanteren voor hetzelfde begrip. Deze worden alternatieve termen. De voorkeursterm is leidend.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Term](#term), [Begrip](#begrip)

### Waarde

> Een waarde is een kwantitatieve aanduiding van een hoeveelheid van een specifieke kwaliteit van een specifiek object in het domein.

Toelichting: Een waarde is niets meer dan dat: een invulling van een bepaald kenmerk van een object in het domein. Zonder de invulling bestaat het kenmerk niet voor dat domeinobject, en zonder kenmerk weten we niet waar de waarde op slaat.

Bron: Kerndepartement J&V [[KDJV]]

Voorbeeld(en): De lengte van Jan is 180 centimeter. De haarkleur van Jan is paarsrood. De straatnaam is Schoolstraat.

### Waardegegevenstype

> Een waardegegevenstype is een [gegevenstype](#gegevenstype) dat als onderwerp een [attribuuttype](#attribuuttype) heeft.

Toelichting: Een waardegegevenstype kan zowel concrete als classificerende attribuuttypen als onderwerp hebben, maar geen domeinrelatieverbintenissen.

De mogelijke invulling van een waardegegevenstype wordt daarnaast beperkt door een bijbehorend (primitief of gestructureerd) datatype.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Gegevenstype](#gegevenstype), [Attribuuttype](#attribuuttype)

### Waardetype

> Een waardetype is een typering van een aantal gelijksoortige [waarden](#waarde).

Toelichting: Een waardetype geeft een naam aan een reeks gelijksoortige waarden.

Bron: Kerndepartement J&V [[KDJV]]

Gerelateerd: [Waarde](#waarde)

Voorbeeld(en): Datum, ordinaal nummer, tijd, afstand, lengte, etc. zijn waardetypen.

### Web Ontology Language

> De Web Ontology Language (OWL) is een formele taal die speciaal is ontworpen voor het definiëren en delen van ontologieën op het semantisch web.

Toelichting: OWL maakt het mogelijk om rijke en complexe kennisrepresentaties te creëren door middel van logische beschrijvingen van concepten, relaties en instanties binnen een bepaald domein. Deze taal ondersteunt automatische redenering, waardoor computers de gestructureerde informatie kunnen interpreteren en er conclusies uit kunnen trekken.

Bron: Web Ontology Language [[W3COWL]], JAGA Gegevenstyperingsbeleid [[Gegevenstyperingsbeleid]]

### Wet- en Regelgeving

> Wet- en regelgeving omvat zowel [wetgeving](#wetgeving) als [regelgeving](#regelgeving)

Toelichting: We verwijzen naar wet- en regelgeving op de officiële naam van de wet, met vermelding van het artikel-, lid- en eventuele sub-nummer.

Bron: Verordening (EU) 679/2016 van het Europees Parlement en de Raad van 27 april 2016 [[AVG]], Archiefwet 1995 [[Archiefwet]], Kerndepartement J&V [[KDJV]]

Gerelateerd: [Wetgeving](#wetgeving), [Regelgeving](#regelgeving)

Voorbeeld(en): De Algemene Verordening Gegevensbescherming (AVG) en de Archiefwet zijn voorbeelden van wetgeving die op vrijwel alle organisatorische activiteiten in de overheid van toepassing zijn.

### Wetgeving

> Wetgeving omvat alle wetten die door een bevoegde wetgevende instantie zijn vastgesteld.

Toelichting: In Nederland is dit voornamelijk het parlement (Staten-Generaal), bestaande uit de Eerste en Tweede Kamer. Wetgeving vormt de basis van het juridisch kader en regelt het gedrag van burgers, bedrijven en overheidsinstanties.

Bron: Kerndepartement J&V [[KDJV]]

