# 📁 Automated File Organizer
**CodTech IT Solutions — Python Programming Internship**  
Task name : Automated File Organizer  
Intern : B.SHAM  
Intern ID  : CITS5427  
Domain : Python Programming  
Duration : 4 Weeks  
Internship Period : 22 June 2026 - 20 July 2026

## 📌 Project Overview

The **Automated File Organizer** is a Python script that automatically scans a given directory and organizes all the files into neatly categorized sub-folders based on their file extension. Instead of manually sorting hundreds of files, you simply run this tool and it does the heavy lifting in seconds.

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🗂️ Auto-categorization | Sorts files into 8 categories (Images, Videos, Audio, Documents, Archives, Code, Executables, Others) |
| 🔁 Conflict handling | Appends a counter instead of overwriting existing files |
| 📋 Detailed logging | Creates a `file_organizer.log` for every run |
| 📊 Summary report | Prints how many files moved to each category |
| 🛡️ Safe operation | Skips sub-folders and the log file itself |
| 💻 Cross-platform | Works on Windows, macOS, and Linux |

## 📂 File Categories

```
📁 Your Directory/
├── 📁 Images/       → .jpg .jpeg .png .gif .bmp .svg .webp .tiff .ico
├── 📁 Videos/       → .mp4 .avi .mkv .mov .wmv .flv .webm .mpeg .3gp
├── 📁 Audio/        → .mp3 .wav .aac .flac .ogg .wma .m4a .opus
├── 📁 Documents/    → .pdf .doc .docx .txt .xls .xlsx .ppt .pptx .csv .md
├── 📁 Archives/     → .zip .tar .gz .rar .7z .bz2 .xz .tgz
├── 📁 Code/         → .py .js .html .css .java .cpp .c .go .rb .php .sql .json
├── 📁 Executables/  → .exe .msi .apk .dmg .deb .rpm
├── 📁 Fonts/        → .ttf .otf .woff .woff2
└── 📁 Others/       → Everything else
```

## 🛠️ Technologies Used

- **Language** : Python 3.x
- **Libraries** : `os` · `shutil` · `logging` · `datetime` *(all built-in, no pip install needed)*
```

```
##  Project Scope
This project automatically organizes files into folders based on their file extensions such as Images, Documents, Videos, and Audio files.
```

```
##  Technologies Used
1.Python  
2.OS Module  
3.Shutil Module  
```

```
##  Features
1.Automatic file sorting  
2.Folder creation  
3.File moving automation  
```

```
## Project Structure
automated-file-organizer/  
│  
├── file_organizer.py     ← Main Python script  
├── file_organizer.log    ← Auto-generated log file (after first run)  
└── README.md             ← Project documentation  
```

```
## How It Works (Step-by-Step)
Step 1 → User provides a directory path  
         ↓  
Step 2 → Script lists all files in that directory  
         ↓  
Step 3 → For each file, extract the extension (.jpg, .pdf, etc.)  
         ↓  
Step 4 → Look up extension in FOLDER_MAP to find category  
         ↓  
Step 5 → Create the category sub-folder (if it doesn't exist)  
         ↓  
Step 6 → Check for name conflicts → rename if needed  
         ↓  
Step 7 → Move the file using shutil.move()  
         ↓  
Step 8 → Log the action & update summary counter  
         ↓  
Step 9 → Print final summary report  
```

```
## Conclusion
This Automated File Organizer efficiently sorts files into categorized folders, reducing manual effort and improving file management. The project demonstrates Python automation, file handling, and GUI development using Tkinter.
```

