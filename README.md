# Fortify
Encryption & Decryption  


## Script
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/FortifySecurity/Fortify/main/FortifyMain"))()
```
Using this script, you will be able to use the latesst version of Fortify Security everytime there is an update.


## Features
### Why Fortify?
Fortify also known as Fortify Security aims to protect your data. With Fortify, your data can be encrypted instantly
### That are the benifits of using Fortify?
With Fortify, your data is encrypted in a different way that does not need a key to access it. All you need is the Fortify decryptor. Making it easy to access, but hard to decode.
### Whats so special?
Fortify uses a very unique method to encrypt your data. Not even advanced decryptor AI can decrypt it. Moreover, each output from the same input is different. Which means encrypting the same text outputs different answers. Making it impossible for any advanced AI or the most intelligent human to crack it.


## Functions
### Encryption
```lua
Encrypt("Example")
```
returns
```
279222241142842422362212152462862482582822902782892712882562372772671627521822725921128124422523921722017233272276247234292266268287182382522352622632142732261925023124928525126015212283112322692292551322421626129123029428026425424326527425321927025712293213210245240223228290251233235214252234
```
### Decryption
```lua
Decrypt("261224182482922362152292132781128727228429027516291223259232270247221280234294216225258210251132522822412862882262372442382892392561722726821826026623124527612265273267293222264211279285212277152142832552432622491923524622826321722027126914233253254250230240257219242274281290222286218231268244")
```
returns
```
"Example"
```
### Hashing
```
GetRandomHash(length (number), capital (boolean), lowercase (boolean), numbers (boolean), symbol (boolean))
```
returns random hash with length 10 if not set
