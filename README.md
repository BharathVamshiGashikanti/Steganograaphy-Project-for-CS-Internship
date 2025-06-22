# Steganograaphy-Project-for-CS-Internship
GUI app to hide and reveal messages inside images using Python.
# 🕵️‍♂️ Image Steganography GUI App

A Python-based graphical user interface (GUI) application to **hide and reveal secret messages inside images** using **LSB (Least Significant Bit) steganography**.

## 🔒 Project Objective

The main goal of this project is to allow users to securely embed a secret message within an image without visibly altering the image. This enhances privacy by avoiding suspicion that a secret message even exists.

---

## 🛠️ Technologies Used

| Component           | Technology             |
|---------------------|------------------------|
| Programming Language| Python 3.x             |
| GUI Framework       | Tkinter                |
| Image Handling      | Pillow (PIL)           |
| Steganography       | Stegano Library (LSB)  |
| File Handling       | `filedialog`, `messagebox` (Tkinter) |

---

## 💡 Features

- Load and preview image files (PNG, JPG)
- Input and hide a secret text message
- Password-protected message hiding and revealing (default: `1234`)
- Save the image with hidden data
- Reveal and display hidden messages with the correct password

---

## 📦 Installation

### ✅ Prerequisites

Make sure you have Python 3 installed.

Install the required libraries:

```bash
pip install pillow stegano
🔧 Run the Application
python main.py
message

📋 How It Works
Open Image: Load an image file (PNG or JPG).

Enter Message: Type your secret message and enter the password.

Hide Message: Embed the message into the image using LSB technique.

Save Image: Save the modified image as Secret file.png.

Reveal Message: Reopen the image, enter the password, and view the hidden message

🔐 Default Password
The current version uses a hardcoded password:
1234
You can modify this in the code:
if password == '1234':
🚀 Future Enhancements
Allow custom passwords and message encryption

Support for more image formats

Drag-and-drop UI support

Hide messages in audio or video files

Export logs or usage reports

reports

📚 References
Python Official Docs

Tkinter Documentation

Stegano Python Library

Pillow (PIL)

)

🧑‍💻 Author
Gahikanti Bharath Vamshi
GitHub: BharathVamshiGashikanti
Project: image-steganography-app
app

📜 License
This project is licensed under the MIT License. Feel free to use and modify it for educational or personal purposes.
Let me know if you'd like this customized with your name, GitHub link, or if you want it as a downloadable file.

