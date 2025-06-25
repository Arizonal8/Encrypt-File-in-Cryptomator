
#  Project Documentation: File Encryption Using Cryptomator

## Objective
To demonstrate how to securely encrypt and decrypt files using Cryptomator, a symmetric encryption tool, on Windows OS.

## Background
Cryptomator is a free and open-source tool that enables end-to-end encrypted storage for cloud and local folders. It uses AES-256 encryption and creates virtual drives for managing encrypted data.

## Tools Used
- Windows 10
- Cryptomator (v1.6+)
- Screenshot tool

## Encryption Process

### Step 1: Vault Creation
- Created a new vault named `EncryptedFiles` using Cryptomator
- Vault stored in `Documents\EncryptedFilesVault`

### Step 2: Password Setup
- Password created using a combination of uppercase, lowercase, number, and symbol
- No recovery option—password stored in secure offline password manager

### Step 3: Unlock Vault
- Vault unlocked to reveal a virtual drive `X:\`

### Step 4: Add Files to Encrypt
- Added file: `confidential_report.pdf`
- File immediately encrypted in the background and stored in `.c9r` format

### Step 5: Lock Vault
- Vault locked and virtual drive disappeared
- Encrypted data remains unreadable in original vault location

## Screenshots Included
- `1_create_vault.png`
- `2_set_password.png`
- `3_unlock_vault.png`
- `4_add_file_to_vault.png`
- `5_lock_vault.png`

## Outcome
- Successfully encrypted and decrypted files using Cryptomator
- Learned how transparent encryption works with virtual drives

## Security Insight
Cryptomator uses AES-256 encryption with filename obfuscation. The password is the only decryption key. Vaults can safely be uploaded to cloud storage without exposing plaintext data.

## Additional Notes
- Cryptomator does not support password recovery
- Vaults are compatible across Windows, macOS, Linux, Android, and iOS
