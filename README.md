# st-decrypt
Utility for encrypting/decrypting ST-Link firmware images.
It is mostly based on decompiled code, which is not human-readable (and probably never was in the first place).

## Usage
Compiled archive can be found in `dist` folder.
```
$ java -jar st_decrypt.jar decrypt firmware.bin firmware_decrypted.bin
$ java -jar st_decrypt.jar encrypt firmware.bin firmware_encrypted.bin
```
