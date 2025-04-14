Dit document beschrijft de gegevenstypering van het Gegevenstyperingsbeleid. Deze gegevenstypering bestaat uit de volgende onderdelen:

1. Een [introductie](#Intro) die in verhalende vorm de relatie tussen de begrippen in het gegevenstyperingsbeleid uitlegt.
1. De definities van de [relevante begrippen](#begrippen) voor het [gegevenstyperingsbeleid](#gegevenstyperingsbeleid) en hun onderlinge relaties;
1. De conceptuele informatiemodellen van het [gegevenstyperingsbeleid](#cim-gegevenstyperingsbeleid) (CIM). Dit model beschrijft de informatiebehoefte in termen van de relevante objecten en hun eigenschappen;
1. Het logische gegevensmodel (LGM) van het [gegevenstyperingsbeleid](#gegevenstyperingsbeleid-0) dat beschrijft welke gegevens bijgehouden dienen te worden (en op welke wijze) als men een administratie (boekhouding) rond gegevenstypering zou willen bijhouden.

De modellen zijn gebaseerd op de volgende documenten:

* Gegevenstyperingsbeleid ([[Gegevenstyperingsbeleid]])
* Implementatiehandreiking Gegevenstyperingsbeleid (te vinden op [[Gegevenstyperingsbeleid]])


**Versionering in dit document**

Het versienummer van dit document is opgebouwd conform Semantic versioning [[SemVer]]. Het versienummer geeft daarmee informatie over de status van dit document:

- Formeel bekendgemaakte en gepubliceerde versies van dit document hebben altijd een versienummer met de aanduiding "vastgestelde versie", plus een datum waarop deze versie is vastgesteld
- Andere versies betreffen werkversies (-concept) dan wel versies ter vaststelling (-rc1, -rc2, etc), met een datum waarop de betreffende versie beschikbaar is gekomen.
- Het versienummer is opgebouwd als MAJOR.MINOR.PATCH.
- Een wijziging van het PATCH deel van het versienummer geeft aan dat een typefout of een verandering van de vorm is doorgevoerd, zonder dat sprake is van een inhoudelijke wijziging. Dergelijke PATCH wijzigingen hebben geen impact op organisaties die gebruik maken van modellen uit dit document;
- Een wijziging van het MINOR deel van het versienummer geeft aan dat een inhoudelijke wijziging of aanvulling is doorgevoerd. Dergelijke MINOR wijzigingen kunnen impact hebben op organisaties die gebruik maken van modellen uit dit document. Geadviseerd wordt om in dat geval te kijken of sprake is van een dergelijke impact en hiervoor de noodzakelijke acties uit te zetten.
- Een wijziging van het MAJOR deel van het versienummer geeft aan dat een grote inhoudelijke wijziging is doorgevoerd. Dergelijke MAJOR wijzigingen zullen een impact hebben op organisaties die gebruik maken van modellen uit dit document. Bij een dergelijke wijziging zal een reviewproces doorlopen worden, gelijk als bij de eerste oplevering van dit document.
