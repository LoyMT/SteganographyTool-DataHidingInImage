# SteganographyTool-DataHidingInImage
This program is able to hide data by encoding the secret message into a cover image file (jpg,jpeg,png,gif) and producing stego-image.

To use this program, users are required to enter their secret message and the exact file name of the chosen cover image file. The program will encode the secret message with the cover image to produce a stego-image by storing the secret message at the end of the data string of the image. The ASCII value of each characters in the secret message are processed so it wont be readable from the hex dump of the stego-image. This program is also able to read the hidden message from the stego-image and display it.
