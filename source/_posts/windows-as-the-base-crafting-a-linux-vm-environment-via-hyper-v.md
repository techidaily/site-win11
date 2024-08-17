---
title: "Windows as the Base: Crafting a Linux VM Environment via Hyper-V"
date: 2024-08-16T00:55:03.791Z
updated: 2024-08-17T00:55:03.791Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Windows as the Base: Crafting a Linux VM Environment via Hyper-V"
excerpt: "This Article Describes Windows as the Base: Crafting a Linux VM Environment via Hyper-V"
keywords: Windows Hyper-V Virtualization,Linux VM on Windows Server,Create Linux VM with Hyper-V,Virtualizing Linux Using Hyper-V,Windows Servers for Linux VMs,Setting up Linux VM in Hyper-V,Hybrid OS
thumbnail: https://thmb.techidaily.com/72529af7d2bf02239916cd0ba31d950846919ac8ac9ff5b071dc373f5d27eae7.jpg
---

## Windows as the Base: Crafting a Linux VM Environment via Hyper-V

 Virtual Machines enable you to experience multiple operating systems on a single system while keeping them isolated from the host OS. You must have tried creating virtual machines to try out a new OS you don’t want to install directly. But have you ever tried using Hyper-V inside a virtual machine?

 Hyper-V is Windows inbuilt hypervisor that allows you to create virtual machines and run them. But it is also possible to use Hyper-V inside a VMware Windows virtual machine. So, you can create a Hyper-V virtual machine inside a VMware virtual machine and run it without any issues. Here’s how to do it.

## The Prerequisites for Running a Linux Virtual Machine Inside Hyper-V

 Firstly, you will need a Windows virtual machine that is completely functional inside VMware. We would suggest Windows 10 or 11 virtual machines for this project. Moreover, you must pick either Windows Pro or Enterprise edition because Hyper-V isn’t available for Windows Home edition.

 Make sure to dedicate an adequate amount of hardware resources to the virtual machine. The reason behind this is that you will try to run a virtual machine inside a virtual machine. So, the Windows virtual machine can dedicate only a portion of its resources to running a Linux virtual machine using Hyper-V. We tested this using a Windows 11 system with 16GB of RAM and an eight-core AMD processor.

 Also, update the VMware Workstation Player to the latest version before you begin the installation method.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
## How to Create a Linux Virtual Machine Inside Windows Virtual Machine Using Hyper-V

 We will break the steps into three parts. Firstly, you must enable the virtualization features for the Windows virtual machine. Then you need to enable Hyper-V on this virtual machine. Lastly, you need to create a Linux virtual machine using Hyper-V.

### 1\. Enable Virtualization for Windows Virtual Machine in VMware

To enable Virtualization, do as follows:

1. Launch the VMware app on your system. Click on the Windows virtual machine you want to use.
2. Virtual machine details will pop up on the right side. Click on the**Edit Virtual Machine settings** option.
3. The**Hardware** tab will open by default. Click on the**Processors** option.
4. Locate the V**irtualize engine section** and click on**Virtualize Intel VT-x/EPT or AMD-V/RV** option.  
![Enable Virtualization for Windows Virtual Machine in VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-virtualization-for-windows-virtual-machine-in-vmware.jpg)
5. Click on the**OK** button to apply changes.

 Virtualization features are now active for the above Windows virtual machine. Next, you need to install Hyper-V.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
### 2\. Install Hyper-V on the Windows Virtual Machine

 To install Hyper-V on the VMware Windows virtual machine, repeat the following steps.

1. Launch the VMware app on your system. Double-click on the Windows virtual machine to boot it up.
2. Once you boot to the desktop, press the**Win + R** key to[launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
3. Type**appwiz.cpl** and press the enter key.
4. The programs and features window will launch. Click on the**Turn Windows Features on or off** option.
5. Scroll down and click on the**Hyper-V** checkbox in the Windows Features list.  
![Install Hyper-V on the Windows Virtual Machine](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/install-hyper-v-on-the-windows-virtual-machine.jpg)
6. Click on the**OK** button to install the feature on your system.
7. **Restart** your system to apply changes when the installation completes.

 Hyper-V is now active on your Windows virtual machine. Next, you need to create a Linux virtual machine it.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
### 3\. Create a Linux Virtual Machine Using Hyper-V

 The last piece of the puzzle is to create a Linux virtual machine inside the Windows virtual machine using Hyper-V. You can pick any Linux distribution that you want. We will go with Ubuntu for this experiment. You have to download the Ubuntu ISO file inside the virtual machine from the[Ubuntu website](https://ubuntu.com/download/desktop) before starting with the steps.

To create an Ubuntu virtual machine, do as follows:

1. Boot up the Windows virtual machine. Press the**Win key** and type Hyper-V manager. Launch the app.
2. Navigate to the right-hand side section and click on**New > Virtual Machine** .  
![Create a Linux Virtual Machine Using Hyper-V 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-1.jpg)
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Click on the**Next** button. Enter the name of the virtual machine and click on**Next** .
4. Click on the**Generation 1** radio button and click on Next.
5. Keep the**Startup Memory** as**2GB** and enable the**Use Dynamic memory for this virtual machine** option.  
![Create a Linux Virtual Machine Using Hyper-V 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-2.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
6. Then, click on**Next** button and select the**Default switch** option in the Configure Networking section.
7. Click on the**Create a virtual hard disk** option and allocate**20GB** to the virtual hard disk. Move to the next section.  
![Create a Linux Virtual Machine Using Hyper-V 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-3.jpg)
8. Pick the**Install an operating system from a bootable CD/DVD-ROM** option located under the Installation options section. Select the Ubuntu Image file (.iso) you downloaded before beginning this step.  
![Create a Linux Virtual Machine Using Hyper-V 4](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-4.jpg)
9. Click on the**Next** button and review the virtual machine configuration. Then, click on the**Finish** button to create the virtual machine.

 Now that the virtual machine is ready, it's time to get Ubuntu up and running:

1. Select the newly created virtual machine in the list and click on the**Start** option to launch the virtual machine.
2. Ubuntu setup will launch. Select the**Install Ubuntu** option and proceed with the installation.
3. Click on**Minimal Installation** and uncheck the**Download updates while installing Ubuntu** option.
4. Then, pick the**Erase disk and install Ubuntu** option and click on the**Install Now** button.
5. Select your geographical location and enter your username and password. Then, click on the**Continue** button.
6. Wait for the installation to complete. It may take longer if you have a SATA HDD installed on your system.
7. The installer will prompt you to restart the system. Click on the**Restart Now** button.  
![Ubuntu Virtual Machine Running Using Hyper-V](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/ubuntu-virtual-machine-running-using-hyper-v.jpg)

 The virtual machine will boot to the Ubuntu desktop. You can use Ubuntu and notice that the system runs fine inside Hyper-V just like it does on any other virtualization software.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
## A Few Things to Remember

 Creating a virtual machine inside a virtual machine is possible. But you have to remember that the underlying configuration of the host system must be such that it can run a virtual machine inside a virtual machine without any issue. If you attempt this experiment on a low-end system with 4GB RAM and a dual-core processor, it will choke the system.

 So, you need to use a system that can devote ample hardware resources to the Windows virtual machine. Only, then you would be able to use Hyper-V and create a Linux virtual machine and allocate run it without any issues. After you try our Ubuntu using Hyper-V, you can power off the virtual machine. Or you can take the extra step and delete the virtual machine from Hyper-V Manager. It will free up a lot of space inside the Windows virtual machine.

 Also, uninstall the Hyper-V feature if you don’t need it any further in your Windows virtual machine. Check out our guide on[how to disable or remove Hyper-V in Windows 11](https://www.makeuseof.com/windows-11-disable-hyper-v/) for more information.

## Use Virtual Machine Inside a Virtual Machine With Hyper-V

 VMware supports hardware virtualization and can extend the feature to its virtual machines. VirtualBox is yet to catch up in this aspect because Hyper-V doesn’t work in a VirtualBox virtual machine as of writing this post. Make sure that you turn off virtualization features for the Windows virtual machine when you no longer need it.


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
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-proven-ways-to-cash-in-instagrams-leading-revenue-methods/"><u>[New] In 2024, Proven Ways to Cash In  Instagram's Leading Revenue Methods</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-sculpt-striking-signs-with-stock-designs-at-no-cost/"><u>[New] Sculpt Striking Signs with Stock Designs at No Cost</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-skip-the-hassle-find-4-ringtone-sources-here/"><u>[New] Skip the Hassle  Find 4 Ringtone Sources Here</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-unwind-youtube-videos-advanced-retrospectives/"><u>[New] Unwind YouTube Videos  Advanced Retrospectives</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-pro-level-7-cameras-perfect-for-professional-broadcasting-vloggers/"><u>[Updated] 2024 Approved  Pro-Level 7 Cameras Perfect for Professional Broadcasting Vloggers</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-2024-approved-vidvault-prodigies-mastering-the-download-of-tweeted-videos/"><u>[Updated] 2024 Approved  VidVault Prodigies  Mastering the Download of Tweeted Videos</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-advanced-photography-skills-precision-cropping-in-digital-spaces/"><u>[Updated] Advanced Photography Skills  Precision Cropping in Digital Spaces</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-fix-obs-white-outage-during-live-streams-for-2024/"><u>[Updated] Fix OBS White Outage During Live Streams for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-art-of-fullscreen-editing-with-premiere-pro-experts/"><u>[Updated] The Art of Fullscreen Editing with Premiere Pro Experts</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-youtube-subscriber-boost4-simplest-tricks-to-grow-your-channel-for-2024/"><u>[Updated] YouTube Subscriber Boost–4 Simplest Tricks to Grow Your Channel for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-pros-picks-the-5-ultimate-gaming-stream-cams-uncovered/"><u>2024 Approved  Pro's Picks  The 5 Ultimate Gaming Stream Cams Uncovered</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-what-makes-a-viral-video-the-tiktok-twitter-link/"><u>2024 Approved  What Makes a Viral Video  The TikTok-Twitter Link</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-msresourceappname-text-glitch-in-w11/"><u>Addressing 'MsResource/AppName Text' Glitch in W11</u></a></li>
<li><a href="https://win11.techidaily.com/becoming-a-closed-captioning-guru-windows-10-insights/"><u>Becoming a Closed Captioning Guru: Windows 10 Insights</u></a></li>
<li><a href="https://win11.techidaily.com/delving-into-variability-between-offline-and-online-windows-installation-processes/"><u>Delving Into Variability Between Offline and Online Windows Installation Processes</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-copy-paste-with-predefined-text-in-w10w11/"><u>Efficient Copy-Paste with Predefined Text in W10/W11</u></a></li>
<li><a href="https://win11.techidaily.com/faster-teams-cleaner-systems-microsofts-pivot/"><u>Faster Teams, Cleaner Systems: Microsoft's Pivot</u></a></li>
<li><a href="https://some-techniques.techidaily.com/for-every-level-of-filmmaker-our-top-10-camera-picks-for-2024/"><u>For Every Level of Filmmaker, Our Top 10 Camera Picks for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/from-boring-to-stunning-switching-themes-in-windows-11-made-simple/"><u>From Boring to Stunning: Switching Themes in Windows 11 Made Simple</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-discovering-the-advantages-of-multi-angle-recording/"><u>In 2024, Discovering the Advantages of Multi-Angle Recording</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-professionals-guide-to-photo-watermarking-solutions/"><u>In 2024, Professional's Guide to Photo Watermarking Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fixes-for-error-code-0x8000fffd-on-pcs/"><u>Mastering Fixes for Error Code 0X8000FFFD on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-volume-adjustment-issues-in-windows-os/"><u>Mastering Volume Adjustment Issues in Windows OS</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-cross-platform-video-editing-mastery-a-step-by-step-chromebook-guide-for-2024/"><u>New Cross-Platform Video Editing Mastery A Step-by-Step Chromebook Guide for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/optimizing-pitch-alteration-in-audacity-a-guide-to-quality-retention/"><u>Optimizing Pitch Alteration in Audacity A Guide to Quality Retention</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-no-more-space-files-issue/"><u>Overcoming 'No More Space' Files Issue</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unable-to-display-errors-in-microsoft-store/"><u>Overcoming 'Unable to Display' Errors in Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-thumbnails-dimensions-on-desktop/"><u>Personalize Thumbnails: Dimensions on Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/rectify-the-disappeared-disk-space-issue/"><u>Rectify the Disappeared Disk Space Issue</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-keyboard-errors-fixing-function-keys-on-windows-11/"><u>Resolve: Keyboard Errors - Fixing Function Keys on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/running-advanced-ai-on-windows-devices/"><u>Running Advanced AI on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/solving-installed-but-inaccessible-microsoft-apps/"><u>Solving Installed but Inaccessible Microsoft Apps</u></a></li>
<li><a href="https://win11.techidaily.com/solving-mbs-service-connection-failures-on-windows-11/"><u>Solving MB's Service Connection Failures on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackle-windows-geforce-scanning-problems-effectively/"><u>Tackle Windows GeForce Scanning Problems Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/the-clear-sight-crusade-nine-methods-to-sharpen-your-monitor/"><u>The Clear Sight Crusade: Nine Methods to Sharpen Your Monitor</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/the-ultimate-checklist-finding-videos-on-fb-today/"><u>The Ultimate Checklist  Finding Videos on FB Today</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/things-about-asmr-video-you-should-know/"><u>Things About ASMR Video You Should Know</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steps-for-quickly-resolving-operation-requirement-errors/"><u>Troubleshooting Steps for Quickly Resolving Operation Requirement Errors</u></a></li>
<li><a href="https://win11.techidaily.com/1719276552494-unlock-windows-free-up-space-no-more-temp-files/"><u>Unlock Windows Free Up Space, No More Temp Files</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-distinctions-of-windows-terminal-vs-powershell/"><u>Unraveling The Distinctions of Windows Terminal Vs. PowerShell</u></a></li>
</ul></div>
