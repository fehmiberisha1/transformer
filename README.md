# transformer

CONVERSION: Between Ascii, Binary, Octal, Decimal and Hexadecimal.

CIPHERING / DECIPHERING: ROT13, ROT47, Caesar's Cipher, Morse Code, Baconian Cipher, Super Cipher :)

HASHING: MD5, SHA2-256, SHA2-384, SHA2-512, SHA3-256, SHA3-384, SHA3-512, Blake2s, Blake2b.

ENCODING / DECODING: Base16, Base32, , Base58, Base64, Ascii85, URL encoding.

ENCRYPTION / DECRYPTION: Currently it does encryption using Fernet library, which means it uses AES-128-CBC and HMAC-SHA256.

Note: When encoding/decoding files, the output has to be written in a path of your choosing. When encoding/decoding strings from the input field, the result is shown normally in the output field. 
This feature was added as a work-around to Qt5 configurations, which don't allow a large amount of lines to appear in a field, therefore, writing in files solves the problem and allows us to perform actions on much larger input than usual.
