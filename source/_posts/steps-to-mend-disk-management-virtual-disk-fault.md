---
title: Steps to Mend Disk Management Virtual Disk Fault
date: 2024-09-09T18:09:10.500Z
updated: 2024-09-17T01:23:06.352Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Steps to Mend Disk Management Virtual Disk Fault
excerpt: This Article Describes Steps to Mend Disk Management Virtual Disk Fault
keywords: Fix Disk Errors,Manage VDisk Problems,Resolve Disk Issues,Repair Disk Faults,Mend Virtual Disks,Stop Disk Malfunctions,Correct Disk Management
thumbnail: https://thmb.techidaily.com/dba89d459ade8c7de3368900b426d88c278b90eb374e6b587ae53e82dd50d862.jpg
---

## Steps to Mend Disk Management Virtual Disk Fault

 Disk Management is a Windows utility with which users can partition and rename drives. However, some users have reported this Windows error message pops up when they try to access Disk Management: “Disk Management could not start Virtual Disk Service (VDS).” A variation of that error message also says, “Unable to connect to Virtual Disk Service.”

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Disconnect External Drives From Your PC

 First, try disconnecting all non-essential USB devices from your PC. Make sure there aren’t any external drives, USB sticks, mobile phones, or card readers connected to your PC. Then try [opening the Disk Management utility](https://www.makeuseof.com/ways-open-disk-management-windows-10/) again.

## 2\. Run System File and Image Repair Scans

 System file corruption could feasibly cause the Disk Management Virtual Disk Service error. So, check the integrity of system files on your PC with the Windows System File Checker command-line tool. That utility will also usually repair corrupted system files detected. This [how to run the System File Checker](https://www.makeuseof.com/system-file-checker-sfc-windows/) guide includes instructions for utilizing that tool.

![The System File Checker command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/sfc-scannow-command.jpg)

 If SFC detects corrupted system files but can’t repair them, you may need to run a Deployment Image Service Management scan. That’s a tool for fixing issues with the Windows system image. You can run that utility by executing this Deployment Image command within the Command Prompt:

`DISM /Online /Cleanup-Image /RestoreHealth`

## 3\. Enable and Run the Virtual Disk Service

 A disabled Virtual Disk service is a common cause of the Disk Management VDS error. Disk Management can’t connect to VDS when the Virtual Disk service is disabled. So, try enabling and running the Virtual Disk service like this:

1. To access Run, press **Win + R**.
2. Enter **services.msc** inside the Run command dialog and press **Return**.
3. Scroll down and double-click on **Virtual Disk** within the Services window.  
![The Services window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/services-window.jpg)
4. Select the **Automatic** setting on the **Startup type** menu.  
![The Startup type drop-down menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/startup-type-drop-down-menu.jpg)
5. Press **Start** within the Virtual Disk Properties window.

1. Select the window’s **Log on** tab.
2. Next, click the **Allow service to interact with desktop** checkbox to select that option.  
![The Log On tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/log-on-tab.jpg)
3. Click **Apply** to save your new Virtual Disk service settings.
4. Select the Virtual Disk Properties window’s **OK** option.
5. If you encounter the Disk Management VDS error within a remote connection environment, repeat the above steps to check the Virtual Disk service is enabled on both the local and remote PCs.

## 4\. Allow Remote Volume Management Through Windows Defender Firewall

 Windows Defender Firewall can cause the Disk Management VDS error by blocking that utility from connecting with Virtual Disk. So, make sure Remote Volume Management is allowed through that firewall on both local and remote PCs. Our [guide to allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) includes instructions for applying this resolution.

![The allowed apps firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/firewall-options.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139121/17108" target="_top" id="2139121">
  <img src="//a.impactradius-go.com/display-ad/17108-2139121" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139121/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Turn Off Third-Party Security Software

 If your PC includes a third-party security (antivirus) app, that software could be blocking Disk Management from establishing a VDS connection. Remember that many third-party security apps also incorporate firewalls along with antivirus components. So, try temporarily disabling both the firewall and antivirus module within your third-party security software.

 To disable the firewall part, look for a turn-off firewall option within the settings tab of your antivirus software. You can usually turn off antivirus shields by right-clicking on security apps’ system tray icons and selecting disable options on their context menus. Select to turn off the antivirus shield for about an hour if you can, and try accessing Disk Management again to see if the issue persists.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115924/19272" target="_top" id="2115924">
  <img src="//a.impactradius-go.com/display-ad/19272-2115924" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115924/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Manage Your Drives With Disk Management Again

 The potential solutions in this guide aren’t totally guaranteed, but they’re the most likely ways to fix the Disk Management VDS error on a Windows PC. So, maybe one will get the Disk Management VDS issue sorted on your PC. Then you can manage and partition your drives with Disk Management again.

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/ed-create-magic-download-premium-soundscapes-now/"><u>[Updated] Create Magic Download Premium Soundscapes Now!</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-perfecting-skype-calls-dial-down-distractions-for-2024/"><u>[Updated] Perfecting Skype Calls Dial Down Distractions for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-your-guide-to-the-premier-10-youtube-news-channels/"><u>[Updated] Your Guide to the Premier 10 YouTube News Channels</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-pro-level-strategies-for-mass-downloading-tiktok-content/"><u>2024 Approved Pro-Level Strategies for Mass Downloading TikTok Content</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-accuracy-and-efficiency-of-windowed-discord-search/"><u>Enhancing Accuracy and Efficiency of Windowed Discord Search</u></a></li>
<li><a href="https://win11.techidaily.com/enigmatic-toolbars-windows-11s-invisible-commands/"><u>Enigmatic Toolbars: Windows 11’S Invisible Commands</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unblock-error-0x80070091-empty-folder-issue-on-windows-11-and-11/"><u>How to Unblock Error #0X80070091 Empty Folder Issue on Windows 11 & 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-scrutinizing-the-significance-of-high-dynamic-range-hdr/"><u>In 2024, Scrutinizing the Significance of High Dynamic Range HDR</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/premium-cameras-to-capture-the-spirit-of-live-music-in-hd/"><u>Premium Cameras to Capture the Spirit of Live Music in HD</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-error-code-0xc00ce556-a-guide/"><u>Resolving Windows' Error Code 0xC00CE556: A Guide</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-search-game-with-these-critical-windows-11-tricks/"><u>Transform Your Search Game with These Critical Windows 11 Tricks</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-8-best-rain-sound-effect-resources-to-download-for-2024/"><u>Updated 8 Best Rain Sound Effect Resources to Download for 2024</u></a></li>
</ul></div>

