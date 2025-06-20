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

```bash
git clone https://github.com/yourusername/auto-file-sorter.git
'''

2. Open the folder:

bash
Copy code
cd auto-file-sorter
Run the Python script:

3. Run the Python script:
bash
Copy code
python file_sorter.py
🧠 How It Works
Looks inside your ~/Downloads folder

Matches each file by its extension

Moves it to the appropriate folder (auto-creates it if needed)

If a file type isn't recognized, it goes into the Others/ folder

💡 Usage
Make sure Python is installed.

Open your terminal and run the script:

bash
Copy code
python file_sorter.py
Type sort when prompted:

text
Copy code
Type 'sort' to organize Downloads: sort
The script will organize your files and display what was moved.

🛠️ Requirements
Python 3.6+

Works on Windows, Linux, and macOS

No third-party dependencies

