# Image Encryption and Steganography with DES and LSB

This project implements a combination of DES (Data Encryption Standard) and LSB (Least Significant Bit) techniques to perform image encryption and steganography. It allows embedding a grayscale image inside an RGB image securely, ensuring confidentiality and integrity.

## Features

- **DES Encryption**: Encrypts the grayscale image using the DES algorithm for secure transmission.
- **LSB Steganography**: Embeds the encrypted grayscale image into an RGB image using LSB embedding.
- **Seamless Integration**: Compatible with images of different sizes, ensuring the embedding process adheres to the capacity constraints.

## File Structure

```
image-encryption-and-steganography-with-des_and_lsb/
├── demo_images/                   # Directory containing demo and output images
├── .gitignore                     # Git ignore file
├── README.md                      # Documentation for the project
├── image_encryption_and_steganography_with_des_and_lsb.ipynb  # Main Jupyter Notebook
└── requirements.txt               # List of dependencies
```

## Getting Started

### Prerequisites

Ensure you have Python 3.8 or later installed along with the following dependencies:

- `numpy`
- `pillow`
- `opencv-python`

You can install the required packages using:

```bash
pip install -r requirements.txt
```

### Running the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Islam-hady9/image-encryption-and-steganography-with-des_and_lsb.git
   cd image-encryption-and-steganography-with-des_and_lsb
   ```

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook image_encryption_and_steganography_with_des_and_lsb.ipynb
   ```

3. Follow the steps in the notebook to:
   - Load images.
   - Perform DES encryption.
   - Embed the encrypted image into an RGB image using LSB steganography.

4. View the results in the `demo_images` directory.

## Demo Images

Demo input and output images are stored in the `demo_images` directory for reference. These images demonstrate the encryption and embedding process.

## Contributions

Contributions are welcome! Feel free to fork the repository, create a new branch, and submit a pull request.

## Acknowledgments

- **DES Encryption**: Leveraged for secure data transmission.
- **LSB Steganography**: Used for embedding images efficiently.
