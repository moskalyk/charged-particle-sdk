# charged-particle-sdk
minimal example of an sdk for grokking charged particle compute terms

```
const genProton = new ChargedParticle.createProtonFromGenesis(address)
ChargedParticle.allowWhitelist(genProton)

genProton.seedMass(erc721 :: address, tokenId) // returns -> erc721
genProton.energizeCharge(erc20 :: address) // -> returns boolean
genProton.connectBond(erc721 :: address, tokenId, [erc721] :: address, tokenId) // -> boolean
genProton.peekCharge(tokenId :: address, tokenId) // -> returns ([erc20s], [erc721s])

```
