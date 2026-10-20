# ShadowFrame

Hide secret messages inside images, protected with a password.

**Live demo:** https://shadowframe-lq50.onrender.com

## Features
- Hide text in PNG/JPG images (LSB steganography)
- Password-based encryption before hiding
- Simple, responsive interface

## Run locally
    git clone https://github.com/kssonu2027/ShadowFrame.git
    cd ShadowFrame
    python -m venv venv
    venv\Scripts\activate
    pip install -r requirements.txt
    python app.py

## Note
Share encoded images as a file or ZIP. WhatsApp and social apps
recompress photos and destroy the hidden message.
