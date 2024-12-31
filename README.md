# Image-Steganography-with-Stego-Analysis

## Description
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

### Running the Project
To run the project from the command line:
- Navigate to the `dist` folder.
- Run the following command:
- java -jar "ImageStegano.jar"

### Distributing the Project
To distribute this project:
- Zip up the `dist` folder (including the `lib` folder).
- Distribute the ZIP file.

**Notes:**
- If two JAR files on the project classpath have the same name, only the first JAR file is copied to the `lib` folder.
- Only JAR files are copied to the `lib` folder. If the classpath contains other types of files or folders, these are not copied.
- If a library on the project's classpath also has a Class-Path element specified in the manifest, the content of the Class-Path element has to be on the project's runtime path.

## Authors and Acknowledgment
This tool is based on research conducted for the paper titled "Improving The Hiding Capacity of Image Steganography with Stego-Analysis" presented at the 2023 IEEE International Conference on Integrated Circuits and Communication Systems. The authors include:
- **Padmaja Grandhe**
- **A.Mallikarjuna Reddy**
- **Manasa Thambabathula**
- **Kavyasri Chillapalli**
- **Kavya Koppera**
- **L P Reddy Surasani**

## Citation
P. Grandhe, A. M. Reddy, K. Chillapalli, K. Koppera, M. Thambabathula and L. P. Reddy Surasani, "Improving The Hiding Capacity of Image Steganography with Stego-Analysis," 2023 IEEE International Conference on Integrated Circuits and Communication Systems (ICICACS), Raichur, India, 2023, pp. 01-06, doi: 10.1109/ICICACS57338.2023.10100146. keywords: {Integrated circuits;Steganography;Costs;Communication systems;Image processing;Government;Communication channels;Cryptography;Digital image processing;Blind Hide Algorithm;Encryption;steganography;stego-image;Bulk Analysis;Benchmark Analysis;Stego Analysis;Decryption},

Visit: https://ieeexplore.ieee.org/document/10100146
