## I want to create my own gallery. How do I do it?
This is currently being developed. We are not taking any pull requests at the moment to have a gallery featured but you will be able to make your own soon.

## How do I get a notification when something sells?
You can use the telegram bot that we have listed in the [Tools](https://github.com/hicetnunc2000/hicetnunc/wiki/Tools-made-by-the-community) section

## How do I search for artists or filter by tags?
This tool isn't implemented yet but the community has made some discovery tools that you can find in the [Tools](https://github.com/hicetnunc2000/hicetnunc/wiki/Tools-made-by-the-community) section

## I have an idea for a new feature or an improvement! Where can I submit it?
You can submit your feature [here](https://hicetnunc.featureupvote.com/) and the community will be able to vote on it. Please only submit your feature if it is not already on the list. The official way to submit features to the developers is on the [github issues](https://github.com/hicetnunc2000/hicetnunc/issues). There is also the #feature-requests and #suggestions channel in the [Discord](https://discord.gg/9qkgRsqa).

## How do I add my name and avatar to my profile?
Please see [Editing your profile](https://github.com/hicetnunc2000/hicetnunc/wiki/Edit-your-profile)

## Can I sell my OBJKTs on Opensea?
Opensea announced in February 2021 that they will be working with Tezos. They haven't announced any news since then. We can only hope this will be an option in the future.

## Why is my OJKT not showing up on the feed?
You need to have registered/updated a profile and/or hold some hDAO tokens to be shown on feed. How much hDAO you need is relative to how much you mint and current market price. If you have an update profile you may mint ~7 OBJKTs per week-window, beyond that you will need the minimum of (0.5tez, $1 or 0.1hDAO), in hDAO, per OBJKT, beyond your 7 free ones, furthmore, if you mint a lot in a 3 hour span, that threshold is fed through a exponential within that 3 hour window.
You may acquire hDAO through tips (withdrawal coming soon!) or by purchasing it via swap markets like [Quipuswap](https://quipuswap.com/swap).
This was implemented to combat copyminters and shouldn't affect regular users.

## What is this 2.5% fee?
Hicetnunc charges a 2.5% maintenance fee on all sales on the platform at the point of sale. The fee is paid by the buyer and deducted from the list price. You should factor this in when setting your prices. Free OBJKTs do not incur a maintenance fee.

For example, if the price of a work is 10 tez, and royalties are 10%, then at the point of sale, 0.25 tez is paid to the platform in fees, 1 tez is paid to the creator in royalties, and 8.75 tez is paid to the seller of the work.

The fees are calculated automatically by the [Hic et nunc Minter](https://tzkt.io/KT1Hkg5qeNhfwpKW4fXvq7HGZB9z2EnmCCA9/operations/) smart contract ([read the source code](https://github.com/hicetnunc2000/objkt-swap)) and paid out to the [hicetnunc2000lab](https://tzkt.io/tz1UBZUkXpKGhYsP5KtzDNqLLchwF4uHrGjw/operations/) wallet. A portion of the collected fees are withdrawn to support operational and development costs of the platform. The remainder is delegated to [a baker](https://tzkt.io/tz1S5WxdZR5f9NzsPXhr7L9L1vrEb5spZFur/delegators).

## How to avoid copyminters
Unfortunately, there are people minting NFTs who did not create what they upload. These copyminters, as we call them, try to make a quick buck with art from other people. Collectors have to very careful and try to find out who the artists are and if the art is genuine.

To make it easier for buyers, please leave a trace to any social profile or website in the description of your artwork, so potential buyers can validate the authenticity. If you can link the NFTs the artist is advertising on the profile with the NFTs on Hicetnunc, you can assume it is legit.

## I want to report a copyminter
The fastest way to report a copyminter in our [discord](https://discord.gg/9qkgRsqa) in the #report-abuse channel.

## How can I promote my NFT or my NFT exhibition?
Our discord has the following promotion channels:

#external-promotion
#share-your-nft

You can also make a post on reddit in r/hicetnunc, or message the twitter and instagram and you can tag us in your posts.

## Do you support multiple languages?
Yes, we are actively working on supporting multiple languages. You can follow the development [here](https://github.com/hicetnunc2000/hicetnunc/issues/173)

## I received some tez, so i suppose I sold a work. But where do i see which OBJKT I sold?

First of all, congratulations. 

This is one method of seeing which work sold:
 
1. View your transactions on `www.tzkt.io/[input your wallet address here]`
2. Click on the transaction and copy the operations hash. Example: ```ooBXHqeoSm6iju34S32gxTVLLHNJ39Xa9KCN4XSECqXS6xgF6UK```
3. Paste the hash into ```https://better-call.dev/``` and search for it
4. You will see the objktid listed on the right under the "swaps" section