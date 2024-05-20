# Modelování a simulace

## Spojité modely
Spojité modely představují systémy, kde se stav systému mění plynule v čase, k popisu se využívají diferenciální rovnice

**Příklady** Elektrické obvody - napětí a proud v obvodech  
**Výhody** Schopnost přesně popsat fyzikální a inženýrské procesy  
**Nevýhody** Složité a výpočetně náročné najít analytická řešení  

## Diskrétní modely
Diskrétní modely představují systémy, kde se stav systému mění v disktrétních časových okamžicích, používají disktréní události k popisu změn stavu systému

**Příklady** Simulace dopravy: pohyb vozidel v křižovatkách  
**Výhody** Vhodné pro systémy, kde změny nastávají v jasně definovaných okamžicích  
**Nevýhody** Může být obtížné modelovat systémy, které jsou přirozeně spojité

## Pozorování 
POzorování zahrnuje sledování a zazamenávání chování systému v jeho přirozeneém prostředí bez zásahů

**Příklady** Ekologické studie sleducjící chování zvířat  ve volné přírodě

## Experiment
Experiment zahrnuje aktivní manipulaci s jednou nebo více proměnnými a sledování výsledků těchto změn

**Příklady** Laboratorní studie testující účinnost nového léku

## Metodika vytváření modelu, způsovy popisu modelů.
Metodika vytvíření modelu jestrukturovanžý proces, který zahrnuje definici problému, formulaci konceptuálního medeum matematickou formulaci, implemaentaci, validaci

Způsoby popisu modelů se liší podle účrelu a typu modelu a zahrnují matematické, grafické, simulační a symbolické dynamické popisy.

## Komparmentové modely a příklady jejich využítí
Kompartmentové modely jsou specifickým typem matematických modelů pouužívaných k popisu dynamiky systému rozdělených do diskrétních částí (kompartmentů)

Přenosy mezi kompartmenty představují toksledované veličiny mezi kompartmenty

Model může rozvěž může obsahovat vnější příjem (injekce) a výstupy (vylučování)

**Příklady** 
- Epidemiologie: nakažení zdravý
- Farmakokinetika: popis distribuce léku v těle
- ekologie: modelace populací

## Spojité a diskrétní modely jednodruhových populací
**Spojité** populace které se množí neustále (mouchy)
**Diskrétní** populace s diskrétními časovými kroky (roční generace)

## Malhusův model vs logistický model
**Malhusův model** Populace roste exponenciálně bez omezení  
**logistický model** upravuje Malthusův model tak aby zodhledňoval omezené zdroje

## Modely kooperace a kompetice
**Kooperace** - spolupráce mezi jedinci, která vede k růstu populace
**Kompetice** - populace roste pomaleji kvůli soutěži o zdroje

## Modely dvoudruhových populací
**Model konkurence** dva různé druhy spolu soutěží o jednu potravu

### Model Lotky-Volterry (dravec - kořist)
Je založen na soustavaě svou nelineárních diferenciálních rovnic, které popisují změny veliksti populací dravců a jejich kořisti v čase.

Populace funguje na pricipu: hodně kořisti -> zvětší se počet dravců -> změnší se počet kořisti -> změnší se počet dravců -> zvětší se počet kořisti

## Epidemiologické modely

### Model SIR (Kermackův - McKendrikův model)
**S (susceptible)** náchylní jedinci  
**I (infected)** infikování jedinci  
**R (recovered)** zotavení jedinci kteří získaly imunitu

### Model SI
Jedinci po infikování zůstanou navždy infikování

### Model SIS
Jedinci po infikování získají imunitu, ale po určité době se stávají opět náchylní

### Model SIR s přenašeci
Obsahuje skupinu přenašeču, kteří nemoc šíří, ale sami nejsou infikováni

### Model SIR s vakcinací
Tento model přidává účinek vakcinace, která přesouvá jedince přímo do skupiny uzdravených

## Modely farmakokinetiky, dávkování léčiv
Farmakokonetické modely jsou zásadní pro pochopení, jak tělo zpracovává léčiva, a pro navrhování optimálníc dávkovacích schémat.   
Kompartmentové modely, jako jsou jednokompartmentové a dvoukompartmentové modely, poskytují rámec pro popis distribuce a eliminace léčiv.


