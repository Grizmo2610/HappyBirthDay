# HAPPY BIRTHDAY WISH

![Gif](image\PyBirthdayWish.gif)

>You can run file PyBirthdayWish.exe in folder dist in exe file or setup as according to under this


## Step 1: 
Dowload and setup VLC Media player to your computer

![VLC](image\VLC.png)

## Step 2: 
Install termcolor, python-vlc, sys, threading, os, time to your computer

## Step 3: 
Open art.py or artwithstars.py in folder arts
> artwithstars.py contain some star

## Step 4: 
Go to [this Web](https://patorjk.com/software/taag/#p=display&f=Crawford2&t=Happy%20Birthday%0A%20%20%20%20%20%20Name) and generate art to replace 'Happy Birthday' with other text and font of you wish to display.


## Step 5: 
Edit the wish in file

## Step 6: 
Open config.py and change line 2

```artFile = "art"``` 

Change "art" with art file you want to use ("art" if edit and use art.py file or "artwithstars" if using artwithstars.py)

## Step 7: 
Run file PyBirthdayWish.py

## Step 8: 
Repeat step 3 if display not as like as you want.

## Step 9: 
Convert file to exe using: pyinstaller --noconfirm --onefile --console --icon "icon.ico" --no-embed-manifest --add-data "arts;arts/" --add-data "config.py;." --add-data "HappyBirthday.mp3;." --add-data "PyBirthdayWish.py;." "PyBirthdayWish.py"



