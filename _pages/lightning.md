---
layout: page
title: Lightning Wallets
permalink: /lightning/
---

Lightning native wallets aren't that different from a 'normal' bitcoin wallet, in fact some of the options below offer both, but come with a particular focus on Lightning functionality of small/fast payments. Some achieve on-chain interaction via the use of [submarine swaps](https://bitcoinmagazine.com/articles/pay-bitcoin-mainnet-lightning-and-back-submarine-swaps-are-now-live), others require users to connect to their own Bitcoin and/or Lightning node. 

### Table of Contents

1.  [Breez](#breez)
2.  [Phoenix](#phoenix)
3.  [Zap](#zap)
4.  [Zeus](#zeus)

***

## Breez

[Breez](https://breez.technology/) is a great option for those wanting to get started with Lightning. It seamlessly supports on-chain send/receive via [submarine swaps](https://medium.com/breez-technology/reverse-submarine-swaps-another-step-towards-a-p2p-lightning-economy-bacb040fdca7). Breez solves the inbound liquidity problem by opening channels [on demand](https://medium.com/breez-technology/the-breez-release-candidate-getting-lightning-ready-for-the-global-takeover-b5d1f9756229) for a small fee. Breez also supports LN URL withdrawal and comes with a built in marketplace with Bitrefill.

<img src="https://raw.githubusercontent.com/BitcoinQnA/bitcoin-wallet-guide/master/images/breez.png" class=responsive width="220" height="450" maxheight="500">

### Notable Features
* Connect to own node
* Send/Receive on chain via swaps 
* POS app built in
* Fast onboarding

### Notable Limitations
* Requires Google Play services to for 100% functionality

### Available on
* iOS + Android

### Other resources
* [Codebase](https://github.com/breez/breezmobile)
* [Documentation](https://github.com/breez/breezmobile)
* [Telegram](https://t.me/breez_lightning)
* [Video](https://youtu.be/lcBsn8e-oQ4)

***

## Phoenix

[Phoenix](https://phoenix.acinq.co/) is another great starter wallet for users wanting to onboard with Lightning. Much like Breez, Phoenix seamlessly supports on-chain send/receive transactions via submarine swaps and also opens channels on demand for a small fee. These swaps result in a certain level of trust in the entity running the swap service (Acinq) and users should also consider the privacy tradeoffs that come with this setup too.

<img src="https://raw.githubusercontent.com/BitcoinQnA/bitcoin-wallet-guide/master/images/Phoenix.png" class=responsive width="220" height="450" maxheight="500">

### Notable Features
* Connect to own node
* Send/Receive on chain via swaps 
* Tor option

### Notable Limitations
* No iOS option

### Available on
* Android

### Other resources
* [Codebase](https://github.com/ACINQ/phoenix)
* [Documentation](https://phoenix.acinq.co/faq)
* [Telegram](https://t.me/phoenix_wallet)
* [Video](https://youtu.be/Cx5PK1H5OR0)

***

## Zap

[Zap](https://zaphq.io/) has multiple [implementations](https://zaphq.io/download), all offering slightly different functionality. Both main release mobile offerings currently do not allow wallet creation and only offer remote Lightning node connection although the [testflight](https://testflight.apple.com/join/elC3EXAK) version on iOS does offer wallet creation functionality. All of the desktop applications come with a built in node but also allow for remote node connectivity and wallet creation. All Zap offerings come with a simple user interface and support on and off chain transactions.

<img src="https://raw.githubusercontent.com/BitcoinQnA/bitcoin-wallet-guide/master/images/Zap.png" class=responsive width="220" height="450" maxheight="500">

### Notable Features
* Connect to own node
* Android supports Tor via Orbot
* Remotely manage channels from your phone

### Notable Limitations
* No mobile wallet creation on main releases
* Node requirement a hurdle for newcomers

### Available on
* iOS + Android + Desktop

### Other resources
* [Codebase](https://github.com/LN-Zap)
* [Documentation](https://docs.zaphq.io/)
* [Slack](https://join.slack.com/t/zaphq/shared_invite/enQtMzgyNDA2NDI2Nzg0LWQ1OGMyMWI3YTdmYTQ0YTVmODg4ZmNkYjQ1MzUxNGExMGRmZWEyNTUyOGQzMzZkYTdhODE3NmQxZWZiOGFkYWI)

***

## Zeus

[Zeus](https://zeusln.app/) is a remote control app that works by connecting to your own node via local IP address or over the Tor network. Zeus allows the user to send/receive on and off chain transactions, manage channels, view invoices and routing fees from anywhere in the world (VPN or Tor option required). Zeus works with all of the popular node implementations.

<img src="https://raw.githubusercontent.com/BitcoinQnA/bitcoin-wallet-guide/master/images/zeus.png" class=responsive width="260" height="450" maxheight="500">

### Notable Features
* Connect to own node
* Works with all 3 Lightning implementations 
* Tor option

### Notable Limitations
* Node requirement a hurdle for newcomers

### Available on
* iOS + Android

### Other resources
* [Codebase](https://github.com/ZeusLN/zeus/releases)
* [Documentation](https://github.com/ZeusLN/zeus)
* [Telegram](https://t.me/zeusLN)
* [Setup Guide](https://www.bitcoinqna.com/post/zeus-101)

***

 <a href="#top">Back to top</a>

Back to [home](https://bitcoinwallet.guide)
