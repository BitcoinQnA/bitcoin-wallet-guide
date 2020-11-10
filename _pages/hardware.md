---
layout: page
title: Hardware Wallets
permalink: /hardware/
---

Hardware wallets offers an increase in security when compared with mobile or desktop wallets. They are designed so that your private keys are generated and stored on a dedicated device that is not directly connected to any potentially malware infected device. However, some of these require plugging into a computer to interact with, which exposes them to more risk than their airgapped counterparts. For the ultimate setup in terms of privacy and security, you should look to use an air gapped device in conjunction with a [mobile](/mobile) or [desktop](/desktop) wallet that is connected to your own [node](https://node.guide). 

This type of set-up does come with additional hurdles that may be more difficult to overcome for first timers. This is why there are items in the list below that trade-off some security and privacy to make the user experience smoother by offering a companion app and USB plug in option. Some options in the list offer alt coin support as well as a Bitcoin only firmware option, always ensure you opt for the Bitcoin only version to minimise another attack vector risk.

### Table of Contents

1.  [BitBox02](#bitbox02)
2.  [Cobo Vault](#cobo-vault)
3.  [Coldcard](#coldcard)
4.  [Specter DIY](#specter-diy)
5.  [Trezor](#trezor)

***

## Bitbox02

[BitBox02](https://shiftcrypto.shop/en/products/bitbox02-bitcoin-only-edition-pre-order-4/#carousel-example-generic) comes with a touch sensitive interface which,  when combined with the companion desktop app, makes the setup and interaction a breeze for beginners. The BitBox02 has to be plugged into a computer to function and works with its own desktop app (which offers coin control), as well as all popular desktop wallets. Users should ensure they manually write down their seed words upon setup, this is not enforced by the app.   

<img src="https://raw.githubusercontent.com/BitcoinQnA/bitcoin-wallet-guide/master/images/bixbox02.png" class=responsive width="300" height="150" maxheight="150">

### Notable Features
* Companion desktop [app](https://shiftcrypto.ch/download/) that connects to your node
* Very simple setup process
* Automatic SD card backups

### Notable Limitations
* Plug in via USB only
* SD card backup not encrypted

### Other resources
* [Codebase](https://github.com/digitalbitbox)
* [Documentation](https://guides.shiftcrypto.ch/bitbox02/)
* [Telegram](https://t.me/bitboxwallet)
* [Video](https://youtu.be/6D4FgJo3j64)

***

## Cobo Vault

[Cobo Vault](https://cobo.com/hardware-wallet) offers three distinct options. The [Essential](https://shop.cobo.com/products/cobo-vault-essential), the [Pro](https://shop.cobo.com/products/cobo-vault) and the [Ultimate](https://shop.cobo.com/products/cobo-vault-ultimate). Their core functionality is the same but you can compare the differences [here](https://cobo.com/hardware-wallet/hardware-wallet-comparison). The Cobo Vault uses a true air gap operation, doing all transaction signing via QR codes and all firmware updates via SD card. The device works with most major desktop applications and allows the user to provide additional entropy when generating a seed which can then be saved via [Shamir](https://medium.com/cobo-vault/why-cobo-vault-implemented-shamir-backups-4665ae379396) backups. Users should ensure they install the Bitcoin only [firmware](https://cobo.com/hardware-wallet/downloads).

<img src="https://raw.githubusercontent.com/BitcoinQnA/bitcoin-wallet-guide/master/images/Cobo%20Vault.png" class=responsive width="250" height="400" maxheight="300">

### Notable Features
* Completely airgapped operation
* Large touchscreen
* PSBT
* Good range of options for all types of user

### Notable Limitations
* Companion app (not required for use) cannot connect to own node 

### Other resources
* [Codebase](https://github.com/CoboVault)
* [Documentation](https://support.cobo.com/hc/en-us/articles/360045490014-Getting-started-in-5-steps)
* [Telegram](https://t.me/CoboVault)
* [Video](https://youtu.be/JnRjvZKulrA)

***

## Coldcard

[Coldcard](https://coldcardwallet.com/) has been the default hardware wallet option for the more focused bitcoiner for multiple years (for good reason). Coldcard offers a true airgapped operation and achieves all transaction signing and firmware updates via the SD card. The Coldcard has a massive feature set that include encrypted SD card backups, paper wallet generation, user added entropy and [BIP85](https://github.com/bitcoin/bips/blob/master/bip-0085.mediawiki) support for deriving multiple wallets from a single seed. Coldcard is compatible with all major desktop wallet integrations.

<img src="https://raw.githubusercontent.com/BitcoinQnA/bitcoin-wallet-guide/master/images/coldcard-front.png" class=responsive width="210" height="350" maxheight="350">

### Notable Features
* Completely airgapped operation
* Encrypted backups
* Duress attack solutions
* Beginners have the option to use via USB

### Notable Limitations
* Menu system not as easy to navigate as alternatives

### Other resources
* [Codebase](https://github.com/coldcard/)
* [Documentation](https://coldcardwallet.com/docs/)
* [Telegram](https://t.me/coldcard)
* [Video](https://www.youtube.com/playlist?list=PLZKkuPrgFw0axLoDDzxAIYzpZeC_T1i7W)

***

## Specter DIY

[Specter DIY](https://specter.solutions/) is an open-source hardware wallet with large touchscreen, QR-code scanner and a smartcard-reader. As the name suggests, this device is built by the user with off the shelf [parts](https://github.com/cryptoadvance/specter-diy/blob/master/docs/shopping.md) that can be purchased from a number of different manufacturers which minimises supply chain risk. Once assembled, the user then flashes the firmware onto the device and proceeds with device setup. The device is supported by Specter Desktop but is still an early project and is not well suited to someone with limited technical knowledge, proceed with caution.

<img src="https://raw.githubusercontent.com/BitcoinQnA/bitcoin-wallet-guide/master/images/Specter%20DIY.png" class=responsive width="210" height="390" maxheight="390">

### Notable Features
* Completely airgapped operation
* Drastically minimises supply chain attack vector
* Built to user specification

### Notable Limitations
* Not for beginners
* Still in prototype status

### Other resources
* [Codebase](https://github.com/cryptoadvance/specter-diy)
* [Documentation](https://github.com/cryptoadvance/specter-diy/tree/master/docs)
* [Telegram](https://t.me/spectersupport)
* [Video](https://www.youtube.com/watch?v=1H7FqG_FmCw)

***

## Trezor

[Trezor](https://shop.trezor.io/) have two offerings, the [One](https://shop.trezor.io/product/trezor-one-white) and the [Model T](https://shop.trezor.io/product/trezor-model-t). The Model T is their flagship model and offers a colour touchscreen making interaction simple. Both devices require being plugged into a computer to sign transactions and are compatible with all popular desktop wallet options. Users should ensure they install the Bitcoin only [firmware](https://wiki.trezor.io/Bitcoin_firmware#Installing_the_Bitcoin-only_firmware).

<img src="https://raw.githubusercontent.com/BitcoinQnA/bitcoin-wallet-guide/master/images/T2-removebg-preview.png" class=responsive width="250" height="220" maxheight="220">

### Notable Features
* Colour touchscreen (Model T)
* Shamir backups

### Notable Limitations
* Plug in via USB only
* Default web wallet leaks privacy and does not support bech32

### Other resources
* [Codebase](https://github.com/trezor)
* [Documentation](https://wiki.trezor.io/Wallet_manual)
* [Telegram](https://t.me/spectersupport)
* [Video](https://www.youtube.com/watch?v=1H7FqG_FmCw)

***

 <a href="#top">Back to top</a>

Finished looking for a hardware wallet? Check out the available [Lightning native](/lightning) wallets.
