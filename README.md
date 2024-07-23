# Video Steganography System
This project is a Video Steganography System developed in Python, aimed at securely embedding secret data within video files. The system utilizes the Least Significant Bit (LSB) methodology for embedding data and integrates the RC4 algorithm for encryption and decryption to enhance the security of the embedded data.

# Features
Data Embedding: Embed secret data within video files using the LSB technique.

Encryption and Decryption: Enhance data security with RC4 encryption before embedding and decrypt data after extraction.

Supports Multiple Video Formats: Works with various common video file formats.

Robust and Secure: Ensures the integrity and confidentiality of the embedded data.

# Technologies Used
Python: Core programming language for implementing the steganography and encryption algorithms.

OpenCV: For video processing and manipulation.

NumPy: For numerical operations and data manipulation.

# Usage
1. Select a video file and a text file containing the secret data.
   
2. Encrypt the secret data using RC4.
    
3. Embed the encrypted data into the video file using LSB.
    
4. Extract the embedded data from the video file.
 
5. Decrypt the extracted data using RC4 to retrieve the original secret data.


Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.
