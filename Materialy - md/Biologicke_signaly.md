### Vlastnosti biologických signálů:

Biologické signály jsou měřitelné fyziologické projevy živých organismů, které mohou mít elektrický, mechanický nebo chemický charakter. Mezi hlavní charakteristiky těchto signálů patří:

- **Amplituda**: maximální hodnota signálu
- **Frekvence**: počet cyklů signálu za sekundu (Hz)
- **Čas trvání**: trvání každé události v signálu
- **Dynamika**: změny signálu v průběhu času
- **Periodicita**: pravidelnost, s jakou se signál opakuje

### Metody vzniku, snímání a základní parametry biosignálů potřebné pro diagnostiku:

Biosignály vznikají jako výsledek fyziologických procesů a jejich snímání je klíčové pro diagnostiku zdravotních stavů.

#### Způsoby vzniku biosignálů

- **Elektrofysiologické**: Elektrická aktivita buněk, například akční potenciály neuronů nebo svalových buněk.
- **Mechanické**: Mechanické pohyby, například zvuky srdce nebo pohyby svalů.
- **Chemické**: Změny v koncentracích iontů a metabolitů.

#### Snímání biosignálů

- **Elektrody**: povrchové, jehlové nebo intramuskulární elektrody.
- **Senzory**: piezoelektrické, optické nebo chemické senzory.
- **Zobrazovací techniky**: MRI, CT, ultrazvuk.

#### Základní parametry

- **Amplituda**: měří sílu signálu.
- **Frekvence**: hodnotí frekvenci opakování cyklů.
- **Latence**: časové zpoždění mezi událostí a reakcí.
- **Rychlost vedení**: rychlost šíření signálu v nervovém nebo svalovém vlákně.

### Signály srdce (EKG):

Elektrická aktivita srdce vzniká depolarizací a repolarizací srdečních buněk. Sinoatriální (SA) uzel, hlavní kardiostimulátor srdce, generuje impulsy s frekvencí 60-100 úderů za minutu. Tyto impulsy se šíří přes předsíňový myokard, atrioventrikulární (AV) uzel a Hisův svazek do komorového myokardu a způsobují kontrakci srdce.

Snímání elektrické aktivity srdce se provádí pomocí elektrokardiografie (EKG), která zaznamenává elektrickou aktivitu srdce pomocí elektrod umístěných na povrchu těla. Standardní 12-svodové EKG poskytuje komplexní informace o činnosti srdce z různých úhlů pohledu. Základní parametry EKG jsou:

- **Vlna P**: depolarizace předsíní
- **QRS komplex**: depolarizace komor
- **Vlna T**: repolarizace komor
- **Srdeční frekvence**: počet úderů za minutu.
- **Intervaly a segmenty**: PR interval, QT interval, ST segment.

### Signály mozku (EEG):

Elektrická aktivita mozku je generována synaptickou aktivitou neuronů. Tato aktivita vytváří elektrické potenciály, které se šíří mozkovou kůrou a vytvářejí měřitelné elektrické vlny. Elektroencefalografie (EEG) zaznamenává tuto elektrickou aktivitu pomocí elektrod umístěných na povrchu pokožky hlavy. Používají se standardní sestavy elektrod jako například systém 10-20. Základní parametry EEG jsou:

#### Frekvenční pásma

- **Delta (0,5-4 Hz)**: hluboký spánek
- **Theta (4-8 Hz)**: lehký spánek a relaxace
- **Alfa (8-13 Hz)**: stav uvolnění
- **Beta (13-30 Hz)**: aktivní myšlení
- **Gama (> 30 Hz)**: vysoká kognitivní aktivita

- **Amplituda**: výška elektrických vln měřená v mikrovoltech.
- **Synchronizace**: současná aktivita neuronů.

### Signály svalů (EMG):

Během svalové kontrakce dochází k elektrické aktivitě svalů. Nervový impuls způsobí uvolnění neurotransmiterů, které spustí depolarizaci svalových vláken a následnou kontrakci. Elektromyografie (EMG) zaznamenává tuto elektrickou aktivitu pomocí povrchových nebo intramuskulárních elektrod. Základní parametry EMG jsou:

- **Motorická jednotka**: skupina svalových vláken inervovaných jedním motorickým neuronem
- **Amplituda**: síla svalové aktivity
- **Frekvence**: frekvence elektrických impulsů
- **Svalové potenciály**: elektrické signály produkované svalovými vlákny během kontrakce

### Signály nervového systému (ENG):

Elektrické impulzy v nervech vznikají při přenosu signálů přes nervová vlákna. Depolarizace a repolarizace nervových buněk vytváří akční potenciály, které se šíří podél nervových drah. Elektroneurografie (ENG) zaznamenává tyto elektrické impulzy v periferních nervech pomocí povrchových elektrod. Základní parametry ENG jsou:

- **Rychlost vedení**: rychlost, jakou se elektrický impuls šíří nervem
- **Amplituda akčního potenciálu**: velikost elektrického signálu
- **Latence**: časové zpoždění mezi stimulací nervu a odpovědí
- **Refrakterní období**: čas, během kterého nervové vlákno nereaguje na další stimulaci

### Metody a algoritmy na zpracování a vyhodnocování nejdůležitějších elektrofysiologických signálů:

Předzpracování signálu zahrnuje odstranění artefaktů a šumu, které mohou ovlivnit přesnost analýzy. Na odstranění nežádoucích frekvencí se používá dolnopropustná, hornopropustná a pásmová filtrace. Korekce artefaktů jako například analýza nezávislých komponent (ICA) pomáhá odstranit artefakty způsobené pohybem, mrkáním nebo svalovou aktivitou.

Analýza signálu se může provádět v časové nebo frekvenční oblasti. V časové oblasti se na vyhodnocení signálů používají statistické metody na výpočet průměru, standardní odchylky a RMS (Root Mean Square). Identifikace a detekce událostí zahrnuje detekci vrcholů vln a jiných významných událostí v signálech. Ve frekvenční oblasti se Fourierova transformace používá na převod signálů z časové oblasti do frekvenční oblasti a na analýzu spektrálních složek. Spektrální analýza identifikuje dominantní frekvence a vyhodnocuje frekvenční obsah signálů.

### Nestacionarita EEG:

Signály EEG jsou nestacionární, což znamená, že jejich statistické vlastnosti se v čase mění. Analýza nestacionárních signálů vyžaduje pokročilé metody jako například vlnková transformace, která poskytuje časově-frekvenční rozlišení a umožňuje analýzu přechodných jevů. Krátkodobá Fourierova transformace (STFT) umožňuje analýzu frekvenčních složek signálu v krátkých časových oknech.

#### Frekvenční rozsah a pásma:

Biologické signály pokrývají různé frekvenční rozsahy, což je důležité pro jejich analýzu. Nízké frekvence (0 - 0,5 Hz) zahrnují stacionární složky a dlouhodobé trendy. Střední frekvence (0,5 - 40 Hz) zahrnují dechové a autonomní funkce. Například EKG signály mají rozsah 0,05 - 100 Hz, přičemž klinicky relevantní analýza se zaměřuje na pásmo 0,5 - 40 Hz. Vysoké frekvence (40 Hz - několik kHz) zahrnují svalovou aktivitu, například EMG signály se obvykle pohybují v rozsahu 5 - 500 Hz, přičemž vysoké frekvence dosahují až 1 000 Hz.

### Základní řetězec konverze do počítače:

Analogové biosignály se musí převést do

 digitální formy na počítačové zpracování. Tento převod zahrnuje použití A/D převodníku. Vzorkovací frekvence musí být dostatečně vysoká, aby zachytila všechny relevantní informace signálu, což je definováno Nyquistovým teorémem. Rozlišení A/D převodníku určuje počet bitů použitých na kvantování signálu, což ovlivňuje přesnost. Problémy vzorkování a kvantizace signálu zahrnují Nyquistův teorém, který vyžaduje, aby vzorkovací frekvence byla alespoň dvojnásobkem maximální frekvence signálu, aby se zabránilo aliasingu. Aliasing způsobuje zkreslení signálu při nedostatečné vzorkovací frekvenci. Kvantizační chyba je rozdíl mezi skutečnou a kvantovanou hodnotou signálu a je ovlivněna rozlišením A/D převodníku.

### Spektrální analýza biosignálů:

Spektrální analýza umožňuje analyzovat frekvenční obsah signálů a identifikovat jejich spektrální složky. Mezi základní metody spektrální analýzy patří parametrické metody, které modelují signál pomocí parametrů jako například AR (AutoRegressive) modely a neparametrické metody, které nepředpokládají specifický model signálu jako například Fourierova transformace. Periodogram odhaduje výkonové spektrum signálu a zobrazuje frekvenční obsah signálu. Mezi praktické problémy odhadu spektra patří omezená délka vzorky a spektrální únik.

Krížové spektrum analyzuje vztah mezi dvěma signály ve frekvenční oblasti, koherence měří stupeň synchronizace mezi dvěma signály v každém frekvenčním pásmu a fáze poskytuje informace o časovém zpoždění mezi signály. Rychlá Fourierova transformace (FFT) je efektivní algoritmus na výpočet diskrétní Fourierovy transformace (DFT), který snižuje počet potřebných operací z O(N^2) na O(N log N) a umožňuje rychlou spektrální analýzu signálů.

### Filtrácia a odstranění šumu:

Digitální filtrace zahrnuje použití filtrů FIR (Finite Impulse Response) a IIR (Infinite Impulse Response) na odstranění nežádoucích frekvencí a šumu. Techniky odstraňování šumu jako je adaptivní filtrace a vlnková denoizace pomáhají odstranit šum bez ztráty důležitých informací.

### Vizualizace výsledků analýzy:

Vizualizace výsledků analýzy usnadňuje interpretaci a prezentaci spektrální analýzy. Spektrogramy zobrazují frekvenční obsah signálu v čase a poskytují časově-frekvenční rozlišení. Topografické mapování vizualizuje prostorové rozložení signálů na povrchu mozku a zobrazuje amplitudy a frekvence.

### Metoda kondenzovaného spektrálního pole (CSA):

Metoda CSA zobrazuje spektrální změny výkonu v časově-frekvenčním prostoru, což je užitečné na analýzu nestacionárních signálů. Poskytuje podrobné časově-frekvenční rozlišení a zobrazuje dynamiku signálů.

### Topografické mapování elektrofyziologické aktivity:

Principem mapování mozku je vizualizace mozkové aktivity pomocí barevného kódování číselných hodnot. Používá se na zobrazení amplitud, frekvencí a jiných parametrů mozkové aktivity. Na jemnější zobrazení hodnot mezi body měření se používá interpolace, přičemž splajnová interpolace poskytuje hladší výsledky a přesnější mapování. Mapování amplitud a frekvencí zobrazuje prostorové rozložení těchto parametrů na povrchu mozku, což pomáhá identifikovat oblasti abnormální aktivity a podporuje diagnostiku a terapii neurologických onemocnění.