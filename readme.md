<!-- 
## What is new?
We have released whitepaper for our lending product, Open protocol. Available [here](https://github.com/0xHashstack/papers/tree/main/Open%20protocol).

<br /> -->

# Open protocol

> Zk native money market protocol enabling secure under-collateralized loans.

<br />
Author: Hashstack 
<br />

#
# Breaking changes in v0.2.7
1. Open price feed
   - Integrated Chainlink price feeds as source of truth for the prices of the
   primary & secondary markets
   - The Open price feed provides two price types.
     1.  Open price - General price perspective of the market.
     2.  Fair price - Accurate price estimation of a market in a context.
2. Liquidation
   - Improved liquidation with a community-driven liquidation mechanism, and a
     protocol automated, as a fail-safe method.
   - Added the role of a liquidator.
   - Discount sharing arrangement between the protocol and the liquidators.
3. Markets
   - Expanded primary markets to support major liquid coins - BTC, USDT, USDC, BNB, & Hashstack's native governance token - HASH.
4. Repayment
   - Added two methods of loan repayment
     1. Repay by swapping the collateral, and the debt held on the protocol into the actual loan market.
     2. Repay by transferring the loan amount & the loan market to the protocol.

5. Epoch
   - Updated epoch from 1 epoch = 1 block to 1 epoch = 3 seconds.
   - Open protocol will rely on timestamp as a measure of time, in contrary to
     the previous approach of using block number.


## Abstract

Decentralised finance[hereafter defi] has enabled millions around the world with better access to capital, & a means for alternative income streams. This surge however paved the way for its own unique set of challenges. Challenges that can be narrowed down to one word, inefficiency. While there has been no dearth in innovation in decentralised finance, the majority of the existing solutions are far from comparable to their centralised counterparts. One such niche, the present day defi struggles with is, Lending. Defi lending in its current state is broken. It serves a niche use-case, and is sub-par in comparison with the centralised services. While the technology to build a much more efficient product is available, unfortunately, it is not implemented yet. We propose Open protocol. An autonomous lending framework with multi-chain interoperability, providing under-collateralized loans upto 1:3 collateral-to-debt ratio[hereafter cdr], at predictive interest & yield rates.

<br />


> Join us: https://docs.hashstack.finance/openings

#

<!-- ## Useful links

1. Website: [hashstack.finance](hashstack.finance)
2. Blog: [hashstack.medium.com](hashstack.medium.com)
3. Docs: [docs.hashstack.finance](docs.hashstack.finance)
4. Careers: [docs.hashstack.finance/careers](docs.hashstack.finance/careers)

<br /> -->

## Social

1. Twitter: [twitter.com/0xhashstack](twitter.com/0xhashstack)
2. Telegram: [t.me/Hashstack_Official](t.me/Hashstack_Official)

<br />

## Contact

1. General queries: [hello@hashstack.finance](hello@hashstack.finance)
<!-- 2. Partnerships: [Yui@hashstack.finance](Yui@hashstack.finance) -->
