# 🔐 Encrypted ASL Recognition System

## Overview

This project is an **Encrypted American Sign Language (ASL) Recognition System** designed to enhance secure communication for deaf and hard-of-hearing users. The system performs real-time ASL recognition using computer vision and machine learning, encrypts the captured video, and securely transfers it between the frontend and backend.

It combines principles of **cryptography**, **machine learning**, **network security**, and **web development** to simulate a secure ASL communication platform.

---

## 🔗 Project Links

- **🔧 Backend (Flask + ASL Recognition + AES Encryption + MongoDB)**  
  [GitHub Repo](https://github.com/ranaabdellatif/ASL-API)

- **🎨 Frontend (React + Video Capture + JWT Auth)**  
  [GitHub Repo](https://github.com/ranaabdellatif/ASL-REACT)

- **📽️ Final Presentation (Slides or Video)**  
  [View Presentation](https://docs.google.com/presentation/d/1FlHOay-_y-eVYmNk74mZVlTBFCwQR4UO7QvkOgcasTY/edit?usp=sharing)

- **📊 Research Poster**  
  [View Poster](https://link-to-your-poster.com)

---

## 🚀 Features

- Real-time ASL gesture recognition using **MediaPipe + OpenCV**
- AES-256 encrypted video file transfer
- Flask API for processing encrypted video
- React-based frontend for user interaction and video capture
- User signup/login with **JWT-based authentication**
- MongoDB integration for secure user session storage

---

## 🧪 Technologies Used

- **Frontend**: React, WebRTC, Axios, Tailwind CSS
- **Backend**: Flask, Python, OpenCV, MediaPipe, PyCryptodome
- **Security**: AES-256 encryption, SHA-256 file validation, JWT
- **Database**: MongoDB
- **Deployment**: Localhost testing with potential for Heroku/Render integration

---

## 📚 Sources

- Stallings, W. (2017). *Cryptography and Network Security: Principles and Practice*.
- Vanhoef, M., & Piessens, F. (2017). *Key Reinstallation Attacks: Forcing Nonce Reuse in WPA2*.
- Paar, C., & Pelzl, J. (2009). *Understanding Cryptography*.
- Katz, J., & Lindell, Y. (2014). *Introduction to Modern Cryptography*.
- OWASP Cheat Sheet Series – [Cryptographic Storage](https://cheatsheetseries.owasp.org/cheatsheets/Cryptographic_Storage_Cheat_Sheet.html)
- NIST Post-Quantum Cryptography Project – [https://csrc.nist.gov](https://csrc.nist.gov)

---

## 📥 Getting Started

1. **Clone Backend**  
   ```bash
   git clone https://github.com/yourusername/encrypted-asl-backend
   cd encrypted-asl-backend
   pip install -r requirements.txt
   python app.py
