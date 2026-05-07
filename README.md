# Living-The-Guide
A simple guide I made for anyone who wants to start emulation using Ryujinx (especially for those who want to emulate Tomodachi Life: Living The Dream)
- DISCLAIMER: I did not create nor contribute to the production of the software mentioned. All credits go to their rightful creators.

# Credits go to:
- gdkchan and the Ryubing Team (Ryujinx Canary)
- dezem (Switch Army Knife)
- THZoria (Switch Firmware)
- prodkeys.net (Switch Prod Keys)
- notUltraNX (ROM database)

# What you'll need:
- An emulator
- Firmware
- Keys
- Your game of choice

# Where you'll find them:
- [Ryujinx Canary](https://git.ryujinx.app/ryubing/canary/releases) (Any build should do, I use 1.3.269)
- [Switch Army Knife](https://github.com/dezem/SAK) (To convert NSZ to NSP)
- [Switch Firmware](https://github.com/THZoria/NX_Firmware/releases) (Make sure to download the latest aka. 22.1.0)
- [Switch Keys](https://prodkeys.net/ryujinx-prod-keys-update/) (Make sure the file you'll download matches the version of your firmware; 22.1.0)
- [ROMs of choice](https://not.ultranx.ru/) (You need an account to download ROMs but you don't need an email to register)

# Importing your Firmware and KEYS file
<img width="592" height="144" alt="image" src="https://github.com/user-attachments/assets/2183887e-a8e0-47b4-8c9c-63cf55f07c8e" />
- You can directly import the .ZIP file of your firmware here
<img width="527" height="150" alt="image" src="https://github.com/user-attachments/assets/469de581-06f6-483b-afde-4bedefed6a46" />
- You can directly import the prod.keys file from your extracted keys folder here

# Importing your prod.keys file to Switch Army Knife
<img width="1701" height="892" alt="image" src="https://github.com/user-attachments/assets/f6a34f3a-8131-44c4-be9e-d3b7f1226d55" />
- Before opening Switch Army Knife, make sure you copy your prod.keys file and paste it onto the folder named bin. Keep in mind that you should be on the "SAK-64bit" folder instead of the "SAK-32bit" folder, unless you're using a 32-bit system

# Converting yor NSZ file to NSP via Switch Army Knife
<img width="510" height="427" alt="image" src="https://github.com/user-attachments/assets/bc4ce6a1-8122-49b0-8052-40d0243be7f4" />
- Upon opening Switch Army Knife after the previous step, click on NSZ to NSP, and then select your file. Once selected, click on "Decompress NSZ file" and when it's done, your NSP file should appear in the SAK-64bit folder.

# Importing games to Ryujinx
<img width="1318" height="1009" alt="image" src="https://github.com/user-attachments/assets/920b5706-2ddb-4a75-886f-841035f433ed" />
- Head over to Ryujinx and click on Options > Settings on the top left as shown. Go to Game Directories and click the "Add" button below. I suggest putting all your games in a folder and then selecting that folder, then click "Apply"

# Important settings to check on Ryujinx
- On the "Graphics" tab, make sure that "Vulkan" is selected as the Graphics Backend.
- Make sure Shader Cache, Texture Recompression, and Macro HLE are also enabled.
- If you're done, click "OK", and you should be good to go!

# TECHNICAL DISCLAIMERS
- If you are using an AMD GPU, chances are you may notice slight artifacting on some game elements depending on your Ryujinx version. If so, don't worry as this is a visual bug and does not affect performance whatsoever.
- TL:LTD is locked to 30 FPS, as this is emulating the Switch 1 version of the game, and not the Switch 2 version.
