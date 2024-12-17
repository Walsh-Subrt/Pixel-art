Dobrý den, zde posílám slovní část ročníkového projektu.

Cílem mého projektu bylo, se lépe seznámit s programovacím ( scriptovacím )jazykem JavaScript. Vybral jsem si programování, protože to bylo vedlo k mému rozhodnutí jít na tuto školu. Vybral jsem si něco, co bych dokázal zpracovat, ovšem jsem musel poprosit jednoho z mých kamarádů, aby mi s kódem pomohl. Naučil jsem se dělat CSS a JS v HTML. Do budoucna bych chtěl tento program rozšířit nebo udělat něco složitějšího, záleží jak daleko se za tu dobu dostanu. Největší problém mi dělala HTML část se kterou jsem potřeboval pomoc. Samotné programování mě baví a zvažuji, že se mu budu věnovat více času. 
Na tvorbě tohoto projektu jsem spolupracoval s využitím vzdělávacích videí na platformě YouTube a asistence AI nástroje, který mi poskytl technickou podporu a rady při psaní kódu. Obrovské poděkování patří také Matějovi Vítovi, který mi s kódem pomohl, děkuji.



Tento program je nástroj pro tvorbu pixelového umění funguje takto:

Inicializace a mřížka:
HTML vytváří mřížku složenou z větších bloků (.bigColumn), které obsahují menší čtverce (.smallColumn).
Každý malý čtverec představuje pixel, který lze vybarvit.

Výběr barvy:
Nad mřížkou je tlačítko "Pick a color" (#colorPicker), které po kliknutí otevře barevné menu (#pickColorDiv).
Uživatel může zvolit jednu ze čtyř přednastavených barev (červená, žlutá, zelená, modrá).
Po výběru barvy se tlačítko změní na vybranou barvu, což indikuje, která barva je právě aktivní.

Vybarvování čtverců:
Uživatel klikne na libovolný čtverec v mřížce, který se okamžitě vybarví aktuální vybranou barvou (nastavenou přes colorPicker).
JavaScript naslouchá událostem kliknutí (addEventListener) a mění backgroundColor daného čtverce.

Vymazání mřížky:
Kliknutím na tlačítko "Clear Grid" (#clearGridBtn) se všechny čtverce mřížky resetují na bílou barvu.

Interaktivita pomocí JavaScriptu:
Výběr barvy: Každé barevné tlačítko mění barvu ukazatele (#colorPicker) a zavírá dialog barev.
Vybarvení čtverce: Skript aplikuje vybranou barvu na čtverec po kliknutí.
Reset: Skript projde všechny čtverce (.smallColumn) a nastaví jim výchozí barvu (white).

Děkuji a přeji krásný zbytek dne, Josef Šubrt



