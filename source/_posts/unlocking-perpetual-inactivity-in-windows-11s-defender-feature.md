---
title: Unlocking Perpetual Inactivity in Windows 11'S Defender Feature
date: 2025-01-21T02:10:50.815Z
updated: 2025-01-24T21:10:39.321Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Unlocking Perpetual Inactivity in Windows 11'S Defender Feature
excerpt: This Article Describes Unlocking Perpetual Inactivity in Windows 11'S Defender Feature
keywords: Windows Defender Lockout,Fix Inactive PCs,Win11 Security Issue,Perpetual Freeze,Enhance OS Protection,Inactivity in Win11,Bypass Defender Block
thumbnail: https://thmb.techidaily.com/a8037b9cb425e19a9ec57f5feba58cc91bfb4e98ab568e20793fc881abc0b40e.jpg
---

## Unlocking Perpetual Inactivity in Windows 11'S Defender Feature

 Microsoft bundles an antivirus program with every copy of the Windows operating system. Microsoft Defender was released in 2006 and has since been integral to every new Windows operating system release. Surprisingly, it is good at identifying and isolating malware on your system and offering real-time protection.

 But have you ever tried disabling Microsoft Defender? Unless you install a third-party antivirus program, it continues to run and monitor your system. Even if you disable the real-time protection, it turns back on after some time. Don’t worry! We will discuss multiple methods to disable Microsoft Defender for good.

## Why Does Microsoft Make It Difficult to Disable Microsoft Defender?

 Microsoft Defender offers robust security against malware and has evolved over time. You can use it to keep your system safe from malware and do not need to spend on any third-party antivirus app. But Microsoft realizes that users can expose their system to attackers if they disable Microsoft Defender completely.

 So, as a fail-safe method, Microsoft Defender turns back on after some time, even if you disable it. In the older version of Windows, disabling real-time protection was enough, but now it takes a lot more to disable Microsoft Defender.

 But what if you want to install and use a third-party app that Microsoft Defender repeatedly flags as malicious? Or if you want to reduce the load on your system resources? Well, then you have to dive deep into Windows Security settings and disable real-time protection as well as other associated protection measures.

 This guide will teach you how to disable Microsoft Defender permanently. It will stay off until you undo the steps you perform in this guide. If you only want Microsoft Defender to turn off for a short amount of time, check out[how to turn off Microsoft Defender](https://www.makeuseof.com/how-to-turn-off-microsoft-defender-windows-11/) for a more temporary solution.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Disable Tamper Protection First

 Tamper Protection makes sure that no other apps can make changes to the Microsoft Defender settings on your computer. You don't need to[enable Tamper Protection](https://www.makeuseof.com/how-to-activate-tamper-protection-defender/) because it is active by default. If you want to completely disable Microsoft Defender (including real-time protection), you must disable Tamper Protection first. Here’s how to do it:

1. Press**Win + S** and type Windows Security. Click on the**Open** option to launch the app.
2. Click on the**Virus and threat protection** option on the home page.
3. Find the Virus and threat protection settings section and click on the**Manage settings** option.
4. Scroll down and click on the**Tamper Protection** toggle to disable it.  
![Disable Tamper Protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/Disable-Tamper-Protection-2.jpg)
5. Close the Windows Security app.

## How to Disable Microsoft Defender in Windows 11

 We have already disabled Tamper Protection, so it won't interfere when you disable Microsoft Defender using GPE, Registry Editor, or any third-party tool. Here are the following methods that work flawlessly to disable the inbuilt security app on Windows 11:

### 1\. Disable Microsoft Defender Using Group Policy Editor

 Group Policy Editor is an excellent tool using which you can customize Windows settings with ease. However, it is only reserved for Windows Pro and Enterprise users. Check out[how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) if you're using that version.

 Here’s how to disable Microsoft Defender using Group Policy Editor:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) . Type**gpedit.msc** in the text input area and press the Enter key.
2. Group Policy Editor will launch. Click on the**Computer Configuration** option on the home page.
3. Navigate to**Administrative Templates > Windows Components** .
4. Locate and click on the Microsoft Defender Antivirus option. Double-click on the**Turn-off Microsoft Defender Antivirus** policy to edit its settings.  
![Disable Windows Defender Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-defender-using-group-policy-editor.jpg)
5. Select the**Enabled** radio button and click on the**Apply** button.
6. Lastly, click on the**OK** button and close the Group Policy Editor. Restart your system and open Windows Security.

### 2\. Disable Microsoft Defender Using Registry Editor

 Windows 11 Home users cannot use the Group Policy Editor. But you can tweak the registry to disable Microsoft Defender on your system. However, before making any changes, please create a registry backup and create a system restore point. That way, you can always undo any changes you make to the registry.

Repeat the following steps to disable Microsoft Defender:

1. Press**Win + S** to open Windows Search and type**Regedit** . Click on the**Run as administrator** button.
2. In the Registry Editor windows, go to the address bar and paste the following path:  
Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Microsoft Defender
3. Right-click and select**New > DWORD (32-bit) Value** .
4. \`Click on the newly created DWORD (32-bit) Value and name it**DisableAntiSpyware** .
5. Double-click on the DisableAntiSpyware value and set the**Value Dat** a to**1** . Keep the**Base** as**Hexadecimal** .  
![Disable Windows Defender Using Group Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-defender-using-group-registry-editor.jpg)
6. Close the Registry Editor and restart your system to apply changes.
7. Launch Windows Security and visit the Virus and threat protection section. You will see a “ **No active antivirus provider. Your device is vulnerable.** ” message.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ITtcSWvS8bo?si=4M4BfMgaabrW6148" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Disable Microsoft Defender Using CMD

 You can even use the Command Prompt app to disable Microsoft Defender. All you need to do is paste a registry modification command, and it will keep Microsoft’s default antivirus solution out of the picture. Here’s how to do it:

1. Press**Win + R** to launch the Run command box. Type**cmd** in the text input area and press**Ctrl + Shift + Enter** key to launch Command Prompt with admin privileges.
2. Now, type the following command and press the enter key:  
reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Microsoft Defender" /v DisableAntiSpyware /t REG_DWORD /d 1 /f
3. You will see a “**The operation completed successfully.** ” message after the successful execution of the above command.  
![Disable Windows Defender Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-defender-using-cmd.jpg)
4. Type**exit** to close the Command Prompt window and restart your system.

### 4\. Disable Microsoft Defender Using Winaero Tweaker

 If you hate tweaking the registry or find running commands too complex, you can use a Windows customization program like Winaero Tweaker. It is a GUI application, so you will find it easier to search for various Windows settings and disable them in a few clicks.

Repeat the following steps:

1. Visit the[Winaero Tweaker download](https://winaero.com/download-winaero-tweaker/) page and download the installer file on your system.
2. Install Winaero Tweaker and right-click on the application and select the**Run as administrator** option.
3. Click on the search icon and type Defender. Click on the**Microsoft Defender \\ Disable Microsoft Defender** search result.  
![Disable Windows Defender Using Winaero Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-defender-using-winaero-tweaker.jpg)
4. Then, click on the**Disable Microsoft Defender** checkbox. Scroll down and click on the**Reboot now** button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eMEJvwMM0vk?si=EQF_jo_4u9v5iJ_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Wait for your computer to restart. Microsoft Defender will be inactive on your system.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 5\. Disable Microsoft Defender Using Ultimate Windows Tweaker

 Like Winaero Tweaker, the Ultimate Windows Tweaker is also a Windows customization app. You can easily enable and disable multiple Windows operating system settings and features which are otherwise very difficult to locate. Repeat the following steps:

1. Go to the[Ultimate Windows Tweaker download webpage](https://www.thewindowsclub.com/ultimate-windows-tweaker-4-windows-10) and download the tool.
2. Extract all its files into a separate folder. Then select the tool and run it with administrator privileges.
3. Click on the**Search For Tweaks** option and type defender. Then click on the**Go** button and select the**Disable Microsoft Defender** option from the list.
4. Select the checkbox next to the**Disable Microsoft Defender** option and click on the**Apply Tweaks** button. You will see a Windows popup that will inform you whether the tweak was successful or not.  
![Disable Windows Defender Using Ultimate Windows Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/disable-windows-defender-using-ultimate-windows-tweaker.jpg)
5. Finally, click on the**Close** button and restart your system.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Permanently Disable Microsoft Defender on Windows 11

 Microsoft Defender is a pain to disable on your system because of multiple fail-safe methods built into Windows Security. So, disable Tamper Protection and then process with a method to disable Microsoft Defender. However, do not leave your system open to malware infestation, and use a third-party antivirus if you don’t like Defender.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-snowy-serenity-top-pick-winter-backgrounds-for-videos/"><u>[Updated] 2024 Approved Snowy Serenity Top Pick Winter Backgrounds for Videos</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-the-complete-windows-11-audio-record-process-for-2024/"><u>[Updated] The Complete Windows 11 Audio Record Process for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/a-concise-guide-to-windows-11-user-grievances-and-gripes/"><u>A Concise Guide to Windows 11 User Grievances and Gripes</u></a></li>
<li><a href="https://win11.techidaily.com/a-practical-guide-to-accessing-the-windows-iscsi-initiator/"><u>A Practical Guide to Accessing the Windows iSCSI Initiator</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-and-starting-verifier-manager-in-win11-os/"><u>Accessing and Starting Verifier Manager in Win11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-invalid-token-usage-in-modern-windows-systems/"><u>Addressing Invalid Token Usage in Modern Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-missing-powershell-from-windows-command-prompt/"><u>Addressing Missing PowerShell From Windows Command Prompt</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-disk-fragmentation-issue/"><u>Addressing Windows Disk Fragmentation Issue</u></a></li>
<li><a href="https://win11.techidaily.com/altering-windows-standard-pdf-display/"><u>Altering Window's Standard PDF Display</u></a></li>
<li><a href="https://tech-revival.techidaily.com/are-questions-rising-about-openais-ability-to-oversee-chatgpt/"><u>Are Questions Rising About OpenAI's Ability to Oversee ChatGPT?</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-ease-of-use-with-mouse-settings-in-win11/"><u>Boosting Ease of Use with Mouse Settings in Win11</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ructing-inquiry-curtain-closers/"><u>Constructing Inquiry Curtain Closers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/dispatched-guide-to-deciphering-and-dismantling-error-code-a00f4289-on-win11/"><u>Dispatched Guide to Deciphering & Dismantling Error Code A00F4289 on Win11</u></a></li>
<li><a href="https://win-top.techidaily.com/free-online-swf-to-mp4-video-converter-easy-and-reliable-conversion-with-movavi/"><u>Free Online SWF to MP4 Video Converter - Easy & Reliable Conversion with Movavi</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Xiaomi Redmi Note 12T Pro? | Dr.fone</u></a></li>
<li><a href="https://facebook.techidaily.com/instafb-embraces-meta-drops-nfts-for-limited-testing-period/"><u>Insta/FB Embraces Meta Drops NFTs for Limited Testing Period</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/maximize-your-apple-watch-experience-with-the-new-watchos-n-update-explore-key-features-and-upgrades/"><u>Maximize Your Apple Watch Experience with the New WatchOS N Update - Explore Key Features and Upgrades!</u></a></li>
</ul></div>

