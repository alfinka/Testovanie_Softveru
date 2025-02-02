# 👨‍💻 Testovanie Softvéru
Materiály k online kurzu Testovanie Softvéru

# 🎓 Požiadavky na SW Testerov, QA Manažérov a Test Analytikov
1. https://www.alianciasr.sk/najziadanejsie-nedostatkove-pracovne-pozicie-na-trhu-prace/
1. https://www.sustavapovolani.sk/register-zamestnani/pracovna-oblast/karta-zamestnania/17936-ikt-tester/
1. https://www.nsp.cz/jednotka-prace/softwarovy-tester
1. https://www.nsp.cz/jednotka-prace/tester-automatizovaneho-t
1. https://www.surveymonkey.com/r/SOQR25?utm_source=website&utm_medium=login-page 
1. https://www.howtodeal.dev/
1. https://neilonsoftware.com/

![image](https://github.com/user-attachments/assets/296176db-6421-4197-967c-63b706d4af46)

## 💰 Práca, projekty a prax pre testerov
1.	uTest - všetky možné testy aj pre začiatočníkov
2.	usertesting - UI testy aj pre začiatočníkov
3.	trymyui - UI testy aj pre začiatočníkov
4.	intellizoom - UI testy aj pre začiatočníkov
5.	Facebook skupina Testeri
6.	Facebook skupina QA Testers Slovakia
7.	Profesia IT tester
8.	Robime.it - Mediori, Seniori, výnimočné aj juniori pozície
9.	Titans Slovakia - Mediori a Seniori
10.	Toptal - Ultra mega Senior

# 🛠 Typy SW Testov a Nástrojov
1. Funkčné testovanie
1. API testovanie 
1. Regresné testovanie 
1. Výkonnostné testovanie	 
1. End-to-End testovanie 
1. Testovanie použiteľnosti  
1. Smoke testovanie 
1. Bezpečnostné testovanie	 
1. Testovanie kompatibility  
1. Testovanie integrácie


## 🧪 Rozdelenie Testovania SW
![image](https://github.com/user-attachments/assets/8cc0e4af-1dd4-431f-bd35-7357c8b72fdf)

**Cvičenia na správnu kategorizáciu testov**
1. Pri zadávaní emailovej adresy do formulára je zobrazené chybové hlásenie, ak je email neplatný (napr. bez „@“ alebo „.com“).  
1. Po zadaní nesprávneho používateľského mena a hesla sa zobrazí chybové hlásenie a používateľ nie je prihlásený.  
1. Testovanie webovej stránky na rôznych zariadeniach (mobil, tablet, desktop) a kontrola, či sa stránka správne zobrazuje na každom z nich.  
1. Po odoslaní objednávky cez nákupný košík systém správne vypočíta celkovú cenu a aplikuje zľavu.  
1. Používateľ klikne na neexistujúci odkaz a zobrazí sa stránka 404 „Stránka neexistuje“.  
1. Používateľ vyplní prihlásenie, ale počas procesu zistí, že zabudol heslo a klikne na odkaz na obnovenie hesla.  
1. Otestovanie, či systém správne reaguje na pokus o SQL injection v prihlasovacom formulári.  
1. Počas testovania na rôznych prehliadačoch (Chrome, Firefox, Safari) sa stránky načítajú správne bez vizuálnych a funkčných problémov.  
1. Po odoslaní formulára na stránke sa zobrazuje správne chybové hlásenie, ak niektoré polia zostanú prázdne.  
1. Na stránke sa testuje, či sa obsah (obrázky, texty) zobrazuje správne a či sa stránka načíta rýchlo aj pri vyššom počte súčasných používateľov  

**Vzorový výstup pre cvičenie:**  
Typ testovania podľa úrovne: Testovanie jednotiek  
Typ testovania podľa prístupu: Gray-box  
Typ testovania podľa cieľa: Testovanie funkčnosti  
Typ testovania podľa automatizácie: Automatizované  
Typ testovania podľa typu softvéru: Testovanie web. app  
Testovaná vlastnosť: Validácia vstupov (formuláre)  
Prístup overovania systému: Overenie výstupov  

## 🔎 Exploratívne testovanie 
Zameriava na objavovanie nečakaných chýb a problémov v aplikácii. Testeri používajú svoje skúsenosti a intuíciu na interakciu s aplikáciou.  
Cieľom je odhaliť nepredvídateľné problémy a potenciálne nedostatky, ktoré nemusia byť zachytené počas systematického testovania.  

**Typické scenáre:**
- Testovanie interakcií medzi rôznymi časťami aplikácie bez predchádzajúcej analýzy scenárov.  
- Zistenie, či používateľ môže vykonať sériu akcií, ktoré neboli pôvodne zohľadnené v testovacích prípadoch.  
- Overenie reakcie aplikácie na neštandardné alebo neobvyklé vstupy, ktoré nie sú explicitne uvedené v požiadavkách.  

**Príklady:**
1. Skúšanie funkčnosti formulárov pri zadaní rôznych neštandardných hodnôt (napr. nečakané špeciálne znaky alebo dlhé reťazce).  
1. Otestovanie správania aplikácie pri rýchlej alebo pomalej navigácii medzi stránkami.  
1. Testovanie možnosti použitia aplikácie bez pripojenia na internet a následné obnovenie pripojenia.  
1. Skúmanie stabilnosti aplikácie pri náhodných alebo neplánovaných interakciách medzi tlačidlami alebo formulármi.  

**Cvičenia na identifikáciu exploratívneho testovania**
Scenár 1: Aplikácia na správu osobných financií umožňuje používateľom pridať, upravit a odstrániť výdavky. Po pridaní výdavku sa automaticky aktualizuje zostatok na účte a zobrazí sa upozornenie o prebytku alebo nedostatku financií.  
Scenár 2: Aplikácia pre spravovanie zoznamu úloh umožňuje používateľom pridávať, upravovať, označovať ako dokončené a odstraňovať úlohy. Každá úloha má názov, popis a dátum splnenia.  
Scenár 3:  Aplikácia pre e-commerce (eshop) umožňuje zákazníkom pridať produkty do nákupného košíka, prejsť k pokladni, vybrať spôsob platby a dokončiť nákup.  
Scenár 4: Aplikácia na spracovanie platieb zabezpečuje, že každý platobný príkaz je spracovaný podľa stanovených pravidiel a že údaje o platbách sú správne zaznamenané v databáze.  
Scenár 5: Mobilná aplikácia na sledovanie športových výkonov zaznamenáva aktivitu používateľov, analyzuje ich výkony a poskytuje odporúčania na zlepšenie.  

Je exploratívne testovanie vhodné pre tento scenár?  
Ak nie, aký typ testovania je vhodný a prečo?  

## 🤖 Automatizované/Web/API/Mobile/Desktop/UI Testy
1.	Doplnok Selenium IDE: https://chrome.google.com/webstore/detail/selenium-ide/mooikfkahbdckldjjndioackbalphokd
2.	Doplnok Katalon Recorder: https://chrome.google.com/webstore/detail/katalon-recorder-selenium/ljdobmomdgdljniojadhoplhkpialdid 
3.	Katalon Studio: https://www.katalon.com/katalon-studio/ 
4.	BlazeMeter | The Continuous Testing Platform: https://chrome.google.com/webstore/detail/blazemeter-the-continuous/mbopgmdnpcbohhpnfglgohlbhfongabi 
5.	Ranorex: https://www.ranorex.com/ 
6.	Tricentis Tosca: https://www.tricentis.com/products/automate-continuous-testing-tosca 
7.	BugBug: https://bugbug.io/ 
8.	Testsigma: https://testsigma.com/ 
9.	TestRigor: https://testrigor.com/
    
## 🛠️ Testerské doplnky k manuál a auto. Test. (ideálne Chrome)
1.	Test & Feedback: https://chrome.google.com/webstore/detail/test-feedback/gnldpbnocfnlkkicnaplmkaphfdnlplb/related 
2.	Exploratory Testing Chrome Extension: https://chrome.google.com/webstore/detail/exploratory-testing-chrom/khigmghadjljgjpamimgjjmpmlbgmekj/related 
3.	Bug Magnet: https://chrome.google.com/webstore/detail/bug-magnet/efhedldbjahpgjcneebmbolkalbhckfi/related 
4.	Bird Eats Bug: Technical Screen Recording: https://chrome.google.com/webstore/detail/bird-eats-bug-technical-s/mdplmiioglkpgkdblijgilgebpppgblm 
5.	Fake Filler: https://chrome.google.com/webstore/detail/fake-filler/bnjjngeaknajbdcgpfkgnonkmififhfo 
6.	Check My Links: https://chrome.google.com/webstore/detail/check-my-links/ojkcdipcgfaekbeaelaapakgnjflfglf 
7.	Resolution Test: https://chrome.google.com/webstore/detail/resolution-test/idhfcdbheobinplaamokffboaccidbal 
8.	Window Resizer: https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh 
 
## 📈 Štatistické a analytické nástroje pre testerov
1.	Statista - Celosvetové štatistiky
2.	Statista - Štatistiky využívania prehliadačov
3.	Statcounter - Podiel desktopových prehliadačov na trhu v Európe
4.	Support Google - Prístup do Google Analytics Demo Účtu
5.	Google Analytics - Testovací Účet pre Merchandise Store
6.	Google Merchandise Store - Eshop Google
   
## 🧰 Nástroje pre Cross-platform testovanie pre testerov
1.	BrowserStack - Desktop + Mobile appky
2.	BrowserStack Dashboard - Automatizované testovanie naprieč platformami
3.	Anaconda + Jupyter Python - Automatizované testovanie Python
4.	Selenium IDE - Doplnok do prehliadača na UI Automatizované testovanie
5.	Opera Install Chrome Extensions - Doplnok pre inštalácia Chrome doplnkov do Opery

## 🖥️ Profil a Akcept/Pilotné testovanie (Acceptance/Pilot Testing)
1.	Supportdetails (Aký máte počítač...): https://supportdetails.com/ 
2.	Speccy: https://www.ccleaner.com/speccy 
3.	Wappalyzer: https://chrome.google.com/webstore/detail/wappalyzer-technology-pro/gppongmhjkpfnbhagpmjfkannfbllamg/related 
4.	BuiltWith: https://chrome.google.com/webstore/detail/builtwith-technology-prof/dapjbgnjinbpoindlpdmhochffioedbn 
5.	Visual Ping (Zmeny na webe/aplikácií): https://visualping.io/ 
6.	UptimeRobot (Dostupnosť/Spoľahlivosť): https://uptimerobot.com/ 
7.	Screaming Frog (SEO): https://www.screamingfrog.co.uk 
8.	Kobiton: https://kobiton.com/
   
## 🕸️ API/Funkčné/Performance/Load/Stress/Speed/Web Testy
1.	Screaming Frog: https://www.screamingfrog.co.uk/seo-spider/ 
2.	SoapUI: https://www.soapui.org/tools/soapui 
3.	Postman: https://www.postman.com/ 
4.	Cypress.io: https://www.cypress.io/ 
5.	Stoplight: https://stoplight.io/ 
6.	Insomnia: https://insomnia.rest/ 
7.	Apache JMeter: https://jmeter.apache.org/ 
8.	Pingdom: https://tools.pingdom.com/ 
9.	GTmetrix: https://gtmetrix.com/
10.	Google Page Speed Insights/Lighthouse: https://pagespeed.web.dev/
    
## 👨‍💻 Testovanie použiteľnosti (Usability Testing)
1.	Userlytics: https://www.userlytics.com/ 
2.	UserZoom: https://www.userzoom.com/ 
3.	Enroll: https://enrollapp.com/ 
4.	UserFeel: https://www.userfeel.com/ 
5.	Analysia: https://www.analysia.com/
   
## 👮 Penetračné/Security Testy
1.	Vega: https://subgraph.com/vega/ 
2.	Burp Suite Community Edition: https://portswigger.net/support/using-burp-to-detect-sql-injection-flaws 
3.	Havij: https://www.darknet.org.uk/2010/09/havij-advanced-automated-sql-injection-tool/ 
4.	Kali Linux: https://www.kali.org/ 
	 
## 💡 Princípy Testovania (ISTQB)
1. Testovanie ukazuje prítomnosť defektov, nie ich neprítomnosť (Buxton 1970)
1. Kompletné testovanie nie je možné (Manna 1978)
1. Včasné testovanie šetrí čas a peniaze (Boehm 1981)
1. Zhlukovanie defektov (Enders 1975)
1. Testy sa opotrebovávajú (Beizer 1990)
1. Testovanie je závislé na kontexte (Kaner 2011)
1. Neprítomnosť defektov je klam (Boehm 1981)

## 📜 V-Model
![image](https://github.com/user-attachments/assets/a781d672-b573-4503-81ce-d6d8eba54f26)

![image](https://github.com/user-attachments/assets/d08b1cbd-895e-4f85-91be-20d737eb4438)

# 🐞 Čo je Chyba a Defekt?
![image](https://github.com/user-attachments/assets/c13b597d-8298-40e4-af15-475c3223530b)

1. Nesprávne rozdelenie úloh medzi tímom
1. Nefunkčné prihlásenie do systému
1. Nesprávne zobrazenie dát v tabuľke
1. Zabudnutie na testovanie
1. Nesprávna kalkulácia cien v nákupnom košíku
1. Chyba v komunikácii medzi tímami
1. Nesprávna správa verzí
1. Výpadok servera pri zvýšenom zaťažení
1. Nedostatočné školenie používateľov
1. Nezohľadnenie bezpečnostných aspektov
1. Pretečenie zásobníka (stack overflow)
1. Nezabezpečené uchovávanie hesiel

## 🔄 Životný cyklus defektu
![image](https://github.com/user-attachments/assets/bf9da579-0fe4-434f-8ea6-823ce595b944)

## 👔 Nástroje na správu a riadenie defektov (Test a Bug Management)
1.	GitHub Issues: https://github.com/ 
2.	Mantis Bug Tracker: https://www.mantisbt.org/bugs/login_page.php 
3.	SAP ALM Cloud: https://support.sap.com/en/alm/demo-systems/cloud-alm-demo-system.html 
4.	Katalon TestOps: https://analytics.katalon.com/ 
5.	YouTrack: https://www.jetbrains.com/youtrack/ 
6.	Jira a Confluence: https://www.atlassian.com/software/jira/features/bug-tracking
7.	Bugzilla: https://www.bugzilla.org/
8.	DownDetector: https://downdetector.com/

# 💡 Zaujímavé odkazy a zdroje
1.	https://www.blazemeter.com/blog/top-15-ui-test-automation-best-practices-you-should-follow 
2.	https://www.ui42.sk/blog/13-zisteni-ako-vylepsit-formulare-na-web-strankach
3.	https://developers.facebook.com/docs/javascript/examples/ 
4.	https://www.toptal.com/services/software-quality-assurance 
5.	https://stackoverflow.com/questions/3065485/understanding-how-software-testing-works-and-what-to-test 
6.	https://www.nsp.cz/jednotka-prace/softwarovy-tester 
7.	https://www.sustavapovolani.sk/karta_zamestnania-17936 
8.	http://automation-beyond.com/wp/wp-content/uploads/2011/04/FUNCTIONALITY.jpg 
9.	https://www.platy.sk/platy/informacne-technologie/it-tester-automatizovane-testy?search=1 
10.	https://www.mirri.gov.sk/wp-content/uploads/2020/08/R1_1_DNR_DETAILNY-NAVRH-RIESENIA_Projekt_AA_Ovm_BB_OsobaXY_DDMMYY_v0.1.docx 
11.	https://support.utest.com/csp?id=csp_index 

