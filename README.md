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
# Clone the project locally
git clone https://github.com/basedBaba/enDec

# Create a virtual environment and install the required packages
cd enDec
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt

# Make the script executable
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