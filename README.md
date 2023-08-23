# encrypted-backup
Bash scripts to create an encrypted tar archive of a given directory using a password file and to decrypt the result.

## Installation
`chmod +x /path/to/encrypt-backup`
`chmod +x /path/to/decrypt-backup`

## Create a password file with a secure password
`echo "securepass" > /path/to/passfile` 

## How to encrypt
- `/path/to/encrypt-backup /path/from/files/ /path/to/destination/ /path/to/passfile`

## How to decrypt
- `/path/to/decrypt-backup /path/from/backup.tar /path/to/destination/ /path/to/passfile`
