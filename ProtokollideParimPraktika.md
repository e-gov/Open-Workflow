````
ABSTRACT
Protocol Specification Best Practice (in Estonian)
This document summarises the best practice of specification of data exchange protocols,
based on methodology and best practice documents of internationally recognized
standards developing organisations.
````
# Protokollide spetsitseerimise parim praktika

Versioon 1.0

16.06.2015

Käesolev dokument esitab andmevahetusprotokollide kirjeldamise ja
spetsifitseerimise parima praktika, lähtudes rahvusvaheliste
tunnustustatud, juhtivate standardeid väljatöötavate organisatsioonide
mitmesugustest metoodikajuhistest.

Parim praktika on on väljendatud nõuetena ja kontrollküsimustena.

Dokument on mõeldud protokollide projekteerijatele,
spetsifitseerijatele, kirjelduste ja spetsifikatsioonide kvaliteedi
kontrollijatele.

## Mõisted

*Andmevahetusprotokoll*, reeglite kogum, mida arvutid kasutavad andmete
võrgu kaudu saatmiseks ja vastuvõtmiseks. Protokoll muuhulgas määrab
edastatavate andmete formaadi, kasutatava veatuvastusmetoodika,
andmetihendusmeetodi ning selle, kuidas saatev seade annab teada, et
sõnumi edastamine on lõpetatud ning kuidas vastu võttev seade annab
teada, et sõnum on edukalt vastu võetud.

*Spetsifikatsioon*, dokument, mis määratleb nõuded. Spetsifikatsioon on
spetsifitseerimise tulemus.

*Dokumendi* all mõistetakse käesolevas kirjutises terviklikku, ühtse
pealkirja alla koondatud, artiklite kogumit ning mille sisu, vorm ja
struktuur on küllaldane selles dokumendis hõlmatud faktide või tegevuse
kirjeldamiseks.

*Kirjeldus* – antud dokumendi raames on mõisted spetsifikatsioon ja
kirjeldus samaväärsed.

## Protokollide vormistamine

1  Kui tegemist on olemasoleva (rakendatud) protokolli kirjeldusega, siis peab kirjeldus olema esitatud sellise täpsusega, et selle alusel oleks võimalik aru saada olemasoleva protokolli toimimise kõikidest aspektidest. 

Kirjelduse ja selles kirjelduses viidatud dokumentides sisalduva teabe alusel peab olema võimalik realiseerida protokoll uuesti.

> Kvaliteedikontroll: Kas dokumendi kirjutamisel on järgitud käesolevas dokumendis kirjeldatud vormistuse nõudeid ja kirjelduse struktuuri nõudeid? (aktsepteeritav
vastus: jah)

2  Kui andmevahetusprotokolli kirjeldus on jagatud mitmesse dokumenti või kui protokoll on osa suuremast tervikust, mis kirjeldatakse teiste dokumentidega, siis peab dokumendi ülevaate jaotise järel paiknevas jaotises olema kirjeldatud nende dokumentide loend, mis annab ülevaate protokolli mõistmiseks vajalikust dokumentatsioonist (jaotis „Seotud dokumendid“). \[4\]

> Kvaliteedikontroll: Kas vaadeldava dokumendi mõistmiseks on vajalik mingite teiste dokumentide tundmine? (aktsepteeritavad vastused: jah ja ei)

> Kui on, siis kas andmevahetusprotokolli kirjeldavas dokumendis on jaotis, kus kirjeldatakse viited nendele dokumentidele? (aktsepteeritav
vastus: jah).

> Kui on, siis kas esitatud seotud dokumentide loend on ammendav? (aktsepteeritav vastus: jah)


3  Andmevahetusprotokolli kirjeldus peab sisaldama kasutatavate mõistete seletavat sõnastikku. Sõnastik võib olla vormistatud andmevahetusprotokolli osana (jaotis „Mõisted“) või vormistatud eraldi dokumendina. Viimasel juhul peab sõnastikule olema viidatud spetsifikatsiooniga seotud dokumentide nimistus (vt. nõue 2) \[1\] \[5\]

> Kvaliteedikontroll: Kas dokument sisaldab kasutatavate mõistete seletavat sõnastikku? (aktsepteeritavad vastused: jah ja ei)

> Kui ei, siis kas vaadeldava dokumendi seotud dokumentide jaotises on viide sõnastikku sisaldavale dokumendile (aktsepteeritav vastus: jah)

> Kas esitatud seotud mõistete loend (olenemata sellest, kas see asub vaadeldavas dokumendis või väljaspool seda) on ammendav?

4  Protokolli kirjeldus peab kinni pidama sõnastikuga normeeritud terminitest.

> Kvaliteedikontroll: Kas kõik protokolli kirjeldamisel kasutatud olulised mõisted on kirjeldatud mõistete loendis (vt. nõue 3)? (aktsepteeritav vastus: jah)

5  Protokolli spetsifikatsioonis peavad selgelt olema eristatavad normatiivsed ja informatiivsed määratlused. Normatiivne teave on see, millega kehtestatakse protokolli nõudeid selle rakendamisel. Informatiivne teave abistab nõuete mõistmisel. Normatiivne ja informatiivne teave peavad protokolli kirjelduses olema üheselt eristatavad. Eristus võib olla tehtud kas dokumendi jaotiste või/ja tekstilõikude tasemel. Samasse tekstilõiku ei tohi kirjutada korraga normatiivset ja informatiivsed teavet. \[6\] 

> Kvaliteedikontroll: Kas dokumendi kõigi tekstilõikude puhul on aru saadav, kas tekstilõik sisaldab normatiivset või informatiivset teavet)? (aktsepteeritav
vastus: jah)

6  Nõuete tugevuse tasemed peavad olema üksteisest selgelt eristatud. Peamiselt kasutatakse nõuete esitamisel sõnu „peab“, „on kohustuslik“, „ei tohi“, „tuleb teha“, „on vajalik“ ja „ei või. Tinglikku kõneviisi „“peaks“, „ei peaks“, „võiks“, „ei võiks“ ja sõnu „võib“, „tohib“, „ei pea“, „on soovitav“, „on vabatahtlik“ („on valikuline“) ning „ei ole vajalik“ kasutatakse ainult juhtudel, kui kirjelduses kirjeldatu rakendamise otsustamine jäetakse nõuete rakendajale \[7\]

> Kvaliteedikontroll: Kas nõuete tasemed kirjelduse erinevates osades on üheselt mõistetavad? (aktsepteeritav vastus: jah)

7  Kõik dokumendis kirjeldatud viited peavad olema jaotatud normatiivseteks ja informatiivseteks. Iga viite puhul peab olema üheselt aru saadav, kas tegemist on normatiivse või informatiivse viitega. Normatiivsed viited on need, mille lugemine on protokolli mõistmiseks vältimatult vajalik või mis sisaldavat tehnoloogiaid, mille tundmine ja olemasolu on protokolli teostamiseks vältimatult vajalik. Muud viited on informatiivsed. \[8\]

> Kvaliteedikontroll: Kas kõigi dokumendiviidete puhul on arusaadav, kas tegemist on normatiivse või informatiivse viitega? (aktsepteeritav vastus: jah)

## Protokolli kirjelduse struktuur

8  Iga spetsifikatsioon algab ülevaatega, mis annab lühidalt kuid ammendavalt ülevaate dokumendi tähendusest ja dokumendis kirjeldatust. Ülevaatest peab selguma millisele kasutajate sihtgrupile on dokument suunatud. (jaotis „Dokumendi skoop“). \[1\] \[4\]

> Kvaliteedikontroll: Kas dokumendil on olemas ülevaatejaotis? (aktsepteeritav vastus: jah)

> Kas ülevaatejaotis on dokumendi esimene jaotis? (aktsepteeritav vastus: jah)

> Kas ülevaate jaotis kirjeldab üheselt mõistetavalt dokumendi tähendust ja sisu? (aktsepteeritav vastus: jah)

9  Protokolli kirjeldus peab algama üldistatud kirjeldusega, kus sõnastatakse protokolli tähendus – millal, kus, milleks ja kes/mis antud protokolli kasutama hakkavad ja millist probleemi protokoll lahendab. Siin kirjeldatakse ära ka protokolli üldised omadused. Tegemist on nö. lühida eelkirjeldusega enne kui hakatakse protokolli detailselt kirjeldama. \[2\]

> Kvaliteedikontroll: Kas andmevahetusprotokoll algab ammendava lühiülevaatega protokolli tähendusest ja olulistest omadustest? (aktsepteeritav vastus: jahi)

10  Protokolli kirjeldus sisaldab protokolli arhitektuurilise ülevaate, mis sisaldab kirjeldavat teksti koos diagrammidega. Arhitektuuriline kirjeldus kirjeldab interaktsiooni osapooli, liikuvate sõnumite eesmärki. Kirjeldatakse: \[6, jaotis 2\] \[4, jaotis 2 ja 3\] \[2, jaotis 4.2\] \[9\]

-   protokolli kui terviku kõrgetasemeline arhitektuurilise vaate skeemi, mis sisaldab osapoolte struktuuri ja omavahelisi seoseid koos ammendava verbaalse kirjeldusega (protokolli)
-   peamised (olulised) andmeelemendid
-   olulised nõuded protokolli toimimisele
-   protokolli kasutamise osapoolte kirjeldused: nende poolt implementeeritav põhiline protokolli kasutamisega seotud funktsionaalsus
-   protokolli kihilisus ja erinevates kihtide omadused ja seal implementeeritav funktsionaalsus
-   olekudiagrammid (state machine diagrams) koos ammendava verbaalse kirjeldusega.
- protokolli oluliste omaduste kirjeldused, mis arhitektuurilises vaates selgelt ei eristu. Osa lisatakse siis kui on vaja täpsustada arhitektuurilises vaates kirjeldatut. \[4, jaotis 3\] \[2, jaotis 4.2\] \[9\]

> Kvaliteedikontroll: Kas dokumendis on olemas protokolli arhitektuurilise ülevaate kirjeldus? (aktsepteeritav vastus: jah)

>Kas protokolli arhitektuuriline ülevaade sisaldab:
> -   protokolli arhitektuurilise vaate skeemi koos ammendava kirjeldusega
> -   peamised (olulised) andmeelemendid
> -   olulised nõuded protokolli toimimisele
> -   osapoolte ja nende poolt protokolli kasutamisega seotud implementeeritava funktsionaalsuse kirjeldusi
> -   protokolli kihilisuse ja erinevates kihtides implementeeritava funktsionaalsuse kirjeldusi
> -   kõiki vajalikke olekudiagramme

> (aktsepteeritav vastus kõigile küsimustele: jah)

> Kas arhitektuuriline vaade vajab täpsustamist? (aktsepteeritavad vastused: jah ja ei)

>  Kui jah, siis kas protokolli oluliste omaduste kirjelduse jaotis on olemas? (aktsepteeritav vastus: jah)

>  Kas protokolli oluliste omaduste kirjeldused on ammendavad? (aktsepteeritav vastus: jah)

12  Edastatavate sõnumite struktuuride kirjeldused:

-   Sõnumites korduvalt kasutatavate andmestruktuuride kirjeldused so. selliste struktuuride kirjeldused, mida kasutatakse mitmetes erinevates sõnumites \[6, jaotis 3.1\]
-   Kõigi võimalike sõnumistruktuuride ammendavad kirjeldused.

> Kvaliteedikontroll: Kas eksisteerivad korduvalt kasutatavad andmestruktuurid? (aktsepteeritavad vastused: jah ja ei)

> Kui jah, siis kas korduvalt kasutatavad andmestruktuurid on kirjeldatud? (aktsepteeritav vastus: jah)

> Kas kõik võimalikud sõnumistruktuurid on kirjeldatud? (aktsepteeritav vastus: jah)

13  Sõnumite töötluse kirjeldused, kus kirjeldatakse millised tegevused peab protokolli käsitlusel läbima mingi konkreetse operatsiooni tegemisel. \[6, kõik jaotised, mille pealkiri sisaldab teksti „Processing rules“\]

> Kvaliteedikontroll: Kas ammendavad sõnumite töötluse kirjeldused on olemas? (aktsepteeritav vastus: jah)

14  Veateadete kirjeldused so. protokolli kõikide veasituatsioonide kirjeldused koos vea tekkimise oleku ja vea verbaalse, ühetähendusliku kirjeldusega.

> Kvaliteedikontroll: Kas veasituatsioonid on ammendavalt kirjeldatud? (aktsepteeritav vastus: jah)

15  Protokolli olekudiagrammide kirjeldused vastu võetud teatete ja saavutatud olekute lõikes \[1, jaotis 3.3\]

> Kvaliteedikontroll: Kas protokolli olekudiagrammide kõik kirjeldused on olemas? (aktsepteeritav vastus: jah)

16  Protokolli erinevate aspektide konstrueerimise kaalutlused (design considerations) \[6, jaotis 4\]

> Kvaliteedikontroll: Kas disaini kaalutlused on kirjeldatud? (aktsepteeritav vastus: jah)

17  Vastavusklausel (conformance clause) on spetsifikatsiooni osa, mis ühte kohta koondatult määratleb kõik nõuded, mida protokolli teostav süsteem peab täitma, et väita end protokolliga vastavuses olema. \[10, jaotis 2.1\]

> Kvaliteedikontroll: Kas vastavusklausel on kirjeldatud? (aktsepteeritav vastus: jah)

18  Vastavusmudeli kirjeldus, mis spetsifitseerib, kas protokolli saab realiseerida ka osaliselt st. kas protokoll näeb ette mitmeid erinevaid profiile. \[11\]

> Kvaliteedikontroll: Kas vastavusmudel on kirjeldatud ammendavalt? (aktsepteeritav vastus: jah)

## Kirjandus

\[1\] RFC 2360 „Guide for Internet Standards Writers“,
[*https://tools.ietf.org/html/rfc2360*](https://tools.ietf.org/html/rfc2360).

\[2\] RFC 4101 „Writing Protocol Models“,
[*https://tools.ietf.org/html/rfc4101*](https://tools.ietf.org/html/rfc4101).

\[3\] W3C Recommendation „QA Framework: Specification Guidelines“,
[*http://www.w3.org/TR/qaframespec/\#specifying-conformance*](http://www.w3.org/TR/qaframespec/#specifying-conformance).

\[4\] FIDO UAF Architectural Overview,
[*https://fidoalliance.org/wp-content/uploads/html/fido-uaf-overview-v1.0-ps-20141208.html*](https://fidoalliance.org/wp-content/uploads/html/fido-uaf-overview-v1.0-ps-20141208.html).

\[5\] FIDO Technical Glossary,
[*https://fidoalliance.org/wp-content/uploads/html/fido-uaf-overview-v1.0-ps-20141208.html*](https://fidoalliance.org/wp-content/uploads/html/fido-uaf-overview-v1.0-ps-20141208.html).

\[6\] FIDO UAF Protocol Specification v1.0,
[*https://fidoalliance.org/wp-content/uploads/html/fido-uaf-protocol-v1.0-ps-20141208.html*](https://fidoalliance.org/wp-content/uploads/html/fido-uaf-protocol-v1.0-ps-20141208.html).

\[7\] Key words for use in RFCs to Indicate Requirement Levels,
[*https://www.ietf.org/rfc/rfc2119.txt*](https://www.ietf.org/rfc/rfc2119.txt).

\[8\] IESG Statement: Normative and Informative References,
[*https://www.ietf.org/iesg/statement/normative-informative.html*](https://www.ietf.org/iesg/statement/normative-informative.html).

\[9\] Mozilla BrowserID Protocol Overview,
[*https://developer.mozilla.org/en-US/Persona/Protocol\_Overview*](https://developer.mozilla.org/en-US/Persona/Protocol_Overview).

10\] W3C QA Framework: Specification Guidelines,
[*http://www.w3.org/TR/qaframe-spec/\#specifying-conformance*](http://www.w3.org/TR/qaframe-spec/#specifying-conformance).

\[11\] W3C Variability in Specifications,
[*http://www.w3.org/TR/spec-variability/*](http://www.w3.org/TR/spec-variability/).
