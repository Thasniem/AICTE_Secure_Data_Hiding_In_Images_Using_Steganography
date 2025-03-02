# Secure Data Hiding in Images using Steganography 🔒

A secure and user-friendly application for encrypting and decrypting messages within images using steganography and password protection.

## 📌 Project Overview

This project implements steganography techniques to hide secret messages within images. The message is securely embedded inside image pixels using OpenCV and can only be retrieved with the correct password, providing an additional layer of security.

## 🛠️ Technologies Used

- **Python** - Core programming language
- **OpenCV** - Image processing and manipulation
- **NumPy** - Numerical operations and array handling
- **PyQt6** - Graphical User Interface development

## 🔥 Features

- ✔ **Steganography-based Encryption**
  - Securely hides messages within image pixels
  - Maintains image quality
  - Undetectable to the naked eye

- ✔ **Password Protection**
  - Secure message retrieval
  - Prevents unauthorized access
  - Enhanced data security

- ✔ **User-Friendly Interface**
  - Intuitive GUI design
  - Easy-to-use controls
  - Clear feedback messages
 
2. Install required dependencies:
```bash
pip install opencv-python numpy PyQt6
 ```

## 🚀 Usage
### Encrypting an Image
1. Run the encryption script:
```bash
python encrypt.py
 ```

2. Follow the GUI prompts:
   - Select an image
   - Enter your secret message
   - Set a password
   - Click "Encrypt Image"
### Decrypting an Image
1. Run the decryption script:
```bash
python decrypt.py
 ```

2. Follow the GUI prompts:
   - Select the encrypted image
   - Enter the password
   - Click "Decrypt Image"
## 💡 Important Notes
- Only use PNG images for best results
- Remember your password - it cannot be recovered
- Keep your encrypted images safe
- Don't modify encrypted images as it may corrupt the hidden message
## 📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.   

- ✔ **Efficient Storage**
  - No external storage needed
  - Message stored directly in image
  - Supports PNG format for lossless compression

## 📥 Installation

1. Clone the repository:
```bash
git clone https://github.com/Thasniem/AICTE_Secure_Data_Hiding_In_Images_Using_Steganography.git
cd AICTE_Encryption_Decryption_project
