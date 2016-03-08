# SEQTA-Background-changer
A simple chrome extension to customize SEQTA
   _____ ______ ____ _______         ____             _                                   _ 
  / ____|  ____/ __ \__   __|/\     |  _ \           | |                                 | |
 | (___ | |__ | |  | | | |  /  \    | |_) | __ _  ___| | ____ _ _ __ ___  _   _ _ __   __| |
  \___ \|  __|| |  | | | | / /\ \   |  _ < / _` |/ __| |/ / _` | '__/ _ \| | | | '_ \ / _` |
  ____) | |___| |__| | | |/ ____ \  | |_) | (_| | (__|   < (_| | | | (_) | |_| | | | | (_| |
 |_____/|______\___\_\ |_/_/    \_\ |____/ \__,_|\___|_|\_\__, |_|  \___/ \__,_|_| |_|\__,_|
                                                           __/ |                            
   _____ _                                                |___/                                                             
  / ____| |                                   
 | |    | |__   __ _ _ __   __ _  ___ _ __ 
 | |    | '_ \ / _` | '_ \ / _` |/ _ \ '__|
 | |____| | | | (_| | | | | (_| |  __/ |   
  \_____|_| |_|\__,_|_| |_|\__, |\___|_|   
                            __/ |          
                           |___/           
--------------------------------------------------------------------------------------------
Instruction for use:
1. Move the folder to your Computer 
2. Open Chrome and head to settings
3. On the lefthand side click extensions
4. At the top click Developer mode
5. Click Load Unpacked extension
6. Head to this folder and click enter
7. The extension will start loading
8. Enjoy! More Images are comeing soon : )

Email me at marcus7lim@gmail.com for image requests and suggestions

To change the background image, move the image to the main folder and rename it "Image"
Then head over to the extension menu and under the extension click reload.
There are some sample picture located in the Images folder
To make your own images the dimensions are 500 by 750 (height = 750, width = 500)

Warnings:
It only accepts .jpg image for now
(If you gave experience in coding you can change it)

Coding to change the image format:

There are two files you'll have to change
1. manifest.json
	Under "web_accessible_resources": add your image type
2. Content.css
	Near the end of the Url change the file type to your file
