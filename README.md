# Secure Email Using OpenPGP

## Overview

This project documents a cybersecurity lab focused on secure email communication using OpenPGP.

I completed the lab on macOS using GPG Suite and Mozilla Thunderbird. The lab involved generating OpenPGP key pairs, configuring Thunderbird for encrypted email, exchanging public keys, sending encrypted and digitally signed email, decrypting the message, and verifying the digital signature.

## Tools Used

- macOS
- GPG Suite
- GPG Keychain
- Mozilla Thunderbird
- Gmail
- OpenPGP

## Objectives

The objectives of this lab were to:

- Generate OpenPGP public and private key pairs
- Configure Mozilla Thunderbird for secure email
- Import OpenPGP keys into Thunderbird
- Enable end-to-end email encryption
- Exchange public keys between two email accounts
- Send an encrypted and digitally signed email
- Receive and decrypt an encrypted email
- Verify a digital signature

## Lab Walkthrough

### 1. Generate OpenPGP Key Pairs

I generated an OpenPGP public/private key pair for each Gmail account using GPG Keychain.

![OpenPGP Key Generation](SS1.pdf)

### 2. Configure Thunderbird

Both Gmail accounts were added to Mozilla Thunderbird using IMAP. I verified that both accounts could send and receive normal email messages.

![Thunderbird Setup](SS2.pdf)

## Step 3 – Import OpenPGP Keys into Thunderbird

The OpenPGP public and private keys were imported into Thunderbird. End-to-end encryption was enabled for each email account by selecting the appropriate OpenPGP key.

[View Screenshot 3.5](SS3.5.pdf)  

[View Screenshot 4](SS4.pdf)

[View Screenshot 5](SS5.pdf)  

[View Screenshot 5.5](SS5.5.pdf)

## Step 4 – Exchange Public Keys

The public OpenPGP keys were exchanged between the two email accounts.

[View Screenshot 6](SS6.pdf)

## Step 5 – Send Encrypted and Digitally Signed Email

An encrypted and digitally signed email was sent using OpenPGP.

[View Screenshot 7](SS7.pdf)

## Step 6 – Receive and Decrypt Email

The encrypted email was received and decrypted using the OpenPGP key configured in Thunderbird.

[View Screenshot 8](SS8.pdf)

## Step 7 – Verify Digital Signature

The digital signature was verified to confirm the authenticity and integrity of the received message.

[View Screenshot 9](SS9.pdf)


## What I Learned

This lab helped me understand how OpenPGP can be used to secure email communication.

I learned how public and private keys work together for encryption and decryption. I also learned how digital signatures can be used to verify the sender and confirm that a message has not been changed.

## Skills Demonstrated

- OpenPGP
- Public-key cryptography
- GPG Suite
- GPG Keychain
- Mozilla Thunderbird
- Email encryption
- Digital signatures
- Key management
- End-to-end encryption
