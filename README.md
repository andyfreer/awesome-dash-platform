# Awesome Dash Platform [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Useful resources for using [Dash Platform](https://dashdevs.org) and building things on top of it

_This list is for projects, tools, or pretty much any things related to Dash Platform that are totally_ **awesome**_. This is for products which are already awesome - if you have plans for cool stuff to do with Dash, you should build it, and then link it here. If you have an idea for an awesome thing to do with Dash, a good place to ask about it might be in [ipfs/apps](https://github.com/ipfs/apps) or [ipfs/notes](https://github.com/ipfs/notes)._

## Table of Contents

- [Contribute](#contribute-to-this-list)
- [Articles](#articles)
- [DAPI](#dapi)
- [Dapps](#dapps)
- [Docs](#docs)
- [Tools](#tools)
- [Videos](#videos)
- [Bounties](#bounties)
- [Discussions](#discussions)
- [License](#license)

## Contribute to this list!

Everyone is welcome to submit their new Dash Platform item, but it will be accepted only if it meets our [content policy](https://github.com/andyfreer/awesome-dash-platform/blob/master/POLICY.md).

Readme and the website are automatically generated. In order to add an element to this list, you need to modify the files in `/data` and then run  `make build` before publishing your pull request. Read [contributing guidelines](https://github.com/andyfreer/awesome-dash-platform/blob/master/CONTRIBUTING.md) to learn how to do so.


## Articles

- 2021-03-08: [Release Announcement Dash Platform v0.18 on Testnet](https://blog.dash.org/release-announcement-dash-platform-v0-18-on-testnet-45f421a6bc98) - Dash Blog
- 2020-12-30: [Release Announcement Dash Platform v0.17 & DashPay on Testnet](https://blog.dash.org/release-announcement-dash-platform-v0-17-dashpay-on-testnet-13a85225902e) - Dash Blog
- 2020-09-30: [Release Announcement Dash Core v0.16 on Mainnet](https://blog.dash.org/release-announcement-dash-core-v0-16-on-mainnet-870aa327240b) - Dash Blog
- 2020-09-05: [Dash Platform v0.15 on Evonet](https://blog.dash.org/release-announcement-dash-platform-v0-15-on-evonet-88131f9c477b) - Dash Blog
- 2020-07-24: [Dash Platform v0.14 on Evonet](https://blog.dash.org/release-announcement-dash-platform-v0-14-on-evonet-9e02ad97d918) - Dash Blog
- 2020-06-14: [Dash Platform v0.13 on Evonet](https://blog.dash.org/release-announcement-dash-platform-v0-13-on-evonet-53c86b081b64) - Dash Blog
- 2020-04-23: [Announcing the Release of Dash Platform v0.12 on Evonet](https://blog.dash.org/announcing-the-release-of-dash-platform-v0-12-on-evonet-e611f2a93ce3) - Dash Blog
- 2020-03-18: [Announcing the Release of Dash Platform v0.11](https://blog.dash.org/announcing-the-release-of-dash-platform-v0-11-d1b7238ed0e6) - Dash Blog
- 2019-12-30: [Announcing the Release of Dash Platform on Evonet](https://blog.dash.org/announcing-the-release-of-dash-platform-on-evonet-c5a94dee0e59) - Dash Blog
- 2019-12-30: [Long-Awaited Dash Evolution Platform Released on Testnet](https://dashnews.org/long-awaited-dash-evolution-platform-released-on-testnet-with-developer-documentation-hub/) - Dash News
- 2019-12-18: [Edge Wallet Highlights Dash Evolution Update](https://dashnews.org/edge-wallet-highlights-dash-evolution-update-skeptical-on-store-of-value-analysis/) - Dash News
- 2019-12-09: [Ryan Taylor Explains Unique Pain Point Dash Platform Solves for Consumers and Merchants](https://dashnews.org/ryan-taylor-explains-unique-pain-point-dash-platform-solves-for-consumers-and-merchants/) - Dash News
- 2019-11-16: [Dash developers announced the timeline of  Evolution platform release](https://www.fxstreet.com/cryptocurrencies/news/dash-developers-announced-the-timeline-of-evolution-platform-release-201911161943) - FX Street
- 2019-10-17: [Introducing the Platform Chain](https://blog.dash.org/introducing-the-platform-chain-982fe6aea67f) - Dash Blog
- 2019-05-20: [An Introduction to Dash Platform, DAPI, and Drive](https://blog.dash.org/an-introduction-to-dash-platform-dapi-and-drive-9d080d6e89c9) - Dash Blog

## DAPI

- [Connecting to Evonet](https://dashplatform.readme.io/docs/tutorial-connecting-to-evonet) - The purpose of this tutorial is to walk through the steps necessary to access Dash's Decentralized API (DAPI)
- [Create and Fund a Wallet](https://dashplatform.readme.io/docs/tutorial-create-and-fund-a-wallet) - This tutorial explains how to generate a new wallet, retrieve an address from it, and transfer test funds to the address from a faucet.
- [DashJS](https://dashevo.github.io/js-dash-sdk/#/) - Connect to Dash from a Browser / NodeJS Server using Dash's Decentralized-API
- [Platform-UserID Secure Messaging Library](https://www.npmjs.com/package/dashmachine-crypto) - secure messaging between UserIDs (unique references to an individual name registration by an identity) from JS clients
- [Register a Data Contract](https://dashplatform.readme.io/docs/tutorial-register-a-data-contract) - In this tutorial we will register a data contract.
- [Register a Name for an Identity](https://dashplatform.readme.io/docs/tutorial-register-a-name-for-an-identity) - The purpose of this tutorial is to walk through the steps necessary to register a Dash Platform Name Service (DPNS) name.
- [Register an Identity](https://dashplatform.readme.io/docs/tutorial-register-an-identity) - Identities serve as the basis for interactions with Dash Platform. The purpose of this tutorial is to walk through the steps necessary to register a user identity.
- [Retrieve Documents](https://dashplatform.readme.io/docs/tutorial-retrieve-documents) - In this tutorial we will retrieve some of the current data from a data contract.
- [Send Funds](https://dashplatform.readme.io/docs/tutorial-send-funds) - Once you have a wallet and some funds, another common task is sending Dash to an address.
- [Submit Documents](https://dashplatform.readme.io/docs/tutorial-submit-documents) - Data is stored in the form of Documents which are entities encapsulated in a state transition before being submitted to DAPI.

## Dapps

- [DashPay](https://github.com/dashevo) - Mobile Dapp enabling Username based payments and Platform authentication (WIP)
- [DPNS](https://dashplatform.readme.io/docs/explanation-dpns) - Name Service Dapp providing Usernames for Dash Blockchain Identities (LIVE) [Source](https://github.com/dashevo/js-dpp/tree/v0.11-dev/schema/identity)
- [Jembe](http://jembe.dashevo.io/) - Decentralized Twitter Alternative Dapp. Join the Conversation [Source](https://github.com/dashameter/jembe)
- [Masternode Polling Tool (Proposal)](https://chat.dashdevs.org) - Polling Masternodes for Decisions (IDEA)
- [Merchant Directory (Proposal)](https://app.dashnexus.org/proposals/dash-platform-merchant-directory/overview) - Merchant Directory Dapp (PROPOSAL)

## Docs

- [Core Developer Guide](https://dashcore.readme.io/docs/core-guide-introduction) - Detailed docs for working with Dash's internal Core Network
- [Dash User Docs](https://docs.dash.org/en/stable/) - User documentation for understanding general Dash concepts & usage
- [DashJS](https://dashevo.github.io/js-dash-sdk) - JavaScript library for Dapp developers on Dash Platform
- [DIP 11](https://github.com/dashpay/dips/blob/master/dip-0011.md) - Dash Improvement Proposal (DIP) 11 on Identities
- [DIP 12](https://github.com/dashpay/dips/blob/master/dip-0012.md) - Dash Improvement Proposal (DIP) 12 on Dash Platform Name Service (DPNS)
- [Platform Developer Guide](https://dashplatform.readme.io/) - Guides and documentation to help you start working with Dash Platform as quickly as possible, as well as support if you get stuck.
- [Tendermint Core Docs](https://docs.tendermint.com/master/) - Docs for Tendermint, the BFT protocol used on Layer 2 in conjunction with Masternode quorums

## Tools

- [Block Explorer (L1)](http://insight.evonet.networks.dash.org:3001/insight/) - Core Network Blocks (Layer 1), for Currency, Identity and Credit Transactions [Source](https://github.com/dashevo/insight-ui)
- [Chrome Wallet](https://github.com/readme55/Dash-Chrome-Wallet/releases/tag/DashChromeWallet-v1.3) - An alternative Platform Wallet implementation created as an extension for Chrome / Firefox
- [DAPI Client C#](https://www.nuget.org/packages/dapi-client-csharp/) - Basic DAPI client in C# [Source](https://github.com/10xcryptodev/dapi-client-csharp)
- [DAPI Client Golang](https://github.com/10xcryptodev/dapi-client-go) - Basic DAPI client in Golang
- [DAPI Client Python](https://github.com/10xcryptodev/dapi-client-py) - Basic DAPI client in Python
- [Dash Masternode Deployment Tool](https://github.com/strophy/dash-masternode-docker) - This tool deploys a Dash masternode to the current host.
- [Dash Network Deploy](https://github.com/dashevo/dash-network-deploy) - This tool assists in deploying and managing Dash networks.
- [Evo Wallet (WIP)](http://evowallet.io/) - An alternative Platform Wallet implementation created as a pure Webapp [Source](https://github.com/evowallet/evowallet)
- [EvoNet Auto-Faucet](https://csb-k2nzi.netlify.app/) - Get EvoNet coins to test with (automated) [Source](https://github.com/riongull/dash-faucet-UI)
- [EvoNet Faucet](http://faucet.evonet.networks.dash.org/) - Get EvoNet coins to test with, uses captcha
- [Get Identitfy from mnemonic](http://getidentity.dashmachine.net/) - JS Library code to input a mnemonic on a client (including browser) and query/return the user identity from the network [Source](https://github.com/dashmachine/identity-from-mnemonic)
- [Pay-To-Username tipping POC](http://tipping.dashmachine.net/) - POC for one username to tip another blindly (without needing a contacting process or any communication between the usernames) [Source](https://github.com/dashmachine/tipping)
- [Platform Console](http://console.dashevo.io/#/wallet) - Explore & Update Platform State (WIP) [Source](https://github.com/denlb/dash-platform-console)
- [Platform Explorer (L2)](https://pce.cloudwheels.net/) - Platform chaion explorer plus State Transitions and user data [Source](https://github.com/dappforce/dappforce-tendermint-explorer)
- [Platform-UserID Secure Messaging Library](https://github.com/dashmachine/dash-platform-user) - Standardized modules for secure messaging between UserIDs (unique references to an individual name registration by an identity)

## Videos

- 2020-10-02: [What is Dash's Decentralized API? (DAPI) | Dash Platform](https://www.youtube.com/watch?v=S0pq-qOu9cQ) - This is episode 3 of a 5 part video series on Dash Platform.
- 2020-09-25: [What is Dash Drive? | Dash Platform](https://www.youtube.com/watch?v=14N5pnl5W0Y) - This is episode 2 of a 5 part video series on Dash Platform.
- 2020-09-18: [Dash is Becoming a Cloud | Dash Platform](https://www.youtube.com/watch?v=9WqUMrIN58Q) - This is episode 1 of a 5 part video series on Dash Platform.
- 2020-09-05: [Demo of DashPay Contacts and Notifications](https://www.youtube.com/watch?v=pQ3_Q45HdOA) - This demo shows the contacts and notifications feature in the upcoming Dashpay wallet.
- 2020-08-17: [Dash Dapps - Demoing Community Development on EvoNet](https://www.youtube.com/watch?v=yy8gO1C8fTs) - Demonstrating community projects built on Dash EvoNet during phase 2 of the Dash Platform Incubator proposal.
- 2020-08-06: [Let's Talk Dash Dapps feat. Sample Dapps & Wallet API (Ep 2)](https://www.youtube.com/watch?v=76pYX44o_j8&t=7s) - Second Episode of Let's Talk Dash Dapp's. Readme looks at him Sample Dapps Collection that is communicating with Chrome Wallet API to submit data.
- 2020-07-28: [Let's Talk Dash Dapps feat. Chrome Wallet (Ep 1)](https://www.youtube.com/watch?v=IjjsQNd3Zto) - First Episode of Let's Talk Dash Dapp's. A comprehensive introduction to Dash Platform Decentralized-API (DAPI), Usernames and Data-Contracts.
- 2020-06-23: [Why Dash's New Username Demo Video Is Game-Changing](https://lbry.tv/@DigitalCashNetwork:c/DashUsernames:5?r=Gd7GBo8adnW7dSEBDc2pPP8Ytw9Rw3L9) - Recently Dash released a new demo video showing off usernames and how they're registered in the soon-to-be-released DashPay app, the first part of the long-awaited Evolution update, now called Dash Platform.
- 2020-06-19: [DashPay Username Registration Demo](https://www.youtube.com/watch?v=GtTaezpxQOs) - A demo of the DashPay Username Registration Process.
- 2020-01-06: [DASH EvoNet Review](https://www.youtube.com/watch?v=Vs3cjw51o4w) - Today we are taking a look at the Dash Evonet which is a development network provided for experimentation and evaluation of Dash Platform features.
- 2019-12-11: [Introduction To Dash Platform - Dana Alibrandi](https://www.youtube.com/watch?v=WNoMSP0nPDQ) - Dana Alibrandi introduces Dash Platform and its functionality
- 2019-12-11: [DashPay Wallet - Brian Foster](https://www.youtube.com/watch?v=wkBFcWbsXtQ) - Brian Foster describes the development and features of the "Evolution" DashPay Wallet
- 2019-12-11: [Dash Evolution Open House Analysis | Tao & Amanda LIVE!](https://www.youtube.com/watch?v=PFIOm9KO5sA) - Join the team from Dash Core Group for an open discussion of the upcoming Dash Platform and Dashpay-enabled wallets release, commonly known as Evolution.
- 2019-12-09: [Dash Evolution Open House 2019](https://www.youtube.com/watch?v=ie7fJMw5WIo) - Join the team from Dash Core Group for an open discussion of the upcoming Dash Platform and Dashpay-enabled wallets release, commonly known as Evolution.
- 2019-11-22: [What is Dash Platform?](https://www.youtube.com/watch?v=8jI7Nt3lILs) - The Cryptoviser analysis of Dash Platform
- 2019-10-31: [Understanding Dash Platform and Chain - Expert Followup](https://www.youtube.com/watch?v=Vb3KwVxPE84) - Christopher sits down with Dash Product Manager Dana Alibrandi and Dash Core Developer Ivan Shumkov to get into more technical details about the Dash Platform's concepts
- 2019-10-12: [Dash Platform - Dana Alibrandi and Ivan Shumkov](https://www.youtube.com/watch?v=5Q1cCt9v1U0) - Dana Alibrandi, Dash Platform Product Owner, Dash Core Group Ivan Shumkov, Dash Platform Engineer, Dash Core Group
- 2019-07-12: [Dash Podcast 112 - Intro To Dash Platform feat. Dana Alibrandi](https://www.youtube.com/watch?v=VcLdDmt9TSM) - Intro To Dash Platform feat. Dana Alibrandi Product Owner from Dash Core Group
- 2019-04-19: [Dash Podcast 100 - Feat. Ivan Shumkov](https://www.youtube.com/watch?v=gUDN62ePWms) - Intro To Dash Platform feat. Dana Alibrandi Product Owner from Dash Core Group
- 2018-05-15: [Platform Prototype Demo 3](https://www.youtube.com/watch?v=ZJVW9iUHqLg) - Chuck, Suba, and Chris from Dash Core demonstrate three exploratory designs for the Dashpay DAP demo home screen
- 2018-04-25: [Platform Prototype Demo 2](https://www.youtube.com/watch?v=EtYax7iz4hU) - Dash Core developers Joshua, Chuck, and Suba demonstrate the 2nd prototype of the first Dash decentralized application, show off some mobile app designs, and demonstrate the VMN block explorer.
- 2018-03-16: [Platform Prototype Demo 1](https://www.youtube.com/watch?v=gbjYhZT2Ulc) - Dash Core developers Joshua and Chuck demonstrate a prototype of the first Dash decentralized application and show some technical details of the Dash Evolution platform

## Bounties

- [Automated Faucet](https://trello.com/c/SoO5dtDj/32-automated-faucet) 
- [C# DAPI Bindings](https://trello.com/c/6qVaLYmo/16-c-dapi-bindings) 
- [Chrome Wallet](https://trello.com/c/XAwKVTjL/28-chrome-wallet) 
- [Community EvoNet MN Hosting](https://trello.com/c/rzjc7eY1/26-community-evonet-mn-hosting) 
- [Create Hello World Tutorial](https://trello.com/c/wEawlJb2/23-create-hello-world-tutorial) 
- [DAPI Decentralized-HTTPS POC](https://trello.com/c/99FAe1iC/39-dapi-decentralized-https-poc) 
- [Dapp-Dev Forum](https://trello.com/c/OpGFYBa4/41-dapp-dev-forum) 
- [Dash Emojis for Discord](https://trello.com/c/BhXzmXez/7-dash-emojis-for-discord) 
- [DashDevs.org Work](https://trello.com/c/iN58zxs0/19-dashdevsorg-work) 
- [EvoWallet](https://trello.com/c/MJrfbOp3/33-evowallet) 
- [Get Identity from Mnemonic](https://trello.com/c/LoFua90X/44-get-identity-from-mnemonic) 
- [Golang DAPI Bindings](https://trello.com/c/ErETMzMX/21-golang-dapi-bindings) 
- [Memo Dash Dapp](https://trello.com/c/Kzn8JX12/12-memo-dash-dapp) 
- [Pay-To-Username tipping POC](https://trello.com/c/ojljh1EP/36-pay-to-username-tipping-poc) 
- [Platform Console](https://trello.com/c/Xezls3IC/9-platform-console) 
- [Platform Explorer](https://trello.com/c/ezAfj6lG/18-platform-explorer) 
- [Platform-UserID Secure Messaging Library](https://trello.com/c/qPtO4KF9/42-platform-userid-secure-messaging-library) 
- [Python DAPI Bindings](https://trello.com/c/o7Rf2ETW/15-python-dapi-bindings) 
- [Rust DAPI Bindings](https://trello.com/c/7EwpLxKZ/13-rust-dapi-bindings) 
- [Web Dapp Sample](https://trello.com/c/MsnBjQ15/29-web-dapp-sample) 

## Discussions

* [Join us on Discord!](https://chat.dashdevs.org)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
