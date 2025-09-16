# Introductie {#Intro}

In deze introductie worden de gemodelleerde begrippen in het Justitie Afsprakenstelsel Gegevens en Algoritmen (JAGA) verbonden in een verhaal, waardoor het model begrijpelijker wordt.

## Afsprakenstelsel

Het JAGA is het Justitie en Veiligheid [Afsprakenstelsel](#afsprakenstelsel) Gegevens en Algoritmen. Het afsprakenstelsel bevat de afspraken over de gewenste omgang met gegevens binnen het Afsprakenstelsel, en de manier waarop binnen het afsprakenstelsel met elkaar en de afspraken wordt omgegaan.

Een afspraak heeft een [naam](#afspraaknaam), een [onderwerp](#afspraakonderwerp), een [beschrijving](#afspraakbeschrijving) die beschrijft wat de afspraak inhoud, en een [versienummer](#versienummer) (*merk op dat dit niet betekent dat de gegevens worden geversioneerd, daar is meer voor nodig*).

[Deelnemers](#deelnemer) committeren zich aan de [afspraken](#afspraak) in het afsprakenstelsel over de rollen, taken en verantwoordelijkheden die deze [partijen](#partij) hebben in de omgang met gegevens. De afspraken in het afsprakenstelsel waar deelnemers zich aan kunnen committeren noemen we [deelnameafspraken](#deelnameafspraak). De [deelnameafspraken](#deelnameafspraak) worden bijgehouden in een [afsprakenboek](#afsprakenboek).

Het afsprakenstelsel wordt beheerd door de [stelselhouder](#stelselhouder), op dit moment de facto de CDO van het Ministerie van Justitie en Veiligheid.

### Gegevenscasus

In het afsprakenstelsel vervullen de deelnemers [rollen](#rol) op [gegevenscasussen](#gegevenscasus).

Een [gegevenscasus](#gegevenscasus) betreft altijd een bepaalde [gegevensset](#gegevensset). Een gegevenscasus kan gerelateerd zijn aan een andere gegevenscasus in een [gegevenscasus relatie](#gegevenscasus-relatie), als deze gerelateerde gegevenscasus op minimaal één gegeven overlapt met de andere gegevenscasus.

Een gegevenscasus kunnen we onderscheiden in meerdere [gegevenscasus soorten](#gegevenscasus-soort):

* [gegevensdeling](#gegevensdeling),
* [gegevensduiding](#gegevensduiding) en
* [gegevensvoering](#gegevensvoering).

Deze soorten volgen elkaar op. Welke soort op welke andere volgt geven we aan in de [gegevenskring](#gegevenskring). Voor nu is de volgorde: gegevensdeling -> gegevensduiding -> gegevensvoering -> gegevensdeling -> et cetera.

Hiermee kunnen we gegevenscasus beter definieëren: een gegevenscasus is het gezamenlijk moment uit het leven van één of meer gegevens (de gegevensset), waarin de gegevensset onderwerp is van één gegevensduiding, gegevensdeling of gegevensvoering.

Een gegevenscasus met gedefinieerde rollen (op basis van de [gegevenscasus soort](#gegevenscasus-soort)) is een [vertrouwenscasus](#vertrouwenscasus-0).

### Vertrouwenscasus

Een [deelnemer](#deelnemer) is een [partij](#partij) die deelneemt aan minimaal één [gegevenscasus](#gegevenscasus) in een bepaalde rol. Daarmee wordt de gegevenscasus een vertrouwenscasus. In een [vertrouwenscasus](#vertrouwenscasus-0) zijn er telkens drie soorten rollen aanwezig op een gegevenscasus:

* [eindverantwoordelijke](#eindverantwoordelijke) rol
* [inhoudelijk baathebbende](#inhoudelijk-baathebbende) rol
* [niet-inhoudelijke derde](#niet-inhoudelijke-derde) rol

Deze krijgen verschillende namen, afhankelijk van het soort casus waar ze op van toepassing zijn.

Welke rol bij welke soort gegevenscasus hoort wordt gedefinieerd in [rol voor gegevenscasus van soort gegevenscasus](#rol-voor-gegevenscasus-van-soort-gegevenscasus). Op een vertrouwenscasus hoeven niet alle rollen te zijn ingevuld met deelnemers, maar wel minimaal één. Er kan slechts één [eindverantwoordelijke rol](#eindverantwoordelijke-rol) per casus worden ingevuld.

Elke [soort gegevenscasus](#gegevenscasus-soort) kent deze drie rollen, maar voor elke gegevenscasus soort worden ze anders genoemd en krijgen ze andere taken en verantwoordelijkheden.

* [gegevensdeling](#gegevensdeling)
    * [eindverantwoordelijke](#eindverantwoordelijke) rol: [deler](#deler)
    * [inhoudelijk baathebbende](#inhoudelijk-baathebbende) rol: [ontvanger](#ontvanger)
    * [niet-inhoudelijke derde](#niet-inhoudelijke-derde) rol: [ontsluiter](#ontsluiter)

* [gegevensduiding](#gegevensduiding)
    * [eindverantwoordelijke](#eindverantwoordelijke) rol: [duider](#duider)
    * [inhoudelijk baathebbende](#inhoudelijk-baathebbende) rol: [opsteller](#opsteller)
    * [niet-inhoudelijke derde](#niet-inhoudelijke-derde) rol: [opmaker](#opmaker)

* [gegevensvoering](#gegevensvoering)
    * [eindverantwoordelijke](#eindverantwoordelijke) rol: [voerder](#voerder)
    * [inhoudelijk baathebbende](#inhoudelijk-baathebbende) rol: [gebruiker](#gebruiker)
    * [niet-inhoudelijke derde](#niet-inhoudelijke-derde) rol: [geleider](#geleider)

De rol bepaalt uiteindelijk de taken en verantwoordelijkheden die een partij op zich neemt, door zich te committeren aan de bij de rol behorende [deelnameafspraken](#deelnameafspraak). Daartoe [omvat de rol deelnameafspraken](#rol-omvat-deelnameafspraak).
