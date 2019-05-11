# Create-Verify-Digital-Signatures
Program to create and verify digital signatures of files

## How to execute:
Generate the signature with the following:
```
python signer.py privKey.pem test.sig test.txt sign
```

Verify with the following:
```
python signer.py pubKey.pem test.sig test.txt verify
```
