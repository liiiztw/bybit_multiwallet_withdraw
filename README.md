# bybit_multiwallet_withdraw
Just for 阿彬168

## Give me a coffe 

metamask wallet
```
0x9FedBBC14302838837284595504Ff15487A5ac85
```

## Description

bybit 多地址提幣功能

## Getting Started
Go to www.bybit.com and get the api key, set multi-wallet addresses to whitelist.

### config.json
```
{
    "accountType": "SPOT", or "FUND"
    "token": "BNB",
    "network": "BSC",
    "amount": 0.015,
    "random_amount":true,
    "delay": { "min": 11, "max": 15 },
    "key":"",
    "secret":""
}
```
1. edit token which you wana withdraw
2. run getTokenSetting.exe to check "chain" and "withdrawMin"
3. edit "network" and "amount"(>withdrawMin)
4. random_amount true or false

### wallets.txt
```
0x9FedBBC14302838837284595504Ff15487A5ac85
0x3728814d34c3C271B276F7528A3370b2015C6C9E
```

## run withdraw.exe

## contact info

[telegram](https://t.me/liiiztw)
[twitter](https://twitter.com/game_liiiz)

## Version History
* v2
    * support choose FUND or SPOT
* v1
    * Initial Release

## License

GPL ( GNU General Public License )
