# GameHub
A console-based C++ project that brings together multiple mini-games like Colored Squares, Catch the Ball, and Rock–Paper– Scissors under one interactive menu.

## How to Run (Windows)

### Option A: Build & Run using Dev-C++ (Easy)
1. Open `GameHub.dev` in Dev-C++.
2. Build and run.

### Option B: Build & Run from PowerShell (MinGW/Dev-C++)

Prerequisite: MinGW (g++ + mingw32-make) installed. If you have Dev-C++ installed, it typically includes MinGW at:
`C:\Program Files (x86)\Dev-Cpp\MinGW64\bin`

From the project folder:
```powershell
cd "./GameHub"
$env:Path = "C:\Program Files (x86)\Dev-Cpp\MinGW64\bin;" + $env:Path

mingw32-make -f Makefile.win clean
mingw32-make -f Makefile.win

./GameHub.exe
```

## Games Included
- Colored Squares
- Catch the Ball
- Rock Paper Scissors
