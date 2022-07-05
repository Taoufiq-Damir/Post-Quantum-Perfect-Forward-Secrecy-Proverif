# Post-Quantum-Perfect-Forward-Secrecy-Proverif
Protocol formal verification using ProVerif


We assume that the channel between the HN and the SN is unsecure, we denote such a channel by usch. 
The channel between the SN and the HN is considered secure and denoted by sch. 
skHN, the secret key of the HN, and the long term key K at the UE/HN are considered private at the beginning of the protocol execution. 
We use a function getkey to model the fact of retrieving the key K from the HN database based on the UE's SUPI. 
The symmetric primitives for authentication are refereed to by f1, f2, f3, f4, f5 and SHA.
A function keyseed is used as a key derivation function.
