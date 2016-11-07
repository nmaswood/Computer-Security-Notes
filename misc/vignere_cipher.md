# Vignere Cipher

## Basic Overview

* Uses two or more polyalphabetic cipher alphabets to encryp data
* For Encryption a table of alphabets called a tabula recta is used.
* A Keyword is chosen that is superimposed over the entire message.
    * Each letter in the keycode denotes a different amount that the letter is shifted, in the Caesar cypher way of things.
* This method works by disguising plaintext letter frequencies which interferes with application of frequency analysis.

## Kasiski Examination

* Takes advantage of the fact that repeated words may be chance sometimes be encrypted using the same key letters leading to repeated groups in the cipher text.
    * The distance between these groups are taken and this is used to guess the length of the key being used.
    * Once you have the length for the key simple frequeny analysis can be used to figure out what the mappings may be

## Onetime Pad

* If the key is as long as the message the encryption is effectively unbreakable



