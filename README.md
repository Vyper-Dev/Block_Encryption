# Block_Encryption

A modified version of my basic encryption program. This version splits the text into three blocks and uses a different key for each block. This method is more secure due to the blocks being asymmetrical and finding one key/pattern will not decrypt the rest. Recently optimized from 458 lines to 65.

There are three versions:
1. Encryption(Characters)- Least Complex, uses a static key and splits the string into blocks
2. Encryption(Random Keys)- Medium Complexity, uses previously generated or newly generated keys
3. Encryption(Random Keys and Text Files)- Most Complex, can do both randomly generated keys as well as writing/saving text files with encrypted text
