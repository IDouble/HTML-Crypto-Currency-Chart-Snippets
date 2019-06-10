# 💹 HTML Crypto Currency Chart Snippets 💹
💹 Simple HTML Snippets to create Tickers / Charts of Cryptocurrencies with the TradingView API 💹

## [💲 Crypto Currency Ticker 💲](https://ayidouble.github.io/HTML-Crypto-Currency-Chart-Snippets/Ticker)

![Crypto Currency Ticker Cryptocurrencies Chart TradingView API](Images/Crypto-Currency-Ticker.png)

```
<div class="tradingview-widget-container">
  <div class="tradingview-widget-container__widget"></div>
  <div class="tradingview-widget-copyright"><a href="https://www.tradingview.com" rel="noopener" target="_blank"><span class="blue-text">Ticker Tape</span></a> by TradingView</div>
  <script type="text/javascript" src="https://s3.tradingview.com/external-embedding/embed-widget-ticker-tape.js" async>
  {
  "symbols": [
    {
      "description": "",
      "proName": "COINBASE:BTCUSD"
    },
    {
      "description": "",
      "proName": "COINBASE:ETHUSD"
    },
    {
      "description": "",
      "proName": "BITFINEX:IOTUSD"
    }
  ],
  "colorTheme": "dark",
  "isTransparent": false,
  "displayMode": "adaptive",
  "locale": "en"
}
  </script>
</div>
```
