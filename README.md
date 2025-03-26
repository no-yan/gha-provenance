## About

This is a example release workflow using provenance.
The released bynary has a provenance, from which you can check the process has legit.

## How to use

```shell
gh release download --repo no-yan/gha-provenance --pattern greet
gh attestation verify greet -o no-yan
```
