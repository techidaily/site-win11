---
title: Temporarily Counteracting Windows 11 Security in 4 Ways
date: 2024-11-06T22:16:14.693Z
updated: 2024-11-07T16:31:41.214Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Temporarily Counteracting Windows 11 Security in 4 Ways
excerpt: This Article Describes Temporarily Counteracting Windows 11 Security in 4 Ways
keywords: Win11 Bypass,Secure Compromise,Bypass Windows Defender,Vulnerability Exploit,Security Hacking,Gain Admin Access,Patch Windows 11
thumbnail: https://thmb.techidaily.com/f852052f5f905f2c87144be9d0c46cf8e36314379ae4c5ac18b6baf95c96be49.jpg
---

## Temporarily Counteracting Windows 11 Security in 4 Ways

 Windows Security is the built-in security app for Windows 11\. You should always keep it enabled as it protects your computer from online and offline threats. However, you may come across situations where you might need to disable it.

 Whether you want to disable it for personal preference or install an app that's facing interference by it, here's how to temporarily disable Windows Security in Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Temporarily Disable Windows Security Using the Settings App

 The Settings app is the central hub of Windows OS, from where you can manage important system settings. You can use it to personalize your computer, change privacy settings, update Windows, and do much more. It's also one of the places to disable Windows Security on your computer. Here's how:

1. Press the**Win + I** hotkeys to open the**Settings** app.
2. Choose**Privacy & security** from the left sidebar.
3. Click the**Open Windows** **Security** button on the right pane.  
![Open Windows Security option in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/open-windows-security.jpg)
4. In the Windows Security app, choose the**Virus & threats protection** option from the left sidebar.
5. Click**Manage settings** under the Virus & threats protection section.
6. Disable the toggle under the**Real-time protection** option.  
![Disabling Real-time protection in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/real-time-protection.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2002018/7443" target="_top" id="2002018">
  <img src="//a.impactradius-go.com/display-ad/7443-2002018" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2002018/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Temporarily Disable Windows Security Using the Registry Editor

 Windows Registry is a massive database of important settings and software installed on your computer. You can access and edit that database using a built-in tool called the Registry Editor.

 The Registry Editor can also come in handy in temporarily disabling Windows Security. Here's how to do that:

1. Open the**Start Menu** by pressing the**Win** key.
2. In the search bar, type**Windows Security** and press Enter.
3. Select**Virus & threat protection** from the left sidebar.
4. Turn off the toggle under the**Tamper protection** option.  
![Disabling Tamper Protection in Windows Security](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/tamper-protection.jpg)
5. Click**Yes** to the UAC that crops up.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130869/7443" target="_top" id="2130869">
  <img src="//a.impactradius-go.com/display-ad/7443-2130869" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130869/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now it's time to open the Registry Editor. Check out[how to open the Registry Editor on Windows 11](https://www.makeuseof.com/windows-11-open-registry-editor/) for steps on how to do this.

1. When the Registry Editor opens, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows Defender`
2. Right-click on**Windows Defender** in the left sidebar and choose**Permissions.**  
![Permissions option in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/permissions.jpg)
3. Click the**Advanced** options.  

![Advanced option in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced.jpg)
4. Click**Change** next to the**Owner** option.
5. In the**Select User or Group window** , click the**Advanced** button.  
![Advanced option in the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/advanced-option.jpg)

1. Click the**Find Now** button and then select the admin account.  
![Find Now option in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/find-now.jpg)
2. Click**OK** \>**OK** to save the changes.
3. Check the **Replace all child object permission entries with inheritable permission entries from this object** box.  
![Replace all child object permission entries with inheritable permission entries from this object box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/replace-all-child-object-permission-entries-with-inheritable-permission-entries-from-this-object.jpg)
4. Click**Apply** \>**OK.**

5. Next, head towards the**Permission for Windows Defender** window, and check the box next to**Full control.**  
![Full control box in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/full-control-box.jpg)
6. Click**Apply** \>**OK.**
7. Right-click on the blank space in the right pane, and create three**DWORD (32-bit) Value** with the following names:  
`DisableAntiVirus  

DisableAntiSpyware  

ServiceStartStates`
8. Double-click on each value, type**1** in**Value data,** and click**OK.**

Restart your computer for the changes to take effect.

## 3\. Temporarily Disable Windows Security Using the Local Group Policy Editor

 Another quick way to temporarily turn off Windows Security is through the Local Group Policy Editor. Here's what you need to do:

1. Open the Run dialog box, type**gpedit.msc** , and click**OK.**
2. In the Local Group Policy Editor, navigate to**Computer Configuration** \>**Administrative Templates** \>**Windows Components** \>**Microsoft Defender Antivirus** .
3. Double-click on the**Turn off Microsoft Defender Antivirus** policy.  
![Microsoft Defender Antivirus policy in LGPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/microsoft-defender-antivirus.jpg)
4. Click**Enabled** .  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111968/7443" target="_top" id="2111968">
  <img src="//a.impactradius-go.com/display-ad/7443-2111968" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111968/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Enabled option in LGPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/enabled-option.jpg)
5. Click**Apply** \>**OK.**

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082539/7443" target="_top" id="2082539">
  <img src="//a.impactradius-go.com/display-ad/7443-2082539" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082539/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once your work is done, you can enable Windows Security by choosing**Disabled** for the Turn off Microsoft Defender Antivirus policy.

## 4\. Temporarily Disable Windows Security Using Autoruns

 Autoruns is a Windows utility using which you can turn off the service responsible for starting Windows Security at startup. Before you use Autoruns, disable Tamper Protection by following the steps in method 2.

 Follow the below instructions to disable Windows Security using Autoruns:

1. To begin with,[download Autoruns](https://download.sysinternals.com/files/Autoruns.zip) on your computer.
2. Extract the downloaded file on your computer.
3. Next, boot your computer in safe mode (see[how to boot in safe mode on Windows](https://www.makeuseof.com/windows-11-boot-safe-mode/) ) and then open the extracted Autoruns folder.
4. Double-click on the**Autoruns64** file and then choose**Run** from the prompt that crops up.  
![Run option for Autoruns](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/run-option.jpg)
5. Click**Agree** in the**Autoruns Licence Agreement window** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918703/19272" target="_top" id="1918703">
  <img src="//a.impactradius-go.com/display-ad/19272-1918703" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918703/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. In the Autoruns window, click**Options** and uncheck**Hide Windows Entries.**  
![Hide Microsoft Entries option in Autoruns](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/hide-microsoft-enteries.jpg)
7. Click**Services.**
8. Uncheck the**WinDefend** box and then close the Autoruns window.  
![Disabling WinDefend in Autoruns](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windefend.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134234/18498" target="_top" id="2134234">
  <img src="//a.impactradius-go.com/display-ad/18498-2134234" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134234/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now, to boot in normal mode, open the**System Configuration** window, select**Normal startup,** and then**OK.**

## Stop Windows Security for a Little While on Windows 11

 The new Window Security app ensures you don't have to install a dedicated antivirus program to safeguard your computer. However, the strict policy of Windows Security can sometimes block the installation of third-party apps on your computer. Fortunately, you can disable Windows Security by following the above methods.

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
<li><a href="https://fox-links.techidaily.com/new-in-2024-evaluating-on-demand-media-podcast-or-youtube/"><u>[New] In 2024, Evaluating On-Demand Media Podcast or YouTube?</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-mystery-of-off-facebook-activity-what-to-know-and-do/"><u>[New] The Mystery of Off-Facebook Activity What to Know & Do</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-shadowy-snapshots-skills-for-stunning-night-images/"><u>[Updated] 2024 Approved Shadowy Snapshots Skills for Stunning Night Images</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/best-youtube-title-generator-for-2024/"><u>Best YouTube Title Generator for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/break-through-boundaries-15plus-best-free-video-starters/"><u>Break Through Boundaries 15+ Best Free Video Starters</u></a></li>
<li><a href="https://win-cloud.techidaily.com/effiziente-methode-zur-vollsicherung-ihres-iphones-unter-verwendung-eines-windows-computers/"><u>Effiziente Methode Zur Vollsicherung Ihres iPhones Unter Verwendung Eines Windows-Computers</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-visibility-and-efficiency-using-a-90-degree-display-shift/"><u>Enhance Visibility & Efficiency Using a 90-Degree Display Shift</u></a></li>
<li><a href="https://win11.techidaily.com/expert-techniques-mastering-your-workflow-with-mspcm-on-w11/"><u>Expert Techniques: Mastering Your Workflow with MSPCM on W11</u></a></li>
<li><a href="https://win11.techidaily.com/getting-rid-of-windows-11s-official-store/"><u>Getting Rid of Windows 11'S Official Store</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-ultimate-guide-top-10-places-to-download-inspiring-slideshow-designs/"><u>In 2024, The Ultimate Guide Top 10 Places to Download Inspiring Slideshow Designs</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/professional-insights-microsoft-surface-pro-8-evaluation-by-tech-experts-at-zdnet/"><u>Professional Insights: Microsoft Surface Pro 8 Evaluation by Tech Experts at ZDNet</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-group-policies-a-proactive-compliance-strategy/"><u>Refreshing Group Policies: A Proactive Compliance Strategy</u></a></li>
<li><a href="https://win11.techidaily.com/retro-to-revitalized-atlasos-for-old-pcs/"><u>Retro to Revitalized: AtlasOS for Old PCs</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-alleviate-wlanextexes-power-drain/"><u>Steps to Alleviate WLANEXT.EXE's Power Drain</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-avoiding-random-keypress-responses/"><u>Strategies for Avoiding Random Keypress Responses</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-vivo-v29-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Vivo V29 Device</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-windows-to-dos-compilation/"><u>The Ultimate Windows To-Dos Compilation</u></a></li>
<li><a href="https://vp-tips.techidaily.com/transformer-un-fichier-asf-en-mpeg-gratuitement-sur-internet-guide-complet-avec-movavi/"><u>Transformer Un Fichier ASF en MPEG Gratuitement Sur Internet - Guide Complet Avec Movavi</u></a></li>
<li><a href="https://win11.techidaily.com/win11-designing-hotkeys-for-audio-level-management/"><u>Win11: Designing Hotkeys for Audio Level Management</u></a></li>
</ul></div>

