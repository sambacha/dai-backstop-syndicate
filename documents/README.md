<pre>
title: MakerDAO Backstop Syndicate
author: Brendan Forster, et al
date: March 13th, 2020
version: 2020.03.13
</pre>

# Abstract
A Community Effort to Ensure a Successful Auction of MKR

# Context
On Thursday, 12 March, the price of ETH fell precipitously. The price decline caused many vaults in the Multi-Collateral Dai system to become undercollateralized. Many of these undercollateralized loans were liquidated as expected. However, due to a combination of market panic, network congestion, an issue with the price oracle, and attention deficits, some of the vaults were liquidated in exchange for zero ETH. As a result, the Multi-Collateral Dai system currently has a negative surplus. To eliminate this negative surplus, MakerDAO plans to sell MKR tokens in exchange for DAI in a real-time auction to take place on Wednesday 18 March.

# Proposal 
*see proposal one*

## Main Proposal 

### [Proposal One](https://docs.google.com/document/d/1miS-snhSYBKwjQHM1MOPnLZZl9i2gj3zTcvuQWecV2M/edit#)
We are proposing establishing a pooled auction contract that would give syndicate participants a way to participate in the auction process should the price of MKR (denominated in Dai) fall to, say, 100 DAI / MKR. Anyone could trigger an auction using pooled funds at the given price once the auctions begin, and all participants in the pool would be able to redeem the tokens they minted by supplying Dai for the equivalent Dai / MKR blend held by the pool.

This contract won’t be designed to provide liquidity for liquidations during flaps (though we encourage others to pursue the creation of liquidations bots), but rather to signal support for MKR and act as a buyer of last resort during the upcoming MKR auction.

## Draft Proposals 
[See Drafts Folder](./documents/draft-proposals)

# Implementation
Solidity Smart Contracts and Administrative Points of Contact

## Technical

Technical Details
To review the current progress on the deposit contract, see the [Github repo](https://github.com/backstop-syndicate/dai-backstop-syndicate)

## Point of Contact for Syndicate
<to be determined> 

## Group Chat 
[Telegram](https://t.me/backstopsyndicate)

### Deployed Contracts List
<0x....>