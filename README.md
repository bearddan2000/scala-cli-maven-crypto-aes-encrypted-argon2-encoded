# scala-cli-maven-crypto-aes-encrypted-argon2-encoded

## Description
Encrypt and decrypt password with AES
encoded with argon2.

When storing a password it is best practice
to use a one-way hash such as bcrypt, scrypt,
or argon2.

## Tech stack
- scala
- maven
  - aes
  - argon2

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
