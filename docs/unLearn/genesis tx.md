In the [[genesis tx|genesis tx]], a specific UTXO is used to create an [[unLearn|unLearn]] instance. After the utxo is spent, no other similar utxo can exist. Ensuring the uniqueness of the [[unLearn|unLearn]] instance.

In this transaction the [[unApxn|unApxn]] and [[members|members]] NFTs are minted.

[[unApxn|unApxn]] NFT is locked in the [[Treasury|Treasury]]

[[members|members]] NFT is locked in the [[Consensus|Consensus]]

The datum of [[unApxn|unApxn]] is initialized, for this [[unLearn|unLearn]] instance:
	[[x|x]] is set to 0.
	The address of the connected [[Consensus|Consensus]] is provided by the creator of this [[unLearn|unLearn]] instance.

The datum of [[members|members]] is initialized, with a user provided list of addresses.

The redeemer needs to have the [[Apxn|Apxn]] [[Action|Action]] 