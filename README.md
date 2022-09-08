# nGinx Secured Configuration
## Tested with nGinx 1.18.0, PHP 7.4 using FASTCGI.

Whether you just need a security-focused nGinx configuration, or just examples on how you can tidy up your code. This repository should prove useful to anyone needing a quick and reliable nGinx setup.

## Features
- Defaults all DNS traffic to CloudFlare.
- Defaults all TLS Handshakes to TLSv1.2 and TLSv1.3.
- ECDH Curves set for security and compatibility (prime256v1, secp384r1, secp521r1).
- Disables the use of insecure SSL Ciphers.
- Supports LetsEncrypt acme-challenge.
- Blocks common SQL injection attacks.
- Blocks common file injection techniques.
- Blocks common web-application exploits.