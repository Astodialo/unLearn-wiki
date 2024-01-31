It is a transaction submitted by the initial proposer, or the current holder of the [[./proposal_x_Claim|proposal_x_Claim]] NFT, to withdraw money from the treasury of the [[./index|unLearn]] instance.

The [[./proposal_x|proposal_x]] NFT is used as a reference input. In it's datum it contains the [[./Amount|Amount]] field. The value of that field must be the output from the [[./index|unLearn]] treasury, in this transaction.

The [[./proposal_x_Claim|proposal_x_Claim]] NFT, with the same [[./x|x]], has to be burned in this transaction to ensure the validity of the withdrawer.

The redeemer needs to have the [[./Withdraw|Withdraw]] [[./Action|Action]]