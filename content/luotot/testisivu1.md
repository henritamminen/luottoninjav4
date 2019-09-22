---
title: "Testisivu1"
date: 2019-09-22T11:33:50+03:00
draft: true
---

  <head>
    <link
      rel="stylesheet"
      href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
    <link
      href="http://maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css"
      rel="stylesheet"
    />
    <style>
      body {
        margin: 0 auto;
      }
      .mainContainer {
        border: 1px solid #ccc;
        padding: 25px;
        border-radius: 3px;
        box-shadow: 3px 3px 5px 0 #ccc;
      }
      .imgWithrating {
        /* background-color: red; */
      }
      .vertical {
        border-right: 1px solid #ccc;
        height: 100%;
      }
      .btn {
        background-color: rgb(144, 190, 125) !important;
        color: #fff;
        border-color: none !important;
        outline-color: none !important;
        border: 1px solid transparent;
      }
      .btn:hover {
        border-color: none !important;
        outline-color: none !important;
        border: 1px solid transparent;
      }
      .rate {
        float: left;
        display: flex !important;
        flex-direction: row;
        align-content: center !important;
        align-items: center !important;
        padding: 0 10px;
        width: 100%;
      }
      .rate:not(:checked) > input {
        position: absolute;
        top: -9999px;
      }
      .rate:not(:checked) > label {
        float: right;
        width: 1em;
        overflow: hidden;
        white-space: nowrap;
        cursor: pointer;
        font-size: 30px;
        color: #ccc;
      }
      .rate:not(:checked) > label:before {
        content: "★";
      }
      .rate > input:checked ~ label {
        color: #ffc700;
      }
      .rate:not(:checked) > label:hover,
      .rate:not(:checked) > label:hover ~ label {
        color: #deb217;
      }
      .rate > input:checked + label:hover,
      .rate > input:checked + label:hover ~ label,
      .rate > input:checked ~ label:hover,
      .rate > input:checked ~ label:hover ~ label,
      .rate > label:hover ~ input:checked ~ label {
        color: #c59b08;
      }
    </style>
  </head>
  <body>
    <div class="container mainContainer">
      <div class="row">
        <div class="col-md-2 col-sm-12 vertical">
          <img src="https://laina.ninja/wp-content/uploads/2019/09/1539686250.jpeg" class="img-fluid" loading="lazy">
          <div class="rate text-center">
            <input type="radio" id="star1" name="rate" value="1">
            <label for="star1" class="rateChecked" title="text"></label>
            <input type="radio" id="star2" name="rate" value="2">
            <label for="star2" class="rateChecked" title="text"></label>
            <input type="radio" id="star3" name="rate" value="3">
            <label for="star3" class="rateChecked" title="text"></label>
            <input type="radio" id="star4" name="rate" value="4">
            <label for="star4" class="rateChecked" title="text"></label>
            <input type="radio" id="star5" name="rate" value="5">
            <label for="star5" class="rateNotChecked" title="text"></label>
          </div>
        </div>
        <div class="col-md-2 col-sm-6 vertical"><strong>1.000 - 60.000 €</strong>
          <p>Lainamäärä</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>-</strong>
          <p>Korko</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>23 vuotta</strong>
          <p>Ikäraja</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>12 - 180 kk</strong>
          <p>Takaisinmaksuaika</p>
        </div>
        <div class="col-md-2 col-sm-12">
            <a href="https://online.adservicemedia.dk/cgi-bin/click.pl?pid=24200&amp;cid=8672" rel="nofollow">
          <button class="btn btn-primary btn-sm btn-block">
            Hae
            <i class="fa fa-check" aria-hidden="true"></i>
          </button>
                </a>
        </div>
      </div>
      <hr>
      <div class="row">
        <div class="col-md-12 smallText">Lainaesimerkki: Lainasummalle 10000€, kun takaisinmaksuaika on 5 vuotta, tilinhoitomaksu 5€, avausmaksu 149€ ja esimerkkikorko 9,5%. Takaisinmaksettava summa on tällöin 13050€, eli 217,50 €/kk.</div>
      </div>
    </div>

<div class="container mainContainer">
      <div class="row">
        <div class="col-md-2 col-sm-12 vertical">
          <img src="https://laina.ninja/wp-content/uploads/2019/09/1515141241.png" class="img-fluid" loading="lazy">
          <div class="rate text-center">
            <input type="radio" id="star1" name="rate" value="1">
            <label for="star1" class="rateChecked" title="text"></label>
            <input type="radio" id="star2" name="rate" value="2">
            <label for="star2" class="rateChecked" title="text"></label>
            <input type="radio" id="star3" name="rate" value="3">
            <label for="star3" class="rateChecked" title="text"></label>
            <input type="radio" id="star4" name="rate" value="4">
            <label for="star4" class="rateChecked" title="text"></label>
            <input type="radio" id="star5" name="rate" value="5">
            <label for="star5" class="rateNotChecked" title="text"></label>
          </div>
        </div>
        <div class="col-md-2 col-sm-6 vertical"><strong>100 - 2.000 €</strong>
          <p>Lainamäärä</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>23,88 - 72 %</strong>
          <p>Korko</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>20 vuotta</strong>
          <p>Ikäraja</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>3 - 30 kk</strong>
          <p>Takaisinmaksuaika</p>
        </div>
        <div class="col-md-2 col-sm-12">
            <a href="https://online.adservicemedia.dk/cgi-bin/click.pl?pid=24200&amp;cid=4970" rel="nofollow">
          <button class="btn btn-primary btn-sm btn-block">
            Hae
            <i class="fa fa-check" aria-hidden="true"></i>
          </button>
                </a>
        </div>
      </div>
      <hr>
      <div class="row">
        <div class="col-md-12 smallText">Lainaesimerkki: 1500 euron nostolle todellinen kulut huomioiva vuosikorko on 56,23 % ja luoton arvioitu kokonaiskustannus 1894 €.</div>
      </div>
    </div>
<div class="container mainContainer">
      <div class="row">
        <div class="col-md-2 col-sm-12 vertical">
          <img src="https://laina.ninja/wp-content/uploads/2019/09/1487169116.jpg" class="img-fluid" loading="lazy">
          <div class="rate text-center">
            <input type="radio" id="star1" name="rate" value="1">
            <label for="star1" class="rateChecked" title="text"></label>
            <input type="radio" id="star2" name="rate" value="2">
            <label for="star2" class="rateChecked" title="text"></label>
            <input type="radio" id="star3" name="rate" value="3">
            <label for="star3" class="rateChecked" title="text"></label>
            <input type="radio" id="star4" name="rate" value="4">
            <label for="star4" class="rateChecked" title="text"></label>
            <input type="radio" id="star5" name="rate" value="5">
            <label for="star5" class="rateNotChecked" title="text"></label>
          </div>
        </div>
        <div class="col-md-2 col-sm-6 vertical"><strong>100 - 2.000 €</strong>
          <p>Lainamäärä</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>19,90 %</strong>
          <p>Korko</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>18 vuotta</strong>
          <p>Ikäraja</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>3 - 30 kk</strong>
          <p>Takaisinmaksuaika</p>
        </div>
        <div class="col-md-2 col-sm-12">
            <a href="https://online.adservicemedia.dk/cgi-bin/click.pl?pid=24200&amp;cid=4969" rel="nofollow">
          <button class="btn btn-primary btn-sm btn-block">
            Hae
            <i class="fa fa-check" aria-hidden="true"></i>
          </button>
                </a>
        </div>
      </div>
      <hr>
      <div class="row">
        <div class="col-md-12 smallText">Lainaesimerkki: Luottotyyppi: 2000 € jatkuva laina. Vuotuinen nimelliskorko 19,9 %. Lainanhoitokulu: 0,01 % / päivä ja korkeintaan 150 € / vuosi. Todellinen vuosikorko: 29,6 %.</div>
      </div>
    </div>

<div class="container mainContainer">
      <div class="row">
        <div class="col-md-2 col-sm-12 vertical">
          <img src="https://laina.ninja/wp-content/uploads/2019/09/1567078490.png" class="img-fluid" loading="lazy">
          <div class="rate text-center">
            <input type="radio" id="star1" name="rate" value="1">
            <label for="star1" class="rateChecked" title="text"></label>
            <input type="radio" id="star2" name="rate" value="2">
            <label for="star2" class="rateChecked" title="text"></label>
            <input type="radio" id="star3" name="rate" value="3">
            <label for="star3" class="rateChecked" title="text"></label>
            <input type="radio" id="star4" name="rate" value="4">
            <label for="star4" class="rateChecked" title="text"></label>
            <input type="radio" id="star5" name="rate" value="5">
            <label for="star5" class="rateNotChecked" title="text"></label>
          </div>
        </div>
        <div class="col-md-2 col-sm-6 vertical"><strong>100 - 2.000 €</strong>
          <p>Lainamäärä</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>1,99 %</strong>
          <p>Korko</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>20 vuotta</strong>
          <p>Ikäraja</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>3 - 30 kk</strong>
          <p>Takaisinmaksuaika</p>
        </div>
        <div class="col-md-2 col-sm-12">
            <a href="https://online.adservicemedia.dk/cgi-bin/click.pl?pid=24200&amp;cid=6230" rel="nofollow">
          <button class="btn btn-primary btn-sm btn-block">
            Hae
            <i class="fa fa-check" aria-hidden="true"></i>
          </button>
                </a>
        </div>
      </div>
      <hr>
      <div class="row">
        <div class="col-md-12 smallText">Lainaesimerkki: 1500 euron nostolle todellinen kulut huomioiva vuosikorko on 56,23 % ja luoton arvioitu kokonaiskustannus 1894 € mikäli asiakas nostaa kerralla 1500 € ja maksaa sen takaisin 12 erässä kuukausittain.</div>
      </div>
    </div>
<div class="container mainContainer">
      <div class="row">
        <div class="col-md-2 col-sm-12 vertical">
          <img src="https://laina.ninja/wp-content/uploads/2019/09/ferratum.png" class="img-fluid" loading="lazy">
          <div class="rate text-center">
            <input type="radio" id="star1" name="rate" value="1">
            <label for="star1" class="rateChecked" title="text"></label>
            <input type="radio" id="star2" name="rate" value="2">
            <label for="star2" class="rateChecked" title="text"></label>
            <input type="radio" id="star3" name="rate" value="3">
            <label for="star3" class="rateChecked" title="text"></label>
            <input type="radio" id="star4" name="rate" value="4">
            <label for="star4" class="rateChecked" title="text"></label>
            <input type="radio" id="star5" name="rate" value="5">
            <label for="star5" class="rateNotChecked" title="text"></label>
          </div>
        </div>
        <div class="col-md-2 col-sm-6 vertical"><strong>100 - 2000 €</strong>
          <p>Lainamäärä</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>20 %</strong>
          <p>Korko</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>21 vuotta</strong>
          <p>Ikäraja</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>3 - 54 kk</strong>
          <p>Takaisinmaksuaika</p>
        </div>
        <div class="col-md-2 col-sm-12">
            <a href="https://online.adservicemedia.dk/cgi-bin/click.pl?pid=24200&amp;cid=1154" rel="nofollow">
          <button class="btn btn-primary btn-sm btn-block">
            Hae
            <i class="fa fa-check" aria-hidden="true"></i>
          </button>
                </a>
        </div>
      </div>
      <hr>
      <div class="row">
        <div class="col-md-12 smallText">Hinnasto: nimellinen vuosikorko 20,00 % ja todellinen vuosikorko 21,94 %. Luoton arvioitu kokonaiskustannus on 2216,65 € olettaen, että asiakas nostaa kerralla 2000 € ja maksaa sen takaisin 12 kk-erässä.</div>
      </div>
    </div>
<div class="container mainContainer">
      <div class="row">
        <div class="col-md-2 col-sm-12 vertical">
          <img src="https://laina.ninja/wp-content/uploads/2019/09/1435838170.jpeg" class="img-fluid" loading="lazy">
          <div class="rate text-center">
            <input type="radio" id="star1" name="rate" value="1">
            <label for="star1" class="rateChecked" title="text"></label>
            <input type="radio" id="star2" name="rate" value="2">
            <label for="star2" class="rateChecked" title="text"></label>
            <input type="radio" id="star3" name="rate" value="3">
            <label for="star3" class="rateChecked" title="text"></label>
            <input type="radio" id="star4" name="rate" value="4">
            <label for="star4" class="rateChecked" title="text"></label>
            <input type="radio" id="star5" name="rate" value="5">
            <label for="star5" class="rateNotChecked" title="text"></label>
          </div>
        </div>
        <div class="col-md-2 col-sm-6 vertical"><strong>100 - 60.000 €</strong>
          <p>Lainamäärä</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>4,19 - 20 %</strong>
          <p>Korko</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>18 vuotta</strong>
          <p>Ikäraja</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>12 - 180 kk</strong>
          <p>Takaisinmaksuaika</p>
        </div>
        <div class="col-md-2 col-sm-12">
            <a href="https://online.adservicemedia.dk/cgi-bin/click.pl?pid=24200&amp;cid=3509" rel="nofollow">
          <button class="btn btn-primary btn-sm btn-block">
            Hae
            <i class="fa fa-check" aria-hidden="true"></i>
          </button>
                </a>
        </div>
      </div>
      <hr>
      <div class="row">
        <div class="col-md-12 smallText">Lainaesimerkki: Kuluttajansuojalain mukainen todellinen vuosikorko on 6,26% laskettuna tyypilliselle lainasummalle 10000€, kun takaisinmaksuaika on 5 vuotta, tilinhoitomaksu 5€, avausmaksu 0€ ja esimerkkikorko 5,0%. Takaisinmaksettava summa on tällöin 11 623€, eli 193,71 €/kk.</div>
      </div>
    </div>

<div class="container mainContainer">
      <div class="row">
        <div class="col-md-2 col-sm-12 vertical">
          <img src="https://laina.ninja/wp-content/uploads/2019/09/1561634715.png" class="img-fluid" loading="lazy">
          <div class="rate text-center">
            <input type="radio" id="star1" name="rate" value="1">
            <label for="star1" class="rateChecked" title="text"></label>
            <input type="radio" id="star2" name="rate" value="2">
            <label for="star2" class="rateChecked" title="text"></label>
            <input type="radio" id="star3" name="rate" value="3">
            <label for="star3" class="rateChecked" title="text"></label>
            <input type="radio" id="star4" name="rate" value="4">
            <label for="star4" class="rateChecked" title="text"></label>
            <input type="radio" id="star5" name="rate" value="5">
            <label for="star5" class="rateNotChecked" title="text"></label>
          </div>
        </div>
        <div class="col-md-2 col-sm-6 vertical"><strong>100 - 60.000 €</strong>
          <p>Lainamäärä</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>-</strong>
          <p>Korko</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>20 vuotta</strong>
          <p>Ikäraja</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>12 - 180 kk</strong>
          <p>Takaisinmaksuaika</p>
        </div>
        <div class="col-md-2 col-sm-12">
            <a href="https://online.adservicemedia.dk/cgi-bin/click.pl?pid=24200&amp;cid=9217" rel="nofollow">
          <button class="btn btn-primary btn-sm btn-block">
            Hae
            <i class="fa fa-check" aria-hidden="true"></i>
          </button>
                </a>
        </div>
      </div>
      <hr>
      <div class="row">
        <div class="col-md-12 smallText">Lainaesimerkki: kuluttajansuojalain mukainen todellinen vuosikorko on 11,76% laskettuna tyypilliselle lainasummalle 10000€, kun takaisinmaksuaika on 5 vuotta, tilinhoitomaksu 5€, avausmaksu 149€ ja esimerkkikorko 9,5%. Takaisinmaksettava summa on tällöin 13050€, eli 217,50 €/kk.</div>
      </div>
    </div>

<div class="container mainContainer">
      <div class="row">
        <div class="col-md-2 col-sm-12 vertical">
          <img src="https://laina.ninja/wp-content/uploads/2019/09/1554715177.png" class="img-fluid" loading="lazy">
          <div class="rate text-center">
            <input type="radio" id="star1" name="rate" value="1">
            <label for="star1" class="rateChecked" title="text"></label>
            <input type="radio" id="star2" name="rate" value="2">
            <label for="star2" class="rateChecked" title="text"></label>
            <input type="radio" id="star3" name="rate" value="3">
            <label for="star3" class="rateChecked" title="text"></label>
            <input type="radio" id="star4" name="rate" value="4">
            <label for="star4" class="rateChecked" title="text"></label>
            <input type="radio" id="star5" name="rate" value="5">
            <label for="star5" class="rateNotChecked" title="text"></label>
          </div>
        </div>
        <div class="col-md-2 col-sm-6 vertical"><strong>500 - 60.000 €</strong>
          <p>Lainamäärä</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>4,90 %</strong>
          <p>Korko</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>18 vuotta</strong>
          <p>Ikäraja</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>1 - 180 kk</strong>
          <p>Takaisinmaksuaika</p>
        </div>
        <div class="col-md-2 col-sm-12">
            <a href="https://online.adservicemedia.dk/cgi-bin/click.pl?pid=24200&amp;cid=9389" rel="nofollow">
          <button class="btn btn-primary btn-sm btn-block">
            Hae
            <i class="fa fa-check" aria-hidden="true"></i>
          </button>
                </a>
        </div>
      </div>
      <hr>
      <div class="row">
        <div class="col-md-12 smallText">Lainaesimerkki: Lainasumma 5000€, laina-aika 48kk, korko 8%, avausmaksu 150€, tilinhoitomaksu 8€. Kuukausierä: 133,73€, lainan kustannukset 1418,87, maksettavaa tällöin yhteensä 6418,87€, todellinen vuosikorko näin ollen 13,62%.</div>
      </div>
    </div>

<div class="container mainContainer">
      <div class="row">
        <div class="col-md-2 col-sm-12 vertical">
          <img src="https://laina.ninja/wp-content/uploads/2019/09/1547818536.jpeg" class="img-fluid" loading="lazy">
          <div class="rate text-center">
            <input type="radio" id="star1" name="rate" value="1">
            <label for="star1" class="rateChecked" title="text"></label>
            <input type="radio" id="star2" name="rate" value="2">
            <label for="star2" class="rateChecked" title="text"></label>
            <input type="radio" id="star3" name="rate" value="3">
            <label for="star3" class="rateChecked" title="text"></label>
            <input type="radio" id="star4" name="rate" value="4">
            <label for="star4" class="rateChecked" title="text"></label>
            <input type="radio" id="star5" name="rate" value="5">
            <label for="star5" class="rateNotChecked" title="text"></label>
          </div>
        </div>
        <div class="col-md-2 col-sm-6 vertical"><strong>500 - 50.000 €</strong>
          <p>Lainamäärä</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>-</strong>
          <p>Korko</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>18 vuotta</strong>
          <p>Ikäraja</p>
        </div>
        <div class="col-md-2 col-sm-6 vertical">
          <strong>1 - 180 kk</strong>
          <p>Takaisinmaksuaika</p>
        </div>
        <div class="col-md-2 col-sm-12">
            <a href="https://online.adservicemedia.dk/cgi-bin/click.pl?pid=24200&amp;cid=8286" rel="nofollow">
          <button class="btn btn-primary btn-sm btn-block">
            Hae
            <i class="fa fa-check" aria-hidden="true"></i>
          </button>
                </a>
        </div>
      </div>
      <hr>
      <div class="row">
        <div class="col-md-12 smallText">Lainaesimerkki: Lainasumma 5000€, laina-aika 48kk, korko 8%, avausmaksu 150€, tilinhoitomaksu 8€. Kuukausierä: 133,73€, lainan kustannukset 1418,87, maksettavaa tällöin yhteensä 6418,87€, todellinen vuosikorko näin ollen 13,62%.</div>
      </div>
    </div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.bundle.min.js"></script>
  </body>
</html>


