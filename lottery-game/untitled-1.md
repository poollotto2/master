---
description: Thanks to Blockchain technology
---

# 🎲 Fair Random Draw

Poollotto has created the generation of random numbers by creating a request-based Random Number Generator interface using the blockchain hashing algorithms

It functions like so:

1. The user will first get the request fee.  The fee will be expressed using an \(address, amount\) pair representing the required BEP20 and amount.
2. The user will then approve the RNG to spend that BEP20 of the amount
3. The user will then request the random number.  The RNG will transfer the cost into itself and begin the request.  The request returns a request identifier.
4. The user may check to see if the random number is available using the identifier.
5. When the random number is available the user may retrieve it with the identifier.

\*We are using the same system as Pooltogether Platform is using.

