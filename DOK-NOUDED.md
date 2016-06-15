## Nõuded üleantavale dokumentatsioonile

(mudeldokument)

Käesolev dokument esitab kogumi üldisi nõudeid ja soovitusi arendusprojektides Täitjate poolt Tellijale üleantavatele dokumentidele.
Osa nõudeid võivad olla diskuteeritavad. Kõik nõuded ei tarvitse olla universaalselt rakendatavad. 
Nõuete ja soovituste osalise või täieliku kohaldamise projektis otsustab projektijuht. Nõudeid saab kohaldada ka asutusesiseselt.
Arvamused ja ettepanekud on teretulnud (GitHub-i Issue ja Pull Request). 

1.	Üldine
    1.	Üleantav dokumentatsioon peab moodustama ühtse terviku, seda nii sisu, struktuuri kui ka vormistuse poolest.
    2.	Üldreeglina peab ka iga üksik dokument moodustama eraldikäsitletava terviku.

2.	Tähtsus
    1.	Dokumentatsiooni eesmärk on projekti tulemuste kindel fikseerimine ja teabe selge ning efektiivne kommunikatsioon erinevatele sihtrühmadele.
    1.	Eelistatud on kompaktsed, põhjalikult ettevalmistatud, küsimusi sisuliselt käsitlevad ja asju seletavad, korrektselt vormistatud dokumendid, mida on ka kerge ajakohasena hoida.
    1.	Dokumentatsioon ei tohi olla formaalne ega dokumentatsiooni suurele mahule orienteeritud. 
    1. Arvestagem agiilse IT-arenduse põhimõttega *Working software over comprehensive documentation*, http://www.agilemanifesto.org/.
    1.	Koodi kvaliteet ja dokumentatsiooni kvaliteet on võrdselt tähtsad.
    1.	Programmeerimises on väljakujunenud praktika stiilijuhiste kasutamine (vt nt [Google programmeerimise stiilijuhised](https://github.com/google/styleguide/)). Täpselt samamoodi on kvaliteetse dokumentatsiooni loomiseks vaja vormistuslikke kokkuleppeid.

3.	Vormivabadus
    1.	 Käesolevate nõuete kohaldamisel on esmatähtis nõude eesmärk ja mõte, mitte nõude vorm.
    1.	Dokumendis on primaarne sisu, mitte vorm.
    1.	Konkreetsele sisule asjakohase vormi leidmine on dokumendi koostaja ülesanne.
    1.	Käesolevad nõuded ei kirjuta ette kivisseraiutud vorme, vaid pakuvad malle, mille kasutamine reeglina hõlbustab kommunikatsiooni.

4.	Sisukorradokument
    1.	Enamast kui ühest dokumendist koosneval dokumendipaketil peab olema eraldiseisev sisukorradokument (ingl Documentation Master List).
    1.	Sisukorradokument peab sisaldama üleantavate dokumentide täielikku loetelu. Iga dokumendi kohta tuleb esitada (minimaalselt) nimetus, viimase versiooni number ja versiooni loomise kuupäev.
    1.	Üleantava dokumentatsiooni komplekt, sh nimetused peavad vastama hankedokumendis, lepingus ja Tellijaga projekti käigus kokkulepitule. 

5.	Esileht
    1.	Dokumendi tiitel- või esilehel esitatakse teave dokumendi Tellija ja Täitja kohta. Organisatsiooni (ettevõtte) nimi esitakse ametliku täisnimena.
    1.	Üleantavat dokumenti ei vormistata ettevõtte blanketil ega ettevõtte kujundusmallil.

6.	Logo
    1.	Esi- või tiitellehele võib paigutada Täitja logo. Sellisel juhul paigutatakse esilehele ka Tellija (Riigi Infosüsteemi Ameti logo). Kui projektis on rohkem partnereid, siis paigutatakse kõigi logod.
    1.	Logo ega autoriõiguse märget ei korrata esi- või tiitellehele järgnevatel lehekülgedel.
    1.	Struktuuritoetuse abil rahastatud projektis tuleb dokumendi päisesse paigutada struktuuritoetuse logo. Juhised vt http://www.struktuurifondid.ee/kujundusfailid-20142020/.  
    1.	Näide: Ernst & Young (2013) Protsessianalüüsi käsiraamat, https://www.mkm.ee/sites/default/files/protsessianaluusi_kasiraamat.pdf.

7.	Keel
    1.	Dokument peab vastama õigekeelsusnormidele. Tekst peab olema keelelt ja stiililt korrektne. *Märkus*. IT erikeele üldtunnustatud tava võib mõnikord üldkeele normist lahkneda.
    1.	Terminoloogia peab olema läbivalt ühtne. Vastavalt vajadusele lisatakse sõnaseletused või definitsioonid; kui neid on rohkem, siis eraldi jaotisena.
    1. Keelekasutus peaks olema vaba eesti keelele mitteomasest lausestruktuurist.
    1. Eelistatud on omakeelsed sõnad.
    1. Tuleb kasutada valdkonnas väljakujunenud terminoloogiat.
    1. Eestikeelsete IT oskussõnade leidmisel on autoriteetsete sõnastike hulgas:
        1. [Andmekaitse ja infoturbe seletussõnastik](http://akit.cyber.ee/) (Cybernetica AS)
        1. [Standardipõhine tarkvaratehnika sõnastik](https://stats.cyber.ee/) (Cybernetica AS)
        1. Heikki Vallaste [E-sõnastik](http://www.vallaste.ee/)
    1. Muukeelseid IT-sõnastikke:
        1. [ISTQB Glossary of Testing Terms](http://www.istqb.org/downloads/category/20-istqb-glossary.html)
        1. [ISO/IEC/IEEE 24765 Systems and software engineering — Vocabulary](http://www.iso.org/iso/catalogue_detail.htm?csnumber=50518)
    2. EL mitmekeelne terminibaas [IATE](http://iate.europa.eu/).
    2. Asjakohases stiilis. Tehniline dokumentatsioon reeglina ametlikus stiilis. Vaba kantseliidist. Ametliku sisuga kirjaliku teksti toimetamisel on heaks abiliseks [Ametniku soovitussõnastik](http://www.eki.ee/dict/ametnik/ametnik.html).

8.	Failinimed ja URL-id
    1. Failide nimed ja samuti URL-id peavad olema süsteemsed ja informatiivsed.
    1. Kui Tellija ei ole mustrit ette andnud, siis valib Täitja ise otstarbeka nimemustri.
    1. Versioneeritava dokumendi failinimetuses kaaluda versiooninumbri lisamist.
    1. Kuupäeva kasutamisel failinimes kasutada kuju AAAA-KK-PP (mitte AAKKPP, PP.KK.AAAA vms).
    1. Avalikult esitletavad failid peaksid saama inimesele kergesti loetavad nimed. Näiteks:
        1. [https://www.ria.ee/public/RIA/Cryptographic_Algorithms_Lifecycle_Report_2016.pdf](https://www.ria.ee/public/RIA/Cryptographic_Algorithms_Lifecycle_Report_2016.pdf)
    1. Kirjandus:
        1. European Commission (2012) [10 rules for persistent URIs](http://ec.europa.eu/isa/news/2013/10-rules-and-good-practices-for-designing-persistent-uris_en.htm)

8.  Nummerdamine
    1. Nummerdamise peamine eesmärk on dokumendi osistele viitamise hõlbustamine.
    1. Lehekülgede nummerdamisel on sageli kasu X (Y) kujust.

9.	Kujundus
    1.	Kujundus peab olema läbivalt ühtne.
    1.	Kujunduse eeskujuks on Riigi Infosüsteemi Ameti asjaajamiskord. Asjaajamiskorra saab RIA-poolselt projektijuhilt.

10.	Joonised
    1.	Joonised üldreeglina nummerdatakse.
    1.	Valitud tähistussüsteemid peavad arvestama lugejaskonna ettevalmistustaset. Vajadusel lisatakse legend või kasutatud tähistuste lahtiseletus.

11.	Versioneerimine
    1.	Üldreeglina dokumendid versioneeritakse. Soovitatav on järgida kokkulepet, et 0.n tähistab tööversiooni, 1.0 – valmisversiooni.
    1.	Üldreeglina näidatakse versiooni numbriga koos ka versiooni valmimise kuupäev.
    1.	Dokumente püütakse hoida ajakohasena.
    1.	Vanad versioonid ja tähtsuse kaotanud dokumendid arhiveeritakse ja „kõrvaldatakse pildilt“.
    1.	Dokumentides ja dokumentide kogumites järgitakse põhimõtet „kõige tähtsam esikohale“.

12.	Kontekst
    1.	Dokumendis tuleb esitada dokumendi mõistmiseks hädavajalik taustateave (dokumendi kontekst).
    1.	Dokumendist peab olema võimalik aru saada, millise toote, süsteemi ja/või projekti juurde dokument kuulub. Standardseks võtteks on toote, süsteemi ja/või projekti nime selge väljatoomine, nt iga lehekülje päises.
    1.	Üldreeglina tuleb dokumendis viidata teistele dokumentidele, mis on vajalikud dokumendi mõistmiseks. Viited peavad olema täpsed. Dokumendi nimetuse muutmisel tuleb ajakohastada ka viited dokumendile.

13.	Eesmärk
    1.	Kohe dokumendi alguses sõnastatakse lahendatav ülesanne ja/või dokumendi eesmärk.
    1.	Vajadusel määratletakse dokumendi käsitlusala (skoop) ja sihtrühm(ad).

14.	Struktuur
    1.	Tekst liigendatakse otstarbekalt.
    1.	Pikemas dokumendis koostatakse sisukord.

15.	Dokumendivormingud
    1.	Dokumendivormingute valikul lähtutakse eelkõige lugejate eelistustest.

16.	Erinõuded
    1.	Lähtudes dokumendi valdkonnast kohalduvad erinõuded ja/või valdkonna dokumenteerimise hea tava. RIA on käesolevaks ajaks välja töötanud järgmised erinõudeid määratlevad doku-mendid:
        1.	[arhitektuuri mall](https://www.ria.ee/ee/valmis-abivahend-andmekogude-arhitektuuri-dokumenteerijatele.html);
        1.	[protokollide spetsifitseerimise parim praktika](https://github.com/e-gov/Open-Workflow/blob/master/ProtokollideParimPraktika.md);
        1.	olemite-suhete andmemudeli dokumenteerimisnõuded.
    1.	Dokumenteerimise erinõudeid sisaldavad dokumendid või viited nendele lisatakse hankedokumentidele.

17.	Kvaliteedikontroll
    1.	 Üleantav dokumentatsioon peab olema läbinud tekstiredaktori õigekirjakontrolli ja/või inimtoimetaja kontrolli.
    1.	Üleantav lõplik dokumentatsioon ei tohi sisaldada TODO märkmeid, töömärkmeid, muutuste jälitamise märkeid, veerukommentaare ega muid „lahtisi otsi“. Võimalikud lahendamata jäänud küsimused ja probleemid tuuakse välja eraldi jaotises.
    1.	Tellijapoolne projektijuht kontrollib üleantavate dokumentide komplektsust ja vormistusnõuete täitmist.
    1.	Vormistusnõuete täiemahuline järgimine on soovitatav juba projekti vältel Tellijale esitatavates kavandites, töö- ja vaheversioonides jms.
