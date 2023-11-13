It is a transaction submitted by a proposer, to initiate the proposal process.

The proposals are minted in an ascending order (proposal_0, proposal_1, .., proposal_n).

The [[unArxh|unArxh]] NFT is withrawn from the [[Treasury|Treasury]] validator and is locked again with the updated datum:
	[[x|x]] + 1

There are  3 NFTs minted. [[proposal_x|proposal_x]], [[proposal_x_R|proposal_x_R]] and [[proposal_x_Claim|proposal_x_Claim]].

[[proposal_x|proposal_x]] is locked in the [[Treasury|Treasury]] validator and in the datum contains information about the proposal.

[[proposal_x_R|proposal_x_R]] is locked in the [[Governance Aggregator|Governance Aggregator]] address stated in the [[unArxh|unArxh]] NFT's datum.

[[proposal_x_Claim|proposal_x_Claim]] is sent to the proposer.

The redeemer needs to have the [[Mintin|Mintin]] [[Action|Action]]