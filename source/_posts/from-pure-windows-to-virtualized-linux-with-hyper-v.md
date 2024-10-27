---
title: From Pure Windows to Virtualized Linux with Hyper-V
date: 2024-10-25T00:47:23.433Z
updated: 2024-10-26T20:32:03.979Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes From Pure Windows to Virtualized Linux with Hyper-V
excerpt: This Article Describes From Pure Windows to Virtualized Linux with Hyper-V
keywords: Hyper-V Virtualization,Hyper-V Windows Shift,Pure OS to Hyper-V,Linux via Hyper-V,Transition Windows to Linux,Virtualized Linux with Hyper-V,Pure Windows Virtualization,Hyper-V Virtualized,Pure OS Hyper-V,Windows to Linux VM
thumbnail: https://thmb.techidaily.com/a208b6b47f62fc53f6719bf37fb44710d3bca87f00271cab6e02272f4110e26d.jpg
---

## From Pure Windows to Virtualized Linux with Hyper-V

 Virtual Machines enable you to experience multiple operating systems on a single system while keeping them isolated from the host OS. You must have tried creating virtual machines to try out a new OS you don’t want to install directly. But have you ever tried using Hyper-V inside a virtual machine?

 Hyper-V is Windows inbuilt hypervisor that allows you to create virtual machines and run them. But it is also possible to use Hyper-V inside a VMware Windows virtual machine. So, you can create a Hyper-V virtual machine inside a VMware virtual machine and run it without any issues. Here’s how to do it.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## The Prerequisites for Running a Linux Virtual Machine Inside Hyper-V

 Firstly, you will need a Windows virtual machine that is completely functional inside VMware. We would suggest Windows 10 or 11 virtual machines for this project. Moreover, you must pick either Windows Pro or Enterprise edition because Hyper-V isn’t available for Windows Home edition.

 Make sure to dedicate an adequate amount of hardware resources to the virtual machine. The reason behind this is that you will try to run a virtual machine inside a virtual machine. So, the Windows virtual machine can dedicate only a portion of its resources to running a Linux virtual machine using Hyper-V. We tested this using a Windows 11 system with 16GB of RAM and an eight-core AMD processor.

 Also, update the VMware Workstation Player to the latest version before you begin the installation method.

## How to Create a Linux Virtual Machine Inside Windows Virtual Machine Using Hyper-V

 We will break the steps into three parts. Firstly, you must enable the virtualization features for the Windows virtual machine. Then you need to enable Hyper-V on this virtual machine. Lastly, you need to create a Linux virtual machine using Hyper-V.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098705/14409" target="_top" id="2098705">
  <img src="//a.impactradius-go.com/display-ad/14409-2098705" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098705/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 1\. Enable Virtualization for Windows Virtual Machine in VMware

To enable Virtualization, do as follows:

1. Launch the VMware app on your system. Click on the Windows virtual machine you want to use.
2. Virtual machine details will pop up on the right side. Click on the**Edit Virtual Machine settings** option.
3. The**Hardware** tab will open by default. Click on the**Processors** option.
4. Locate the V**irtualize engine section** and click on**Virtualize Intel VT-x/EPT or AMD-V/RV** option.  
![Enable Virtualization for Windows Virtual Machine in VMware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/enable-virtualization-for-windows-virtual-machine-in-vmware.jpg)
5. Click on the**OK** button to apply changes.

 Virtualization features are now active for the above Windows virtual machine. Next, you need to install Hyper-V.

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
<a href="https://aligracehair.sjv.io/c/5597632/2036472/19272" target="_top" id="2036472">
  <img src="//a.impactradius-go.com/display-ad/19272-2036472" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036472/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 3\. Create a Linux Virtual Machine Using Hyper-V

 The last piece of the puzzle is to create a Linux virtual machine inside the Windows virtual machine using Hyper-V. You can pick any Linux distribution that you want. We will go with Ubuntu for this experiment. You have to download the Ubuntu ISO file inside the virtual machine from the[Ubuntu website](https://ubuntu.com/download/desktop) before starting with the steps.

To create an Ubuntu virtual machine, do as follows:

1. Boot up the Windows virtual machine. Press the**Win key** and type Hyper-V manager. Launch the app.
2. Navigate to the right-hand side section and click on**New > Virtual Machine** .  
![Create a Linux Virtual Machine Using Hyper-V 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-1.jpg)
3. Click on the**Next** button. Enter the name of the virtual machine and click on**Next** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144309/7443" target="_top" id="2144309">
  <img src="//a.impactradius-go.com/display-ad/7443-2144309" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144309/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. Click on the**Generation 1** radio button and click on Next.
5. Keep the**Startup Memory** as**2GB** and enable the**Use Dynamic memory for this virtual machine** option.  
![Create a Linux Virtual Machine Using Hyper-V 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-2.jpg)
6. Then, click on**Next** button and select the**Default switch** option in the Configure Networking section.
7. Click on the**Create a virtual hard disk** option and allocate**20GB** to the virtual hard disk. Move to the next section.  
![Create a Linux Virtual Machine Using Hyper-V 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-3.jpg)
8. Pick the**Install an operating system from a bootable CD/DVD-ROM** option located under the Installation options section. Select the Ubuntu Image file (.iso) you downloaded before beginning this step.  
![Create a Linux Virtual Machine Using Hyper-V 4](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-4.jpg)
9. Click on the**Next** button and review the virtual machine configuration. Then, click on the**Finish** button to create the virtual machine.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037318/7443" target="_top" id="2037318">
  <img src="//a.impactradius-go.com/display-ad/7443-2037318" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037318/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now that the virtual machine is ready, it's time to get Ubuntu up and running:

1. Select the newly created virtual machine in the list and click on the**Start** option to launch the virtual machine.
2. Ubuntu setup will launch. Select the**Install Ubuntu** option and proceed with the installation.
3. Click on**Minimal Installation** and uncheck the**Download updates while installing Ubuntu** option.
4. Then, pick the**Erase disk and install Ubuntu** option and click on the**Install Now** button.
5. Select your geographical location and enter your username and password. Then, click on the**Continue** button.
6. Wait for the installation to complete. It may take longer if you have a SATA HDD installed on your system.
7. The installer will prompt you to restart the system. Click on the**Restart Now** button.  
![Ubuntu Virtual Machine Running Using Hyper-V](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/ubuntu-virtual-machine-running-using-hyper-v.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144308/7443" target="_top" id="2144308">
  <img src="//a.impactradius-go.com/display-ad/7443-2144308" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144308/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The virtual machine will boot to the Ubuntu desktop. You can use Ubuntu and notice that the system runs fine inside Hyper-V just like it does on any other virtualization software.

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
<li><a href="https://youtube-lab.techidaily.com/024-approved-turn-your-youtube-shorts-into-a-stream-of-income/"><u>[New] 2024 Approved Turn Your YouTube Shorts Into a Stream of Income</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-easy-passes-to-friends-tiktok-live-events/"><u>[New] Easy Passes to Friends' TikTok Live Events</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-in-2024-effortless-creative-ending-videos-at-zero-price/"><u>[New] In 2024, Effortless Creative Ending Videos at Zero Price</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-revolutionizing-content-creation-the-future-of-live-video-on-facebook/"><u>[New] In 2024, Revolutionizing Content Creation The Future of Live Video on Facebook</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-mastering-full-circle-clips-iphone-filming-tips/"><u>[Updated] Mastering Full-Circle Clips IPhone Filming Tips</u></a></li>
<li><a href="https://win11.techidaily.com/creating-a-fixed-file-disposal-area-on-your-windows-desktop/"><u>Creating a Fixed File Disposal Area on Your Windows Desktop</u></a></li>
<li><a href="https://tech-haven.techidaily.com/effective-techniques-for-reducing-the-size-of-your-audio-recordings-using-windows-11-tools/"><u>Effective Techniques for Reducing the Size of Your Audio Recordings Using Windows 11 Tools</u></a></li>
<li><a href="https://win11.techidaily.com/essential-knowledge-using-windows-canary-channels/"><u>Essential Knowledge: Using Windows Canary Channels</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-steam-unable-to-connect-files-on-pc/"><u>Fixes for Steam Unable to Connect Files on PC</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-creating-ken-burns-transitions-in-camtasia-9-a-step-by-step-guide/"><u>In 2024, Creating Ken Burns Transitions in Camtasia 9 A Step-by-Step Guide</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-the-ultimate-guide-to-effective-screen-recorders/"><u>In 2024, The Ultimate Guide to Effective Screen Recorders</u></a></li>
<li><a href="https://win11.techidaily.com/instructions-for-installing-intel-ethernet-drivers/"><u>Instructions for Installing Intel Ethernet Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-initialization-delays-in-wow-patch/"><u>Overcoming Initialization Delays in WoW Patch</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-non-selectable-components-on-win11-screen/"><u>Overcoming Non-Selectable Components on Win11 Screen</u></a></li>
<li><a href="https://win11.techidaily.com/solving-microsoft-store-issue-x80073d26-in-win11/"><u>Solving Microsoft Store Issue X:80073d26 in Win11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/step-by-step-tutorial-on-leveraging-videoproc-for-efficient-media-manipulation/"><u>Step-by-Step Tutorial on Leveraging VideoProc for Efficient Media Manipulation</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-the-challenges-of-office-activation-errors/"><u>Tackling the Challenges of Office Activation Errors</u></a></li>
<li><a href="https://win11.techidaily.com/the-role-and-safety-implications-of-windows-process-aggregatorhostexe/"><u>The Role and Safety Implications of Windows Process AggregatorHost.exe</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-vivo-y27-4g-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Vivo Y27 4G Location | Dr.fone</u></a></li>
</ul></div>

