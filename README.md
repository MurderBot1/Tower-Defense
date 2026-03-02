# Tower-Defense

## Downloading the game
1. Go to the releases section
2. Download your OS's version
3. Extract it
4. Open the terminal
5. run the executable from the root directory of the project

On Windows in powershell
```
./src/tower-defense.exe
```

## Install the source code with
```
git clone https://github.com/EQ81366/Tower-Defense.git
cd Tower-Defense
```

## How to install on linux:  
Run these commands in the terminal
```
sudo apt install python3
sudo apt install pip
# if this doesn't work replace pip with pip3
pip install -r requirements.txt
```

## How to install on windows:
Run this in command prompt
```
curl -L "https://www.python.org/ftp/python/3.13.12/python-3.13.12-amd64.exe" -o python-installer.exe
python-installer.exe /quiet InstallAllUsers=1 PrependPath=1 Include_test=0
python -m pip install -r requirements.txt
```

## How to install on mac:
Run this in terminal
```
curl -L "https://www.python.org/ftp/python/3.14.3/python-3.14.3-macos11.pkg" -o python.pkg
sudo installer -pkg python.pkg -target /
python -m pip install -r requirements.txt
```

## Run the game with
```
python src/main.py
```
