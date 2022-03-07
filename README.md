# RageMP-EclipseRP-Safe-Cracker

## This will automaticly try to guess all possible code combinations (10000). The list was taken from [Here](https://github.com/danielmiessler/SecLists/blob/master/Passwords/Common-Credentials/four-digit-pin-codes-sorted-by-frequency-withcount.csv)

**I made this with very slim almost to none python knowlage so the code is dogshit, but it works *(might have some errors due to me not having alot of time to test it out. (Got banned for ban evading))***

**If there is any number skipping open ECRP_SafeCracker.py, add .10 to every `time.sleep()` E.G: if it is: `time.sleep(0.3)` change it to `time.sleep(0.4)`**

**I Wont be working on this anymore btw.**

# How to use
1. Download: "ECRP_SafeCracker.py"
2. pip install the requirements:
```
pynput==1.7.6
pywin32==303
```
3. In EclipseRP go near a safe/door that you want to unlock, Open the keypad, run the script (Make sure when you close the keypad you can just press e to open it back up).

by meaning "Open the keypad" I mean this (ignore the crosshair): ![image](https://i.imgur.com/SSvmRK7.png)


4. Open cmd as `administrator` and type: python (Full python script location. E.G: `python C:\Users\Admin\Desktop\ECRP_SafeCracker.py`)
- If you don't open cmd as `administrator` script might not work due to RageMP running in administrator!

- If you get Afk Math press F3 to stop the script from running, answer the Afk math, open the program again and type the last code it had tried.
- If you get the safe unlocked press F3 to stop the script from running. The code that it tried to crack should be in the cmd. 

# I don't have python installed what do I do?
1. Download: [Python](https://www.python.org/ftp/python/3.9.0/python-3.9.0-amd64.exe)
- Open python installation file, Select: "Add Python 3.9 to PATH", press "Install Now"
