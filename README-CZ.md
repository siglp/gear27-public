# Gear27

[Anglická verze (English version)](https://github.com/siglp/gear27-public)

## Datové pole pro Garmin

Pokud se vám pole líbí, ohodnoťte ho prosím!

Gear27 je datové pole pro zařízení Garmin. Slouží pro zobrazovaní a zapisování hodnot řazení na kole z připojeného senzoru.

Cílem je, aby toto pole bylo konfigurovatelné. Můžete se rozhodnout, které hodnoty jsou důležité a ty si nechat zobrazovat. Například pokud chcete vidět jen číslo zadního pastorku, tak můžete "vypnout" zobrazovaní ostatních dat (velikost pastorku, název pole atd.).

Testováno je na řazení SRAM AXS a realných  Garmin zařízeních Fenix 5x Plus, Fenix 7x Pro a Edge MTB.

## Nastavení
- #### Barva pozadí
    - Definovaná barva pozadí nebo automatická - vybere zařízení (černobílé displeje mají k dispozici jen bílou a černou)
        - Automaticky
        - Bílá
        - Světle Šedá
        - Tmavě Šedá
        - Černá
        - Červená
        - Tmavě Červená
        - Oranžová
        - Žlutá
        - Zelená
        - Tmavě Zelená
        - Modrá
        - Tmavě modrá
        - Fialová
        - Růžová-
- #### Barva písma
    - Definovaná barva písma nebo automatická - vybere zařízení (černobílé displeje mají k dispozici jen bílou a černou)
        - Automaticky
        - Bílá
        - Světle Šedá
        - Tmavě Šedá
        - Černá
        - Červená
        - Tmavě Červená
        - Oranžová
        - Žlutá
        - Zelená
        - Tmavě Zelená
        - Modrá
        - Tmavě modrá
        - Fialová
        - Růžová-
- #### Př./Pa. oddělovač
    - Znak, který bude zobrazen mezi hodnotami
        - Lomítko ' / '
        - Pomlčka ' - '
        - Dvojtečka ' : '
        - Mezera '   '
- #### Zobrazovat mezeru v hodnotách
    - Zobrazovat mezeru mezi znaky a oddělovačem v hodnotách
        - Ano / Ne
- #### Hlavní hodnota
    - Která hodnota bude v poli zobrazena jako hlavní
        - Číslo převodu
        - Velikost převodu
- #### Druhá hodnota (menší)
    - Která hodnota bude v poli zobrazena jako druhá (menší)
        - Číslo převodu
        - Velikost převodu
- #### Zobrazovat název (pokud to jde)
    - Zobrazovat název v poli pokud je to možné vzhledem k velikosti pole
        - Ano / Ne
- #### Zobrazovat druhou hodnotu (pokud to jde)
    - Zobrazovat také druhou hodnotu v poli pokud je to možné vzhledem k velikosti pole
        - Ano / Ne
- #### Zobrazovat převodník
    - Zobrazovat aktuální hodnotu Převodníku v poli
        - Ano / Ne
- #### Zobrazovat pastorek
    - Zobrazovat aktuální hodnotu Pastorku v poli
        - Ano / Ne
- #### Korekce pozice názvu (x,y)
    - Korekce pozice názvu o +/- pixelů na ose X a +/- pixelů na ose Y
    - Sem vložte počet pixelů o které chcete posunout zobrazení názvu
        - vždy zadejte 2 hodnoty oddělené čárkami, 0 znamená žádný posun
        - př. 10,15: posunutí o 10 pixelů doprava a 15 pixelů dolů
        - př. -10,-15: posunutí o 10 pixelů doleva a 15 pixelů nahoru
- #### Korekce pozice hlavní hodnoty (x,y)
    - Korekce pozice hlavní hodnoty o +/- pixelů na ose X a +/- pixelů na ose Y
    - Sem vložte počet pixelů o které chcete posunout zobrazení hlavní hodnoty
        - vždy zadejte 2 hodnoty oddělené čárkami, 0 znamená žádný posun
        - př. 10,15: posunutí o 10 pixelů doprava a 15 pixelů dolů
        - př. -10,-15: posunutí o 10 pixelů doleva a 15 pixelů nahoru
- #### Korekce pozice druhé hodnoty (x,y)
    - Korekce pozice druhé hodnoty o +/- pixelů na ose X a +/- pixelů na ose Y
    - Sem vložte počet pixelů o které chcete posunout zobrazení druhé hodnoty
        - vždy zadejte 2 hodnoty oddělené čárkami, 0 znamená žádný posun
        - př. 10,15: posunutí o 10 pixelů doprava a 15 pixelů dolů
        - př. -10,-15: posunutí o 10 pixelů doleva a 15 pixelů nahoru
- #### Číslo převodníku/ů - přepis
    - Sem vložte csv pro vlastní čísla převodníku/ů
        - př. bežné pořadí pro kolo: 1,2,3
        - př. obrácené pořadí pro kolo: 3,2,1
        - není nutné zadávat všechny hodnoty
- #### Velikost převodníku/ů - přepis
    - Sem vložte csv pro vlastní velikost převodníku/ů
        - př. (3 převodníky): 22,32,42
        - př. (1 převodník): 32
        - není nutné zadávat všechny hodnoty
- #### Číslo pastorku/ů - přepis
    - Sem vložte csv pro vlastní definici čísla pastorku/ů
        - př. bežné pořadí pro kolo: 12,11,10,9,8,7,6,5,4,3,2,1
        - př. obrácené pořadí pro kolo: 1,2,3,4,5,6,7,8,9,10,11,12
        - není nutné zadávat všechny hodnoty
- #### Velikost pastorku/ů - přepis
    - Sem vložte csv pro vlastní velikost pastorku/ů
        - př. (SRAM 10-52): 52,42,36,32,28,24,21,18,16,14,12,10
        - není nutné zadávat všechny hodnoty, např. 52 přepíše velikost jen "pro realný index = 1", vše ostatní se bude brát ze senzoru
- #### Fix ztráty spojení
    - Pokud dojde ke ztrátě spojení mezi řazením a zařízením Garmin, tak použít poslední známou hodnotu a ne '-'
        - Ano / Ne

## Podporovaná zařízení

### Plná podpora nahrávaní aktivity
Zařízení, která nahravájí statistiky použití převodů během kol a celé aktivity.

 - 	D2™ Mach 1
 - 	D2™ Mach 2 Pro
 - 	D2™ Mach 2
 - 	Descent™ Mk2 / Mk2i
 - 	Descent™ Mk2 S
 - 	Descent™ Mk3 43mm / Mk3i 43mm
 - 	Descent™ Mk3i 51mm
 - 	Edge® 1030 Plus
 - 	Edge® 1030
 - 	Edge® 1040 / 1040 Solar
 - 	Edge® 1050
 - 	Edge® 530
 - 	Edge® 540 / 540 Solar
 - 	Edge® 550
 - 	Edge® 830
 - 	Edge® 840 / 840 Solar
 - 	Edge® 850
 - 	Edge® MTB
 - 	Enduro™ 3
 - 	epix™ (Gen 2) / quatix® 7 Sapphire
 - 	epix™ Pro (Gen 2) 42mm
 - 	epix™ Pro (Gen 2) 47mm / quatix® 7 Pro
 - 	epix™ Pro (Gen 2) 51mm / D2™ Mach 1 Pro / tactix® 7 – AMOLED Edition
 - 	fēnix® 5 Plus
 - 	fēnix® 5S Plus
 - 	fēnix® 5X Plus
 - 	fēnix® 6 Pro / 6 Sapphire / 6 Pro Solar / 6 Pro Dual Power / quatix® 6
 - 	fēnix® 6S Pro / 6S Sapphire / 6S Pro Solar / 6S Pro Dual Power
 - 	fēnix® 6X Pro / 6X Sapphire / 6X Pro Solar / tactix® Delta Sapphire / Delta Solar / Delta Solar - Ballistics Edition / quatix® 6X / 6X Solar / 6X Dual Power
 - 	fēnix® 7 / quatix® 7
 - 	fēnix® 7 Pro - Solar Edition (no Wi-Fi)
 - 	fēnix® 7 Pro
 - 	fēnix® 7S Pro
 - 	fēnix® 7S
 - 	fēnix® 7X / tactix® 7 / quatix® 7X Solar / Enduro™ 2
 - 	fēnix® 7X Pro - Solar Edition (no Wi-Fi)
 - 	fēnix® 7X Pro
 - 	fēnix® 8 43mm
 - 	fēnix® 8 47mm / 51mm / tactix® 8 47mm / 51mm / quatix® 8 47mm / 51mm
 - 	fēnix® 8 Pro 47mm / 51mm / MicroLED / quatix® 8 Pro 47mm / 51mm
 - 	fēnix® 8 Solar 47mm
 - 	fēnix® 8 Solar 51mm / tactix® 8 Solar 51mm
 -	fēnix® 9 43mm
 - 	fēnix® 9 47mm / 51mm
 - 	fēnix® 9 Pro 43mm
 - 	fēnix® 9 Pro 47mm
 - 	fēnix® 9 Pro 51mm
 - 	fēnix® 9 Pro Solar 47mm
 - 	fēnix® 9 Pro Solar 51mm
 - 	fēnix® E
 - 	Forerunner® 745
 - 	Forerunner® 945 LTE
 - 	Forerunner® 945
 - 	Forerunner® 955 / Solar
 - 	Forerunner® 965
 - 	Forerunner® 970
 - 	MARQ® (Gen 2) Athlete / Adventurer / Captain / Golfer / Carbon Edition / Commander - Carbon Edition
 - 	MARQ® (Gen 2) Aviator
 - 	MARQ® Adventurer
 - 	MARQ® Athlete
 - 	MARQ® Aviator
 - 	MARQ® Captain / MARQ® Captain: American Magic Edition
 - 	MARQ® Commander
 - 	MARQ® Driver
 - 	MARQ® Expedition
 - 	MARQ® Golfer
 - 	Venu® 4 41mm
 - 	Venu® 4 45mm / D2™ Air X15
 - 	Venu® X1

### Nepodporovaná zařízení z důvodu malé dostupné paměti (32K)
Zařízení, která mají jen 32K paměti pro pole NEJSOU od verze 2.0.0 podporována. Použijte **Gear27-32K**, které je odvozené od verze 1.12.0.

- Enduro™
- fēnix® 6 / 6 Solar / 6 Dual Power
- fēnix® 6S / 6S Solar / 6S Dual Power

### Garmin Edge Explorer, Edge Explorer 2, Forerunner 1xx, 2xx, 6xx
Garmin Edge Explorer, Garmin Edge Explorer 2, Forerunner 1xx, 2xx, 6xx nepodporují standardní rozhraní pro řazení. Pole na nich NEbude fungovat a zařízení tak NEjsou podporována.

## Chyby a návrhy
Chyby a návrhy můžete zadávat zde: https://github.com/siglp/gear27-public/issues

Prosím vždy o vyplnění:
- Verzi aplikace Gear27.
- Typ zařízení Garmin.
- Typ telefonu, pokud je problém v ConnectIQ nebo nastavení.

## Lokalizace do jiného jazyka
Pokud je zde někdo, kdo může a chtěl by pomoci s překladem do jiného jazyka, tak by mi to moc pomohlo. Prosím kontaktujte mě přes stránky Garmin Connect IQ Store.

## Verze
### Releasnuté (vydané)
- #### 2.3.0 - [ 1.9.2026 ]
    - Podpora pro nová zařízení (Fenix 9 Pro 43mm / 47mm, Fenix 9 Pro Solar 47mm / 51mm)
- #### 2.2.0 - [ 28.8.2026 ]
    - Podpora pro nová zařízení (Fenix 9 43mm / 47mm / 51mm, Fenix 9 Pro 51mm)
- #### 2.1.0 - [ 10.7.2026 ]
    - Přidán celkový počet použitých převodů do aktivity
    - Podpora pro nové zařízení (D2 Mach 2 Pro)
    - Podpora pro případný DEBUG aplikace
    - Odstraněna kompatibilita pro zařízení, která podle manuálu nepodporují rozhraní (API) pro řazení (Edge Explore 2, Forerunner 1xx, 2xx, 5xx, 6xx, Instinct 3 apod.)
    - Přesun projektu na GitHub
- #### 2.0.0 - [ 9.12.2025 ]
    - Možnost SW fixnout výpadek spojení mezi zařízením a řazením (použije se poslední známá hodnota)
    - Zrušena podpora pro zařízení, která mají jen 32K paměti pro pole (Enduro, Fenix 6 / 6 Solar / 6 Dual Power, Fenix 6S / 6S Solar / 6S Dual Power, Forerunner 245, Forerunner 645, Instinct E 40mm, Instinct E 45mm, Instinct 3 Solar 45mm / 50mm). Toto omezení již nebylo možné nijak obejít a brzdilo další rozvoj pole. Pro tato zařízení vzniklo Gear27-32K.
- #### 1.12.0 - [ 3.11.2025 ]
    - Podpora pro nová zařízení (D2 Mach 2)
    - Úpravy v německém překladu (díky Tobias Fengels)
- #### 1.11.0 - [ 13.10.2025 ]
    - Podpora pro nová zařízení (Edge 550, Edge 850, quatix 8 47mm / 51 mm, Fenix 8 Pro 47mm / 51 mm / MicroLED, Instinct Crossover AMOLED, Venu 4 41mm / 51mm)
    - Možnost upravit pozici zobrazování na zařízení
    - Přidána němčina (pomocí AI)
- #### 1.10.0 - [ 19.6.2025 ]
    - Podpora pro nová zařízení (Edge MTB, Venu X1)
- #### 1.9.0 - [ 20.5.2025 ]
    - Podpora pro nová zařízení (Forerunner 570 42mm / 47mm, Forerunner 970)
- #### 1.8.0 - [ 12.5.2025 ]
    - Podpora pro nová zařízení (Descent G2, tactix 8 47mm / 51mm / Solar 51mm, Instinct 3 AMOLED 45mm / 50 mm / Solar 45mm / Solar 50mm, Instinct E 40mm / 45mm)
- #### 1.7.0 - [ 9.10.2024 ]
    - Podpora pro nové zařízení (Enduro 3)
- #### 1.6.0 - [ 4.9.2024 ]
    - Podpora pro nová zařízení (Fenix 8 43mm / 47mm / 51mm / Solar 47mm / Solar 51mm, Fenix E)
- #### 1.5.0 - [ 26.7.2024 ]
    - Podpora pro nová zařízení (Descent Mk3/Mk3i 43mm/51mm, Edge 1050, Forerunner 165/165 Music, Fenix 7 Pro/7X Pro (no Wi-Fi))
- #### 1.4.0 - [ 28.7.2023 ]
    - Podpora pro nová zařízení (Epix2 42mm/47mm/51mm, Fenix 7 Pro/7s Pro/7x Pro)
- #### 1.3.0 - [ 3.5.2023 ]
    - Podpora pro nová zařízení (Edge 540/840, Forerunner 265/965)
- #### 1.2.1 - [ 28.3.2023 ]
    - Bugfix - Barva pozadí při tmavém režimu
- #### 1.2.0 - [ 13.3.2023 ]
    - Bugfix - průhlednost pole v mapě a statistiky (opět...).
- #### 1.1.0 - [ 6.3.2023 ]
    - Bugfix.
    - Přidána francouzština (díky Anthony Humeau)
- #### 1.0.0 - [ 3.3.2023 ]
    - Bugfix.
    - Možnost zobrazení mezery / ne-mezery v hodnotě.
    - Možnost definovat barvu pozadí a popředí.
    - Revize podporovaných zařízení (odstranění zařízení bez podpory Shifting API, přidání nových zařízení)
- #### 0.6.0 - [ 23.6.2022 ]
    - Počítání různých statistik pro každý převodník / pastorek (např. jak dlouho byl používán). Pouze pro zařízení s pamětí pro pole nad 32K a některé vyjímky s 32K.
    - Zapisovaní statistik do aktivity.
    - Velký refactoring kódu kvůli paměťovým limitům (zvláště pro zařízení s pamětí pro pole 32K)
- #### 0.5.0 - [ 8.6.2022 ]
    - Možnost předefinovat velikost jednotlivých převodníků / pastorků (některé starší typy hodinek nedovolují zadat velikost pastorku 45+, některé nedovolí nastavit správnou velikost převodníku).
    - Možnost změnit číslo převodníků / pastorků (nejmenší = 1 a ne 12).
    - Podpora pro co největší počet Garmin zařízení (vzhledem k testům v simulátoru).
- #### 0.4.0 - [ 3.6.2022 ]
    - Přepracování problematického kódu pro některá zařízení.
- #### 0.3.x (0.3.0 and 0.3.1) - [ 2.6.2022 ]
    - **POZOR** - v těchto verzích se na některých realných zařízeních (Fenix5x, Fenix6) objevily problémy s nastavením. Pracuji na přepisu, některých částí kódu, které by to mohly mít na svědomí. Dočasné řešení je neměnit defaultní nastavení. Omlouvám se...
- #### 0.3.1 - [ 2.6.2022 ]
    - Pokus o opravu zobrazovaní / nezobrazování názvu pole.
        - Fix je naslepo, protože simulátory, alfa verze (sideload) i beta verze (ConnectIQ) fungují...
- #### 0.3.0 - [ 2.6.2022 ]
    - **POZOR** - došlo ke změně souboru pro grafy v aktivitě, starší aktivity se tak mohou zobrazovat nekorektně.
    - Vyladění vzhledu pro 1-8 polové UI.
    - Možnost výběru zda zobrazovat číslo převodu nebo velikost převodníku / pastorku (nebo obou).
    - Nahrávání velikosti převodu do aktivity a zobrazení v grafech.
    - Zapisování převodu (poměr Př. / Pa) do aktivity a zobrazení v grafech.
- #### 0.2.0 - [ 23.5.2022 ]
    - Nastavení "vzhledu".
    - Nahrávání čísla převodu do aktivity a zobrazení v grafech.
    - Podpora pro 1-4 polové UI na hodinkách (kulatý design).
- #### 0.1.0 - [ 22.5.2022 ]
    - Prvotní testovací release - nebyl veřejný

### Plánované (budoucí)
- #### 2.x.y ??? - [ ??? ]
    - ??? Bugfix.
    - ??? Možnost definovat velikost fontů a zarovnání.
    - ??? Stav baterie.
    - ??? Manuální nastavení vzhledu přes Connect IQ.
    - ??? Možná podpora pro výběr, která data zapisovat a která ne.
    - ??? Další návrhy.
