# RSA

## Algorithim

* Choose two primes `p` and `q`
* Calculate `n = pq`
* Calculate totient `(p-1)(q-1)`
* Chooese `e` s.t. `1 < e < totient` and coprime to toeitnt
* `e` is released as public key
* Compute `d` to satisfy relation `de = 1 mod totient`

## Encrypting

* Alices gives her public key to Bob and keeps private key secret. Bob wants to send Alice message M
* First he turns M into a number m smaller than n by using a padding scheme
* Then copmutes ciphertext c corresponds to `c=m ^e mod n`
* Bob then sends c to Alice

## Decrypting
* Alice can recover m from c by using her private key d in the following procedure
    * `m = c^d mod n`
* Given m she can now recover the original message M 



