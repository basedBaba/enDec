# enDec

```
                  ____              
      ___  ____  / __ \___  _____   
     / _ \/ __ \/ / / / _ \/ ___/   
    /  __/ / / / /_/ /  __/ /__     
    \___/_/ /_/_____/\___/\___/     
                                     
```

Encrypt/Decrypt files with fernet symmetric cryptography

## Installation

```
git clone https://github.com/based-baba/enDec

cd enDec

chmod +x endec.py

./endec.py -h
```

## Usage

### Help

```
usage: endec.py [-h] [-k KEY] command file

Encrypt/Decrypt files

positional arguments:
  command            encrypt/decrypt
  file               file to be encrypted/decrypted

options:
  -h, --help         show this help message and exit
  -k KEY, --key KEY  secret key for decryption
```

### Encryption

```
./endec.py encrypt [file]
```

### Decryption

```
./endec.py decrypt [file] -k [key]
```