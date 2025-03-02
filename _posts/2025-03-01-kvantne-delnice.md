---
layout: post
title:  "Ikarjev let: Precenjenost kvantnih delnic"
date:   2025-03-01 12:00:00 -0400
categories: Investing
---

# Uvod
V zadnjih treh mesecih smo priča novi špekulativni mrzlici, tokrat na
področju kvantnega računalništva. Nedavna objava Googla o napredku v
kvantnem svetu z novim čipom imenovanim »Willow« je še dodatno podžgala
že tako razgrete apetite malih tehnoloških vlagateljev, ki so zamudili
rast delnic, povezanih z umetno inteligenco, kot je \$NVDA in \$PLTR. V upanju na ponovitev zgodbe o hitrem obogatitvenem ciklu se je
množica vlagateljev usmerila v novo up vzbuajoče področje kvantenga
računalništva. Ameriška podjetja na tem področju, kot so Rigetti
Computing (RGTI), IonQ (IONQ), D-Wave Quantum (QBTS) in Quantum
Computing Inc. (QUBT), so skupaj z nekaterimi manj znanimi imeni, v zelo
kratkem času doživela neverjetno rast (več 100% ). IonQ, trenutno dosega
skoraj 8 milijard dolarjev tržne kapitalizacije, kar je osupljiva
številka za nakaj kar je praktično le »znanstveni eksperiment«, in
ustvarja vse prihodke iz vladnih pogodb. Ta prispevek na kratko razloži
trenutni prostor kvantnega računalništva, nedavne napredke na tem
področju in analizira uporabnost produktov teh podjetij. Cilj je jasno
prikazati, zakaj trenutna evforija spominja na klasičen špekulativni
balon, ki bo -- kot vsi taki baloni -- sčasoma počil in za sabo pustil
opustošenje in ogromno slabe volje. Vrednotenja so presegla meje
racionalnega, in vprašanje ni, če, temveč le še kdaj se bo ta zgodba
končala s tragičnimi padci vrednosti.

# Kratka zgodovina področja

Prve Ideje o kvantnem računalniku so se porodile v zgodnjih 80ih, ko je
tehnologija klasičnih računalnikov napredvala z nepredstavljivo
hitrostjo in so znanstevniki (Feyman, Deutsch) začeli razmišljati o
njihovi uporabi na raznih področjih. Kljub velikim obljubam o razvoju
novih nepredstavljivo zmogljivih klasičnih računalnikov pa so hitro
začeli dvomiti, da nekatere pojave ki izkazujejo kvantno naravo s takimi
stroji nikoli ne bomo mogli simulirati ter dobro opisati. Napredki na
področju eksperimentalne kvantne mehanike ter teorije računske
kompleksnosti so porodili novo raziskovalno področje kvatntnih
informacijskih znanosti. David Deutsch je leta 1985 dokazal da lahko
kvantni računalnik simulira vsak izračun ki je mogoč na klasičnem
računalniku, kar pomeni da je lahko kvantni računalnik vsaj tako
zmogljiv kot klasični. Prav tako je uvedel idejo o »kvantnem
paralelizmu« ki trdi da z dovolj zmogljivim kvantnim računalnikom lahko
nekatere probleme rešimo bistveno hitreje kot z klasičnimi pristopi.
Nedolgo za tem je leta 1994 Peter Williston Shor izumil in objavil Šorov
algoritem, ki je dokazal praktično uporabnost kvantnih računalnikov.
Šorov algoritem pokaže, da se lahko faktorizacija števil izvede v
polinomskem času, kar je za kompleksnostni razred hitreje od do sedaj
domnevanega eksponentnega časa, ki je potreben na klasičnem računalniku.
Ta preboj je potrdil potencial kvantnih računalnikov, da rešijo
probleme, ki so na klasičnih računalnikih nedosegljivi. Po prelomnem
odkritju Šorovega algoritma leta 1994 je področje kvantnega
računalništva doživelo izjemen razvoj. V zadnjih treh desetletjih so
raziskovalci in inženirji dosegli pomembne mejnike, ki so kvantne
računalnike približali praktični uporabi. Razvoj kvantnih procesorjev je
bil osredotočen na povečanje števila kvantnih bitov imenovanih »kubitov«
in izboljšanje njihove kakovosti. Od prvih eksperimentalnih sistemov z
nekaj kubiti smo do leta 2025 prišli do kvantnih računalnikov s
stotinami visoko koherentnih kubitov. Tehnologije, kot so superprevodne
zanke, ionske pasti in fotonski sistemi, so omogočile boljše
nadzorovanje in povezovanje kubitov, kar je ključnega pomena za
izvajanje kompleksnih kvantnih algoritmov. Poleg Šorovega algoritma so
bili razviti tudi drugi kvantni algoritmi, namenjeni reševanju
specifičnih problemov, kot so optimizacija, simulacija kvantnih sistemov
in strojno učenje. Razvoj programske opreme in platform, kot so Qiskit
in Cirq, je raziskovalcem in razvijalcem omogočil enostavnejše
programiranje in testiranje kvantnih algoritmov na dejanskih kvantnih
napravah.

# Od bitov do kubitov: Evolucija računalništva

V svetu računalništva klasični računalniki temeljijo na obdelavi
električnih signalov v digitalnih vezjih, izdelanih na polprevodniških
silicijevih rezinah. Informacije obdelujejo z uporabo bitov, ki lahko
zavzamejo eno od dveh diskretnih stanj: 0 ali 1. Ti sistemi uporabljajo
tranzistorje kot osnovne gradnike, ki delujejo kot stikala,
preklapljajoč med izklopljenim (0) in vklopljenim (1) stanjem. Tak način
obdelave informacij je determinističen, saj za vsak vhod določa natančen
izhod. Klasični računalniki so trenutno temelj vsega procesiranja in
prenašanja informacij. Gre za tehnologijo, ki je množično proizvedena,
dobro razumljena in izpopolnjena do izjemnih podrobnosti. Njena vrednost
je ogromna, saj omogoča reševanje širokega spektra problemov ter
ustvarjanje novih tehnologij, ki vplivajo na skoraj vse vidike sodobnega
življenja. Kljub dolgoletnemu razvoju procesiranja na siliciju se
inovacije še vedno nadaljujejo in velikosti tranzistorjev zmanjšujejo,
kar odpira nove možnosti za optimizacijo zmogljivost in energetsko
učinkovitost. Kvantni računalniki temeljijo na načelih kvantne mehanike,
ki preprosto povedano niso intuitivna, a kljub temu predstavljajo
najboljši opis narave, ki ga poznamo. Namesto bitov uporabljajo kubite,
ki lahko obstajajo v superpoziciji stanj. V medijih močno razširjena
analogija pravi, da kubit hkrati predstavlja 0 in 1, čeprav to ni nujno
napačno, pa ni čisto natančno in ne pomaga pri razumevanju. V resnici je
kubit v superpoziciji linearna kombinacija osnovnih stanj
$\lvert 0 \rangle$ in $\lvert 1 \rangle$, kar pomeni, da ga opišemo
$\alpha \lvert 0 \rangle + \beta \lvert 1 \rangle$, kjer sta $\alpha$ in
$\beta$ kompleksni števili, ki določata verjetnosti za vsako stanje
($\lvert \alpha \rvert^2 + \lvert \beta \rvert^2 = 1$). Šele ob meritvi
se kubit "zruši" v eno izmed osnovnih stanj $\lvert 0 \rangle$ ali
$\lvert 1 \rangle$ (meritev kubita je hkrati njegov prehod v diskretno
stanje), kar poudarja, da je to verjetnostna porazdelitev možnih izidov.
Za boljšo predstavo si lahko zamislimo kubit kot vektor v
dvodimenzionalnem prostoru, kjer osnovni stanji $\lvert 0 \rangle$ in
$\lvert 1 \rangle$ predstavljata pravokotni osi. Superpozicijo lahko
izrazimo kot linearno kombinacijo teh dveh stanj:
$$\lvert \psi \rangle = \alpha \lvert 0 \rangle + \beta \lvert 1 \rangle.$$
Superpozicija ni zgolj teoretičen koncept kvantnih računalnikov, temveč
osnovni pojav v naravi, ki ga opazimo pri kvantnih delcih, kot so
elektroni, fotoni in celo atomi. Eden najbolj znanih primerov
superpozicije je srednješolski fizikalni eksperiment z dvema režama
(double slit experiment), kjer posamezni fotoni ali elektroni, ko
potujejo skozi pregrade z dvema odprtinama, ne izberejo le ene poti,
ampak obstajajo v superpoziciji obeh poti hkrati. Šele ko izvedemo
meritev, se delci "odločijo" za eno izmed možnih poti, kar nakazuje, da
kvantni delci ne sledijo klasičnim zakonitostim deterministične poti.

Pri kvantnih računalnikih se superpozicijo izkorišča tako, da se kubit
nahaja v kombinaciji obeh osnovnih stanj $\lvert 0 \rangle$ in
$\lvert 1 \rangle$, kar lahko pohitri določene algoritme. Vendar pa
zgolj imeti kubit v superpoziciji ne zadostuje za hitrejše reševanje
problemov -- potrebno je vključiti še druge kvantne pojave, kot sta
prepletenost (entanglement) in interferenca (interference).

Prepletenost je posebna kvantna lastnost, pri kateri kvantni delci
postanejo povezani in stanje enega delca neposredno vpliva na stanje
drugega, ne glede na njuno medsebojno razdaljo. To pomeni, da če imamo
dva prepletena kubita, meritev enega takoj določi stanje drugega, tudi
če sta ločena in je med njima velika razdalja. Za razumevanje koncepta
prepletenosti si predstavljajte sistem z mnogimi deli, na primer knjigo
s 100 stranmi. Pri običajni knjigi s 100 stranmi vsakič, ko preberete
novo stran, predelate dodaten 1 % vsebine knjige, in ko preberete vse
strani eno za drugo, poznate celotno vsebino knjige. Zdaj si
predstavljajte, da gre za kvantno knjigo, kjer so strani zelo močno
prepletene med seboj. Ko listate čez tako knjigo stran za stranjo,
vidite samo naključno in nesmiselno nanizane črke brez pomena, popolnoma
nerazumljive in brez konteksta, to je zato, ker informacije v kvantni
knjigi niso predstavljene na posameznih straneh, ampak so v celoti
zakodirane v tem, kako so strani povezane z drugimi stranmi. Za branje
take knjige morate opazovati več strani hkrati.

V kvantnih računalnikih je prepletenost ključna za ustvarjanje
kompleksnih povezav med kubiti, kar omogoča učinkovitejše računanje.
Klasični računalniki temeljijo na posameznih bitih, ki so si med sabo
popolnoma neodvisni, zato menimo, da primerjava klasičnih bitov in
kubitov ni dobra za razumevanje kubitov.

Interferenca je pojav, kjer se kvantna stanja med seboj ojačajo ali
oslabijo, odvisno od njihove faze (enako kot pri klasičnem fizikalnem
opisu). To omogoča kvantnim algoritmom, da selektivno ojačajo pravilne
rešitve problema in oslabijo napačne.

Primer tega je Groverjev algoritem za iskanje v neurejeni množici
podatkov. Klasični algoritem bi moral preveriti vsak vnos posebej, kar
pomeni, da bi potreboval $O(N)$ korakov (preveril bi vsak element
posebej) za iskanje pravilnega rezultata v množici velikosti $N$.
Kvantni pristop pa omogoča iskanje v približno $O(\sqrt{N})$ korakih,
kar je kvadratno hitrejše.

Iz zgoraj na kratko predstavljene teorije lahko sklepamo, kako temeljne
razlike med kvantnim in klasičnim pristopom vplivajo na način izvajanja
računskih operacij in kako lahko potencialno izboljšajo časovno
kompleksnost reševanja različnih problemov.

Na tem mestu je pomembno poudariti, da je področje uporabe kvantnih
računalnikov izjemno kompleksno in v grobem še neraziskano. Pravzaprav
je še vedno neznano, kateri problemi spadajo v katere kompleksnostne
razrede na klasičnih računalnikih, kaj šele na kvantnih. To pomeni, da
je težko napovedati, katere naloge bo mogoče optimizirati z kvantnimi
računalniki. Razumevanje teh vprašanj ni enostavno, niti ni cilj tega
prispevka, saj se nahajamo na področju, kjer obstaja veliko špekulacij,
tako glede kvantnih kot tudi klasičnih računalnikov. V preteklosti smo
že večkrat odkrili polinomske algoritme za probleme, za katere smo pred
tem stoletja bili prepričani (testiranje, če je število praštevilo --
The AKS Primality Test (2002)), da so eksponentne zahtevnosti. Torej se
meja med \"težkimi\" in \"lahkimi\" računalniškimi problemi še vedno
spreminja. Kvantno računalništvo dodaja še dodatno plast negotovosti,
saj so tako teoretični temelji kot praktične implementacije še v zgodnji
fazi razvoja in pravzaprav nihče zares ni dokazal, da lahko obstajajo v
klasičnem prostoru enako hitri algoritmi kot v kvantnem.

# Kvantni Računalniki danes in njihova komercialna uporaba

Kubit je mogoče realizirati na različne načine, vsekakor pa potrebujemo
kvantne pojave, ki jih lahko opazujemo in nadzorujemo. Ti pojavi
vključujejo superpozicijo, prepletenost in kvantno interferenco, ki
omogoča manipulacijo verjetnostnih amplitud kvantnih stanj za izvedbo
računalniških operacij. Vsak kvantni računalniški sistem mora omogočati
merjenje teh pojavov, pri čemer je ključnega pomena, da jih lahko
stabilno hranimo in manipuliramo brez prehitre decoherence, ki vodi v
izgubo kvantnih lastnosti. V praksi to pomeni, da različne fizične
realizacije kubitov -- kot so superprevodna vezja, ionske pasti ali
fotonski sistemi -- izkoriščajo specifične kvantne učinke, ki so
merljivi in uporabni za izvajanje kvantnih operacij. Tako superprevodna
vezja kot ionske pasti so že uspešno implementirani in v praksi tudi
demonstrirani s strani raznih podjetij. Rigettijev računanik Ankaa-3
temelji na superprevodnih vezjih, medtem ko IonQ kot že ime namiguje
uporablja ionske pasti. Obe podjetji ponujata svoje računalnike za
komercialno uporabo preko amazonove AWS platforme (trenutno sta oba
računalnika iz neznanih razlogov nedosegljiva(offline)). Zakaj torej
kvantnih računalnikov še ne uporabljamo za probleme, ki jih lahko
eksponentno hitreje rešijo npr. faktorizacijo velikih števil (šorjev
algoritem), ali za učinkovito iskanje po velikih podatkovnih zbirkah
(groverjev algoritem) ali za druge v medijih omenjene probleme kot so
kemijske simulacije za odkrivanje novih zdravil, ali celo globoko učenje
in umetna inteligenca, kot si mnogi mislijo. Vsi omenjeni problemi imajo
neverjeten ekonomski potencial. Da omenimo samo šorov algoritem, če bi
uspeli faktoritzirati števila v polinomskem času, bi to pomenilo, da bi
lahko razbili večino današnjih varnostnih sistemov, ki temeljijo na
asimetrični kriptografiji. RSA, ki temelji na težavnosti faktorizacije
velikih števil, bi postal neuporaben. To bi imelo več katastrofalnih
posledic:

-   **Zlom spletne varnosti**: Vse spletne transakcije, od bančništva do
    šifrirane komunikacije prek HTTPS, bi postale ranljive. Napadalci bi
    lahko prestregli in dešifrirali podatke, ki so bili prej varno
    zaščiteni.

-   **Bitcoin in druge kriptovalute**: Če bi lahko učinkovito
    faktorizirali števila, bi lahko zlomili tudi varnost podpisov v
    Bitcoin omrežju. Bitcoin uporablja ECDSA (eliptično kriptografijo)
    za generiranje zasebnih in javnih ključev ter za preverjanje
    transakcij. ECC (elyptic curve cryptography) temelji na težavnosti
    problema diskretnega logaritma na eliptičnih krivuljah, ki je
    klasičnim računalnikom praktično nerešljiv. Šorjev algoritem, ki
    faktorizacijo števil reši v polinomskem času, lahko v polinomskem
    času reši tudi problem diskretnega logaritma, ki je za klasičen
    računalnik eksponentne zahtevnosti. To pomeni, da bi dovolj močan
    kvantni računalnik s primernim številom kubitov lahko izračunal
    zasebni ključ iz javnega ključa in ukradel sredstva iz vseh
    denarnic, ki so že izvedle transakcije. Pri trenutni tržni
    kapitalizaciji bitcoina (\$2 ) je motivacija za to ogromna.

Potencial za uporabo kvantnih računalnikov je torej neomejen? Ne povsem.
Kljub teoretičnemu potencialu kvantnih računalnikov se soočamo s
številnimi praktičnimi izzivi, ki ovirajo njihovo široko uporabo.
Ključni problem je ohranjanje kvantnih lastnosti kubitov in
zagotavljanje stabilnosti kvantnih operacij. Kvantni sistemi so izjemno
občutljivi na zunanje motnje, zaradi česar kvantni podatki hitro
izgubijo svoje kvantne lastnosti v procesu, imenovanem dekoherenca. To
pomeni, da je kvantne informacije težko shranjevati in procesirati brez
znatnih izgub. Še več, opazovanje kvantnega sistema neizogibno povzroči
njegovo motnjo. Vsako merjenje kvantnega stanja povzroči propad valovne
funkcije in uniči superpozicijo, kar pomeni, da kvantno računalniško
operacijo prekinemo, če poskušamo prebrati stanje vmes. To je temeljna
razlika med klasičnim računalnikom, kjer lahko preverjamo podatke
kadarkoli brez vpliva na njihovo stanje. Zaradi tega mora biti kvantni
računalnik hkrati dovolj izoliran, da prepreči neželene interakcije z
okoljem, in hkrati dovolj dostopen, da omogoča izvajanje kvantnih
operacij. Ravnovesje med tema dvema zahtevama je izjemno težko doseči.
Potrebujemo kvantno korekcijo napak, ki pa zahteva znatno povečanje
števila fizičnih kubitov za en logični kubit, v industrijji trenutno
razširejno mnenje je da za en logični kubit potrebujemo približno 1000
strojnih kubitov. Poleg tega imajo trenutno dostopni kvantni računalniki
visoke stopnje napak pri kvantnih vratih. Vsaka dvokubitna kvantna vrata
uvajajo napako, ki se s povečanjem števila operacij akumulira, kar
omejuje uporabnost obstoječih naprav. Ker še nismo dosegli učinkovitega
kvantnega popravljanja napak na praktični ravni, trenutni kvantni
računalniki ne morejo izvesti dolgotrajnih ali kompleksnih računskih
nalog brez izgube natančnosti. Primer kvantnih napak lahko ponazorimo s
podatki o točnosti vrat (gate fidelity), ki predstavlja verjetnost, da
se kvantna operacija izvede pravilno brez napake. Vzemimo za primer
Rigetti Ankaa-3 kvantni računalnik z 98 kubiti, kjer imajo enokubitna
vrata 99.9% fidelnost, dvokubitna vrata (ISWAP) pa 98.7% točnost (po
njihovih navedbah). Za primerjavo s klasičnimi silicijevimi
tranzistorji, kjer je verjetnost napake pri osnovni operaciji manjša od
$9^{-18}$, izračunajmo, koliko zaporednih dvokubitnih operacij lahko
izvedemo na Ankaa-3, preden pade verjetnost pravilnega rezultata pod 1%.

Fidelnost vsake dvokubitne operacije je torej 0.987. Če izvedemo N
takšnih operacij, je skupna verjetnost pravilnega rezultata:
$$(0.987)^N < 0.01$$

$$\log \left( (0.987)^N \right) < \log (0.01)$$

$$N \cdot \log (0.987) < \log (0.01)$$

$$N > \frac{\log (0.01)}{\log (0.987)}$$

$$N > 352$$

Izračun pokaže, da že ko izvedemo približno 352 dvokubitnih operacij,
verjetnost da imamno pravi rezultat pade pod 1%. Na tem mestu je vredno
omeniti da izračun temelji na eksperimentalno določenih vrednostih ki so
po podane kot mediane napake, kar v praksi pomeni, da je dejansko
število operacij da pademo pod 1% v slabih primerih še veliko manjše. Za
primerjavo, v klasičnih tranzistorskih sistemih, kjer je verjetnost
napake manjša od $9^{-18}$, bi bilo število dovoljenih operacij pred
padcem verjetnosti uspešnosti pod 99% astronomsko veliko -- praktično
neomejeno za vse realne poljubno velike računske naloge. Pri uporabnosti
kubitov je zelo pomemben tudi čas, ki določa, kako dolgo je lahko kubit
uporaben. Čas T1 predstavlja povprečni čas, v katerem kubit spontano
preide iz vzbujenega v osnovno stanje zaradi interakcij z okoljem.
Kratek T1 pomeni, da kvantne informacije hitro izginejo, kar omejuje,
kako dolgo lahko sistem izvaja računanje. Čas T2 pa opisuje, kako dolgo
lahko kvantni sistem ohranja svojo fazno koherenco, preden jo zaradi
dekoherence izgubi. To neposredno vpliva na število zaporednih operacij,
ki jih lahko izvedemo, preden kvantni računalnik izgubi zanesljivost.
Trenutno dostopni kubiti v Rigetti Ankaa-3 računalniku, dosegajo T1
približno 21 µs in T2 približno 19 µs (mediane vrednosti). To pomeni, da
lahko kvantni sistem izvede le omejeno število operacij, preden kubiti
izgubijo informacije ki jih nosijo. Glede na tipične čase za izvedbo
kvantnih vrat ( 100 ns za enokubitna vrata in  250 ns za dvokubitna
vrata) lahko teoretično izpeljemo največ nekaj sto do nekaj tisoč
operacij, preden vezje postane totalno neuporabno. Da povzamemo,
trenutno največji javno dostopni kvantni računalniki posedujejo največ
nekaj 100 kubitov (npr. IBM, Google, Rigetti, IonQ), Koherenčni časi T1
pri superprevodnih kubitih običajno znašajo 10--100 µs, medtem ko so za
T2 pogosto manj kot 100 µs, kar omejuje število operacij pred izgubo
stanja. Ionski kubiti imajo sicer boljše T2 čase (v razponu od 100 ms do
10 s), vendar so operacije na njih kar 1000 krat počasnejše. Točnost
operacij (gate fidelity) je pri enokubitnih vratih običajno 99.9% ali
manj, pri dvokubitnih vratih (npr. CNOT, iSWAP) pa znaša 97% -- 99%, kar
pomeni, da napaka pri vsaki operaciji narašča in omejuje število
zanesljivih operacij. Brez kvantnega popravljanja napak lahko trenutno v
dobrih pogojih izvedemo nekaj tisoč operacij, preden koherenčni časi in
napake postanejo problematični in rezultati neuporabni. Poglejmo kakšen
kvantni računalnik bi potrebovali, da bi lahko uporabili Šorov algoritem
za dešifriranje RSA enkripcije (pri 2048 bitnem ključu). Število
logičnih kubitov je določeno z globino vezja, ki ga algoritem potrebuje
in sposobnostjo odpravljanja napak. Nekatere raziskave iz optimizacije
namigujejo da potrebujemo najmanj 6000 logičnih kubitov druge (Gidney
and Ekerå's) pa ocenjujejo število na okoli 14000, razlike nastanejo
zaradi kompromisov, ki jih sprejemamo med številom kubitov in dovoljenim
časom za izračun ko določene korake algoritma paraleliziramo (potrebno
je najti kompromis med obema prisopoma). Po oceni 6000 in trenutnem
kolektivnemu mnenju da potrebujemo najmanj 1000, verjetna realnost je
tudi 10000 strojnih kubitov za realizacijo enega logičnega bita, bomo
torej potrebovali najmanj 6 milijonov strojnih kubitov, kar je po
najbolj optimističnih ocenah vsaj nekaj 1000-krat več če ne 10000-krat
več kubitov kot jih lahko realiziramo trenutno. Realna številka bi lahko
bila bližje 20 miljonom kubitov. Poleg ogromnega števila kubitov bi
potrebovali koherenčna časa T1 in T2 vsaj več kot 100 ms, kar je vsaj
10x več kot je sedaj komercialno dostopno. Seveda za implentacijo takega
algoritma ki potrebuje nekaj trilijonov operacij potrebujemo kvantna
vrata z veliko manjšo verjetnostjo napake kot je trenutnih 1.3% na
Rigetti Ankaa-3. Na tem mestu je pomembno poudariti da je napredek na
tem področju zelo počasen. Za to da smo prišli iz 5 kubitov na 100
kubitov je trajalo skoraj 20 let. Za to da smo pri enokubitnih vratih
opazili pomemben napredek -- točnost operacij (gate fidelity) se je
izboljšala s približno 99 % na med 99,5 % in 99,9 % smo potrebovali 5
let. Zato da so se časi koherence, ki smo jih v začetnih fazah merili v
nanosekundah (približno 5 ns), izboljšali do obsega mikrosekund smo
porabili približno deset let, potrebne so bile številne inovacijame na
področju materialov, na področju toplotnih strojev (dilution
refrigerator) ter na področju specializiranih merilinih sistemov. Šorov
algoritem, so na kvantnem računalniku s sedmimi kubiti(IBM) prvič
implementirali leta 2001 in faktorizirali število 15 na 3 in 5, (15 je
štiribitno število). Ta dosežek je bil pomemben mejnik v kvantnem
računalništvu, saj je pokazal praktično izvedljivost Šorovega algoritma.
V naslednjih letih so raziskovalci uspeli faktorizirati tudi večja
števila; leta 2012 so na primer faktorizirali število 21 (5 bitno
število), leta 2016 pa ponovno število 15 z uporabo ionskih pasti. Kljub
ogromnemu tehnološkemu napredku na področju in velikim investicijam, smo
pravzaprav dosegli zelo malo. Danes (2025) lahko na naslovnicah
znanstevnih člankov zasledimo da je nekatrim že uspelo faktorizirati
večja števila kot je 4088459=2017×2027, a na žalost je to le lep trik
brez praktične kriptografske uporabnosti, ki deluje na številih (2017,
2027) ki so si v binarnem zapisu različna le za 2 bita. Podobnih trikov
in hibridnih pristopov k faktroiziranju s pomočjo kvantnih računalnikov
je ogromno, a nobeden od teh načinov ni niti približno boljši od
pristopov na klasičnih računalnikih niti ni uporaben za resne
kriptografske primere ali skalabilen. Faktorizacija majnhnih števil npr.
21 = 7 x 3 s pravim šorovim algoritmom na najnovejših kvantnih
računalnikih še vedno ostaja velik izziv.

# Rigetti Computing: Kvantno podjetje brez realnega napredka

Rigetti Computing (RGTI) je prvo »pravo« kvantno podjetje, ki ga
podrobneje predstavimo. Chad Rigetti je podjetje ustanovil leta 2013, od
takrat je porabilo 402 milijone dolarjev. Njihovi prihodki počasi
upadajo (2022: 13 milijonov, 2023: 12 milijonov, 2024: 12 milijonov),
prihodnost Rigetti pa je bila še pred Googlovim najnovejšim kvantnim
napredkom videti slabo. Po več krogih zasebnega financiranja po nižjih
vrednotenjih, združitvi s SPAC in nenehnem pomanjkanju komercialnega
napredka je Chad Rigetti zapustil podjetje. Z vrednostjo le 300
milijonov dolarjev in naraščajočimi izgubami se je zdelo, da je Rigetti
na robu propada. Nato so prodali delnice po 1.53 (ATM) in po 2,00
dolarja v registriranem direktnem odkupu. Delnica je trenutno pri 12
dolarjih.

Kaj Rigetti sploh počne? Rigetti izdeluje prave kvantne računalnike.
Težava je v tem, da ne delujejo ravno dobro. Rigetti velja v kvantni
industriji za počasnega konkurenta. Podjetje uporablja superprevodna
vezja, ki jih podpirata tudi Google in IBM. Pred kratkim so uvedli svoj
84-kubitni sistem \"Ankaa-3\", a ta je še vedno daleč za vodilnimi
igralci industrije.

Kakšne so torej komercialne možnosti za podjetje, kot je Rigetti, če bi
doseglo svoje cilje? Odgovor je: ne velike. Celoten proračun NSA
(National Security Agency) naj bi znašal med 10 in 15 milijard dolarjev.
To je logična ocena, saj je proračun FBI javno razkrit in znaša 11
milijard dolarjev, medtem ko naj bi proračun CIA znašal 14 do 15
milijard dolarjev. Predpostavimo da NSA letno porabi približno 2
milijarde dolarjev za računalništvo. Bolj verjetno kot ne je, da vsaj
polovico tega proračuna porabijo za shranjevanje podatkov in upravljanje
podatkovnih centrov, verjetno pa še več. Če bi kvantno računalništvo
prevzelo polovico tega proračuna ali pa bi se proračun povečal za
milijardo dolarjev, bi to predstavljalo sredstva ki bi bila na voljo
podjetjem na kvantnem področju. Lahko si predstavljamo različne
scenarije, kjer bi Rigetti (ali drugo podjetje) prejelo 50 % tega
proračuna. Težava je v tem, da si ta sredstva želijo tudi Google, IBM,
Quantinuum, IonQ in drugi. Ampak za namen optimističnega scenarija
radodarno predpostavimo, da bi Rigetti nekako uspel dobiti celoten delež
in da bi se ta proračun pojavil v naslednjih petih letih. Če
diskontiramo denarni tok s 50 % neto marže (brez davkov) po diskontni
stopnji od 12 % do 25 %, bi neto sedanja vrednost (NPV) znašala med 1 in
4 dolarje na delnico v primerjavi s trenutno ceno 12 dolarjev na
delnico. Tudi če predpostavimo, da bi se ta proračun enormno povečal za
industrijsko in akademsko uporabo ter da bi Rigetti do leta 2035 dosegel
2 milijardi dolarjev prihodkov, bi bila delnica vredna med 5 in 13
dolarjev, odvisno od diskontne stopnje. Žal se zdi, da Rigetti nima
možnosti, da bi to uresničil.

# IonQ -- bolj resno podjetje, a še vedno v zaostanku

IonQ (IONQ) se na prvi pogled zdi bolj resno podjetje kot Rigetti.
Njihovi akademski dosežki so vredni spoštovanja. Njihova pristop temelji
na uporabi ujetih ionov za shranjevanje kvantnih informacij, namesto
superprevodnih vezij, ki jih uporablja večina industrije. Ioni so lahko
pri sobni temperaturi, kar je prednost pred superprevodniki, ki jih
moramo hladiti 15 milikelvinov, vendar jih je treba hraniti v izjemno
nizkotlačnem vakuumu in nadzorovati z laserji, da nimajo skoraj nič
energije. Splošno mnenje v industriji je, da so pasti z ioni preveč
občutljive in prepočasne za praktično uporabo.

IonQ je napovedal izdajo 100-kubitnega računalnika Tempo do konca
letošnjega leta. Žal je IBM že daleč pred to kapaciteto. Čeprav ima IonQ
več prihodkov kot Rigetti in se zdi, da raste, je veliko njihovega
prihodka povezanega z vladnimi pogodbami, kar lahko popači percepcijo
njihovega vodilnega položaja. Trenutno so javno kotirane kvantne delnice
edine, ki so dostopne malim vlagateljem, saj ni smiselno kupovati Google
ali IBM samo zaradi njihovih kvantnih raziskav in dosežkov, ki ne
vplivajo na ceno teh dveh delnic. Quantinuum in druga zanimiva podjetja
so zasebna. Zaradi tega lahko vlagatelji napačno sklepajo, da z
vlaganjem v podjetja, kot sta IonQ ali Rigetti, lahko obogatijo, ker so
to edine kvantne delnice, ki bodo bistveno rastle.

Kljub nekoliko višjim prihodkom, predvsem zaradi pogodbe z ameriškim
letalstvom (US Air Force), je IonQ še vedno daleč za resnimi igralci v
kvantni industriji: IBM, Google, Quantinuum (zasebno) in PsiQuantum
(zasebno). Njihov najnaprednejši računalnik v storitvi AWS Braket, Forte
1, ima le 36 kubitov. Od začetka januarja je bil Forte 1, ki stane 7.000
dolarjev na uro, nepričakovano v vzdrževanju in ni bil dosegljiv skoraj
1 mesec. Izkušnje raziskovalcev z IBM-jevimi kvantnimi računalniki
kažejo, da so njihovi računalniki stabilni, a kljub temu polni napak.
Njihovi 128-kubitni računalniki so zaenkrat neuporabni. IonQ pa še
zdaleč ni na ravni 128 kubitov! Tako se zdi, da je visoka vrednost IonQ
v primerjavi z Rigetti popolnoma neupravičena, zaradi česar verjamemo,
da je to še boljša kratka pozicija.

# Povzetek

Kljub velikemu financiranju in virom, vloženim v kvantno računalništvo,
je tehnologija danes večinoma neuporabna za kakršnekoli resnične
aplikacije. Kvantni računalniki, čeprav teoretično zmogljivi, so izjemno
težko gradljivi in vzdrževani, saj zahtevajo visoko specializirana
okolja, kot so razredčevalni hladilniki, da lahko superprevodni kubiti
delujejo pri temperaturah blizu absolutne ničle. Kljub temu imajo
obstoječi kvantni računalniki kratke čase koherence, visoke stopnje
napak in omejeno skalabilnost. Trenutno obstaja le peščica kvantnih
naprav, ki niso široko dostopne. Večina je dostopna le prek cloud
storitev (AWS Braket) podjetij, kot so IBM, Google in Rigetti . To močno
omejuje eksperimentiranje in razvoj, kar pripomore k počasnemu
napredovanju, ki je omejeno na majhno število raziskovalcev z dostopom
do teh ekskluzivnih sistemov. Medtem ko so klasični tranzistorski
polprevodniki eksponentno napredovali v po Moorovem zakonu in dosegli
več kot 1000-kratno izboljšanje od 80. let---je kvantno računalništvo
komaj napredovalo linearno. Število kubitov se je povečalo le minimalno,
njihova zanesljivost pa ostaja vprašljiva. Za razliko od klasičnih
računalnikov, kjer lahko na en sam čip spravimo milijarde tranzistorjev
in bitov, kvantni računalniki zahtevajo zapleteno in občutljivo
inženirstvo, zaradi česar je množična proizvodnja z današnjo tehnologijo
nemogoča. Ena največjih groženj kvantnega računalništva---razbijanje RSA
šifriranja s Shorjevim algoritmom---postaja vse bolj nepomembna.
Postkvantni kriptografski algoritmi, zasnovani za odpornost proti
kvantnim napadom, so že v razvoju. Do trenutka, ko bodo kvantni
računalniki dejansko sposobni ogroziti RSA, bo svet že prešel na kvantno
odporne metode šifriranja, zaradi česar bo Shorjev algoritem zastarel.
Groverjev algoritem, še en pogosto omenjen razlog za kvantno
računalništvo, zgolj zagotavlja kvadratno pohitritev pri iskanju po
neurejenih podatkovnih bazah. Vendar bodo stroški izvajanja Groverjevega
algoritma na kvantni strojni opremi verjetno veliko večji od njegovih
prednosti, saj klasični algoritmi za iskanje še naprej napredujejo in
ostajajo bolj praktični za skoraj vse primere uporabe. Za razliko od
polprevodniške revolucije, kjer je praktična uporaba spodbujala
tehnološki napredek, kvantno računalništvo še vedno ni pokazalo pravega
problema, ki bi ga lahko rešilo bolje kot klasični računalniki. Pravi
preboji v kvantnih aplikacijah bodo verjetno prišli iz nepredvidenih
odkritij, ko bomo lahko dejansko uporabljali tehnologijo v večjem
obsegu---tako kot se je računalniška revolucija odvila šele z množično
uporabo polprevodnikov. Temeljni zakoni narave naredijo kvantno
računalništvo izjemno težavno. Globlje kot gremo v kvantno mehaniko,
težje postane nadzorovati in manipulirati te občutljive sisteme. Kvantna
dekoherenca, šum in popravljanje napak zahtevajo eksponentno več truda,
in ko poskušamo povečati obseg, se izzivi le še večajo. Za razliko od
klasičnega računalništva, ki je imelo jasno inženirsko pot, se kvantno
računalništvo sooča s temeljnimi fizikalnimi omejitvami, ki lahko
preprečijo njegov prehod v mainstream tehnologijo v naslednjih
desetletjih. Zaradi vseh navedenih razlogov trdno verjamem, da bodo
kvantne delnice uničile male vlagatelje, ko bodo ti ugotovili, da niso
revolucionarne in da kvantno računalništvo še vsaj desetletje ne bo
imelo resničnega vpliva. Ko bodo te delnice začele padati proti svojim
realnim vrednostim, bodo peščici pametnim kratkim prodajalcem prinesle
bogastvo, medtem ko bo veliko malih vlagateljev ostalo brez vsega.
