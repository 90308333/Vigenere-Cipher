# Computer Code
### How it works:
 * A key of 2 or more letters in the alphabet should be used
 * To encrypt: Locate the first letter of the plaintext on the first column, then locate the first letter of the key on the first row. Where the two intersect becomes a letter in the ciphertext. Keep doing this throughout the plaintext. If you run out of letters in the key, start back at the beginning. Now you have your ciphertext.
 * There are 2 options for decryption:
 Subtraction method: Letters have the value of their position in the alphabet (it starts frm zero). Subtract the value of the first letter in the key from the first letter in thr ciphertext. This value will give you a letter. If you run out of letters in the key, start back at the begining.
 Table method: Locate the first letter of the key in the left colum. Go down the row till you find the first letter in the ciphertext. Then go up the row to the letter in the first column. This will give you the first letter of the plaintext. If you run out of letters in the key, start back at the beginning.

### ![Vigenere](https://user-images.githubusercontent.com/72951482/142250285-3249a34e-b803-413c-8137-aaef12b70363.png)
### On the website linked below there is an easy decoder available.

[Link to Encoder/Decoder for Vigenere Cipher](https://cryptii.com/pipes/vigenere-cipher)
