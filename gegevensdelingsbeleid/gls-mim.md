# CIM gegevensleveringsspecificatie

![](gegevensleveringsspecificatie.svg "Conceptueel informatiemodel gegevensleveringsspecificatie")

- [Afspraak](#TAfspraak)
  - [GLS Afspraak](#TGLS_Afspraak)
  - [Gegevensleversetspecificatie Afspraak](#TGegevensleversetspecificatie_Afspraak)
  - [Gegevensmiddelspecificatie Afspraak](#TGegevensmiddelspecificatie_Afspraak)
- [Afspraakonderwerp](#TAfspraakonderwerp)
- [Begrippenkader](#TBegrippenkader)
- [Begrippenkader omvat Term](#TBegrippenkader_omvat_Term)
- [Classificatie](#TClassificatie)
  - [Classificatie AKI-gegevens](#TClassificatie_AKI-gegevens)
  - [Classificatie BIV Beschikbaarheid](#TClassificatie_BIV_Beschikbaarheid)
  - [Classificatie BIV Integriteit](#TClassificatie_BIV_Integriteit)
  - [Classificatie BIV Vertrouwelijkheid](#TClassificatie_BIV_Vertrouwelijkheid)
  - [Classificatie Basisbeveiligingsniveau (BBN)](#TClassificatie_Basisbeveiligingsniveau__BBN_)
  - [Classificatie Gerechtelijke Strafgegevens](#TClassificatie_Gerechtelijke_Strafgegevens)
  - [Classificatie Justitiële Gegevens](#TClassificatie_Justiti_le_Gegevens)
  - [Classificatie Persoonsgegevens](#TClassificatie_Persoonsgegevens)
    - [Classificatie Bijzondere Persoonsgegevens](#TClassificatie_Bijzondere_Persoonsgegevens)
  - [Classificatie Politiegegevens](#TClassificatie_Politiegegevens)
  - [Classificatie Strafvorderlijke Gegevens](#TClassificatie_Strafvorderlijke_Gegevens)
  - [Classificatie Te Beschermen Belang](#TClassificatie_Te_Beschermen_Belang)
  - [Classificatie Tenuitvoerleggingsgegevens](#TClassificatie_Tenuitvoerleggingsgegevens)
  - [Classificatie Verantwoordingsbelang](#TClassificatie_Verantwoordingsbelang)
  - [Classificatie Vitaal Belang](#TClassificatie_Vitaal_Belang)
- [Document](#TDocument)
- [Functie in Organisatorische eenheid van Partij](#TFunctie_in_Organisatorische_eenheid_van_Partij)
- [GLS Afspraakonderwerp](#TGLS_Afspraakonderwerp)
- [GLS Rol](#TGLS_Rol)
- [GLS Standaardafspraken](#TGLS_Standaardafspraken)
- [GLS heeft Contactpersoon](#TGLS_heeft_Contactpersoon)
- [Gegevensdeling](#TGegevensdeling)
- [Gegevensleveringsprotocol](#TGegevensleveringsprotocol)
- [Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie)
- [Gegevensleversetspecificatie](#TGegevensleversetspecificatie)
- [Gegevensleversetspecificatie Afspraakonderwerp](#TGegevensleversetspecificatie_Afspraakonderwerp)
- [Gegevensmiddelspecificatie](#TGegevensmiddelspecificatie)
- [Gegevensmiddelspecificatie Afspraakonderwerp](#TGegevensmiddelspecificatie_Afspraakonderwerp)
- [Gegevenstype](#TGegevenstype)
  - [Gegevenstype categorisch](#TGegevenstype_categorisch)
- [Gegevensveld](#TGegevensveld)
- [Geregistreerd Algoritme](#TGeregistreerd_Algoritme)
- [Logisch Gegevensmodel](#TLogisch_Gegevensmodel)
- [Partij](#TPartij)
- [Persoon](#TPersoon)
- [Persoon in Functie](#TPersoon_in_Functie)
- [Technisch Gegevensmodel](#TTechnisch_Gegevensmodel)
- [Verwerkersovereenkomst](#TVerwerkersovereenkomst)

## Afspraak {#TAfspraak}

|{: .def}||
|-|-|
|Begrip|[Afspraak](#afspraak)|
|Subtype(s)|[Gegevensmiddelspecificatie Afspraak](#TGegevensmiddelspecificatie_Afspraak), [Gegevensleversetspecificatie Afspraak](#TGegevensleversetspecificatie_Afspraak), [GLS Afspraak](#TGLS_Afspraak)|
|Toelichting|afspraak [afspraaknaam]() bestaat;<br/>[afspraaknaam]()|
|Kenmerken|[Afspraak Beschrijving](#TAfspraak_Beschrijving), [afspraaknaam](#TAfspraakafspraaknaam)|
|Relatie met|[Afspraak over Afspraakonderwerp](#TAfspraak_over_Afspraakonderwerp), [Afspraken in GLS Standaardafspraken](#TAfspraken_in_GLS_Standaardafspraken)|

### Afspraak Beschrijving {#TAfspraak_Beschrijving}

|{: .def}||
|-|-|
|Toelichting|[Afspraak](#TAfspraak) is: [afspraakbeschrijving]()|
|Eigenschap van|[Afspraak](#TAfspraak)|
|Type|[afspraakbeschrijving](#Tafspraakbeschrijving)|

### afspraaknaam {#TAfspraakafspraaknaam}

|{: .def}||
|-|-|
|Eigenschap van|[Afspraak](#TAfspraak)|
|Type|CharacterString|

## Afspraakonderwerp {#TAfspraakonderwerp}

|{: .def}||
|-|-|
|Toelichting|[afspraakonderwerpbeschrijving]();<br/>We kunnen afspraken maken over [afspraakonderwerpbeschrijving]()|
|Kenmerken|[afspraakonderwerpbeschrijving](#TAfspraakonderwerpafspraakonderwerpbeschrijving)|
|Rollen|[Afspraak over Afspraakonderwerp](#TAfspraak_over_Afspraakonderwerp)|

### afspraakonderwerpbeschrijving {#TAfspraakonderwerpafspraakonderwerpbeschrijving}

|{: .def}||
|-|-|
|Eigenschap van|[Afspraakonderwerp](#TAfspraakonderwerp)|
|Type|CharacterString|

### Afspraak over Afspraakonderwerp {#TAfspraak_over_Afspraakonderwerp}

|{: .def}||
|-|-|
|Toelichting|[Afspraak](#TAfspraak) over [Afspraakonderwerp](#TAfspraakonderwerp)|
|Rol van|1..1 [Afspraakonderwerp](#TAfspraakonderwerp)|
|Met|0..1 [Afspraak](#TAfspraak)|

## Begrippenkader {#TBegrippenkader}

|{: .def}||
|-|-|
|Begrip|[Begrippenkader](#begrippenkader)|
|Toelichting|[begrippenkadercode]()|
|Kenmerken|[begrippenkadercode](#TBegrippenkaderbegrippenkadercode)|
|Relatie met|[Begrippenkader](#TBegrippenkader_omvat_TermBegrippenkader), [GLS Begrippenkader](#TGLS_Begrippenkader)|

### begrippenkadercode {#TBegrippenkaderbegrippenkadercode}

|{: .def}||
|-|-|
|Eigenschap van|[Begrippenkader](#TBegrippenkader)|
|Type|CharacterString|

## Begrippenkader omvat Term {#TBegrippenkader_omvat_Term}

|{: .def}||
|-|-|
|Toelichting|begrippenkader [Begrippenkader](#TBegrippenkader) definieert Term [termnaam]()|
|Kenmerken|[Term beschrijving](#TTerm_beschrijving), [termnaam](#TBegrippenkader_omvat_Termtermnaam)|
|Rollen|[Begrippenkader](#TBegrippenkader_omvat_TermBegrippenkader), [Term bij Gegevenstype](#TTerm_bij_Gegevenstype)|

### Term beschrijving {#TTerm_beschrijving}

|{: .def}||
|-|-|
|Toelichting|[Begrippenkader omvat Term](#TBegrippenkader_omvat_Term) met termbeschrijving [Termbeschrijving]()|
|Eigenschap van|[Begrippenkader omvat Term](#TBegrippenkader_omvat_Term)|
|Type|[Termbeschrijving](#TTermbeschrijving)|

### termnaam {#TBegrippenkader_omvat_Termtermnaam}

|{: .def}||
|-|-|
|Eigenschap van|[Begrippenkader omvat Term](#TBegrippenkader_omvat_Term)|
|Type|CharacterString|

### Begrippenkader {#TBegrippenkader_omvat_TermBegrippenkader}

|{: .def}||
|-|-|
|Begrip|[Begrippenkader](#begrippenkader)|
|Rol van|1..* [Begrippenkader omvat Term](#TBegrippenkader_omvat_Term)|
|Met| [Begrippenkader](#TBegrippenkader)|

### Term bij Gegevenstype {#TTerm_bij_Gegevenstype}

|{: .def}||
|-|-|
|Toelichting|[Begrippenkader omvat Term](#TBegrippenkader_omvat_Term) behorende bij [Gegevenstype](#TGegevenstype)|
|Rol van|1..1 [Begrippenkader omvat Term](#TBegrippenkader_omvat_Term)|
|Met|0..1 [Gegevenstype](#TGegevenstype)|

## Classificatie {#TClassificatie}

|{: .def}||
|-|-|
|Begrip|[Classificatie](#classificatie)|
|Subtype(s)|[Classificatie Strafvorderlijke Gegevens](#TClassificatie_Strafvorderlijke_Gegevens), [Classificatie Vitaal Belang](#TClassificatie_Vitaal_Belang), [Classificatie Te Beschermen Belang](#TClassificatie_Te_Beschermen_Belang), [Classificatie Verantwoordingsbelang](#TClassificatie_Verantwoordingsbelang), [Classificatie Gerechtelijke Strafgegevens](#TClassificatie_Gerechtelijke_Strafgegevens), [Classificatie Tenuitvoerleggingsgegevens](#TClassificatie_Tenuitvoerleggingsgegevens), [Classificatie BIV Beschikbaarheid](#TClassificatie_BIV_Beschikbaarheid), [Classificatie Politiegegevens](#TClassificatie_Politiegegevens), [Classificatie BIV Integriteit](#TClassificatie_BIV_Integriteit), [Classificatie Persoonsgegevens](#TClassificatie_Persoonsgegevens), [Classificatie Basisbeveiligingsniveau (BBN)](#TClassificatie_Basisbeveiligingsniveau__BBN_), [Classificatie Justitiële Gegevens](#TClassificatie_Justiti_le_Gegevens), [Classificatie BIV Vertrouwelijkheid](#TClassificatie_BIV_Vertrouwelijkheid), [Classificatie AKI-gegevens](#TClassificatie_AKI-gegevens)|
|Toelichting|classificatie [classificatie id]() bestaat|
|Kenmerken|[Classificatie heeft classificatietype](#TClassificatie_heeft_classificatietype), [classificatie id](#TClassificatieclassificatie_id)|
|Relatie met|[GLS heeft Classificatie](#TGLS_heeft_Classificatie), [Gegevensleversetspecificatie heeft Classificatie](#TGegevensleversetspecificatie_heeft_Classificatie), [Gegevenstype heeft Classificatie](#TGegevenstype_heeft_Classificatie)|

### classificatie id {#TClassificatieclassificatie_id}

|{: .def}||
|-|-|
|Eigenschap van|[Classificatie](#TClassificatie)|
|Type|CharacterString|

### Classificatie heeft classificatietype {#TClassificatie_heeft_classificatietype}

|{: .def}||
|-|-|
|Toelichting|[Classificatie](#TClassificatie) is een [classificatietypenaam]()|
|Eigenschap van|[Classificatie](#TClassificatie)|
|Type|[classificatietypenaam](#Tclassificatietypenaam)|

## Classificatie AKI-gegevens {#TClassificatie_AKI-gegevens}

|{: .def}||
|-|-|
|Supertype|[Classificatie](#TClassificatie)|
|Toelichting|Classificatie AKI-gegevens [Classificatie](#TClassificatie)|
|Kenmerken|[Classificatie AKI-gegevens waarde](#TClassificatie_AKI-gegevens_waarde)|
|Rollen|[Bij AKI-Classificatie hoort Geregistreerd Algoritme](#TBij_AKI-Classificatie_hoort_Geregistreerd_Algoritme)|

### Classificatie AKI-gegevens waarde {#TClassificatie_AKI-gegevens_waarde}

|{: .def}||
|-|-|
|Toelichting|[Classificatie AKI-gegevens](#TClassificatie_AKI-gegevens) heeft waarde [classificatie_akigegevens_waarde]()|
|Eigenschap van|[Classificatie AKI-gegevens](#TClassificatie_AKI-gegevens)|
|Type|[classificatie_akigegevens_waarde](#Tclassificatie_akigegevens_waarde)|
|Mogelijke waarden|bevat geen gegevens die uit algoritmen afkomstig zijn; bevat gegevens die op basis van regels zijn afgeleid; ja, minimaal risico; ja, beperkt risico; ja, hoog risico; ja, onaanvaardbaar risico|

### Bij AKI-Classificatie hoort Geregistreerd Algoritme {#TBij_AKI-Classificatie_hoort_Geregistreerd_Algoritme}

|{: .def}||
|-|-|
|Toelichting|[Classificatie AKI-gegevens](#TClassificatie_AKI-gegevens) en heeft een geregistreerd algoritme [Geregistreerd Algoritme](#TGeregistreerd_Algoritme)|
|Rol van|1..1 [Classificatie AKI-gegevens](#TClassificatie_AKI-gegevens)|
|Met|0..1 [Geregistreerd Algoritme](#TGeregistreerd_Algoritme)|

## Classificatie BIV Beschikbaarheid {#TClassificatie_BIV_Beschikbaarheid}

|{: .def}||
|-|-|
|Supertype|[Classificatie](#TClassificatie)|
|Toelichting|Classificatie BIV Beschikbaarheid [Classificatie](#TClassificatie)|
|Kenmerken|[Classificatie BIV Beschikbaarheid waarde](#TClassificatie_BIV_Beschikbaarheid_waarde)|

### Classificatie BIV Beschikbaarheid waarde {#TClassificatie_BIV_Beschikbaarheid_waarde}

|{: .def}||
|-|-|
|Toelichting|[Classificatie BIV Beschikbaarheid](#TClassificatie_BIV_Beschikbaarheid) heeft waarde [classificatie_biv_beschikbaarheid_waarde]()|
|Eigenschap van|[Classificatie BIV Beschikbaarheid](#TClassificatie_BIV_Beschikbaarheid)|
|Type|[classificatie_biv_beschikbaarheid_waarde](#Tclassificatie_biv_beschikbaarheid_waarde)|
|Mogelijke waarden|laag -1; hoog-3; midden-2|

## Classificatie BIV Integriteit {#TClassificatie_BIV_Integriteit}

|{: .def}||
|-|-|
|Supertype|[Classificatie](#TClassificatie)|
|Toelichting|Classificatie BIV Integriteit [Classificatie](#TClassificatie)|
|Kenmerken|[Classificatie BIV Integriteit waarde](#TClassificatie_BIV_Integriteit_waarde)|

### Classificatie BIV Integriteit waarde {#TClassificatie_BIV_Integriteit_waarde}

|{: .def}||
|-|-|
|Toelichting|[Classificatie BIV Integriteit](#TClassificatie_BIV_Integriteit) heeft waarde [classificatie_biv_integriteit_waarde]()|
|Eigenschap van|[Classificatie BIV Integriteit](#TClassificatie_BIV_Integriteit)|
|Type|[classificatie_biv_integriteit_waarde](#Tclassificatie_biv_integriteit_waarde)|
|Mogelijke waarden|laag-1; midden-2; hoog-3|

## Classificatie BIV Vertrouwelijkheid {#TClassificatie_BIV_Vertrouwelijkheid}

|{: .def}||
|-|-|
|Supertype|[Classificatie](#TClassificatie)|
|Toelichting|Classificatie BIV Vertrouwelijkheid [Classificatie](#TClassificatie)|
|Kenmerken|[Classificatie BIV Vertrouwelijkheid waarde](#TClassificatie_BIV_Vertrouwelijkheid_waarde)|

### Classificatie BIV Vertrouwelijkheid waarde {#TClassificatie_BIV_Vertrouwelijkheid_waarde}

|{: .def}||
|-|-|
|Toelichting|[Classificatie BIV Vertrouwelijkheid](#TClassificatie_BIV_Vertrouwelijkheid) heeft waarde [classificatie_biv_vertrouwelijkheid_waarde]()|
|Eigenschap van|[Classificatie BIV Vertrouwelijkheid](#TClassificatie_BIV_Vertrouwelijkheid)|
|Type|[classificatie_biv_vertrouwelijkheid_waarde](#Tclassificatie_biv_vertrouwelijkheid_waarde)|
|Mogelijke waarden|midden-2; laag-1; hoog-3|

## Classificatie Basisbeveiligingsniveau (BBN) {#TClassificatie_Basisbeveiligingsniveau__BBN_}

|{: .def}||
|-|-|
|Supertype|[Classificatie](#TClassificatie)|
|Toelichting|Classificatie Vastgesteld Basisbeveiligingsniveau (BBN) [Classificatie](#TClassificatie)|
|Kenmerken|[Classificatie Basisbeveiligingsniveau (BBN) waarde](#TClassificatie_Basisbeveiligingsniveau__BBN__waarde)|

### Classificatie Basisbeveiligingsniveau (BBN) waarde {#TClassificatie_Basisbeveiligingsniveau__BBN__waarde}

|{: .def}||
|-|-|
|Toelichting|[Classificatie Basisbeveiligingsniveau (BBN)](#TClassificatie_Basisbeveiligingsniveau__BBN_) heeft waarde [classificatie_bbn_waarde]()|
|Eigenschap van|[Classificatie Basisbeveiligingsniveau (BBN)](#TClassificatie_Basisbeveiligingsniveau__BBN_)|
|Type|[classificatie_bbn_waarde](#Tclassificatie_bbn_waarde)|
|Mogelijke waarden|BBN2; BBN3; BBN1|

## Classificatie Bijzondere Persoonsgegevens {#TClassificatie_Bijzondere_Persoonsgegevens}

|{: .def}||
|-|-|
|Supertype|[Classificatie Persoonsgegevens](#TClassificatie_Persoonsgegevens)|
|Toelichting|classificatie Bijzondere Persoonsgegevens [Classificatie Persoonsgegevens](#TClassificatie_Persoonsgegevens);<br/>Classificatie Bijzondere Persoonsgegevens [Classificatie Persoonsgegevens](#TClassificatie_Persoonsgegevens)|
|Kenmerken|[Classificatie Bijzondere Persoonsgegevens waarde](#TClassificatie_Bijzondere_Persoonsgegevens_waarde)|

### Classificatie Bijzondere Persoonsgegevens waarde {#TClassificatie_Bijzondere_Persoonsgegevens_waarde}

|{: .def}||
|-|-|
|Toelichting|[Classificatie Bijzondere Persoonsgegevens](#TClassificatie_Bijzondere_Persoonsgegevens) bevat [classificatie_bpg_waarde]()|
|Eigenschap van|[Classificatie Bijzondere Persoonsgegevens](#TClassificatie_Bijzondere_Persoonsgegevens)|
|Type|[classificatie_bpg_waarde](#Tclassificatie_bpg_waarde)|
|Mogelijke waarden|biometrische gegevens met het oog op de unieke identificatie van een persoon; genetische gegevens; gegevens over politieke opvattingen; gegevens over ras of etnische afkomst; gegevens over religieuze of levensbeschouwelijke overtuigingen; gegevens over gezondheid; gegevens over lidmaatschap van een vakbond; gegevens over iemands seksueel gedrag of seksuele gerichtheid|

## Classificatie Gerechtelijke Strafgegevens {#TClassificatie_Gerechtelijke_Strafgegevens}

|{: .def}||
|-|-|
|Supertype|[Classificatie](#TClassificatie)|
|Toelichting|Classificatie Gerechtelijke Strafgegevens [Classificatie](#TClassificatie)|
|Kenmerken|[Classificatie Gerechtelijke Strafgegevens Waarde](#TClassificatie_Gerechtelijke_Strafgegevens_Waarde)|

### Classificatie Gerechtelijke Strafgegevens Waarde {#TClassificatie_Gerechtelijke_Strafgegevens_Waarde}

|{: .def}||
|-|-|
|Toelichting|[Classificatie Gerechtelijke Strafgegevens](#TClassificatie_Gerechtelijke_Strafgegevens)  [classificatie_gerechtelijkestrafgegevens_waarde]()|
|Eigenschap van|[Classificatie Gerechtelijke Strafgegevens](#TClassificatie_Gerechtelijke_Strafgegevens)|
|Type|[classificatie_gerechtelijkestrafgegevens_waarde](#Tclassificatie_gerechtelijkestrafgegevens_waarde)|
|Mogelijke waarden|bevat gerechtelijke strafgegevens; bevat geen gerechtelijke strafgegevens|

## Classificatie Justitiële Gegevens {#TClassificatie_Justiti_le_Gegevens}

|{: .def}||
|-|-|
|Supertype|[Classificatie](#TClassificatie)|
|Toelichting|Classificatie Justitie- en Strafvordelijke gegevens [Classificatie](#TClassificatie)|
|Kenmerken|[Classificatie Justitiële Gegevens waarde](#TClassificatie_Justiti_le_Gegevens_waarde)|

### Classificatie Justitiële Gegevens waarde {#TClassificatie_Justiti_le_Gegevens_waarde}

|{: .def}||
|-|-|
|Toelichting|[Classificatie Justitiële Gegevens](#TClassificatie_Justiti_le_Gegevens)  [classificatie_justitiegegevens_waarde]()|
|Eigenschap van|[Classificatie Justitiële Gegevens](#TClassificatie_Justiti_le_Gegevens)|
|Type|[classificatie_justitiegegevens_waarde](#Tclassificatie_justitiegegevens_waarde)|
|Mogelijke waarden|bevat geen justitiële gegevens; bevat justitiële gegevens|

## Classificatie Persoonsgegevens {#TClassificatie_Persoonsgegevens}

|{: .def}||
|-|-|
|Supertype|[Classificatie](#TClassificatie)|
|Subtype(s)|[Classificatie Bijzondere Persoonsgegevens](#TClassificatie_Bijzondere_Persoonsgegevens)|
|Toelichting|Classificatie Persoonsgegevens [Classificatie](#TClassificatie)|
|Kenmerken|[Classificatie Persoonsgegevens Waarde](#TClassificatie_Persoonsgegevens_Waarde)|

### Classificatie Persoonsgegevens Waarde {#TClassificatie_Persoonsgegevens_Waarde}

|{: .def}||
|-|-|
|Toelichting|[Classificatie Persoonsgegevens](#TClassificatie_Persoonsgegevens) heeft waarde [classificatie_pg_waarde]()|
|Eigenschap van|[Classificatie Persoonsgegevens](#TClassificatie_Persoonsgegevens)|
|Type|[classificatie_pg_waarde](#Tclassificatie_pg_waarde)|
|Mogelijke waarden|bevat geen persoonsgegevens; bevat wettelijk identificatienummer; bevat gevoelige persoonsgegevens; bevat bijzondere persoonsgegevens; bevat strafrechtelijke persoonsgegevens; bevat gewone persoonsgegeven|

## Classificatie Politiegegevens {#TClassificatie_Politiegegevens}

|{: .def}||
|-|-|
|Supertype|[Classificatie](#TClassificatie)|
|Toelichting|Classificatie Politiegegevens [Classificatie](#TClassificatie)|
|Kenmerken|[Classificatie Politiegegevens Waarde](#TClassificatie_Politiegegevens_Waarde)|

### Classificatie Politiegegevens Waarde {#TClassificatie_Politiegegevens_Waarde}

|{: .def}||
|-|-|
|Toelichting|[Classificatie Politiegegevens](#TClassificatie_Politiegegevens) heeft waarde [classificatie_politiegegevens_waarde]()|
|Eigenschap van|[Classificatie Politiegegevens](#TClassificatie_Politiegegevens)|
|Type|[classificatie_politiegegevens_waarde](#Tclassificatie_politiegegevens_waarde)|
|Mogelijke waarden|bevat geen politiegegevens; bevat politiegegevens|

## Classificatie Strafvorderlijke Gegevens {#TClassificatie_Strafvorderlijke_Gegevens}

|{: .def}||
|-|-|
|Supertype|[Classificatie](#TClassificatie)|
|Toelichting|Classificatie Strafvorderlijke Gegevens [Classificatie](#TClassificatie)|
|Kenmerken|[Classificatie Strafvorderlijke Gegevens waarde](#TClassificatie_Strafvorderlijke_Gegevens_waarde)|

### Classificatie Strafvorderlijke Gegevens waarde {#TClassificatie_Strafvorderlijke_Gegevens_waarde}

|{: .def}||
|-|-|
|Toelichting|[Classificatie Strafvorderlijke Gegevens](#TClassificatie_Strafvorderlijke_Gegevens)  [classificatie_strafvorderlijkegegevens_waarde]()|
|Eigenschap van|[Classificatie Strafvorderlijke Gegevens](#TClassificatie_Strafvorderlijke_Gegevens)|
|Type|[classificatie_strafvorderlijkegegevens_waarde](#Tclassificatie_strafvorderlijkegegevens_waarde)|
|Mogelijke waarden|bevat strafvorderlijke gegevens; bevat geen strafvorderlijke gegevens|

## Classificatie Te Beschermen Belang {#TClassificatie_Te_Beschermen_Belang}

|{: .def}||
|-|-|
|Supertype|[Classificatie](#TClassificatie)|
|Toelichting|Classificatie Te Beschermen Belang [Classificatie](#TClassificatie)|
|Kenmerken|[Classificatie Te Beschermen Belang waarde](#TClassificatie_Te_Beschermen_Belang_waarde)|

### Classificatie Te Beschermen Belang waarde {#TClassificatie_Te_Beschermen_Belang_waarde}

|{: .def}||
|-|-|
|Toelichting|[Classificatie Te Beschermen Belang](#TClassificatie_Te_Beschermen_Belang) heeft waarde [classificatie_tbb_waarde]()|
|Eigenschap van|[Classificatie Te Beschermen Belang](#TClassificatie_Te_Beschermen_Belang)|
|Type|[classificatie_tbb_waarde](#Tclassificatie_tbb_waarde)|
|Mogelijke waarden|geheim – staatsgeheim ZEER GEHEIM; geheim – staatsgeheim CONFIDENTIEEL; intern; geheim – staatsgeheim GEHEIM; openbaar; geheim – departementaal VERTROUWELIJK; vertrouwelijk|

## Classificatie Tenuitvoerleggingsgegevens {#TClassificatie_Tenuitvoerleggingsgegevens}

|{: .def}||
|-|-|
|Supertype|[Classificatie](#TClassificatie)|
|Toelichting|Classificatie Tenuitvoerleggingsgegevens [Classificatie](#TClassificatie)|
|Kenmerken|[Classificatie Tenuitvoerleggingsgegevens Waarde](#TClassificatie_Tenuitvoerleggingsgegevens_Waarde)|

### Classificatie Tenuitvoerleggingsgegevens Waarde {#TClassificatie_Tenuitvoerleggingsgegevens_Waarde}

|{: .def}||
|-|-|
|Toelichting|[Classificatie Tenuitvoerleggingsgegevens](#TClassificatie_Tenuitvoerleggingsgegevens)  [classificatie_tenuitvoerleggingsgegevens_waarde]()|
|Eigenschap van|[Classificatie Tenuitvoerleggingsgegevens](#TClassificatie_Tenuitvoerleggingsgegevens)|
|Type|[classificatie_tenuitvoerleggingsgegevens_waarde](#Tclassificatie_tenuitvoerleggingsgegevens_waarde)|
|Mogelijke waarden|bevat geen tenuitvoerleggingsgegevens; bevat tenuitvoerleggingsgegevens|

## Classificatie Verantwoordingsbelang {#TClassificatie_Verantwoordingsbelang}

|{: .def}||
|-|-|
|Supertype|[Classificatie](#TClassificatie)|
|Toelichting|Classificatie Verantwoordingsbelang [Classificatie](#TClassificatie)|
|Kenmerken|[Classificatie Verantwoordingsbelang waarde](#TClassificatie_Verantwoordingsbelang_waarde)|

### Classificatie Verantwoordingsbelang waarde {#TClassificatie_Verantwoordingsbelang_waarde}

|{: .def}||
|-|-|
|Toelichting|[Classificatie Verantwoordingsbelang](#TClassificatie_Verantwoordingsbelang) heeft waarde [classificatie_verantwoordingsbelang_waarde]()|
|Eigenschap van|[Classificatie Verantwoordingsbelang](#TClassificatie_Verantwoordingsbelang)|
|Type|[classificatie_verantwoordingsbelang_waarde](#Tclassificatie_verantwoordingsbelang_waarde)|
|Mogelijke waarden|ja, de termijn is afhankelijk van de context; ja, moet blijvend worden bewaard; ja, moet tijdelijk worden bewaard; geen verantwoordingsbelang|

## Classificatie Vitaal Belang {#TClassificatie_Vitaal_Belang}

|{: .def}||
|-|-|
|Supertype|[Classificatie](#TClassificatie)|
|Toelichting|Classificatie Vitaal Belang [Classificatie](#TClassificatie)|
|Kenmerken|[Classificatie Vitaal Belang waarde](#TClassificatie_Vitaal_Belang_waarde)|

### Classificatie Vitaal Belang waarde {#TClassificatie_Vitaal_Belang_waarde}

|{: .def}||
|-|-|
|Toelichting|[Classificatie Vitaal Belang](#TClassificatie_Vitaal_Belang) heeft waarde [classificatie_vitaalbelang_waarde]()|
|Eigenschap van|[Classificatie Vitaal Belang](#TClassificatie_Vitaal_Belang)|
|Type|[classificatie_vitaalbelang_waarde](#Tclassificatie_vitaalbelang_waarde)|
|Mogelijke waarden|een vitaal belang; geen vitaal belang|

## Document {#TDocument}

|{: .def}||
|-|-|
|Begrip|[Document](#document)|
|Toelichting|[documentcode]()|
|Kenmerken|[Document Locatie](#TDocument_Locatie), [Document Naam](#TDocument_Naam), [Document Soort](#TDocument_Soort), [Document Versie](#TDocument_Versie), [documentcode](#TDocumentdocumentcode)|
|Rollen|[Document Auteur](#TDocument_Auteur)|
|Relatie met|[GLS Standaardafspraken vastgelegd in Document](#TGLS_Standaardafspraken_vastgelegd_in_Document), [GLS Standaardmodel Document](#TGLS_Standaardmodel_Document), [GLS heeft gerelateerd Document](#TGLS_heeft_gerelateerd_Document)|

### documentcode {#TDocumentdocumentcode}

|{: .def}||
|-|-|
|Eigenschap van|[Document](#TDocument)|
|Type|CharacterString|

### Document Locatie {#TDocument_Locatie}

|{: .def}||
|-|-|
|Toelichting|de locatie van document [Document](#TDocument) is [locatie]()|
|Eigenschap van|[Document](#TDocument)|
|Type|[locatie](#Tlocatie)|

### Document Soort {#TDocument_Soort}

|{: .def}||
|-|-|
|Toelichting|[Document](#TDocument) is van het soort [documentsoort]()|
|Eigenschap van|[Document](#TDocument)|
|Type|[documentsoort](#Tdocumentsoort)|

### Document Versie {#TDocument_Versie}

|{: .def}||
|-|-|
|Toelichting|[Document](#TDocument) heeft versienummer [versienummer]()|
|Eigenschap van|[Document](#TDocument)|
|Type|[versienummer](#Tversienummer)|

### Document Naam {#TDocument_Naam}

|{: .def}||
|-|-|
|Toelichting|document [Document](#TDocument) heet [naam]()|
|Eigenschap van|[Document](#TDocument)|
|Type|[naam](#Tnaam)|

### Document Auteur {#TDocument_Auteur}

|{: .def}||
|-|-|
|Toelichting|document [Document](#TDocument) heeft auteur [Persoon](#TPersoon)|
|Rol van|1..* [Document](#TDocument)|
|Met|0..* [Persoon](#TPersoon)|

## Functie in Organisatorische eenheid van Partij {#TFunctie_in_Organisatorische_eenheid_van_Partij}

|{: .def}||
|-|-|
|Toelichting|[functie]() in [organisatorische eenheid]() binnen [Partij](#TPartij)|
|Kenmerken|[functie](#TFunctie_in_Organisatorische_eenheid_van_Partijfunctie), [organisatorische eenheid](#TFunctie_in_Organisatorische_eenheid_van_Partijorganisatorische_eenheid)|
|Rollen|[Partij](#TFunctie_in_Organisatorische_eenheid_van_PartijPartij)|
|Relatie met|[Functie in Organisatorische eenheid van Partij](#TPersoon_in_FunctieFunctie_in_Organisatorische_eenheid_van_Partij)|

### organisatorische eenheid {#TFunctie_in_Organisatorische_eenheid_van_Partijorganisatorische_eenheid}

|{: .def}||
|-|-|
|Begrip|[Organisatorische eenheid](#organisatorische-eenheid)|
|Eigenschap van|[Functie in Organisatorische eenheid van Partij](#TFunctie_in_Organisatorische_eenheid_van_Partij)|
|Type|CharacterString|

### functie {#TFunctie_in_Organisatorische_eenheid_van_Partijfunctie}

|{: .def}||
|-|-|
|Begrip|[Functie](#functie)|
|Eigenschap van|[Functie in Organisatorische eenheid van Partij](#TFunctie_in_Organisatorische_eenheid_van_Partij)|
|Type|CharacterString|

### Partij {#TFunctie_in_Organisatorische_eenheid_van_PartijPartij}

|{: .def}||
|-|-|
|Begrip|[Partij](#partij)|
|Rol van|0..* 0..* [Functie in Organisatorische eenheid van Partij](#TFunctie_in_Organisatorische_eenheid_van_Partij)|
|Met| [Partij](#TPartij)|

## GLS Afspraak {#TGLS_Afspraak}

|{: .def}||
|-|-|
|Supertype|[Afspraak](#TAfspraak)|
|Toelichting|GLS Afspraak [Afspraak](#TAfspraak)|
|Rollen|[GLS Afspraak over GLS Afspraakonderwerp](#TGLS_Afspraak_over_GLS_Afspraakonderwerp)|
|Relatie met|[GLS heeft extra Afspraak](#TGLS_heeft_extra_Afspraak)|

### GLS Afspraak over GLS Afspraakonderwerp {#TGLS_Afspraak_over_GLS_Afspraakonderwerp}

|{: .def}||
|-|-|
|Toelichting|[GLS Afspraak](#TGLS_Afspraak) over [GLS Afspraakonderwerp](#TGLS_Afspraakonderwerp)|
|Rol van|0..1 [GLS Afspraak](#TGLS_Afspraak)|
|Met|1..1 [GLS Afspraakonderwerp](#TGLS_Afspraakonderwerp)|

## GLS Afspraakonderwerp {#TGLS_Afspraakonderwerp}

|{: .def}||
|-|-|
|Toelichting|[glsafspraakonderwerpbeschrijving]();<br/>We kunnen afspraken maken over [glsafspraakonderwerpbeschrijving]()|
|Kenmerken|[glsafspraakonderwerpbeschrijving](#TGLS_Afspraakonderwerpglsafspraakonderwerpbeschrijving)|
|Relatie met|[GLS Afspraak over GLS Afspraakonderwerp](#TGLS_Afspraak_over_GLS_Afspraakonderwerp)|

### glsafspraakonderwerpbeschrijving {#TGLS_Afspraakonderwerpglsafspraakonderwerpbeschrijving}

|{: .def}||
|-|-|
|Eigenschap van|[GLS Afspraakonderwerp](#TGLS_Afspraakonderwerp)|
|Type|CharacterString|

## GLS Rol {#TGLS_Rol}

|{: .def}||
|-|-|
|Toelichting|[gls_rolnaam]()|
|Kenmerken|[gls_rolnaam](#TGLS_Rolgls_rolnaam)|
|Relatie met|[GLS heeft Contactpersoon in Rol](#TGLS_heeft_Contactpersoon_in_Rol)|

### gls_rolnaam {#TGLS_Rolgls_rolnaam}

|{: .def}||
|-|-|
|Eigenschap van|[GLS Rol](#TGLS_Rol)|
|Type|CharacterString|

## GLS Standaardafspraken {#TGLS_Standaardafspraken}

|{: .def}||
|-|-|
|Begrip|[GLS Standaardafspraken](#gls-standaardafspraken)|
|Toelichting|Afspraken bekend als code [glsstandaardafsprakencode]()|
|Kenmerken|[GLS Standaardafspraken Versiegeschiedenis](#TGLS_Standaardafspraken_Versiegeschiedenis), [glsstandaardafsprakencode](#TGLS_Standaardafsprakenglsstandaardafsprakencode)|
|Rollen|[Afspraken in GLS Standaardafspraken](#TAfspraken_in_GLS_Standaardafspraken), [GLS Standaardafspraken vastgelegd in Document](#TGLS_Standaardafspraken_vastgelegd_in_Document)|
|Relatie met|[GLS heeft GLS Standaardafspraken](#TGLS_heeft_GLS_Standaardafspraken)|

### glsstandaardafsprakencode {#TGLS_Standaardafsprakenglsstandaardafsprakencode}

|{: .def}||
|-|-|
|Eigenschap van|[GLS Standaardafspraken](#TGLS_Standaardafspraken)|
|Type|CharacterString|

### GLS Standaardafspraken Versiegeschiedenis {#TGLS_Standaardafspraken_Versiegeschiedenis}

|{: .def}||
|-|-|
|Toelichting|[GLS Standaardafspraken](#TGLS_Standaardafspraken) versie [versienummer]()|
|Eigenschap van|[GLS Standaardafspraken](#TGLS_Standaardafspraken)|
|Type|[versienummer](#Tversienummer)|

### Afspraken in GLS Standaardafspraken {#TAfspraken_in_GLS_Standaardafspraken}

|{: .def}||
|-|-|
|Toelichting|[GLS Standaardafspraken](#TGLS_Standaardafspraken) bevat [Afspraak](#TAfspraak)|
|Rol van|0..* [GLS Standaardafspraken](#TGLS_Standaardafspraken)|
|Met|1..* [Afspraak](#TAfspraak)|

### GLS Standaardafspraken vastgelegd in Document {#TGLS_Standaardafspraken_vastgelegd_in_Document}

|{: .def}||
|-|-|
|Toelichting|[GLS Standaardafspraken](#TGLS_Standaardafspraken) worden vastgelegd in [Document](#TDocument)|
|Rol van|0..1 [GLS Standaardafspraken](#TGLS_Standaardafspraken)|
|Met|1..1 [Document](#TDocument)|

## GLS heeft Contactpersoon {#TGLS_heeft_Contactpersoon}

|{: .def}||
|-|-|
|Toelichting|Contactpersoon  voor [Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie) is [Persoon in Functie](#TPersoon_in_Functie)|
|Rollen|[GLS heeft Contactpersoon in Rol](#TGLS_heeft_Contactpersoon_in_Rol), [Gegevensleveringsspecificatie](#TGLS_heeft_ContactpersoonGegevensleveringsspecificatie), [Persoon in Functie](#TGLS_heeft_ContactpersoonPersoon_in_Functie)|

### Persoon in Functie {#TGLS_heeft_ContactpersoonPersoon_in_Functie}

|{: .def}||
|-|-|
|Rol van|0..* [GLS heeft Contactpersoon](#TGLS_heeft_Contactpersoon)|
|Met| [Persoon in Functie](#TPersoon_in_Functie)|

### Gegevensleveringsspecificatie {#TGLS_heeft_ContactpersoonGegevensleveringsspecificatie}

|{: .def}||
|-|-|
|Begrip|[Gegevensleveringsspecificatie](#gegevensleveringsspecificatie)|
|Rol van|1..* [GLS heeft Contactpersoon](#TGLS_heeft_Contactpersoon)|
|Met| [Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie)|

### GLS heeft Contactpersoon in Rol {#TGLS_heeft_Contactpersoon_in_Rol}

|{: .def}||
|-|-|
|Toelichting|[GLS heeft Contactpersoon](#TGLS_heeft_Contactpersoon) in rol [GLS Rol](#TGLS_Rol)|
|Rol van|0..1 [GLS heeft Contactpersoon](#TGLS_heeft_Contactpersoon)|
|Met|1..1 [GLS Rol](#TGLS_Rol)|

## Gegevensdeling {#TGegevensdeling}

|{: .def}||
|-|-|
|Begrip|[Gegevensdeling](#gegevensdeling)|
|Toelichting|gegevensdeling met gegevensdelingscode [gegevensdelingscode]();<br/>gegevensdeling met gegevensdelingscode [gegevensdelingscode]() bestaat|
|Kenmerken|[gegevensdelingscode](#TGegevensdelinggegevensdelingscode)|
|Relatie met|[GLP voor Gegevensdeling](#TGLP_voor_Gegevensdeling), [Verwerkersovereenkomst voor Gegevensdeling](#TVerwerkersovereenkomst_voor_Gegevensdeling)|

### gegevensdelingscode {#TGegevensdelinggegevensdelingscode}

|{: .def}||
|-|-|
|Eigenschap van|[Gegevensdeling](#TGegevensdeling)|
|Type|CharacterString|

## Gegevensleveringsprotocol {#TGegevensleveringsprotocol}

|{: .def}||
|-|-|
|Begrip|[Gegevensleveringsprotocol](#gegevensleveringsprotocol)|
|Toelichting|[glp-code]();<br/>er is een GLP met GLP-code [glp-code]()|
|Kenmerken|[glp-code](#TGegevensleveringsprotocolglp-code)|
|Rollen|[GLP voor Gegevensdeling](#TGLP_voor_Gegevensdeling)|
|Relatie met|[GLS hoort bij GLP](#TGLS_hoort_bij_GLP)|

### glp-code {#TGegevensleveringsprotocolglp-code}

|{: .def}||
|-|-|
|Begrip|[GLP-code](#glp-code)|
|Eigenschap van|[Gegevensleveringsprotocol](#TGegevensleveringsprotocol)|
|Type|CharacterString|

### GLP voor Gegevensdeling {#TGLP_voor_Gegevensdeling}

|{: .def}||
|-|-|
|Toelichting|[Gegevensleveringsprotocol](#TGegevensleveringsprotocol) beschrijft de juridische en organisatorische afspraken voor [Gegevensdeling](#TGegevensdeling)|
|Rol van|1..1 [Gegevensleveringsprotocol](#TGegevensleveringsprotocol)|
|Met|0..1 [Gegevensdeling](#TGegevensdeling)|

## Gegevensleveringsspecificatie {#TGegevensleveringsspecificatie}

|{: .def}||
|-|-|
|Begrip|[Gegevensleveringsspecificatie](#gegevensleveringsspecificatie)|
|Toelichting|[gls-code]()|
|Kenmerken|[GLS Naam](#TGLS_Naam), [GLS globale beschrijving](#TGLS_globale_beschrijving), [GLS populatiebeschrijving](#TGLS_populatiebeschrijving), [gls-code](#TGegevensleveringsspecificatiegls-code)|
|Rollen|[GLS Begrippenkader](#TGLS_Begrippenkader), [GLS Standaardmodel Document](#TGLS_Standaardmodel_Document), [GLS heeft Classificatie](#TGLS_heeft_Classificatie), [GLS heeft GLS Standaardafspraken](#TGLS_heeft_GLS_Standaardafspraken), [GLS heeft LGM](#TGLS_heeft_LGM), [GLS heeft extra Afspraak](#TGLS_heeft_extra_Afspraak), [GLS heeft gerelateerd Document](#TGLS_heeft_gerelateerd_Document), [GLS hoort bij GLP](#TGLS_hoort_bij_GLP), [Gegevensleveringsspecificatie hoort bij Verwerkersovereenkomst](#TGegevensleveringsspecificatie_hoort_bij_Verwerkersovereenkomst)|
|Relatie met|[GLS omvat Gegevensleversetspecificatie](#TGLS_omvat_Gegevensleversetspecificatie), [Gegevensleveringsspecificatie](#TGLS_heeft_ContactpersoonGegevensleveringsspecificatie)|

### GLS Naam {#TGLS_Naam}

|{: .def}||
|-|-|
|Toelichting|[Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie) heet [gls_naam]()|
|Eigenschap van|[Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie)|
|Type|[gls_naam](#Tgls_naam)|

### GLS populatiebeschrijving {#TGLS_populatiebeschrijving}

|{: .def}||
|-|-|
|Toelichting|[Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie) deelt gegevens over [populatiebeschrijving]()|
|Eigenschap van|[Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie)|
|Type|[populatiebeschrijving](#Tpopulatiebeschrijving)|

### gls-code {#TGegevensleveringsspecificatiegls-code}

|{: .def}||
|-|-|
|Begrip|[GLS-code](#gls-code)|
|Eigenschap van|[Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie)|
|Type|CharacterString|

### GLS globale beschrijving {#TGLS_globale_beschrijving}

|{: .def}||
|-|-|
|Toelichting|gegevensleveringsspecificatie [Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie) wordt globaal beschreven als [GLS-globalebeschrijving]()|
|Eigenschap van|[Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie)|
|Type|[GLS-globalebeschrijving](#TGLS-globalebeschrijving)|

### GLS Begrippenkader {#TGLS_Begrippenkader}

|{: .def}||
|-|-|
|Toelichting|gegevensleveringsspecificatie [Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie) bevat term [Begrippenkader](#TBegrippenkader)|
|Rol van|0..1 [Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie)|
|Met|1..1 [Begrippenkader](#TBegrippenkader)|

### GLS heeft gerelateerd Document {#TGLS_heeft_gerelateerd_Document}

|{: .def}||
|-|-|
|Toelichting|[Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie) heeft gerelateerd [Document](#TDocument)|
|Rol van|0..* [Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie)|
|Met|0..* [Document](#TDocument)|

### GLS Standaardmodel Document {#TGLS_Standaardmodel_Document}

|{: .def}||
|-|-|
|Toelichting|[Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie) gebruikt standaardmodel [Document](#TDocument)|
|Rol van|0..1 [Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie)|
|Met|0..1 [Document](#TDocument)|

### GLS heeft GLS Standaardafspraken {#TGLS_heeft_GLS_Standaardafspraken}

|{: .def}||
|-|-|
|Toelichting|[Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie) conformeert aan [GLS Standaardafspraken](#TGLS_Standaardafspraken)|
|Rol van|0..1 [Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie)|
|Met|0..1 [GLS Standaardafspraken](#TGLS_Standaardafspraken)|

### Gegevensleveringsspecificatie hoort bij Verwerkersovereenkomst {#TGegevensleveringsspecificatie_hoort_bij_Verwerkersovereenkomst}

|{: .def}||
|-|-|
|Toelichting|gegevensleveringsspecificatie met GLS-code [Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie) hoort bij verwerkersovereenkomst met verwerkersovereenkomstcode [Verwerkersovereenkomst](#TVerwerkersovereenkomst)|
|Rol van|0..* [Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie)|
|Met|1..* [Verwerkersovereenkomst](#TVerwerkersovereenkomst)|

### GLS heeft LGM {#TGLS_heeft_LGM}

|{: .def}||
|-|-|
|Toelichting|gegevensleveringsspecificatie [Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie) heeft Logisch Gegevensmodel [Logisch Gegevensmodel](#TLogisch_Gegevensmodel)|
|Rol van|1..1 [Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie)|
|Met|1..1 [Logisch Gegevensmodel](#TLogisch_Gegevensmodel)|

### GLS hoort bij GLP {#TGLS_hoort_bij_GLP}

|{: .def}||
|-|-|
|Toelichting|gegevensleveringsspecificatie met GLS-code [Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie) hoort bij gegevensleveringsprotocol met GLP-code [Gegevensleveringsprotocol](#TGegevensleveringsprotocol)|
|Rol van|0..* [Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie)|
|Met|1..* [Gegevensleveringsprotocol](#TGegevensleveringsprotocol)|

### GLS heeft extra Afspraak {#TGLS_heeft_extra_Afspraak}

|{: .def}||
|-|-|
|Toelichting|GLS [Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie) bevat [GLS Afspraak](#TGLS_Afspraak)|
|Rol van|1..* [Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie)|
|Met|1..* [GLS Afspraak](#TGLS_Afspraak)|

### GLS heeft Classificatie {#TGLS_heeft_Classificatie}

|{: .def}||
|-|-|
|Toelichting|[Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie) heeft classificatie [Classificatie](#TClassificatie)|
|Rol van|0..* [Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie)|
|Met|0..* [Classificatie](#TClassificatie)|

## Gegevensleversetspecificatie {#TGegevensleversetspecificatie}

|{: .def}||
|-|-|
|Begrip|[Gegevensleversetspecificatie](#gegevensleversetspecificatie)|
|Toelichting|[gegevensleversetspecificatiecode]()|
|Kenmerken|[Gegevensleverset wordt gefilterd op Gegevenstype](#TGegevensleverset_wordt_gefilterd_op_Gegevenstype), [Gegevensleversetspecificatie populatiebeschrijving](#TGegevensleversetspecificatie_populatiebeschrijving), [gegevensleversetspecificatiecode](#TGegevensleversetspecificatiegegevensleversetspecificatiecode)|
|Rollen|[GLS omvat Gegevensleversetspecificatie](#TGLS_omvat_Gegevensleversetspecificatie), [Gegevensleverset wordt gefilterd op Gegevenstype](#TGegevensleverset_wordt_gefilterd_op_Gegevenstype), [Gegevensleversetspecificatie heeft Afspraak](#TGegevensleversetspecificatie_heeft_Afspraak), [Gegevensleversetspecificatie heeft Classificatie](#TGegevensleversetspecificatie_heeft_Classificatie), [Gegevensleversetspecificatie heeft LGM](#TGegevensleversetspecificatie_heeft_LGM), [Gegevensleversetspecificatie omvat Gegevensmiddelspecificatie](#TGegevensleversetspecificatie_omvat_Gegevensmiddelspecificatie)|

### Gegevensleversetspecificatie populatiebeschrijving {#TGegevensleversetspecificatie_populatiebeschrijving}

|{: .def}||
|-|-|
|Toelichting|[Gegevensleversetspecificatie](#TGegevensleversetspecificatie) deelt gegevens over [populatiebeschrijving]()|
|Eigenschap van|[Gegevensleversetspecificatie](#TGegevensleversetspecificatie)|
|Type|[populatiebeschrijving](#Tpopulatiebeschrijving)|

### Gegevensleverset wordt gefilterd op Gegevenstype {#TGegevensleverset_wordt_gefilterd_op_Gegevenstype}

|{: .def}||
|-|-|
|Toelichting|[Gegevensleversetspecificatie](#TGegevensleversetspecificatie) filtert gegevenstype [Gegevenstype](#TGegevenstype) op gegevensfilterconditie [gegevensfilterconditie]();<br/>[Gegevensleversetspecificatie](#TGegevensleversetspecificatie) filtert gegevenstype [Gegevenstype](#TGegevenstype) op gegevensfilterconditie [gegevensfilterconditie]()|
|Eigenschap van|[Gegevensleversetspecificatie](#TGegevensleversetspecificatie)[Gegevenstype](#TGegevenstype)|
|Type|[gegevensfilterconditie](#Tgegevensfilterconditie)|

### gegevensleversetspecificatiecode {#TGegevensleversetspecificatiegegevensleversetspecificatiecode}

|{: .def}||
|-|-|
|Eigenschap van|[Gegevensleversetspecificatie](#TGegevensleversetspecificatie)|
|Type|CharacterString|

### Gegevensleversetspecificatie omvat Gegevensmiddelspecificatie {#TGegevensleversetspecificatie_omvat_Gegevensmiddelspecificatie}

|{: .def}||
|-|-|
|Toelichting|[Gegevensleversetspecificatie](#TGegevensleversetspecificatie) omvat gegevensmiddelspecificatie [Gegevensmiddelspecificatie](#TGegevensmiddelspecificatie)|
|Rol van|1..1 [Gegevensleversetspecificatie](#TGegevensleversetspecificatie)|
|Met|1..1 [Gegevensmiddelspecificatie](#TGegevensmiddelspecificatie)|

### GLS omvat Gegevensleversetspecificatie {#TGLS_omvat_Gegevensleversetspecificatie}

|{: .def}||
|-|-|
|Toelichting|[Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie) omvat gegevensleversetspecificatie [Gegevensleversetspecificatie](#TGegevensleversetspecificatie)|
|Rol van|1..1 [Gegevensleversetspecificatie](#TGegevensleversetspecificatie)|
|Met|1..1 [Gegevensleveringsspecificatie](#TGegevensleveringsspecificatie)|

### Gegevensleversetspecificatie heeft Afspraak {#TGegevensleversetspecificatie_heeft_Afspraak}

|{: .def}||
|-|-|
|Toelichting|[Gegevensleversetspecificatie](#TGegevensleversetspecificatie) heeft [Gegevensleversetspecificatie Afspraak](#TGegevensleversetspecificatie_Afspraak)|
|Rol van|1..* [Gegevensleversetspecificatie](#TGegevensleversetspecificatie)|
|Met|0..* [Gegevensleversetspecificatie Afspraak](#TGegevensleversetspecificatie_Afspraak)|

### Gegevensleverset wordt gefilterd op Gegevenstype {#TGegevensleverset_wordt_gefilterd_op_Gegevenstype}

|{: .def}||
|-|-|
|Toelichting|[Gegevensleversetspecificatie](#TGegevensleversetspecificatie) filtert gegevenstype [Gegevenstype](#TGegevenstype) op gegevensfilterconditie [gegevensfilterconditie]();<br/>[Gegevensleversetspecificatie](#TGegevensleversetspecificatie) filtert gegevenstype [Gegevenstype](#TGegevenstype) op gegevensfilterconditie [gegevensfilterconditie]()|
|Rol van|0..* [Gegevensleversetspecificatie](#TGegevensleversetspecificatie)|
|Met|0..* [Gegevenstype](#TGegevenstype)|

### Gegevensleversetspecificatie heeft LGM {#TGegevensleversetspecificatie_heeft_LGM}

|{: .def}||
|-|-|
|Toelichting|gegevensleversetspecificatie [Gegevensleversetspecificatie](#TGegevensleversetspecificatie) heeft LGM [Logisch Gegevensmodel](#TLogisch_Gegevensmodel)|
|Rol van|1..1 [Gegevensleversetspecificatie](#TGegevensleversetspecificatie)|
|Met|1..1 [Logisch Gegevensmodel](#TLogisch_Gegevensmodel)|

### Gegevensleversetspecificatie heeft Classificatie {#TGegevensleversetspecificatie_heeft_Classificatie}

|{: .def}||
|-|-|
|Toelichting|[Gegevensleversetspecificatie](#TGegevensleversetspecificatie) heeft classificatie [Classificatie](#TClassificatie)|
|Rol van|0..* [Gegevensleversetspecificatie](#TGegevensleversetspecificatie)|
|Met|0..* [Classificatie](#TClassificatie)|

## Gegevensleversetspecificatie Afspraak {#TGegevensleversetspecificatie_Afspraak}

|{: .def}||
|-|-|
|Supertype|[Afspraak](#TAfspraak)|
|Toelichting|Gegevensleversetspecificatie Afspraak [Afspraak](#TAfspraak)|
|Rollen|[Gegevensleversetspecificatie Afspraak Afspraakonderwerp](#TGegevensleversetspecificatie_Afspraak_Afspraakonderwerp)|
|Relatie met|[Gegevensleversetspecificatie heeft Afspraak](#TGegevensleversetspecificatie_heeft_Afspraak)|

### Gegevensleversetspecificatie Afspraak Afspraakonderwerp {#TGegevensleversetspecificatie_Afspraak_Afspraakonderwerp}

|{: .def}||
|-|-|
|Toelichting|[Gegevensleversetspecificatie Afspraak](#TGegevensleversetspecificatie_Afspraak) over [Gegevensleversetspecificatie Afspraakonderwerp](#TGegevensleversetspecificatie_Afspraakonderwerp)|
|Rol van|0..1 [Gegevensleversetspecificatie Afspraak](#TGegevensleversetspecificatie_Afspraak)|
|Met|1..1 [Gegevensleversetspecificatie Afspraakonderwerp](#TGegevensleversetspecificatie_Afspraakonderwerp)|

## Gegevensleversetspecificatie Afspraakonderwerp {#TGegevensleversetspecificatie_Afspraakonderwerp}

|{: .def}||
|-|-|
|Toelichting|[gegevensleversetspecificatieafspraakonderwerpbeschrijving]();<br/>We kunnen afspraken maken over [gegevensleversetspecificatieafspraakonderwerpbeschrijving]()|
|Kenmerken|[gegevensleversetspecificatieafspraakonderwerpbeschrijving](#TGegevensleversetspecificatie_Afspraakonderwerpgegevensleversetspecificatieafspraakonderwerpbeschrijving)|
|Relatie met|[Gegevensleversetspecificatie Afspraak Afspraakonderwerp](#TGegevensleversetspecificatie_Afspraak_Afspraakonderwerp)|

### gegevensleversetspecificatieafspraakonderwerpbeschrijving {#TGegevensleversetspecificatie_Afspraakonderwerpgegevensleversetspecificatieafspraakonderwerpbeschrijving}

|{: .def}||
|-|-|
|Eigenschap van|[Gegevensleversetspecificatie Afspraakonderwerp](#TGegevensleversetspecificatie_Afspraakonderwerp)|
|Type|CharacterString|

## Gegevensmiddelspecificatie {#TGegevensmiddelspecificatie}

|{: .def}||
|-|-|
|Begrip|[Gegevensmiddelspecificatie](#gegevensmiddelspecificatie)|
|Toelichting|[gegevensmiddelspecificatiecode]()|
|Kenmerken|[Gegevensmiddelspecificatie beschrijving](#TGegevensmiddelspecificatie_beschrijving), [Gegevensmiddelspecificatie specificeert Type](#TGegevensmiddelspecificatie_specificeert_Type), [gegevensmiddelspecificatiecode](#TGegevensmiddelspecificatiegegevensmiddelspecificatiecode)|
|Rollen|[Gegevensmiddelspecificatie heeft Afspraak](#TGegevensmiddelspecificatie_heeft_Afspraak), [Gegevensmiddelspecificatie omvat Technisch Gegevensmodel](#TGegevensmiddelspecificatie_omvat_Technisch_Gegevensmodel)|
|Relatie met|[Gegevensleversetspecificatie omvat Gegevensmiddelspecificatie](#TGegevensleversetspecificatie_omvat_Gegevensmiddelspecificatie)|

### Gegevensmiddelspecificatie beschrijving {#TGegevensmiddelspecificatie_beschrijving}

|{: .def}||
|-|-|
|Toelichting|Gegevensmiddelspecificatie [Gegevensmiddelspecificatie](#TGegevensmiddelspecificatie) beschrijft [gegevensmiddelspecificatiebeschrijving]()|
|Eigenschap van|[Gegevensmiddelspecificatie](#TGegevensmiddelspecificatie)|
|Type|[gegevensmiddelspecificatiebeschrijving](#Tgegevensmiddelspecificatiebeschrijving)|

### Gegevensmiddelspecificatie specificeert Type {#TGegevensmiddelspecificatie_specificeert_Type}

|{: .def}||
|-|-|
|Toelichting|gegevensmiddel voor [Gegevensmiddelspecificatie](#TGegevensmiddelspecificatie) wordt geleverd in de vorm van een [gegevensmiddeltype]()|
|Eigenschap van|[Gegevensmiddelspecificatie](#TGegevensmiddelspecificatie)|
|Type|[gegevensmiddeltype](#Tgegevensmiddeltype)|

### gegevensmiddelspecificatiecode {#TGegevensmiddelspecificatiegegevensmiddelspecificatiecode}

|{: .def}||
|-|-|
|Eigenschap van|[Gegevensmiddelspecificatie](#TGegevensmiddelspecificatie)|
|Type|CharacterString|

### Gegevensmiddelspecificatie heeft Afspraak {#TGegevensmiddelspecificatie_heeft_Afspraak}

|{: .def}||
|-|-|
|Toelichting|[Gegevensmiddelspecificatie](#TGegevensmiddelspecificatie) heeft [Gegevensmiddelspecificatie Afspraak](#TGegevensmiddelspecificatie_Afspraak)|
|Rol van|1..* [Gegevensmiddelspecificatie](#TGegevensmiddelspecificatie)|
|Met|0..* [Gegevensmiddelspecificatie Afspraak](#TGegevensmiddelspecificatie_Afspraak)|

### Gegevensmiddelspecificatie omvat Technisch Gegevensmodel {#TGegevensmiddelspecificatie_omvat_Technisch_Gegevensmodel}

|{: .def}||
|-|-|
|Toelichting|gegevensmiddelspecificatie [Gegevensmiddelspecificatie](#TGegevensmiddelspecificatie) heeft technisch gegevensmodel [Technisch Gegevensmodel](#TTechnisch_Gegevensmodel)|
|Rol van|1..1 [Gegevensmiddelspecificatie](#TGegevensmiddelspecificatie)|
|Met|1..1 [Technisch Gegevensmodel](#TTechnisch_Gegevensmodel)|

## Gegevensmiddelspecificatie Afspraak {#TGegevensmiddelspecificatie_Afspraak}

|{: .def}||
|-|-|
|Supertype|[Afspraak](#TAfspraak)|
|Toelichting|Gegevensmiddelafspraak [Afspraak](#TAfspraak)|
|Rollen|[Gegevensmiddelspecificatie Afspraak Afspraakonderwerp](#TGegevensmiddelspecificatie_Afspraak_Afspraakonderwerp)|
|Relatie met|[Gegevensmiddelspecificatie heeft Afspraak](#TGegevensmiddelspecificatie_heeft_Afspraak)|

### Gegevensmiddelspecificatie Afspraak Afspraakonderwerp {#TGegevensmiddelspecificatie_Afspraak_Afspraakonderwerp}

|{: .def}||
|-|-|
|Toelichting|[Gegevensmiddelspecificatie Afspraak](#TGegevensmiddelspecificatie_Afspraak) over [Gegevensmiddelspecificatie Afspraakonderwerp](#TGegevensmiddelspecificatie_Afspraakonderwerp)|
|Rol van|0..1 [Gegevensmiddelspecificatie Afspraak](#TGegevensmiddelspecificatie_Afspraak)|
|Met|1..1 [Gegevensmiddelspecificatie Afspraakonderwerp](#TGegevensmiddelspecificatie_Afspraakonderwerp)|

## Gegevensmiddelspecificatie Afspraakonderwerp {#TGegevensmiddelspecificatie_Afspraakonderwerp}

|{: .def}||
|-|-|
|Toelichting|[gegevensmiddelspecificatieafspraakonderwerpbeschrijving]();<br/>We kunnen afspraken maken over [gegevensmiddelspecificatieafspraakonderwerpbeschrijving]()|
|Kenmerken|[gegevensmiddelspecificatieafspraakonderwerpbeschrijving](#TGegevensmiddelspecificatie_Afspraakonderwerpgegevensmiddelspecificatieafspraakonderwerpbeschrijving)|
|Relatie met|[Gegevensmiddelspecificatie Afspraak Afspraakonderwerp](#TGegevensmiddelspecificatie_Afspraak_Afspraakonderwerp)|

### gegevensmiddelspecificatieafspraakonderwerpbeschrijving {#TGegevensmiddelspecificatie_Afspraakonderwerpgegevensmiddelspecificatieafspraakonderwerpbeschrijving}

|{: .def}||
|-|-|
|Eigenschap van|[Gegevensmiddelspecificatie Afspraakonderwerp](#TGegevensmiddelspecificatie_Afspraakonderwerp)|
|Type|CharacterString|

## Gegevenstype {#TGegevenstype}

|{: .def}||
|-|-|
|Begrip|[Gegevenstype](#gegevenstype)|
|Subtype(s)|[Gegevenstype categorisch](#TGegevenstype_categorisch)|
|Toelichting|er is een Gegevenstype [gegevenstype code]();<br/>gegevenstype [gegevenstype code]();<br/>Gegevenstype [gegevenstype code]() bestaat;<br/>Gegevenstype [gegevenstype code]();<br/>gegevenstype [gegevenstype code]() bestaat|
|Kenmerken|[Gegevensleverset wordt gefilterd op Gegevenstype](#TGegevensleverset_wordt_gefilterd_op_Gegevenstype), [Naam gegevenstype](#TNaam_gegevenstype), [Waardetype gegevenstype](#TWaardetype_gegevenstype), [gegevenstype code](#TGegevenstypegegevenstype_code)|
|Rollen|[Gegevenstype heeft Classificatie](#TGegevenstype_heeft_Classificatie), [Gegevenstypemapping](#TGegevenstypemapping)|
|Relatie met|[Gegevensleverset wordt gefilterd op Gegevenstype](#TGegevensleverset_wordt_gefilterd_op_Gegevenstype), [LGM bevat Gegevenstype](#TLGM_bevat_Gegevenstype), [Term bij Gegevenstype](#TTerm_bij_Gegevenstype)|

### Waardetype gegevenstype {#TWaardetype_gegevenstype}

|{: .def}||
|-|-|
|Toelichting|het type van [Gegevenstype](#TGegevenstype) is [waarde waardetype gegevenstype]()|
|Eigenschap van|[Gegevenstype](#TGegevenstype)|
|Type|[waarde waardetype gegevenstype](#Twaarde_waardetype_gegevenstype)|
|Mogelijke waarden|Byte; Boolean; List; String; DateTime; Blob; Categorical; Float; Double; Duration; Time; Date; Decimal; Integer|

### gegevenstype code {#TGegevenstypegegevenstype_code}

|{: .def}||
|-|-|
|Eigenschap van|[Gegevenstype](#TGegevenstype)|
|Type|CharacterString|

### Naam gegevenstype {#TNaam_gegevenstype}

|{: .def}||
|-|-|
|Toelichting|[Gegevenstype](#TGegevenstype) heet [gegevenstypenaam]();<br/>[gegevenstypenaam]() is de naam van [Gegevenstype](#TGegevenstype)|
|Eigenschap van|[Gegevenstype](#TGegevenstype)|
|Type|[gegevenstypenaam](#Tgegevenstypenaam)|

### Gegevensleverset wordt gefilterd op Gegevenstype {#TGegevensleverset_wordt_gefilterd_op_Gegevenstype}

|{: .def}||
|-|-|
|Toelichting|[Gegevensleversetspecificatie](#TGegevensleversetspecificatie) filtert gegevenstype [Gegevenstype](#TGegevenstype) op gegevensfilterconditie [gegevensfilterconditie]();<br/>[Gegevensleversetspecificatie](#TGegevensleversetspecificatie) filtert gegevenstype [Gegevenstype](#TGegevenstype) op gegevensfilterconditie [gegevensfilterconditie]()|
|Eigenschap van|[Gegevensleversetspecificatie](#TGegevensleversetspecificatie)[Gegevenstype](#TGegevenstype)|
|Type|[gegevensfilterconditie](#Tgegevensfilterconditie)|

### Gegevenstype heeft Classificatie {#TGegevenstype_heeft_Classificatie}

|{: .def}||
|-|-|
|Toelichting|[Gegevenstype](#TGegevenstype) heeft classificatie [Classificatie](#TClassificatie)|
|Rol van|0..* [Gegevenstype](#TGegevenstype)|
|Met|0..* [Classificatie](#TClassificatie)|

### Gegevenstypemapping {#TGegevenstypemapping}

|{: .def}||
|-|-|
|Begrip|[Gegevenstypemapping](#gegevenstypemapping)|
|Toelichting|[Gegevenstype](#TGegevenstype) wordt fysiek gerepresenteerd door [Gegevensveld](#TGegevensveld);<br/>[Gegevensveld](#TGegevensveld) is een fysieke representatie van [Gegevenstype](#TGegevenstype)|
|Rol van|1..1 [Gegevenstype](#TGegevenstype)|
|Met|0..1 [Gegevensveld](#TGegevensveld)|

## Gegevenstype categorisch {#TGegevenstype_categorisch}

|{: .def}||
|-|-|
|Supertype|[Gegevenstype](#TGegevenstype)|
|Toelichting|categorisch [Gegevenstype](#TGegevenstype)|
|Kenmerken|[Waardebereik gegevenstype](#TWaardebereik_gegevenstype)|

### Waardebereik gegevenstype {#TWaardebereik_gegevenstype}

|{: .def}||
|-|-|
|Toelichting|de mogelijke waardes van [Gegevenstype categorisch](#TGegevenstype_categorisch) zijn [waardes gegevenstype]()|
|Eigenschap van|[Gegevenstype categorisch](#TGegevenstype_categorisch)|
|Type|[waardes gegevenstype](#Twaardes_gegevenstype)|

## Gegevensveld {#TGegevensveld}

|{: .def}||
|-|-|
|Begrip|[Gegevensveld](#gegevensveld)|
|Toelichting|Gegevensveld [gegevensveld id]();<br/>gegevensveld [gegevensveld id]() bestaat|
|Kenmerken|[Beschrijving gegevensveld](#TBeschrijving_gegevensveld), [Naam gegevensveld](#TNaam_gegevensveld), [gegevensveld id](#TGegevensveldgegevensveld_id)|
|Relatie met|[Gegevenstypemapping](#TGegevenstypemapping), [Gegevensveld in Technisch Gegevensmodel](#TGegevensveld_in_Technisch_Gegevensmodel)|

### gegevensveld id {#TGegevensveldgegevensveld_id}

|{: .def}||
|-|-|
|Eigenschap van|[Gegevensveld](#TGegevensveld)|
|Type|CharacterString|

### Naam gegevensveld {#TNaam_gegevensveld}

|{: .def}||
|-|-|
|Toelichting|de naam van [Gegevensveld](#TGegevensveld) is [gegevensveldnaam]()|
|Eigenschap van|[Gegevensveld](#TGegevensveld)|
|Type|[gegevensveldnaam](#Tgegevensveldnaam)|

### Beschrijving gegevensveld {#TBeschrijving_gegevensveld}

|{: .def}||
|-|-|
|Toelichting|[Gegevensveld](#TGegevensveld) is [gegevensveldbeschrijving]()|
|Eigenschap van|[Gegevensveld](#TGegevensveld)|
|Type|[gegevensveldbeschrijving](#Tgegevensveldbeschrijving)|

## Geregistreerd Algoritme {#TGeregistreerd_Algoritme}

|{: .def}||
|-|-|
|Begrip|[Geregistreerd algoritme](#geregistreerd-algoritme)|
|Toelichting|[geregistreerdalgoritmenaam]()|
|Kenmerken|[Geregistreerd Algoritme heeft URL](#TGeregistreerd_Algoritme_heeft_URL), [geregistreerdalgoritmenaam](#TGeregistreerd_Algoritmegeregistreerdalgoritmenaam)|
|Relatie met|[Bij AKI-Classificatie hoort Geregistreerd Algoritme](#TBij_AKI-Classificatie_hoort_Geregistreerd_Algoritme)|

### geregistreerdalgoritmenaam {#TGeregistreerd_Algoritmegeregistreerdalgoritmenaam}

|{: .def}||
|-|-|
|Eigenschap van|[Geregistreerd Algoritme](#TGeregistreerd_Algoritme)|
|Type|CharacterString|

### Geregistreerd Algoritme heeft URL {#TGeregistreerd_Algoritme_heeft_URL}

|{: .def}||
|-|-|
|Toelichting|[Geregistreerd Algoritme](#TGeregistreerd_Algoritme) heeft registerURL [geregistreerdalgoritmeurl]()|
|Eigenschap van|[Geregistreerd Algoritme](#TGeregistreerd_Algoritme)|
|Type|[geregistreerdalgoritmeurl](#Tgeregistreerdalgoritmeurl)|

## Logisch Gegevensmodel {#TLogisch_Gegevensmodel}

|{: .def}||
|-|-|
|Begrip|[Logisch gegevensmodel](#logisch-gegevensmodel)|
|Toelichting|logisch Gegevensmodel [logisch gegevensmodel code]() bestaat;<br/>[logisch gegevensmodel code]()|
|Kenmerken|[logisch gegevensmodel code](#TLogisch_Gegevensmodellogisch_gegevensmodel_code)|
|Rollen|[LGM bevat Gegevenstype](#TLGM_bevat_Gegevenstype)|
|Relatie met|[GLS heeft LGM](#TGLS_heeft_LGM), [Gegevensleversetspecificatie heeft LGM](#TGegevensleversetspecificatie_heeft_LGM)|

### logisch gegevensmodel code {#TLogisch_Gegevensmodellogisch_gegevensmodel_code}

|{: .def}||
|-|-|
|Eigenschap van|[Logisch Gegevensmodel](#TLogisch_Gegevensmodel)|
|Type|CharacterString|

### LGM bevat Gegevenstype {#TLGM_bevat_Gegevenstype}

|{: .def}||
|-|-|
|Toelichting|logisch gegevensmodel [Logisch Gegevensmodel](#TLogisch_Gegevensmodel) bevat gegevenstype [Gegevenstype](#TGegevenstype)|
|Rol van|0..* [Logisch Gegevensmodel](#TLogisch_Gegevensmodel)|
|Met|1..* [Gegevenstype](#TGegevenstype)|

## Partij {#TPartij}

|{: .def}||
|-|-|
|Begrip|[Partij](#partij)|
|Toelichting|Partij [partij id]();<br/>Organisatie [partij id]();<br/>Partij [partij id]() bestaat;<br/>[partij id]()|
|Kenmerken|[Partij naam](#TPartij_naam), [partij id](#TPartijpartij_id)|
|Relatie met|[Partij](#TFunctie_in_Organisatorische_eenheid_van_PartijPartij)|

### Partij naam {#TPartij_naam}

|{: .def}||
|-|-|
|Toelichting|[Partij](#TPartij) heet [naam]()|
|Eigenschap van|[Partij](#TPartij)|
|Type|[naam](#Tnaam)|

### partij id {#TPartijpartij_id}

|{: .def}||
|-|-|
|Eigenschap van|[Partij](#TPartij)|
|Type|CharacterString|

## Persoon {#TPersoon}

|{: .def}||
|-|-|
|Toelichting|Er is een persoon [persoon id]();<br/>persoon [persoon id]()|
|Kenmerken|[Persoonsnaam](#TPersoonsnaam), [persoon id](#TPersoonpersoon_id)|
|Relatie met|[Document Auteur](#TDocument_Auteur), [Persoon](#TPersoon_in_FunctiePersoon)|

### persoon id {#TPersoonpersoon_id}

|{: .def}||
|-|-|
|Eigenschap van|[Persoon](#TPersoon)|
|Type|CharacterString|

### Persoonsnaam {#TPersoonsnaam}

|{: .def}||
|-|-|
|Toelichting|[naam]() is de naam van [Persoon](#TPersoon)|
|Eigenschap van|[Persoon](#TPersoon)|
|Type|[naam](#Tnaam)|

## Persoon in Functie {#TPersoon_in_Functie}

|{: .def}||
|-|-|
|Toelichting|[Persoon](#TPersoon) bekleedt [Functie in Organisatorische eenheid van Partij](#TFunctie_in_Organisatorische_eenheid_van_Partij);<br/>[Persoon](#TPersoon) in [Functie in Organisatorische eenheid van Partij](#TFunctie_in_Organisatorische_eenheid_van_Partij)|
|Rollen|[Functie in Organisatorische eenheid van Partij](#TPersoon_in_FunctieFunctie_in_Organisatorische_eenheid_van_Partij), [Persoon](#TPersoon_in_FunctiePersoon)|
|Relatie met|[Persoon in Functie](#TGLS_heeft_ContactpersoonPersoon_in_Functie)|

### Persoon {#TPersoon_in_FunctiePersoon}

|{: .def}||
|-|-|
|Rol van|1..* [Persoon in Functie](#TPersoon_in_Functie)|
|Met| [Persoon](#TPersoon)|

### Functie in Organisatorische eenheid van Partij {#TPersoon_in_FunctieFunctie_in_Organisatorische_eenheid_van_Partij}

|{: .def}||
|-|-|
|Rol van|0..* [Persoon in Functie](#TPersoon_in_Functie)|
|Met| [Functie in Organisatorische eenheid van Partij](#TFunctie_in_Organisatorische_eenheid_van_Partij)|

## Technisch Gegevensmodel {#TTechnisch_Gegevensmodel}

|{: .def}||
|-|-|
|Begrip|[Technisch gegevensmodel](#technisch-gegevensmodel)|
|Toelichting|[technisch gegevensmodel code]()|
|Kenmerken|[technisch gegevensmodel code](#TTechnisch_Gegevensmodeltechnisch_gegevensmodel_code)|
|Rollen|[Gegevensveld in Technisch Gegevensmodel](#TGegevensveld_in_Technisch_Gegevensmodel)|
|Relatie met|[Gegevensmiddelspecificatie omvat Technisch Gegevensmodel](#TGegevensmiddelspecificatie_omvat_Technisch_Gegevensmodel)|

### technisch gegevensmodel code {#TTechnisch_Gegevensmodeltechnisch_gegevensmodel_code}

|{: .def}||
|-|-|
|Eigenschap van|[Technisch Gegevensmodel](#TTechnisch_Gegevensmodel)|
|Type|CharacterString|

### Gegevensveld in Technisch Gegevensmodel {#TGegevensveld_in_Technisch_Gegevensmodel}

|{: .def}||
|-|-|
|Toelichting|technisch gegevensmodel [Technisch Gegevensmodel](#TTechnisch_Gegevensmodel) bevat gegevensveld [Gegevensveld](#TGegevensveld)|
|Rol van|1..1 [Technisch Gegevensmodel](#TTechnisch_Gegevensmodel)|
|Met|1..1 [Gegevensveld](#TGegevensveld)|

## Verwerkersovereenkomst {#TVerwerkersovereenkomst}

|{: .def}||
|-|-|
|Begrip|[Verwerkersovereenkomst](#verwerkersovereenkomst)|
|Toelichting|[verwerkersovereenkomstcode]();<br/>verwerkersovereenkomst met verwerkersovereenkomstcode [verwerkersovereenkomstcode]()|
|Kenmerken|[verwerkersovereenkomstcode](#TVerwerkersovereenkomstverwerkersovereenkomstcode)|
|Rollen|[Verwerkersovereenkomst voor Gegevensdeling](#TVerwerkersovereenkomst_voor_Gegevensdeling)|
|Relatie met|[Gegevensleveringsspecificatie hoort bij Verwerkersovereenkomst](#TGegevensleveringsspecificatie_hoort_bij_Verwerkersovereenkomst)|

### verwerkersovereenkomstcode {#TVerwerkersovereenkomstverwerkersovereenkomstcode}

|{: .def}||
|-|-|
|Eigenschap van|[Verwerkersovereenkomst](#TVerwerkersovereenkomst)|
|Type|CharacterString|

### Verwerkersovereenkomst voor Gegevensdeling {#TVerwerkersovereenkomst_voor_Gegevensdeling}

|{: .def}||
|-|-|
|Toelichting|[Verwerkersovereenkomst](#TVerwerkersovereenkomst) regelt xxx voor de [Gegevensdeling](#TGegevensdeling)|
|Rol van|1..1 [Verwerkersovereenkomst](#TVerwerkersovereenkomst)|
|Met|0..1 [Gegevensdeling](#TGegevensdeling)|

## Waardetypering en referentielijsten

### GLS-globalebeschrijving {#TGLS-globalebeschrijving}

|{: .def}||
|-|-|
|Gebaseerd op|CharacterString|

### Termbeschrijving {#TTermbeschrijving}

|{: .def}||
|-|-|
|Gebaseerd op|CharacterString|

### afspraakbeschrijving {#Tafspraakbeschrijving}

|{: .def}||
|-|-|
|Gebaseerd op|CharacterString|

### classificatietypenaam {#Tclassificatietypenaam}

|{: .def}||
|-|-|
|Gebaseerd op|CharacterString|

### documentsoort {#Tdocumentsoort}

|{: .def}||
|-|-|
|Gebaseerd op|CharacterString|

### gegevensfilterconditie {#Tgegevensfilterconditie}

|{: .def}||
|-|-|
|Gebaseerd op|CharacterString|

### gegevensmiddelspecificatiebeschrijving {#Tgegevensmiddelspecificatiebeschrijving}

|{: .def}||
|-|-|
|Gebaseerd op|CharacterString|

### gegevensmiddeltype {#Tgegevensmiddeltype}

|{: .def}||
|-|-|
|Gebaseerd op|CharacterString|

### gegevenstypenaam {#Tgegevenstypenaam}

|{: .def}||
|-|-|
|Gebaseerd op|CharacterString|

### gegevensveldbeschrijving {#Tgegevensveldbeschrijving}

|{: .def}||
|-|-|
|Gebaseerd op|CharacterString|

### gegevensveldnaam {#Tgegevensveldnaam}

|{: .def}||
|-|-|
|Gebaseerd op|CharacterString|

### geregistreerdalgoritmeurl {#Tgeregistreerdalgoritmeurl}

|{: .def}||
|-|-|
|Gebaseerd op|CharacterString|

### gls_naam {#Tgls_naam}

|{: .def}||
|-|-|
|Gebaseerd op|CharacterString|

### locatie {#Tlocatie}

|{: .def}||
|-|-|
|Gebaseerd op|CharacterString|

### naam {#Tnaam}

|{: .def}||
|-|-|
|Gebaseerd op|CharacterString|

### populatiebeschrijving {#Tpopulatiebeschrijving}

|{: .def}||
|-|-|
|Begrip|[Populatiebeschrijving](#populatiebeschrijving)|
|Gebaseerd op|CharacterString|

### versienummer {#Tversienummer}

|{: .def}||
|-|-|
|Begrip|[Versienummer](#versienummer)|
|Gebaseerd op|CharacterString|

### waardes gegevenstype {#Twaardes_gegevenstype}

|{: .def}||
|-|-|
|Gebaseerd op|CharacterString|

### afspraakonderwerpbeschrijving {#Tafspraakonderwerpbeschrijving}

De volgende waarden zijn mogelijk:
- administratieve kwaliteit
- bewaartermijnen
- communicatie bij afwijkende levering
- communicatie bij normale levering
- communicatie over kwaliteit
- de actualiteit van het gegevensmiddel
- de gegevensleveringsfrequentie
- de samenstelling van het gegevensmiddel
- de wijze van leveren
- deelleveringen
- [deltaverwerking](#deltaverwerking)
- foutherstel door hernieuwde levering
- [gegevenskwaliteit](#gegevenskwaliteit)
- gegevensleveringsinitiatie
- het gegevensmiddelmedium
- maatregelen tegen herleidbaarheid van gegevens
- naamgevingsconventies
- tijdslijnen
- toe te passen beveiligingsmaatregelen
- transportkarakteristieken

### classificatie_akigegevens_waarde {#Tclassificatie_akigegevens_waarde}

De volgende waarden zijn mogelijk:
- [bevat geen gegevens die uit algoritmen afkomstig zijn](#aki-gegevens-bevat-geen-gegevens-die-uit-algoritmen-afkomstig-zijn)
- [bevat gegevens die op basis van regels zijn afgeleid](#aki-gegevens-bevat-gegevens-die-op-basis-van-regels-zijn-afgeleid)
- [ja, beperkt risico](#aki-gegevens-ja,-beperkt-risico)
- [ja, hoog risico](#aki-gegevens-ja,-hoog-risico)
- [ja, minimaal risico](#aki-gegevens-ja,-minimaal-risico)
- [ja, onaanvaardbaar risico](#aki-gegevens-ja,-onaanvaardbaar-risico)

### classificatie_bbn_waarde {#Tclassificatie_bbn_waarde}

De volgende waarden zijn mogelijk:
- [BBN1](#basis-beveiliging-niveau---bbn1)
- [BBN2](#basis-beveiliging-niveau---bbn2)
- [BBN3](#basis-beveiliging-niveau---bbn3)

### classificatie_biv_beschikbaarheid_waarde {#Tclassificatie_biv_beschikbaarheid_waarde}

De volgende waarden zijn mogelijk:
- [hoog-3](#biv-classificatie-beschikbaarheid---hoog)
- laag -1
- [midden-2](#biv-classificatie-beschikbaarheid---midden)

### classificatie_biv_integriteit_waarde {#Tclassificatie_biv_integriteit_waarde}

De volgende waarden zijn mogelijk:
- [hoog-3](#biv-classificatie-integriteit-hoog)
- [laag-1](#biv-classificatie-integriteit-laag)
- [midden-2](#biv-classificatie-integriteit-midden)

### classificatie_biv_vertrouwelijkheid_waarde {#Tclassificatie_biv_vertrouwelijkheid_waarde}

De volgende waarden zijn mogelijk:
- [hoog-3](#biv-classificatie-vertrouwelijkheid-hoog)
- [laag-1](#biv-classificatie-vertrouwelijkheid-laag)
- [midden-2](#biv-classificatie-vertrouwelijkheid-midden)

### classificatie_bpg_waarde {#Tclassificatie_bpg_waarde}

De volgende waarden zijn mogelijk:
- [biometrische gegevens met het oog op de unieke identificatie van een persoon](#bijzondere-persoonsgegevens-politieke-opvattingen)
- [gegevens over gezondheid](#bijzondere-persoonsgegevens-ras-of-etnische-afkomst)
- [gegevens over iemands seksueel gedrag of seksuele gerichtheid](#bijzondere-persoonsgegevens-religieuze-of-levensbeschouwelijke-overtuigingen)
- [gegevens over lidmaatschap van een vakbond](#bijzondere-persoonsgegevens-genetische-gegevens)
- [gegevens over politieke opvattingen](#bijzondere-persoonsgegevens-gegevens-met-betrekking-tot-iemands-seksueel-gedrag-of-seksuele-gerichtheid)
- [gegevens over ras of etnische afkomst](#bijzondere-persoonsgegevens-biometrische-gegevens-met-het-oog-op-de-unieke-identificatie-van-een-persoon)
- [gegevens over religieuze of levensbeschouwelijke overtuigingen](#bijzondere-persoonsgegevens-gegevens-over-gezondheid)
- [genetische gegevens](#bijzondere-persoonsgegevens-lidmaatschap-van-een-vakbond)

### classificatie_gerechtelijkestrafgegevens_waarde {#Tclassificatie_gerechtelijkestrafgegevens_waarde}

De volgende waarden zijn mogelijk:
- [bevat geen gerechtelijke strafgegevens](#gerechtelijke-strafgegevens-bevat-geen-gerechtelijke-strafgegevens)
- [bevat gerechtelijke strafgegevens](#gerechtelijke-strafgegevens-bevat-gerechtelijke-strafgegevens)

### classificatie_justitiegegevens_waarde {#Tclassificatie_justitiegegevens_waarde}

De volgende waarden zijn mogelijk:
- [bevat geen justitiële gegevens](#justitiële-gegevens-bevat-geen-justitiële-gegevens)
- [bevat justitiële gegevens](#justitiële-gegevens-bevat-justitiële-gegevens)

### classificatie_pg_waarde {#Tclassificatie_pg_waarde}

De volgende waarden zijn mogelijk:
- [bevat bijzondere persoonsgegevens](#persoonsgegevens-bevat-bijzondere-persoonsgegevens)
- [bevat geen persoonsgegevens](#persoonsgegevens-bevat-geen-persoonsgegevens)
- [bevat gevoelige persoonsgegevens](#persoonsgegevens-bevat-gevoelige-persoonsgegevens)
- [bevat gewone persoonsgegeven](#persoonsgegevens-bevat-gewone-persoonsgegeven)
- [bevat strafrechtelijke persoonsgegevens](#persoonsgegevens-bevat-persoonsgegevens-van-strafrechtelijke-aard)
- [bevat wettelijk identificatienummer](#persoonsgegevens-bevat-wettelijk-identificatienummer)

### classificatie_politiegegevens_waarde {#Tclassificatie_politiegegevens_waarde}

De volgende waarden zijn mogelijk:
- [bevat geen politiegegevens](#politiegegevens-bevat-geen-politiegegevens)
- [bevat politiegegevens](#politiegegevens-bevat-politiegegevens)

### classificatie_strafvorderlijkegegevens_waarde {#Tclassificatie_strafvorderlijkegegevens_waarde}

De volgende waarden zijn mogelijk:
- [bevat geen strafvorderlijke gegevens](#strafvorderlijke-gegevens-bevat-geen-strafvorderlijke-gegevens)
- [bevat strafvorderlijke gegevens](#strafvorderlijke-gegevens-bevat-strafvorderlijke-gegevens)

### classificatie_tbb_waarde {#Tclassificatie_tbb_waarde}

De volgende waarden zijn mogelijk:
- [geheim – departementaal VERTROUWELIJK](#te-beschermen-belang---geheim---departementaal-vertrouwelijk-(dep.v))
- [geheim – staatsgeheim CONFIDENTIEEL](#te-beschermen-belang---geheim---staatsgeheim-confidentieel-(stg.c))
- [geheim – staatsgeheim GEHEIM](#te-beschermen-belang---geheim---staatsgeheim-geheim-(stg.g))
- [geheim – staatsgeheim ZEER GEHEIM](#te-beschermen-belang---geheim---staatsgeheim-zeer-geheim-(stg.zg))
- [intern](#te-beschermen-belang---intern)
- [openbaar](#te-beschermen-belang---openbaar)
- [vertrouwelijk](#te-beschermen-belang---vertrouwelijk)

### classificatie_tenuitvoerleggingsgegevens_waarde {#Tclassificatie_tenuitvoerleggingsgegevens_waarde}

De volgende waarden zijn mogelijk:
- [bevat geen tenuitvoerleggingsgegevens](#tenuitvoerleggingsgegevens-bevat-geen-tenuitvoerleggingsgegevens)
- [bevat tenuitvoerleggingsgegevens](#tenuitvoerleggingsgegevens-bevat-tenuitvoerleggingsgegevens)

### classificatie_verantwoordingsbelang_waarde {#Tclassificatie_verantwoordingsbelang_waarde}

De volgende waarden zijn mogelijk:
- [geen verantwoordingsbelang](#verantwoordingsbelang---kennen-geen-verantwoordingsbelang)
- [ja, de termijn is afhankelijk van de context](#verantwoordingsbelang---is-afhankelijk-van-de-context)
- [ja, moet blijvend worden bewaard](#verantwoordingsbelang---moeten-blijvend-bewaard-worden)
- [ja, moet tijdelijk worden bewaard](#verantwoordingsbelang---moeten-tijdelijk-bewaard-worden)

### classificatie_vitaalbelang_waarde {#Tclassificatie_vitaalbelang_waarde}

De volgende waarden zijn mogelijk:
- [een vitaal belang](#vitaal-belang---vitaal-belang)
- [geen vitaal belang](#vitaal-belang---geen-vitaal-belang)

### gegevensleversetspecificatieafspraakonderwerpbeschrijving {#Tgegevensleversetspecificatieafspraakonderwerpbeschrijving}

De volgende waarden zijn mogelijk:
- bewaartermijnen
- tijdslijnen
- toe te passen beveiligingsmaatregelen

### gegevensmiddelspecificatieafspraakonderwerpbeschrijving {#Tgegevensmiddelspecificatieafspraakonderwerpbeschrijving}

De volgende waarden zijn mogelijk:
- de actualiteit van het gegevensmiddel
- de gegevensleveringsfrequentie
- de interpretatie van het gegevensmiddel
- de samenstelling van het gegevensmiddel
- de wijze van leveren
- deelleveringen
- [deltaverwerking](#deltaverwerking)
- gegevensleveringsinitiatie
- het gegevensmiddeltype
- naamgevingsconventies
- transportkarakteristieken

### glsafspraakonderwerpbeschrijving {#Tglsafspraakonderwerpbeschrijving}

De volgende waarden zijn mogelijk:
- administratieve kwaliteit
- communicatie bij afwijkende levering
- communicatie bij normale levering
- communicatie over kwaliteit
- foutherstel door hernieuwde levering
- [gegevenskwaliteit](#gegevenskwaliteit)
- maatregelen tegen herleidbaarheid van gegevens

### waarde waardetype gegevenstype {#Twaarde_waardetype_gegevenstype}

De volgende waarden zijn mogelijk:
- Blob
- Boolean
- Byte
- Categorical
- Date
- DateTime
- Decimal
- Double
- Duration
- Float
- Integer
- List
- String
- Time

