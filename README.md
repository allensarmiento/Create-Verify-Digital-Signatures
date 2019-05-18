# Create-Verify-Digital-Signatures
Program to create and verify digital signatures of files

## Group Members:
* Nathan S
* Stephen S
* Jasper C
* Allen S
* Hector M

## Programming Language: Python

## How to execute:
Generate the signature with the following:
```
python signer.py privKey.pem test.sig test.txt sign
```

Verify with the following:
```
python signer.py pubKey.pem test.sig test.txt verify
```
