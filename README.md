# 🇭🇺 HUN-OSINT

**Magyarország és az Európai Unió Nyílt Forrású Hírszerzési (OSINT) Adattára**

Magyar kiberbiztonsági szakemberek, etikus hackerek, oknyomozó újságírók és nyomozók számára készült átfogó OSINT forrásgyűjtemény.

![License](https://img.shields.io/badge/License-MIT-green.svg)
![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)
![Last Updated](https://img.shields.io/badge/Last%20Updated-Febru%C3%A1r%202026-blue.svg)

---

## 📋 Tartalomjegyzék

- [Bevezetés](#-bevezetés)
- [Jogi figyelmeztetés](#️-jogi-figyelmeztetés)
- [Kezdeti lépések](#-kezdeti-lépések)
  - [OSINT Operációs Rendszerek](#osint-operációs-rendszerek)
  - [Virtuális gépek](#virtuális-gépek)
  - [VPN szolgáltatások](#vpn-szolgáltatások)
  - [Böngészők és kiegészítők](#böngészők-és-kiegészítők)
- [Magyar Hatóságok](#-magyar-hatóságok)
  - [Rendőrség és bűnüldözés](#rendőrség-és-bűnüldözés)
  - [Titkosszolgálatok és nemzetbiztonság](#titkosszolgálatok-és-nemzetbiztonság)
  - [Kiberbiztonság](#kiberbiztonság)
- [Céginformációk](#-céginformációk)
  - [Magyar cégnyilvántartások](#magyar-cégnyilvántartások)
  - [EU-s cégkereső](#eu-s-cégkereső)
  - [Pénzügyi és adóhatósági adatok](#pénzügyi-és-adóhatósági-adatok)
- [Személykeresés](#-személykeresés)
  - [Telefonkönyvek](#telefonkönyvek)
  - [Közösségi média](#közösségi-média)
  - [Társkereső oldalak](#magyar-társkereső-oldalak)
  - [Álláskeresés](#álláskereső-portálok)
- [Gépjármű és közlekedés](#-gépjármű-és-közlekedés)
- [Ingatlan és térképészet](#-ingatlan-és-térképészet)
- [Bíróságok és jogtárak](#️-bíróságok-és-jogtárak)
- [Archívumok és média](#-archívumok-és-média)
- [Adatszivárgások és dark web](#-adatszivárgások-és-dark-web)
- [OSINT eszközök](#️-osint-eszközök)
  - [Automatizált eszközök](#automatizált-osint-eszközök)
  - [Képelemzés](#képelemzés-és-forensics)
  - [Geolokáció](#geolokációs-eszközök)
  - [Felhasználónév keresés](#felhasználónév-keresők)
  - [E-mail eszközök](#e-mail-eszközök)
  - [Telefonszám OSINT](#telefonszám-osint)
  - [Weboldal és domain](#weboldal-és-domain-eszközök)
  - [Fenyegetés-felderítés](#fenyegetés-felderítés-threat-intelligence)
- [Körözések és eltűnt személyek](#-körözések-és-eltűnt-személyek)
- [Közérdekű adatok](#-közérdekű-adatok)
  - [Nemzeti Közadatportál](#nemzeti-közadatportál)
  - [Vagyonnyilatkozatok és átláthatóság](#vagyonnyilatkozatok-és-átláthatóság)
  - [Nemzetközi oknyomozói adatbázisok](#nemzetközi-oknyomozói-adatbázisok)
- [Külső OSINT források](#-külső-osint-források)
- [Hozzájárulás](#-hozzájárulás)

---

## 📖 Bevezetés

Ez a gyűjtemény a magyar és EU-s környezetre optimalizált OSINT (Open Source Intelligence) folyamatokat támogatja. A lista hasznos lehet:

- 🛡️ **Nemzeti Kibervédelmi Intézet (NKI)** munkatársainak
- 👮 **Rendőrségi nyomozóknak**
- 📰 **Oknyomozó újságíróknak** (Átlátszó, Direkt36, Telex, 444)
- 👥 **HR és Recruiter szakembereknek**
- 🔍 **Magánnyomozóknak**
- 🎓 **Biztonsági kutatóknak és etikus hackereknek**

---

## ⚠️ Jogi figyelmeztetés

> **FONTOS:** Magyarországon és az EU-ban szigorú adatvédelmi törvények (GDPR, Infotv.) vannak érvényben. Az itt található eszközök nyilvánosan elérhető forrásokat használnak, de a megszerzett adatok kezelése felelősséggel jár!

- Ne használj személyes adatokat jogellenes célokra
- Tartsd be a GDPR és a magyar adatvédelmi törvényeket
- Az OSINT nem azonos a hackeléssel - csak nyilvános adatokat használj
- Dokumentáld a kutatási folyamatot

---

## 🚀 Kezdeti lépések

### OSINT Operációs Rendszerek

| Név | Leírás | Link |
|-----|--------|------|
| **Trace Labs OSINT VM** | Eltűnt személyek keresésére optimalizált VM | [Letöltés](https://www.tracelabs.org/initiatives/osint-vm) |
| **Kali Linux** | Az iparági standard penetration testing és OSINT disztribúció | [Letöltés](https://www.kali.org/get-kali/) |
| **Tsurugi Linux** | Digitális forensics és OSINT-re kihegyezett Linux | [Letöltés](https://tsurugi-linux.org/) |
| **CSI Linux** | Cyber Security Investigation Linux | [Letöltés](https://csilinux.com/) |

### Virtuális gépek

| Név | Leírás | Link |
|-----|--------|------|
| **VirtualBox** | Ingyenes, nyílt forráskódú virtualizáció | [Letöltés](https://www.virtualbox.org/) |
| **VMware Workstation Pro** | Ingyenes személyes használatra (2024 óta) | [Letöltés](https://www.vmware.com/products/desktop-hypervisor/workstation-and-fusion) |

### VPN szolgáltatások

> ⚠️ **Soha ne használj ingyenes VPN-t OSINT munkához!**

| Név | Székhely | Megjegyzés | Link |
|-----|----------|------------|------|
| **Mullvad VPN** | 🇸🇪 Svédország | Nincs log, EU-s, anonim fizetés | [mullvad.net](https://mullvad.net/) |
| **ProtonVPN** | 🇨🇭 Svájc | Erős titkosítás, van ingyenes verzió | [protonvpn.com](https://protonvpn.com/) |
| **IVPN** | 🇬🇮 Gibraltár | No-log policy, WireGuard | [ivpn.net](https://www.ivpn.net/) |
| **NordVPN** | 🇵🇦 Panama | Népszerű, sok szerver | [nordvpn.com](https://nordvpn.com/) |

### Böngészők és kiegészítők

**Ajánlott böngészők:**

| Név | Leírás | Link |
|-----|--------|------|
| **Firefox** | Testreszabható, privacy-fokuszált | [Letöltés](https://www.mozilla.org/firefox/) |
| **Tor Browser** | Anonim böngészés, dark web elérés | [Letöltés](https://www.torproject.org/) |
| **Brave** | Beépített adblocker és tracker-védelem | [Letöltés](https://brave.com/) |

**Hasznos Firefox/Chrome kiegészítők:**

- [uBlock Origin](https://ublockorigin.com/) - Hatékony reklámblokkoló
- [User-Agent Switcher](https://addons.mozilla.org/firefox/addon/uaswitcher/) - Böngésző identitás váltás
- [Exif Viewer](https://addons.mozilla.org/firefox/addon/exif-viewer/) - EXIF adatok megtekintése
- [Wayback Machine](https://addons.mozilla.org/firefox/addon/wayback-machine_new/) - Archivált oldalak
- [RevEye](https://chrome.google.com/webstore/detail/reveye-reverse-image-sear) - Fordított képkeresés

---

## 🏛️ Magyar Hatóságok

### Rendőrség és bűnüldözés

| Szervezet | Leírás | Link |
|-----------|--------|------|
| **Rendőrség (ORFK)** | Magyar Rendőrség hivatalos oldala | [police.hu](https://www.police.hu/) |
| **Körözési Toplista** | Legkeresettebb személyek | [police.hu/koral](https://www.police.hu/hu/koral/toplistas-korozesek) |
| **Körözések keresése** | Nyilvános körözési adatbázis | [police.hu/koral](https://www.police.hu/hu/koral) |
| **Bűnügyi térkép** | Interaktív bűnügyi térkép | [terkep.police.hu](https://terkep.police.hu/portal/bunugyi) |
| **Baleseti térkép** | Közlekedési balesetek térképe | [terkep.police.hu](https://terkep.police.hu/portal/baleseti) |
| **Terrorelhárítási Központ (TEK)** | Terrorelhárítás és VIP védelem | [tek.gov.hu](https://tek.gov.hu/) |
| **Nemzeti Nyomozó Iroda (NNI)** | Szervezett bűnözés elleni harc | [police.hu](https://www.police.hu/) |
| **NSZKK** | Nemzeti Szakértői és Kutató Központ | [nszkk.gov.hu](https://nszkk.gov.hu/) |

### Titkosszolgálatok és nemzetbiztonság

| Szervezet | Leírás | Link |
|-----------|--------|------|
| **Alkotmányvédelmi Hivatal (AH)** | Polgári elhárítás, kémelhárítás | [ah.gov.hu](https://ah.gov.hu/) |
| **Információs Hivatal (IH)** | Polgári hírszerzés | [ih.gov.hu](https://ih.gov.hu/) |
| **Nemzetbiztonsági Szakszolgálat (NBSZ)** | Titkos információgyűjtés, lehallgatás | [nbsz.gov.hu](https://nbsz.gov.hu/) |
| **Katonai Nemzetbiztonsági Szolgálat (KNBSZ)** | Katonai hírszerzés és elhárítás | [knbsz.gov.hu](https://knbsz.gov.hu/) |

### Kiberbiztonság

| Szervezet | Leírás | Link |
|-----------|--------|------|
| **Nemzeti Kibervédelmi Intézet (NKI)** | Kiberbiztonsági incidenskezelés, riasztások | [nki.gov.hu](https://nki.gov.hu/) |
| **GovCERT Hungary** | Kormányzati CERT | [nki.gov.hu](https://nki.gov.hu/) |
| **NIIF CSIRT** | Akadémiai hálózat biztonsága | [niif.hu](https://niif.hu/) |

### EU-s bűnüldöző szervek

| Szervezet | Leírás | Link |
|-----------|--------|------|
| **Europol** | EU bűnüldöző ügynökség | [europol.europa.eu](https://www.europol.europa.eu/) |
| **EU Most Wanted** | Európai körözési lista | [eumostwanted.eu](https://eumostwanted.eu/) |
| **Eurojust** | EU igazságügyi együttműködés | [eurojust.europa.eu](https://www.eurojust.europa.eu/) |
| **OLAF** | EU csalás elleni hivatal | [ec.europa.eu/anti-fraud](https://anti-fraud.ec.europa.eu/) |

---

## 🏢 Céginformációk

### Magyar cégnyilvántartások

| Szolgáltatás | Leírás | Ár | Link |
|--------------|--------|-----|------|
| **E-Cégjegyzék** | Hivatalos, ingyenes cégadatok | Ingyenes | [e-cegjegyzek.hu](https://www.e-cegjegyzek.hu/) |
| **e-Beszámoló** | Cégek pénzügyi beszámolói, mérlegek (Igazágügyi Minisztérium) | Ingyenes | [e-beszamolo.im.gov.hu](https://e-beszamolo.im.gov.hu/) |
| **Céginformációs Szolgálat** | Hiteles cégkivonatok | Fizetős | [ceginformaciosszolgalat.kormany.hu](https://ceginformaciosszolgalat.kormany.hu/) |
| **Opten** | Részletes céginformációk, kapcsolati hálók | Részben fizetős | [opten.hu](https://www.opten.hu/) |
| **Nemzeti Cégtár** | Vizualizált kapcsolati hálók | Részben fizetős | [nemzeticegtar.hu](https://www.nemzeticegtar.hu/) |
| **HVG Cégadatbázis** | Cégkeresés és elemzés | Ingyenes | [cegadatbazis.hvg.hu](https://cegadatbazis.hvg.hu/) |
| **Cégtaláló** | Egyszerű cégkeresés | Ingyenes | [cegtalalo.hu](https://www.cegtalalo.hu/) |

### EU-s cégkereső

| Szolgáltatás | Leírás | Link |
|--------------|--------|------|
| **E-Justice Business Registers** | EU tagállamok cégnyilvántartásai | [e-justice.europa.eu](https://e-justice.europa.eu/content_business_registers_in_member_states-106-hu.do) |
| **OpenCorporates** | Globális céginformációk | [opencorporates.com](https://opencorporates.com/) |
| **North Data** | Európai cégadatok | [northdata.com](https://www.northdata.com/) |
| **LEI Search** | Legal Entity Identifier keresés | [gleif.org](https://search.gleif.org/) |

### Pénzügyi és adóhatósági adatok

| Szolgáltatás | Leírás | Link |
|--------------|--------|------|
| **NAV Adóalanyok lekérdezése** | ÁFA és adózói adatbázis | [nav.gov.hu/adatbazisok](https://nav.gov.hu/adatbazisok/adatbleker) |
| **NAV Adósságlista** | Végrehajtás alatti adózók, hátralékosok | [nav.gov.hu/adoslista](https://nav.gov.hu/adatbazisok/adoslista) |
| **NAV Köztartozásmentes adózók** | Rendezett adózók listája | [nav.gov.hu](https://nav.gov.hu/nav/adatbazisok/koztartozasmentes) |
| **MNB Felügyeleti adatbázis** | Engedélyezett pénzügyi szolgáltatók | [mnb.hu](https://www.mnb.hu/felugyelet/engedelyezes-es-intezmenyfelugyeles/intezmenykereső) |
| **EU VAT Validation** | EU ÁFA szám ellenőrzés | [ec.europa.eu/vies](https://ec.europa.eu/taxation_customs/vies/) |

---

## 👤 Személykeresés

### Telefonkönyvek

| Szolgáltatás | Leírás | Link |
|--------------|--------|------|
| **Telekom Tudakozó** | Magyar Telekom telefonkönyv | [tudakozo.telekom.hu](https://tudakozo.telekom.hu/) |
| **Telefonkönyv.hu** | Online telefonkönyv | [telefonkonyv.hu](https://telefonkonyv.hu/) |
| **Arany Oldalak** | Céges telefonkönyv | [aranyoldalak.hu](https://www.aranyoldalak.hu/) |

### Közösségi média

**Globális platformok:**

| Platform | Magyar felhasználók | Link |
|----------|---------------------|------|
| **Facebook** | ~6 millió | [facebook.com](https://www.facebook.com/) |
| **Instagram** | ~3 millió | [instagram.com](https://www.instagram.com/) |
| **LinkedIn** | ~1.5 millió | [linkedin.com](https://www.linkedin.com/) |
| **TikTok** | ~2 millió | [tiktok.com](https://www.tiktok.com/) |
| **Twitter/X** | ~500 ezer | [x.com](https://x.com/) |

**Magyar fórumok és közösségek:**

| Platform | Leírás | Link |
|----------|--------|------|
| **Gyakori Kérdések** | Kérdések és válaszok, régi tartalom | [gyakorikerdesek.hu](https://www.gyakorikerdesek.hu/) |
| **Prohardver Fórum** | Tech közösség | [prohardver.hu/fórum](https://prohardver.hu/forum/) |
| **Index Fórum** | Általános fórum | [forum.index.hu](https://forum.index.hu/) |
| **Jogiforum** | Jogi témájú fórum | [jogiforum.hu](https://www.jogiforum.hu/) |

### Magyar társkereső oldalak

| Platform | Leírás | Link |
|----------|--------|------|
| **Randivonal** | Legnagyobb magyar társkereső | [randivonal.hu](https://www.randivonal.hu/) |
| **Badoo** | Népszerű Kelet-Európában | [badoo.com/hu](https://badoo.com/hu/) |
| **Tinder** | Globális, Magyarországon is népszerű | [tinder.com](https://tinder.com/) |
| **Elittárs** | Felsőfokú végzettségűeknek | [elittars.hu](https://www.elittars.hu/) |
| **Párkeresés.hu** | Magyar társkereső | [parkereses.hu](https://www.parkereses.hu/) |

### Álláskereső portálok

| Szolgáltatás | Leírás | Link |
|--------------|--------|------|
| **Profession.hu** | Legnagyobb magyar állásportál | [profession.hu](https://www.profession.hu/) |
| **LinkedIn Jobs** | Szűrés: Hungary | [linkedin.com/jobs](https://www.linkedin.com/jobs/) |
| **Közigállás** | Közszféra állások archívuma | [kozigallas.gov.hu](https://kozigallas.gov.hu/) |
| **Indeed Magyarország** | Globális álláskereső | [hu.indeed.com](https://hu.indeed.com/) |
| **Helloworkforce** | IT és tech állások | [helloworkforce.com](https://www.helloworkforce.com/) |
| **NoFluffJobs** | IT állások | [nofluffjobs.com/hu](https://nofluffjobs.com/hu) |
| **Jooble** | Állásaggregátor | [hu.jooble.org](https://hu.jooble.org/) |

---

## 🚗 Gépjármű és közlekedés

### Gépjármű-adatbázisok

| Szolgáltatás | Leírás | Hozzáférés | Link |
|--------------|--------|------------|------|
| **Jármű Szolgáltatási Platform (JSZP)** | Rendszám alapján: műszaki adatok, fotók, km-óra állások, előélet | Ügyfélkapu | [magyarorszag.hu/jszp](https://magyarorszag.hu/jszp_szuf) |
| **MABISZ Kártörténet** | Biztosítási kárelőzmény, KGFB fedezet ellenőrzés | Ingyenes | [mabisz.hu](https://mabisz.hu/) |
| **TotalCar Autóértékelés** | Használt autók piaci értéke | Ingyenes | [totalcar.hu](https://totalcar.hu/autos-ertek/) |
| **Carvertical** | Jármű-előélet ellenőrzés (EU) | Fizetős | [carvertical.com/hu](https://www.carvertical.com/hu) |

### Közlekedési kamerák és forgalom

| Szolgáltatás | Leírás | Link |
|--------------|--------|------|
| **Útinform** | Magyar közúti helyzet | [utinform.hu](https://www.utinform.hu/) |
| **Waze Live Map** | Valós idejű forgalom | [waze.com/hu/live-map](https://www.waze.com/hu/live-map) |
| **BKK Futár** | Budapest közlekedés | [futar.bkk.hu](https://futar.bkk.hu/) |
| **MÁV Menetrend** | Vasúti közlekedés | [mavcsoport.hu](https://jegy.mav.hu/) |

### Légi forgalom

| Szolgáltatás | Leírás | Link |
|--------------|--------|------|
| **Flightradar24** | Repülőgép-követés | [flightradar24.com](https://www.flightradar24.com/) |
| **ADS-B Exchange** | Nyílt légiforgalmi adat | [adsbexchange.com](https://www.adsbexchange.com/) |
| **FlightAware** | Járatinformációk | [flightaware.com](https://www.flightaware.com/) |

---

## 🏠 Ingatlan és térképészet

### Ingatlan-nyilvántartás

| Szolgáltatás | Leírás | Ár | Link |
|--------------|--------|-----|------|
| **Földhivatal Online** | Tulajdoni lap lekérdezés | Fizetős (Ügyfélkapu) | [foldhivatal.hu](https://www.foldhivatal.hu/) |
| **e-Közmű** | Közművezetékek térképe | Ingyenes | [e-epites.hu/ekozmu](https://www.e-epites.hu/e-kozmu) |
| **MePAR** | Mezőgazdasági parcella azonosító | Ingyenes | [mepar.hu](https://www.mepar.hu/) |
| **LECHNER Térkép** | Szakági nyilvántartások | Ingyenes | [lfrinfo.hu](https://www.lfrinfo.hu/) |
| **Fentrol.hu** | Légifotó Archívum (1950-1990 közötti légifotók) | Ingyenes | [fentrol.hu](https://www.fentrol.hu/) |

### Térképek és műholdas felvételek

| Szolgáltatás | Leírás | Link |
|--------------|--------|------|
| **Google Maps / Street View** | Utcakép, térkép | [google.com/maps](https://www.google.com/maps) |
| **OpenStreetMap** | Nyílt térképadatok | [openstreetmap.org](https://www.openstreetmap.org/) |
| **Google Earth Pro** | Műholdas felvételek, időgép | [earth.google.com](https://earth.google.com/) |
| **Bing Maps** | Bird's Eye nézet | [bing.com/maps](https://www.bing.com/maps) |
| **FÖMI Térképtár** | Történeti térképek | [mapire.eu](https://mapire.eu/hu/) |

### Webkamerák

| Szolgáltatás | Leírás | Link |
|--------------|--------|------|
| **Időkép Webkamerák** | Élő kamerák országszerte | [idokep.hu/webkamera](https://www.idokep.hu/webkamera) |
| **Budapest Cameras** | Budapest forgalmi kamerák | [bfrk.hu](https://bfrk.hu/) |

---

## ⚖️ Bíróságok és jogtárak

### Bírósági adatbázisok

| Szolgáltatás | Leírás | Link |
|--------------|--------|------|
| **Bírósági Határozatok Gyűjteménye (BH)** | Anonimizált ítéletek keresése | [birosag.hu/birosagi-hatarozatok](https://birosag.hu/birosagi-hatarozatok-gyujtemenye) |
| **Tárgyalási jegyzék** | Bírósági tárgyalások listája | [birosag.hu/targyalasi-jegyzek](https://birosag.hu/targyalasi-jegyzek) |
| **Cégbíróság** | Cégbírósági eljárások | [birosag.hu](https://birosag.hu/) |
| **Felszámolási Névjegyzék** | Csődbe ment cégek | [cegkozlony.hu](https://www.cegkozlony.hu/) |

### Jogszabályok és közlönyök

| Szolgáltatás | Leírás | Link |
|--------------|--------|------|
| **Magyar Közlöny** | Hivatalos jogszabályok, kinevezések | [magyarkozlony.hu](https://magyarkozlony.hu/) |
| **Nemzeti Jogszabálytár** | Hatályos jogszabályok | [njt.hu](https://njt.hu/) |
| **EUR-Lex** | EU jogszabályok | [eur-lex.europa.eu](https://eur-lex.europa.eu/homepage.html?locale=hu) |
| **Cégközlöny** | Cégbírósági bejegyzések | [cegkozlony.hu](https://www.cegkozlony.hu/) |

### Egyéb nyilvántartások

| Szolgáltatás | Leírás | Link |
|--------------|--------|------|
| **Civil szervezetek névjegyzéke** | Alapítványok, egyesületek | [birosag.hu](https://birosag.hu/civil-szervezetek-nevjegyzeke) |
| **Végrehajtói Kamara** | Végrehajtási ügyek | [mbvk.hu](https://www.mbvk.hu/) |
| **Ügyvédi Kamara** | Ügyvédek keresése | [magyarugyvedikamara.hu](https://www.magyarugyvedikamara.hu/) |

---

## 📚 Archívumok és média

### Digitális archívumok

| Szolgáltatás | Leírás | Ár | Link |
|--------------|--------|-----|------|
| **Arcanum Digitális Tudománytár (ADT)** | Újságok, folyóiratok, könyvek archívuma | Fizetős | [adt.arcanum.com](https://adt.arcanum.com/) |
| **Hungaricana** | Közgyűjtemények portálja | Ingyenes | [hungaricana.hu](https://hungaricana.hu/) |
| **Magyar Nemzeti Levéltár** | Levéltári anyagok | Ingyenes | [mnl.gov.hu](https://mnl.gov.hu/adatbazisokonline) |
| **Fortepan** | Közösségi fotóarchívum | Ingyenes | [fortepan.hu](https://fortepan.hu/) |
| **MTI Archívum** | Magyar Távirati Iroda hírek | Részben ingyenes | [archiv.mti.hu](https://archiv.mti.hu/) |
| **OSZK Digitális Könyvtár** | Országos Széchényi Könyvtár | Ingyenes | [mek.oszk.hu](https://mek.oszk.hu/) |

### Webarchívumok

| Szolgáltatás | Leírás | Link |
|--------------|--------|------|
| **Wayback Machine** | Archivált weboldalak | [web.archive.org](https://web.archive.org/) |
| **Archive.today** | Weboldal pillanatképek | [archive.today](https://archive.today/) |
| **Google Cache** | Google gyorsítótár | `cache:URL` keresés |

### Hírportálok (oknyomozás)

| Portál | Fókusz | Link |
|--------|--------|------|
| **Átlátszó** | Oknyomozó újságírás, közpénzek | [atlatszo.hu](https://atlatszo.hu/) |
| **Direkt36** | Oknyomozó cikkek | [direkt36.hu](https://www.direkt36.hu/) |
| **Telex** | Független hírportál | [telex.hu](https://telex.hu/) |
| **444.hu** | Független média | [444.hu](https://444.hu/) |
| **K-Monitor** | Korrupciófigyelő | [k-monitor.hu](https://k-monitor.hu/) |
| **Transparency International HU** | Korrupció elleni szervezet | [transparency.hu](https://transparency.hu/) |

---

## 🔓 Adatszivárgások és dark web

### Adatszivárgás-ellenőrzés

| Szolgáltatás | Leírás | Link |
|--------------|--------|------|
| **Have I Been Pwned** | Email ellenőrzés szivárgásokban | [haveibeenpwned.com](https://haveibeenpwned.com/) |
| **DeHashed** | Felhasználónév/email/jelszó keresés, breach adatok | [dehashed.com](https://dehashed.com/) |
| **Intelligence X** | Darknet, szivárgott adatok, történeti rekordok keresése | [intelx.io](https://intelx.io/) |
| **Hudson Rock** | Infostealer malware ellenőrzés | [hudsonrock.com](https://www.hudsonrock.com/threat-intelligence-cybercrime-tools) |
| **LeakCheck** | Adatszivárgás-kereső | [leakcheck.io](https://leakcheck.io/) |
| **BreachDirectory** | Credential leak validáció | [breachdirectory.org](https://breachdirectory.org/) |
| **h8mail** | Breach adatok és jelszavak keresése (CLI) | [GitHub](https://github.com/khast3x/h8mail) |
| **Pentester.com** | Email breach detection és digital footprint | [pentester.com](https://pentester.com/) |

### Dark web hozzáférés

| Eszköz | Leírás | Link |
|--------|--------|------|
| **Tor Browser** | .onion oldalak elérése | [torproject.org](https://www.torproject.org/) |
| **Tails OS** | Anonim operációs rendszer | [tails.boum.org](https://tails.boum.org/) |

> ⚠️ **Figyelmeztetés:** A dark web illegális tartalmakat is tartalmaz. Csak legális célokra használd!

---

## 🛠️ OSINT eszközök

- [Dark-Moon](https://github.com/ASCIT31/Dark-Moon) - Nyílt forráskódú, önállóan működő MI-alapú behatolástesztelő platform (self-hosted, MCP-szerver) webes, API-, Active Directory- és Kubernetes-célpontok automatizált felderítésére és biztonsági vizsgálatára; beépített Privacy Gateway adatvédelemhez.
### Automatizált OSINT eszközök

| Eszköz | Leírás | Link |
|--------|--------|------|
| **Maltego** | Kapcsolati hálók vizualizálása, link analysis | [maltego.com](https://www.maltego.com/) |
| **SpiderFoot** | Automatizált OSINT adatgyűjtés, breach és darknet keresés | [spiderfoot.net](https://www.spiderfoot.net/) |
| **theHarvester** | E-mail és domain felderítés | [GitHub](https://github.com/laramies/theHarvester) |
| **Recon-ng** | Web felderítési keretrendszer | [GitHub](https://github.com/lanmaster53/recon-ng) |
| **Photon** | Gyors web crawler | [GitHub](https://github.com/s0md3v/Photon) |
| **Sherlock** | Felhasználónév keresés 400+ oldalon | [GitHub](https://github.com/sherlock-project/sherlock) |
| **Maigret** | Továbbfejlesztett Sherlock, részletes profilok | [GitHub](https://github.com/soxoj/maigret) |
| **Holehe** | Email regisztráció ellenőrzés platformokon | [GitHub](https://github.com/megadose/holehe) |
| **GHunt** | Gmail account részletes információk (név, fotó, YouTube, Drive) | [GitHub](https://github.com/mxrch/GHunt) |
| **Socialscan** | Email és felhasználónév létezés ellenőrzése | [GitHub](https://github.com/iojw/socialscan) |
| **Social Analyzer** | Profil keresés 1000+ oldalon (API támogatás) | [GitHub](https://github.com/qeeqbox/social-analyzer) |
| **sn0int** | Félautomata OSINT keretrendszer (Rust) | [GitHub](https://github.com/kpcyrd/sn0int) |
| **LinkScope Client** | Grafikus link-elemzés, Maltego alternatíva | [GitHub](https://github.com/AccentuSoft/LinkScope_Client) |

### Képelemzés és forensics

| Eszköz | Leírás | Link |
|--------|--------|------|
| **TinEye** | Fordított képkeresés, milliárd archivált kép | [tineye.com](https://tineye.com/) |
| **Google Images** | Fordított képkeresés | [images.google.com](https://images.google.com/) |
| **Yandex Images** | Arcfelismerés-barát keresés (legjobb arcokra) | [yandex.com/images](https://yandex.com/images/) |
| **PimEyes** | Arcfelismerés (fizetős) | [pimeyes.com](https://pimeyes.com/) |
| **FaceCheck.ID** | Valós idejű arcfelismerés közösségi profilokhoz | [facecheck.id](https://facecheck.id/) |
| **Lenso AI** | Arc alapú fordított képkeresés | [lenso.ai](https://lenso.ai/) |
| **FotoForensics** | Képmanipuláció-detektálás (ELA) | [fotoforensics.com](https://fotoforensics.com/) |
| **Jeffrey's EXIF Viewer** | EXIF adatok elemzése | [exif.regex.info](https://exif.regex.info/) |
| **EXIF.tools** | Modern EXIF olvasó GPS, kamera adatokhoz | [exif.tools](https://exif.tools/) |
| **ViewExifData** | Egyszerű EXIF metaadat megjelenítő | [viewexifdata.com](https://www.viewexifdata.com/) |
| **Search by Image** | Böngésző extension multi-engine képkereséshez | [GitHub](https://github.com/dessant/search-by-image) |

### Geolokációs eszközök

| Eszköz | Leírás | Link |
|--------|--------|------|
| **Google Earth Pro** | Műholdképek, mérések | [earth.google.com](https://earth.google.com/) |
| **SunCalc** | Napállás alapú geolokáció | [suncalc.org](https://www.suncalc.org/) |
| **GeoGuessr** | Geolokációs gyakorlás | [geoguessr.com](https://www.geoguessr.com/) |
| **What3Words** | 3 szavas helymeghatározás | [what3words.com](https://what3words.com/) |
| **Mapillary** | Utcaképek közösségi adatbázisa | [mapillary.com](https://www.mapillary.com/) |
| **GeoSpy AI** | AI geolokáció fotókból EXIF adatok nélkül | [geospy.ai](https://geospy.ai/) |

### Felhasználónév keresők

| Eszköz | Leírás | Link |
|--------|--------|------|
| **Sherlock** | 400+ oldalon keres (CLI) | [GitHub](https://github.com/sherlock-project/sherlock) |
| **Maigret** | Sherlock továbbfejlesztett verzió, részletes profilok | [GitHub](https://github.com/soxoj/maigret) |
| **WhatsMyName** | 500+ oldalon keres (webes) | [whatsmyname.app](https://whatsmyname.app/) |
| **OSINT.Rocks** | Sherlock + Maigret webes verzió, 500+ platform | [osint.rocks](https://osint.rocks/) |
| **Namechk** | Felhasználónév elérhetőség | [namechk.com](https://namechk.com/) |
| **KnowEm** | 550+ oldalon keres | [knowem.com](https://knowem.com/) |
| **CastrickClues** | Digitális lábnyom email/username/telefon alapján | [castrickclues.com](https://castrickclues.com/) |
| **Blackbird** | Felhasználónév keresés 600+ oldalon (CLI) | [GitHub](https://github.com/p1ngul1n0/blackbird) |

### E-mail eszközök

| Eszköz | Leírás | Link |
|--------|--------|------|
| **Hunter.io** | Céges e-mail címek keresése | [hunter.io](https://hunter.io/) |
| **EmailRep** | E-mail reputáció és kockázat ellenőrzés | [emailrep.io](https://emailrep.io/) |
| **Epieos** | E-mail kapcsolódó fiókok, közösségi profilok | [epieos.com](https://epieos.com/) |
| **Holehe** | Email regisztráció ellenőrzés platformokon | [GitHub](https://github.com/megadose/holehe) |
| **GHunt** | Gmail részletes adatok (név, fotó, YouTube, Drive) | [GitHub](https://github.com/mxrch/GHunt) |
| **Email Permutator** | E-mail címek generálása | [metricsparrow.com](https://metricsparrow.com/toolkit/email-permutator/) |

### Telefonszám OSINT

| Eszköz | Leírás | Link |
|--------|--------|------|
| **PhoneInfoga** | Telefonszám részletek (lokáció, szolgáltató, típus) | [GitHub](https://github.com/sundowndev/phoneinfoga) |
| **Epieos (Phone)** | Telefonszám alapján közösségi profilok | [epieos.com](https://epieos.com/) |
| **Truecaller** | Hívószám azonosítás, spam védelem | [truecaller.com](https://www.truecaller.com/) |
| **Sync.ME** | Hívószám azonosítás közösségi média alapján | [sync.me](https://sync.me/) |

### Weboldal és domain eszközök

| Eszköz | Leírás | Link |
|--------|--------|------|
| **ViewDNS.info** | 20+ DNS eszköz (WHOIS, reverse IP, stb.) | [viewdns.info](https://viewdns.info/) |
| **DNSDumpster** | DNS recon, subdomain keresés, vizualizáció | [dnsdumpster.com](https://dnsdumpster.com/) |
| **Wappalyzer** | Weboldal tech stack azonosítás | [wappalyzer.com](https://www.wappalyzer.com/) |
| **BuiltWith** | Weboldal technológia elemzés | [builtwith.com](https://builtwith.com/) |
| **URLScan** | URL elemzés, phishing és malware detektálás | [urlscan.io](https://urlscan.io/) |
| **Shodan** | IoT eszközök, nyitott portok keresése | [shodan.io](https://www.shodan.io/) |
| **Censys** | Domain, IP, SSL certificate keresés | [censys.io](https://censys.io/) |
| **ZoomEye** | Eszközök, protokollok, CVE-k keresése | [zoomeye.org](https://www.zoomeye.org/) |
| **FOFA** | Globális eszköz és port fingerprinting | [fofa.info](https://fofa.info/) |
| **OWASP Amass** | DNS felderítés, subdomain keresés | [GitHub](https://github.com/owasp-amass/amass) |
| **Web-Check** | All-in-one weboldal elemzés (30+ ellenőrzés) | [web-check.as93.net](https://web-check.as93.net/) |
| **ChangeDetection.io** | Weboldal-változás figyelés, nyílt forráskódú | [GitHub](https://github.com/dgtlmoon/changedetection.io) |

### Fenyegetés-felderítés (Threat Intelligence)

| Eszköz | Leírás | Link |
|--------|--------|------|
| **VirusTotal** | Fájl, URL, IP ellenőrzés 70+ AV motorral | [virustotal.com](https://www.virustotal.com/) |
| **ANY.RUN** | Interaktív malware sandbox | [any.run](https://any.run/) |
| **Hybrid Analysis** | Malware elemzés és viselkedés profilozás | [hybrid-analysis.com](https://www.hybrid-analysis.com/) |
| **Onyphe** | Cyber threat intelligence, dark web monitoring | [onyphe.io](https://www.onyphe.io/) |
| **OnionScan** | .onion hidden service elemzés | [GitHub](https://github.com/s-rah/onionscan) |

---

## 🔍 Körözések és eltűnt személyek

### Magyar körözési adatbázisok

| Szolgáltatás | Leírás | Link |
|--------------|--------|------|
| **Körözési Toplista** | Legkeresettebb személyek | [police.hu](https://www.police.hu/hu/koral/toplistas-korozesek) |
| **Körözési adatbázis** | Összes nyilvános körözés | [police.hu/koral](https://www.police.hu/hu/koral) |
| **Telefontanú** | Anonim bejelentések | [police.hu](https://www.police.hu/hu/ugyintezes/telefontanu) |

### EU és nemzetközi

| Szolgáltatás | Leírás | Link |
|--------------|--------|------|
| **EU Most Wanted** | Európai körözési lista (ENFAST) | [eumostwanted.eu](https://eumostwanted.eu/) |
| **Interpol Red Notices** | Nemzetközi körözések | [interpol.int](https://www.interpol.int/How-we-work/Notices/Red-Notices) |
| **FBI Most Wanted** | FBI körözési lista | [fbi.gov/wanted](https://www.fbi.gov/wanted) |
| **NamUs** | USA eltűnt személyek | [namus.nij.ojp.gov](https://www.namus.gov/) |

---

## 📊 Közérdekű adatok

### Nemzeti Közadatportál

| Szolgáltatás | Leírás | Link |
|--------------|--------|------|
| **OpenData.gov.hu** | Magyar nyílt adatok | [opendata.gov.hu](https://opendata.gov.hu/) |
| **KSH** | Központi Statisztikai Hivatal | [ksh.hu](https://www.ksh.hu/) |
| **Közbeszerzési Hatóság** | Közbeszerzési adatok | [kozbeszerzes.hu](https://www.kozbeszerzes.hu/) |
| **EKR** | Elektronikus Közbeszerzési Rendszer | [ekr.gov.hu](https://ekr.gov.hu/) |

### Vagyonnyilatkozatok és átláthatóság

| Szolgáltatás | Leírás | Link |
|--------------|--------|------|
| **Vagyonnyilatkozat-kereső** | Képviselők vagyonnyilatkozatai | [parlament.hu](https://www.parlament.hu/kepviselok/vagyonnyilatkozatok) |
| **K-Monitor Adat** | Közpénz-adatbázis | [k-monitor.hu](https://adatbazis.k-monitor.hu/) |
| **Red Flags** | Közbeszerzési anomália-jelző (K-Monitor, adatok: 2012–2023) | [redflags.eu](https://www.redflags.eu/) |

### Nemzetközi oknyomozói adatbázisok

| Szolgáltatás | Leírás | Link |
|--------------|--------|------|
| **OCCRP Aleph** | 277M+ entitás: cégek, személyek, dokumentumok, kiszivárgott anyagok | [aleph.occrp.org](https://aleph.occrp.org/) |
| **ICIJ Offshore Leaks** | 810 000+ offshore entitás (Panama Papers, Pandora Papers stb.) | [offshoreleaks.icij.org](https://offshoreleaks.icij.org/) |
| **OpenSanctions** | Szankciós listák, PEP személyek, 325 forrás, 2M+ entitás | [opensanctions.org](https://www.opensanctions.org/) |

---

## 🔗 Külső OSINT források

### Magyar és nemzetközi OSINT gyűjtemények

| Forrás | Leírás | Link |
|--------|--------|------|
| **HUN-OSINT Start.me** | Átfogó magyar OSINT dashboard | [start.me/p/kxGLzd/hun-osint](https://start.me/p/kxGLzd/hun-osint) |
| **HU OSINT Hub** | OSINT eszközök kategorizálva (HackersUnskool) | [osint.hackersunskool.com](https://osint.hackersunskool.com/) |
| **OSINT Framework** | Klasszikus OSINT eszköz-keretrendszer | [osintframework.com](https://osintframework.com/) |
| **Cylect** | AI OSINT keresőmotor (domain, email, username, IP, crypto, sandbox) | [cylect.io](https://cylect.io/) |
| **Awesome OSINT** | GitHub OSINT gyűjtemény | [GitHub](https://github.com/jivoi/awesome-osint) |
| **IntelTechniques** | Michael Bazzell OSINT eszközök | [inteltechniques.com](https://inteltechniques.com/tools/) |
| **Bellingcat Toolkit** | Oknyomozó újságírás eszközei | [bellingcat.com](https://www.bellingcat.com/category/resources/) |
| **CybDetective OSINT Map** | Interaktív OSINT térkép országonként | [cybdetective.com](https://cybdetective.com/osintmap) |
| **OSINT Dojo** | OSINT tanulási források | [osintdojo.com](https://www.osintdojo.com/) |

### Hasznos OSINT közösségek

| Közösség | Leírás | Link |
|----------|--------|------|
| **Trace Labs** | Eltűnt személyek keresése CTF-eken | [tracelabs.org](https://www.tracelabs.org/) |
| **OSINT Curious** | OSINT podcast és közösség | [osintcurio.us](https://osintcurio.us/) |
| **r/OSINT** | Reddit OSINT közösség | [reddit.com/r/OSINT](https://www.reddit.com/r/OSINT/) |
| **OSINT.team** | OSINT eszközök és technikák | [osint.team](https://osint.team/) |

---

## 🤝 Hozzájárulás

Szívesen fogadom a hozzájárulásokat! Kérlek, olvasd el a [CONTRIBUTING.md](CONTRIBUTING.md) fájlt a részletekért.

### Hogyan járulhatsz hozzá?

1. **Fork** a repository-t
2. Készíts egy **új branch**-et (`git checkout -b feature/uj-funkcio`)
3. **Commit**-old a változtatásokat (`git commit -am 'Új forrás hozzáadása'`)
4. **Push** a branch-re (`git push origin feature/uj-funkcio`)
5. Nyiss egy **Pull Request**-et

### Mit fogadok el?

✅ Működő, ellenőrzött linkek  
✅ Magyar vagy EU-specifikus források  
✅ Legális OSINT eszközök  
✅ Jól dokumentált hozzájárulások

❌ Illegális eszközök vagy módszerek  
❌ Nem működő linkek  
❌ Duplikált tartalom

---

## 📜 Licenc

Ez a projekt [MIT License](LICENSE) alatt áll.

---

## ⭐ Támogatás

Ha hasznosnak találod ezt a gyűjteményt:

- ⭐ **Star**-old a repository-t
- 🔗 **Oszd meg** kollégáiddal
- 🐛 **Jelentsd** a hibás linkeket
- ✍️ **Járulj hozzá** új forrásokkal

---

**Utolsó frissítés:** 2026. február

**Készítette:** HUN-OSINT

---

> *"A nyílt forráskódú hírszerzés nem a titkokat keresi, hanem a nyilvánosan elérhető információkat értelmezi."*
