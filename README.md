# 🔒 LSB Image Steganography using C

Hide secret data inside BMP images using the **Least Significant Bit (LSB)** technique — developed in **C**.

---

## 📘 Overview
A simple yet powerful project that embeds and retrieves hidden text files inside images.  
Uses **bitwise manipulation** and **file handling** to achieve secure, invisible data hiding.

---

## ⚙️ Features
- Encode & decode text files in BMP images  
- Authentication using magic string  
- Modular C implementation (`encode.c`, `decode.c`, `types.h`)  
- Works via command-line interface  

---

## 🧩 Usage
```bash
gcc test_encode.c encode.c decode.c -o stego_tool
./stego_tool -e source.bmp secret.txt stego.bmp     # Encode
./stego_tool -d stego.bmp output                    # Decode
