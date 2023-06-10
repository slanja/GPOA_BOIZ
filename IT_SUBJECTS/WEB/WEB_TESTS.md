[<--- Back](https://github.com/slanja/GPOA_BOYZ/blob/main/README.md)

## Overview
- [HTML I](#HTML-I)
- [HTML II](#HTML-II)
- [HTML III](#HTML-III)
- [CSS I](#CSS-I)
- [CSS II](#CSS-II)
- [CSS III](#CSS-III)
- [HTML + CSS](#HTML-CSS)
- [PHP I](#PHP-I)
- [PHP II](#PHP-II)


### [^](#Overview)HTML I
1. Jak se do zdroje HTML zadávají speciální znaky jako je ©?

    ```
    entitou &copy
    ```
    
2. Jak se nazývá jazyk, pro vytvoření nejjednodušších internetových stránek?

    - [x] a) HTML
    - [ ] b) Word Wide Web
    - [ ] c) Hyppertext
    - [ ] d) FLASH

3. Co je to webhosting?

    ```
    server, který nám zapůjčí prostor na nahrání webových stránek, ze začátku se zde nachází startovací soubor 
    index.html nebo index.php
    ```

4. Cesta k odkazovanému souboru se nazývá (doplňte)

    - [ ] a) syntaxe
    - [ ] b) informační kód
    - [ ] c) odkazovací adresa
    - [ ] d) zdrojový kód
    - [x] e) relativní nebo absolutní adresa

5. Jak se chápe konec řádku ve zdroji?

    ```
    konec řádku je jako enter
    ```

6. Může být na začátku názvu tagu mezera?

    - [ ] a) Může
    - [ ] b) Může, ale jen u některých.
    - [x] c) Nesmí

7. Lze si u každé HTML stránky na internetu prohlédnout její zdrojový kód?

    - [x] a) Ano
    - [ ] b) Lze to zakázat
    - [ ] c) Ne

### [^](#Overview)HTML II
1. Jakou rodinu protokolů používá internet?

    - [ ] a) IP/TPC
    - [ ] b) IP/DNS
    - [ ] c) TCP/WWW
    - [x] d) TCP/IP
    - [ ] e) TCP/DNS

2. Vyberte jen správné odpovědi u otázek, týkajících se obecné syntaxe HTML

    - Tagy, které prohlížeč nezná, jako by nebyly. ```Ano```
    - V adresách a jménech souborů nezáleží na velikosti písmen, smějí tam být mezery a čeština. ```Ne```
    - Nezáleží na velikosti písem, např. "body" je totéž co "BODY". ```Ano```
    - Dvě mezery po sobě (nebo víc) mají stejný význam jako jedna mezera. ```Ano```
    
3. Jak se v HTML tvoří poznámky? (zapište přesně)

    ```
    <!--poznámka--->
    ```  
  
4. HTML soubor je text obalený značkami, které se nazývají (doplňte) a dělíme je na (doplňte)

    ```  
    tagy, jsou párové a nepárové
    ```
    
5. Jak říkáme webovým editorům, ve kterých je verze zobrazená na obrazovce vzhledově totožná s výslednou verzí internetové stránky

    - [ ] a) Rychlé editory HTML
    - [ ] b) HTML editory
    - [ ] c) Prezentační editory
    - [ ] d) Přímé editory HTML
    - [x] e) WYSIWYG editory

### [^](#Overview)HTML III

1. Co bývá součástí webhostingových služeb? (uveďte alespoň 3 služby)

    ```
    emailoví klient
    FTP
    správce souborů
    MySQL
    ```
    
2. Co by mělo tvořit základní strukturu (stavbu nebo také kostru) webové HTML stránky? (stačí pouze česky názvy částí)

    ```
    hlava a tělo
    body, head
    ```
    
3. Jak se jmenuje protokol, kterým nejběžněji přenášíme soubory z lokálního PC na vzdálený server?

    ```
    FTP - File Transfer Protocol
    ```
    
4. Co je to startovací stránka webu? Uveďte alespoň 2 příklady

    ```
    Soubor, který na webovém prostoru od začátku, většinou je prázdný nebo obsahuje nějákou reklamu
    index.html nebo index.php
    ```
    
5. O který řád (úroveň) domény uvedené v následující webové adrese se jedná? http://skola.zde.cz
    
    - [x] a) 3
    - [ ] b) 0
    - [ ] c) 1
    - [ ] d) 2

### [^](#Overview)CSS I
1. Napište příklad nebo vysvětlete co je to pseudotřída:

    ```
    a:hover
    ```
    
2. Chceme, aby se odstavec vypsal modře, tučně a kurzívou (kód musí odpovídat standardům W3C). Vyberte správnou variantu odpovědi:

    - [x] a) &lt;p style="font-style: italic; font-weight: bold; color: blue">Tento odstavec bude modrý.</p>
    - [ ] b) &lt;p>Tento text bude modrý.<style="font-style: italic; font-weight: bold; color: blue"</p>
    - [ ] c) &lt;p style="font style: italic, font weight: bold; color: blue">Tento odstavec bude modrý.</p>
    - [ ] d) &lt;p text-style="font-style: italic; font-weight: bold; color: blue">Tento odstavec bude modrý.</p>

3. Napište jakými způsoby můžeme deklarovat (zapsat, použít) CSS?

    ```
    do hlavičky
    do tagů: &lt;p style="color: black">Text</p>
    do externího dokumentu, který se potom musí zmínit v html dokumentu
    ```
    
4. Jak se prohlížeč chová v CSS k hodnotám, které nezná?

    ```
    ignoruje je
    ```
 
5. Jak se v CSS tvoří komentáře?

    ```
    /* komentář */
    ```
    
6. Podívejte se důkladně na následující kód:
    ```CSS
    <style type="text/css">
        a {text-decoration: none}
        a:link {color: green}
        a:visited {color: navy}
        a:active {color: black}
        a:hover {color: red; text-decoration: underline}
    </style>
    ```
    Jakou barvu bude mít odkaz po "najetí" myši?

      - [ ] a) modrou
      - [x] b) červenou
      - [ ] c) černou
      - [ ] d) zelenou

### [^](#Overview)CSS II
1. Vyberte správnou hodnotu vlastnosti text-decoration:

    - [x] a) none
    - [ ] b) normal
    - [ ] c) capitalize
    - [ ] d) bold
    - [ ] e) left

2. K čemu se vztahuje nebo co ovlivní následující styl a konkrétně přesně jak? border: `1px solid blue`

    ```
    ohraničí element modrým, 1px, nepřerušovaným ohraničením
    ```

3. Napište text "Toto je nadpis kapitoly" nadpisem nejvyšší úrovně a doplňte CSS kód přímo k tagu a to s těmito vlastnostmi:
    - zarovnání na střed
    - a fontem Tahoma
    
    ```css
    <h1 style="text-align: center; font-family: tahoma">Toto je nadpis kapitoly</h1>
    ```

4. Okraje v CSS obecně mají základní dvě vlastnosti. Které?

    ```
    margin
    padding
    ```

5. Vyberte k jednotlivým vlastnostem stylu FONT správný význam či hodnotu:

    - font-style ```např. kurzíva```
    - font-family ```např. Arial CE```
    - font-size ```např. small```
    - font-weight ```např. tučné```
    - font-variant ```např. kapitálky```

6. Přiřaďte správně význam k následujícím vlastnostem:

    - font variant ```kapitálky```
    - margin ```vnější okraj```
    - padding ```vnitřní okraj```

### [^](#Overview)CSS III
1. Vyberte k jednotlivým vlastnostem stylu SEZNAMY správný význam či hodnotu

    - list-style-type ```např. circle```
    - list-style-image ```obrázková odrážka```
    - list-style-position ```např. inside```
 
 2. Vyberte k jednotlivým vlastnostem stylu BARVY A POZADÍ správný význam či hodnotu:

    - background-image ```obrázek na pozadí```
    - color ```barva písma```
    - background-position ```např. left```
    - background-attachment ```např. fixed```
    - background-repeat ```repeat-x```
    - background-color ```barva pozadí```

3. Vytvořte zjednodušený HTML kód, který bude obsahovat jen odstavec s textem "Toto je červený tučný text." tak, aby byl červený, tučný a to pomocí CSS kódu, který je zapsán v hlavičce dokumentu. V hlavičce nemusí být nic dalšího.

    ```html
    <html>
        <head>
            <style>
                p {
                    font-weight: bold; 
                    color: red;
                }
            </style>
        </head>
        <body>
            <p>Toto je červený tučný text</p>
        </body>
    </html>
    ```
    
4. Vyberte k jednotlivým vlastnostem stylu TEXT správný význam či hodnotu:

    - text-decoration ```např. podtržení```
    - text-align ```např. vpravo```
    - text-transform ```např. všechna velká písmena```
    - text-indent ```odsazení prvního řádku```

### [^](#Overview)HTML + CSS
1. Projděte si zdrojový kód a napište, ve kterých řádcích je chyba nebo kde něco chybí a přesně napište co:

    ```css
    #header {
        background: #FE7B09 url("foto.jpg") repeat-x;
        hieght: 215px;
    }

    #header hl {
        font-size: 30px;
        padding: 22px Opx 5px lOpx;
    }

    theader hl a {
        color: #000;
        text decoration: none;
    }

    #header hl a:hover {
        color: #000;
        text-decoration: underline;
    }

    #header h2 {
        color: #eee;
        font-size: 19 px;
        padding: 0 0 0 llpx;
        line-height: 12px;
    }
    ```
    
    ```
    řádek 3: height: 215px;
    řádek 11: text-decoration: none;
    řádek: 19: font-size: 19px;
    ```
    
2. Ze tří následujících zdrojových kódů varianta A až C vyberte ten, který odpovídá vykreslení webové stránky na obrázku:

    - [x] a) varianta A
    - [ ] b) varianta B
    - [ ] c) varianta C
    
3. Následující zdrojový kód bude vykreslovat jednu z uvedených tří možností. Která to je? (vyberte správnou variantu obrázku)

    - [ ] a) varianta A
    - [ ] b) varianta B
    - [x] c) varianta C


### [^](#Overview)PHP I
1. V PHP se komentář dá vytvořit tímto způsobem:

	- [x] a) # komentář na jeden řádek
	- [ ] b) */ komentář na jeden řádek /*
	- [ ] c) &lt;!-- komentář na více řádků -->
	- [ ] d) &lt;!-- komentář na jeden řádek -->
	- [x] e) // komentář na jeden řádek
	- [x] f) /* komentář na více řádků */

2. PHP můžeme do webových stránek zapsat několika způsoby. Vyberte jen ty správné:
	
	- [ ] a) &lt;%php echo 'Nějaký libovolný text;%>
	- [ ] b) &lt;style language="php"> echo 'Nějaký libovolný text;</style>
	- [x] c) &lt;?echo 'Nějaký libovolný text;?>
	- [ ] d) &lt;?echo 'Nějaký libovolný text;>
	- [ ] e) &lt;?echo 'Nějaký libovolný text;php?>
	- [x] f) &lt;?php echo 'Nějaký libovolný text';?>
	- [x] g) &lt;% echo 'Nějaký libovolný text';%>
	- [x] h) &lt;script language="php"> echo 'Nějaký libovolný text';</script>

3. Syntaxe jazyka je inspirována několika programovacími jazyky. Jakými např.?
	
	- [ ] a) JavaScript
	- [ ] b) C#
	- [ ] c) Oracle
	- [x] d) Java
	- [x] e) C
	- [x] f) Pascal

4. Vyberte správné odpovědi o charakteristice PHP:
	
	- [ ] a) Jedná se o programovací jazyk, běžící na straně klienta.
	- [x] b) Jedná se o interpretovaný jazyk
	- [x] c) Jedná se o programovací jazyk, běžící na straně serveru.
	- [ ] d) Jedná se o kompilovaný jazyk
	- [x] e) Záleží na velikosti písmen
	- [ ] f) Jedná se o programovací jazyk závislý na platformě.

5. PHP podporuje přístup k většině databázových systémů. Které to např. jsou? (vyberte jen správné odpovědi)
	
	- [ ] a) IMAP
	- [x] b) PostgreSQL
	- [x] c) MSSQL
	- [x] d) Oracle
	- [ ] e) FTP
	- [x] f) MySQL
	- [ ] g) SMTP
	- [ ] h) LDAP

6. Co potřebujeme pro editaci a tvorbu PHP souboru? Jaký program, software nebo aplikaci?

	- [ ] a) Jakýkoliv textový editor a operační systém Windows
	- [x] b) Jakýkoliv textový editor.
	- [ ] c) Jakýkoliv textový editor a FTP klienta
	- [ ] d) Speciální textový editor pro tvorbu a editaci PHP
	
7. Co je bezpodmíněčně nutné mít minimálně nainstalováno na počítači, který není připojen k internetu pro běh a testování PHP skriptů?

	- [x] a) Samotné PHP
	- [ ] b) Databázi MySQL
	- [ ] c) FTP klienta, např. FileZilla
	- [ ] d) Operační systém Windows
	- [ ] e) Základní sadu Microsoft Office nebo podobnou
	- [x] f) Webový server, např. Apache

### [^](#Overview)PHP II
1. Spojte správně definice datových typů

	- kladné a záporné celočíselné hodnoty. Rozsah hodnot závisí na platformě, kde PHP běží, obvykle se hodnota pohybuje někde okolo dvou miliard (32-bit signed). `integer`
	- zdroje jsou speciální typy, které vytváří funkce v PHP a které odkazují na vnější zdroje. Pokud např. potřebujeme otevřít soubor(fopen), pak funkce vrací prostředek, který slouží k výběru zadáneho souboru. `resource`
	- objektová proměná může obsahovat různé prvky PHP, např. proměnné, funkce a konstanty. `object`
	- hodnota proměnné může nabývat buď hodnoty TRUE nebo FALSE `boolean`
	- řetězce jsou v PHP kódovány 1 bajtem, takže mohou obsahovat 256 znaků. `string`
	- jedná se o složený typ, který může obsahovat i ostatní datové typy. `array`
	- hodnota s plovoucí desetinnou čárkou. Rozsah tohoto typu proměnné také závisí na platformě, kde PHP běží obvykle je k dispozici 1,8e308 hodnot (64-bit signed). `float`
	- jedná se o zvláštní datový typ, který nemá žádnou hodnotu. Hodí se třeba tehdy, pokud není nějaká proměnná inicializována nebo pokud byla smazána funkcí unset(). Je samozřejmě možné libovolné proměnné přiřadit hodnotu null dodatečně. `null`

2. Který příkaz nebo funkce vypíše v prohlížeči toto: `string(4) "Ahoj"`

	- [ ] a) ani jeden. Jedná se o chybu.
	- [x] b) var_dump
	- [ ] c) print_r
	- [ ] d) echo

3. Co vypíše prohlížeč?
	```php
	<?php
		echo "Tento text obsahuje lomeno / a uvozovky \".";
	?>
	```

	- [ ] a) Tento text obsahuje lomeno / a uvozovky.
	- [ ] b) Tento text obsahuje lomeno a uvozovky ".
	- [x] c) Tento text obsahuje lomeno / a uvozovky ".
	- [ ] d) Tento text obsahuje lomeno // a uvozovky ".
	- [ ] e) Nic. V kódu je chyba.

4. Co je to v PHP řetězec?

	- [ ] a) Jsou to čísla, která spolu navzájem něják souvisí. Proto značíme symbolem řetězu.
	- [x] b) Je to jakýkoliv text včetně čísel nebo zvláštních znaků.
	- [ ] c) Jsou to speciální znaky, které spolu nějakým způsobem souvisí. Proto značíme symbolem řetězu.
	- [ ] d) Je to jakýkoliv text mimo čísel a zvláštních znaků.

5. Přiřaďte k sobě správné definice a slova týkající se textových řetězců v PHP:

	- Zjištění délky řetězce `strlen`
	- Získání části řetězce `substr`
	- Odstranění bilých mezer `trim`
	- Nahrazení textového řetězce `str_replace`
	- Zjištění pozice textu `strpos`

6. Vyberte pouze ty definice a pojmy, které jsou správné:

	- [x] a) **Echo** je příkaz, který je nejčastější metoda pro výpis dat. Dobře postačí na jednoduché datové typy a to čísla a řetězce.
	- [ ] b) Prohlížeč po zadání skriptu **var_dump("Adam")** vypíše boolean(4) "Adam".
	- [ ] c) Prohlížeč po zadání skriptu **var_dump("Adam")** vypíše text(4) "Adam".
	- [x] d) **Print_r** je funkce, která je daleko univerzálnějším řešením, dokáže vypsat jakoukoliv hodnotu a to i tam, kde echo nestačí.
	- [ ] e) Prohlížeč po zadání skriptu **var_dump("Adam")** vypíše integer(4) 'Adam'.
	- [x] f) **Var_dump** je funkce a liší se tím, že kromě samotných dat vypíše i typ, o který se jedná.
	- [x] g) **Var_dump** - této funkci říkáme **diagnostická**. Jejím účelem je především podat maximální informace o nějakých datech.
	- [ ] h) Prohlížeč po zadání skriptu **var_dump("Adam")** vypíše varchar(4) "Adam".
	- [ ] i) **Print_r** - této funkci říkáme **diagnostická**. Jejím účelem je především podat maximální informace o nějakých datech.
	- [x] j) **Print_r** - hodnota se musí vypisovat do závorek, zatímco u **echa** se závorky používat nemusejí, ale mohou.

7. Který ze zdrojových kódů obsahu tzv. syntaci heredoc?

	- [x] a) 
		```php
		<?php
			$text = <<<MMM
			Toto je příklad
			dlouhého řetězce
			na více řádků...
			MMM;
			echo $text;
		?>
		```
	- [ ] b) 
		```php
		<?php
			echo "Tady je příklad použití syntaxe heredoc \" a text dále pokračuje.";
		?>
		```
	- [ ] c) 
		```php
		<?php
			echo "Tady je příklad použití syntaxe heredoc \\" a text dále pokračuje.";
		?>
		```
		
7. Který z následujících zdrojových kódů obsahuje chybu?

	- [ ] a) 
		```php
		<?php
			echo "Tady bude <span style='color: red;'>červený text</span>- <br> Další text na novém řádku.";
		?>
		```
	- [ ] b) 
		```php
		<?php
			echo 'Tady bude <span style="color: red;">červený text</span>- <br> Další text na novém řádku.';
		?>
		```
	- [x] c) 
		```php
		<?php
			echo 'Tady bude <span style='color: red;'>červený text</span>- <br> Další text na novém řádku.';
		?>
		```
