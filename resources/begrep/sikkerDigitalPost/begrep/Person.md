---
title: Person 
permalink: sdp_person.html
sidebar: begrep_sidebar
---

|---|---|
|Term|{{page.title}}|
|Definisjon|Person definert for Sikker digital post|
|Datatype|complexType|
|Kilde|DIFI|
|Kommentar|Person er [mottakeren](sdp_mottaker.html) som Digital Post skal sendes til.|

Merk at Person ikke er unik definert på tvers av Difi sine
felleskomponenter, men at hver av felleskomponentene har en definisjon
av Person i forhold til behovene i den enkelte felleskomponentene.

#### Attributer

| Term                                               | Kardinalitet | Datatype                                              |
| --- | --- | --- |
| [personidentifikator](personidentifikator.md) | 1..1         | [xs:string](http://www.w3.org/TR/xmlschema-2/#string) |
| [postkasseadresse](postkasseadresse.md)       | 1..1         | [xs:string](http://www.w3.org/TR/xmlschema-2/#string) |

#### Xml eksempel

``` 
<sdp:Person>
    <sdp:personidentifikator>01012295312</sdp:personidentifikator>
    <sdp:postkasseadresse>1</sdp:postkasseadresse>
</sdp:Person>

```
