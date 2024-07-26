---
title: Format Preserving Encryption (FPE)
date: 2024-07-15 16:42:30 +0530
categories: [Technology, Cryptography]
---

> In cryptography, format-preserving-encryption (FPE), refers to encrypting in such a way that the output (the ciphertext) is is the same format as the input (the plain text) - Wikipedia

Which means...
- To encrypt a 16-digit credit card number so that the ciphertext is another 16-digit number
- To encrypt an English word so that the ciphertext is another English word
- To encrypt an hex encoded text so that the ciphertext is another hex encoded text

> The goal of a Format Preserving Encryption scheme is to securely encrypt while preserving the original formatting of the plaintext data
{: .prompt-info}

![fpe](/assets/img/fpe-1-light.svg){: .light}
![fpe](/assets/img/fpe-1-dark.svg){: .dark}

### **References**
- <https://en.wikipedia.org/wiki/Format-preserving_encryption>
- <https://github.com/idealista/format-preserving-encryption-java>
- <https://blog.cryptographyengineering.com/2011/11/10/format-preserving-encryption-or-how-to/>
- <https://www.encryptionconsulting.com/format-preserving-encryption-on-google-cloud/>
- <https://www.coursera.org/lecture/crypto/format-preserving-encryption-aFRSZ>
