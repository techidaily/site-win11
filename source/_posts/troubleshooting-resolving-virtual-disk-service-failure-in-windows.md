---
title: "Troubleshooting: Resolving Virtual Disk Service Failure in Windows"
date: 2024-06-25T11:40:02.190Z
updated: 2024-06-26T11:40:02.190Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting: Resolving Virtual Disk Service Failure in Windows"
excerpt: "This Article Describes Troubleshooting: Resolving Virtual Disk Service Failure in Windows"
keywords: Fix Virtual Disk Errors,DBTSVDISK Win Trouble,Bypass VDisk Service Fails,Resolve DV-Service Crashes,Stop Windows VDisk Failures,Correcting VDisk Services,Overcome VDisk Windows Errors
thumbnail: https://thmb.techidaily.com/b7fdec82e5e2a50f89b07a18bb64e205705f93d7819f0fe370579d848f9daaea.jpg
---

## Troubleshooting: Resolving Virtual Disk Service Failure in Windows

 Disk Management is a Windows utility with which users can partition and rename drives. However, some users have reported this Windows error message pops up when they try to access Disk Management: “Disk Management could not start Virtual Disk Service (VDS).” A variation of that error message also says, “Unable to connect to Virtual Disk Service.”

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

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

## 5\. Turn Off Third-Party Security Software

 If your PC includes a third-party security (antivirus) app, that software could be blocking Disk Management from establishing a VDS connection. Remember that many third-party security apps also incorporate firewalls along with antivirus components. So, try temporarily disabling both the firewall and antivirus module within your third-party security software.

 To disable the firewall part, look for a turn-off firewall option within the settings tab of your antivirus software. You can usually turn off antivirus shields by right-clicking on security apps’ system tray icons and selecting disable options on their context menus. Select to turn off the antivirus shield for about an hour if you can, and try accessing Disk Management again to see if the issue persists.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

## Manage Your Drives With Disk Management Again

 The potential solutions in this guide aren’t totally guaranteed, but they’re the most likely ways to fix the Disk Management VDS error on a Windows PC. So, maybe one will get the Disk Management VDS issue sorted on your PC. Then you can manage and partition your drives with Disk Management again.

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/screen-notes-made-easy-winning-sticky-pad-solutions-for-pc/"><u>Screen Notes Made Easy: Winning Sticky Pad Solutions for PC</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steps-for-quickly-resolving-operation-requirement-errors/"><u>Troubleshooting Steps for Quickly Resolving Operation Requirement Errors</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-not-recognized-fix-for-windows-users/"><u>Overcoming Device Not Recognized: Fix for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/expertly-restoring-erased-data-in-a-microsoft-world/"><u>Expertly Restoring Erased Data in a Microsoft World</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-repeated-sign-in-alerts-team-collaboration-edition/"><u>Avoiding Repeated Sign-In Alerts: Team Collaboration Edition</u></a></li>
<li><a href="https://win11.techidaily.com/nine-no-go-areas-for-novice-windows-11-users/"><u>Nine No-Go Areas for Novice Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/bypass-tactics-for-repeated-usernamepassword-alerts/"><u>Bypass Tactics for Repeated Username/Password Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/1719218317457-gpt4all-windows-guide-to-free-on-premise-chatbots/"><u>GPT4All Windows Guide to Free, On-Premise ChatBots.</u></a></li>
<li><a href="https://win11.techidaily.com/is-obs-studio-unable-to-record-audio-on-windows-11-try-these-fixes/"><u>Is OBS Studio Unable to Record Audio on Windows 11? Try These Fixes</u></a></li>
<li><a href="https://discord-videos.techidaily.com/in-2024-exploring-innovative-ways-to-personalize-your-discord-status/"><u>In 2024, Exploring Innovative Ways to Personalize Your Discord Status</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-world-kitchen-popular-tiktok-food-trends/"><u>[Updated] 2024 Approved  World Kitchen  Popular TikTok Food Trends</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-unlocking-your-cameras-screen-recording-features/"><u>[Updated] 2024 Approved  Unlocking Your Camera's Screen Recording Features</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-honor-90-gt-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Honor 90 GT | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-add-a-digital-signature-block-to-word-2013-by-ldigisigner-sign-a-word-sign-a-word/"><u>How to add a digital signature block to Word 2013</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-nubia-red-magic-9-pro-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Nubia Red Magic 9 Pro FRP Android 10/11/12/13</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/conquering-camera-angst-the-ultimate-list-of-video-blogging-phobias/"><u>Conquering Camera Angst  The Ultimate List of Video Blogging Phobias</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-beat-weavers-treasury-high-res-dj-visual-samples/"><u>In 2024, The Beat Weaver's Treasury  High-Res DJ Visual Samples</u></a></li>
<li><a href="https://review-topics.techidaily.com/play-hevc-h265-on-galaxy-m54-5g-is-it-possible-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>Play HEVC H.265 on Galaxy M54 5G, is it possible?</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-revamping-youtube-images-adding-electric-neon-frames/"><u>2024 Approved  Revamping YouTube Images  Adding Electric Neon Frames</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>