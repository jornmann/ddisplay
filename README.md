# ddisplay
A dmenu script for connecting your external monitor

## What ddisplay is?
Is a dmenu script that helps you to connect your external monitor/tv/video projector to your bare metal

## How can I install it?
1: Download the "ddisplay" file (it would be available on releases too)

2: Open your text editor and load the file

3: Edit these 3 lines. 

![image](https://user-images.githubusercontent.com/88589756/168911425-d4cb9aa4-3abd-4973-8ac5-68d5385dfce5.png)

You don't know what should you type there? Connect your external monitor, open the terminal and type `xrandr`. It would show something like this:

![image](https://user-images.githubusercontent.com/88589756/168911787-a452a1fa-72ac-4234-a25f-1968384ac360.png)

According to this, you'll find everything you need:

![image](https://user-images.githubusercontent.com/88589756/168912453-47417863-5749-4f9d-913e-a63ece5f09d9.png)

Like that: 

![image](https://user-images.githubusercontent.com/88589756/168913090-0921d752-173b-47a6-b3f0-34e6d8044c15.png)

4: Save the file, and `chmod +x ./ddisplay` and `doas (or replace doas with sudo) cp ./ddisplay /bin/ddisplay`

5: Enjoy connecting your cool monitor/tv/video projector ;)

## Do you have an idea or want to contribute?
Feel free to join. Everyone can `git clone` edit and then `git add --all && git commit -m "My commit" && git push`. So enjoy ;)
