## PLEASE CAREFULLY READ INFORMATION BEFORE USE



## Bin-BOT v0.5 Early Access


Official webpage for the bot app is https://github.com/dachu02/Bin-BOT-Early-Access/
Bin-BOT app in still in development phase, but I do my best to make it work without any issue and errors, but if any occur, please let me know via github page.
I'm not a corporate, I'm not a company - I'm crypto enthusiast, who knows Python a little and didn't want to pay $$ for other both available on the market ;)

If you are happy about the app, and you earn some money you can buy me a coffee or send me a tip to:

ETH Wallet

BTC Wallet

Binance Account via Pay tab in you Binance App (no fee):
my ID: 73860889

If you don't have Binance account yet, you can use my referral and support me that way:)

https://accounts.binance.com/pl/register?ref=23777960   or use ref number during registration 23777960


## Bin-BOT - virus scan report

App is for sure virus free but sometimes Windows Defender reports it as Malware, its false positive and for the final version I''l try to request false positive removal.
For now you can upload the app to the Kacpersky Online check (https://opentip.kaspersky.com/) to be sure that file is free of viruses.



## APP features

1. Auto trading on SPOT market on Binance.com - current version supports 3 predefined coin pairs (BTCUSDT,ETHUSDT,BNBUSDT) and max 3 open orders per pair. Buy and Sell is basing on the basic strategies which are using MACD and EMA indicators. Currently, there is a support for scalping and mid term strategy.
2. Manual trading on predefined pairs (buy and sell)
3. Statistics of past trades via bot or manual trade
4. Manual DCA for open orders
5. Checking current Binance account balance
6. Trailing stop-loss feature for orders placed by bot - you can define your thresholds
7. TakeProfit and StopLoss with predefined thresholds and possibility to disable them.
8. Windows notification when new buy or sell order is placed
9. Add support for other base assets different that USDT (eg. USDC, BUSD)

Currently, I'm still working on:
- users custom strategies
- automated DCA for the bot
- nicer look of the app :)

## APP configuration

Using config.ini you can change basic settings of the app and provide your API KEYs
Below there is a list of parameters with description (all values should be provided without ' ' or " "):

- akey - api key from Binance, instruction how generate key on https://github.com/dachu02
- skey - secret key from Binance, instruction how generate key on https://github.com/dachu02
- apiUrl - Binance API URL, default set as https://api.binance.com
- finhubApiKey - api key from finnhub, instruction how generate key on https://github.com/dachu02
- pairList - list of coins supported by the bot (coma separated, eg. BTCUSDT,ETHUSDT,BNBUSDT), currently only pairs with USDT are supported *this constant is disabled in Early Access
- maxOpenOrdersPerCoin - maximum open orders per one coin *this constant is disabled in Early Access
- defaultBuyAmountInUSDT - amount of USDT that will be spent for one order, 12 is the minimum value, Binance will reject smaller orders
- takeProfit - percentage value on which bot will sell positions, recommended value from 0.5 to 5
- botBuyEnabled - enable or disable auto buy by bot
- stopLossActive - enable or disable Stop-Loss, if you activate it bot can sell positions with loss on stopLossValue
- stopLossValue - value of Stop-Loss, remember to put here negative number (eg. -0.5)
- trailingStopLossActive - enable or disable TrailingStop-loss
- trailingStopLossArm - at this percentage value bot will be "armed", sell will be automatically when percentage drops by trailingStopLossMargin
- trailingStopLossMargin - margin for trailingStopLossArm (eg. when trailingStopLossArm = 2 and trailingStopLossMargin = 0.5 bot will sell at minimum 1.5 when threshold of 2 will be reached, but if profit will achieve eg. 4% then order will be sold at 0.5% less) more explanation on github page
- allowNotification - enable or disable windows notifications
- debug - show or hide debug info (hide recommended if bot is working properly, there is a lot information there)

*some features are disabled in early access


## RESPONSIBILITY & RISK
1. !App is for the people over 18, you are playing with real money and you can both take profit or lose your money.
2. !Use the app only if you understand what you are doing and you understand all the risks of trading cryptocurrencies. You warrant that you understand the price volatility in the cryptocurrency market and the potential loss.
3. !Me as a Bin-BOT developer and Binance and any other third party will NOT TAKE responsibility on your profit or loss.
4. !You are aware of the risks related with the use of Bin-BOT, risk of possible errors and assume full responsibility for these risks.
5. !Last but not least, I'm not providing any investments advices. If you need one, please go to the professional financial advisor.


## STRATEGIES DESCRIPTION
TBA
