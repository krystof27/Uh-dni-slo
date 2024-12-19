# Uh-dni-slo
Dobrý den pane učiteli, posílám Vám vypracovaný ročníkoví projekt.
Cílem toho to projektu bylo vytvořit jednoduchou webovou hru "Uhodni číslo". Hra by měla hráčovi ukázat zábvný způsob, jak si vyzkoušet hádání vygenerovaného náhodného čísla v rozsahu od 1 do 10. Tento projekt jsem bral jako novou výzvu, ze kterých jsem se mohl více naučit z webových technologií, jako je HTML, CSS a JavaScript. Chtěl jsem pro hráče vytvořit přehlednou stránku, a aby hráče bavila.

Stav projektu je momentálně funkční a hráč má za úkol uhodnout vygenerováné náhodné číslo v rozsahu (1-10). Hra funguje, tak že po spuštění hry vygeneruje náhodné číslo, které hráč musí uhodnout. Hráč zadá svůj tip do textového pole a potvrdí ho stisknutím Enter nebo tlačítkem Submit. Pokud je hráčův tip špatný hra zobrazí zprávu: "Too small" (pokud je číslo menší než vygenerované) nebo "Too big" (pokud číslo je větší než vygenerované), ale pokud hráč uhodne číslo správně, tak se zobrazí výherní obrazovka: "You won" (hrač vyhrál) a zobrazí se také "It took you 4 guesses! (počet pokusů, které k uhodnutí čísla potřeboval). Po výhře hráč může začít hrát novu hru kliknutím na tlačítko "Play again", které stránku znovu načte. Desing hry jsem pro pozadí vybral tmavě lososovou. Texty a tlačítka jsou navrženy, tak aby byly dobře čitelné a tlačítka mají ještě zaoblené strany a mění bravu při najetí myší nebo po klinuti, což nám zlepšuje vzhled. Všechny prvky jsou umístěny uprostřed obrazovky a k tomu jsem použil CSS Grid. Kod této hry jsem popsal ve visual code.

Na vytvoření této hry jsem si rozmyslel, jak hra bude fungovat a jak bude vypadat. A proto jsem zvolil jednoduchí vzhled, který je snadný pro orientaci. Na tuto hru jsem potřeboval funkce např.: počítání pokusů, generování čísla. Kod pro generování náhodné čísla jsem udělal pomocí Math.random(). Poté jsem přidal vstupní pole a tlačítko pro odesílaní čísel. Funkce nám kontroluje, zda je číslo správné, příliš malé nebo velké. Ale jestliže hráč zadá to pole text místo čísla, zobrzí se upozornění "Please enter a number!"(zadej číslo). Vyherní obrazovku pokuď hráč uhodl číslo, tak se mu zobrazí nová obrazovka s počtem pokusů a tlačítkem pro restart. Tato funkce je vytvořena pomocí manipulace s DOM, kdy se mění styl a přídávání nové zprávy. Styl CSS jsem nastavil barvy, fonty a zarovnání. Nato jsem požil Grid pro centrování prvků a zjednodušení. Při testování webu jsem přišel na pár chyb např.: Zadaný text místo čísal způsoboval pád programu. To jsem opravil pomocí isNaN(), zobrazením varováním. Pčítadlo pokusů se nezobrazovalo správně, upravil jsem tuto hodnotu v DOM. Restart hry pomocí tlačítka nefugoval, protože jsem zapoměl resetovat proměnné (počet pokusů, vygenerování čísla). A pro vylepšení jsem přidal, aby hráči mohli ovládat hru pomocí Enter pro jednoduší ovládání.

Do budoucna bych těl určitě vylepšit, aby tato hra měla větší rozsah čísel (např. 1-100), přidal bych časovač za jak dlouho hráč uhodl číslo a vylepšit vzhledově skore a celkově vylepšit stránku vzheledově. Když hráč vyhraje tak, aby se mu ukázala animace, kde by byl panáček s pohárem nebo by zazněla výherní znělka. Tento projekt mi pomohl lépe pochopit práci s HTML, CSS a JavaSriptu. Byla to pro mě velká výzva něco takového udělat a hlvně jsem se naučil více programovat.

Při této práci jsem používal tyto zdroje https://developer.mozilla.org/en-US/; https://www.w3schools.com/
 
