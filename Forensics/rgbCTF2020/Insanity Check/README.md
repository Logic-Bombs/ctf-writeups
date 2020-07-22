# Insanity Check

## Description
There's a flag in our Discord server. Can you get it?
Server Link: https://discord.gg/CfhfYPQ

## Writeup
After a keen search, I realised that the answer can only be in the Discord server icon of the CTF\
To download the server icon, open the developer tools in browser with **Ctrl+Shift+i**

Run zsteg on the image to get the flag.

		$ gem install zsteg
		$ zsteg .\rgb.png
		
## Flag
rgbCTF{y0u_c4n_d0wn104d_th1s}
