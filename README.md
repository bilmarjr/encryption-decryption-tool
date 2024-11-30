# encryption-decryption-tool

 this Python script provides a simple way to encrypt and decrypt files using the cryptography library. It securely encrypts files using a generated secret key and allows you to decrypt them using the same key.

Features
* generate a secret key: automatically generates and saves a secret key in Secret.key.
* file encryption: encrypt any file using the secret key.
* file decryption: decrypt encrypted files using the same secret key.

## How to Use
install Dependencies:
Ensure you have the cryptography library installed. If not, install it with:
> pip install cryptography

Run the Script:
> python <script_name>.py

Choose an Option:

* Enter E to encrypt a file. provide the file name (including extension). A secret key will be generated automatically.
* Enter D to decrypt a file. ensure the Secret.key file exists in the same directory as the script.
