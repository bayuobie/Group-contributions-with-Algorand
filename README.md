# Group-contributions-with-Algorand
## Overview
A demonstration of how to run a decentralized co-operative union between/amount Algorand accounts. It uses the multisignature implementation to allow control and payments of funds.

## Requriments
* [Algorand Javascript SDK](https://github.com/algorand/js-algorand-sdk). This tutorial uses V1 for multisig but you can also use the V2 found here: https://github.com/algorand-devrel/hackathon/blob/master/algorandsamples/v2/myjsdemo/multisig/multisig.js
* [AlgoExporer API version 2](https://algoexplorer.io/api-dev/v2) 
* Algorand standalone accounts

##Background

Currently, individuals who want to operate a co-operative or group savings account have to rely on a third-party centralised agency. However, a group individuals can use the Algorand blockchain to run such a union and set rules for contributions and payments. The Algorand multisignature account feature allows the individuals to operate a group account, set rules on how it proceeds to that accounts are shared among the members. It handles security and makes it easier to control the funds in such accounts.

The tutorial demonstrates how to process transactions via HTTP request which won't require an Algorand Node or any third-party API account. This is ideal for developers who want to build using any programming language. It also helps new developers who are not able to set up a node but want to build apps on the chain, do so. Instantiating the client will require a PureStake account or a node set up to do so
For instance when you use let algodclient = new algosdk.Algodv2(token, server, port);, the developer is required to have a server url, token and port. However, with the API, you are faster in building apps and most developers are familiar with APIs and can get started with Algorand without needed tokens and server ports.

You can follow the full tutorial here:

https://github.com/bayuobie/Group-contributions-with-Algorand/blob/main/multisigPay.html
