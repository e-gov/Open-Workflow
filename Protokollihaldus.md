# Protokollihaldus

##Mõisted

__protokoll__ tähendab siin lisaks andmevahetusprotokollidele ka teisi olemuslikult standardina toimivaid artefakte (nt XML skeeme, masinloetavate vormingute spetsifikatsioone). Standardina toimimine tähendab seda, et artefakti kasutajate ring on lai ja kasutajaid ei saa ammendavalt üles lugeda.

__vara__, standardina toimivaid artefakte võib nimetada ka „varadeks“.

##Nõuete keel

Läbiva suurtähega esitatud sõnu tuleb tõlgendada järgmiselt (vrdl [RFC 2119]): ”PEAB”, “TOHIB AINULT” – protsessi rakendaja ei saa deklareerida protsessi vastavust, kui nõue on täitmata. “PEAKS” - nõue ei pea tingimata olema implementeeritud, kuid implementatsiooni saab lugeda protsessimudelile vastavaks ainult siis, kui nõude täitmisest kõrvalekaldumiseks on kaalukas põhjus. “VÕIB” - omadust võib implementeerida; mitteimplementeerimist ei pea põhjendama.

## Protokollihalduse eesmärgid

Protokollihalduse peamisteks eesmärkideks on protokollide jm standarditena kasutatavate varade kasutajatele kättesaadavaks tegemine, varade ühelt poolt stabiilsus ja teiselt poolt muutmisvajaduste kontrollitud, kaalutletud ja kvaliteetne rahuldamine.

## Protokollihalduse miinimumnõuded 

1.  Avaldamiskoht. Protokollil PEAB olema ühene stabiilne, kasutajatele kättesaadav avaldamiskoht
2.  Omanik. Protokollil PEAB olema selge omanik (organisatsioon või üksus). Teave omaniku kohta PEAB olema kõigile selgelt nähtav.
3.  Vastutav isik. Omanikukohustus PEAB olema viidud isiku tasandile.
4.  Ettepanekute haldus
  - PEAB olema selgelt kommunikeeritud võimalus teha ettepanekuid vara edasiarendamiseks
  - Ettepanekute registreerimiseks, läbivaatamiseks ja muutmisotsuste tegemiseks PEAB olema protsess, mis tagab kõigi ettepanekute selge formuleerimise, analüüsi, hindamise ja otsuse tegemise mõistliku aja jooksul.
  -  Muutmistegevused PEAVAD olema läbipaistvad ja jälgitavad (ingl traceable); selleks PEAB olema korraldatud asjakohane dokumenteerimine.
  - Muudatuse dokumenteerimine PEAB sisaldama kaalutlusi ja põhjendusi, mille alusel muudatus on tehtud.
5.  Versioonihaldus
Varale PEAB olema rakendatud versioonihaldus. PEAKS kasutama semantilist versioneerimist (http://semver.org/). 
