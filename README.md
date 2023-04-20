# Introducing
**Introducing the Nebula project - an open-source browser built from scratch using the Python programming language!
Nebula is a powerful tool for exploring and navigating through code files. It was designed to be an open-source alternative to other popular browsers, providing a fast and intuitive browsing experience. Nebula is written in Python, making it a great choice for those looking to learn about programming or contribute to open-source code.**

**The Nebula browser is highly customizable and offers various configuration options to suit the needs of each user. It is designed to run on multiple operating systems, including Windows, Linux, and Mac OS.**

**The Nebula project is an impressive example of an open-source initiative that is contributing to the programming community worldwide. If you're looking for a fast, reliable, and customizable open-source browser, Nebula is an excellent choice!**
#
# Pre-requisites
```
- python
- git
- Free Space = 1GB
- PyQt5
- PyQtWebEngine
- libqt5gui5
```
**To install python you can install it on the project's official site:**
```
https://www.python.org/downloads/
```
**To install git:**
```
https://git-scm.com/downloads
```
**To install PyQt5:**
```
pip install PyQt5
```
**To install PyQtWebEngine:**
```
pip install PyQtWebEngine
sudo apt install python3-pyqt5.qtwebengine
```
**To install libqt5gui5 in Linux (Ubuntu):**
```
sudo apt-get install libqt5gui5
```
**For Fedora:**
```
sudo dnf install qt5-qtx11extras
```
**For Windows:**

Follow this tutorial:
* Go to the Qt download page: https://www.qt.io/download
* Choose the appropriate version of Qt (e.g., Qt 5.15.2) and download the installer for Windows.
* Run the installer and select the desired components. Make sure to select the "Qt 5.15.2 -> Qt -> Qt 5.15.2 -> Desktop gcc 64-bit" component, which includes the necessary plugins for running your script.
* Follow the prompts and complete the installation.
# Installation
**First you need to clone the nebula repository with git:**
```
git clone https://github.com/Centauri-OS/Nebula
```
**To make Nebula work under Windows follow this tutorial:**
* Right-click on the Nebula.py
* Select "Open with" and then "Choose another app".
* In the "Open with" window, scroll down and select "More apps".
* In the list of apps, select "Look for another app on this PC".
* Navigate to the folder where Python is installed and select the Python executable (usually called "python.exe"). Make sure to select the option "Always use this app to open .py files".
* Click "OK" to save the changes and close the window.

**For Linux:**
**In the terminal:**
```
chmod +x Nebula.py
```
**Go to your bash profile of preference, in this case I am using bashrc as an example:**
```
nano ~/.bashrc
alias Nebula = "./directory_where_you_left_nebula/Nebula.py"
source ~/.bashrc
```
**For MacOS:**
* Open "Script Editor" on macOS.
* Write the following code:
```
do shell script "python /directory_where_you_left_nebula/Nebula.py"
```
* Save the file with the ".app" extension (e.g. "Nebula.app").
* Open "Automator" on macOS.
* Select the "Application" option.
* Drag the "Run AppleScript" item to the right panel.
* Paste the code from step 2 into the "Run AppleScript" field.
* Save the application.
