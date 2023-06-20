[<--- Back](https://github.com/slanja/GPOA_BOYZ/blob/main/README.md)

## Overview
- [BOOTSTRAP WEB I PART I](#BOOTSTRAP_WEB_I_PART_I)

## [^](#Overview)BOOTSTRAP WEB I PART I
<p align="center">
    <img src="images/bootstrap_web_I_part_I.png" width="700px">
</p>

<details>
<summary>ZADANI</summary>
    <div>
      <div>
        <div>
          <p>
            <b>Vytvořte webové stránky dle následujícího zadání:</b>
          </p>
          <p></p>
          <ol>
            <li>celý web bude obsahovat 4 jednotlivé webové stránky: <br>
            </li>
            <ol>
              <li>Titulní strana</li>
              <li>Reference</li>
              <li>Přesměrování</li>
              <li>a Kontakt</li>
            </ol>
            <li>v této části úkolu vytvoříte pouze první z uvedených stránek - index.html.</li>
            <li>web bude uložen ve vámi vytvořeném adresáři (složce) ve vašem FTP prostoru (název je libovolný) a veškeré další soubory či podsložky budou v tomto adresáři. Konkrétní názvy souborů či složek tvořící tyto stránky si zvolte libovolně dle vlastního uvážení, <b>ale jejich názvy musí odpovídat syntaxi HTML</b>. <br>
            </li>
            <li>pokud není zadáno jinak, použijte původní defaultní barvy, fonty či další nastavení prvků či atributů frameworku Bootstrap verze 4, který bude na web napojen</li>
            <li>nejprve si vytvořte Titulní stranu, kterou vytvořte tak, aby byla ve verzi HTML 5 a byla "napojena" na framework Bootstrap, verze 4. Titulní strana tvoří startovací stránku webu.</li>
            <li>doplňte metatag "title" vaším jménem a příjmením. Ostatní metatagy nemusíte vyplňovat, pokud není dále stanoveno jinak.</li>
            <li>web bude také "napojen" na externí stylopis, do kterého budou vkládány všechny CSS styly. Jeho název a umístění si zvolte sami</li>
            <li>metatag pro favikonu upravte tak, aby web načítal jako favikonu <a href="https://moodle.gpoa.cz/pluginfile.php/9721/mod_assign/intro/favikona.ico" target="_blank">tento soubor (klikněte pro stažení)</a>: <br>
              <br>
            </li>
            <li>dále vytvořte základní "obal" stránky za pomoci "kontejneru" (container). Do tohoto "obalu" stránky budete vkládat vše, co bude v hlavní obsahové části webu</li>
            <li>jako první vytvořte v horní části "jumbotron". V něm bude nadpisem nejvyšší úrovně vytvořen text "Vaše jméno a Příjmení" a dále normálním odstavcem text "Samostatný úkol na známky". Dále bude mít nastaven vnější <b>horní</b> okraj na 15px: <br>
              <br>
            </li>
            <li>do kontejneru nyní vložte menu. Využijte k tomu "Navbar" (verze Colored Navbar) - tmavou variantu, konkrétně s pozadím "bg-dark": <br>
            </li>
            <li>jednotlivé položky menu budou: <br>
            </li>
            <ol>
              <li>Titulní strana</li>
              <li>Reference</li>
              <li>Přesměrování</li>
              <li>Kontakt</li>
            </ol>
            <li>položky menu budou směřovat na soubory, které si následně budete vytvářet. Jejich název zvolte dle vlastního uvážení (jak již bylo uvedeno).&nbsp; Nyní bude funkční pouze startovací stránka webu. Ostatní zatím ne.</li>
            <li>dále vytvořte slider (carousel), který bude mít tyto tři obrázky - <a href="https://moodle.gpoa.cz/pluginfile.php/9721/mod_assign/intro/slider1.jpg" target="_blank">slider1</a>, <a href="https://moodle.gpoa.cz/pluginfile.php/9721/mod_assign/intro/slider2.jpg" target="_blank">slider2</a> a <a href="https://moodle.gpoa.cz/pluginfile.php/9721/mod_assign/intro/slider3.jpg" target="_blank">slider3</a>. Uložte si je do samostatné složky (název dle vlastního uvážení) <br>
              <br>
            </li>
            <li>jednotlivé snímky slideru (carouselu) nebudou mít žádné další popisky ani podtexty (tedy použijte základní - defaultní typ)</li>
            <li>dále vytvořte hlavní část (obsah) webu, který bude rozdělen na dvě stejné poloviny. Levá polovina bude mít nadpis druhé nejvyšší úrovně "O nás" a pravá bude mít také nadpis druhé nejvyšší úrovně "Nabízíme". Do obou těchto polovin vložte shodně text vygenerovaný Lorem Ipsum generátorem a to s parametry - 3 odstavce, 20-30 slov z českého zásobníku slov: <br>
              <br>
            </li>
            <li>dále vytvořte zápatí a to za pomoci "row" a "col" (šířka přes celý kontejner). Barva pozadí této části bude "bg-info". Text bude vystředěn za pomoci třídy frameworku a bude vytvořen nadpisem 4. úrovně a to vaše jméno, příjmení a rok: <br>
              <br>
              <br>
            </li>
            <li>nyní uvedenou webovou stránku uložte do vašeho FTP prostoru do libovolného nového adresáře <b>(jak již bylo zmíněno)</b>. <b>Adresu (odkaz) na tento web vložte jako výsledek vaší práce zde do systému Moodle níže jako aktivní "klikatelný" odkaz, který se otevře v novém okně.</b> Stránka by měla vypadat ve výsledku takto: <br>
              <br>
            </li>
            <li>
              <b>Po odevzdání (a uložení) si vyzkoušejte kliknutím, že tento odkaz funguje!</b>
            </li>
          </ol>
          <p></p>
        </div>
      </div>
    </div>
</details>



HTML
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>[Jméno Příjmení]</title>
        <link rel="icon" href="images/favicon.ico" type="image/x-icon"/>
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="container">
            <!--JUMBOTRON-->
            <div class="jumbotron">
              <h1 class="display-4">[Jméno Příjmení]</h1>
              <p class="lead">Samostatný úkol na známky</p>
            </div>

            <!--NAV-->
            <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
              <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav">
                  <a class="nav-link active" href="index.html">Titulní strana<span class="sr-only">(current)</span></a>
                  <a class="nav-link" href="reference.html">Reference</a>
                  <a class="nav-link" href="redirect.html">Přesměrování</a>
                  <a class="nav-link" href="contact.html">Kontakt</a>
                </div>
              </div>
            </nav>

            <!--CAROUSEL-->
            <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
              <ol class="carousel-indicators">
                <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
                <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
              </ol>
              <div class="carousel-inner">
                <div class="carousel-item active">
                  <img src="images/carousel/slide_1.jpg" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                  <img src="images/carousel/slide_2.jpg" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                  <img src="images/carousel/slide_3.jpg" class="d-block w-100" alt="...">
                </div>
              </div>
              <button class="carousel-control-prev" type="button" data-target="#carouselExampleIndicators" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
              </button>
              <button class="carousel-control-next" type="button" data-target="#carouselExampleIndicators" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
              </button>
            </div>

            <!--MAIN PART-->
            <div class="row">
                <div class="col-sm-6">
                    <h2>O nás</h2>

                    <p>Lákamí vůněhulás úmyval rohlivý jednovod lek škočajine Ra alehlínům rohlý ští. Lek klehrátce dopicí alehradi ma ční mělý mocipáda Měsí zavěď pánová. Sudbale je.</p>

                    <p>Prozený hal je úmysl čepicí dobrajin lák jít já Umrabus přestavý. Rojednova ačít starásný kráčepres.</p>

                    <p>A z čilo pa leda váto prozzásko hane marabubej napný věný. Umí bý dobrajen ří onověď jít burdíčkov měsíčníkl magne záprajen ční. Hafanadop bájen kráčepres ří.</p>           
                </div>
                <div class="col-sm-6">
                    <h2>Nabízíme</h2>

                    <p>Lákamí vůněhulás úmyval rohlivý jednovod lek škočajine Ra alehlínům rohlý ští. Lek klehrátce dopicí alehradi ma ční mělý mocipáda Měsí zavěď pánová. Sudbale je.</p>

                    <p>Prozený hal je úmysl čepicí dobrajin lák jít já Umrabus přestavý. Rojednova ačít starásný kráčepres.</p>

                    <p>A z čilo pa leda váto prozzásko hane marabubej napný věný. Umí bý dobrajen ří onověď jít burdíčkov měsíčníkl magne záprajen ční. Hafanadop bájen kráčepres ří.</p>
                </div>
            </div>

            <!--FOOTER-->
            <div class="row">
                <div class="col-sm-12 bg-info text-center">
                    <h4>[Jméno Příjmení] [Rok]</h4>
                </div>
            </div>
        </div>

        <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-Fy6S3B9q64WdZWQUiU+q4/2Lc9npb8tCaSX9FK7E8HnRr0Jz8D6OP9dO5Vg3Q9ct" crossorigin="anonymous"></script>
    </body>
</html>
```

CSS
```css
.jumbotron {
    margin-top: 15px;
}
```

FILES (carousel images and favicon)
```
https://www.mediafire.com/folder/lwjm36eu2ozjd/images
```
