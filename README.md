# image-steganography

# Proposed Algorithm
The algorithm is more dedicated towards the algorithm proposed by Rosziati Ibrahim and Teoh Suk Kuan in their Research Paper published on February 25, 2011.

# Encoding Algorithm
Firstly, the secret message that is extracted is compressed as the contents in the compressed string will significantly hard to detect and read, furthermore it reduces the size of string.
Secondly, the compressed string is encrypted with the secret key.
Finally, encoding the encrypted message in the image. It uses LSB steganographic embedding to encode data into an image. Once the message is encoded the process stops.

# LSB(Least Significant Bit) Embedding
The LSB is the lowest significant bit in the byte value of the image pixel. The LSB based image steganography embeds the secret in the least significant bits of pixel values of the cover image (CVR). The concept of LSB Embedding is simple. It exploits the fact that the level of precision in many image formats is far greater than that perceivable by average human vision. Therefore, an altered image with slight variations in its colors will be indistinguishable from the original by a human being, just by looking at it. In conventional LSB technique, which requires eight bytes of pixels to store 1byte of secret data but in proposed LSB technique, just four bytes of pixels are sufficient to hold one message byte. Rest of the bits in the pixels remains the same. 
