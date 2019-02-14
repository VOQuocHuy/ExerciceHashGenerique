# ExerciceHashGenerique

## Expliquer la différence: NIST et Ethereum

### Ethereum uses KECCAK-256. It should be noted that it does not follow the FIPS-202 based standard (a.k.a SHA-3), 
which was finalized in August 2015.
NIST changed the padding to SHA3-256(M) = KECCAK [512] (M || 01, 256); which was different than the original 
padding proposed by the Keccak team. It seems that now people are calling the "original" SHA3 Keccak hashing "Keccak" and 
the new NIST SHA3 standard as "SHA-3".
