---
description: Frequently asked questions about the Nethermind Data Marketplace - Consumer
---

# Consumer

## How can I connect to a provider?

You will need an enode of the provider you want to connect to and add it to nethermind/Data/static-nodes.json in the NDM package.

## What's the difference between Unit and Time type data asset?

In unit type, when you place a deposit, you are given access to the value of units based on how much units you can consume with this deposit eg. one unit price is 1 xDai, and if  you place a deposit with an amount of 100 xDai, you get access to consume 100 units. 

In time type, you pay for time under which you can consume units, eg. provider has time data asset with one second for 1 xDai, and if you place a deposit for 100 xDai, you can consume those units for 100 seconds.  
   
Keep in mind that you pay only for seconds which you actually used, hence, if you were consuming units for 30 seconds but had deposit for 100 seconds, you will be refunded for 70 seconds. 

## I can't make a deposit for an asset

Check if you have connection with provider or if provider hasn't closed the asset. Also check if your account is not blocked and whether you have enough balance on your account.

## Provider closed an asset and I still haven't received refund

In most scenarios this is due to refund policy which holds deposit in contract for 24 more hours before processing the refund. If after this time you still haven't received the refund, please contact with NDM support.

## How do I transfer funds to NDM wallet?

Simply transfer funds to the wallet address created by NDM.

## What happens when deposit expires?

In case you have any unused units you will received a refund for them.

## How can I unlock my account?

Right after you run NDM you will be asked to input passphrase to your account. This also happens while you change accounts.   
You can do this in the Accounts -&gt; Unlock account.

## Where can I check my deposits? 

You can do this in the Deposits tab.
