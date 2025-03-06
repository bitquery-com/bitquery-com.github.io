<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Ponomar&display=swap" rel="stylesheet">
<style>  
  header {
    display: flex;
    align-items: center;
    justify-content: center;
    color: #36364c;
    height: 96px;
    background-color: #f9f9f9;
  }
  
  .ad-large {
    text-align: center;
    width: 100%;
    padding: 70px 0;
    font-size: large;
    font-weight: bold;
    border: 3px solid #f9f9f9;
    border-radius: 7px;
    color: #ececec;
  }

  .ad-small {
    text-align: center;
    width: 100%;
    padding: 25px 0;
    font-size: large;
    font-weight: bold;
    border: 3px solid #f9f9f9;
    border-radius: 7px;
    color: #ececec;
  }

  .footer-section {
    padding-top: 70px;
  }

  .spacer {
    height: 25px;
  }

  .space {
    background-color: #f9f9f9;
  }

  .logo {
    font-family: "Ponomar", system-ui;
    font-weight: 400;
    font-style: normal;
  }

  .logo-header {
    font-size: 100px;
  }
</style>

<header>
  <p class="logo">::::bitquery</p>
</header>

<script defer src="https://www.livecoinwatch.com/static/lcw-widget.js"></script>
<div class="livecoinwatch-widget-5 space" lcw-base="USD" lcw-color-tx="#abb8c3" lcw-marquee-1="coins" lcw-marquee-2="movers" lcw-marquee-items="10" ></div>

<div class="spacer"></div>

<div class="ad-large">AD SPACE</div>

<div class="spacer"></div>

<div style="height: 500px">
  <div class="space" style="width: 49%; height: 100%; float: left;">
    <div class="tradingview-widget-container">
      <div class="tradingview-widget-container__widget"></div>
      <script type="text/javascript" src="https://s3.tradingview.com/external-embedding/embed-widget-events.js" async>
      {
        "width": "100%",
        "height": "100%",
        "colorTheme": "light",
        "isTransparent": true,
        "locale": "en",
        "importanceFilter": "0,1",
        "countryFilter": "ar,au,br,ca,cn,fr,de,in,id,it,jp,kr,mx,ru,sa,za,tr,gb,us,eu"
      }
      </script>
    </div>
  </div>

  <div class="space" style="width: 49%; height: 100%; float: right;">
    <div class="tradingview-widget-container">
      <div class="tradingview-widget-container__widget"></div>
      <script type="text/javascript" src="https://s3.tradingview.com/external-embedding/embed-widget-timeline.js" async>
      {
        "feedMode": "all_symbols",
        "isTransparent": true,
        "displayMode": "regular",
        "width": "100%",
        "height": "100%",
        "colorTheme": "light",
        "locale": "en"
      }
      </script>
    </div>
  </div>
</div>

<div class="spacer"></div>

<div class="ad-small">AD SPACE</div>

<div class="spacer"></div>

<div class="tradingview-widget-container space">
  <div class="tradingview-widget-container__widget"></div>
  <script type="text/javascript" src="https://s3.tradingview.com/external-embedding/embed-widget-advanced-chart.js" async>
  {
  "width": "100%",
  "height": "610",
  "symbol": "MARKETSCOM:BITCOIN",
  "interval": "D",
  "timezone": "exchange",
  "theme": "light",
  "style": "2",
  "locale": "en",
  "backgroundColor": "rgba(255, 255, 255, 1)",
  "withdateranges": true,
  "allow_symbol_change": true,
  "compareSymbols": [
    {
      "symbol": "MARKETSCOM:ETHEREUM",
      "position": "SameScale"
    }
  ],
  "details": true,
  "calendar": false,
  "support_host": "https://www.tradingview.com"
}
  </script>
</div>

<div class="spacer"></div>

<div class="ad-small">AD SPACE</div>

<div class="spacer"></div>

<div class="tradingview-widget-container space">
  <div class="tradingview-widget-container__widget"></div>
  <script type="text/javascript" src="https://s3.tradingview.com/external-embedding/embed-widget-screener.js" async>
  {
    "width": "100%",
    "height": 550,
    "defaultColumn": "overview",
    "screener_type": "crypto_mkt",
    "displayCurrency": "USD",
    "colorTheme": "light",
    "locale": "en"
  }
  </script>
</div>

<footer>
  <section class="footer-section">
    <div>
        <div>
            <nav>
                <p>Contact</p>
                <a href="mailto:contact@bitquery.com">contact@bitquery.com</a>
            </nav>
        </div>
        <div style="text-align: center;">
            <p>© Copyright 2025. All Rights Reserved.</p>
        </div>
    </div>
  </section>
</footer>
