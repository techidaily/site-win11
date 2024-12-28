---
title: Integrating Linux Into Hyper-V on Windows Systems
date: 2024-12-26T23:07:32.465Z
updated: 2024-12-28T00:27:06.412Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Integrating Linux Into Hyper-V on Windows Systems
excerpt: This Article Describes Integrating Linux Into Hyper-V on Windows Systems
keywords: Linux & Hyper-V Integration,Linux VM on Windows,Hyper-V for Linux Servers,Virtualizing Linux,Hyper-V Linux Hosting,Windows + Linux Hybrid,Linux in Hyper-V Setup
thumbnail: https://thmb.techidaily.com/f5381cefae4db3e611ab844891c6d979a90ee4ce440fddff39e8b37de541c533.jpg
---

## Integrating Linux Into Hyper-V on Windows Systems

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

### 3\. Create a Linux Virtual Machine Using Hyper-V

 The last piece of the puzzle is to create a Linux virtual machine inside the Windows virtual machine using Hyper-V. You can pick any Linux distribution that you want. We will go with Ubuntu for this experiment. You have to download the Ubuntu ISO file inside the virtual machine from the[Ubuntu website](https://ubuntu.com/download/desktop) before starting with the steps.

To create an Ubuntu virtual machine, do as follows:

1. Boot up the Windows virtual machine. Press the**Win key** and type Hyper-V manager. Launch the app.
2. Navigate to the right-hand side section and click on**New > Virtual Machine** .  
![Create a Linux Virtual Machine Using Hyper-V 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-1.jpg)
3. Click on the**Next** button. Enter the name of the virtual machine and click on**Next** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4. Click on the**Generation 1** radio button and click on Next.
5. Keep the**Startup Memory** as**2GB** and enable the**Use Dynamic memory for this virtual machine** option.  
![Create a Linux Virtual Machine Using Hyper-V 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-2.jpg)
6. Then, click on**Next** button and select the**Default switch** option in the Configure Networking section.

7. Click on the**Create a virtual hard disk** option and allocate**20GB** to the virtual hard disk. Move to the next section.  
![Create a Linux Virtual Machine Using Hyper-V 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/create-a-linux-virtual-machine-using-hyper-v-3.jpg)
8. Pick the**Install an operating system from a bootable CD/DVD-ROM** option located under the Installation options section. Select the Ubuntu Image file (.iso) you downloaded before beginning this step.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The virtual machine will boot to the Ubuntu desktop. You can use Ubuntu and notice that the system runs fine inside Hyper-V just like it does on any other virtualization software.

## A Few Things to Remember

 Creating a virtual machine inside a virtual machine is possible. But you have to remember that the underlying configuration of the host system must be such that it can run a virtual machine inside a virtual machine without any issue. If you attempt this experiment on a low-end system with 4GB RAM and a dual-core processor, it will choke the system.

 So, you need to use a system that can devote ample hardware resources to the Windows virtual machine. Only, then you would be able to use Hyper-V and create a Linux virtual machine and allocate run it without any issues. After you try our Ubuntu using Hyper-V, you can power off the virtual machine. Or you can take the extra step and delete the virtual machine from Hyper-V Manager. It will free up a lot of space inside the Windows virtual machine.

 Also, uninstall the Hyper-V feature if you don’t need it any further in your Windows virtual machine. Check out our guide on[how to disable or remove Hyper-V in Windows 11](https://www.makeuseof.com/windows-11-disable-hyper-v/) for more information.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-tips.techidaily.com/new-up-to-date-tips-for-purchasing-top-360-imagers/"><u>[New] Up-to-Date Tips for Purchasing Top 360 Imagers</u></a></li>
<li><a href="https://solve-info.techidaily.com/1-how-to-perform-driver-updates-on-windows-step-by-step-guide-by-yl-computing/"><u>1. How to Perform Driver Updates on Windows - Step-by-Step Guide by YL Computing</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-public-assessment-of-vllo-functionality/"><u>2024 Approved Public Assessment of VLLO Functionality</u></a></li>
<li><a href="https://win11.techidaily.com/compiling-a-winning-selection-of-torrenting-apps/"><u>Compiling a Winning Selection of Torrenting Apps</u></a></li>
<li><a href="https://win11.techidaily.com/deciphers-overcoming-the-common-steam-error-in-games-on-win-11/"><u>Deciphers: Overcoming the Common Steam Error in Games on Win 11</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-advanced-airpods-pro-4-by-apple-now-equipped-with-locate-my-earbuds-function-and-modernized-usb-c-power-connection-insights-revealed/"><u>Discover the Advanced AirPods Pro 4 by Apple, Now Equipped with 'Locate My Earbuds' Function and Modernized USB-C Power Connection – Insights Revealed</u></a></li>
<li><a href="https://win11.techidaily.com/evaluating-video-codecs-making-an-informed-decision-on-windows/"><u>Evaluating Video Codecs: Making an Informed Decision on Windows</u></a></li>
<li><a href="https://discover-exceptional.techidaily.com/guide-simple-pour-passer-windows-server-2019-vers-la-derniere-version-windows-server-2022/"><u>Guide Simple Pour Passer Windows Server 201^9 Vers La Dernière Version, Windows Server 202^2</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-eradicating-windows-11-upgrade-errors-on-pcs/"><u>Guide to Eradicating Windows 11 Upgrade Errors on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-cure-corrupted-files-issue-error-code-0x80070570-in-windows-11-os/"><u>How to Cure Corrupted Files Issue (Error Code 0X80070570) in Windows 11 OS</u></a></li>
<li><a href="https://extra-hints.techidaily.com/how-to-ensure-the-best-live-experience-with-top-networks/"><u>How to Ensure the Best Live Experience with Top Networks</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-lava-yuva-3-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Hassle-Free Solutions to Fake Location on Find My Friends Of Lava Yuva 3 Pro | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-mastering-vimeo-video-editing-top-5-techniques-for-cuts-and-trimming/"><u>In 2024, Mastering Vimeo Video Editing Top 5 Techniques for Cuts & Trimming</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-two-ways-to-track-my-boyfriends-oppo-f25-pro-5g-without-him-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Two Ways to Track My Boyfriends Oppo F25 Pro 5G without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/october-launch-apple-postpones-introduction-of-smart-ai-capabilities-insights/"><u>October Launch: Apple Postpones Introduction of Smart AI Capabilities, Insights</u></a></li>
<li><a href="https://win11.techidaily.com/proactive-windows-care-self-updates-plus-gpu-switching-routine/"><u>Proactive Windows Care: Self-Updates + GPU Switching Routine</u></a></li>
<li><a href="https://win11.techidaily.com/procedures-to-thwart-insider-build-leaks/"><u>Procedures to Thwart Insider Build Leaks</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionizing-phone-integration-on-windows-11-platforms/"><u>Revolutionizing Phone Integration on Windows 11 Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-lost-wi-fi-win-ethernet-woes/"><u>Troubleshooting Lost Wi-Fi: Win Ethernet Woes</u></a></li>
</ul></div>

