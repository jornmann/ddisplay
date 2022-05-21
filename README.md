# ddisplay
A dmenu script for connecting your external monitor

## What ddisplay is?
It's a dmenu script that helps you to connect your external monitor/tv/video projector to your bare metal

## How can I install it?
1: Download the "ddisplay" file (it would be available on releases too)

2: Open your text editor and load the file

3: Edit these 4 lines. 

![image](https://user-images.githubusercontent.com/88589756/169661028-d7d3e300-e415-4fe2-bd06-b9a385cfe9d9.png)

You don't know what you should type there? Connect your external monitor, open the terminal and then type `xrandr`. It would show something like this:

![image](https://user-images.githubusercontent.com/88589756/168911787-a452a1fa-72ac-4234-a25f-1968384ac360.png)

According to this, you'll find everything you need:

![image](https://user-images.githubusercontent.com/88589756/169661208-925174ea-1b2f-452f-92a7-c5b1b2bee7cf.png)

Like that: 

![image](https://user-images.githubusercontent.com/88589756/169661308-9525d293-5a24-44d6-88b9-80bf130614b8.png)

4: Save the file, and `chmod +x ./ddisplay` and `doas (sudo) cp ./ddisplay /bin/ddisplay`

5: Enjoy connecting your cool monitor/tv/video projector ;)

## Do you have an idea or want to contribute?
Feel free to join. Everyone can `git clone` edit and then `git add --all && git commit -m "My commit" && git push`. So enjoy ;)
