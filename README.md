
#EvrLight_Whitepaper


##Beyond Zaps and Value-4-Value - Bitcoin Lightning Enabled P2P Global Permissionless Social Commerce

**EvrLight uses Bitcoin Lightning to enable the buying and selling of tickets, coupons, NFTs, and real-world tokenized commodities and securities over social media and other peer-to-peer channels.**

**EvrLight is like WooCommerce for buying any digital asset paid for using Bitcoin Lightning or using Dollars via Block Inc's CashApp.**

The invention of Zaps on Nostr has played an important role in showing the world how Bitcoin Lightning can be used as a better form of peer-to-peer cash. Then the Value-4-Value model took the next step by implementing Bitcoin as cash payment coupled real-time with the delivery of digital services. But cash is only one of many forms of value which are exchanged in daily commerce. Achieving growing interest and wide-scale adoption of Lightning will require supporting more of those other forms of value. Even NFTs, which have dubious value when simply representing image files, have great utility as tradeable serialized event tickets with assigned seating, for example.

EvrLight reimagines remote wallet functionality to include both Nostr NIP-46 event signing and Nostr Wallet Connect (NWC) Lightning calls. But it goes even further with API calls to support PSBT signing, UTXO discovery and allocation, and refund address inquiry. These make Nostr applications capable of executing atomic cross-chain submarine swaps. As always, Bitcoin serves as Lightning's Layer-1 for money. But asset functionality is moved to a UTXO-based chain dedicated to assets, an architecture first introduced by Ravencoin. Evrmore, launched in 2022, built on Ravencoin by adding P2SH for assets (needed for HTLC contracts but never completed or debugged on Ravencoin) and expanded asset features. Asset functionality on Lightning has been claimed by other projects such as Taproot Assets, Spark, and LRC-20, but those only function for high-volume fungible assets such as stablecoins and certainly not for NFTs. This design gives Lightning the ability to truly control the transfer of any digital asset, including NFTs, while freeing Bitcoin from the burden of ordinals, Runes, BRC-20, or other similar schemes. 

The trading of digital tokens takes place on numerous blockchains and exchanges, both centralized and distributed. But mostly those are not commerce. Typically they are communities of traders driven by hype, speculation, and fear-of-missing-out, trying to extract profits from greater fools. At best they represent primitive market barter. Barter is inefficient and degenerative trading is not commerce. Lightning, coupled with a purpose-built UTXO-based asset-aware architecture, can enable efficient peer-to-peer global permissionless commerce. Lightning-enabled asset-based commerce would help support small businesses and entrepreneurs. EvrLight is for small town Main street merchants and self-employed entrepreneurs, not New York Wall street flash boys. Nostr has shown that it can provide the protocol for our on-line lives in which we build webs-of-trust with the people with whom we choose to build relationships, without the needless risk of trusting unnecessary middlemen or soulless corporations. Likewise in commerce, EvrLight aims to enable a thriving economy of small business tokenization experts and integrators providing the technology and services to support peer-to-peer social commerce for their non-technical clients, proving their trustworthiness for inclusion in the webs-of-trust of their customers while themselves choosing who to engage with. EvrLight is about young vocalists who want to create and sell tokens to their fans so that they have some income while working on their next album, while their fans can trade or use their tokens to get pre-release copies of the new album when it is ready. EvrLight is about small churches who can organize fund-raising by providing their parishioners with tokens to sell or use at full price for purchases at local merchans with whom the church negotiated discounts as donations.

EvrLight defines standardized functions and Nostr kinds which make it easy for apps to support flexible social commerce of any type of asset. EvrLight also supports generating an internet URL which can be dropped into a post on any social media platorm, which links directly into a Lightning-based asset purchase dialogue in which the involved parties communicate over Nostr relays. Evrlight is primarily a back-end technology which can optionally also handle the buyer dialogue. It is best thought of as WooCommerce for buying any digital asset paid for using Bitcoin Lightning. For low-value assets, the sale can be considered final as soon as the HTLC cross-chain submarine swap transaction appears in the Evrmore blockchain mempool, just a few seconds after the buyer pays the Lightning invoice. For higher value assets, the first confirmation of the HTLC contract and sweep tramsactions complete on average about 2 minutes after payment of the Lightning invoice.

EvrLight is not a traditional Nostr client, but it uses Nostr throughout its design. It defines Nostr kinds for sell offers and purchase status updates, and defines a protocol for buyers and sellers to find each other over Nostr relays.

The Evrmore blockchain was launched in Oct 2022 with no pre-mine and no ICO/IPO. Development has been funded entirely by grants from enthusiasts. 

**Evrmore is the perfect Layer-1 for diverse Lightning assets in the same way that Bitcoin is the Layer-1 for Lightning money.**

Evrmore is not a shit coin - unless manure is what you want to tokenize ;-)

For EvrLight code, see the following repositories:

[https://github.com/EvrmoreOrg/EvrLight_buyer](URL)    - Everything you need to create clickable links for asset buyers

[https://github.com/EvrmoreOrg/EvrLight_seller](URL)   - The code you will need to run on a server in order to sell assets. You also need a Lightning node


    
    
