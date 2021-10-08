# AntiAdmiralCookies
Quickly disable cookies "powered by Admiral"

Disclaimer: Only tested on Linux Mint.

![Showing it off](https://cdn.discordapp.com/attachments/735916878215512146/896168104076406794/EwAdMoney.gif)

## How to install

### Requires python
#### Install python on Windows
1. [Download Python](https://www.python.org/downloads/)
2. Run the installer and make sure to tick the "add to path" box.
3. Follow setup guide for Windows below

#### Install python on Debian Linux
1. open the terminal
2. Enter the following commands:

`sudo apt-get update`

`sudo apt-get install python3 python3-venv python3-pip`

3. See if install was successful with following command:

`python3 --version`

4. Follow setup guide for Linux Debian below

## How to set up
#### Set up for Windows
1. Open windows search bar and search for "cmd" without the quotes and press enter.
2. Enter the following commands:

`python3 -m pip install opencv-python --user`

`python3 -m pip install pyautogui --user`

`python3 -m pip install numpy --user`

#### Set up for Linux Debian
1. Open the terminal.
2. Enter the following commands:

`python3 -m pip install opencv-python --user`

`python3 -m pip install pyautogui --user`

`python3 -m pip install numpy --user`

`sudo apt-get install scrot`

`sudo apt-get install python3-tk`

`sudo apt-get install python3-dev`

## How to use
When encountering a site that has cookies that says "Powered By Admiral" that has an seemingly infintie list of partners you need to turn off manually you can use this.
1. Make sure you're in the "partners" list.
![Partners list](https://cdn.discordapp.com/attachments/735916878215512146/896164060033339392/unknown.png)
2. Make sure at least one partner in the window is ticked to on.
3. Run the python script.
4. Don't touch anything until it closes again.
5. Enjoy having disabled all them cookies with zero effort.
