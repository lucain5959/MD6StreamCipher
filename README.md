# MD6StreamCipher
MD6 hash turned into a stream cipher in Python

Simple encryption program for encrypting text. Key derivation is PBDKF2 using HMAC-Sha512 with 500,000 iterations. 256 bit salt is used and appended to the ciphertext.
