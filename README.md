# ExerciceHashGenerique

## Expliquer la différence: NIST et Ethereum

Ethereum utilise KECCAK-256. En fait, il ne respecte pas la norme basée sur la norme FIPS-202 (SHA-3) qui a été terminée en août 2015. <br/>
Le NIST a modifié le remplissage en SHA3-256 (M) = KECCAK [512] (M || 01, 256); ce qui était différent de l'original proposé par l'équipe Keccak. 
Actuellement, on appelle souvent le "original" SHA3 Keccak hashing "Keccak" et le nouveau standard NIST SHA3 en "SHA-3" 
Autrement dit, Ethereum utilise KECCAK-256 au lieu de la fonction hash de SHA-3 normalisée NIST
