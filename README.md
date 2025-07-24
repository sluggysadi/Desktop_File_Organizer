# 🗂️ Desktop File Organizer

A simple Python utility to automatically organize files in your current directory by file type. Categorizes documents, images, videos, archives, and more into structured folders for easy access and cleanliness.

## 🚀 Features

- Automatically classifies files into folders:
  - 📄 Documents (`.pdf`, `.docx`, `.txt`, etc.)
  - 🖼️ Images (`.png`, `.jpg`, `.jpeg`, etc.)
  - 📹 Videos (`.mp4`, `.mkv`, etc.)
  - 🗜️ Archives (`.zip`, `.rar`, etc.)
- Works in your current working directory
- Easy to run and install
- Saves time by decluttering your folders

## 📦 Installation

```bash
pip install organizer
```

🏃 How to Use
From your terminal, navigate to the directory you’d like to organize and run:
```bash
$ Organizer
```

📁 Example

Before:
```
Downloads/
├── homework.docx
├── report.pdf
├── work.pdf
├── Catpic.png
├── SQL.zip
├── Work.jpg
```
After:
```
Downloads/
├── Documents/
│   ├── homework.docx
│   ├── report.pdf
│   └── work.pdf
│
├── Archives/
│   └── SQL.zip
│
├── Images/
│   ├── Catpic.png
│   └── Work.
```
🔧 Requirements
- Python 3.6+
- Built-in libraries: os, shutil, argparse

👩‍💻 Author
```
Sadia Fathima
```
