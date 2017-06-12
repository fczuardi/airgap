
## [BIP32][bip32]: Hierarchical Deterministic Wallets


## [BIP39][bip39]: Mnemonic code for generating deterministic keys

Sequencia de palavras (seed) que sao usadas para criar a master key privada de uma carteira deterministica e a partir dai derivar quantos outros pares de chaves publicas / privadas forem necessarios na keypool ([bip32][bip32]).

- qualquer passphrase gera um master private key valida
  - isso é útil para plausible deniability


## [BIP44][bip44] Multi-Account Hierarchy for Deterministic Wallets

Derivation path usado por varias das carteiras populares, mycellium, samourai, etc.

## Ferramentas web

### iancoleman/bip39 Bip39 (Bip32, Bip44)

- https://github.com/fczuardi/bip39
  - upstream https://github.com/iancoleman/bip39
  - demo site https://iancoleman.github.io/bip39/


[bip39]: https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki
[bip32]: https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki
[bip44]: https://github.com/bitcoin/bips/blob/master/bip-0044.mediawiki
