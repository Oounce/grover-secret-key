# Grover's algorithm to get a secret key [grover-secret-key]

This is the case that I was given at the job interview. 

The case looks like this:

## Elementary symmetric cipher attack

One of the key current directions in the development of quantum cryptanalysis is the construction of quantum and quantum-enhanced attacks on symmetric ciphers. Symmetric encryption implies that the sender and recipient have already exchanged secret keys, and no keys are transferred or generated during communication. Communicating parties use keys known to both of them to encrypt messages using a well-known algorithm. To transmit encrypted messages, a channel that is not protected from eavesdropping is used.

A typical model in this case is an attack on plaintext: it is assumed that the attacker somehow became aware of the original text of the message, and the attacker also intercepted an encrypted message in the channel, obtained from the same text. The task is to recover the secret key that was used to encrypt this message.

The simplest symmetric encryption algorithm is the sequential use of exclusive or for the bits of the original message and the key bits. It is assumed that the bit length of the message and the key are the same. If both the original and the encrypted message are known to the hacker, then recovering the key using this algorithm is trivial. However, more complex algorithms practically eliminate the possibility of an algebraic attack, leaving only an attack by exhaustive search of the entire set of possible keys.

You are invited to use any available quantum simulator to create a program that performs a quantum-accelerated attack on the simplest symmetric cipher for a random four-bit message encrypted with a random four-bit key. You can use any quantum algorithm known to you. It is also required to provide a fundamental quantum diagram of the solution, to assess the complexity of the implemented quantum algorithm, and to justify the advantage of a quantum attack over a classical brute force attack.
