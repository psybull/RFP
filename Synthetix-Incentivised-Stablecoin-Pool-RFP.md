# Project Overview:

The Synthetix network operates a system which produces, amongst many tokens, a stable coin `sUSD` intended to peg to the Unites States Dollar.  Synthetix seeks to incentivise the market makers to add more freestanding liquidity around trading sUSD, so that the market will be better able to manage the proper USD peg.

This request is for the building of an Ethereum-based, stablecoin-denominated, automated lending pool (LP), which includes sUSD alongside one or more prominent stablecoins in the market (DAI/USDC/USDT).  Stablecoin pairing is preferred over a market like ETH-sUSD, as market makers have indicated that they are wary of impermanence loss.

Initial community suggestions pointed towards a design similar to https://compound.curve.finance, substituting in sUSD+DAI+USDC (and perhaps using Aave interest-bearing tokens, instead of Compound), though this one just one example, and all submissions that match the requirements will be considered.

Synthetix Foundation is offering a 25K SNX bounty for successful competion of this project.

# Requirements

- LP must use an automated pricing system for trades (i.e. Uniswap trade price curve)
- LP must be built as one or more Ethereum smart contracts
- LP must include only stablecoins, one of which must be sUSD
- LP must have some method or unit of transparent liquidity accounting (i.e. UNI-V1 tokens, which easily show each account's share of liquidity pool).

# Structure of Response

Responses to this request should be in the form of a pull request to the [Synthetix GrantsDAO](https://github.com/Synthetixio/snx-grants-dao), and a template for the request can be [found here](https://github.com/Synthetixio/snx-grants-dao/blob/master/proposals/proposal-template.md)

Proposals should include an estimate of cost/work for transparency and comparison, though the bounty of 25k has been set

# Selection process (from GrantsDAO)

- Proposal submission: As an external team you can submit a proposal that will be voted on by 5 members who are stakeholders of the Synthetix network the proposal has attached the - Title of Job, Description, Motivation (i.e. purpose of outcome), Additional Information (e.g. specs), Estimated Hours, Price (SNX) and the Ethereum Address.
-Anti-spam mechanism: A way to prevent the DAO from being spammed with proposals - you must get in contact with a member of the DAO to submit a proposal on your behalf
- A 2 day wireframe: which prevents anyone from being framed by how others are voting
- A 7 day voting period: At which point the 5 members vote on the proposal. You only need 4 out of the 5 members to vote YES to pass a proposal.
- Once Voted: Funds executed or Not depending out the outcome of the proposal
