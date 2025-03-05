---
title: "Command Line: A Step-by-Step Guide to Win Registry Alteration"
date: 2025-02-27T21:35:38.504Z
updated: 2025-03-04T19:29:03.361Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Command Line: A Step-by-Step Guide to Win Registry Alteration"
excerpt: "This Article Describes Command Line: A Step-by-Step Guide to Win Registry Alteration"
keywords: CMD Line Basics,Steps for RegEdit,Editing Windows Registry,Win Registry Tips,Advanced Registry Changes,Command Guide for Reg,RegEdit Alteration Guide
thumbnail: https://thmb.techidaily.com/e5207beb7032dbe2a223f71bc8ac9ba7ae1e50509055968df3fdf501a1448078.jpg
---

## Command Line: A Step-by-Step Guide to Win Registry Alteration

 The Registry Editor is the first thing Windows users bring up when it comes to editing the Windows Registry. However, if you don't want to deal with a distracting GUI and too many clicks, there's a simpler-looking tool you can use: the Command Prompt.

 Although using it takes a little more know-how than the Registry Editor, our guide should be able to get you started.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

 If you have [created a Windows Registry file](https://www.makeuseof.com/windows-registry-file-guide/) or downloaded it elsewhere, you can import it into the registry using the **reg import** command. All you need to do is specify the path to the registry file and Command Prompt will do the rest. Here's an example:

`reg import C:\Users\CHIFUNDO\Desktop\MyRegFile.reg`

 Once you run that command, the contents of the reg file will be merged with the registry.

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
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-skys-best-pixels-face-off-dji-inspire-1-and-gopro-fusion-mini/"><u>[New] In 2024, Sky's Best Pixels Face-Off DJi Inspire 1 & GoPro Fusion Mini</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-unlocking-the-best-free-screen-recorders-on-windows-10/"><u>[Updated] 2024 Approved Unlocking the Best Free Screen Recorders on Windows 10</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-beginners-glossary-for-instagram-chat-rooms/"><u>[Updated] In 2024, Beginner's Glossary for Instagram Chat Rooms</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-enhancing-youtube-visibility-with-tubebuddy/"><u>[Updated] In 2024, Enhancing YouTube Visibility with TubeBuddy</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unlock-efficient-airdrop-transfers-fixes-for-all-apple-gadgets/"><u>[Updated] Unlock Efficient AirDrop Transfers - Fixes for All Apple Gadgets</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-unlock-fb-livestream-potential-with-recorded-content-know-how/"><u>2024 Approved Unlock FB Livestream Potential with Recorded Content Know-How</u></a></li>
<li><a href="https://win11.techidaily.com/effortless-blending-of-win-product-key-and-microsoft-account/"><u>Effortless Blending of WIN Product Key & MICROSOFT ACCOUNT</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-overcoming-frozen-state-of-essential-wsreset/"><u>Guide to Overcoming Frozen State of Essential WSReset</u></a></li>
<li><a href="https://extra-tips.techidaily.com/seamless-tweeting-expert-video-conversion-software/"><u>Seamless Tweeting Expert Video Conversion Software</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-fix-for-xbox-controller-compatibility-issues-on-windows-7-8-and-11/"><u>Step-by-Step Fix for Xbox Controller Compatibility Issues on Windows 7, 8, and 11</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-bypass-difficulty-in-installing-version-22h2-of-win11-updater/"><u>Techniques to Bypass Difficulty in Installing Version 22H2 of Win11 Updater</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-windows-top-security-programs-for-privacy-150-chars/"><u>Unveiling Window's Top Security Programs for Privacy (150 Chars)</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-dxgi-correction-for-removed-devices/"><u>Windows 11 DXGI Correction for Removed Devices</u></a></li>
</ul></div>

