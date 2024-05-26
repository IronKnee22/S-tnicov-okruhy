### Zpracování obrazových dat

#### Zrakový orgán
Oko je zodpovědné za zachytávání světla a přeměnu optických signálů na nervové impulzy. Mezi hlavní části oka patří rohovka, čočka, sítnice, sklivec a zrakový nerv. Světlo prochází rohovkou, láme se přes čočku a dopadá na sítnici, kde jsou fotoreceptory (tyčinky a čípky) zodpovědné za detekci světla a barev.

#### Jasová citlivost oka
Oko je citlivé na širokou škálu jasů, ale nejcitlivější je při středních úrovních osvětlení. K adaptaci na různé úrovně jasu dochází prostřednictvím změn citlivosti tyčinek a čípků na sítnici. Tyčinky jsou citlivější na slabé světlo, zatímco čípky jsou citlivější na barvy a vyšší úrovně světla.

#### Kontrastní citlivost oka
Schopnost oka rozlišovat mezi objekty s různým jasem. Kontrastní citlivost je maximální při středních prostorových frekvencích a klesá při velmi nízkých nebo vysokých frekvencích. Lidské oko je nejcitlivější na kontrast při prostorových frekvencích okolo 3 - 4 cyklů na stupeň zorného pole.

#### Prostorová rozlišovací schopnost oka
Schopnost oka rozlišit jemné detaily obrazu. Je určena hustotou fotoreceptorů v sítnici, zejména ve žluté skvrně (fovea). Prostorové rozlišování je ovlivněno faktory jako jsou osvětlení, kontrast a adaptace.

#### Časová rozlišovací schopnost oka
Schopnost oka rozpoznat změny intenzity světla v čase. Oko dokáže vnímat až 60 - 90 změn za sekundu, což odpovídá vnímání pohybu a blikání světla. Časové rozlišení je rozhodující pro sledování rychle se pohybujících objektů.

#### Všeobecná schéma zobrazovacího procesu
Proces zobrazování zahrnuje zachycení obrazu, jeho zpracování a zobrazení. Tento proces může zahrnovat různé kroky:
1. **Snímání obrazu**: Získání obrazových údajů pomocí snímačů (např. kamer, skenerů).
2. **Digitalizace**: Konverze analogového signálu na digitální vzorkováním a kvantizací.
3. **Zpracování obrazu**: Aplikace různých algoritmů na zlepšení kvality obrazu, extrakci informací a analýzu.
4. **Zobrazení**: Vizualizace výsledného obrazu na displeji nebo jiném zobrazovacím zařízení.

#### Základní principy sběru obrazových dat
- **Analogový obraz**: Nepřetržitý signál, který se kontinuálně mění a jsou spojité signály.
- **Digitální obraz**: Diskrétní reprezentace obrazu, kde každý pixel má určitou hodnotu a digitalizace zahrnuje vzorkování a kvantizaci analogového signálu.
- **Vzorkování obrazu**: Proces převodu spojitého obrazu na diskrétní mřížku pixelů.
- **Kvantování obrazu**: Proces přeměny spojitých úrovní šedé nebo barev na diskrétní hodnoty.

#### Základní úlohy zpracování obrazu
Mezi ně patří zlepšení kvality obrazu (úprava kontrastu, odstranění šumu, zaostření), detekce a extrakce objektů (identifikace a segmentace objektů v obraze), komprese obrazu (zmenšení velikosti obrazových souborů) a rozpoznávání vzorů (identifikace a klasifikace objektů nebo vzorů v obraze). Tyto úlohy využívají různé algoritmy a techniky jako je filtrovaní, segmentace a transformace.

#### Lineární zobrazovací systém
Systém, jehož výstup je lineární kombinací vstupů. Při zpracování obrazu to znamená, že operace aplikované na obraz jsou lineární, například konvoluce nebo filtrace. Platí aditivita a homogenita.

#### Impulzní odezva
Odezva systému na jednotkový impulz. V zobrazování představuje reakci systému na bodový zdroj světla. Impulzní odezva je klíčem k charakterizaci systémů zpracování obrazu.

#### Prostorově invariantní systém
Systém, jehož vlastnosti a chování se nemění v závislosti na poloze vstupního signálu v prostoru. Odezva systému na impulz je stejná v celém prostoru obrazu, tzv. izoplanární proces zobrazování.

#### Konvoluce v spojité a diskrétní oblasti
Matematická operace používaná na filtrovaní signálů. V spojité oblasti je konvoluce integrálem součinu dvou funkcí. V diskrétní oblasti je konvoluce součtem součinu dvou postupností.

#### Konvoluce vs korelace
- **Konvoluce**: Matematická operace, která kombinuje dva signály nebo obrazy na účely filtrácie nebo analýzy. Konvoluce má zásadní význam při zpracování signálů a obrazů, zejména při aplikaci filtrů. Vlastnosti jsou komutativita, asociativita a distributivita.
- **Korelace**: Matematická operace používaná na měření podobnosti mezi dvěma signály nebo obrazy. Korelace se často používá při detekci vzorů a objektů v obrazech. Vlastnosti jsou, že není komutativní a měří podobnost.

#### Princip farebného zobrazení
Je založený na kombinaci základních barev (červená, zelená, modrá - model RGB). Barvy v obraze jsou tvořeny kombinací těchto tří základních barev s různou intenzitou.

#### Režimy snímaní
- **Čiarová grafika**: Zobrazení obrázku pomocí čar a křivek.
- **Poltóny**: Používání různých odstínů šedé na zobrazení obrázků.
- **Odtiene šedej**: Obrázky, které obsahují odstíny šedé, ale nemají barvu.
- **Farebné**: Obrázky, které obsahují farebné informace.

#### Operace na obrázcích
- **Bodové operace**: Operace, které se aplikují na jednotlivé pixely obrázku. Příkladem je prahování, při kterém se pixely rozdělí na základě určité prahové hodnoty.
- **Lokální operace**: Operace, které se aplikují na okolí jednotlivých pixelů. Příkladem je vyhlazení nebo doostření obrázku pomocí filtrů.
- **Globální operace**: Operace, které se použijí na celý obrázek. Příkladem je vyrovnání histogramu, které upravuje kontrast celého obrázku.

#### Specifické metody a techniky
- **Prahování**: Metoda segmentace obrazu, při které se pixely segmentují na základě prahové hodnoty.
- **Adaptivní prahování**: Metoda prahování, která se přizpůsobuje lokálním vlastnostem obrazu a umožňuje lepší segmentaci v případě nerovnoměrného osvětlení. Existují dva přístupy: Chow-Kaneko přístup a lokální prahování.
- **Úprava kontrastu**: Proces zlepšení viditelnosti detailů v obraze zvýšením rozdílů mezi světlými a tmavými oblastmi.
- **Vyrovnání histogramu**: Technika úpravy intenzity obrazu, která rozšiřuje rozložení intenzity tak, aby pokrývalo celý rozsah možných hodnot.
- **Logaritmický operátor**: Používá se na zlepšení kontrastu v snímkách s vysokým dynamickým rozsahem komprimováním hodnot intenzity.
- **Exponenciální operátor**: Používá se na úpravu intenzity obrazu exponenciální změnou hodnot pixelů.
- **Vyhlazovací filtre**: Filtry používané na snížení šumu a zjemnění obrazu. Příkladem je průměrovací filtr a Gaussov filtr.
- **Zaostrení obrazu**: Proces zvyšování ostrosti a jasnosti obrazu. Používají se techniky jako je například unsharp masking.
- **Mediánová filtrace**: Nelineární

 technika používaná na odstranění šumu z obrazu nahrazením každého pixelu mediánem hodnot v jeho okolí.
- **Fourierova transformace**: Matematická technika, která převádí obraz z prostorové do frekvenční oblasti. Umožňuje analýzu frekvenčního obsahu obrazu.
- **Filtrovaní ve frekvenční oblasti**: Proces úpravy frekvenčních složek obrazu pomocí filtrů jako jsou pásmové průchody a dolní průchody.
- **Restaurace obrazu**: Obnova obrazu je technika předběžného zpracování, která se snaží využít apriorní znalosti o porušení matematického modelu obrazu.
- **Inverzní filtrácia**: Technika obnovy obrazu odstraněním degradace pomocí inverzního filtra.
- **Wienerova filtrácia**: Technika obnovy obrazu, která zohledňuje funkci šumu a degradace s cílem optimalizovat poměr signál/šum.
- **Detekce hrán**: Proces identifikace hrán objektů na obrázku. Používají se metody jako Sobelov, Prewittov a Cannyho operátor.
- **Segmentace obrazu**: Proces rozdělení obrazu na oblasti s podobnými vlastnostmi. Používají se metody jako prahování, k-means clustering a watershed transformace.
- **Houghova transformace**: Metoda na detekci tvarů v obraze, například čar a kružnic, transformací z obrazového prostoru do prostoru parametrů.
- **DCT (Diskrétní kosínusová transformace)**: Transformace, která převádí obraz z prostorové do frekvenční oblasti pomocí kosínusových funkcí. Používá se při kompresi obrázků, například JPEG.

#### Metódy komprese
- **Jednoduché metódy**: Metódy jako RLE (Run-Length Encoding), které kódují opakující se sekvence znaků.
- **Štatistické metódy**: Metódy jako Huffmanovo a aritmetické kódování, které využívají frekvenci výskytu znaků.
- **Slovníkové metódy**: Metódy jako LZW (Lempel-Ziv-Welch), které kódují postupnosti znaků pomocí slovníků.
- **Transformační metódy**: Metódy jako JPEG, které na komprimaci obrazu používají transformace (DCT, wavelet).

#### JPEG
Štandard komprese obrazu, který využívá DCT na zmenšení velikosti dat obrazu při zachování jeho vizuální kvality.

#### Popis objektů v obrazech
Proces extrakce a reprezentace informací o objektech v obraze. Používají se metody jako detekce hrán, momenty a Fourierovy deskriptory.

#### Rozpoznání
Proces identifikace objektů nebo vzorů na obrázku. Používají se techniky jako rozpoznávání vzorů, štatistické metódy a strojové učení.

#### PCA (Principal Component Analysis)
Technika redukce dimenzionality údajů, která identifikuje hlavní komponenty datového prostoru. Používá se na kompresi a analýzu údajů.

#### Matematická morfologie
Teorie zkoumající prostorové struktury:
- **Erózia**: Operace, která zmenšuje velikost objektů na obrázku.
- **Dilatácia**: Operace, která zvětšuje objekty na obrázku.
- **Otvorenie**: Erózia po které následuje dilatácia, odstraňuje malé objekty.
- **Uzavretie**: Dilatácia následovaná eróziou, vyplňuje malé otvory.

#### Geometrické transformace
Zahrnují změnu velikosti, otočení, posunutí a zrcadlení obrazu. Na aplikaci těchto změn na obrázek se používají transformační a interpolační matice:
- **Škálování**: Změna velikosti obrazu.
- **Rotace**: Změna orientace.
- **Zrcadlení**: Překlopení obrazu.
- **Posun (translácia)**: Změna pozice.
- **Afinná transformace**: Lineární geometrická transformace obrazu.