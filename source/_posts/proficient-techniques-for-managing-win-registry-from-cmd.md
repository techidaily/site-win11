---
title: Proficient Techniques for Managing Win Registry From CMD
date: 2024-09-11T09:35:54.738Z
updated: 2024-09-12T09:35:54.738Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Proficient Techniques for Managing Win Registry From CMD
excerpt: This Article Describes Proficient Techniques for Managing Win Registry From CMD
keywords: Win Reg Edit Commands,CMD Registry Hacks,Mastering Win Registry,Effective Win Reg Solutions,CMD Manage Windows Registry,Optimizing Win Reg via Command Line,Advanced Win Reg Tricks
thumbnail: https://thmb.techidaily.com/ce80644caee7b986767dc148a3626afb6dedcf8d303ed5814c688bdf2e6498bb.jpg
---

## Proficient Techniques for Managing Win Registry From CMD

 The Registry Editor is the first thing Windows users bring up when it comes to editing the Windows Registry. However, if you don't want to deal with a distracting GUI and too many clicks, there's a simpler-looking tool you can use: the Command Prompt.

 Although using it takes a little more know-how than the Registry Editor, our guide should be able to get you started.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135369/19272" target="_top" id="2135369">
  <img src="//a.impactradius-go.com/display-ad/19272-2135369" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135369/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to View the List of Registry Commands in Command Prompt

![the command to view all reg commands](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/the-command-to-view-all-reg-commands.jpg)

<!-- affiliate ads begin -->
<span id="1899850">
					<video width="486" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1899850.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14483-1899850">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1899850.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:304px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Felectronicx.pxf.io%2Fc%2F5597632%2F1899850%2F14483'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1899850/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 There aren't a lot of commands when it comes to editing the registry using Command Line. To view them all, [open Command Prompt as an administrator](https://www.makeuseof.com/windows-run-command-prompt-admin/) and run the below command in Command Prompt:

`reg /?`

 Command Prompt will then list the commands, such as **reg add**, **reg delete**, **reg copy**, and **reg save**.

![the list reg commands in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/the-list-reg-commands-in-command-prompt.jpg)

 If you want to see more information about them, just add the **/?** switch at the end of the command. For, example, if you want to find out what the **reg add** command does, you'd enter the below command:

`reg add /?`

 After you run it, you'll get all the details on what it does and how to use it.

![details of the reg add command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/details-of-the-reg-add-command-in-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135398/19272" target="_top" id="2135398">
  <img src="//a.impactradius-go.com/display-ad/19272-2135398" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135398/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134241/18498" target="_top" id="2134241">
  <img src="//a.impactradius-go.com/display-ad/18498-2134241" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134241/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135359/19272" target="_top" id="2135359">
  <img src="//a.impactradius-go.com/display-ad/19272-2135359" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135359/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Copy Registry Entries From One Key to Another

![transfering entries from one registry key to another in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/transfering-entries-from-one-registry-key-to-another-in-command-prompt.jpg)

 Sometimes, you might want to copy the values from one key to another in the registry. This is as easy as using the **reg copy** command while specifying the key you're copying them from and the one you're copying them to (keep in mind that both keys have to already exist before you run the command). Here's an example:

`reg copy HKLM\SOFTWARE\MyNewKey1 HKLM\SOFTWARE\MyNewKey2 /s`

 The **/s** switch at the end tells Command Prompt that it should copy every subkey and value in the first key (**MyNewKey1**) into the second one (**MyNewKey2**).

 Unfortunately, there's no way to copy specific values from one key to another. You'll have to use the Registry Editor for that.

<!-- affiliate ads begin -->
<span id="1444782">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1444782.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1444782">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1444782.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1444782%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1444782/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Import Registry Entries

![importing a registry file in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/importing-a-registry-file-in-command-prompt.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123466/16836" target="_top" id="2123466">
  <img src="//a.impactradius-go.com/display-ad/16836-2123466" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123466/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you have [created a Windows Registry file](https://www.makeuseof.com/windows-registry-file-guide/) or downloaded it elsewhere, you can import it into the registry using the **reg import** command. All you need to do is specify the path to the registry file and Command Prompt will do the rest. Here's an example:

`reg import C:\Users\CHIFUNDO\Desktop\MyRegFile.reg`

 Once you run that command, the contents of the reg file will be merged with the registry.

<!-- affiliate ads begin -->
<span id="1983474">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983474.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983474">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983474.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983474%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983474/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Export Registry Entries

![exproting a registry key in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/exproting-a-registry-key-in-command-prompt.jpg)

 You can export a key in the registry using the **reg export** command while specifying the path of the key you want to export and the file you want to create. This comes in handy when you need to back up certain keys and values to restore them elsewhere. Here's an example:

`reg export "HKLM\SOFTWARE\MyNewKey" D:\Reg_Backup\CHIFUNDO\Desktop\MyRegFile.reg`

 After you run the command successfully, check the location you entered, and you'll find the key and its associated subkeys and values have been exported successfully. In our case, it will create a file called **MyRegFile.reg** and save it on the desktop.

 You can also export a specific value using the **reg query** command and include the key, value, and path to the registry file you want to export the value to. Here's an example.

`reg query HKLM\SOFTWARE\MyNewKey /v MyValue > C:\Users\CHIFUNDO\Desktop\MyRegFile.reg`

 The resulting registry file will only contain the key and the specific value you exported.

## How to Save Registry Entries

![saving-a-key-to-a-registry-file-in-windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/saving-a-key-to-a-registry-file-in-windows.jpg)

 If you already have a registry file or any other text file, you can add keys to it using Command Prompt and the **reg save** command, which will overwrite the file with the new information. You just need to specify the name of the key and the registry file you want to save it to. Here's an example:

`reg save HKLM\SOFTWARE\MyNewKey2 C:\Users\CHIFUNDO\Desktop\MyRegFile.hiv /y`

 The **/y** switch at the end of the command above overwrites the file you're saving the key to without bringing up a prompt. When you open the file, you won't be able to read the contents since it will be saved as a binary file.

## How to Restore Registry Entries

![restoring-a-registry-key-in-command-prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/09/restoring-a-registry-key-in-command-prompt.jpg)

 So, let's say something has happened to the keys and values within the **MyNewKey2** we saved in the previous section, you can use the backup file you created to restore it. You'll need to use the **reg restore** command. Here's how to run it:

`reg restore HKLM\SOFTWARE\MyNewKey2 C:\Users\CHIFUNDO\Desktop\MyRegFile.hiv`

 Now the **MyNewKey2** key should return to the state it was in when you made the backup.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137393/7443" target="_top" id="2137393">
  <img src="//a.impactradius-go.com/display-ad/7443-2137393" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137393/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Tweak the Registry Without the Registry Editor

 While Command Prompt can't do everything the Registry Editor does, it does offer a quick way to edit the registry without opening the aforementioned tool. While using Command Prompt to tweak the registry is quite advanced, even if you're the average user, you should be able to get by if you follow along closely.

 Just don't forget to do what we mentioned earlier to avoid permanently ruining your Windows computer and create a system restore point first

 Although using it takes a little more know-how than the Registry Editor, our guide should be able to get you started.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-best-practices-to-avoid-missed-frames-during-video-capture/"><u>[New] In 2024, Best Practices to Avoid Missed Frames During Video Capture</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-elevate-your-instagram-feed-vertical-video-edits-in-fcpx-for-2024/"><u>[Updated] Elevate Your Instagram Feed Vertical Video Edits in FCPX for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-clearing-up-confusion-understanding-digital-rights-management-drm/"><u>[Updated] In 2024, Clearing Up Confusion Understanding Digital Rights Management (DRM)</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-your-speech-any-sound-discover-the-best-vocal-transformation-tools-on-android/"><u>[Updated] In 2024, Your Speech, Any Sound Discover the Best Vocal Transformation Tools on Android</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-seamless-conversion-excellence-with-these-top-8-tools/"><u>2024 Approved Seamless Conversion Excellence with These Top 8 Tools</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-skyrocket-your-marketing-game-on-reddit-proven-success-techniques/"><u>2024 Approved Skyrocket Your Marketing Game on Reddit Proven Success Techniques</u></a></li>
<li><a href="https://tech-revival.techidaily.com/browser-based-ai-management-mastering-the-use-of-agentgpt/"><u>Browser-Based AI Management: Mastering the Use of AgentGPT</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/comprehensive-tutorial-for-shifting-facial-gender-representation-online/"><u>Comprehensive Tutorial for Shifting Facial Gender Representation Online</u></a></li>
<li><a href="https://win11.techidaily.com/demystifying-mouseclicklock-usage-on-windows-pcs/"><u>Demystifying MouseClickLock Usage on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/disassembling-and-reassembling-windows-app-settings-for-success/"><u>Disassembling and Reassembling Windows App Settings for Success</u></a></li>
<li><a href="https://win11.techidaily.com/effective-booting-technique-startup-windows-unveil-notebooks/"><u>Effective Booting Technique: Startup Windows, Unveil Notebooks</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-error-132-wow-troubleshooting-guide/"><u>Eradicating Error #132: WoW Troubleshooting Guide</u></a></li>
<li><a href="https://win11.techidaily.com/escaping-the-shadows-reclaiming-light-from-darkness/"><u>Escaping the Shadows: Reclaiming Light From Darkness</u></a></li>
<li><a href="https://win11.techidaily.com/establish-prerequisites-before-vbox-installation/"><u>Establish Prerequisites Before VBox Installation</u></a></li>
<li><a href="https://win11.techidaily.com/expert-advice-on-avoiding-file-explorer-oversights-in-windows-11/"><u>Expert Advice on Avoiding File Explorer Oversights in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/fasten-the-toggling-of-microsofts-taskbar-integrated-chat/"><u>Fasten the Toggling of Microsoft’s Taskbar-Integrated Chat</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/finding-the-facebook-in-niche-driven-instagram-realms-for-2024/"><u>Finding the Face(book) in Niche-Driven Instagram Realms for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-failed-file-creation-on-win11s-camera-app/"><u>Fixing Failed File Creation on Win11's Camera App</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-server-stumbled-microsoft-store-error-in-windows-10-and-11/"><u>How to Fix the “Server Stumbled” Microsoft Store Error in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-open-the-driver-verifier-manager-in-windows-11/"><u>How to Open the Driver Verifier Manager in Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-itel-a70-to-samsung-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Itel A70 to Samsung Phone | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-realme-c55-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Pokémon Emerald Master Ball Cheat On Realme C55 | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-innovative-android-for-ultimate-3d-playback/"><u>In 2024, Innovative Android for Ultimate 3D Playback</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-six-steps-to-a-color-rich-photographic-world/"><u>In 2024, Six Steps to a Color-Rich Photographic World</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-insiders-guide-to-instagram-video-success/"><u>In 2024, The Insider’s Guide to Instagram Video Success</u></a></li>
<li><a href="https://win11.techidaily.com/insight-guide-reviewing-and-removing-windows-history/"><u>Insight Guide: Reviewing & Removing Windows History</u></a></li>
<li><a href="https://win11.techidaily.com/isolating-and-remedying-solo-sideheadphone-glitches-in-win/"><u>Isolating and Remedying Solo Sideheadphone Glitches in WIN</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-file-security-using-powertoys-lockmaster/"><u>Mastering File Security: Using PowerToys' Lockmaster</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-11-search-configurations-reset/"><u>Mastering Windows 11 Search Configurations Reset</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-pc-potential-through-processor-options/"><u>Maximizing PC Potential Through Processor Options</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-camera-error-a00f425d/"><u>Navigating Through Windows Camera Error A00F425D</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-subsystem-for-linux-solving-error-4294967295/"><u>Navigating Through Windows Subsystem for Linux: Solving Error 4294967295</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-windows-11-notes-for-universal-accessibility/"><u>Optimize Windows 11 Notes for Universal Accessibility</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-high-usage-chatgpt-alerts-on-pc/"><u>Overcoming High Usage ChatGPT Alerts on PC</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-blocked-by-admin-error-in-windows-setup/"><u>Overcoming the Blocked by Admin Error in Windows Setup</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-loadlibrary-error-87-in-windows/"><u>Resolving LoadLibrary Error 87 in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionizing-the-taskbar-in-windows-11-top-6-suggested-enhancements/"><u>Revolutionizing the Taskbar in Windows 11: Top 6 Suggested Enhancements</u></a></li>
<li><a href="https://win11.techidaily.com/shattered-scenery-9-ways-to-restore-win11-screen-snapshots/"><u>Shattered Scenery? 9 Ways to Restore Win11 Screen Snapshots</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-inactive-alerts-for-phone-link-app-on-windows-devices/"><u>Tackling Inactive Alerts for Phone Link App on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-addressing-launch-failed-lunar-client-issues/"><u>Techniques for Addressing “Launch Failed Lunar Client” Issues</u></a></li>
<li><a href="https://win11.techidaily.com/temporary-user-profiles-avoiding-login-interruptions/"><u>Temporary User Profiles: Avoiding Login Interruptions</u></a></li>
<li><a href="https://win11.techidaily.com/the-roadmap-for-utilizing-the-calculator-in-windows-11/"><u>The Roadmap for Utilizing the Calculator in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/triggers-for-launching-system-restore-in-windows-11-environment/"><u>Triggers for Launching System Restore in Windows 11 Environment</u></a></li>
<li><a href="https://win11.techidaily.com/turbocharge-your-watching-youtube-performance-in-chrome/"><u>Turbocharge Your Watching: YouTube Performance in Chrome</u></a></li>
<li><a href="https://win11.techidaily.com/unfreeze-opera-downloads-tips-for-windows-users/"><u>Unfreeze Opera Downloads: Tips for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-system-index-adjustments/"><u>Unlocking System Index Adjustments</u></a></li>
<li><a href="https://win11.techidaily.com/windows-component-tools-accessing-and-operating-guide/"><u>Windows Component Tools: Accessing & Operating Guide</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    