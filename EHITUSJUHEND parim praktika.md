## Ehitusjuhend: parim praktika

_Käesolev parima praktika koond on koostatud Riigi Infosüsteemi Ameti asjatundjate poolt. Kasutatav mallina lepinguliste nõuete püstitamisel_

Tähistused
- __Tarkvaratoode__ - Täitja poolt teostatav , Tellijale üleantav tarkvara, sh dokumentatsioon. Dokumentatsiooni osaks on ehitusjuhend.

Põhinõuded
- Üleantava __Tarkvaratoote__ ehitusjuhend peab tagama, et ehitamise protsess on korratav.
- Ehitusjuhend peab tagama, et juhendi abil saab tavalise IT ettevalmistusega inimene protsessi edukalt läbi teha. Eriteadmiste vajadus tuleb selgelt välja tuua.
- Ebakvaliteetne ehitusjuhis (täpsemini ehituse korratavus) on oluline barjäär uute arendajate kaasamiseks. Teinekord on mõistlik lihtsuse huvides hoida protsess natuke pikem aga lihtsam, kui "kavalalt" lühike, aga keskmise arendaja jaoks mitte hoomatav-korratav.
- Teha selget vahet võrgust sõltuvatel ja võrgust sõltumatutel etappidel.
- Kui tarkvara sisaldab mingit allkirjastamist, peab see olema selgelt dokumenteeritud ja tarkvaratehniliselt võimalikult isoleeritud "ehitusprotsessist" - võtmemajanduse rakendamise huvides.

Koosseis
- Ehitusjuhendit käsitame koos ehitusskripti(de)ga; juhend moodustab skriptidega koos ühe terviku.
-	Ehitusjuhend on osa __Tarkvaratoote__ dokumentatsioonist; lisada asjakohased viited teistele __Tarkvaratoote__ dokumentatsiooni osadele.

Sihtrühm
-	Ehitusjuhendil on mitu sihtrühma:
  -	Tellija infraosakonna töötaja, kes ehitab ja koostab paigalduspaketid publitseerimiseks
  - __Tarkvaratoodet__ kasutav andmekogu omanik, kes ehitab oma tarbeks (oma andmekogule paigaldamiseks)
  - __Tarkvaratoote__ edasiarendaja
  - põhimõtteliselt igasugune lähtekoodi tarbija (eriti avatud lähtekoodi puhul).

Ehitamise sisendid
-	__Tarkvaratoote__ lähtekood, nii nagu see on üle antud Tellijaga kokkulepitud koodivaramusse.
- Vähegi keerukama tarkvara puhul on alustuseks vaja saada terviklik lähtekood (a la kas on `git checkout` või `git checkout --recursive` või veel hoopis kolmandat), rääkimata teekide sõltuvustest.
-	Teadmine (ja tehtud valik), millise paigalduskonfiguratsiooni jaoks __Tarkvaratoode__ ehitatakse. Kuna __Tarkvaratoodet__ võib paigaldada mitmes erinevas konfiguratsioonis, siis tuleb ehitusjuhendi koostamisel analüüsida ja teha ettepanek, millise konfiguratsiooni või konfiguratsioonide jaoks Tellijal oleks otstarbekas paigalduspaketid publitseerida. Oma tarbeks __Tarkvaratoodet__ ehitavale kasutajale peab olema juhendis selgitatud – ja ehitusskriptid peavad seda toetama – kuidas ta omale vajaliku konfiguratsiooniga __Tarkvaratoote__ saab ehitada. Ehitusjuhend ei pea erinevaid paigalduskonfiguratsioone detailselt seletama, kui seda tehakse __Tarkvaratoote__ rakendusjuhendis (küll aga peab rakendusjuhisele viitama).
- Selgitada, kuidas Tellija soovib tarkvara paigalduspakette publitseerida: kas Tellija laseb Täitjal tarnida paigalduspaketid ja publitseerib need (kas GitHubis või Tellija oma varamu või veebilehe kaudu) või ehitab Tellija ise paigalduspaketid. 

Ehituskeskkonna ettevalmistamine
-	Ehitusjuhendis tuleb selgelt kommunikeerida nõuded ehituskeskkonnale (arvuti, operatsioonisüsteem, süsteemitarkvara, ehitamise abivahendid, teegid).
-	Eeldame, et ehitatakse masinas, kuhu on paigaldatud sama operatsioonisüsteem, mida kasutatakse ka __Tarkvaratoote__ käitluskeskkonnas (nt Ubuntu 14.04 LTS).
-	Ehitusvahendi (nt Maveni või Gradle) puhul näidata, kas piisab ehitusvahendi standardkonfiguratsioonist või on vaja ehitusvahendit veel kuidagi seadistada.
-	Kui on vaja teeke vm komponente või vahendeid, mida operatsioonisüsteemi ja ehitusvahendi standardkoosseisus ei ole, siis näidata kust ja kuidas need paigaldada. 

Ehitamine
-	Ehitamise protsess vastavalt kasutatud programmeerimiskeele rakenduste üldlevinud heale praktikale. Sisaldab kompileerimist, ühiktestide täitmist, ehitamist, pakendamist.
-	Selgelt näidata protsessi sammud.
-	Sammude puhul selged ja täpsed juhised.
-	Sammude edukuse kriteeriumid, kohtades, kus see on võimalik ja otstarbekas
-	Kui sammu täitmist saab kontrollida, siis näidata, kuidas seda teha
-	Veateadete esitamine

Ehitamise väljund
-	Ehitamise väljundiks on __Tarkvaratoote__ paigalduspakett (üks või mitu paketti).
-	Kirjeldada, kuhu see tekib ja millest see koosneb (eeldame põhiteadmisi __Tarkvaratootes__ kasutatud programmeerimiskeelest).

Paigaldamine
-	Ehitamisprotsessile järgneb paigaldamisprotsess. Paigaldamisprotsessi käsitletakse __Tarkvaratoote__ rakendusjuhendis. Ehitusjuhend ja paigaldamisprotsessi käsitlus rakendusjuhendis peavad üksteisega haakuma ja olema kooskõlas.

Ehitusskript
- Soovitavalt üks skript, mis kontrollib keskkonnanõudeid, oskab paigaldada-käivitada-rollbackida jne.
- Kui ühe skriptiga pole võimalik või otstarbekas, siis mitu skripti; näidata selgelt, mis järjekorras skripte käivitada ja mida inimene vahel peab tegema.
- Teinekord vajab osade sõltuvuste või vahendite paigaldamine inimlikke (ühekordseid) tegevusi. Neid ei saa (ei ole mõistlik) skripti sisse panna, küll aga kirjeldada (Windows, OSX puhul eriti).
- Skript võib katta ka paigaldamist jm ehitamisega seonduvaid tegevusi, sellisel juhul peab olema võimalik valida, mida teha.
- Skript peab olema kommenteeritud.
- Kui on tegevusi, mis vajavad erinevate tasemega pääsuõigusi , siis kaaluda tegevuste lahutamist eraldi skriptidesse (nt `sudo` õigustega tegevused ühes, tavakasutaja õigustega teises). 

Vormistus
-	Markdown fail

Ehitusjuhendi vastuvõtmine
-	Ehitusjuhendi vastuvõtmisel teeb Tellija infraosakonna töötaja ehitusprotsessi juhendi alusel läbi. Samuti kontrollitakse juhendi sisulist ja vomistuslikku täielikkust ja piisavat detailsust. Tõrke korral (juhend arusaamatu või ehitamine ei õnnestu) antakse Täitjale kohe teada ja üritatakse ühistöös leida tõrke põhjus. Kui tõrke põhjus on kõrvaldatav ehitusjuhendi kiire muutmisega (pisiparandus), siis tehakse kiire parandus ja korratakse test-ehitamist. Tõsisemate probleemide korral fikseeritakse üleantud töös puudus.
