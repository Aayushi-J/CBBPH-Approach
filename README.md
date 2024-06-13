# CBBPH-Approach


The methodology of the Columnar Binary Braille Pixel Hiding (CBBPH) approach involves several key steps to enhance data security by combining Braille encoding, image steganography, encryption, and columnar transposition. Here's a detailed breakdown of the process:

### 1. **Encoding Plaintext Messages into Braille**
- **Step 1:** Convert the plaintext message into Braille characters. Braille is a tactile writing system used by visually impaired individuals and is represented by patterns of raised dots.
- **Step 2:** Each character in the plaintext message is mapped to its corresponding Braille representation, which is a binary format suitable for further processing.

### 2. **Applying Columnar Transposition**
- **Step 1:** Arrange the Braille-encoded message into a grid or table format. The width of the grid (number of columns) is a parameter that can be chosen based on the desired level of security.
- **Step 2:** Perform columnar transposition by rearranging the columns of the grid according to a predetermined key. This step shuffles the order of the characters, adding a layer of encryption and making the encoded message harder to decipher without the key.

### 3. **Embedding the Encoded Message into Image Pixels**
- **Step 1:** Select an image for steganographic embedding. This image serves as the carrier for the hidden message.
- **Step 2:** Identify the least significant bits (LSBs) of the image pixels. These are the bits that can be altered with minimal impact on the visual quality of the image.
- **Step 3:** Embed the transposed Braille-encoded message into the LSBs of the selected image pixels. The Braille binary data is inserted bit by bit into the LSBs, ensuring that the changes are imperceptible to the human eye.

The following are the code files for the same.
