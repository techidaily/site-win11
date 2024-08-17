---
title: "Troubleshooting Techniques: Windows Sandbox Lacks Hyprocvisor"
date: 2024-08-15T23:59:10.377Z
updated: 2024-08-16T23:59:10.377Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Troubleshooting Techniques: Windows Sandbox Lacks Hyprocvisor"
excerpt: "This Article Describes Troubleshooting Techniques: Windows Sandbox Lacks Hyprocvisor"
keywords: Windows Sandbox Woes,Hyproc Manager Missing,Sandbox Troubleshoot,Zero-Vulnerability Test,Non-Hyproc Window Sys,Tech Issue Resolution,Vulnerability Free Workspace
thumbnail: https://thmb.techidaily.com/6631d02aad6297e4d6f700e032b5f1a6df7f0a4821dff69d11f95fe1acb0191f.jpg
---

## Troubleshooting Techniques: Windows Sandbox Lacks Hyprocvisor

 Windows Sandbox is a handy utility to test untrusted apps and files in a secure virtual environment. The setup process is pretty straightforward for Windows Sandbox. However, when you try to launch the app, you may encounter the "No Hypervisor was found code 0XC0351000" error.

 The error message indicates that Windows Sandbox was unable to detect Hypervisor. This can happen due to many reasons, including incorrectly configured virtual machine-related features in Windows Features.

 Follow the steps in the article below to troubleshoot this error on your Windows PC.

## 1\. Check and Enable Virtualization Technology in BIOS

![virtualization status windows task manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/virtualization-status-windows-task-manager.jpg)

 All the virtualization-based tools need hardware virtualization enabled in BIOS to work. If you haven’t configured your hardware virtualization, check if it is enabled in Task Manager. If not, you can manually enable it in BIOS to support virtualization tools.

To check the virtualization status:

1. Right-click on**Start** and open**Task Manager.**
2. In Task Manager, open the**Performance** tab.
3. Next, make sure the**CPU** tab is selected.
4. Locate the**Virtualization** section. If**Enabled** , skip to the next method.
5. If**Disabled** , follow the steps below to enable hardware virtualization on your computer.

 Now we'll cover how to enable Hardware Virtualization in BISO on an HP computer. The instructions to enable hardware virtualization may vary depending on your computer manufacturer. You can find specific instructions on your computer manufacturer's website, or check out [how to enter the BIOS in Windows 10/11](https://www.makeuseof.com/tag/enter-bios-computer/) .

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## 2\. Enable Virtual Machine Platform Features

 Windows Sandbox is available as an optional feature that you can install from the Windows Features dialog, and we've covered how to do this in our guide on [how to enable and set up Windows Sandbox in Windows 11](https://www.makeuseof.com/enable-set-up-windows-sandbox-windows-11/) . Similarly, you may need to enable a few additional optional features essential to run the virtualization tool successfully.

 The two optional features you need to enable are**Virtual Machine Platform** and**Windows Hypervisor Platform** . These tools enable platform support for virtual machines and provide the necessary API to run virtualization software on Windows.

To enable virtualization features:

1. Press**Win + I** to open**Settings** .
2. Type**appwiz.cpl** and click**OK** to open**Control Panel.**  
![turn windows features on off windows 11 control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-windows-featureson-off-windows-11-control-panel.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
3. In the left pane, click on**Turn Windows features on or off.**  
![turn on virtual machine platform windows hypervisor platform](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/turn-on-virtual-machine-platform-windows-hypervisor-platform.jpg)
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
4. In the**Windows Features** dialogue, scroll down and locate**Virtual Machine Platform** and**Windows Hypervisor Platform.**
5. Select both options and click**OK** .
6. Windows will start installing the necessary files. So, wait for the process to complete. Once done, click on**Restart Now** to restart your system and apply the changes.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
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
<li><a href="https://vp-tips.techidaily.com/new-aesthetic-fusion-studio-ultimate-photo-alchemy/"><u>[New] Aesthetic Fusion Studio  Ultimate Photo Alchemy</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-elevating-video-reach-the-role-of-smart-backlinking-techniques/"><u>[New] In 2024, Elevating Video Reach  The Role of Smart Backlinking Techniques</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-exploring-virtual-realms-with-kinemaster-app-for-android-users/"><u>[New] In 2024, Exploring Virtual Realms with KineMaster App for Android Users</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-troubleshooting-techniques-for-sudden-facebook-live-freezes/"><u>[New] In 2024, Troubleshooting Techniques for Sudden Facebook Live Freezes</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-embracing-whimsy-cartoon-face-magic-in-snapchat/"><u>[Updated] 2024 Approved  Embracing Whimsy  Cartoon Face Magic in Snapchat</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-share-and-celebrate-with-instagram-videos/"><u>[Updated] In 2024, Share & Celebrate with Instagram Videos</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-a-look-at-amazon-primes-biggest-tweeters-and-favorites-in-23/"><u>2024 Approved  A Look at Amazon Prime’s Biggest Tweeters and Favorites in '23</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-instagram-shout-out-for-podcast-fans/"><u>2024 Approved  Instagram Shout-Out for Podcast Fans</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-steps-to-restore-your-usb-wi-fi-on-a-pc/"><u>7 Key Steps to Restore Your USB Wi-Fi On a PC</u></a></li>
<li><a href="https://win11.techidaily.com/a-practical-approach-backing-up-and-restoring-notebooks/"><u>A Practical Approach: Backing Up & Restoring Notebooks</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-workflow-creating-windows-11-folders-en-masse/"><u>Accelerate Workflow: Creating Windows 11 Folders En Masse</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-disrupted-microphone-linkage-in-pc-gaming-with-valorant/"><u>Addressing Disrupted Microphone Linkage in PC Gaming with Valorant</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-functional-cortana-on-windows-11/"><u>Addressing Non-Functional Cortana on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-software-instability-in-windows-store-purchases/"><u>Addressing Software Instability in Windows Store Purchases</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-10-and-11s-0x0000011b-faults/"><u>Addressing Windows 10 & 11'S 0X0000011B Faults</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-fatal-error-code-0x8007007e/"><u>Addressing Windows Fatal Error: Code 0X8007007E</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-down-windows-repair-tool-guide/"><u>Breaking Down Windows Repair Tool Guide</u></a></li>
<li><a href="https://win11.techidaily.com/confirming-windows-11s-integrity-quick-checks/"><u>Confirming Windows 11'S Integrity: Quick Checks</u></a></li>
<li><a href="https://win11.techidaily.com/cut-down-complexity-set-terminal-as-the-default-cli/"><u>Cut-Down Complexity: Set Terminal as the Default CLI</u></a></li>
<li><a href="https://win11.techidaily.com/designing-a-secure-hardware-removal-window-tip/"><u>Designing a Secure Hardware Removal Window Tip</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/effective-fixes-for-missing-or-corrupted-fm20dll-files/"><u>Effective Fixes for Missing or Corrupted Fm20.dll Files</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-blank-spaces-in-windows-explorer/"><u>Eliminating Blank Spaces in Windows Explorer</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-pcs-archives-functionality/"><u>Enhance Your PC's Archives Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/fix-unrecognized-app-warning-during-windows-setup/"><u>Fix Unrecognized App Warning During Windows Setup</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/get-a-powerful-64-bit-video-editor-windows-8and10-included-for-2024/"><u>Get a Powerful 64-Bit Video Editor (Windows 8&10 Included) for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-audit-your-windows-drive-space-usage-efficiently/"><u>How to Audit Your Windows Drive Space Usage Efficiently</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-on-google-pixel-8-pro-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock on Google Pixel 8 Pro Devices</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-the-two-factor-authentication-from-iphone-12-pro-max-by-drfone-ios/"><u>How To Remove the Two Factor Authentication From iPhone 12 Pro Max</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-rescue-your-windows-mail-app-from-the-clutches-of-0x800713f/"><u>How to Rescue Your Windows Mail App From the Clutches of 0X800713F</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-new-folders-into-windows-11s-menu/"><u>Integrating New Folders Into Windows 11'S Menu</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-windows-11-experience-introducing-an-augmented-run-feature/"><u>Master Your Windows 11 Experience: Introducing an Augmented Run Feature</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-new-windows-11-taskbar-features/"><u>Mastering the New Windows 11 Taskbar Features</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-error-missing-driver-issues/"><u>Overcoming Windows Error: Missing Driver Issues</u></a></li>
<li><a href="https://win11.techidaily.com/precision-steps-restoring-your-windows-11-search-efficiency/"><u>Precision Steps: Restoring Your Window's 11 Search Efficiency</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-black-screen-during-games-on-win/"><u>Resolving Black Screen During Games on WIN</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-device-unreachable-errors/"><u>Resolving Windows Device Unreachable Errors</u></a></li>
<li><a href="https://win11.techidaily.com/secure-your-gameplay-preventing-minecraft-freezes/"><u>Secure Your Gameplay: Preventing Minecraft Freezes</u></a></li>
<li><a href="https://win11.techidaily.com/security-simplified-defaults-in-windows-11-setup/"><u>Security Simplified: Defaults in Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-not-empty-directory-problem-in-windows-os/"><u>Steps to Overcome Not Empty Directory Problem in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-unlock-regular-startup-for-outlook-on-safe-mode/"><u>Steps to Unlock Regular Startup for Outlook on Safe Mode</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-failed-onedrive-cloud-sync/"><u>Strategies for Fixing Failed OneDrive Cloud Sync</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solution-to-interrupt-error-in-windows-11-screensaver/"><u>Swift Solution to INTERRUPT ERROR in Windows 11 Screensaver</u></a></li>
<li><a href="https://some-guidance.techidaily.com/ultimate-comic-editor-app-for-2024/"><u>Ultimate Comic Editor App for 2024</u></a></li>
<li><a href="https://some-tips.techidaily.com/understanding-the-zip-to-srt-file-transition-for-2024/"><u>Understanding the Zip to Srt File Transition for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-access-issues-with-these-top-5-windows-fixes-on-security-keys/"><u>Unlock Access Issues with These Top 5 Windows Fixes on Security Keys</u></a></li>
<li><a href="https://win-answers.techidaily.com/unlocking-seamless-gameplay-expert-advice-for-addressing-persona-5-strikers-performance-errors-on-desktops/"><u>Unlocking Seamless Gameplay: Expert Advice for Addressing Persona 5 Strikers' Performance Errors on Desktops</u></a></li>
<li><a href="https://fox-that.techidaily.com/unlocking-the-secrets-putting-your-ipad-into-recovery-mode-without-stress/"><u>Unlocking the Secrets: Putting Your iPad Into Recovery Mode Without Stress</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-say-goodbye-to-grainy-videos-top-resolution-enhancement-tools-for-2024/"><u>Updated Say Goodbye to Grainy Videos Top Resolution Enhancement Tools for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/wired-for-security-swiftly-repairing-windows-features/"><u>Wired for Security: Swiftly Repairing Windows Features</u></a></li>
</ul></div>
