3DS Stereoscopic Image Viewer Example
=======
Stereoscopic image viewer for the Nintendo 3DS that displays two png files as a stereoscopic image.
This application utilizes libpng to render two PNG images on screen as a stereoscopic image. The two images "1_left.png" and "1_right.png" /3ds/3dimg/ folder. You must put this folder in the proper place on your SD card for this application to work.

The code for this example is modified from the work of pyroticinsanity (https://github.com/pyroticinsanity/3dsdod) and is licensed GPL 3. 

Controls:
- D-Pad Down - Scroll down
- D-Pad Up - Scroll up
- D-Pad Right - Scroll right
- D-Pad Left - Scroll left
- X - Scale image up
- B - Scale image down
- Start - Exit the homebrew

The images in this example come from ChristIsLord12: https://github.com/christislord12/Love2D-Anaglyph-Demo and are licensed CC0.

Additional Notes:
- The 3DS only supports a max texture size of 1024x1024 so you need to resize any files larger than that.