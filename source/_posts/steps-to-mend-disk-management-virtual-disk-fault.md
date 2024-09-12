---
title: Steps to Mend Disk Management Virtual Disk Fault
date: 2024-09-11T09:42:35.938Z
updated: 2024-09-12T09:42:35.938Z
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135393/19272" target="_top" id="2135393">
  <img src="//a.impactradius-go.com/display-ad/19272-2135393" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135393/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If SFC detects corrupted system files but can’t repair them, you may need to run a Deployment Image Service Management scan. That’s a tool for fixing issues with the Windows system image. You can run that utility by executing this Deployment Image command within the Command Prompt:

`DISM /Online /Cleanup-Image /RestoreHealth`

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136545/16384" target="_top" id="2136545">
  <img src="//a.impactradius-go.com/display-ad/16384-2136545" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136545/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129739/7443" target="_top" id="2129739">
  <img src="//a.impactradius-go.com/display-ad/7443-2129739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129739/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Allow Remote Volume Management Through Windows Defender Firewall

 Windows Defender Firewall can cause the Disk Management VDS error by blocking that utility from connecting with Virtual Disk. So, make sure Remote Volume Management is allowed through that firewall on both local and remote PCs. Our [guide to allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) includes instructions for applying this resolution.

![The allowed apps firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/firewall-options.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135369/19272" target="_top" id="2135369">
  <img src="//a.impactradius-go.com/display-ad/19272-2135369" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135369/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Turn Off Third-Party Security Software

 If your PC includes a third-party security (antivirus) app, that software could be blocking Disk Management from establishing a VDS connection. Remember that many third-party security apps also incorporate firewalls along with antivirus components. So, try temporarily disabling both the firewall and antivirus module within your third-party security software.

 To disable the firewall part, look for a turn-off firewall option within the settings tab of your antivirus software. You can usually turn off antivirus shields by right-clicking on security apps’ system tray icons and selecting disable options on their context menus. Select to turn off the antivirus shield for about an hour if you can, and try accessing Disk Management again to see if the issue persists.

![Temporarily disable antivirus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/06/disable-antivirus.jpg)

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139563/4704" target="_top" id="2139563">
  <img src="//a.impactradius-go.com/display-ad/4704-2139563" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139563/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129738/7443" target="_top" id="2129738">
  <img src="//a.impactradius-go.com/display-ad/7443-2129738" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129738/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Manage Your Drives With Disk Management Again

 The potential solutions in this guide aren’t totally guaranteed, but they’re the most likely ways to fix the Disk Management VDS error on a Windows PC. So, maybe one will get the Disk Management VDS issue sorted on your PC. Then you can manage and partition your drives with Disk Management again.

 This error means users can’t access and utilize Disk Management. The issue more typically arises in remote connection environments. This is how you can fix the Disk Management Virtual Disk Service error in Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-http.techidaily.com/new-in-2024-exploring-the-upside-down-world-of-instagram-videos/"><u>[New] In 2024, Exploring the Upside-Down World of Instagram Videos</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-seamless-incorporation-of-virtual-boards-in-web-conferencing-mobiledesktop-methods/"><u>[New] In 2024, Seamless Incorporation of Virtual Boards in Web Conferencing Mobile/Desktop Methods</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-download-voice-log-inspect-for-2024/"><u>[Updated] Download Voice Log Inspect for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-expert-advice-for-capturing-evening-images/"><u>[Updated] In 2024, Expert Advice for Capturing Evening Images</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-simplifying-slide-sharing-using-your-webcam-effectively-for-2024/"><u>[Updated] Simplifying Slide Sharing Using Your Webcam Effectively for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/a-working-guide-for-pachirisu-pokemon-go-map-on-oppo-k11x-drfone-by-drfone-virtual-android/"><u>A Working Guide For Pachirisu Pokemon Go Map On Oppo K11x | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/compreran-disk-definitions-clarity-on-c-vs-d/"><u>Compreran Disk Definitions: Clarity on 'C' Vs 'D'</u></a></li>
<li><a href="https://win11.techidaily.com/do-your-windows-settings-reset-to-default-on-reboot-try-these-fixes/"><u>Do Your Windows Settings Reset to Default on Reboot? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-multitasking-through-90-degree-display-rotation/"><u>Efficient Multitasking Through 90-Degree Display Rotation</u></a></li>
<li><a href="https://win11.techidaily.com/eight-slips-new-users-shouldnt-fall-into-with-windows-11/"><u>Eight Slips New Users Shouldn't Fall Into With Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-problematic-code-0x00000001-a-guide-to-xbox-game-pass-fixes-on-windows-11/"><u>Eliminating Problematic Code 0X00000001: A Guide to Xbox Game Pass Fixes on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/empowering-typing-efficiency-with-filter-keys-settings/"><u>Empowering Typing Efficiency with Filter Keys Settings</u></a></li>
<li><a href="https://win11-tips.techidaily.com/end-stuck-operator-download-on-windows-heres-how/"><u>End Stuck Operator Download on Windows - Here's How</u></a></li>
<li><a href="https://tech-haven.techidaily.com/examining-the-safety-of-gpt-web-extensions/"><u>Examining the Safety of GPT Web Extensions</u></a></li>
<li><a href="https://win11.techidaily.com/explore-the-future-of-windows-through-vivetools-potential/"><u>Explore the Future of Windows Through ViVeTool's Potential</u></a></li>
<li><a href="https://win-blog.techidaily.com/far-cry-6-solutions-fixing-the-troublesome-black-screen-problem/"><u>Far Cry 6 Solutions: Fixing the Troublesome Black Screen Problem</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-black-ops-cold-war-bug-resolving-error-887a0005/"><u>Fixing Black Ops Cold War Bug: Resolving Error 887A0005</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-eliminate-windows-task-failure-error-0x8007000f/"><u>How to Eliminate Window's Task Failure Error 0X8007000f</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-install-windows-11-in-vmware-workstation-17-player/"><u>How to Install Windows 11 in VMware Workstation 17 Player</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-infinix-hot-30-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Infinix Hot 30 5G to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-top-15-augmented-reality-games-like-pokemon-go-to-play-on-vivo-y100i-power-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Top 15 Augmented Reality Games Like Pokémon GO To Play On Vivo Y100i Power 5G | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/infinite-gaming-space-10-ssds-hdds-for-ps5-for-2024/"><u>Infinite Gaming Space #10 SSDs, HDDs for PS5 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/key-driven-awakening-mouse-and-keyboards-role-on-windows-1011/"><u>Key-Driven Awakening: Mouse & Keyboard's Role on Windows 10/11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/mastering-image-transformation-with-effective-use-of-3d-lut-in-ps-for-2024/"><u>Mastering Image Transformation with Effective Use of 3D LUT in PS for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-fix-for-media-server-collapse/"><u>Mastering the Fix for Media Server Collapse</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-globally-advanced-mouse-techniques-in-powertoys/"><u>Navigating Globally: Advanced Mouse Techniques in PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-insufficient-access-during-app-removal-in-win-11/"><u>Navigating Insufficient Access During App Removal in Win 11</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-in-2024-final-cut-pro-essentials-crafting-a-compelling-video-slideshow/"><u>New In 2024, Final Cut Pro Essentials Crafting a Compelling Video Slideshow</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-updater-glitch-code-0x80073712/"><u>Quick Fixes for Updater Glitch: Code 0X80073712</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/secrets-to-flawless-game-recording-in-windows-11-for-2024/"><u>Secrets to Flawless Game Recording in Windows 11 for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/secure-windows-pc-changing-pin-now/"><u>Secure Windows PC: Changing PIN Now</u></a></li>
<li><a href="https://win11.techidaily.com/sharpen-sound-win-5-free-windows-editing-apps/"><u>Sharpen Sound: Win 5 Free Windows Editing Apps</u></a></li>
<li><a href="https://win11.techidaily.com/simplifying-your-win-11-menu-choices/"><u>Simplifying Your Win 11 Menu Choices</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-find-and-remove-empty-folders-with-confidence-in-windows/"><u>Techniques to Find & Remove Empty Folders with Confidence in Windows</u></a></li>
<li><a href="https://techtrends.techidaily.com/turn-your-laptop-into-a-second-screen-tips-and-tricks-for-seamless-dual-display-setup/"><u>Turn Your Laptop Into a Second Screen - Tips & Tricks for Seamless Dual-Display Setup</u></a></li>
<li><a href="https://win11.techidaily.com/unwrapping-the-mystery-of-0xc000003e-app-launch-failure/"><u>Unwrapping the Mystery of 0XC000003E App Launch Failure</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-best-ios-and-android-apps-you-can-use-to-create-animoji-and-memoji-videos/"><u>Updated Best iOS and Android Apps You Can Use to Create Animoji and Memoji Videos</u></a></li>
<li><a href="https://win11.techidaily.com/which-windows-11-services-are-safe-to-disable/"><u>Which Windows 11 Services Are Safe to Disable?</u></a></li>
<li><a href="https://win11.techidaily.com/win11-customization-keeping-the-look-unaltered/"><u>Win11 Customization: Keeping the Look Unaltered</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    