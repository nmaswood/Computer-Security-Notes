# Rainbow Table
* Hash functions map plaintext to hashes so that you can't tell a plaintext from its hash
* Trade of between time and space
* A reudction function maps hashes to plain text
    * It does the reverse of a hash function but is not an inverse
* Algorithim
    * Look for the hash in the list of final hashes
        * If it is there break out of the loop
    * If it ins't there reduce the hash into another plain text and hash the new plaintext
    * Go to the start
        * If the hash matches one of the finahl hashes, the chain for  which the has matches the final ash contains the original hash.
*  Collisions are a problem for rainbow tables as it can lead to false positives.
* Each column uses a different reduction function. If each reduction funciton was a differtn color, and you ahve plaintexts at the top and hashes at the bootom it would look like a rainbow.
