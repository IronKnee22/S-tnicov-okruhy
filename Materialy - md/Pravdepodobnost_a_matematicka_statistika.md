Zde je český překlad úryvku z dokumentu "Pravděpodobnost a matematická statistika":

---

**Náhodná veličina:** je veličina, jejíž hodnota závisí na výsledku náhodného jevu. Existují dva hlavní typy náhodných proměnných:
- **Diskrétní náhodná veličina:** nabývá pouze určitých hodnot. Příkladem je hod kostkou, kde výsledkem může být jedno z čísel 1 až 6. Diskrétní proměnné jsou často spojeny s čísly nebo kategoriemi.
- **Spojitá náhodná veličina:** může nabývat jakékoliv hodnoty v rámci určitého intervalu. Například výška nebo hmotnost člověka může být jakékoliv reálné číslo v rámci určitého intervalu. Spojité veličiny jsou často spojeny s měřeními.

**Distribuční funkce:** určuje pravděpodobnost, že náhodná proměnná bude mít hodnotu menší nebo rovnou určité hodnotě. Je to kumulativní funkce, která roste s rostoucí hodnotou náhodné proměnné a poskytuje úplný obraz o rozdělení pravděpodobnosti.

**Pravděpodobnostní funkce:** je specifická pro diskrétní náhodné proměnné a určuje pravděpodobnost, že proměnná nabude určité hodnoty. Například pravděpodobnost, že hod kostkou přinese výsledek 3, je 1/6.

**Hustota pravděpodobnosti:** je specifická pro spojité náhodné proměnné a určuje hustotu pravděpodobnosti v konkrétním bodě. Hustota pravděpodobnosti je užitečná pro zjištění pravděpodobnosti, že hodnota spadá do určitého intervalu.

**Kvartily:** jsou hodnoty, které rozdělují soubor údajů na určité části. Například:
- **Medián:** hodnota, která rozděluje soubor údajů na dvě stejné části.
- **Kvartily:** hodnoty, které rozdělují soubor údajů na čtvrtiny (Q1, Q2, Q3).
- **Percentily:** hodnoty, které dělí soubor údajů na 100 stejných částí (např. 25. percentil, 75. percentil).

**Střední hodnota (průměr):** je průměr všech hodnot v souboru a představuje centrální hodnotu údajů. Vypočítá se jako součet všech hodnot dělený jejich počtem. Střední hodnota je užitečná pro pochopení průměrného chování údajů.

**Rozptyl (odchylka):** Rozptyl měří, jak jsou hodnoty rozptýleny kolem střední hodnoty. Vyšší rozptyl znamená, že hodnoty jsou více rozptýlené, zatímco nižší rozptyl znamená, že hodnoty jsou blíže k průměru. Rozptyl se často používá ve statistice k hodnocení variability údajů.

**Bodové a intervalové odhady:**
- **Bodový odhad:** je konkrétní číslo, které se používá jako nejlepší odhad parametru populace na základě vzorku. Například průměr vzorku (výběrový průměr) je bodový odhad populačního průměru.
- **Intervalový odhad:** poskytuje rozsah hodnot, který obsahuje skutečnou hodnotu populačního parametru s určitou pravděpodobností. Tento interval se nazývá interval spolehlivosti. Intervalové odhady poskytují více informací než bodové odhady, protože zahrnují nejistotu odhadu.

**Obecné principy testování statistických hypotéz:** Testování statistických hypotéz je metoda rozhodování o údajích na základě pravděpodobnosti. Zahrnuje následující kroky:
1. Formulace hypotézy:
   - **Nulová hypotéza (H0):** předpoklad, že neexistuje žádný účinek nebo rozdíl mezi pozorovanými jevy.
   - **Alternativní hypotéza (H1):** předpoklad, že mezi pozorovanými jevy existuje účinek nebo rozdíl.
2. Výběr testovacího kritéria: Určení vhodného statistického testu (např. t-test, z-test) na testování hypotézy.
3. Určení hladiny významnosti (α): obvykle 0,05 nebo 5 %, což znamená, že existuje 5 % pravděpodobnost, že zamítnutí H0 je nesprávné.
4. Výpočet testové statistiky a p-hodnoty: p-hodnota určuje pravděpodobnost, že pozorované výsledky by nastaly, pokud by H0 byla pravdivá. Pokud je p-hodnota menší než α, H0 se zamítá.
5. Rozhodnutí: Na základě p-hodnoty a hladiny významnosti se rozhodneme, zda H0 zamítneme nebo ne.

**Testy parametrů normálního rozdělení:** Testy parametrů normálního rozdělení se používají na testování hypotéz o parametrech (např. středních hodnotách) normálně rozdělené populace:
- **Z-test:** Používá se při velkých vzorcích nebo když je známa směrodatná odchylka populace. Pomáhá zjistit, zda se průměr vzorku významně liší od předpokládaného průměru.
- **T-test:** Používá se při malých vzorcích nebo když není známa směrodatná odchylka populace. Existují různé typy T-testů:
  - **Jednovýběrový t-test:** Porovnává průměr jedné vzorky s hypotetickou hodnotou.
  - **Dvojvýběrový t-test:** Porovnává průměry dvou nezávislých vzorků.
  - **Párový t-test:** Porovnává průměry dvou závislých vzorků (např. měření před a po intervenci na týchž subjektech).

**Chi-kvadrát test dobré shody:** Chí-kvadrát test dobré shody se používá na testování, zda se pozorovaná frekvence kategorických údajů shoduje s očekávanou frekvencí. Postup:
1. Formulace hypotéz:
   - **H0:** Pozorovaná data odpovídají očekávanému rozdělení.
   - **H1:** Pozorovaná data neodpovídají očekávanému rozdělení.
2. Výpočet testovací statistiky: Testovací statistika porovnává pozorované a očekávané frekvence.
3. Porovnání s kritickou hodnotou: Pokud je testovací statistika větší než kritická hodnota z chi-kvadrát rozdělení pro danou hladinu významnosti, H0 se zamítá.

**Variabilita a normálnost dat:**
- **Variabilita:** Variabilita měří rozptyl hodnot v souboru údajů. Základní ukazatele variability jsou:
  - **Rozptyl:** Ukazuje střední kvadratickou odchylku hodnot od průměru.
  - **Štandardní odchylka:** odmocnina z rozptylu poskytuje míru průměrné odchylky od průměru.
  - **Medzikvartilové rozpětí (IQR):** Rozdíl mezi 75. a 25. percentilem ukazuje šířku středních 50 % údajů.
- **Normálnost dat:** Normálnost údajů se testuje pomocí statistických testů a grafických metod:
  - **Statistické testy:**
    - **Shapiro-Wilk test:** testuje, zda údaje pocházejí z normálního rozdělení.
    - **Kolmogorov-Smirnov test:** porovnává distribuční funkci vzorku s očekávanou normální distribuční funkcí.
  - **Grafické metody:**
    - **Q-Q graf:** graf porovnávající kvantily údajů s kvantily normálního rozdělení.
    - **Histogram:** Graf frekvencí, který může vizuálně naznačit, zda jsou údaje normální.

**Typy experimentálních studií:**
- **Randomizované kontrolované studie** se považují za zlatý standard v klinickém výzkumu. Účastníci jsou náhodně přiřazeni do experimentální nebo kontrolní skupiny, což minimalizuje zkreslení a zaručuje, že jakékoliv rozdíly ve výsledcích lze připsat test

ované intervenci.
- **V křížových studiích** dostává každý účastník dvě léčby (experimentální a kontrolní) v různém čase, což umožňuje přímé porovnání účinků v rámci téhož subjektu. Tento plán snižuje vliv variability mezi subjekty.

**Typy pozorovacích studií:**
- **Kohortové studie** sledují skupinu lidí (kohortu) během určitého časového období s cílem zjistit, jaké faktory mohou ovlivnit výskyt nemoci nebo jiných zdravotních následků. Kohortové studie mohou být:
  - **Prospektivní:** sbírají údaje do budoucna od počátečního bodu.
  - **Retrospektivní:** analýza existujících údajů.
- **Případové studie:** se porovnávají lidé s určitým onemocněním (případy) s lidmi bez onemocnění (kontroly) s cílem identifikovat rizikové faktory spojené s onemocněním. Tyto studie jsou užitečné při zřídka se vyskytujících onemocněních a jsou rychlejší a levnější než kohortové studie.

**Medicína založená na důkazech (EBM):** spojuje nejlepší dostupné vědecké důkazy s klinickými odbornými znalostmi a hodnotami pro pacienta. Proces EBM zahrnuje:
1. **Formulování klinické otázky:** použití metody PICO (Patient, Intervention, Comparison, Outcome) na vytvoření jasné a specifické otázky.
2. **Vyhledávání důkazů:** použití databází jako jsou PubMed, Cochrane Library na vyhledání relevantních studií.
3. **Hodnocení důkazů:** kritické posouzení kvality a relevance studií, často pomocí nástrojů jako je GRADE (Grading of Recommendations, Assessment, Development and Evaluation).
4. **Aplikace důkazů:** integrace důkazů do klinické praxe s přihlédnutím k individuálním podmínkám pacienta.
5. **Hodnocení výsledků:** Průběžné hodnocení účinnosti a bezpečnosti zavedených postupů a úprava léčby na základě výsledků.

