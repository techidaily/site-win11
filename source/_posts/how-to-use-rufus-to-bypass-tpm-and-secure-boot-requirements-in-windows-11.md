---
title: How to Use Rufus to Bypass TPM and Secure Boot Requirements in Windows 11
date: 2024-11-26T16:03:32.164Z
updated: 2024-11-28T01:44:38.266Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Use Rufus to Bypass TPM and Secure Boot Requirements in Windows 11
excerpt: This Article Describes How to Use Rufus to Bypass TPM and Secure Boot Requirements in Windows 11
keywords: Rufus TPM Bypass,TPM Security Bypass,Secure Boot Circuitry,Bypassing UEFI Locks,Windows 11 TPM Bypass,Rufus UEFI Bypass Tool,Disabling TPM Windows 11
thumbnail: https://thmb.techidaily.com/289e1b59f873ec0dc8305b0281292ab73fb1d9fdd29063def94d2427e3383ad3.jpg
---

## How to Use Rufus to Bypass TPM and Secure Boot Requirements in Windows 11

 Windows 11 still has the minimum requirement of TPM 2.0 and Secure Boot to run on any operating system. After it launched, enthusiasts quickly discovered a registry hack to bypass both of these requirements and install the operating system without any difficulty.

 There are even tweaked ISO files of Windows 11 available which bypasses both requirements before installation. However, Rufus has a better solution. It can help you prepare a Windows installation media while bypassing these requirements and adding more tweaks. Want to know more? Let’s begin.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Why Is Rufus the Tool for the Job?

 In Rufus version 3.2 and above, you can create a tweaked Windows 11 bootable media. The main attraction is that it can remove the 4GB RAM, TPM 2.0, and Secure Boot requirements while creating the bootable USB drive.

 Apart from that, it can also remove the infuriating requirement of signing in using a Microsoft Account before setting up your Windows 11 PC. These two requirements deter a lot of users from trying out Windows 11, but Rufus can now bypass both of these. All you need to do is configure Rufus to create a bootable USB drive.

 Apart from these two tweaks, Rufus can also speed up the installation process by avoiding the setup pages for tracking, [disabling BitLocker encryption](https://www.makeuseof.com/windows-10-disable-or-suspend-bitlocker/), and settings the same language and region options as the computer you are using to create a bootable USB drive. So, you can prepare a Windows 11 bootable drive that takes less time to install and set up on a new system.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Create a Bootable USB Drive Which Bypasses Windows 11 Requirements Using Rufus

 Firstly, you need to [download the latest version of Rufus](https://rufus.ie/). It is available on Microsoft Store, GitHub and even has an official website where they post the details about new and upcoming releases. We suggest you download the portable version of Rufus to avoid the installation process altogether. You will also need the latest version of the Windows 11 ISO image file. Visit the official Microsoft webpage and [download the ISO file](https://www.microsoft.com/en-in/software-download/windows11) from there.

 After downloading the portable version of Rufus, repeat the following steps:

1. Go to the downloads folder and double-click on Rufus to run the tool.
2. **UAC** will pop up. Click on the **Yes** button to continue.
3. Insert a USB drive into your Windows 11 system. Ensure that the USB drive has a capacity of 8 GB or more. Rufus will automatically recognize the USB drive.
4. Click on the **Select** button in the **Boot selection** section. **Browse** your computer for the ISO file and select it.
5. Next, click on the **Partition scheme** option. Select **MBR** if you want to use this USB drive on a system with BIOS or UEFI. Leave the Target system and Partition scheme untouched if you plan to use this bootable USB drive on a UEFI system.  
![Create a Bootable USB Drive Using Rufus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/create-a-bootable-usb-drive-using-rufus.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

1. Navigate to the bottom of Rufus' window and click on the **Start** button.
2. A Windows User Experience box will open. Here, you can apply all the customizations you want to the Windows 11 bootable USB drive. Click on the checkbox in front of the **Remove requirement for 4GB+ RAM, Secure Boot, and TPM 2.0** option.
3. Similarly, select the **Remove requirement for an online Microsoft account** checkbox and **Disable data collection (Skip privacy questions)** checkbox.  
![Create a Bootable USB Drive Using Rufus 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/create-a-bootable-usb-drive-using-rufus-2.jpg)
4. Click on the **OK** button. Rufus will generate a warning about deleting all data on the USB drive.  
![Create a Bootable USB Drive Using Rufus 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/create-a-bootable-usb-drive-using-rufus-3.jpg)
5. Lastly, click on the **OK** button and wait for Rufus to create the bootable Windows 11 USB drive. Eject the drive after you see a “**Ready**” message.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Install the Modified Windows 11 on Your System

 Repeat the following steps to install Windows 11 while bypassing its system requirements:

1. Plug the bootable USB drive you created with Rufus into the target system. Press the designated F-key repeatedly (F10, F12, F2, or Esc) to enter the boot devices menu.
2. Select the USB drive from the list using the arrow keys and press the **Enter** key to boot.
3. Select the language and region and click on the **Next** button. Then, click on the **Install now** button.  
![Install the Modified Windows 11 on Your System](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-the-modified-windows-11-on-your-system.jpg)
4. Click on the **I don’t have the product key** option.  
![Install the Modified Windows 11 on Your System 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-the-modified-windows-11-on-your-system-2.jpg)
5. Select the version of Windows 11 you want to install (Home, Pro, Enterprise, or Education) and click on **Next**.  
![Install the Modified Windows 11 on Your System 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-the-modified-windows-11-on-your-system-3.jpg)

1. Accept the EULA and click on the **Next** button. Then, click on the **Custom** option.
2. Pick the drive where you want to install Windows 11\. Click on the **Format** button to format the drive and click on **Next**.
3. The setup will begin installing Windows 11 automatically. However, if TPM and Secure Boot bypass weren’t in place, you would never make it past the Enter product key page.  
![Install the Modified Windows 11 on Your System 4](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-the-modified-windows-11-on-your-system-4.jpg)
4. Your system will restart a few times and then boot to the Windows 11 setup page. Disconnect your system from the internet otherwise, it will attempt to check and download updates which can take a long time.
5. Enter your **Name** and select **three security questions** and their answers as well. Click on **Next**.  
![Install the Modified Windows 11 on Your System 5](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-the-modified-windows-11-on-your-system-5.jpg)
6. Windows will prepare your system for the first boot. After a short while you will boot to the desktop.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Windows 11 up and running on an unsupported system](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-11-up-and-running-on-an-unsupported-system.jpg)

## Benefits of Using Rufus to Create a Custom Windows 11 Installation Media

 Rufus isn’t just a means to bypass the Windows 11 stern requirements on an unsupported system. It can also help you avoid the excessively long route Windows 11 setup forces you to take while installing the operating system. Forcing users to sign up or sign in using a Microsoft Account, downloading and installing updates, and not allowing them to [proceed with a Windows installation without an internet connection](https://www.makeuseof.com/windows-11-set-up-without-internet-connection/) end up ruining the user experience.

 Moreover, confusing privacy and tracking settings take up a whole page. You need to disable the six-eight toggles to opt out of it and have to deal with pop-ups like Microsoft 365 and Xbox GamePass.

 But you can avoid all these things by selecting the **Disable data collection (Skip privacy questions)** checkbox in Rufus. If you want to keep the PC name and region settings on the target system the same as your primary system, you can select the **Set regional options to the same values as this user’s** and **Create a local account with username** checkboxes.

 However, you will need to set up a new PIN if you plan to inherit the same username and region options as your main Windows computer. Otherwise, you won’t be able to log in.

## A Frictionless Windows 11 Installation With Rufus

 Rufus can help you create a custom Windows 11 bootable drive that bypasses all the unnecessary requirements and setup pages. It is much better than using a tweaked ISO file with questionable security. Plus you don’t have to pay a dime because Rufus is completely open-source.

 There are even tweaked ISO files of Windows 11 available which bypasses both requirements before installation. However, Rufus has a better solution. It can help you prepare a Windows installation media while bypassing these requirements and adding more tweaks. Want to know more? Let’s begin.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-innovative-ways-to-archive-voice-transcripts-from-whatsapp/"><u>[New] 2024 Approved Innovative Ways to Archive Voice Transcripts From WhatsApp</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-scrutinizing-vlc-for-video-capturing/"><u>[Updated] Scrutinizing VLC for Video Capturing</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-what-separates-full-immersion-from-panoramic-videos-in-2024/"><u>[Updated] What Separates Full Immersion From Panoramic Videos, In 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/crafting-charm-in-tiktok-videos-for-2024/"><u>Crafting Charm in TikTok Videos for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/diving-into-the-interface-of-magix-music-maker-2024/"><u>Diving Into the Interface of Magix Music Maker 2024</u></a></li>
<li><a href="https://win11.techidaily.com/do-your-windows-settings-reset-to-default-on-reboot-try-these-fixes/"><u>Do Your Windows Settings Reset to Default on Reboot? Try These Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-multitasking-through-90-degree-display-rotation/"><u>Efficient Multitasking Through 90-Degree Display Rotation</u></a></li>
<li><a href="https://win11.techidaily.com/eight-slips-new-users-shouldnt-fall-into-with-windows-11/"><u>Eight Slips New Users Shouldn't Fall Into With Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-problematic-code-0x00000001-a-guide-to-xbox-game-pass-fixes-on-windows-11/"><u>Eliminating Problematic Code 0X00000001: A Guide to Xbox Game Pass Fixes on Windows 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-honor-x9b-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Honor X9b</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-trouble-with-apple-iphone-6-plus-swipe-up-try-these-11-solutions-drfone-by-drfone-ios/"><u>In 2024, Trouble with Apple iPhone 6 Plus Swipe-Up? Try These 11 Solutions | Dr.fone</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/in-depth-tcl-32s325-roku-smart-led-tv-2019-a-comprehensive-performance-review/"><u>In-Depth TCL 32S325 Roku Smart LED TV (2019): A Comprehensive Performance Review</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-fix-for-media-server-collapse/"><u>Mastering the Fix for Media Server Collapse</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-globally-advanced-mouse-techniques-in-powertoys/"><u>Navigating Globally: Advanced Mouse Techniques in PowerToys</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-updater-glitch-code-0x80073712/"><u>Quick Fixes for Updater Glitch: Code 0X80073712</u></a></li>
<li><a href="https://win11.techidaily.com/swift-solutions-for-win-rpc-errors-a-quick-guide/"><u>Swift Solutions for Win RPC Errors - A Quick Guide</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-ranking-virtual-reality-headsets-ideal-choices-for-gamers-and-pc-users/"><u>Top-Ranking Virtual Reality Headsets: Ideal Choices for Gamers and PC Users</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    