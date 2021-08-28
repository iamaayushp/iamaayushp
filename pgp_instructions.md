## Importing my Public Key
Download my Public Key from this repository and trun the following command to import it.
```shell
gpg --import <path to public_key.asc>
```

## Sending Encrypted Message to Me
Type your message in a text file like `txt`, `asc` etc. and encrypt it using the following command. This will create an encrypted `PGP` file, send that file to me.

```shell
gpg --encrypt --recipient aayushp26@yahoo.com <path to message file>
```
