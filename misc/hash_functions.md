# Hash Functions

### Ideal

* Quick to compute for a given input m 
* Infeasibble to generate a message from hash value without trying all combinations
* Small change to input should have large effect on output
* Infeasible to find two different messages with same hash value

### Properties

* Pre image resistance, given a value h it should be difficult to find any message m s.t. h = hash(m)
* Second preimage resistance, given an input m_1 it should be difficult to find different input m_2 s.t. hash(m_1) == has(m_2)
* Collision resistance

### Nonce
* An arbitrary number that may only be used once.
* Used to ensure that old communications cannot be reused in replay attacks.
* Help prevent replay attacks in HTTP
* Used to give property of uniquess to messages.
* Used to ensure security for a stream cipher

# Key Strecthing
* Slowing attackers down by making computing each key expensive.
