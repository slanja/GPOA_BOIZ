[<--- Back](https://github.com/slanja/GPOA_BOYZ/blob/main/README.md)

## Overview
- [HTML I](#HTML-I)
- [HTML II](#HTML-II)
- [HTML III](#HTML-III)
- [CSS I](#CSS-I)
- [CSS II](#CSS-II)
- [CSS III](#CSS-III)


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
