# Asistivní technologie a robotika v lékařství

## Kinematika

### Kinematická dvojce
Jedná se o základní stavební jednotku mechanického systému, která představuje dvě tělesa spojená tak, že mezi nimi může docházet k relativnímu pohybu.  

**Rotační dvojce** Umožnuje rozaci jednotho tělasa vůči druhému (kloub)
**Translační dvojce** Umožnuje lineární pohyb jednoho tělesa vůci druhému (pojezdy)

### Kinematický řetězec
Jedná se o systém spojených kinematických dvojic

**Otevřený kinematický řetězec** konce nejsou spojeny (lidská ruka)  
**Zavřený kinematický řetězec** Konce jsou spojeny (nůžkový zvedák)

### Stupně volnosti
Stupně volnosti označují počet nezávislých pohybů, které může mechanický systém vykonávat.

### Strukturní a kinematické schéma
**Strukturní schéma** ukazuje jak jsou jednotlivé komponenty machanického systému spojeny (ukazuje strukturu)  
**Kinematické schéma** obsahuje informace o typech kinematických dvojic a stupních volnosti 

### Kinematika robotů v homogenní souřadné soustavě
Kinematika robotů se zabývá pohybem roborů bez ohledu na síly působící na ně. V homogenní souřadné soustavě se využívají matice, které umožňují jednodušejí provádět operace jako tranformace polohy a orientace

**Homogenní transformační matice 4*4** reprezentuje rozaci a translaci v 3D prostoru. Umožnuje snadné skládání více transformací

### Homogenní trandformace a transformační matice
Homogenní tranfoemace  je metoda, která umožňuje popisovat polohu a orientaci objektů v prostoru pomocí matice

**Homogenní transformační matice 4*4** reprezentuje rozaci a translaci v 3D prostoru. Umožnuje snadné skládání více transformací

**Charakteristická matice základní pohybů** Základní pohyby v prostoru zahnují rotace kolem os x,y,z a translace podel těchto os.

**Poloha bodu** v prostoru je reprezentován pomocí homogenního vektoru (ten umožnuje reprezentovat vody v projektivním prostoru pomocí homogenních souřadnic)

#### Matice rychlosti tělesa a rychlosti bodu
Rychlostní kynematika se zabývá rychlostmi jednotlivých bodů tělesa. To můžeme popsat pomocí jakobiánové matice, která spojuje rychlost kloubů s rychlostí koncového efektrou

**Matice zrychlení tělesa a zrychlení bodu** podobně jako rychlost můžeme i zrychlení popsat pomocí jakobiánovy rovnice pro zrychlení

### Kinematika otevřených řetězců
**Přímá kinematika** určuje polohu koncového efektru z daných kloubých parametrů

**Inverzní kinematika** Určuje potřebné kloubové parametry, aby koncový efektro dosáhl požadované polohy

### Matice inverzního pohybu
Matice inverzního pohybu se používá k vyjádření zpětné transformace, tj. když chceme získat původní souřadnice po aplikaci transformační matice

### Poloha, rychlost a zrychlení koncového bodu vůči rámu a ostatním tělesům
**Poloha** koncového bodu vůči rámu lze vypočítat pomocí transformačních matic

**Rychlost** koncového bodu je určena jakobiánovou maticí, která spojuje rychlosti kloubů s rychlostmi koncového bodu

**Zrychlení** Podobně jako zrychlení můžeme vyjádřit i zrychlení koncového bodu pomocí jakobiánovy matice a její časové derivace

### Výpočty jacobiánu a jeho využití při řešení inverzní úlohy kinematiky
**Výpočet jakobiánovy matice** skládá se ze dvou částí translační a rotační části, příspěvek do jakobiánovy rovnice závisí na typu kloubu(rotační nebo translační)

#### Inverzní úloha kinematiky
Inverzní kinematika řeší problém nalezení kloubových parametrů, které vedou k pařadované poloze a orientaci koncového efektoru

Iterativně upravujeme kloubové úhly tak, aby se minimalizovala chyba mezi aktuální a požadovanou polohou

## Dynamika

### Dynamika otevřených řetězců
Dynamika otevřených kinematických řetězců se zabývá analýzou sil a momentů působících na jednotlivé části řetězce, pro tento účel se využívají lagrangeovy rovnice 2. druhu

### Aproximace rozložení hmotnosti členů kinematickéého řetězce
Při modelování dynamiky robotických systému je důležité znát homotnostní a setrvačnostní vlastni jednotlivých částí,

### Potenciální a kinetická energie řetězce
**Potenciální energie** je energie kterou má objekt v důsledku polohy nebo konfigurace soustavy  
**Kinetická energie** vzniká v důsledku pohybu enrgie

Tyto dvě energie se navzájem střídají

### Lagrangeovy rovnice II. druhu
Lagrangeovy rovnice II. druhu poskytují způsob, jak odvodit pohybové rovnice systému ze znalosti kinetické a potenciální energie

### Výpočty matic C,D a G a sestavení rovnice dynamiky v matickové formě
**D** Matice momentů  
**C** Matice odstředivých sil  
**G** Matice gravitačních sil  

**Sestavení rovnice dynamiky v maticové formě** zkombinují se všechny členy do maticového tvaru

## Asistivní technologie

### Paradigmata silového řízení otevřených řetězců
Silové řízení je technika, která umožňuje robotům interagovat s prostředím, zejména při úkolech, kde je důležité řídit sílu nebo moment aplikovaný na objekt nebo povrch.

#### Impedační řízení
Představte si robota, který manipuluje s křehkým skleněným objekteem. Impedační řítení by umožnilo robotu "ustoupit" nebo se prohnout, pokud by narazil na něco pevného, čímž by snížil riziko rozbití skla

#### Admitanční řízení
Robot který má za úkol přimontovat víko na krabici s definovanou silou

### Ověření říení v simulačním prostředí Matlab
V simulinku
- modelování robota
- implementace řízení
- Simulace
- analýza výsledků

### Využití senzorů a aktuátorů pro konstrukci rozhraní člověk-stroj
**Senzory** snímače síly a monetu  
**Aktuátory** motory, hydraulické a pneumatické systémy

### Předzpracování a využití signálů pro úlohy řízení pohybu
**Filtrace signálu** Odstranění šumu z uživatelských vstupů pomocí fitrů  
**Normalizace signálu** Přizpůsobení rozsahu signálů pro konzistentní zpracování

### Ovládání polohovatelného lůžka a podobných věcí
**Musí obsahovat**
- uživatelské rozhraní
- bezpečnostní senzory
- řídící algoritmy

### Využití embeded systémů
Embeded systémy jsou specializované počítače určené k vykonávání specifických úkolů.

### Alternativní komunikační systémy pro hendikepované
- text to speech
- brain-computer interface
