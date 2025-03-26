## About

This is a example release workflow using provenance.
The released bynary has a provenance, from which you can check the process has legit.

## How to use

```shell
gh release download --repo no-yan/gha-provenance
gh attestation verify PATH/TO/ARTIFACT -o no-yan
```
