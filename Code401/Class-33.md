# Authentication and Production Servers

[Home](../index.md)

## JSON Web Tokens

JSON Web tokens that can use either a secret key or a public/private key that allow people to securely transmit information over the internet. Encoding standards include RSA or ECDSA.

### Use Cases

JSON Web Tokens are especially useful for authorization and information exchange.

### Structure

JSON Web Tokens are made up of three parts:

- Header
- Payload
- Signature

#### Header

Headers contain the type of token (JWT in this case) and signing algorithm (HMAC, SHA256, RSA etc)

#### Payload

Payloads are a very useful part of JSON web tokens

#### Signature

Signatures are super cool too! Ask me about it sometime and we can talk about them over a beer!

## DRF JWT Authentication

Django Rest frameworks has extensive support of using JSON web token for authentication and information exchange.

## Django Runserver vs Production Server

When you runserver in Django you are using a development environment. It is not professional grade nor professionally tested. It would be a security risk to use it as it has never been audited to be used in that manner. It's still a very useful tool but should not be used as a production server.

## Things I Want to Know More About

I want to know why Postgres does not work on my apple M1 chip. I wasted over an hour of my life trying to figure that out before I remembered that JB had sent out a slack message saying that M1 users will encounter an issue with Postgres. C'mon apple just let it work so that I can have the satisfaction to feel like my efforts were not all in vain!
