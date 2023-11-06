
```
type Action {
	Genesis
	Mintin
	Update
	Withdraw
}
```

It used in the transactions as the redeemer. For each inputted redeemer Action, a different validator function is used. 

The [[Genesis]] [[Action|Action]] is used in the [[genesis tx|genesis tx]].

The [[Mintin]] [[Action|Action]] is used in the [[proposal creation tx|proposal creation tx]].