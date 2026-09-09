# DSA Journey 🚀

This repository contains C++ solutions and code snippets for Data Structures and Algorithms (DSA).

---

## 🧹 Clearing Up `.exe` Files

When compiling C++ files, executable binary files (`.exe`) are generated in the folder. You can clear out all generated `.exe` files using the terminal commands below.

### PowerShell (Windows)
To delete all `.exe` files in the current workspace folder:
```powershell
Remove-Item *.exe
```
If you want to force remove all `.exe` files recursively across subfolders:
```powershell
Get-ChildItem -Path . -Filter *.exe -Recurse | Remove-Item -Force
```

---

## 🛠️ Compiling and Running C++ Code

To compile and run a C++ file manually in the terminal:

```powershell
# Compile file
g++ filename.cpp -o filename

# Run executable
.\filename
```

> **Note:** Binary output files (`*.exe`, `*.out`, `*.o`) are automatically ignored by Git via [.gitignore](file:///c:/DSA/DSA_Journey/.gitignore).
