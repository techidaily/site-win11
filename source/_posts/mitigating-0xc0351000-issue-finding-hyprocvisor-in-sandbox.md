---
title: "Mitigating 0xC0351000 Issue: Finding Hyprocvisor in Sandbox"
date: 2024-12-10T17:57:07.592Z
updated: 2024-12-12T21:52:52.089Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mitigating 0xC0351000 Issue: Finding Hyprocvisor in Sandbox"
excerpt: "This Article Describes Mitigating 0xC0351000 Issue: Finding Hyprocvisor in Sandbox"
keywords: Mitigate C0351000 Error,Hyprocvisor Detection,ZeroFlag Vulnerability,Sandbox Security,ProcVir Locator,HYPROC Fix Guide,Exploit Prevention
thumbnail: https://thmb.techidaily.com/8852f9f0dff99dd98034c53ca9e7b84a75b979ac3b7699086866b0998ff7b7cb.jpg
---

## Mitigating 0xC0351000 Issue: Finding Hyprocvisor in Sandbox

 Windows Sandbox is a handy utility to test untrusted apps and files in a secure virtual environment. The setup process is pretty straightforward for Windows Sandbox. However, when you try to launch the app, you may encounter the "No Hypervisor was found code 0XC0351000" error.

 The error message indicates that Windows Sandbox was unable to detect Hypervisor. This can happen due to many reasons, including incorrectly configured virtual machine-related features in Windows Features.

 Follow the steps in the article below to troubleshoot this error on your Windows PC.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Check and Enable Virtualization Technology in BIOS

![virtualization status windows task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/virtualization-status-windows-task-manager.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Enable Virtual Machine Platform Features

 Windows Sandbox is available as an optional feature that you can install from the Windows Features dialog, and we've covered how to do this in our guide on[how to enable and set up Windows Sandbox in Windows 11](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/) . Similarly, you may need to enable a few additional optional features essential to run the virtualization tool successfully.

 The two optional features you need to enable are**Virtual Machine Platform** and**Windows Hypervisor Platform** . These tools enable platform support for virtual machines and provide the necessary API to run virtualization software on Windows.

To enable virtualization features:

1. Press**Win + I** to open**Settings** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**  
![turn windows features on off windows 11 control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-windows-featureson-off-windows-11-control-panel.jpg)
3. In the left pane, click on**Turn Windows features on or off.**  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![turn on virtual machine platform windows hypervisor platform](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-virtual-machine-platform-windows-hypervisor-platform.jpg)
4. In the**Windows Features** dialogue, scroll down and locate**Virtual Machine Platform** and**Windows Hypervisor Platform.**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Select both options and click**OK** .
6. Windows will start installing the necessary files. So, wait for the process to complete. Once done, click on**Restart Now** to restart your system and apply the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-capture.techidaily.com/new-winning-strategies-the-best-5-methods-for-game-recording-in-windows-11/"><u>[New] Winning Strategies The Best 5 Methods for Game Recording in Windows 11</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-superior-ai-photo-cutting-master/"><u>2024 Approved Superior AI Photo Cutting Master</u></a></li>
<li><a href="https://win11.techidaily.com/controlling-user-authentication-w11-from-a-domain-perspective/"><u>Controlling User Authentication: W11 From a Domain Perspective</u></a></li>
<li><a href="https://sound-issues.techidaily.com/diy-fixes-for-google-meet-microphone-not-working-on-windows-operating-systems-11-and-10/"><u>DIY Fixes for Google Meet Microphone Not Working on Windows Operating Systems - 11 and 10</u></a></li>
<li><a href="https://win-answers.techidaily.com/eliminating-persistent-issues-with-thunder-tier-one-stability-improvements-for-pc-users/"><u>Eliminating Persistent Issues with Thunder TIER One - Stability Improvements for PC Users</u></a></li>
<li><a href="https://win11.techidaily.com/halt-windows-autolock-functionality-easily/"><u>Halt Windows Autolock Functionality Easily</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-data-from-iphone-xs-max-to-other-iphone-11-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From iPhone XS Max To Other iPhone 11 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-oppo-a79-5g-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Transfer Music from Oppo A79 5G to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-can-we-unlock-our-lava-yuva-2-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our Lava Yuva 2 Phone Screen?</u></a></li>
<li><a href="https://win11.techidaily.com/key-mousy-woes-awakening-windows-in-slumber-mode/"><u>Key-Mousy Woes: Awakening Windows in Slumber Mode</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/masterful-notetaking-strategies-using-gpt-technology/"><u>Masterful Notetaking Strategies Using GPT Technology</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-access-control-screen-windows-11-management/"><u>Mastering Access Control Screen (Windows 11) Management</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-productivity-filter-mastery-and-style-upgrade-in-windows-11s-task-manager/"><u>Maximizing Productivity: Filter Mastery & Style Upgrade in Windows 11'S Task Manager</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-local-sam-service-deactivated-message/"><u>Resolving 'Local SAM Service Deactivated' Message</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-approach-augmenting-virtual-memory-on-windows-11/"><u>Step-by-Step Approach: Augmenting Virtual Memory on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-audio-workflow-win-five-free-editors/"><u>Streamline Audio Workflow: Win Five Free Editors</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-visual-experience-with-in-built-color-tuning-win11/"><u>Streamline Visual Experience with In-Built Color Tuning (Win11)</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/tailor-your-own-memetic-masterpiece-now/"><u>Tailor Your Own Memetic Masterpiece Now</u></a></li>
<li><a href="https://win-tips.techidaily.com/uncovering-issues-detecting-absence-of-sound-card-in-system-playback-devices-expert-advice-from-yl-computers/"><u>Uncovering Issues: Detecting Absence of Sound Card in System Playback Devices – Expert Advice From YL Computers</u></a></li>
</ul></div>

