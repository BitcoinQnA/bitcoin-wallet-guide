---
layout: page
title: Hardware Wallets
permalink: /hardware/
---

Plug and Play node boxes offer a convenient way to run your own node. Most run on a variation of a single board computer such as a [Raspberry Pi](https://www.raspberrypi.org/). You simply choose your specification (*if multiples are offered*), wait for it to be delivered, plug it in and you are off. This convenience comes with some tradeoffs that you should be aware of. Because you are buying pre built hardware, you can never be 100% sure that there are no malicious components installed that could be leaking your privacy, or worse your bitcoin. However, were one of the suppliers below were to perform such an attack, they would not be in business for long! Finally, you should consider the privacy and security aspects of getting Bitcoin related hardware delivered to your home address.

### Table of Contents

1.  [myNode One](#mynode-one)
2.  [Nodl One](#nodl-one)
3.  [Nodl Dojo](#nodl-dojo)
4.  [RaspiBlitz](#raspiblitz)
5.  [Start9 Embassy](#start9-embassy)
6.  [Build-A-Node](#build-a-node)

***

### Cost Comparison

| Node                                | Cost                               |
|-------------------------------------|------------------------------------|
| [myNode One](#mynode-one)           | $339 (HDD)                         |
|                                     | $419 (SSD)                         |
| [Nodl One](#nodl-one)               | $499                               |
|                                     | +$50 w/ kill switch                |
|                                     | +$50 w/ Dojo support               |
| [Nodl Dojo](#nodl-dojo)             | $849                               |
| [RaspiBlitz](#raspiblitz)           | 269€ (2GB)                         |
|                                     | 299€ (4GB)                         |
|                                     | 369€ (8GB)                         |
|                                     | 379€ (4GB) w/ terminal style case  |
| [Start9 Embassy](#start9-embassy)   | $239                               |
| [Build-A-Node](#build-a-node)       | From $410                          |

## myNode One

The [myNode One](https://mynodebtc.com/products/one) is a Raspberry Pi4 4GB and comes packaged with their premium software which provides extra features and support. The myNode software comes with a beginner friendly web based user interface and is packed with features. At time of writing myNode currently offers 15 different Bitcoin and Lightning related applications.

<img src="https://raw.githubusercontent.com/BitcoinQnA/node-guide/master/images/d3-removebg-preview.png" class=responsive width="300" height="250" maxheight="250">


### Features

* RTL, Thunderhub + LN Bits
* Electrum Server (*Electrs*)
* BTC Pay Server
* BTC Explorer
* Samourai Dojo + Whirlpool
* Mempool Viewer
* Caravan + Specter Wallet Interfaces
* Remote access via Tor or VPN
* One click upgrades


### Ease of setup

Once you receive the device, connect the hardware and power it on. Visit `http://mynode.local/` with your phone, laptop or computer. Enter the product key that was supplied with the device. Your initial block download will then commence.


### Limitations

Some users report reliability issues. Currently only shipping to the U.S and Canada.

### Cost

* $279 with no storage supplied
* $339 with a 1TB hard drive
* $419 with a 1TB sold state drive

### Recommended Hardware

Comes pre built with a Raspberry Pi4 4GB. User specifies type of storage.

### Other resources

* [Codebase](https://github.com/mynodebtc/mynode)
* [Telegram](https://t.me/mynode_btc)
* [Guide Page](https://mynodebtc.com/guides)
* [Setup Video](https://www.youtube.com/playlist?list=PLCRbH-IWlcW0KP8DxyWWrqahGafZyV2HR)

***

## Nodl One

The [Nodl One](https://www.nodl.it/nodl-one.html) is a Rock Pi4 with 4GB ram and comes with a web based user interface and higher spec hardware than most plug and play nodes.

<img src="https://raw.githubusercontent.com/BitcoinQnA/node-guide/master/images/nodl-one-early-bird-removebg-preview.png" class=responsive width="300" height="250" maxheight="250">


### Features

* RTL
* Electrum Server (*Electrs*)
* BTC Pay Server
* BTC Explorer
* Samourai Dojo + Whirlpool
* Remote access via Tor or VPN
* One click upgrades
* Full SSD encryption


### Ease of setup

Once you receive the device, connect the hardware and power it on. Visit `http://nodl.local:8338/` with your phone, laptop or computer. Click on the Nodl logo, set your password and you will then see the Nodl homepage.


### Limitations

Documentation is sparse.

### Cost

* $499 standard
* $50 extra for kill switch
* $50 extra for Samourai/Dojo premium support 

### Recommended Hardware

Comes pre built with a Rock Pi4 4GB, 16GB eMMC and 1TB SSD.

### Other resources

* [Codebase](https://gitlab.lightning-solutions.eu/search?utf8=%E2%9C%93&search=nodl&group_id=&project_id=&repository_ref=)
* [Telegram](https://t.me/nodl_it)
* [Guide Page](https://docs.lightning-solutions.eu/nodl-box/quick-start/getting-started)
* [Setup Video](https://www.keepitsimplebitcoin.com/setup-nodl/)

***

## Nodl Dojo


The [Nodl Dojo](https://www.nodl.it/nodl-dojo.html) is similar to the Nodl One at its core. The main differences are a custom red case, fully encrypted SSDs, RAID 1 mirroring for extra redundancy (if one SSD fails, your node continues to run) and a premium support package. 

<img src="https://raw.githubusercontent.com/BitcoinQnA/node-guide/master/images/angled-box.png" class=responsive width="200" height="175" maxheight="300">


### Features

* RTL
* Electrum Server (*Electrs*)
* BTC Pay Server
* BTC Explorer
* Samourai Dojo + Whirlpool
* Remote access via Tor or VPN
* One click upgrades
* Full SSD encryption
* RAID Mirroring


### Ease of setup

Once you receive the device, connect the hardware and power it on. Visit `http://nodl.local:8338/` with your phone, laptop or computer. Click on the Nodl logo, set your password and you will then see the Nodl homepage.


### Limitations

Stock is limited and sells out fast.

### Cost

* $849

### Recommended Hardware

Comes pre built with a Rock Pi4 4GB, 16GB eMMC and 2x 1TB SSDs.

### Other resources

* [Codebase](https://gitlab.lightning-solutions.eu/search?utf8=%E2%9C%93&search=nodl&group_id=&project_id=&repository_ref=)
* [Telegram](https://t.me/nodl_it)
* [Guide Page](https://docs.lightning-solutions.eu/nodl-box/quick-start/getting-started)
* [Setup Video](https://www.keepitsimplebitcoin.com/setup-nodl/)

***


## RaspiBlitz


The [RaspiBlitz](https://shop.fulmo.org/raspiblitz/) is one of the longest standing node projects and comes feature packed with a significant focus on the Lightning network. The RaspiBlitz boasts rock sold uptime and well tested update procedures. 

<img src="https://raw.githubusercontent.com/BitcoinQnA/node-guide/master/images/blitz1.png" class=responsive width="300" height="250" maxheight="250">


### Features

* RTL
* Thunderhub
* Electrum Server (*Electrs*)
* BTC Pay Server
* BTC Explorer
* LN Bits
* Specter Desktop
* Mempool Viewer
* Joinmarket
* Loop
* IP 2 Tor
* Remote access via Tor
* Touchscreen display


### Ease of setup

Once you receive the device, connect the hardware and power it on. You should then see the local IP and password address of your RaspiBlitz on the LCD panel. Using an [SSH tool](https://en.wikipedia.org/wiki/Comparison_of_SSH_clients), connect through to your RaspiBlitz and finish the setup process.


### Limitations

Lack of web user interface may put some users off.

### Cost

* 269 EUR (*2GB*)
* 299 EUR (*4GB*)
* 369 EUR (*8GB*)
* 379 EUR (*4GB with metal case*)

### Recommended Hardware

Comes pre built with a Raspberry PI with a selection of 2,4 or 8GB ram, 1TB SSD and a touchscreen and optional 'terminal style' metal case.

### Other resources

* [Codebase](https://github.com/rootzoll/raspiblitz)
* [Telegram](https://t.me/raspiblitz)
* [Guide Page](https://github.com/rootzoll/raspiblitz)
* [Deep Dive Video](https://www.youtube.com/watch?v=_cjGxjze8PM)

***


## Start9 Embassy


The [Embassy One](https://store.start9labs.com/collections/embassy/products/embassy-one) is a new node implementation with a focus on making setup and interaction a frictionless as possible. The Embassy is limited in features but is working towards becoming your own personal server that does more than just be a Bitcoin node. 

<img src="https://raw.githubusercontent.com/BitcoinQnA/node-guide/master/images/Embassy-Evolution_360x.png" class=responsive width="300" height="250" maxheight="250">


### Features

* Cups encrypted messaging
* Bitwarden password manager
* File browser
* Remote Tor access
* Companion phone app
* Web based UI


### Ease of setup

Once you receive the device, connect the hardware and power it on. Inside the setup app, enter your product key and then create your password. You can now log in and start installing and using the available services.

### Limitations

No hard drive, all storage is done via an SD card which can be unstable. No Lightning network and runs in 'pruned' mode so importing existing wallets is not possible.

### Cost

* $239

### Recommended Hardware

Comes pre built with a Raspberry Pi 4GB.

### Other resources

* [Codebase](https://github.com/Start9Labs)
* [Telegram](https://t.me/start9_labs)
* [Guide Page](https://docs.start9labs.com/)
* [Setup Video](https://www.youtube.com/watch?v=YMStLevc034)

***

## Build-A-Node

The [CryptoCloaks](https://www.cryptocloaks.com) team offer a [build a node](https://www.cryptocloaks.com/product/build-a-node/) service that lets you customise your own plug + play node. The node will arrive ready to go with a choice of the myNode community, myNode premium or RaspiBlitz software. You can also create a custom case for your node to add a more personal touch.

<img src="https://github.com/BitcoinQnA/node-guide/blob/master/images/PXL_20201007_111600379-removebg-preview.png?raw=true" class=responsive width="300" height="250" maxheight="250">

### Cost

* From $410

### Recommended Hardware

Comes packaged with this base hardware but upgrades are available.

* Raspberry Pi Model 4B 4GB
* Pimoroni Fan Shim
* 32GB SD Card
* 1TB SSD
* 3.5″ LCD (*RaspiBlitz only*)
* Custom case

***

Want to build your own node? Check out the [DIY](/do-it-yourself/) page.
