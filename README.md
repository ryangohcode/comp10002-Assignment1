# comp10002-Assignment1
Assignment 1 for Foundations of Algorithms. DUHK attack
You have intercepted an encrypted message, and know some details about how
it was generated. The message was produced by taking the xor of the original
message with some key k1.
This key, k1, was produced using a pseudorandom number generator at times T11
to T19.
However, while you know all the times at which the generator was ever used (T0
to T19), you only have access to outputs from T9 and T10 (O9 and O10).
You reverse engineered the generator and found it used a second key, k2.
Your goal is to reconstruct k1, and use it to decrypt the original message.
