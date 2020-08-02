# exchage-rates-getter

We are using this tool for getting crypto exchange rates for our day instagram stories

## How to use 

1. Configure Env 

```dotenv
API_URL_LIVE="http://api.coinlayer.com/api/live?access_key=<put your secret here>" # dont forget to insert your secret key
API_URL_HISTORY="http://api.coinlayer.com/api/%s?access_key=<put your secret here>" # dont forget to insert your secret key
CURRENCIES="BTC,ETH,BCH,BTG,XLM,TRX,XRP" # currencies to process
```

2. Compile

`go build`

3. Run

`./exchange-rates-to-image`

4. Rate will be in TXT fil `rates-YYYY-MM-DD.txt`
