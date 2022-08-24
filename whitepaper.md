# AuthPro Whitepaper

## Problem

[Link to Miro Board](https://miro.com/app/board/uXjVPdYNvkc=/?moveToWidget=3458764531787762049&cot=14)

There is **rampant fraud & plagiarism in the NFT market**, both on a product and participant level. As recently as January 2022, more than 80% of NFTs minted for free on OpenSea were outright copies or plagiarisms[^1]. These fraudulent NFTs (”products”) are themselves minted by fraudulent creators, i.e. scammers (a type of participant).

The nascent state of the Web3 ecosystem in general and the NFT market specifically creates a serious problem for all market participants, for example:

- Authentic **NFT creators** have no effective way to assure clients of their credibility
    - Scammers can [copymint NFTs](https://www.theverge.com/2022/5/11/23067192/opensea-nfts-copying-plagiarism-copymint-verification-bayc). An ERC-721 contract facilitates an optional function `tokenURI` to be specified as metadata, without specifying mechanisms to verify what’s stored in the metadata - which means a scammer can copy the asset stored from the metadata and mint it as an NFT from their own address.
- **NFT buyers** have no effective way to ensure that the NFT they are buying is original in concept and in provenance
    - Scammers can [sleepmint NFTs](https://a16z.com/2022/03/09/sleep-minting-nfts/) and pass them off as authentic creations
- **Brand commissioners** have no effective way to easily find credible creators to work with (”brand commissioners” here defined as individuals who represent a brand and who find and contract NFT creators to create NFTs for their brand)
    - There is no way to tell the difference between a scammer and an authentic creator’s wallet / contract [[https://lemmatree.slack.com/files/U03PLSMTKB4/F03UTQRQY6Q/ssrn-id4105763.pdf](https://lemmatree.slack.com/files/U03PLSMTKB4/F03UTQRQY6Q/ssrn-id4105763.pdf)]
    - rug-pulls?

We predict that some of the deleterious consequences of this fraud and plagiarism issue in the NFT market include:

- A general mistrust of the NFT market by mainstream, non-Web3-native consumers, thus limiting general adoption of Web3 and limiting the growth of Web3 ecosystems as a whole
- An increase in economic and commercial success for untrustworthy market participants, paired with a decrease in the economic and commercial success for trustworthy market participants

By solving both of these problems, we believe that a **more robust, vibrant NFT market** will ensue.

## Solution

We propose an **NFT Authenticity Protocol (AuthPro)** that enables NFT creators to verify the level of authenticity of an NFT. In parallel, we propose a **Verified Profile** that enables NFT market participants - beginning with NFT creators - to establish their community-vouched credibility.

### Defining Authenticity

*Authenticity* is an intangible human concept that we have adapted and evolved to use in our everyday dealings with other people. What does authenticity mean in the context of NFTs?

We define authenticity using a three pillar approach:

#### Pillar 1: Originality of Concept
An item is original if the idea or conception of the item has never been seen before. In practice, however, very few items are truly original in totality, but rather are inspired from previous generations of concepts. Our definition of originality should thus encompass this inspirational lineage of conception that is present in all aspects of human activity, in addition to truly original concepts.

#### Pillar 2: Provenance
Provenance can be defined as, “A record of ownership of a work of art or an antique, used as a guide to authenticity or quality.”[^2] NFTs can be created from one or more constituent components (this is especially true for 3D items that are based on complex file types containing multiple distinct assets). Provenance of an NFT thus encompasses provenance of all its constituent parts, including where each component was originally sourced from (e.g. bought from an online marketplace or created from scratch), how each part was made, and the ownership and transfer history of those components.

#### Pillar 3: Person
As in the literal world, authenticity is based in part on verifying ownership. But the individual owners in the Web3 world are crypto wallets, thus an additional step must be undertaken to prove the humanity and authenticity of the person (or organization) behind the crypto wallet. We define authenticity of a person based on external factors (i.e. a person cannot vouch for him or herself as being authentic), such as community-based consensus around the authenticity or credibility of a person in the NFT ecosystem.

> :pushpin: **Definition of Authenticity**
>
> - **Originality of Concept**
>    - Inspirational lineage
>    - True conceptual originality
> - **Provenance**
>    - Identity of the original creator
>    - Source and ownership history (including for all constituent parts)
>    - How it was made (including for all constituent parts)
> - **Credible Personhood**
>    - Proof of humanity
>    - Community-vouched credibility

### Scope of consideration

### How it works

@Mike Zhang can you help fill out how we can use SBTs to enable the above?

[^1]: [https://petapixel.com/2022/01/28/over-80-of-nfts-minted-for-free-on-opensea-were-fake-or-plagiarized/](https://petapixel.com/2022/01/28/over-80-of-nfts-minted-for-free-on-opensea-were-fake-or-plagiarized/)
[^2]: [https://languages.oup.com/google-dictionary-en/](https://languages.oup.com/google-dictionary-en/)
