# 🎵 MP3 Tag Reader

## 📌 Overview

MP3 Tag Reader is a command-line application developed in C Programming that allows users to view and edit metadata stored inside MP3 files. The project demonstrates file handling, command-line arguments, modular programming, and binary file operations.

---

## ✨ Features

- View MP3 metadata
- Edit Song Title
- Edit Artist Name
- Edit Album Name
- Edit Year
- Edit Genre
- Edit Comment
- Command-line interface
- Error handling for invalid inputs

---

## 🛠️ Technologies Used

- C Programming
- GCC Compiler
- Linux (Ubuntu/WSL)
- File Handling
- Binary File Operations

---

## 📂 Project Structure

```
MP3-Tag-Reader
│── main.c
│── view.c
│── view.h
│── edit.c
│── edit.h
│── sample.mp3
│── README.md
```

---

## ▶️ Compile

```bash
gcc main.c view.c edit.c -o mp3_tag
```

---

## ▶️ Run

### View MP3 Details

```bash
./mp3_tag -v sample.mp3
```

### Edit Title

```bash
./mp3_tag -e -t sample.mp3
```

### Edit Artist

```bash
./mp3_tag -e -a sample.mp3
```

### Edit Album

```bash
./mp3_tag -e -A sample.mp3
```

### Edit Year

```bash
./mp3_tag -e -y sample.mp3
```

### Edit Genre

```bash
./mp3_tag -e -g sample.mp3
```

### Edit Comment

```bash
./mp3_tag -e -c sample.mp3
```

---

## 📸 Sample Output

View MP3 Details

```
Title   : Example Song
Artist  : Example Artist
Album   : Example Album
Year    : 2025
Genre   : Pop
Comment : Demo
```

---

## 📚 Concepts Used

- File Handling
- Binary File Processing
- Structures
- Functions
- Modular Programming
- Command Line Arguments
- Error Handling

---

## 🚀 Future Improvements

- Support for more audio formats
- Graphical User Interface (GUI)
- Batch editing of multiple MP3 files

---

## 👨‍💻 Author

**Swaraj Gulhane**

Electronics & Telecommunication Engineering

GitHub: https://github.com/swarajgulhane2005-rgb
