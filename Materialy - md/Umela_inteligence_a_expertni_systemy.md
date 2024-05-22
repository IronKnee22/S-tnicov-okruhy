### Umělá inteligence a expertní systémy

#### Stav a stavový prostor:
- **Stav:** Reprezentace situace nebo konfigurace systému v daném čase. Každý stav může být definován souborem hodnot proměnných, které popisují systém.
- **Stavový prostor:** Množina všech možných stavů, které může systém zaujmout. Problémy řešení problémů si lze často představit jako hledání cesty ve stavovém prostoru z počátečního stavu do cílového stavu.

#### Prohledávání stavového prostoru:
- **Informované metody:**
  - **Gradientní algoritmy:** Používají se k optimalizaci funkcí. Základní myšlenkou je vypočítat gradient (směr maximálního růstu funkce) a pohybovat se ve směru tohoto gradientu.
  - **Metoda větví a hranic:** Kombinuje prvky systematického hledání s heuristikou. Rozděluje problém na menší části (větve) a na omezení hledání používá horní a dolní hranice.
  - **A\*:** Heuristický algoritmus pro hledání optimální cesty ve stavovém prostoru. Používá rankingovou funkci f(n) = g(n) + h(n), kde g(n) jsou náklady na cestu z počátečního stavu do stavu n a h(n) jsou odhadované náklady z n do cílového stavu.

- **Neinformované metody:**
  - **Vyhledávání do hloubky (DFS):** Algoritmus před návratem prohledává každou větev co nejdále. Výhodou je nízká spotřeba paměti, nevýhodou může být zablokování v nekonečných větvích.
  - **Vyhledávání do šířky (BFS):** Algoritmus prohledává všechny sousední uzly na aktuální úrovni před přechodem na další úroveň. Zaručuje nalezení nejkratší cesty, ale je náročnější na paměť.

#### Strojové učení:
- **Příznakové metody:** Pracují s číselnými hodnotami nebo kategoriemi získanými z údajů. Například regresní analýza nebo klasifikace.
- **Strukturální metody:** Pracují s údaji, které mají vnitřní strukturu, například text nebo grafy.

- **Regrese:** Používá se pro předpovídání číselných hodnot. Například lineární regrese předpokládá lineární vztah mezi vstupy a výstupy.
- **Klasifikace:**
  - **k-NN (k nejbližších sousedů):** Klasifikátor, který neznámý objekt přiřadí k třídě na základě většiny tříd jeho k nejbližších sousedů.
  - **Rozhodovací stromy:** Stromová struktura, kde každý uzel představuje test na atribut a každá větev představuje výsledek testu. Listy představují třídy.
  - **Bayesovský klasifikátor:** Naivní Bayesovský klasifikátor předpokládá nezávislost mezi atributy a používá Bayesovu teorii k výpočtu pravděpodobnosti, že objekt patří do určité třídy.

- **Učení bez učitele:**
  - **Zhlukování:** Seskupení datových bodů do zhluků tak, aby body ve stejném zhluku byly podobné a body v různých zhlukách byly odlišné. Příkladem je algoritmus k-means.

#### Neuronové sítě:
- Jsou modely inspirované fungováním biologického mozku a sestávají z vzájemně propojených jednotek nazývaných neurony. Tyto sítě se používají pro různé úlohy strojového učení, jako je klasifikace, regrese a rozpoznávání vzorů.

- **Matematický model neuronu:**
  - **Vstupy (x1, x2, ...):** Každý neuron přijímá několik vstupů, které mohou být vážené.
  - **Váhy (w1, w2, ...):** Každý vstup se násobí vahou, která určuje důležitost daného vstupu.
  - **Aktivační funkce (f):** Funkce, která transformuje součet vážených vstupů na výstup neuronu. Mezi běžné aktivační funkce patří:
    - **Sigmoid:** f(x) = 1 / (1 + e^(-x))
    - **ReLU (Rectified Linear Unit):** f(x) = max(0, x)
  - **Výstup (y):** Výstup neuronu je výsledkem aktivační funkce aplikované na vážený součet vstupů.

  - Matematický model neuronu lze vyjádřit takto: y=f(∑(wi * xi) + b), kde b je bias (skreslení), které umožňuje modelu lépe se přizpůsobit údajům.

- **Viacvrstvová perceptronová síť (MLP):** Sestává z vrstvy vstupních neuronů, jedné nebo více skrytých vrstev neuronů a vrstvy výstupních neuronů. Každý neuron v jedné vrstvě je propojen se všemi neurony v následující vrstvě. MLP se trénují pomocí algoritmu zpětného šíření.

#### Expertní systémy:
- Jsou počítačové programy, které využívají znalosti a postupy odvozování k řešení složitých problémů, které by za normálních okolností vyžadovaly lidské odborné znalosti. Jsou navrženy tak, aby napodobovaly rozhodovací schopnosti lidských expertů v určité oblasti.

- **Složky ES:**
  - **Báze znalostí**
  - **Báze pravidel**
  - **Inferenční mechanismus**
  - **Báze dat**
  - **Vysvětlovací modul**
  - **Komunikační modul**

- **Báze znalostí:** Centrální část expertního systému, která obsahuje všechny odborné znalosti potřebné k řešení problémů. Zahrnuje:
  - **Fakta:** Objektivní informace, které se považují za pravdivé. Například: „Pacient má teplotu 38 °C“.
  - **Pravidla:** Logické podmínky a činnosti, které popisují způsob řešení problémů na základě faktů. Příklad pravidla IF-THEN: „Pokud má pacient teplotu vyšší než 37,5 °C, pak má pacient horečku“.
  - **Heuristika:** Znalosti založené na zkušenostech nebo intuici experta, které pomáhají při rozhodování v případech, kdy nejsou k dispozici přesné informace.

- **Báze pravidel:** Specifická část báze znalostí, která sestává z pravidel, jimiž se řídí chování expertního systému. Pravidla jsou vyjádřena ve formě IF-THEN:
  - **IF (podmínka):** Popisuje situaci nebo podmínku, která musí být splněna.
  - **THEN (akce):** Určuje akci nebo rozhodnutí, které se má přijmout, pokud je podmínka splněna.

  - **Typy pravidel:**
    - **Produkční pravidla:** Standardní pravidla IF-THEN.
    - **Heuristická pravidla:** Pravidla založená na zkušenosti nebo intuici, která nemusí být vždy přesná.

- **Inferenční mechanismus:** Logický procesor, který využívá bázi znalostí k odvození nových znalostí nebo rozhodnutí. Funguje jako „mozek“ expertního systému, který analyzuje fakta a pravidla, aby dospěl k závěru.
  - **Vyhledávání pravidel:** Identifikuje relevantní pravidla v bázi znalostí na základě skutečných faktů.
  - **Aplikace pravidel:** Používání pravidel k vyvození závěrů nebo opatření.
  - **Řešení konfliktů:** Řeší situace, ve kterých se může současně uplatnit více pravidel.

  - **Typy:**
    - **Postupné řetězení:** Postupuje od známých faktů k novým závěrům (na základě údajů).
    - **Zpětné řetězení:** Začíná s cílem a postupuje dozadu s cílem najít fakta, která tento cíl podporují (řízené cílem).

- **Tvorba expertního systému (ES):** Složitý proces, který zahrnuje několik klíčových kroků a fází. Cílem je

 vytvořit systém, který dokáže napodobit rozhodovací schopnosti lidského experta v určité oblasti. Zahrnuje několik klíčových kroků:
  - **Analýza problému:** Vymezení oblasti, ve které se bude ES používat a identifikace problémů, které má řešit. Určení cílů a požadavků systému.
  - **Specifikace systému:** Určení funkcí, návrh architektury systému (báze znalostí, inferenční mechanismus, vysvětlovací modul, komunikační modul) a určení technických požadavků.
  - **Extrakce znalostí expertů:** Proces získávání znalostí od lidských expertů pomocí různých technik.
  - **Vývoj báze znalostí:** Převod získaných znalostí do formátu, který lze uložit do báze znalostí, jako jsou pravidla IF-THEN. Štrukturování a ověřování znalostí.
  - **Implementace:** Kódování pravidel a logiky, integrace všech komponentů systému a vývoj uživatelského rozhraní.
  - **Testování a ladění:** Provádění testů s reálnými údaji, ladění systému na základě zpětné vazby a opakované zlepšování.
  - **Údržba a aktualizace:** Průběžná aktualizace databáze znalostí a systému podle nových informací a zkušeností.

#### Získávání znalostí od experta:
- **Získávání znalostí:** Klíčová fáze vývoje ES. Kvalita systému závisí na kvalitě a úplnosti získaných znalostí. Tento proces může zahrnovat:
  - **Verbální techniky:**
    - **Rozhovory:** Strukturované nebo nestrukturované rozhovory s experty s cílem získat jejich znalosti.
    - **Introspekce:** Expert popisuje své myšlenkové postupy při řešení problémů.
  - **Neverbální techniky:**
    - **Pozorování:** Pozorování odborníků při práci a zaznamenávání jejich rozhodovacích procesů.
    - **Simulace:** Vytváření simulovaných situací a analýza rozhodování expertů.

  - **Techniky založené na štrukturovaných metodách:**
    - **Třídění karet:** Expert třídí karty s pojmy nebo znaky do skupin a vysvětluje jejich uspořádání.
    - **Repertory Grid:** Tabulka, ve které expert přiřazuje objektům hodnoty konstrukcí, což pomáhá identifikovat důležité vztahy a pravidla.
    - **Matrix Analysis:** Dvojrozměrná tabulka, kde jsou objekty v jedné dimenzi a jejich vlastnosti ve druhé dimenzi a expert určuje přítomnost nebo nepřítomnost vlastností.