# 🛡️ Secure Data Hiding in Images Using Steganography

## 🔍 Overview
This project implements image-based steganography to securely hide and retrieve secret messages within images. Using Least Significant Bit (LSB) encoding, it embeds text inside an image without significantly altering its appearance. The hidden message can only be retrieved with the correct passcode, ensuring confidentiality and security.

## ✨ Features
✔️ Stealthy Data Hiding – Embed text messages inside images invisibly.<br>
✔️ Password Protection – Decrypt only with the correct passcode.<br>
✔️ Minimal Image Distortion – Ensures high visual fidelity.<br>
✔️ Lightweight & Fast – Works efficiently with OpenCV.<br>
✔️ Cross-Platform Compatibility – Runs on Windows, Linux, and macOS.<br>

## 🛠️ Technologies Used
**Python** – Core programming language<br>
**OpenCV** – Image processing library<br>
**OS Module** – System commands for opening images<br>

## 📜 How It Works
**🔐 Encryption Process:**<br>
Load an image (e.g., cat.jpg).<br>
Input the secret message and a passcode.<br>
Encode the message into the image pixel values.<br>
Save the modified image as encryptedImage.jpg.<br>
**🔓 Decryption Process:**<br>
Load the encrypted image.<br>
Input the correct passcode to retrieve the hidden message.<br>
If the passcode is incorrect, access is denied.<br>

## ⚠️ Limitations
Only works with RGB images.<br>
Limited message size based on image dimensions.<br>
Basic LSB implementation; can be enhanced with DCT/DWT techniques.<br>

## 📌 Future Enhancements
✅ Improve security with AES encryption.<br>
✅ Support for multiple image formats.<br>
✅ Develop a GUI-based version.<br>

## 🏆 Contributing
Feel free to fork, improve, and contribute! Create a pull request with your changes.
