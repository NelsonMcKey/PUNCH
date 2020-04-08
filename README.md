# PUNCH
## Introduction ##
Punch is an open platform merchant/customer loyalty solution that flips the typical coffee punch card on its head. Merchants can create a branded digital dollar, legally representing a good or service that they provide. Loyal customers can obtain discounted digital dollars, to be traded or redeemed - from their favourite merchants. This simple mechanism creates new sources of discounted cash flow for small businesses, and creates new commerce opportunities for loyal customers who intend to advocate for and purchase from a brand for more than a single transaction.

## Features ##

**Merchant Portal User Stories**
- Create a new merchant wallet and profile (Authereum, 3box)
- Issue a branded digital dollar (multi-currency) with associated redemption contract and token metadata (Openlaw)
- Place a tranche of tokens on the open market for sale (Uniswap)
- Redeem tokens at point of sale (Authereum)

**Customer Portal User Stories**
- Create a new customer wallet and profile, or authenticate with an existing profile (Authereum, 3box)
- Search by merchants that I know, like (previous interaction), or are in close proximity to me
- View and filter a list of merchants and see the current sale price of their tokens (as a percentage of their chosen currency)
- Purchase a token
- Sell a token
- View tokens held
- Redeem a token at Point of Sale

**Punch Website User Stories**
- Allow a merchant or user to login to their customer portal
- Tutorial on how it works
- Legal agreements and disclaimers

**Guiding Principles**
- Cleanly separate front-end and back-end
- Repackage existing services wherever possible
- Web view should be a curation of on-chain data, rather than a novel or complex contract code
- Onboarding flows should repackage existing services and present them as simple steps, but everything could be completed independently (ie. wallet creation, issuance, redemption, key storage)


**Mandatory Reading and references**
- I found a centralised version: https://www.kabbage.com/
- Uniswag is similar for physical goods: https://www.uniswag.io/
- $Roll creates social money: https://www.dapp.com/dapp/roll-2
- An example of a personal token on Uniswap: https://uniswap.info/token/0x5a844590c5b8f40ae56190771d06c60b9ab1da1c
- OpenLaw contract for personal token issuance: https://lib.openlaw.io/web/default/template/Generate%20Personal%20Token%20%F0%9F%91%A4
- Affogato, a specific solution for Coffee: https://affogato.co/
- And the Affogato write up: https://medium.com/affogato-network/cafe-dynamically-priced-coffee-fc1d0a5ec98d

**Solution Stack for Investigation (TBC)**
- Torus, OAuth for web3: https://tor.us/
- Blocknative: https://www.blocknative.com/
- Identity: 3box.io
- Contracts: OpenLaw
