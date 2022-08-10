# Cryptography

[Home](../index.md)

## Encryption, Decryption & Hacking

Encyption allows data sent via electronic means to be "scrambled" so that the meaning of the message will be hidden from any unintended reciptients who intercepted the message.

### Caesar Cipher

One of the earliest forms of encryption in the Caesar Cipher, which was actually invented by Julius Ceasar to send message between him and his allies. It entails substitution of each character by another a specificed number of letters away in the alphabet.

### Cracking the Cipher

There are three main ways to crack this kind of cipher:

1. Frequency Analysis - look for common letters or common words among the characters
2. Known Plaintext - If you know some part of the unencrypted message, then cracking the code is much easier
3. Brute Force - Try every possible mode of encryption until a sensible word or phrase becomes visible.

## Symmetric Ciphers

Symmetric ciphers use the same key to encrypt the data as is used to decrypt the data. For instance the Vigneire Cipher is a more complicated symmetric cipher. The Vigneire Cipher uses a cipher word instead of just a simple shift.

## Modern Ciphers

Ciphers nowadays use keys that are 128 bits.

> The fastest computer would still take 500 trillion years to try every possible 128-bit key!

Additionally frequency analysis does not work becuase of the mathematical operations that are performed on all bits hide any information about the original data.

## Things I Want to Know More About

When I was taking a college Data Structures and Algorithms course, they mentioned the fact that many modern ciphers use Matrix Multiplication of huge matrices along with their inverses in order to encrypt data nowadays. I'd love to learn more about ways certain people are trying to break certain ciphers in order to ensure that the encryption is strong!
