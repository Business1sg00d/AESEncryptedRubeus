Converted Rubeus.exe to Hex array delimited with "," and prepended with "0x", then AES Encrypted and Base64 converted.
Using a standard AMSI bypass DLL converted the same way, but not AES encrypted or base64 converted. Standard byte array.
Decrypts the Rubeus base64 blob using hardcoded key and IV.
Make sure to compile into x64.
Use the final binary just as you would with Rubeus.exe.
