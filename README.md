Wrapper script for gpg

```
my_pgp 0.5
Copyright 1993 - 2020 (c) Badassops LLC
License BSD, http://www.freebsd.org/copyright/freebsd-license.html

Written by Luc Suryo <luc@badassops.com>
Wrapper script for gpg

Usage : my_pgp [-h] [ option ... ]
 Options:
   -h this help page.
   -D debug mode, dry-run mode.
   -d value, the file to be decrypted
   -e value, the file to be encrypted
   -i value, imported public key from given file
   -l, list all imported public key
   -p save public key in the file pub_key.gpg
   -r value, recipient, to be use with the -f option
   -s value, search the given user and import key
   -S value, sign the key of the given email or key-id
   -x value, delete the key of the given email or key-id
   -v Show version.

Notes: during decryption there migth be some error
that could be ignored, so always check the decrypted file
```

Note
```
before usage make sure to edit the script and adjust the _my_key variable.
comments welcome :)
```


Enjoy

momo
