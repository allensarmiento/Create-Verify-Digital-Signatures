# Create-Verify-Digital-Signatures
Program to create and verify digital signatures of files

## Group Members:
* Nathan S
* Stephen S
* Jasper C
* Allen S
* Hector M

## Programming Language: Python 2

## Installation Instructions for the ECS/Alina Server
```
git clone https://github.com/allensarmiento/Create-Verify-Digital-Signatures.git
cd Create-Verify-Digital-Signatures
pip2 install -r requirements.txt
```

## How to execute:
Generate the signature with the following:
```
python2 signer.py privKey.pem test.sig test.txt sign
```

Verify with the following:
```
python2 signer.py pubKey.pem test.sig test.txt verify
```

## Extra Credit Implemented: No

