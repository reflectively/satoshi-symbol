# Do we need a satoshi sign (symbol)

This is not a proposal, but rather a start for a discussion. I would love to receive feedback from BTC devs and users.

Tldr: A dedicated sathoshi might contribute to...:
* Creating a closed ecosystem: Encourage thinking in satoshis instead of cents or USD -> move away from fiat based evaluation
* UX/UI flexibility: especially mobile interfaces have limited amount of screen space. Going down from 3 to 1 characters doesn't sound a lot, but can contribute to user experience. E.g. bigger font size for better visibility.

# Satoshi denomination due to rising BTC price

It's reasonable to expect BTC to go up to 100k USD by 2022.
![Log regression adoption price for BTC](btc-logreg-price.jpg)
Source: Tuur Demeester https://twitter.com/TuurDemeester/status/1029132554769760256

## Examples for micro transaction values:

Use cases for sat denomination:

* Ingame transactions for items
* Content access (text, audio, video)
* Partial content access (e.g. pay per second of consumption)
* Coffee purchase
* Royalty and licensing collection/calculation

1 BTC = 100k USD:
* 0.01 USD = 10sat = 0.1 bits
* 0.19 USD = 190sat = 1.9 bits
* 0.39 USD = 390sat = 3.9 bits
* 0.99 USD = 990sat = 9.9 bits
* 4.99 USD = 4990sat 49.90 bits
* 9.99 USD = 9990sat = 99.90 bits

1 BTC = 1mio USD:

In this scenario 1 bit = 1 USD makes everything easier
* 0.01 USD = 1sat = 0.01 bits
* 0.19 USD = 19sat = 0.19 bits
* 0.39 USD = 39sat = 0.39 bits
* 0.99 USD = 99sat  = 0.99 bits
* 4.99 USD = 499sat = 4.99 bits
* 9.99 USD = 999sat = 9.99 bits

## Going subsatoshi

LN supports transactions < 1sat.
Hence a clear denomination and distinction is required.

http://www.unicode.org/versions/Unicode10.0.0/
BTC was added to unicode standard: http://www.unicode.org/L2/L2015/15229-bitcoin-sign.pdf

List of all currency symbols in Unicode:
https://www.unicode.org/charts/PDF/U20A0.pdf

Avoid any confusion or multiple standards early on:

![Source: https://xkcd.com/927/](https://imgs.xkcd.com/comics/standards.png)

## Closed ecosystem is the ultimate goal

* Samourai removed USD denomination
* Lightning is coming, micro transactions will be a thing

**Building a habit early on for users to think in satoshis**
# Use cases

## Accounting

Bitcoin Businesses have major pains to add BTC as a currency in their company books. Most bookkeeping Saas only support two decimals for currencies. Hence anything below 0.01 BTC (64.20 USD as of writing this) cannot be added natively. Special tools  (barely existent) or workarounds are mandatory which is a major pain in the industry.

# Historical examples from other currencies and units

dedicated currency signs often consist of a latin letter combined with a crossing horizontal, vertical or diagonal line.

https://en.wikipedia.org/wiki/Currency_symbol
https://en.wikipedia.org/wiki/Currency

Out of the 20 most traded currencies worldwide 16 make use of a dedicated sign. The top 6 currencies all use a dedicated sign for main and sometimes the subdivision unit:

1. USD: $1 = 100¢
* EUR: 1€ = 100¢
* JPY: 1¥ = 100 sen (did not have an intl symbol)
* GBP: £1 = 100p (no dedicated sign)
* AUD: $1 = 100c
* CAD: $1 = 100¢

# Existing Proposals

https://en.bitcoin.it/wiki/Satoshi_(unit)
List of possible japanese symbols suggested in the past. Widespread adoption unlikely in the eyes of the author. Historycally the haven't been any non-latin based international currency signs .

https://www.reddit.com/r/Bitcoin/comments/8xcy81/introducing_a_new_symbol_for_satoshi/
Coinranking proposed a latin S with a dot below the character. There hasn' been any widespread adoption or discussion for that.

# Proposed symbols by the author

## Requirements for symbol

* Internationally understood as a subunit to BTC (the understanding has to be built with adoption by time)
* latin character based
* no confusion with signs of existing currencies or general units of measure

## 1. latin small letter s with dot above

| ṡ |
| - |
| latin small letter s with dot above |

> Ṡ is used in Emilian-Romagnol to represent [z], e.g. faṡû [faˈzuː] "beans". It is used in Tunisian Arabic transliteration for /sˁ/ (based on Maltese with additional letters).
> - https://en.wikipedia.org/wiki/%E1%B9%A0

Does exist in unicode
Not really used for much worldwide

## 2. ...small s with 55° line through it

![](sat-55deg.png)

* Similar like cent ¢ cent sign, just an s instead of a c
* Does not exist in unicode, hence could make its own distinctive symbol

# Possible issues with this proposal

## Many subdivision-units don't have a sign and are used just fine:

Examples: 

1. GBP
1. Meter
2. gramm
3. Pascal
5. 

## "sat" sign is not used for anything else and cannot be confused anyway

The author is not aware of any international use of the "sat" sign for any kind of unit. Hence just sticking with sat mgiht be a viable solution.

## Adoption 

# Credits

All the credits go to Satoshi Nakamoto for the initial design of Bitcoin, to all Bitcoin developers, volunteers, supporters, users, miners, influencers, believers.

Special thanks to Jimmy Song whose [BIP 176](https://github.com/bitcoin/bips/blob/master/bip-0176.mediawiki) inspired me to propose this idea to the Bitcoin community.
