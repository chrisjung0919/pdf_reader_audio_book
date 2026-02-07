# PDF Text-to-Speech Reader

> **Opens a PDF and reads it out loud, page by page**

---

## 📖 Project Overview  
A simple Python utility that combines **PyPDF2** and **pyttsx3** with a file dialog to:

- Select a PDF file from your computer  
- Extract and read text from each page  
- Speak it aloud using your system’s voice engine  

Great for listening to books, notes, or articles without internet.

---

## 🙏 Inspiration & Credits

| Resource | How it helped |
| -------- | ------------- |
| 🎥 YouTube — [“Python PDF Reader & Text-to-Speech Tutorial”](https://www.youtube.com/watch?v=Flm2YHEFd5A) | Showed how to combine file dialog, PDF reading, and text-to-speech |
| 📚 PyPI — [PyPDF2](https://pypi.org/project/PyPDF2/) | Used to extract text from PDF pages |
| 📚 PyPI — [pyttsx3](https://pypi.org/project/pyttsx3/) | Used for offline text-to-speech output |

---

## ⚙️ Requirements

| Package     | Install Command           |
|-------------|---------------------------|
| PyPDF2      | `pip install PyPDF2`      |
| pyttsx3     | `pip install pyttsx3`     |

---

## 📂 How to Use

1. **Install dependencies**  
   ```bash
   pip install PyPDF2 pyttsx3
   ```

2. **Run the script**  
   ```bash
   python main.py
   ```

3. **Select your PDF** using the file dialog and listen as it's read aloud.

---

## 🗂️ Project Structure
```
pdf_tts_reader/
├─ main.py               # main script
└─ README.md
```

---

## 📹 Tutorial Reference

“Python PDF Reader & Text-to-Speech Tutorial” by Original Creator (Standard YouTube License)  
<https://www.youtube.com/watch?v=Flm2YHEFd5A>


📄 **[View Screen Layouts (PDF)](Screen_Layouts.pdf)**
