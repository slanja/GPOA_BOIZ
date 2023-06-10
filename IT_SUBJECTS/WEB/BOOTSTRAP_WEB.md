[<--- Back](https://github.com/slanja/GPOA_BOYZ/blob/main/README.md)

## Overview
- [BOOTSTRAP WEB I PART I](#BOOTSTRAP_WEB_I_PART_I)

## [^](#Overview)BOOTSTRAP WEB I PART I
<p align="center">
    <img src="images/bootstrap_web_I_part_I.png" width="700px">
</p>

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
            <div id="carouselExampleSlidesOnly" class="carousel slide" data-ride="carousel">
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
