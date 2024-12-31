# Image-Steganography-with-Stego-Analysis
This repository hosts a Java-based image steganography tool designed to securely embed secret messages within digital images. The tool supports various image formats, including PNG, JPEG, and BMP, and employs multiple steganography techniques to maintain the integrity and confidentiality of the data.

## Key Features
- **Multiple Image Format Support:** The tool can process images in PNG, JPEG, and BMP formats.
- **LSB Encoding:** Utilizes Least Significant Bit encoding to hide data within the image pixels without noticeable changes.
- **Bit Plane Manipulation:** Manipulates image bit planes to embed data, enhancing the security of the hidden information.
- **Bitwise XOR Operations:** Uses XOR operations for data embedding, providing an additional layer of complexity and security.
- **Error Handling and Data Validation:** Ensures the integrity and confidentiality of the data through robust error handling and validation mechanisms.

## Technologies Used
- **Java:** Core programming language used for the tool's development.
- **AWT:** Utilized for image manipulation tasks.
- **DataInputStream:** Employed for efficient file handling operations.

## Usage
To use this tool, ensure you have Java installed on your machine. Compile and run the Java files according to the functionality you need to perform, such as encoding or decoding steganographic messages in images.

## Authors and Acknowledgment
This tool is based on research conducted for the paper titled "Improving The Hiding Capacity of Image Steganography with Stego-Analysis" presented at the 2023 IEEE International Conference on Integrated Circuits and Communication Systems. The authors include:
- **Padmaja Grandhe**
- **A.Mallikarjuna Reddy**
- **Kavyasri Chillapalli**
- **Kavya Koppera**
- **Manasa Thambabathula**
- **L P Reddy Surasani**

## Citation
P. Grandhe, A. M. Reddy, K. Chillapalli, K. Koppera, M. Thambabathula and L. P. Reddy Surasani, "Improving The Hiding Capacity of Image Steganography with Stego-Analysis," 2023 IEEE International Conference on Integrated Circuits and Communication Systems (ICICACS), Raichur, India, 2023, pp. 01-06, doi: 10.1109/ICICACS57338.2023.10100146. keywords: {Integrated circuits;Steganography;Costs;Communication systems;Image processing;Government;Communication channels;Cryptography;Digital image processing;Blind Hide Algorithm;Encryption;steganography;stego-image;Bulk Analysis;Benchmark Analysis;Stego Analysis;Decryption},

Their contributions to the field of secure communication through steganography have been foundational in the development of this tool.
