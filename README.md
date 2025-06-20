# 🗂️ Auto File Sorter – Python Downloads Organizer

Organize your chaotic `Downloads` folder in one click!  
This Python script scans your Downloads directory and automatically **sorts files by type** into subfolders like `Images`, `Videos`, `Documents`, `Apps`, and more.

## 🚀 Features

- ✅ Automatically sorts common file types (e.g. `.mp4`, `.jpg`, `.pdf`, `.exe`, `.json`)
- 📂 Creates folders like `Music`, `Zips`, `Apps`, etc.
- 🧠 Smart extension detection
- 🧪 Simple command line interface – just type `sort` and go
- 🛠️ No external libraries required – runs on pure Python

---

## 📁 Sorted File Categories

| Folder Name | Extensions Handled |
|-------------|--------------------|
| `Images`    | `.jpg`, `.jpeg`, `.png`, `.gif`, `.webp` |
| `Videos`    | `.mp4`, `.mkv`, `.mov`, `.avi`, `.flv` |
| `Music`     | `.mp3`, `.wav`, `.opus` |
| `Documents` | `.txt`, `.pdf`, `.docx`, `.xlsx`, `.pptx` |
| `Apps`      | `.exe`, `.msi`, `.apk` |
| `ISOs`      | `.iso` |
| `Zips`      | `.zip`, `.rar`, `.7z` |
| `Code`      | `.py`, `.java`, `.c`, `.cpp` |
| `Data`      | `.csv`, `.json`, `.xml` |
| `Others`    | All remaining types |

---

## 📦 Installation

1. Clone this repository or download the script:


```git clone https://github.com/Xhanti/auto-file-sorter.git```

2. Open the folder:
```cd auto-file-sorter```

3. Run the Python script:
```python file_sorter.py```


## 🧠 How It Works

Looks inside your `~/Downloads` folder

Matches each file by its extension

Moves it to the appropriate folder (auto-creates it if needed)

If a file type isn't recognized, it goes into the  `Others/` folder

💡 Usage
1. Make sure Python is installed.

2. Open your terminal and run the script:
```python file_sorter.py```


3. Type sort when prompted:
Type `sort` to organize Downloads: sort


## The script will organize your files and display what was moved.

🛠️ Requirements

º Python 3.6+

º Works on Windows, Linux, and macOS

º No third-party dependencies

