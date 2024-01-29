[Zpět na přehled okruhů](../README.md)

# Počítačový systém v softwarovém inženýrství
Počítačový systém v softwarovém inženýrství zahrnuje interakci hardwaru a softwaru pro dosažení určitého cíle nebo řešení konkrétního problému. Zde jsou některé klíčové aspekty počítačových systémů v softwarovém inženýrství:

1. **Hardwarová a softwarová architektura:**
   - **Hardwarová architektura:** Zahrnuje fyzické komponenty počítače, jako jsou procesory, paměť, periferní zařízení a další. Architektura ovlivňuje výkonnost a schopnosti počítačového systému.
   - **Softwarová architektura:** Definuje strukturu a organizaci softwarových komponentů, které běží na hardwaru. Architektura zahrnuje návrh a rozdělení funkcionalit mezi různé části softwaru.

2. **Operační systém:**
   - **Operační systém (OS):** Je základním softwarem, který spravuje hardwarové a softwarové zdroje počítače. Zajišťuje komunikaci mezi hardwarovými komponenty a aplikacemi, řídí procesy, spravuje paměť a zajišťuje spolehlivý běh celého systému.

3. **Vývoj softwaru:**
   - **Životní cyklus softwarového vývoje:** Zahrnuje fáze od definice požadavků a návrhu přes implementaci a testování až po údržbu a aktualizace.
   - **Metodologie vývoje:** Různé metody a postupy pro řízení vývoje softwaru, jako jsou Vodopádový model, Agilní metody (Scrum, Kanban) nebo DevOps.

4. **Softwarové inženýrství a návrh:**
   - **Návrhové vzory:** Opakující se řešení pro běžné problémy v návrhu softwaru.
   - **Objektově orientovaný návrh (OOP):** Paradigma, které koncepci rozděluje do objektů, které mohou obsahovat data a funkce.

5. **Testování a kvalita softwaru:**
   - **Testování softwaru:** Identifikuje chyby a ověřuje správnost a spolehlivost softwaru.
   - **Zajišťování kvality:** Praktiky a procesy, které se snaží zajistit vysokou kvalitu softwaru od počátečního návrhu až po nasazení.

6. **Správa konfigurace a verzování:**
   - **Správa konfigurace:** Řídí změny v softwarových konfiguracích a sleduje vztahy mezi různými verzemi softwaru.
   - **Verzování:** Umožňuje sledování historie změn v kódu a umožňuje obnovení předchozích verzí.

7. **Bezpečnost:**
   - **Bezpečnostní mechanismy:** Implementace zabezpečení na úrovni softwaru, například šifrování dat, ověřování totožnosti nebo správa oprávnění.

8. **Distribuované systémy:**
   - **Distribuované aplikace:** Softwarové aplikace, které běží na více než jednom počítači a komunikují přes síť.
   - **Síťová komunikace:** Zahrnuje protokoly a techniky pro komunikaci mezi různými částmi distribuovaného systému.

9. **Správa projektu:**
   - **Nástroje a metody pro správu projektu:** Pomáhají organizovat práci týmu, plánovat úkoly a sledovat pokrok v rámci softwarového vývoje.

Toto jsou obecné oblasti a koncepty spojené s počítačovým systémem v softwarovém inženýrství. Pokud máte konkrétní otázky nebo potřebujete další informace o některém z těchto témat, dejte mi vědět!

# Nástroje pro vývoje software a jeho životní cyklus
Existuje mnoho nástrojů pro vývoj softwaru a správu jeho životního cyklu. Tyto nástroje pomáhají týmům v organizaci, sledování a optimalizaci procesů od počáteční fáze analýzy až po nasazení a údržbu. Zde je seznam několika kategorií nástrojů a několika konkrétních příkladů:

### **Správa projektu a spolupráce:**
1. **Jira (Atlassian):** Výkonný nástroj pro sledování úkolů, správu projektů a agilní plánování.


### **Správa verzování a kódu:**
1. **Git:** Distribuovaný systém pro správu verzí kódu.
2. **GitHub, GitLab:** Webové platformy pro hostování projektů postavených na Gitu, poskytující sledování chyb, kolaboraci a další funkce.

### **Návrh a vývoj:**
1. **IDE (Integrated Development Environment):**
   - **Visual Studio Code, IntelliJ IDEA:** IDE pro mnoho programovacích jazyků.
2. **Nástroje pro kolaborativní vývoj:**
   - **VS Live Share, CodeTogether:** Umožňují vývojářům spolupracovat v reálném čase.

### **Testování:**
1. **Selenium:** Automatizovaný nástroj pro testování webových aplikací.
2. **JUnit, NUnit, pytest:** Rámce pro jednotkové testování v různých programovacích jazycích.

### **Integrace a doručování:**
1. **GitLab CI/CD:** Nástroje pro automatizaci procesů integrace a doručování.
2. **Docker:** Platforma pro kontejnerizaci aplikací, což usnadňuje přenositelnost a nasazování.

### **Správa požadavků a analýza:**
1. **Confluence (Atlassian):** Nástroj pro sdílení a spolupráci na dokumentaci.
2. **IBM Engineering Requirements Management DOORS:** Nástroje pro správu a sledování požadavků.

### **Monitorování a řízení chyb:**
1. **New Relic, Datadog, Splunk:** Nástroje pro sledování výkonu a analýzu dat.
2. **Bugzilla, Jira:** Systémy pro sledování chyb a správu úkolů.

### **Správa konfigurace:**
1. **Ansible, Puppet, Chef:** Nástroje pro automatizaci konfigurace a nasazování.

### **Dokumentace:**
1. **Swagger, Apiary:** Nástroje pro dokumentaci API.
2. **Doxygen, Sphinx:** Generátory dokumentace kódu.

Toto jsou pouze některé příklady a existuje mnoho dalších specializovaných nástrojů v každé kategorii. Volba konkrétních nástrojů závisí na potřebách týmu, technologiích používaných ve vašem projektu a preferencích vývojářů.

# Git vs SVN
Subversion (SVN) a Git jsou oba systémy pro správu verzí, ale mají několik klíčových rozdílů, které ovlivňují způsob, jakým se používají a jakým způsobem zpracovávají historii změn v kódu.

### 1. **Distribuovaný vs. Centrální:**
   - **Git:** Je distribuovaný systém pro správu verzí. Každý vývojář má kompletní repozitář na svém lokálním počítači, což umožňuje offline práci, rychlé operace a vytváření větví a slučování bez potřeby připojení k centrálnímu serveru.
   - **SVN:** Je centrální systém, což znamená, že všichni vývojáři se připojují k jednomu centrálnímu repozitáři pro stahování a odesílání změn.

### 2. **Revize:**
   - **Git:** Každý vývojář má celý repozitář na svém počítači, takže revize jsou lokální a nezávislé na připojení k serveru. Každý commit má unikátní identifikátor (SHA-1 hash).
   - **SVN:** Revize jsou přidělovány centrálně a jsou globálně identifikovány jedním číslem.

### 3. **Větvení a Slučování:**
   - **Git:** Silné podporuje větvení a slučování. Vytváření nových větví je snadné a slučování změn je efektivní a často používané.
   - **SVN:** Větvení a slučování jsou možné, ale může to být méně intuitivní a někdy obtížnější ve srovnání s Gitem.

### 4. **Rychlost:**
   - **Git:** Je obecně považován za rychlejší, zejména při operacích, které nevyžadují připojení k serveru.
   - **SVN:** Může být pomalejší, zejména při operacích, které vyžadují přístup k centrálnímu serveru.

### 5. **Offline Práce:**
   - **Git:** Umožňuje vývojářům pracovat offline a později odeslat své změny na server.
   - **SVN:** Vyžaduje připojení k serveru pro většinu operací.

### 6. **Správa Adresářové Struktury:**
   - **Git:** Nijak neomezuje strukturu adresářů. Máte jednoho hlavního správce, který má celou historii.
   - **SVN:** Má pevnější strukturu adresářů a podporuje standardní adresářovou strukturu.

### 7. **Historie Smazaných Souborů:**
   - **Git:** Uchovává historii smazaných souborů.
   - **SVN:** Historie smazaných souborů se ukládá pouze v případě, že byl soubor smazán ve stejné revizi, ve které byl také přidán.

### 8. **Práce se Vzdálenými Větvemi:**
   - **Git:** Vzdálené větve jsou snadno přístupné a manipulovatelné.
   - **SVN:** Vzdálené větve mohou vyžadovat specifické operace.

Oba systémy mají své výhody a nevýhody a volba mezi nimi závisí na potřebách projektu a preferencích týmu. Git je v současné době mnohem populárnější, zejména kvůli jeho distribuované povaze a široké podpoře vývojářské komunity.

# Síťové a webové technologie + databázové systémy
Síťové webové technologie se zabývají vývojem a provozem aplikací a služeb na internetu. Zahrnují širokou škálu nástrojů, protokolů, jazyků a frameworků, které umožňují komunikaci a interakci mezi klienty a servery přes síť. Níže jsou uvedeny některé klíčové složky síťových webových technologií:

### 1. **Protokoly:**
   - **HTTP/HTTPS (Hypertext Transfer Protocol/Secure):** Protokol pro přenos hypertextových dat mezi webovým prohlížečem a webovým serverem. HTTPS je zabezpečená verze HTTP, která využívá šifrování.

   - **WebSocket:** Protokol umožňující dvoucestnou komunikaci mezi klientem a serverem přes jedno TCP spojení. Je vhodný pro aplikace s reálným časem.

   - **FTP (File Transfer Protocol):** Protokol pro přenos souborů mezi klientem a serverem.

### 2. **Jazyky pro Klienta:**
   - **HTML (Hypertext Markup Language):** Značkovací jazyk používaný pro strukturování obsahu webových stránek.

   - **CSS (Cascading Style Sheets):** Jazyk pro popis vizuálního vzhledu HTML dokumentů.

   - **JavaScript:** Skriptovací jazyk, který umožňuje interaktivitu na straně klienta. Populární frameworky jsou např. React.

### 3. **Jazyky pro Server:**
   - **PHP:** Serverový skriptovací jazyk často používaný pro vytváření dynamických webových stránek - hodně zastaralé.

   - **Node.js:** JavaScriptový framework na straně serveru, který umožňuje asynchronní I/O a tvorbu škálovatelných webových aplikací.

### 4. **Databázové Technologie:**
   - **MySQL, PostgreSQL, Oracle:** Relační databázové systémy často používané pro ukládání dat webových aplikací.

   - **MongoDB:** NoSQL databázové systémy vhodné pro ukládání nestrukturovaných nebo polostrukturovaných dat.

### 5. **Frameworky:**
   - **Express.js:** Minimální a flexibilní Node.js framework pro tvorbu webových a mobilních aplikací.

   - **Django:** Pythonový framework, který usnadňuje rychlý vývoj robustních webových aplikací.

### 6. **API (Application Programming Interface):**
   - **REST (Representational State Transfer):** Architektonický styl pro návrh webových služeb, který využívá standardní HTTP protokol.

   - **GraphQL:** Dotazovací jazyk pro API, který umožňuje klientům specifikovat, jaká data potřebují.

### 7. **Webové Servery:**
   - **Apache:** Open-source webový server, často v kombinaci s PHP.

### 8. **Cloudové Služby:**
   - **AWS, Azure:** Poskytují škálovatelnou infrastrukturu a různé služby pro vývoj webových aplikací v cloudu.

Tyto technologie a nástroje společně umožňují vývojářům vytvářet moderní a výkonné webové aplikace a služby. Je důležité sledovat aktuální trendy a novinky v této oblasti, protože se technologie neustále vyvíjejí.