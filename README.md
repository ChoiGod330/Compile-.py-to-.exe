## Tutorial
### Check if Python is installed (Skip if installed)
1. Press "Win" + "R" to open Utility
2. Enter "cmd" to open CommandPrompt or "powershell" to open PowerShell
3. Run the command below to check if python is installed:
```Shell
python --version
```
4. If you already installed python in your computer, please skip to Install PyInstaller

### Install Python
1. Go to [python.org](https://www.python.org/downloads/)
2. Download the latest version of python
3. Open the installer
4. Ensure "Add Python to PATH" is checked during installation. <--IMPORTANT
![image](https://github.com/ChoiGod330/Compile-.py-to-.exe/blob/main/Install%20Python.png)

### Install PyInstaller
1. Press "Win" + "R" to open Utility
2. Enter "cmd" to open CommandPrompt or "powershell" to open PowerShell
3. Install PyInstaller:
```Shell
pip install pyinstaller
```
4. If "pip" command cannot be used, please reinstall Python and check "Add Python to PATH" during installation.

### Compile .py file to .exe
1. Navigate to the script's(.py) folder:
```Shell
cd C:\[PATH]
```
2. Run the command below:
```Shell
pyinstaller --onefile [FILENAME.py]
```
3. The .exe file will be created in the path
```Shell
C:\[PATH]\dist\[FILENAME.exe]
```



This is a tutorial for compiling .py to .exe written by @ChoiGod330
