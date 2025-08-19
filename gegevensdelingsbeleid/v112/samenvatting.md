Dit document beschrijft de gegevenstypering van het op 24 oktober 2024 door de CIO Raad van het Ministerie van Justitie vastgestelde gegevensdelingsbeleid. Deze gegevenstypering bestaat uit de volgende onderdelen:

1. De definities van de relevante [begrippen](#begrippen) voor gegevensdeling en hun onderlinge relaties;
1. Het [conceptueel informatiemodel (CIM) van het gegevensdelingsbeleid](#cim-gegevensdelingsbeleid) met daarin een weergave van de relatie tussen het gegevensleveringsprotocol (GLP) en de gegevensleveringsspecificatie (GLS) in een gegevensdeling. Een conceptueel informatiemodel beschrijft de informatiebehoefte voor een bepaald onderwerp in termen van de relevante objecten en hun eigenschappen;
1. Het [conceptueel informatiemodel (CIM) van het gegevensleveringsprotocol (GLP)](#cim-gegevensleveringsprotocol);
1. Het [conceptueel informatiemodel (CIM) van de gegevensleveringsspecificatie (GLS)](#cim-gegevensleveringsspecificatie);
1. Het [conceptueel informatiemodel (CIM) van de in het GLS gebruikte gegevensclassificaties](#cim-gegevensclassificaties);
1. De [logische gegevensmodellen (LGM)](#logische-gegevensmodellen) van het GLP, het GLS en de gegevensclassificaties die beschrijven welke gegevens bijgehouden dienen te worden als een administratie (boekhouding) van de gegevensdeling wordt gevoerd.

**Versionering in dit document**

Het versienummer van dit document is opgebouwd conform Semantic versioning [[SemVer]]. Het versienummer geeft daarmee informatie over de status van dit document:

- Formeel bekendgemaakte en gepubliceerde versies van dit document hebben altijd een versienummer met de aanduiding "vastgestelde versie", plus een datum waarop deze versie is vastgesteld;
- Andere versies betreffen werkversies (-concept) dan wel versies ter vaststelling (-rc1, -rc2, etc), met een datum waarop de betreffende versie beschikbaar is gekomen;
- Het versienummer is opgebouwd als MAJOR.MINOR.PATCH;
- Een wijziging van het PATCH deel van het versienummer geeft aan dat een typefout of een verandering van de vorm is doorgevoerd, zonder dat sprake is van een inhoudelijke wijziging. Dergelijke PATCH wijzigingen hebben geen impact op organisaties die gebruik maken van modellen uit dit document;
- Een wijziging van het MINOR deel van het versienummer geeft aan dat een inhoudelijke wijziging of aanvulling is doorgevoerd. Dergelijke MINOR wijzigingen kunnen impact hebben op organisaties die gebruik maken van modellen uit dit document. Geadviseerd wordt om in dat geval te kijken of sprake is van een dergelijke impact en hiervoor de noodzakelijke acties uit te zetten;
- Een wijziging van het MAJOR deel van het versienummer geeft aan dat een grote inhoudelijke wijziging is doorgevoerd. Dergelijke MAJOR wijzigingen zullen een impact hebben op organisaties die gebruik maken van modellen uit dit document. Bij een dergelijke wijziging zal een reviewproces doorlopen worden, gelijk als bij de eerste oplevering van dit document.

De [veranderingen](#changes) ten opzichte van vorige versies van dit informatiemodel worden beschreven in [Appendix A](#changes).
