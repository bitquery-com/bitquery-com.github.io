<style>
  header {
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

  .spacer {
    height: 25px;
  }

  .space {
    background-color: #f9f9f9;
  }
</style>

<header>
  
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
  <section class="w-full bg-white">
    <div class="px-8 py-12 mx-auto max-w-7xl">
        <div class="grid grid-cols-2 gap-10 mb-3 md:grid-cols-3 lg:grid-cols-12 lg:gap-20">
            <div class="col-span-3">
                <a href="#_" class="text-xl font-black leading-none text-gray-900 select-none logo">tails.</a>
                <p class="my-4 text-xs leading-normal text-gray-500">
                    Beautifully hand-crafted components to help you build amazing pages.
                </p>
            </div>
            <nav class="col-span-2 md:col-span-1 lg:col-span-2">
                <p class="mb-3 text-xs font-semibold tracking-wider text-gray-400 uppercase">Contact</p>
                <a href="#" class="flex mb-3 text-sm font-medium text-gray-500 transition hover:text-gray-700 md:mb-2 hover:text-primary">Advertising</a>
                <a href="#" class="flex mb-3 text-sm font-medium text-gray-500 transition hover:text-gray-700 md:mb-2 hover:text-primary">Press</a>
                <a href="#" class="flex mb-3 text-sm font-medium text-gray-500 transition hover:text-gray-700 md:mb-2 hover:text-primary">Email</a>
                <a href="#" class="flex mb-3 text-sm font-medium text-gray-500 transition hover:text-gray-700 md:mb-2 hover:text-primary">Partners</a>
                <a href="#" class="flex mb-3 text-sm font-medium text-gray-500 transition hover:text-gray-700 md:mb-2 hover:text-primary">Jobs</a>
            </nav>
        </div>
        <div class="flex flex-col items-start justify-between pt-10 mt-10 border-t border-gray-100 md:flex-row md:items-center">
            <p class="mb-6 text-sm text-left text-gray-600 md:mb-0">© Copyright 2021 Tails. All Rights Reserved.</p>
        </div>
    </div>
  </section>
</footer>
