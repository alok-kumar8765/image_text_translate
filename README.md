# 🖼️ Image Text Translator (OCR + Translation)

A Python application that **extracts text from images in any language** using OCR and **translates it into a user-selected target language**.

This project combines:

* **Tesseract OCR** for text extraction
* **Google Translator (deep-translator)** for language translation
* **OpenCV** for image processing

---

## ✨ Features

* 📷 Extract text from images (JPEG, PNG, etc.)
* 🌍 Supports **multiple source languages automatically**
* 🔤 Translate text into **any target language chosen by the user**
* 🧠 Auto language detection
* ⚡ Simple command-line interface
* 🧒 Beginner-friendly & easy to extend

---

## 🛠️ Tech Stack

| Component        | Library           |
| ---------------- | ----------------- |
| OCR              | `pytesseract`     |
| Image Processing | `opencv-python`   |
| Translation      | `deep-translator` |
| OCR Engine       | Tesseract OCR     |
| Language         | Python 3          |

---

## 📦 Installation

### 1️⃣ Install Python Libraries

```bash
pip install opencv-python pytesseract deep-translator pillow
```

---

### 2️⃣ Install Tesseract OCR

#### 🐧 Linux (Ubuntu)

```bash
sudo apt install tesseract-ocr
```

#### 🪟 Windows

* Download from:
  [https://github.com/UB-Mannheim/tesseract/wiki](https://github.com/UB-Mannheim/tesseract/wiki)
* Set path in code if needed:

```python
pytesseract.pytesseract.tesseract_cmd = r"C:\Program Files\Tesseract-OCR\tesseract.exe"
```

#### 🍎 macOS

```bash
brew install tesseract
```

---

### 3️⃣ Install OCR Language Packs (Optional)

```bash
sudo apt install tesseract-ocr-hin tesseract-ocr-spa tesseract-ocr-fra tesseract-ocr-deu tesseract-ocr-ara tesseract-ocr-chi-sim
```

---

## ▶️ How to Run

```bash
python image_translate.py
```

---

## 🧪 Example Usage

```
📷 Enter image path: sample.jpg

🌍 Choose target language:

en → English
hi → Hindi
es → Spanish
fr → French
de → German
ar → Arabic
zh-cn → Chinese

Enter language code: hi
```

---

## 📄 Output

```
📝 --- Extracted Text ---

Hello World

🌐 --- Translated Text ---

नमस्ते दुनिया
```

---

## 🌍 Supported Languages

* English (`en`)
* Hindi (`hi`)
* Spanish (`es`)
* French (`fr`)
* German (`de`)
* Arabic (`ar`)
* Chinese (`zh-cn`)

> Source language is **auto-detected**

---

## 📁 Project Structure

```
├── image_translate.py
├── README.md
└── sample.jpg
```

---

## ⚠️ Common Issues

### ❌ Image not loading

* Ensure image path is correct
* Supported formats: `.jpg`, `.png`, `.jpeg`

### ❌ No text detected

* Image may be blurry or low contrast
* Try improving lighting or resolution

---

## 🚀 Future Enhancements

* 🖥️ Streamlit Web App
* 🔊 Text-to-Speech Output
* 📱 Mobile App (Flutter)
* 🧠 Offline Translation Support
* 📂 Batch Image Processing
* 🤖 AI-powered text summarization

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

---

## 📜 License

This project is licensed under the **MIT License**.

---

## ⭐ If You Like This Project

Give it a ⭐ on GitHub and share it with others!

---
