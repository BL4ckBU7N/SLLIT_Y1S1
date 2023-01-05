- Original Papers and Markings (Scanned PDFs) are located in Resources.rar

**FFLUSH REFERENCE**

**fflush** - *flushes (clears) the buffer/stream*

**stdin**  - *input stream*

- `c = getchar();`  *//get first input*
- `fflush(stdin);`  *//flush first input*
- `c = getchar();`  *//get input again*
---
### Configure GCC compiler for Text Editors
1. Downoad & Install [MSYS2](https://github.com/msys2/msys2-installer/releases/download/2022-12-16/msys2-x86_64-20221216.exe)
3. Open MSYS2
	- Type "pacman -Syu"
	- Type "pacman -Su"
4. Open MSYS2 MinGW
	- Type "pacman -Ss gcc"
	- Copy Package Name - [mingw-w64-x86_64-gcc]
	- pacman -S [Package-Name]
	- Type "pacman -Ss gdb"
	- Copy Package Name - [mingw-w64-x86_64-gdb]
	- pacman -S [Package-Name]
5. Check On MSYS2
	- gcc --version
	- g++ --version
	- gdb --version
6. Add Encironment Varieables
	- Copy installation location  *C:\msys64\mingw64\bin
	- Environment Varieables > System Varieables > Path > Edit > New > Paste location
7. Check On CMD or PowerShell
	- gcc --version
	- g++ --version
	- gdb --version
---
Downloads : 

[Dev C++ Dark Version](https://github.com/Embarcadero/Dev-Cpp)

[Fira Code Font](https://github.com/tonsky/FiraCode)



![GitHub repo size](https://img.shields.io/github/repo-size/BL4ckBU7N/SLIIT_Y1S1)
![GitHub Discussions](https://img.shields.io/github/discussions/BL4ckBU7N/SLIIT_Y1S1)
![GitHub contributors](https://img.shields.io/github/contributors/BL4ckBU7N/SLIIT_Y1S1)

![GitHub Repo stars](https://img.shields.io/github/stars/BL4ckBU7N/SLIIT_Y1S1?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/BL4ckBU7N/SLIIT_Y1S1?style=social)
