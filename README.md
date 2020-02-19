# All_Ciphers

this repository contians some techniques to chiper messages.

the techniques are : 


1- Affine Cipher : each letter in an alphabet is mapped to its numeric equivalent, encrypted using a simple mathematical function, and converted back to a letter. Letter A is given number 0 and letter Z is given number 26. Each letter is encrypted with the function (5x + 8) mod 26. The decryption function is 21(y − 8) mod 26.  


2- Caesar Cipher :  is one of the simplest and most widely known encryption techniques. It is a type of substitution cipher in which each letter in the plaintext is replaced by a letter at some fixed number of positions down the alphabet. For example, with a right shift of 3, A would be replaced by D, B would become E, X becomes A, and so on. 


3- Atbash Cipher : The Atbash cipher is a very common, simple cipher. Basically, when encoded, an "A" becomes a "Z", "B" turns into "Y", etc. 


4- ROT13 Cipher : It is a simple letter substitution cipher that replaces a letter with the 13th letter after it, in the alphabet. Because there are 26 letters (2×13) in the basic Latin alphabet, ROT13 is its own inverse; that is, to undo ROT13, the same algorithm is applied, so the same action can be used for encoding and decoding.   


5- Baconian Cipher : To encode a message, each letter of the plaintext is replaced by a group of five of the letters 'A' or 'B'. This replacement is a binary encoding.  


6- Simple Substitution Cipher :  In this cipher, Create a general version that builds the cipher alphabet using a given key of 5 unique letters. The user enters the key to cipher a message and the same key to decipher the message. The cipher alphabet is built by adding the remaining 21 letters in order after the key letters. For example, if the user enters "zebra" as the key, then: 

plain alphabet : a b c d e f g h i j k l m n o p q r s t u v w x y z 

cipher alphabet: z e b r a c d f g h i j k l m n o p q s t u v w x y 


7- Polybius Square Cipher :  Each letter is replaced with two numbers according to the following table. Write another version where top and left numbers are given as a key, but you will need to have the same key to decipher the message 


8- Morse Code : t is a code consisting of two symbols dot and dash and used to in the telegraph system in the past and also communicate messages in primitive ways. 


9- XOR Cipher : In this cipher, a secret key consisting of one letter is give. Then each letter of the message goes through XOR operation with the secret letter. The output is printed in text and hexadecimal. The original message can be recovered from the encrypted message by the same algorithm, XOR with the secret letter.  


10- Rail-fence Cipher : The railfence cipher is an easy to apply transposition cipher that jumbles up the order of the letters of a message in a quick convenient way. It also has the security of a key to make it a little bit harder to break.
The Rail Fence cipher works by writing your message on alternate lines across the page, and then reading off each line in turn. 

