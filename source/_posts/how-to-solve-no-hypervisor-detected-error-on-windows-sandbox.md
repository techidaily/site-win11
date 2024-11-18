---
title: How to Solve No Hypervisor Detected Error on Windows Sandbox
date: 2024-11-14T19:24:33.611Z
updated: 2024-11-18T01:49:04.905Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Solve No Hypervisor Detected Error on Windows Sandbox
excerpt: This Article Describes How to Solve No Hypervisor Detected Error on Windows Sandbox
keywords: Windows SANDBOX Troubleshooting Guide,Resolving Hypervisor Missing Error,Fixing Hypervisor Not Found in WS,Solve No Hypervisor on Windows Sandbox,Windows Sandbox Hypervisor Fix,Addressing Hypervisor Absence WS,Correcting Hypervisor WS Detect Issue
thumbnail: https://thmb.techidaily.com/78d24648f206f65b94f12ac351c4b3ce727b02ece4c292665e0f6b95fb5f60be.jpg
---

## How to Solve No Hypervisor Detected Error on Windows Sandbox

 Windows Sandbox is a handy utility to test untrusted apps and files in a secure virtual environment. The setup process is pretty straightforward for Windows Sandbox. However, when you try to launch the app, you may encounter the "No Hypervisor was found code 0XC0351000" error.

 The error message indicates that Windows Sandbox was unable to detect Hypervisor. This can happen due to many reasons, including incorrectly configured virtual machine-related features in Windows Features.

 Follow the steps in the article below to troubleshoot this error on your Windows PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Check and Enable Virtualization Technology in BIOS

![virtualization status windows task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/virtualization-status-windows-task-manager.jpg)

 All the virtualization-based tools need hardware virtualization enabled in BIOS to work. If you haven’t configured your hardware virtualization, check if it is enabled in Task Manager. If not, you can manually enable it in BIOS to support virtualization tools.

To check the virtualization status:

1. Right-click on**Start** and open**Task Manager.**
2. In Task Manager, open the**Performance** tab.
3. Next, make sure the**CPU** tab is selected.
4. Locate the**Virtualization** section. If**Enabled** , skip to the next method.
5. If**Disabled** , follow the steps below to enable hardware virtualization on your computer.

 Now we'll cover how to enable Hardware Virtualization in BISO on an HP computer. The instructions to enable hardware virtualization may vary depending on your computer manufacturer. You can find specific instructions on your computer manufacturer's website, or check out[how to enter the BIOS in Windows 10/11](https://www.makeuseof.com/tag/enter-bios-computer/) .

1. Shut down your PC.
2. Press the**Power** button and then start pressing the**Esc** key to view the**Start menu** .
3. Press**F10** to enter**BIOS Setup.**  
![startup menu bios setup utility](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/startup-menu-bios-setup-utility.jpg)
4. In the**BIOS Setup Utility,** use the right-left arrow keys to locate and open the**Configuration** tab.
5. Next, use the down-up arrow keys to select**Virtualization Technology** or anything with similar terms.  
![enable hardware virtualization bios](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-hardware-virtualization-bios.jpg)
6. With the option highlighted, press**Enter** and select**Enabled** from the options. Now the Virtualization Technology status will show as**Enabled** .
7. Press**F10** again to save the changes and exit BIOS.

 Wait for your computer to restart. Open Task Manager to see the Virtualization status in the CPU tab. If it says "Enabled," try to open Windows Sandbox to see if it works without the error.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082530/7443" target="_top" id="2082530">
  <img src="//a.impactradius-go.com/display-ad/7443-2082530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082530/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Enable Virtual Machine Platform Features

 Windows Sandbox is available as an optional feature that you can install from the Windows Features dialog, and we've covered how to do this in our guide on[how to enable and set up Windows Sandbox in Windows 11](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/) . Similarly, you may need to enable a few additional optional features essential to run the virtualization tool successfully.

 The two optional features you need to enable are**Virtual Machine Platform** and**Windows Hypervisor Platform** . These tools enable platform support for virtual machines and provide the necessary API to run virtualization software on Windows.

To enable virtualization features:

1. Press**Win + I** to open**Settings** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**  
![turn windows features on off windows 11 control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-windows-featureson-off-windows-11-control-panel.jpg)
3. In the left pane, click on**Turn Windows features on or off.**  

![turn on virtual machine platform windows hypervisor platform](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-virtual-machine-platform-windows-hypervisor-platform.jpg)
4. In the**Windows Features** dialogue, scroll down and locate**Virtual Machine Platform** and**Windows Hypervisor Platform.**

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997643/19272" target="_top" id="1997643">
  <img src="//a.impactradius-go.com/display-ad/19272-1997643" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997643/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Select both options and click**OK** .
6. Windows will start installing the necessary files. So, wait for the process to complete. Once done, click on**Restart Now** to restart your system and apply the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130871/7443" target="_top" id="2130871">
  <img src="//a.impactradius-go.com/display-ad/7443-2130871" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130871/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Set Hypervisor to Run at System Startup

 Windows Sandbox may not work if Hypervisor fails to start during system startup. To fix this issue, you can modify your Boot Configuration Data (BCD) file to launch Hypervisor automatically at system startup.

To set Hypervisor to launch at system startup:

1. Press the**Win** key and type**cmd** . Then, right-click on**Command Prompt** and select**Run as administrator.**
2. In the Command Prompt window, type the following command and press Enter:  
`BCDEDIT /Set {current} hypervisorlaunchtype auto`
3. Wait for the success message and restart your PC.
4. After the restart, open Command Prompt as administrator and run the following command:  
`bcdedit`
5. Next, scroll down to the**Hypervisorlaunchtype** entry and make sure it is set to**Auto** .
6. Try to launch Windows Sandbox and check if the No Hypervisor was found error is resolved.

 Note that with the Hypervisor set to launch at startup, virtual machines running on third-party virtualization tools such as VMWare may not work correctly.

 To disable Hypervisor at startup, type the following command in the elevated Command Prompt:

`bcdedit /set hypervisorlaunchtype off`

Once done, restart your computer to apply the changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137380/7443" target="_top" id="2137380">
  <img src="//a.impactradius-go.com/display-ad/7443-2137380" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137380/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Set With Your Sandbox Again

 While only available on the Pro, Enterprise, and Education editions of the Windows 10 and 11 running systems, Sandbox is an excellent lightweight virtualization solution to test unsafe files and apps on your PC.

 However, if this virtualization option is unavailable, consider using a Windows Sandbox alternative such as Sandboxie-Plus. It is free to use and works on all the editions of Windows OS.

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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-ultimate-guide-ten-most-affordable-screen-capture-software/"><u>[New] 2024 Approved Ultimate Guide Ten Most Affordable Screen Capture Software</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-a-stepwise-approach-to-designing-powerful-edu-vids-on-social-media/"><u>[New] In 2024, A Stepwise Approach to Designing Powerful Edu-Vids on Social Media</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-monetize-like-a-pro-how-to-use-youtube-studio-on-any-device/"><u>[New] In 2024, Monetize Like a Pro How to Use Youtube Studio on Any Device</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-sculpt-your-vision-editing-videos-using-story-remix-and-windows-photos/"><u>2024 Approved Sculpt Your Vision Editing Videos Using Story Remix and Windows Photos</u></a></li>
<li><a href="https://win11.techidaily.com/correcting-loadlibrary-failure-error-87/"><u>Correcting LoadLibrary Failure Error 87</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-regain-full-audio-functionality-on-windows-voice-and-music-only-speaker/"><u>How to Regain Full Audio Functionality on Windows: Voice & Music Only Speaker</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-broken-video-files-of-oppo-on-mac-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair Broken video files of Oppo on Mac?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-xiaomi-mix-fold-3-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Xiaomi Mix Fold 3 | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-nokia-105-classic-drfone-by-drfone-virtual-android/"><u>How to use Snapchat Location Spoofer to Protect Your Privacy On Nokia 105 Classic? | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/how-to-use-the-chatgpt-widget-on-android/"><u>How to Use the ChatGPT Widget on Android</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-incorrect-system-token-usage-errors/"><u>Resolving “Incorrect System Token Usage” Errors</u></a></li>
<li><a href="https://fox-that.techidaily.com/revive-your-iphone-top-7-methods-to-unstick-from-apple-boot-screen/"><u>Revive Your iPhone: Top 7 Methods to Unstick From Apple Boot Screen</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-integration-using-ios-calendar-in-windows-1011/"><u>Seamless Integration: Using iOS Calendar in Windows 10/11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/sony-vaio-driver-setup-and-download-for-windows-systems-step-by-step-tutorial/"><u>Sony VAIO Driver Setup and Download for Windows Systems - Step-by-Step Tutorial</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-win-11s-extra-view-command-in-menu/"><u>Streamlining Win 11'S Extra View Command in Menu</u></a></li>
<li><a href="https://win11.techidaily.com/the-blueprint-for-rectifying-error-code-31-on-your-pcs-network/"><u>The Blueprint for Rectifying Error Code 31 on Your PC's Network</u></a></li>
<li><a href="https://win11.techidaily.com/the-essential-guide-to-a-clearer-taskbar-in-win11/"><u>The Essential Guide to a Clearer Taskbar in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-a-shining-windows-11-title-bar/"><u>Tips for a Shining Windows 11 Title Bar</u></a></li>
<li><a href="https://win11.techidaily.com/win11-definitive-definitions-made-simple/"><u>Win11 Definitive Definitions Made Simple</u></a></li>
</ul></div>

