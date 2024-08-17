---
title: Navigating and Altering Windows Registry Using CLI
date: 2024-08-16T00:21:19.293Z
updated: 2024-08-17T00:21:19.293Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Navigating and Altering Windows Registry Using CLI
excerpt: This Article Describes Navigating and Altering Windows Registry Using CLI
keywords: WinReg Management CLI,CLI Edit Windows Reg,Command Line RegEdit,System RegModify CLI,Registry Tweaks Cli,CLI Adjust Windows Reg,Execute RegCli Change
thumbnail: https://thmb.techidaily.com/bb1f002a7be8b73cd12562f7aa67a81110093e83a5e29cc0296d5b97722e8cc9.png
---

## Navigating and Altering Windows Registry Using CLI

 The Registry Editor is the first thing Windows users bring up when it comes to editing the Windows Registry. However, if you don't want to deal with a distracting GUI and too many clicks, there's a simpler-looking tool you can use: the Command Prompt.

 Although using it takes a little more know-how than the Registry Editor, our guide should be able to get you started.

## How to View the List of Registry Commands in Command Prompt

![the command to view all reg commands](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/the-command-to-view-all-reg-commands.jpg)

 There aren't a lot of commands when it comes to editing the registry using Command Line. To view them all, [open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) and run the below command in Command Prompt:

`reg /?`

 Command Prompt will then list the commands, such as **reg add**, **reg delete**, **reg copy**, and **reg save**.

![the list reg commands in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/the-list-reg-commands-in-command-prompt.jpg)

 If you want to see more information about them, just add the **/?** switch at the end of the command. For, example, if you want to find out what the **reg add** command does, you'd enter the below command:

`reg add /?`

 After you run it, you'll get all the details on what it does and how to use it.

![details of the reg add command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/details-of-the-reg-add-command-in-command-prompt.jpg)

 If you're finding it hard the commands out on your own, don't worry. We will simplify it for you and show you how to get started using them.

## Add and Delete Keys in the Windows Registry

 To add a key to the registry using Command Prompt, you need to use the **reg add** command while specifying the path to the new key and whether you want to force the operation with the **/f** switch(this will bypass the need for the confirmation prompt).

 As always, when it comes to editing the Windows Registry, we recommend that the first thing you do is [create a system restore point on Windows](https://www.makeuseof.com/use-system-restore-windows/).

 Here's an example:

`REG Add HKLM\SOFTWARE\MyNewKey /f`

 In the above command, we're adding the **MyNewKey** subkey to the **KHLM/Software** key. If you go to the Registry Editor and expand that key, you'll be able to see the **MyNewKey** subkey within it.

 Deleting the key is simple as well, as you just need to replace **add** with **delete** in the above example. Here's how:

`reg delete HKLM\SOFTWARE\MyNewKey /f`

 Now the **MySubKey** key will disappear in the Registry Editor.

## How to Add, Modify, and Delete Values in the Windows Registry

![adding a value to Windows registry in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/adding-a-value-to-windows-registry-in-command-prompt.jpg)

 To add or modify a value key in the registry using Command Prompt, you'll still use the **reg add** command like above. However, this time, you'll also have to specify the following parameters: value (**/v**), value type (**/t**), and value data (**/d**). Here's an example of what the command would like:

`reg add HKLM\SOFTWARE\MyNewKey /v MyValue /t REG_DWORD /d "1" /f`

 Once you run the command, you will be able to find the value in the Registry Editor. And if the key doesn't exist, Command Prompt will create it.

 The Windows Registry uses several value types, and here's a table of the common ones:

| Value Type      | Description           |
| --------------- | --------------------- |
| REG\_NONE       | No value type         |
| REG\_SZ         | String value          |
| REG\_MULTI\_SZ  | Multi-string value    |
| REG\_EXPAND\_SZ | Expanded string value |
| REG\_DWORD      | 32-bit DWORD value    |
| REG\_QWORD      | 64-bit QWORD value    |
| REG\_BINARY     | Binary value          |

 To delete the value, you just need to use the **reg delete** command while specifying the path to the key, and the name of the value. Here's an example of deleting the value we created earlier:

`reg delete HKLM\SOFTWARE\MyNewKey /v MyValue /f`

 After running the above command successfully, the value should disappear from the Registry Editor.

## How to Copy Registry Entries From One Key to Another

![transfering entries from one registry key to another in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/transfering-entries-from-one-registry-key-to-another-in-command-prompt.jpg)

 Sometimes, you might want to copy the values from one key to another in the registry. This is as easy as using the **reg copy** command while specifying the key you're copying them from and the one you're copying them to (keep in mind that both keys have to already exist before you run the command). Here's an example:

`reg copy HKLM\SOFTWARE\MyNewKey1 HKLM\SOFTWARE\MyNewKey2 /s`

 The **/s** switch at the end tells Command Prompt that it should copy every subkey and value in the first key (**MyNewKey1**) into the second one (**MyNewKey2**).

 Unfortunately, there's no way to copy specific values from one key to another. You'll have to use the Registry Editor for that.

## How to Import Registry Entries

![importing a registry file in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/importing-a-registry-file-in-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you have [created a Windows Registry file](https://www.makeuseof.com/windows-registry-file-guide/) or downloaded it elsewhere, you can import it into the registry using the **reg import** command. All you need to do is specify the path to the registry file and Command Prompt will do the rest. Here's an example:

`reg import C:\Users\CHIFUNDO\Desktop\MyRegFile.reg`

 Once you run that command, the contents of the reg file will be merged with the registry.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
## How to Export Registry Entries

![exproting a registry key in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/exproting-a-registry-key-in-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->

 You can export a key in the registry using the **reg export** command while specifying the path of the key you want to export and the file you want to create. This comes in handy when you need to back up certain keys and values to restore them elsewhere. Here's an example:

`reg export "HKLM\SOFTWARE\MyNewKey" D:\Reg_Backup\CHIFUNDO\Desktop\MyRegFile.reg`

 After you run the command successfully, check the location you entered, and you'll find the key and its associated subkeys and values have been exported successfully. In our case, it will create a file called **MyRegFile.reg** and save it on the desktop.

 You can also export a specific value using the **reg query** command and include the key, value, and path to the registry file you want to export the value to. Here's an example.

`reg query HKLM\SOFTWARE\MyNewKey /v MyValue > C:\Users\CHIFUNDO\Desktop\MyRegFile.reg`

 The resulting registry file will only contain the key and the specific value you exported.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
## How to Save Registry Entries

![saving-a-key-to-a-registry-file-in-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/saving-a-key-to-a-registry-file-in-windows.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->

 If you already have a registry file or any other text file, you can add keys to it using Command Prompt and the **reg save** command, which will overwrite the file with the new information. You just need to specify the name of the key and the registry file you want to save it to. Here's an example:

`reg save HKLM\SOFTWARE\MyNewKey2 C:\Users\CHIFUNDO\Desktop\MyRegFile.hiv /y`

 The **/y** switch at the end of the command above overwrites the file you're saving the key to without bringing up a prompt. When you open the file, you won't be able to read the contents since it will be saved as a binary file.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Restore Registry Entries

![restoring-a-registry-key-in-command-prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/restoring-a-registry-key-in-command-prompt.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->

 So, let's say something has happened to the keys and values within the **MyNewKey2** we saved in the previous section, you can use the backup file you created to restore it. You'll need to use the **reg restore** command. Here's how to run it:

`reg restore HKLM\SOFTWARE\MyNewKey2 C:\Users\CHIFUNDO\Desktop\MyRegFile.hiv`

 Now the **MyNewKey2** key should return to the state it was in when you made the backup.

## Tweak the Registry Without the Registry Editor

 While Command Prompt can't do everything the Registry Editor does, it does offer a quick way to edit the registry without opening the aforementioned tool. While using Command Prompt to tweak the registry is quite advanced, even if you're the average user, you should be able to get by if you follow along closely.

 Just don't forget to do what we mentioned earlier to avoid permanently ruining your Windows computer and create a system restore point first

 Although using it takes a little more know-how than the Registry Editor, our guide should be able to get you started.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-strategizing-an-attention-grabbing-tiktok-signoff/"><u>[New] 2024 Approved  Strategizing an Attention-Grabbing TikTok Signoff</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-fb-snapcast-converter/"><u>[New] FB Snapcast Converter</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-techniques-for-efficiently-storing-fb-messenger-conversations-for-2024/"><u>[New] Techniques for Efficiently Storing FB Messenger Conversations for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solved-counter-strike-2-mic-not-working/"><u>[SOLVED] Counter-Strike 2 Mic Not Working</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-effortless-preservation-of-your-loved-instagram-reels/"><u>[Updated] In 2024, Effortless Preservation of Your Loved Instagram Reels</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-ultimate-funny-photo-editor/"><u>[Updated] Ultimate Funny Photo Editor</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-transform-ideas-into-engaging-movies-using-youtube-editor/"><u>2024 Approved  Transform Ideas Into Engaging Movies Using YouTube Editor</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-visualizing-chronoscopic-imagery-in-media/"><u>2024 Approved  Visualizing Chronoscopic Imagery in Media</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-for-the-savvy-employee-advanced-methods-for-drafting-and-delivering-tough-workplace-emails/"><u>ChatGPT for the Savvy Employee: Advanced Methods for Drafting and Delivering Tough Workplace Emails</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-lack-of-access-for-windows-app-removal/"><u>Correcting Lack of Access for Windows App Removal</u></a></li>
<li><a href="https://win11.techidaily.com/corrective-measures-for-disk-read-failure-windows/"><u>Corrective Measures for Disk Read Failure Windows</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/crafty-counterfeits-how-to-find-fake-engagements/"><u>Crafty Counterfeits  How to Find Fake Engagements</u></a></li>
<li><a href="https://win11.techidaily.com/decreasing-resource-consumption-handling-unrealcefsubprocess-in-windows/"><u>Decreasing Resource Consumption: Handling UnrealCEFSubprocess in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/disabling-personalized-game-recommendations-on-w11/"><u>Disabling Personalized Game Recommendations on W11</u></a></li>
<li><a href="https://fox-that.techidaily.com/effective-strategies-to-overcome-the-black-screen-of-death-on-iphones/"><u>Effective Strategies To Overcome the 'Black Screen of Death' On iPhones</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-taskmanager-stays-top-focused/"><u>Ensuring TaskManager Stays Top-Focused</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/here-are-some-of-the-best-pokemon-discord-servers-to-join-on-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>Here are Some of the Best Pokemon Discord Servers to Join On Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-yellowed-lcd-on-computer-screens/"><u>How to Fix Yellowed LCD on Computer Screens</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-the-taskbar-for-tablets-on-windows-11/"><u>How to Get the Taskbar for Tablets on Windows 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/how-to-record-iptv-screen/"><u>How to Record IPTV Screen</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rectify-the-outlook-failed-error-in-windows/"><u>How to Rectify the 'Outlook Failed' Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-safely-and-quickly-upgrade-your-surface-computers-software/"><u>How to Safely and Quickly Upgrade Your Surface Computers' Software</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-best-gpus-for-ultra-hd-video-production/"><u>In 2024, Best GPUs for Ultra HD Video Production</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-motorola-moto-g-5g-2023-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos From Motorola Moto G 5G (2023) to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-resolving-disabled-state-of-obs-fullscreen/"><u>In 2024, Resolving Disabled State of OBS Fullscreen</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-9-motorola-g24-power-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>In 2024, Top 9 Motorola G24 Power Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-11-issues-with-5ghz-wireless-networks/"><u>Navigating Windows 11 Issues with 5GHz Wireless Networks</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-unlock-free-vocal-manipulation-expertise-with-in-depth-guide-to-voice-editing-via-filmora-for-2024/"><u>New Unlock Free Vocal Manipulation Expertise with In-Depth Guide to Voice Editing via Filmora for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-wi-fi-prompt-shortcomings-completing-missing-steps-in-windows/"><u>Overcoming Wi-Fi Prompt Shortcomings: Completing Missing Steps in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/pro-win-efficiency-selecting-the-best-apps-for-window-11-users/"><u>Pro-Win Efficiency: Selecting the Best Apps for Window 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/proposing-a-new-vision-for-windows-11s-taskbar-functionality/"><u>Proposing a New Vision for Windows 11'S Taskbar Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/quick-solutions-for-common-cc-problems-on-win11/"><u>Quick Solutions for Common CC Problems on Win11</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/quickly-upgrade-3000-gfx-drivers-in-win10/"><u>Quickly Upgrade 3000 GFX Drivers in Win10</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-the-basics-of-windows-backup-configurations/"><u>Regaining the Basics of Windows Backup Configurations</u></a></li>
<li><a href="https://win11.techidaily.com/rejuvenating-windows-1011s-faulty-recycle-bin-error/"><u>Rejuvenating Windows 10/11'S Faulty Recycle Bin Error</u></a></li>
<li><a href="https://win11.techidaily.com/secrets-to-affordable-windows-10-a-comprehensible-guide/"><u>Secrets to Affordable Windows 10: A Comprehensible Guide</u></a></li>
<li><a href="https://win11.techidaily.com/self-sufficient-windows-patch-application/"><u>Self-Sufficient Windows Patch Application</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-healing-defective-windows-registry-entries/"><u>Step-by-Step: Healing Defective Windows Registry Entries</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/transformative-instagram-edits-professional-strategies/"><u>Transformative Instagram Edits  Professional Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-hidden-features-of-system-restore-in-win11/"><u>Unlocking the Hidden Features of System Restore in Win11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-realme-narzo-60-5g-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Realme Narzo 60 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-evolution-retro-revamped-to-the-era-of-98/"><u>Windows Evolution Retro-Revamped: To the Era of 98</u></a></li>
<li><a href="https://win11.techidaily.com/windows-guide-cpu-state-showcase-at-peak-levels/"><u>Windows Guide: CPU State Showcase at Peak Levels</u></a></li>
<li><a href="https://win11.techidaily.com/winning-at-warhammer-40k-boltgun-fix-pc-stutter-issues/"><u>Winning at Warhammer 40K Boltgun: Fix PC Stutter Issues</u></a></li>
</ul></div>
