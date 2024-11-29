![Logo](https://files.catbox.moe/3ioqa0.png)

# RedM Frequently Asked Questions (FAQs)

1. **What is RedM?**
```
RedM is a platform for modding and playing the PC version of Red Dead Redemption 2 on private servers. RedM allows players to set up their own servers, add various mods (scripts etc.) and have custom RP (Roleplay) experiences.
```

2. **If I buy the game from Rockstar/Epic/Steam, will it work with RedM?**
```
Yes, any legal copy of the game purchased through Steam, Rockstar and Epic Games will work fine. Steam only needs to be open in the background for authentication purposes. Red Dead Online also works independently with RedM, but this may change in the future.
```

3. **If I buy Red Dead Online, can I still play RedM?**
```
Yes, Red Dead Online is enough for you to play RedM.
```

4. **How to Install RedM?**
```
Step 1: Make sure you have the PC version of Red Dead Redemption 2 and have installed the latest version of the game


Step 2: Download RedM from the official website (https://redm.net/)


Step 3: Open RedM and complete the installation


Step 4: After installation, you can connect to the server of your choice and play
```

5. **In-Game Microphone / Voice Chat Not Working, How Can I Fix It?**
```
Step 1: Make sure your microphone is connected correctly.


Step 2: Check microphone permissions in Windows (Settings > Privacy > Microphone).


Step 3: Check the audio settings in the game and make sure the microphone is selected as the correct input device.

```

6. **How do I clear my game cache?**
```
You can delete the folder “\Users\User\AppData\Local\RedM\RedM.app\data”. If you need to delete only cache, you need to delete cache, server-cache, server-cache-priv files in the “...\data” folder.
```

7. **How to verify game files?**
```
Steam Launcher
- Go to the Library screen
- Right-click on the game in your library and select “Properties”.
- Go to the “Installed Files” tab.
- “Verify integrity of game files”


Epic Games Launcher
- Open the Epic Games launcher
- Go to the library
- Find Red Dead Redemption 2 in the list.
- Click on the gear icon to the right of Red Dead Redemption 2
- Click Verify


Rockstar Games Launcher
- Open Rockstar Games Launcher
- Go to settings
- Click on the My installed games tab
- Choose Red Dead Redemption 2
- Click on the Validate Integrity button
```

8. **My game stuck on the loading screen**
```
• Go to your game settings and turn off Vsync.
• Restart your Red Dead Redemption 2 to see if it loads normally.
• If the infinite loading screen issue persists, go to the NVIDIA Control Panel. 
• Under Manage 3D Settings, click on Program Settings > Add > Select your Red Dead Redemption 2 .exe file.
• Then scroll down the list and click on Vertical Sync and Triple Buffering, and set both to On. Click Apply to save the changes.

• If this method doesn’t work, go to NVIDIA Control Panel > Manage 3D Settings > Restore Defaults. If these methods don’t work; Repair your system
 files (try this if you are considering formatting and are not worried about data loss). Checking and restoring your system files can take a long time and requires computer skills. You will need to run many commands, wait for the process to complete, or risk your personal data. Scan for corrupt files using the System File Checker System File Checker (SFC) is a built-in Windows tool for identifying and repairing corrupt system files.

• On your keyboard, press the Windows logo key and R at the same time to open the Run box. To run the Command Prompt as an administrator, type cmd and press Ctrl+Shift+Enter.

• Or, you can search for CMD and open it as an administrator (simple).

• In the Command Prompt, type "sfc /scannow" and press Enter.

• The System File Checker will begin scanning all system files and repairing 
any corrupt or missing ones it detects. This may take 3-5 minutes.

• After verification, you may receive the following messages: no errors it fixed some errors could not fix all errors could not fix errors at all Regardless of which message you receive, you can try running dism.exe (Deployment Image Servicing and Management) to further scan your computer’s health.

• Run Command Prompt (CMD) as administrator and enter the following commands. This command line will scan your computer’s health: dism.exe 
/online /cleanup-image /scanhealth This command line will restore your PC’s health: dism.exe /online /cleanup-image /restorehealth
```

9. **RAGE error: How to resolve ERR_GFX_STATE Error?**
```
We go into the “System.xml” I specified in “\Users\User\Documents\Rockstar Games\Red Dead Redemption 2\Settings\System.xml” and look for the “VULKAN” text. Replace “VULKAN” with “DX12”. If not, you can try the opposite.
```

10. **There is a white bar on the right side of my screen in the game or In-game HUDs do not fit on the screen properly. How can I solve this?**
```
RedM Launcher > Settings > Game > Under the "Fixed-size NUI" section, check the box to the left of the option that says, "Force in-server UI to 1920x1080 resolution, scaled/letterboxed to fit (for servers with UI assuming 1920x1080)."
```

11. **Players voice coming from behind me or elsewhere / Sound problem on Wide Monitors**
```
Solution to the issue with Windows 11 Spatial Sound/ Dolby Atmos / Windows Sonic


To access spatial sound settings: "Windows Settings > System > Sound > Headphones (your device) > Properties > Spatial Sound"
```

12. **My FPS started to drop as I started playing on servers**
```
Apart from optimizing game settings and other hardware issues, you can try clearing the game cache.

If you don't know how to clear your game cache, see point 6
```

13. **RedM Rockstar Launcher - We couldn't sign you in aotumatically, please login manually using...** (You try to open RedM and Rockstar Launcher asking you to enter your rockstar account)
```
After entering the account information, press “Contact Support” on the verification code screen, then re-enter your account on the screen that opens.
```

> [!NOTE]
> This document is open to updating and adding new information over time. Frequently asked questions, solutions and new information will be regularly incorporated into the document based on the needs of players and developers. The goal of the document is to quickly and effectively answer RedM related issues, guide players and provide a better gaming experience.
