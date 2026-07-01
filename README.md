# G6ThumbCameraFirmware
- For firmware version HF 9850-260513. 
'''backup1.bin'''
- binwalk did not work properly with extraction, so used foremost, changed the boot up sound to a 4 second pc boot, (which feels a bit too long and i think i will make it shorter later).
- put a JAWS pixelart or opening, and an octopus pixelart for closing (compressed to fit bytes, kinda ...., might fix it later). '''modified1.bin'''
- Using HxD, incremented the byte at offset 0x14, removed the last byte.
'''hx330x_sdk.bin'''

## To Use:
Simply put the sdk.bin (Go inside the HF 98-260513) into the root of the sd card and boot up the camera normally. It will open up, then will have something like a loading screen come up and turn off.
Congratulations you now don't have a bad boot sound, and have good artwork for the screen.
You can delete the .bin file from you sdcard now.

**It will basically look like this:**  
F:\
|AUDIO  
|LOST.DIR  
|PHOTO  
|VIDEO  
|hx330x_sdk.bin

Sources:
- For general steps to follow: https://www.reddit.com/r/toycameras/comments/1quqesl/g6_thumb_camera_firmware_dump/
- Sound: https://freesound.org/s/649067/
- Images: by u/Alan_M28 on reddit
    -   Welcome screen: https://www.reddit.com/r/PixelArt/comments/18az9gu/jaws_just_a_fun_bit_of_fan_art_320240_58_colours/
    -   Turn off screen:
https://www.reddit.com/r/PixelArt/comments/1qyutod/octopus_vs_sub_320240_4_colours_painted_in/