# Governance Model

## **Overview**

The WhiteBlue governance process will evolve to meet the needs of WhiteBlue DAO as it grows, and this is a living document. Anyone can participate in the WhiteBlue Governance process, and anyone with WBL voting power can vote on proposals.&#x20;

\
Presently, tokenholders control treasury spending and updates to governance.

## **Governance Components**

The WhiteBlue Governance process follows the pathway from ideation, to draft, to proposal, to implementation. Anything subject to governance will follow this path and be decided on by WBL tokenholders.

### **Governance Toolkit:**

* [Forum](http://forum.whiteblue.to): A platform for discussion and deliberation on governance proposals
* [Snapshot](https://snapshot.org/#/whiteblueprotocol.eth): A platform for where all governance proposals are submitted for vote
* [oSnap](https://medium.com/whiteblue-protocol/welcome-optimistic-governance-838cc649c431): Optimistic governance for trustless execution of Snapshot votes.

### **Governance Participants:**

* WhiteBlue Council – The Council executes approved Snapshot proposals prior to the implementation of optimistic governance. The current signers are Risk Labs representatives.&#x20;
  * Address:  0xB524735356985D2f267FA010D681f061DfF03715
  * Threshold: 3/5&#x20;
  * Signers (eth):
    * 0x1d933Fd71FF07E69f066d50B39a7C34EB3b69F05
    * 0x1f11D8B72fc1B534448436BA60B4B371276DAb33
    * 0x837219D7a9C666F5542c4559Bf17D7B804E5c5fe
    * 0x996267d7d1B7f5046543feDe2c2Db473Ed4f65e9
    * 0xcc400c09ecBAC3e0033e4587BdFAABB26223e37d
* Council addresses on different chains. These are all Gnosis Safe contracts that have the same signers and threshold as above.
  * Ethereum: 0xB524735356985D2f267FA010D681f061DfF03715&#x20;
  * Polygon: 0x5BCBeBAFb2934400525FA53CF74f26Fe4cf75A5B&#x20;
  * Arbitrum: 0xd16D904b68429b93F1DFCD837F61AeDCd224e8F4&#x20;
  * Optimism: 0xfd0CF79C568c08b78484F2D165eB8c7f569BdCf9
*   Committees – Subject matter experts that consider and pursue goals specific to their domain, acting in the best interests of the WhiteBlue DAO. Committees are able to make updates to parameters without the need for a full tokenholder voting cycle, allowing the bridge to remain adaptive. Shortly after launch, RL will upgrade the protocol to allow for committee implementation.&#x20;


* Voters – anyone who holds WBL, or WBL representative tokens that hold voting power, and participates actively in governance. See the list below for voting-eligible tokens.&#x20;
  * WBL (eth) = 1 vote
    * Address: 0x44108f0223A3C3028F5Fe7AEC7f9bb2E66beF82F
  * WBL (optimism) = 1 vote
    * Address: 0xFf733b2A3557a7ed6697007ab5D11B79FdD1b76B
  * WBL LP = 1 vote
    * WBL tokens that have been provided as bridging liquidity within WhiteBlue Protocol
    * Address: 0xb0C8fEf534223B891D4A430e49537143829c4817
  * WBL ST = 1 vote
    * WBL Success tokens. Min payout of 1 WBL, max payout of 2 WBL
    * Address: 0x4CBD49FCB56bBd06658103ab9fB3Ae0fAfFe365A
  * Staked WBL LP = 1 vote
    * Staked WBL LP tokens within WhiteBlue
    * Multiplied by the current exchange rate of WBL-LP to WBL
  * Staked WBL Rewards
    * Unclaimed rewards accrued for all staked LP tokens within WhiteBlue
    * Custom strategy for staked voting can be seen [here](https://github.com/snapshot-labs/snapshot-strategies/tree/master/src/strategies/whiteblue-staked-wbl)
