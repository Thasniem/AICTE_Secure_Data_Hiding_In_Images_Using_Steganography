🔒 Secure Data Hiding in Images Using Steganography
📌 Project Overview
This project provides a secure and user-friendly way to encrypt and decrypt messages within images using steganography and password protection. The message is embedded inside an image using OpenCV, and only the correct password can retrieve the hidden message. This ensures confidentiality and prevents unauthorized access.

🛠️ Technologies Used
Python – Programming language
OpenCV – Image processing and manipulation
NumPy – Efficient array operations
PyQt6 – Graphical User Interface (GUI) framework
🔥 Features
✔ Steganography-based encryption – Hides messages inside image pixels, making them invisible to the naked eye.
✔ Password-protected decryption – Ensures that only authorized users can access the hidden message.
✔ Graphical User Interface (GUI) – Provides an intuitive and user-friendly experience.
✔ No need for external storage – The message is directly embedded in the image, eliminating the need for separate storage.
✔ Lossless encryption – Works with PNG images, ensuring image quality is preserved.
✔ Lightweight and fast – The application runs efficiently with minimal resource usage.
✔ Cross-platform compatibility – Works on Windows, macOS, and Linux.
✔ Easy integration – Can be extended for more secure applications like watermarking or confidential data sharing.

📌 Installation
Ensure you have Python installed. Then, install the required dependencies:

sh
Copy
Edit
pip install opencv-python numpy pyqt6
🔐 Encrypt an Image
Run the encryption script:
sh
Copy
Edit
python encrypt.py
Enter the secret message and password.
Click on Encrypt Image, and an encrypted image will be generated.
🔓 Decrypt an Image
Run the decryption script:
sh
Copy
Edit
python decrypt.py
Enter the password used during encryption.
If the password is correct, the hidden message will be displayed.
📌 Use Cases
Secure Communication – Send confidential messages hidden within images.
Digital Watermarking – Protect image copyrights by embedding hidden ownership details.
Forensic Applications – Hide and retrieve critical information in sensitive scenarios.
Password-Protected Image Sharing – Store text within images for secure retrieval.
🤝 Contribution
Fork the repository.
Create a feature branch (git checkout -b feature-name).
Commit your changes (git commit -m "Added feature").
Push to the branch (git push origin feature-name).
Submit a pull request.
📜 License
This project is licensed under the MIT License – Free to use, modify, and distribute.

Let me know if you need further improvements! 🚀







