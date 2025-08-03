# Paraphrase
Paraphrase App is an AI-powered mobile app built with Flutter. It allows users to rephrase content via text, image (camera/gallery), audio, and PDF input. It extracts text and uses a paraphrasing API to generate smart, rewritten versions for academic or creative use.
# 🧠 Paraphrase App – AI-powered Rewriting Tool

The **Paraphrase App** is an AI-powered mobile application developed using **Flutter** (initially designed using FlutterFlow). It helps users paraphrase or rewrite text from various input sources like plain text, images, audio, or PDFs. Ideal for students, content creators, and researchers who want to enhance readability or avoid plagiarism.

---

## 📱 Key Features

- ✍️ **Manual Text Input** – Users can enter any text to paraphrase.
- 📷 **Image Upload** – Upload an image (from gallery or camera), extract text using OCR, and paraphrase it.
- 🎙️ **Speech-to-Text Input** – Record speech and convert it to text for paraphrasing.
- 📄 **PDF Upload** – Choose a PDF file, extract the text, and paraphrase it.
- 🔁 **AI-Powered Paraphrasing** – Uses a backend or third-party API to return paraphrased content.
- 💾 **Results Display** – View rephrased content directly within the app.

---

## 📁 Folder Structure

This project includes only the essential folders:

/lib # Main Dart files including UI, logic, and FlutterFlow generated code
/assets # Images, icons, fonts, PDFs, and other assets

Other folders (`android`, `ios`, etc.) and config files will be regenerated using Flutter tools.

---

## 🛠️ Getting Started

### Step 1: Clone the repository

```bash
git clone https://github.com/your-username/paraphrase-app.git
cd paraphrase-app

Step 2: Make sure Flutter SDK is installed
flutter --version

Step 3: Generate missing project files

flutter create .

Step 4: Install dependencies
flutter pub get

Step 5: Run the app
flutter run


Required Dependencies

dependencies:
  flutter:
    sdk: flutter
  flutter_tts: ^3.5.2           # For text-to-speech (if used)
  speech_to_text: ^6.3.0        # For speech recognition
  pdf_text: ^1.0.0              # For extracting text from PDFs
  image_picker: ^1.0.0          # For picking images
  http: ^1.2.0                  # For making HTTP requests to the paraphrasing API


flutter run
