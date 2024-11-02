---
title: How to Silence File Explorer's Default Tabs
date: 2024-10-25T17:18:55.517Z
updated: 2024-11-02T00:05:21.007Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Silence File Explorer's Default Tabs
excerpt: This Article Describes How to Silence File Explorer's Default Tabs
keywords: Close Explorer Tabs Quickly,Mute File Explorer Sounds,Hide Windows Files View,Disable Open Tab Alert,Quietify File Explorer,Silence Default Explorer,Minimize Pop-Up Tabs
thumbnail: https://thmb.techidaily.com/fe07e4a07925d03fd4feb686ae505e57245e98882a78ba5795218840cbfa3c62.JPG
---

## How to Silence File Explorer's Default Tabs

 Microsoft was hoping to launch the tabs feature in the File Explorer app for Windows 10\. But it scrapped the idea later on. However, with the Windows 11 22H2 update, users can now try out the tabs feature in File Explorer. The participants of the Windows Insider Program got early access to the feature and Microsoft could soon apply the tabs idea to Windows Notepad as well.

 But what if you want to turn the File Explorer Tabs feature off? An immediate idea would be to uninstall the update, but that is a temporary workaround. You can use ViVeTool to enable or disable the tabs feature or any other new feature of Windows 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is ViVeTool?

 ViVeTool is an open-source command line tool that can enable or disable Windows operating system features. Microsoft continuously works on many experimental features and does a lot of testing before rolling out a stable version of a feature. But if you are impatient, you can use ViVeTool to enable an otherwise hidden feature. It is free and the developers recently launched a GUI version of the tool as well.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118320/7443" target="_top" id="2118320">
  <img src="//a.impactradius-go.com/display-ad/7443-2118320" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118320/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Disable File Explorer Tabs In Windows 11

 You can disable the File Explorer Tabs by either using the ViVeTool or the ViVeTool GUI version. The latter is much simpler to use because you can search for a feature and activate or deactivate it in one click. But before doing that, download and install both of these tools on your system. Also,[create a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) for added precaution, in case the tool wrecks something on your Windows 11 computer.

**Download:** [ViVeTool](https://github.com/thebookisclosed/ViVe/releases)

**Download:** [ViVeTool GUI](https://github.com/PeterStrick/ViVeTool-GUI/releases)

### 1\. Disable File Explorer Tabs Using the ViVeTool

 Since it is a command line tool, you can access it from a terminal window. Here’s how to do it:

1. Press**Win + R** to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. Type**CMD** in the text input area and press**Ctrl + Shift + Enter** key to launch the command prompt with administrator privileges.
3. Type**cd Drive Name:\\path** . Here, you need to enter the exact location where you extracted the tool after downloading it. For example, we extracted it to a folder name Vive in C drive. So, our command is**cd C:\\Vive** .
4. Now, you will be in the directory where ViVeTool exists. Type**vivetool** and press the**Enter** key. You will see a bunch of parameters you can use with the tool.  
![Disable File Explorer Tabs Using the ViVeTool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool.jpg)
5. Type the following two commands, one by one in the CMD and press the**Enter** key.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075476/7443" target="_top" id="2075476">
  <img src="//a.impactradius-go.com/display-ad/7443-2075476" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075476/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

vivetool /disable /id:37634385  
vivetool /disable /id:36354489
6. You will see the “**Successfully set feature configuration(s)** ” if the command executes successfully.
7. Now,**restart** your system for the changes to take effect. The File Explorer Tabs feature will no longer be active on your system.

### 2\. Disable File Explorer Tabs Using the ViVeTool GUI version

 The GUI version of ViVeTool works similarly. You can manually enter the feature ID or use the search function to find a feature in the list. Repeat the following steps to disable File Explorer Tabs using the ViVeTool GUI.

1. Launch the ViVeTool GUI with admin privileges.
2. Click on the drop-down list and select the latest Windows build number. Wait for the tool to list all the feature IDs available for the Windows build.
3. Type**37634385** in the search bar. Select the highlighted feature and click on the**Perform Action** button.  
![Disable File Explorer Tabs Using the ViVeTool GUI version](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-file-explorer-tabs-using-the-vivetool-gui-version.jpg)
4. Select the**Deactivate Feature** option. Similarly, find the feature ID**36354489** and deactivate it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080347/19272" target="_top" id="2080347">
  <img src="//a.impactradius-go.com/display-ad/19272-2080347" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080347/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Now, close the ViVeTool GUI and**restart** your system.
6. Open the File Explorer and you won’t see the tabs feature anymore.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148775/18498" target="_top" id="2148775">
  <img src="//a.impactradius-go.com/display-ad/18498-2148775" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148775/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Disable Any Windows 11 Feature Using ViVeTool

 File Explorer tabs are more useful than you think. But if you use another File Explorer program or can make do without it, ViVeTool is a great utility to disable/enable it. Moreover, it is completely free, and you can even enable other experimental features of Windows 11.

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
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-identifying-optimal-frame-rate-in-slow-motion-film-production/"><u>[Updated] 2024 Approved Identifying Optimal Frame Rate in Slow Motion Film Production</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-cutting-edge-royalty-free-music-platforms-for-content-makers-for-2024/"><u>[Updated] Cutting-Edge Royalty-Free Music Platforms for Content Makers for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-elevate-your-youtube-presence-featuring-essential-channels-tutorial-for-2024/"><u>[Updated] Elevate Your Youtube Presence Featuring Essential Channels Tutorial for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-crossos-virtual-maestro-mixer/"><u>[Updated] In 2024, CrossOS Virtual Maestro Mixer</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-error-code-0x800704b3-on-windows-pcs/"><u>Addressing Error Code 0X800704B3 on Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-windows-credential-entry-attempts/"><u>Analyzing Windows Credential Entry Attempts</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-elevate-needed-errors-with-ease-in-windows-os/"><u>Bypassing 'Elevate Needed' Errors with Ease in Windows OS</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/capturecare-essential-guide-to-ig-photo-and-video-resize-for-2024/"><u>CaptureCare Essential Guide to IG Photo & Video Resize for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-fixing-error-code-0xc0000001-on-windows/"><u>Decoding and Fixing Error Code 0XC0000001 on Windows</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/dive-into-hardware-with-toms-electronic-evaluator-the-ultimate-resource/"><u>Dive Into Hardware with Tom’s Electronic Evaluator: The Ultimate Resource</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-audio-excellence-with-5-free-windows-apps/"><u>Elevate Audio Excellence with 5 Free Windows Apps</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/how-to-track-apple-iphone-7-location-without-installing-software-drfone-by-drfone-virtual-ios/"><u>How to Track Apple iPhone 7 Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Tecno Spark 10 4G? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-selecting-the-perfect-drone-stabilizer-a-guide/"><u>In 2024, Selecting the Perfect Drone Stabilizer A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-error-x0001-with-nvidia-experience-w11/"><u>Remedying Error X0001 with Nvidia Experience, W11</u></a></li>
<li><a href="https://win11.techidaily.com/repairing-non-functional-installation-of-ccleaner-on-windows-1011/"><u>Repairing Non-Functional Installation of CCleaner on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/1719380495510-unravel-and-solve-your-windows-update-puzzle-fast/"><u>Unravel and Solve Your Windows Update Puzzle Fast</u></a></li>
</ul></div>

