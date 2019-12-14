# Binance API Client

Simple client interface to facilitate the use of some Binance API.   


[![NuGet](https://img.shields.io/nuget/v/Alex75.BinanceApiClient.svg)](https://www.nuget.org/packages/Alex75.BinanceApiClient) 
[![Build Status](https://alex75.visualstudio.com/Binance%20API%20Client/_apis/build/status/Build%20v2?branchName=master)](https://alex75.visualstudio.com/Binance%20API%20Client/_build/latest?definitionId=22&branchName=master)

## Functionalities

Function                     | API Key | Description                                             | Status
---                          |---      |---                                                      |---
| Get Ticker / Get Tickers   | No      | Get the Ask/Bid/Min/Max/Last prices of currency pair(s) | Done
| Get Balance                | Yes     | List the availability of all the currencies			 | Done
| Create Market Order        | Yes     | Create a market order									 | Done
| Withdraw                   | Yes     | Withdraw a currency                                     | Done


<!--
| Create Limit Order         | Yes     | Create a limit order									 | Not implemented
| List Open Orders           | Yes     | List open orders										 | Not implemented
| Check Order Status         | Yes     |														 | Not implemented
| Cancel Order               | Yes     | Cancel an order										 | Not implemented
| List User Transactions     | Yes     | List the User Transactions								 | Not implemented
-->



## XRP note

Binance does not offer the pair _XRP/USD_ nor _XRP/EUR_.  
XRP can only be exchanged using:  
- XRP/BTC
- XRP/ETH
- TRX/XRP
- ZXC/XRP

Withdraw XRP has a minimum quantity of 25.



## For Developers

- https://www.binance.com/userCenter/createApi.html
- https://github.com/binance-exchange/binance-official-api-docs/blob/master/rest-api.md



