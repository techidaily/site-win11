---
title: Overcoming Low-End PC Issues in Window's Game Capture
date: 2024-09-10T01:20:06.474Z
updated: 2024-09-17T06:45:18.665Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming Low-End PC Issues in Window's Game Capture
excerpt: This Article Describes Overcoming Low-End PC Issues in Window's Game Capture
keywords: Gaming PC Troubleshoot,WinCapture Optimize,Fixing LOW Gamespeed,Enhance Low-End Gaming,Improve Capture Performance,Boost Window's Game Speed,Resolving Graphics Lag
thumbnail: https://thmb.techidaily.com/fe46f510d5bddf23ae454985f506805f0ef965f8513d0fdf45dc77d6a53d075d.jpg
---

## Overcoming Low-End PC Issues in Window's Game Capture

 Many users utilize the Xbox Game Bar app pre-installed with Windows for recording game clips. However, some users can’t record anything with the Game Bar because of an error that says, “sorry, your PC doesn't meet the hardware requirements for captures.” That error message can appear within Settings or when users select to record.

 The error message highlights a PC doesn’t meet system requirements for Game Bar recording. Yet, this error often arises for users who’ve utilized Game Bar’s recording on their PCs before. This is how you can fix the “PC doesn't meet the hardware requirements for captures” error in Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Enable Game DVR With Game DVR Config

 Game DVR Config is third-party software with which some users have resolved the “PC doesn't meet the hardware requirements for captures” error. That software includes settings users can select to enable Game DVR along with audio and microphone capture.

 Here is how you can enable Game DVR with that software:

1. Open the [Game DVR Config](https://github.com/FunkyFr3sh/GameDVR%5FConfig/releases) page.
2. Click the **GameDVR\_Config.exe** download link.
3. Bring up Windows Explorer and the Downloads folder or other directory containing the Game DVR file.
4. Double-click the **GameDVR\_Config** file.
5. Select the **Enable Game DVR (Win+G)** checkbox.  
![The Game DVR Config software](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/game-dvr-config.jpg)
6. Click the **Force software MFT** checkbox to select that setting.
7. Exit Game DVR Config and [open Task Manager](https://www.makeuseof.com/ways-to-open-task-manager-windows-10/).
8. Look for the Broadcast DVR server on the **Processes** tab. Right-click Broadcast DVR Server and select **End task** if you can find that process.

## Edit the Control Registry Key

 Editing the Control registry key is a fix that’s worked for some users. Try editing that key like this:

1. To activate Run, simultaneously press **Win** \+ **R**.
2. Type **regedit** within the Run command box and press the **Enter** key.
3. Clear the text in the address bar and input this registry key location there:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control`
4. If there isn’t a **PortableOperatingSystem** DWORD already, right-click on the **Control** key and select **New** and **DWORD**. Input **PortableOperatingSystem** within the new key’s text box.  
![The New and Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/new-key-options.jpg)
5. Double-click on the **PortableOperatingSystem** DWORD in the Control key.
6. Delete the **0** number and input **1** within the **Value data** box.  
![The Edit DWORD window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window.jpg)
7. Set the value by clicking **OK** inside the Edit DWORD window.

8. Then close out of the Registry Editor app and restart Windows.

## Update Your Graphics Adapter’s Driver

 An outdated or faulty graphics driver might be causing this recording issue on your PC. Try installing the latest graphics driver for your GPU if you haven’t updated it in a while (or ever). This guide tells you [how to update a PC’s graphics driver in Windows](http://www.makeuseof.com/update-graphics-drivers-in-windows-10/).

![The NVIDIA graphics driver download page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/nvidia-driver-download.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134491/18498" target="_top" id="2134491">
  <img src="//a.impactradius-go.com/display-ad/18498-2134491" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134491/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Enable the Windows Game Recording and Broadcasting Policy

 Group Policy Editor includes a Game Recording and Broadcasting policy that prevents recording when disabled. So, Windows Pro and Enterprise users must make sure that the Game Recording and Broadcasting policy is set to enabled. Do note that Windows Home doesn’t include the Group Policy Editor.

 Here is how you can enable that policy:

1. [Open Local Group Policy Editor](https://www.makeuseof.com/tag/open-local-group-policy-editor-windows/) and double-click **Computer Configuration** when it appears.
2. Double-click **Administrative Templates** \> **Windows Components**.
3. Select **Windows Game Recording and Broadcasting** in Group Policy’s sidebar.
4. Then double-click on the **Enables or disables Windows Game Recording and Broadcasting** policy.  
![The Group Policy Editor window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/group-policy-editor.jpg)
5. Click **Enabled** if that policy is disabled.

6. Select **Apply** to enable the recording policy and **OK** to close the window.  
![The Enables or disables Windows Game Recording and Broadcasting policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/windows-game-and-recording-policy-window.jpg)
7. Close Group Policy Editor, bring up your Start menu and select **Power** \> **Restart**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123726/7443" target="_top" id="2123726">
  <img src="//a.impactradius-go.com/display-ad/7443-2123726" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123726/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Erase Data in the GameDVR Registry Key

 Corrupted GameDVR entries within the registry can cause the “PC doesn't meet the hardware requirements for captures” error. You can fix that by deleting DWORDs and strings in the GameDVR registry key, which will automatically regenerate. However, we still recommend users back up the registry before applying this potential solution.

 You can erase data from the GameDVR registry key as follows:

1. Open Registry Editor with Run, as covered in the first couple of steps of resolution two.
2. Go to this GameDVR registry key location:  
`HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\GameDVR`
3. Select all DWORDs and strings within the GameDVR key by holding the **Ctrl** key and clicking on them.
4. Then right-click and select **Delete** \> **Yes**.  
![the-delete-option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/the-delete-option.jpg)
5. Click the Start menu’s Power button and select **Restart**.

## Get Recording Again With the Xbox Game Bar

 The potential solutions covered here are widely confirmed to resolve the “PC doesn't meet the hardware requirements for captures” by users who’ve needed to fix that issue. So, it’s most likely applying the potential fixes above will resolve that Game Bar recording issue on your Windows laptop or desktop. Then you can record video while gaming with the Game Bar’s recording feature again.

 The error message highlights a PC doesn’t meet system requirements for Game Bar recording. Yet, this error often arises for users who’ve utilized Game Bar’s recording on their PCs before. This is how you can fix the “PC doesn't meet the hardware requirements for captures” error in Windows 10 and 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-webster.techidaily.com/024-approved-football-film-breakdown-premier-insights-on-youtube/"><u>[New] 2024 Approved Football Film Breakdown Premier Insights on YouTube</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-perfecting-hp-screen-capture-top-4-methods-unveiled-for-2024/"><u>[Updated] Perfecting HP Screen Capture Top 4 Methods Unveiled for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/aviyoutube/"><u>AVI形式への無料YouTubeビデオ変換</u></a></li>
<li><a href="https://games-able.techidaily.com/battle-of-the-chips-winning-gamers-cpu/"><u>Battle of the Chips: Winning Gamer's CPU?</u></a></li>
<li><a href="https://win11.techidaily.com/best-top-10-screen-capture-tools-on-windows-10-enhance-your-productivity/"><u>Best Top 10 Screen Capture Tools on Windows 10: Enhance Your Productivity</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-dvd-video-toolkit-effortless-conversion-from-dvd-to-apple-devices-and-cellphones/"><u>Comprehensive DVD Video Toolkit - Effortless Conversion From DVD to Apple Devices and Cellphones</u></a></li>
<li><a href="https://win11.techidaily.com/convert-your-ape-audio-files-free-of-charge-simple-and-effective-techniques/"><u>Convert Your APE Audio Files Free of Charge: Simple and Effective Techniques</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-19-critical-examples-of-the-metaverse-unveiled/"><u>In 2024, 19 Critical Examples of the Metaverse Unveiled</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-stealth-instagram-story-viewing-guide-for-desktops-android-and-ios/"><u>In 2024, Stealth Instagram Story Viewing Guide for Desktops, Android & iOS</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-most-useful-tips-for-pokemon-go-ultra-league-on-honor-x9a-drfone-by-drfone-virtual-android/"><u>In 2024, The Most Useful Tips for Pokemon Go Ultra League On Honor X9a | Dr.fone</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/moving-on-from-smart-displays-heres-how-to-find-alternatives-to-the-echo-dot-and-clock/"><u>Moving On From Smart Displays? Here's How to Find Alternatives to the Echo Dot and Clock</u></a></li>
<li><a href="https://article-files.techidaily.com/precision-flight-the-new-era-with-yuneec-drone-review/"><u>Precision Flight The New Era with Yuneec Drone Review</u></a></li>
<li><a href="https://techidaily.com/the-way-to-convert-mts-for-xiaomi-redmi-k70-pro-by-aiseesoft-video-converter-play-mts-on-android/"><u>The way to convert MTS for Xiaomi Redmi K70 Pro</u></a></li>
</ul></div>

