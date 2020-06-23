# cryptoProject
A cryptography college project to secure delivery of grey images by generate a key from Diffie Hellman and send it to RC6 algorithm with CBC mode  to encrypt and decrypt the image. 


There are 2 version of these project :

1- simple project that runs that ecnrypts adn decrypts an image using CR6 AES with CBC operation mode and a key generated by diffie hellman

2- same as above including an actual client server architecture using socket API 




to run version 1 of the project please run main.py

to run version 2 follow these steps:

1- run server.py

2- run sender.py and reciever.py

3- when they sender.py window appears click the button and choose an image to encrypt

4- click 'encrypt and send' button

5- wait until the image and in the reciever.py GUI ( it may take some time of the image is big)

6- click 'decrypt' button in the reciever.py window