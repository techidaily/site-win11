---
title: "Hosting Multiple OSes: Linux VM Inside Hyper-V on a Windows Machine"
date: 2024-08-16T00:40:34.630Z
updated: 2024-08-17T00:40:34.630Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Hosting Multiple OSes: Linux VM Inside Hyper-V on a Windows Machine"
excerpt: "This Article Describes Hosting Multiple OSes: Linux VM Inside Hyper-V on a Windows Machine"
keywords: Multi OS Hosting,Hyper-V Linux VM,Windows Hyper-V Support,VMware Linux Integration,Linux Virtualization,Cross-Platform Virtualization,Operating Systems in One PC
thumbnail: https://thmb.techidaily.com/60a050976608e9140d90809a0ac2529ef41e9995b243e26e295a790742b88b8b.jpg
---

## Hosting Multiple OSes: Linux VM Inside Hyper-V on a Windows Machine

 Virtual Machines enable you to experience multiple operating systems on a single system while keeping them isolated from the host OS. You must have tried creating virtual machines to try out a new OS you don’t want to install directly. But have you ever tried using Hyper-V inside a virtual machine?

 Hyper-V is Windows inbuilt hypervisor that allows you to create virtual machines and run them. But it is also possible to use Hyper-V inside a VMware Windows virtual machine. So, you can create a Hyper-V virtual machine inside a VMware virtual machine and run it without any issues. Here’s how to do it.

## The Prerequisites for Running a Linux Virtual Machine Inside Hyper-V

 Firstly, you will need a Windows virtual machine that is completely functional inside VMware. We would suggest Windows 10 or 11 virtual machines for this project. Moreover, you must pick either Windows Pro or Enterprise edition because Hyper-V isn’t available for Windows Home edition.

 Make sure to dedicate an adequate amount of hardware resources to the virtual machine. The reason behind this is that you will try to run a virtual machine inside a virtual machine. So, the Windows virtual machine can dedicate only a portion of its resources to running a Linux virtual machine using Hyper-V. We tested this using a Windows 11 system with 16GB of RAM and an eight-core AMD processor.

 Also, update the VMware Workstation Player to the latest version before you begin the installation method.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
## How to Create a Linux Virtual Machine Inside Windows Virtual Machine Using Hyper-V

 We will break the steps into three parts. Firstly, you must enable the virtualization features for the Windows virtual machine. Then you need to enable Hyper-V on this virtual machine. Lastly, you need to create a Linux virtual machine using Hyper-V.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 1\. Enable Virtualization for Windows Virtual Machine in VMware

To enable Virtualization, do as follows:

1. Launch the VMware app on your system. Click on the Windows virtual machine you want to use.
2. Virtual machine details will pop up on the right side. Click on the**Edit Virtual Machine settings** option.
3. The**Hardware** tab will open by default. Click on the**Processors** option.
4. Locate the V**irtualize engine section** and click on**Virtualize Intel VT-x/EPT or AMD-V/RV** option.  
![Enable Virtualization for Windows Virtual Machine in VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-virtualization-for-windows-virtual-machine-in-vmware.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Click on the**OK** button to apply changes.

 Virtualization features are now active for the above Windows virtual machine. Next, you need to install Hyper-V.

### 2\. Install Hyper-V on the Windows Virtual Machine

 To install Hyper-V on the VMware Windows virtual machine, repeat the following steps.

1. Launch the VMware app on your system. Double-click on the Windows virtual machine to boot it up.
2. Once you boot to the desktop, press the**Win + R** key to [launch the Run command box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
3. Type**appwiz.cpl** and press the enter key.
4. The programs and features window will launch. Click on the**Turn Windows Features on or off** option.
5. Scroll down and click on the**Hyper-V** checkbox in the Windows Features list.  
![Install Hyper-V on the Windows Virtual Machine](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/install-hyper-v-on-the-windows-virtual-machine.jpg)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Click on the**OK** button to install the feature on your system.
7. **Restart** your system to apply changes when the installation completes.

 Hyper-V is now active on your Windows virtual machine. Next, you need to create a Linux virtual machine it.

### 3\. Create a Linux Virtual Machine Using Hyper-V

 The last piece of the puzzle is to create a Linux virtual machine inside the Windows virtual machine using Hyper-V. You can pick any Linux distribution that you want. We will go with Ubuntu for this experiment. You have to download the Ubuntu ISO file inside the virtual machine from the [Ubuntu website](https://ubuntu.com/download/desktop) before starting with the steps.

To create an Ubuntu virtual machine, do as follows:

1. Boot up the Windows virtual machine. Press the**Win key** and type Hyper-V manager. Launch the app.
2. Navigate to the right-hand side section and click on**New > Virtual Machine** .  
![Create a Linux Virtual Machine Using Hyper-V 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-1.jpg)
3. Click on the**Next** button. Enter the name of the virtual machine and click on**Next** .
4. Click on the**Generation 1** radio button and click on Next.
5. Keep the**Startup Memory** as**2GB** and enable the**Use Dynamic memory for this virtual machine** option.  
![Create a Linux Virtual Machine Using Hyper-V 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-2.jpg)
6. Then, click on**Next** button and select the**Default switch** option in the Configure Networking section.
7. Click on the**Create a virtual hard disk** option and allocate**20GB** to the virtual hard disk. Move to the next section.  
![Create a Linux Virtual Machine Using Hyper-V 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-3.jpg)
8. Pick the**Install an operating system from a bootable CD/DVD-ROM** option located under the Installation options section. Select the Ubuntu Image file (.iso) you downloaded before beginning this step.  
![Create a Linux Virtual Machine Using Hyper-V 4](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-4.jpg)
<!-- affiliate ads begin -->
<span id="1997795">
					<video width="250" height="250" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/23621-1997795">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1997795.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:250px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fproteahair.pxf.io%2Fc%2F5597632%2F1997795%2F23621'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997795/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

## A Few Things to Remember

 Creating a virtual machine inside a virtual machine is possible. But you have to remember that the underlying configuration of the host system must be such that it can run a virtual machine inside a virtual machine without any issue. If you attempt this experiment on a low-end system with 4GB RAM and a dual-core processor, it will choke the system.

 So, you need to use a system that can devote ample hardware resources to the Windows virtual machine. Only, then you would be able to use Hyper-V and create a Linux virtual machine and allocate run it without any issues. After you try our Ubuntu using Hyper-V, you can power off the virtual machine. Or you can take the extra step and delete the virtual machine from Hyper-V Manager. It will free up a lot of space inside the Windows virtual machine.

 Also, uninstall the Hyper-V feature if you don’t need it any further in your Windows virtual machine. Check out our guide on [how to disable or remove Hyper-V in Windows 11](https://www.makeuseof.com/windows-11-disable-hyper-v/) for more information.

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-boost-your-revenue-yielding-earnings-from-youtube-at-500-followers/"><u>[New] In 2024, Boost Your Revenue  Yielding Earnings From YouTube at 500 Followers</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/nnovators-intertwining-video-with-melodious-images-for-2024/"><u>[New] Innovators Intertwining Video with Melodious Images for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-design-humor-in-frames-picgenius/"><u>[Updated] 2024 Approved  Design Humor in Frames  PicGenius</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-unleash-creativity-capturing-quality-videos-on-logitech-for-2024/"><u>[Updated] Unleash Creativity  Capturing Quality Videos on Logitech for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/7-key-approaches-to-cure-the-ailing-windows-service-control-panel/"><u>7 Key Approaches to Cure the Ailing Windows Service Control Panel</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-windows-1011s-share-issue-with-nvidia/"><u>Addressing Windows 10/11'S Share Issue with NVIDIA</u></a></li>
<li><a href="https://win11.techidaily.com/beating-the-deadly-world-of-warcraft-fatality-windows-fix-guide/"><u>Beating the Deadly World of Warcraft Fatality: Windows Fix Guide</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ehensive-directory-of-inexpensive-stock-images-for-2024/"><u>Comprehensive Directory of Inexpensive Stock Images for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/easy-guide-clearing-out-microsoft-edge/"><u>Easy Guide: Clearing Out Microsoft Edge</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/error-solved-excel-2016-file-is-not-in-recognizable-format-by-stellar-guide/"><u>Error Solved Excel 2016 file is not in recognizable format</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-for-moving-programs-from-older-win-pcs-to-windows-11/"><u>Essential Steps for Moving Programs From Older Win PCs to Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-to-prevent-vscode-failures-w11/"><u>Essential Steps to Prevent VSCode Failures W11</u></a></li>
<li><a href="https://win11.techidaily.com/examining-the-role-and-relevance-of-wasd-in-windows/"><u>Examining the Role and Relevance of WASD in Windows</u></a></li>
<li><a href="https://tech-revival.techidaily.com/expert-strategies-to-correct-common-chatgpt-sign-in-errors/"><u>Expert Strategies to Correct Common ChatGPT Sign-In Errors</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/fixing-the-insufficient-bandwidth-warning-in-windows-11-a-step-by-step-guide/"><u>Fixing the 'Insufficient Bandwidth' Warning in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-regain-basic-windows-settings-after-restart/"><u>Guide to Regain Basic Windows Settings After Restart</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/guide-accessing-espn-plus-on-your-lg-smart-television/"><u>Guide: Accessing ESPN + On Your LG Smart Television</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-to-fix-amd-radeon-software-not-opening/"><u>How to Fix AMD Radeon Software Not Opening</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-force-windows-11-to-notify-you-when-someone-accesses-your-camera/"><u>How to Force Windows 11 to Notify You When Someone Accesses Your Camera</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-restore-a-bricked-realme-c67-5g-back-to-operation-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Restore a Bricked Realme C67 5G Back to Operation | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-honor-magic-v2-drfone-by-drfone-android/"><u>How to Screen Mirroring Honor Magic V2? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-sharefake-location-on-whatsapp-for-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>How to Share/Fake Location on WhatsApp for Samsung Galaxy F15 5G | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-2-ways-to-fade-audio-in-ableton/"><u>In 2024, 2 Ways to Fade Audio in Ableton</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-intercept-text-messages-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Intercept Text Messages on Xiaomi Redmi 13C 5G | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-mastering-podcast-beginnings-eye-catching-strategies/"><u>In 2024, Mastering Podcast Beginnings  Eye-Catching Strategies</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-top-group-video-chat-apps-you-should-know-for-video-conferences-and-meetings/"><u>In 2024, Top Group Video Chat Apps You Should Know [For Video Conferences and Meetings]</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-ultimate-guide-from-honor-x50i-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide from Honor X50i FRP Bypass</u></a></li>
<li><a href="https://win11-tips.techidaily.com/increase-your-productivity-in-windows-with-flow-launcher/"><u>Increase Your Productivity in Windows With Flow Launcher</u></a></li>
<li><a href="https://win11.techidaily.com/interpreting-windows-build-numbers/"><u>Interpreting Windows Build Numbers</u></a></li>
<li><a href="https://win11.techidaily.com/jumpstart-your-virtual-machine-performance-with-six-windows-tricks/"><u>Jumpstart Your Virtual Machine Performance with Six Windows Tricks</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fps-in-csgo-essential-insights/"><u>Mastering FPS in CS:GO - Essential Insights</u></a></li>
<li><a href="https://win11.techidaily.com/mending-usb30-device-failure-in-windows-1011-systems/"><u>Mending USB3.0 Device Failure in Windows 10/11 Systems</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-split-screen-video-editing-software-free-online-and-offline-solutions/"><u>New Split Screen Video Editing Software Free Online and Offline Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/one-os-multiple-worlds-windows-across-mobile-tablet-mac-and-desktop-realized/"><u>One OS, Multiple Worlds: Windows Across Mobile, Tablet, Mac & Desktop Realized</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-lighting-top-brightness-managers-for-windows-monitors/"><u>Optimal Lighting: Top Brightness Managers for Windows Monitors</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-device-pathway-restrictions-in-windows/"><u>Overcoming Device Pathway Restrictions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-launchers-secure-login-failures-on-windows-os/"><u>Overcoming Launcher's Secure Login Failures on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-outdated-boot-options-gray/"><u>Overcoming Outdated BOOT Options Gray</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-win11-how-to-resolve-stalled-file-transfers-4/"><u>Overcoming WIN11: How to Resolve Stalled File Transfers (4)</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-visual-harmony-with-windows-desktop-wallpapers/"><u>Perfecting Visual Harmony with Windows Desktop Wallpapers</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-accessing-your-iis-management-center/"><u>Quick Fixes for Accessing Your IIS Management Center</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/savor-these-tantalizing-titles-top-ten-cooking-masterpieces-streamed-on-netflix/"><u>Savor These Tantalizing Titles: Top Ten Cooking Masterpieces Streamed on Netflix</u></a></li>
<li><a href="https://win11.techidaily.com/steer-clear-from-cheap-windows-codes-a-cautionary-tale/"><u>Steer Clear From Cheap Windows Codes: A Cautionary Tale</u></a></li>
<li><a href="https://win11.techidaily.com/swift-remedies-for-the-delayed-folder-upload-issue-onedrive-errors/"><u>Swift Remedies for the Delayed Folder Upload Issue: OneDrive Errors</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-temporary-path-errors-quick-fix-guide-for-windows-error-1152/"><u>Tackling Temporary Path Errors - Quick Fix Guide for Windows Error 1152</u></a></li>
<li><a href="https://win11.techidaily.com/the-mechanics-of-controlling-gpgpu-priority-on-winos/"><u>The Mechanics of Controlling GPGPU Priority on WINOS</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-visual-verdict-sj6-meets-xiaomis-yi-visionaries-for-2024/"><u>The Ultimate Visual Verdict  SJ6 Meets Xiaomi’s Yi Visionaries for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-missing-device-issue-on-windows-os/"><u>Troubleshooting Missing Device Issue on Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/unblocking-the-blocked-fixing-windows-access-issues/"><u>Unblocking the Blocked: Fixing Windows Access Issues</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-peak-potential-7-efficient-practices-for-windows-11-users/"><u>Unleash Peak Potential: 7 Efficient Practices for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/unzipping-complex-archives-a-windows-cli-experts-manual/"><u>Unzipping Complex Archives: A Windows CLI Expert's Manual</u></a></li>
<li><a href="https://win11.techidaily.com/w11s-moment-update-a-glimpse-at-the-next-gen-features/"><u>W11's Moment Update: A Glimpse at the Next-Gen Features</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-realme-narzo-60-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Realme Narzo 60 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/windows-secure-access-tips-for-stuck-pins/"><u>Windows Secure Access: Tips for Stuck Pins</u></a></li>
</ul></div>
