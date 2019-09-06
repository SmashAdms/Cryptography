# Cryptography
For this project I used OpenSSL to generate an RSA and AES keypair to exchange messages through encryption and decryption.
I used a hybrid cryptosystem to exchange encrypted messages with a friend. 
This took many steps to complete as I had to use OpenSSL to generate an RSA keypair and send my public key to my friend.
Next, I created a symmetric key to I could encrypt my message with AES key. 
Then I used my asymmetric, private ket to encrypt my symmetric key and sent both the encrypted message and the encrypted symmetric key to my friend.
My friend mirrored the process and we decrypted eachothers messages.
This was so much fun because of the secrecy involved and required collaboration which I really enjoyed.
