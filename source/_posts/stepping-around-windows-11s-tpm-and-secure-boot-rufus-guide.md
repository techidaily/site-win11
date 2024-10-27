---
title: "Stepping Around Windows 11'S TPM & Secure Boot: Rufus Guide"
date: 2024-10-25T05:49:17.261Z
updated: 2024-10-26T18:27:04.669Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Stepping Around Windows 11'S TPM & Secure Boot: Rufus Guide"
excerpt: "This Article Describes Stepping Around Windows 11'S TPM & Secure Boot: Rufus Guide"
keywords: Windows 11 Security (TPM),Secure Boot Explained,Rufus for TPM,Secure Boot Setup,TPM in Windows 11,Rufus TPM Guide,TPM & Secure Boot Installation
thumbnail: https://thmb.techidaily.com/cb7e01d77e11396989975642eff6b3a0f5621896796311364cd34b031c122e69.jpg
---

## Stepping Around Windows 11'S TPM & Secure Boot: Rufus Guide

 Windows 11 still has the minimum requirement of TPM 2.0 and Secure Boot to run on any operating system. After it launched, enthusiasts quickly discovered a registry hack to bypass both of these requirements and install the operating system without any difficulty.

 There are even tweaked ISO files of Windows 11 available which bypasses both requirements before installation. However, Rufus has a better solution. It can help you prepare a Windows installation media while bypassing these requirements and adding more tweaks. Want to know more? Let’s begin.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why Is Rufus the Tool for the Job?

 In Rufus version 3.2 and above, you can create a tweaked Windows 11 bootable media. The main attraction is that it can remove the 4GB RAM, TPM 2.0, and Secure Boot requirements while creating the bootable USB drive.

 Apart from that, it can also remove the infuriating requirement of signing in using a Microsoft Account before setting up your Windows 11 PC. These two requirements deter a lot of users from trying out Windows 11, but Rufus can now bypass both of these. All you need to do is configure Rufus to create a bootable USB drive.

 Apart from these two tweaks, Rufus can also speed up the installation process by avoiding the setup pages for tracking, [disabling BitLocker encryption](https://www.makeuseof.com/windows-10-disable-or-suspend-bitlocker/), and settings the same language and region options as the computer you are using to create a bootable USB drive. So, you can prepare a Windows 11 bootable drive that takes less time to install and set up on a new system.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134498/18498" target="_top" id="2134498">
  <img src="//a.impactradius-go.com/display-ad/18498-2134498" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134498/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2043639/7443" target="_top" id="2043639">
  <img src="//a.impactradius-go.com/display-ad/7443-2043639" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043639/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Navigate to the bottom of Rufus' window and click on the **Start** button.
2. A Windows User Experience box will open. Here, you can apply all the customizations you want to the Windows 11 bootable USB drive. Click on the checkbox in front of the **Remove requirement for 4GB+ RAM, Secure Boot, and TPM 2.0** option.
3. Similarly, select the **Remove requirement for an online Microsoft account** checkbox and **Disable data collection (Skip privacy questions)** checkbox.  
![Create a Bootable USB Drive Using Rufus 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/create-a-bootable-usb-drive-using-rufus-2.jpg)
4. Click on the **OK** button. Rufus will generate a warning about deleting all data on the USB drive.  

![Create a Bootable USB Drive Using Rufus 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/create-a-bootable-usb-drive-using-rufus-3.jpg)
5. Lastly, click on the **OK** button and wait for Rufus to create the bootable Windows 11 USB drive. Eject the drive after you see a “**Ready**” message.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134244/18498" target="_top" id="2134244">
  <img src="//a.impactradius-go.com/display-ad/18498-2134244" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134244/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Install the Modified Windows 11 on Your System

 Repeat the following steps to install Windows 11 while bypassing its system requirements:

1. Plug the bootable USB drive you created with Rufus into the target system. Press the designated F-key repeatedly (F10, F12, F2, or Esc) to enter the boot devices menu.
2. Select the USB drive from the list using the arrow keys and press the **Enter** key to boot.
3. Select the language and region and click on the **Next** button. Then, click on the **Install now** button.  
![Install the Modified Windows 11 on Your System](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-the-modified-windows-11-on-your-system.jpg)
4. Click on the **I don’t have the product key** option.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036496/19272" target="_top" id="2036496">
  <img src="//a.impactradius-go.com/display-ad/19272-2036496" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036496/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Install the Modified Windows 11 on Your System 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-the-modified-windows-11-on-your-system-2.jpg)
5. Select the version of Windows 11 you want to install (Home, Pro, Enterprise, or Education) and click on **Next**.  
![Install the Modified Windows 11 on Your System 3](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-the-modified-windows-11-on-your-system-3.jpg)

1. Accept the EULA and click on the **Next** button. Then, click on the **Custom** option.
2. Pick the drive where you want to install Windows 11\. Click on the **Format** button to format the drive and click on **Next**.
3. The setup will begin installing Windows 11 automatically. However, if TPM and Secure Boot bypass weren’t in place, you would never make it past the Enter product key page.  
![Install the Modified Windows 11 on Your System 4](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-the-modified-windows-11-on-your-system-4.jpg)
4. Your system will restart a few times and then boot to the Windows 11 setup page. Disconnect your system from the internet otherwise, it will attempt to check and download updates which can take a long time.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136623/26400" target="_top" id="2136623">
  <img src="//a.impactradius-go.com/display-ad/26400-2136623" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136623/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Enter your **Name** and select **three security questions** and their answers as well. Click on **Next**.  
![Install the Modified Windows 11 on Your System 5](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/install-the-modified-windows-11-on-your-system-5.jpg)
6. Windows will prepare your system for the first boot. After a short while you will boot to the desktop.  
![Windows 11 up and running on an unsupported system](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/windows-11-up-and-running-on-an-unsupported-system.jpg)

## Benefits of Using Rufus to Create a Custom Windows 11 Installation Media

 Rufus isn’t just a means to bypass the Windows 11 stern requirements on an unsupported system. It can also help you avoid the excessively long route Windows 11 setup forces you to take while installing the operating system. Forcing users to sign up or sign in using a Microsoft Account, downloading and installing updates, and not allowing them to [proceed with a Windows installation without an internet connection](https://www.makeuseof.com/windows-11-set-up-without-internet-connection/) end up ruining the user experience.

 Moreover, confusing privacy and tracking settings take up a whole page. You need to disable the six-eight toggles to opt out of it and have to deal with pop-ups like Microsoft 365 and Xbox GamePass.

 But you can avoid all these things by selecting the **Disable data collection (Skip privacy questions)** checkbox in Rufus. If you want to keep the PC name and region settings on the target system the same as your primary system, you can select the **Set regional options to the same values as this user’s** and **Create a local account with username** checkboxes.

 However, you will need to set up a new PIN if you plan to inherit the same username and region options as your main Windows computer. Otherwise, you won’t be able to log in.

## A Frictionless Windows 11 Installation With Rufus

 Rufus can help you create a custom Windows 11 bootable drive that bypasses all the unnecessary requirements and setup pages. It is much better than using a tweaked ISO file with questionable security. Plus you don’t have to pay a dime because Rufus is completely open-source.

 There are even tweaked ISO files of Windows 11 available which bypasses both requirements before installation. However, Rufus has a better solution. It can help you prepare a Windows installation media while bypassing these requirements and adding more tweaks. Want to know more? Let’s begin.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://article-tips.techidaily.com/new-discover-the-leading-15-cost-effective-online-photo-editors-2023-for-2024/"><u>[New] Discover the Leading 15 Cost-Effective Online Photo Editors, 2023 for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-the-art-of-capture-and-storage-managing-snapshots-like-a-pro/"><u>[New] In 2024, The Art of Capture and Storage Managing Snapshots Like a Pro</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-virtual-reality-top-emulators-for-playing-ps3-games-on-pc/"><u>[New] In 2024, Virtual Reality Top Emulators for Playing PS3 Games on PC</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-frontier-visionaries-merging-media-triad/"><u>[Updated] Frontier Visionaries Merging Media Triad</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-bringing-sketches-to-life-foremost-ipados-apps/"><u>2024 Approved Bringing Sketches to Life Foremost iPadOS Apps</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/advanced-techniques-for-professional-mac-burned-discs-for-2024/"><u>Advanced Techniques for Professional Mac-Burned Discs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-guide-to-user-management-in-windows-cmd/"><u>Comprehensive Guide to User Management in Windows CMD</u></a></li>
<li><a href="https://fox-where.techidaily.com/how-to-recover-past-conversations-on-wechat-reinstate-or-clear-your-chats-easily/"><u>How to Recover Past Conversations on WeChat: Reinstate or Clear Your Chats Easily</u></a></li>
<li><a href="https://program-issues.techidaily.com/master-level-tips-to-keep-maplestory-running-without-a-hitch-on-your-windows-11-pc/"><u>Master Level Tips to Keep MapleStory Running Without a Hitch on Your Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-resolution-of-unpredicted-error-messages/"><u>Mastering the Resolution of Unpredicted Error Messages</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-win11s-cursor-anomalies-a-decades-insight/"><u>Mastering Win11's Cursor Anomalies: A Decade's Insight</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-without-automation-time-zone-fixes-for-windows/"><u>Navigate Without Automation: Time Zone Fixes for Windows</u></a></li>
<li><a href="https://extra-hints.techidaily.com/navigating-win11-a-detailed-look-at-zoom-functions/"><u>Navigating Win11 A Detailed Look at Zoom Functions</u></a></li>
<li><a href="https://win11.techidaily.com/redefining-your-desktop-with-dynamic-backgrounds/"><u>Redefining Your Desktop with Dynamic Backgrounds</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-lost-steam-games-images-in-windows/"><u>Restoring Lost Steam Games Images in Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/rgbs-role-in-modern-color-standards-compared-to-srgb-for-2024/"><u>Rgb's Role in Modern Color Standards Compared to Srgb for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/six-secrets-to-temporarily-halt-updates-on-your-pc/"><u>Six Secrets to Temporarily Halt Updates on Your PC</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-immediate-reopening-of-battlenet-interface/"><u>Strategies for Immediate Reopening of Battle.net Interface</u></a></li>
<li><a href="https://win11.techidaily.com/three-approaches-to-test-windows-11-activation/"><u>Three Approaches to Test Windows 11 Activation</u></a></li>
</ul></div>

