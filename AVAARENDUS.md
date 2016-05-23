
## Avaarendusest

### Mis asi on avaarendus?

Avaarendus on: 1) arendusprotsess, mis olulistes momentides on avatud, läbinähtav, transparentne – interneti vahendusel, kogu maailmale; 2) ekstrovertne arendus; 3) sageli agiilne arendus; 4) sageli kaasav, sotsiaalne arendus; 5) toimub reeglina GitHubis.

Avaarendus ei ole: suletud arendus, mis lõpeb valmis koodi väljapanemisega.

Avaarendus on sageli kaasav, kuid igasugune avaarendus ei ole automaatselt kaasav. Mitmeid laialt tuntud tarkvarasüsteeme (Linux, Python) avaarendatakse nn „heatahtliku diktaatori“ ([_benevolent dictator for life_](https://en.wikipedia.org/wiki/Benevolent_dictator_for_life)) mudeli alusel.

### Avaarendus tähendab siis GitHubis arendamist?
GitHub on praegu juhtiv tarkvara avaarenduse keskkond. Koodi hoitakse koodihoidlates (repod), samas on võimalik hoida dokumentatsiooni (eelistatult Markdown märgendkeeles). Koodihoidla juures on võimalik pidada vikit, luua ja hallata tööülesandeid (Issues). Arenduses võivad osaleda paljud koodihoidlad. Koodihoidlate sünkroonimine toimub Git protokolliga. Järgnevas eeldame, et avaarendus käib GitHubis.

### Avaarendus on seega internetis avalikult programmeerimine?
Tarkvara elutsükkel piirdu programmeerimisega. Kui 3-kuulisele programmeerimisprojektile eelneb 12 kuud kavandamist, arhitektimist, hankimist, süsteemianalüüsi ja disaini, siis tekib küsimus, kas neid tegevusi võiks ka avamudeli järgi teha. Vastus on lahtine. GitHub on eelkõige koodihoidla.

### Mis kasu on avaarendusest?
Pragmaatilised kasud:
- kergem ja kiirem pääsuhaldus – lugemisõigus on vaikimisi kõigil; kirjutamisõiguste jagamine on koodihoidla omaniku käes. See võib olla mugavam, kiirem, turvalisem kui pääsuhaldus korporatiivkeskkonnas. Pääsuhalduse kulu ja keerukust sageli alahinnatakse. Kiire ja kerge pääsuhaldus on kiire arenduse üks oluline eeldus;
- kergem ja kiirem jagada arendusteavet – avalik koodihoidla on kättesaadav töölt, kodust, igalt poolt. Teave on viidatav;
- arendajale pakub GitHub head kasutajaliidest ja kasulikke funktsionaalsusi.

### Kas avaarendusest on lisaks sellele veel mingit kasu?
Sügavam kasu tuleb kiiremast ja laiahaardelisemast kommunikatsioonist:
- arendusse tulevad sisendid, mis muidu ei tuleks; arvamused, küsimused, ettepanekud – nii juhukülalistelt kui ka projekti kaastöölistelt; uued kaastöölised;
- arenduse tulemid lähevad varem kasutusse; Suletud arenduses teeme enne produkti valmis ja siis hakkame mõtlema kuidas seda maha müüa. teavituskampaaniad jms. Avaarendus võimaldab müüa juba vahetulemusi;
- tekivad koordinatsioonimustrid teiste projektidega, mis muidu jääksid tekkimata;
- teadmiste ja kogemuste liikumine;
- tööde kulgemisest on parem ülevaade; Näiteks, millal on programmeerija [ADIT](https://github.com/e-gov/ADIT)-is viimati toimetanud? 
Kuid - arendusse täiendavalt tulevad sisendid võivad olla ka negatiivsed: projektist saadakse teada, hakatakse kaikaid kodaratesse torkama või tapetakse projekt üldse ära, idee varastatakse jne. Teatud tingimustes saab teatud projekte teha ainult varjatult. Avalikult arendatava mõttetu projekti mõttetus tuleb varem ilmsiks.
Avaarenduse kasud on mitmesugused; osalt ehk ka raskesti tajutavad ning raskesti sõnastatavad.

### Kas avaarendust kasutavad ainult marginaalid ja häkkerid?
Facebook, Google, Twitter jne, aga samuti idufirmad eelistavad paljudel juhtudel avaarendust. Seda võib lugeda tugevaks empiiriliseks kinnituseks avaarenduses kasust.

### Kas avaarendust kasutatakse ka Eesti avalikus sektoris?
Eesti avalikus sektoris käib samal ajal hinnanguliselt 200-300 arendusprojekti. Avamudelit kasutavad neist vaid üksikud, üks loetelu vt https://github.com/e-gov/Open-Workflow. "GitHub and Government" https://government.github.com/community/ edetabelis on Eesti Soomest isegi kriipsu võrra ees (6 projekti soomlaste 4 vastu). RIAs – ja Eesti avalikus sektoris – kõige kaugemal kahtlemata on e-ID valdkond. Võrdluseks, USAs on üle 200 asutuse publitseerinud üle 4000 GitHubi koodihoidla http://gsa.github.io/github-federal-stats/.

### Töövoog avaarenduses
Praktilisi küsimusi (koos vastuste ettepanekutega):
- kas ma tohin endale GitHubi konto teha? – Jah.
- kuidas ma teen endale GitHubi konto? – https://github.com/join. 
- kas ma tohin ise repo teha? – Tohid küll.
- kuhu ma repo teen? – Uuri, kas asutusel on GitHubis organisatsioonikonto. Kui on, siis selle organisatsioonikonto alla. Selgita välja, kes on organisatsioonikonto haldurid. Küsi neilt ligipääsu.
- kui palju arenduste tellija peab teadma Gitist? – Git on protokoll, millega saab koodihoidla sisu versioone hallata ja erinevate koodihoidlate sisu sünkroniseerida.
- kes ja kuidas jagab pääsuõigusi? (Avaarendus ei saa läbi pääsuõigusteta) – vt p 3. Omaloodud koodihoidlas jagad ise.
- kuidas toimub varundamine? – Varundamine on GitHubis lihtne. Git protokolli abil tuleb luua koodihoidla kloon ja seda perioodiliselt sünkroonida.
Kas vajame asutuse „avaarenduse poliitikat“, protseduure, avaarenduse strateegiat jms?

### Mida avaarenduse puhul arenduslepingus sätestada?
Tavapärased arenduslepingud ei toeta avaarendust:
- „Tööde tegemise käigus loodud originaalteosed“ – mis on teos avaarenduses?
- „Töövõtja loovutab Tellijale täielikult ja tagasivõetamatult varalised õigused originaalteostele ning annab Litsentsi isiklikele õigustele Tööde üleandmise hetkest“ – milline on avalikult väljapandud asja staatus enne üleandmist? Kas ostame tulemeid või tööd?
Standardvormelid töötavad – seni, kuni ühel hetkel on probleem? 

### Mis on avaarenduse ohud?
Nii nagu on leitud 50 põhjust, miks andmeid ei saa avaandmetena välja panna, on tõenäoliselt ka 50 põhjust, miks avalikult arendada ei saa:
- kui arendushanke ettevalmistamine paistab internetist välja, siis võivad firmad ettevalmistust mõjutada. (Aga kas see on alati halb?);
- kui internetist paistavad välja hanget ettevalmistavate ametnike nimed, siis võivad firmad tagaukse kaudu endale soodsaid hanketingimusi sisse suruda. (See on kindlasti halb);
- pooliku asja väljapanemine on ohtlik. Võidakse valesti tõlgendada. (Arendada tuleks nii, et iga vahetulemus on „töötav“);
- arenduse tulemeid, eelkõige koodi, mida ei ole testitud, valideeritud, verifitseeritud jne ei tohi välja panna, sest keegi võib seda kasutada ja vigase koodiga endale või teistele kahju tekitada. (Vt eelmine p).

### Milliseid vastuargumente avaarendusele veel saab leida? 
- pooleliolevat tööd ei saa avaldada, sest seal võib olla vigu või puudusi, mis näitavad välja autori rumalust. (Kas see pole mitte tavaarenduse allasurutud hirmude ülekandmine? Mis on viga tarkvara arenduses? Juhtimisviga? Raske juhtimisviga? Arhitektuuriline prohmakas? Programmeerimisviga? Bugi? Eksimus koodi stiilireeglite vastu? Õigekirjaviga? Näpuviga? Seis, kus selgub, et midagi tuleb ümber teha? Hirm vea ees ja selle ületamine. Iga lähteülesandes/spekis/arenduslepingus olevat puudust kasutab IT-firma kohe ära. Perfektsed ülesandepüstitused/spekid. Kindlad lepingud. Koskmudel.);
- poolikut tööd ei ole põhimõtteliselt mõtet avaldada. Ainult valmis tulemust. (Seda põhimõtet võib aktsepteerida).
- meie arendused on juba avalikud. Hankeplaan on avalik.

### Millised võivad olla avaarenduse vastuargumendid, mida avalikult välja ei öelda?
Info on võim.

### GitHub brändib end kui Social Coding keskkonda. Mida see tähendab?
Programmeerijate sõbralikku kogukonda.

