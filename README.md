# Gooey Example
Example of packaging a CLI app into an executable with Gooey and PyInstaller

1) Create and activate a virtual environment
2) run ```pip install -r requirements.txt```
3) To check the application run ```python src/main.py```
4) To package the application run:
    - Windows: ```pyinstaller -F --windowed build-win.spec```
    - MacOS: ```pyinstaller -F --windowed build-osx.spec```
5) The executable should be now within the ```dist/``` directory

