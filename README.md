# SCT_CS_1
create a program that can encrypt and decrypt text using caesar cipher algorithm . allow users to input a message nd shift value to perform encryption and decryption .

## What is the Caesar Cipher?
The Caesar Cipher is a simple encryption technique that replaces each letter in a message with a letter a fixed number of positions down the alphabet. For example, with a shift of 1, the letter "a" becomes "b", "b" becomes "c", and so on.

### How to use this program
Run the program and select one of the following options:                                                                                         Encrypt a message: Enter a message and a shift value to encrypt it.                                                                              Decrypt a message: Enter an encrypted message and a shift value to decrypt it.                                                                     Quit: Exit the program.                                                                                                                           Follow the prompts to enter the required information.

#### Functions
caesar_encrypt(message, shift)                                                                                                                  
Encrypts a message using the Caesar Cipher algorithm with a given shift value.                                                                  
message: The message to be encrypted.                                                                                                             
shift: The shift value to use for encryption.                                                                                                   
Returns: The encrypted message.                                                                                        
caesar_decrypt(encrypted_message, shift)                                                                                                        Decrypts an encrypted message using the Caesar Cipher algorithm with a given shift value.                                             
encrypted_message: The encrypted message to be decrypted.                                                                                        
shift: The shift value to use for decryption.                                                                                                  
Returns: The decrypted message.
