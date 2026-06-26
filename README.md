# 🕵️‍♂️ Stealth Paradox – Web-Based Steganography Tool

> Hide secret messages inside PNG images directly in your browser using Least Significant Bit (LSB) steganography.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Security](https://img.shields.io/badge/Domain-Cybersecurity-red)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 📖 Overview

**Stealth Paradox** is a browser-based steganography application developed as part of the **Application of Information and Communication Technologies (AICT)** course at Air University.

The application allows users to securely hide and extract secret messages inside PNG images using the **Least Significant Bit (LSB)** technique. All processing takes place locally in the browser, ensuring complete privacy without requiring any server-side communication.

---

## 🎯 Project Objectives

- Demonstrate practical applications of information security concepts.
- Implement image-based steganography using the LSB algorithm.
- Develop a fully client-side web application.
- Create a responsive and user-friendly interface.
- Explore modern web development technologies.

---

## ✨ Features

### 🔒 Privacy First
- 100% client-side processing
- No server uploads
- No cloud storage
- No cookies or user tracking

### 🖼️ Image Steganography
- Hide secret text messages inside PNG images
- Extract hidden messages from encoded images
- Imperceptible image modifications

### ⚡ Instant Processing
- Real-time encoding and decoding
- No external dependencies
- Fast browser-based execution

### 📱 Responsive Design
- Mobile-friendly interface
- Desktop optimization
- Cross-browser compatibility

### ♿ Accessibility
- Keyboard navigation support
- Semantic HTML structure
- User-friendly workflow

---

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript (Vanilla JS)

### Web APIs
- HTML5 Canvas API
- FileReader API

### Design
- CSS Grid
- Flexbox
- Responsive Layouts
- Modern UI Animations

---

## 🔍 How It Works

### Encoding Process

1. Upload a PNG image.
2. Enter a secret message.
3. Convert the message into binary.
4. Modify the least significant bit of image pixels.
5. Append a unique 32-bit delimiter.
6. Download the encoded image.

```text
PNG Image → Secret Message → LSB Encoding → Encoded PNG
```

### Decoding Process

1. Upload the encoded PNG image.
2. Extract pixel data.
3. Read LSB values.
4. Locate the delimiter.
5. Convert binary data back into text.

```text
Encoded PNG → Extract LSB Data → Decode Binary → Secret Message
```

---

## 🔐 LSB Steganography Technique

The project uses the **Least Significant Bit (LSB)** method for information hiding.

### Encoding

- Message text is converted into binary.
- The least significant bit of pixel color values is modified.
- Visual image quality remains virtually unchanged.

### Decoding

- LSB values are extracted from image pixels.
- Binary data is reconstructed into readable text.

### Message Capacity

- Supports messages up to **500 characters**
- Capacity can be expanded through code modification

---

## 🏗️ Application Architecture

### Pages

#### 🏠 Home
- Project introduction
- Feature highlights
- Educational content

#### 🔐 Encode
- PNG upload
- Secret message input
- Encoding functionality

#### 🔓 Decode
- Encoded image upload
- Hidden message extraction

#### ℹ️ About
- Team information
- Technology overview

#### ❓ FAQ
- Searchable help documentation
- User guidance

---


## 🚀 Running the Project

### Method 1: Open Directly

Simply open:

```text
index.html
```

in your browser.

### Method 2: Local Server

Using VS Code Live Server:

```bash
Right Click → Open with Live Server
```

---

## ✅ Testing & Validation

The project was tested for:

- Message encoding
- Message decoding
- PNG validation
- Empty input handling
- Image preview functionality
- Browser compatibility

### Supported Browsers

- Google Chrome 90+
- Mozilla Firefox 88+
- Microsoft Edge 90+
- Safari 14+

---

## ⚠️ Limitations

- PNG images only
- 500-character message limit
- Hidden messages are not encrypted
- Advanced steganalysis techniques may detect modifications

---

## 🔮 Future Improvements

- AES Encryption Integration
- Drag & Drop Image Support
- Dark/Light Theme Toggle
- Image Quality Analysis
- Multi-File Support
- Password-Protected Messages
- Advanced Steganography Algorithms

---

## 👥 Team

### Muhammad Saim Iftikhar
**Lead Developer & Documentation**

### Isra Batool
**UI/UX Designer**

### Musa Madni
**Testing & Validation**

---

## 🎓 Academic Information

**Course:** Application of Information and Communication Technologies (AICT)

**Institution:** Air University

**Academic Year:** 2024–2025

---

## 📜 License

This project was developed for educational and academic purposes.

Feel free to explore, learn, and build upon it.
