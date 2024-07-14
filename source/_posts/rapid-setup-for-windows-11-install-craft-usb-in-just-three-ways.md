---
title: "Rapid Setup for Windows 11 Install: Craft USB in Just Three Ways"
date: 2024-07-13T10:40:43.616Z
updated: 2024-07-14T10:40:43.616Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Rapid Setup for Windows 11 Install: Craft USB in Just Three Ways"
excerpt: "This Article Describes Rapid Setup for Windows 11 Install: Craft USB in Just Three Ways"
keywords: Win11 Quick Prep,Speedy Win11 Creation,Rapid Win11 Bootable,Easy Windows 11 USB,Quick Install Setup Win11,Faster Windows 11 USB,Simple Win11 Provisioning
thumbnail: https://thmb.techidaily.com/207578e24a0a184b7539ba9edecf41bf44046bb6668830fc6d1ed96db57dfa6c.png
---

## Rapid Setup for Windows 11 Install: Craft USB in Just Three Ways

 A Windows 11 bootable USB drive is useful to clean install your OS, or perform an upgrade. A bootable Windows USB also helps you troubleshoot your PC from critical errors and install Windows on multiple PCs offline.

 Microsoft makes it easy to create an installation media with its Media Creation Tool. In addition, you can also use Rufus and the Command Prompt to create one. In this guide, we show you the three different ways to create a USB flash drive installer for Windows 11\.

## Before We Start: How to Download the Windows 11 ISO Image

 To successfully create a Windows 11 USB bootable drive, you will need a Windows 11 ISO file, also known as an [ISO image](https://www.makeuseof.com/what-is-iso/). As such, get this sorted before you proceed to create a bootable USB. You can easily [download the Windows 11 ISO](https://www.makeuseof.com/windows-11-download-iso/) from the Microsoft official website. Here's how to do it:

1. Visit [Microsoft’s official page](https://www.microsoft.com/software-download/windows11) to download Windows 11\.
2. Scroll down to the **Download Windows 11 Disk Image (ISO) for X64 devices** section.
3. Click the drop-down menu and select **Windows 11 (multi-edition ISO)**.  
![download windows 11 iso](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/download-windows-11-iso.jpg)
4. Next, click on the **Download** **Now** button to continue.
5. The current page will load additional information and show the **Select the product language** section. Click the drop-down for **Choose one** and select your preferred language. Click **Confirm** to continue.  
![download windows 11 iso choose language](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/download-windows-11-iso-choose-language.jpg)
6. When the download section loads, click the **64-bit Download** button.  
![download windows 11 iso 64 bit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/download-windows-11-iso-64-bit.jpg)
7. Your download will begin immediately. However, it may take some time to finish downloading, depending on your Internet speed.

 Once you have the ISO file downloaded, follow one of the methods below to create a Windows 11 bootable USB drive.

## 1\. How to Create a Windows 11 Bootable USB Using Rufus

![create windows 11 bootable usb drive with rufus](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/create-windows-11-bootable-usb-drive-with-rufus.png)

 Rufus is an open-source utility to format and create a bootable USB flash drive for the Windows operating system. It's a lightweight utility and offers a few more customization options compared to Microsoft's in-house media creation tool.

 To create a Windows 11 bootable USB drive using Rufus:

1. Visit the [Rufus website](https://rufus.ie/en/) and scroll down to the **Download** section.
2. Click on the **Rufus link** to download the latest version.
3. Run the executable file and click **Yes** if prompted by UAC.
4. Connect your USB flash drive to your PC and wait for Rufus to detect and show it under the **Device** section.
5. Click the drop-down for **Boot selection** and select **Disk or ISO image.**

1. Then, click the **SELECT** button.
2. Select the **Windows ISO** file and click **Open**.
3. Click the drop-down under the **Image option** and select **Standard Windows 11 Installation**.
4. Leave the **Partition scheme (GPT)** and **Target system (UEFI)** as default.
5. Under **Volume label**, enter a name for your bootable flash drive.
6. Leave the **File system** and **Cluster size,** and other options as default.
7. Make sure the **Quick format** and **Create extended label and icon files** option is checked.
8. Click the **Start** button to initiate the bootable drive creating process.

 Once done, Rufus will show a success message. Now you can use the [Windows 11 bootable drive to install the OS](http://www.makeuseof.com/how-to-clean-install-windows-11/) on any compatible system.

## 2\. How to Create a Windows 11 Bootable USB Drive Using the Media Creation Tool

 The media creation tool is Microsoft's in-house solution to create an installation media. You can use the media creation tool to create a bootable USB flash drive or download the ISO file to your local drive. Since it needs to download the ISO to create a bootable drive, you cannot use an existing Windows ISO image with this tool.

 To create an installation media using the media creation tool:

1. Connect your USB flash drive of at least 8GB to your PC. Make sure it is detected and you have taken a backup of all the files on your USB drive.
2. Next, visit the [Microsoft download center](https://www.microsoft.com/software-download/windows11) page.
3. Under the **Create Windows 11 Installation Media** section, click the **Download Now** button and save the file to your PC.
4. Next, run the **Mediacreationtool.exe** file and click **Yes** if prompted by UAC. The tool may take a few seconds to launch, so wait till you see the **Setup wizard.**
5. Click the **Accept button** to agree to the terms.  
![select language and edition Create bootable drive windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/select-langugae-and-edition.png)

1. The media creation tool will automatically select the **Edition** and **Language** to match the current Windows configuration on your PC. To change the language, uncheck **Use the recommended options for this PC** box and select your preferred language from the drop-down menu.
2. Choose your options and click **Next**.  
![choose which media to use Media Creation Tool Bootable Drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/choose-which-media-to-use.png)
3. In the **Choose which media to use** window, select **USB flash** drive.
4. Click the **Next** button.
5. Select your USB drive from the list of drives available.  
![select a usb drive media creation tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/select-a-usb-drive.png)
6. Click the **Next** button to continue.
7. Next, click the **Finish** button.

 Media Creation Tool will now download the necessary Windows 11 files and create an installation media. When the "your USB flash drive is ready" message appears, click the **Finish** button to close the setup wizard. Now you can boot from the USB drive to troubleshoot or [clean install Windows 11](https://www.makeuseof.com/how-to-clean-install-windows-11/).

## 3\. How to Create a Bootable Drive Using Command Prompt

 If you don’t want to use a third-party tool to create a bootable drive, you can use the Diskpart utility and Command Prompt to create installation media. Here's how to do it.

1. First, take a backup of all the files on your USB drive and then connect it to your PC.
2. Press the **Win** key, type cmd, **and** click on **Run as Administrator** under **Command Prompt.** You can also use PowerShell if you prefer it over Command Prompt.  
![disk part windows 11 bootable drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/disk-part-windows-11-bootable-drive.png)
3. In the Command Prompt window, type the following command and hit enter to launch the **Windows Diskpart** utility.  
`DISKPART`
4. Next, type the following command to list all the available storage devices:  
`LIST DISK`
5. Here, locate your USB drive. You can look at the **Size column** to determine your USB drive. In this case, the USB drive is listed as **Disk 2.**

1. Next, type the following command to select your drive:  
`SEL DISK 2`
2. In the above command, change **DISK 2** with the number assigned to your USB drive. For example, if you have a single SSD or SATA drive setup, your primary drive will show as **DISK 0** and USB drive as **DISK 1**. It is of **extreme importance that you select the right drive** as the next step involves wiping clean the selected drive.
3. Once the drive is erased, type the following command and hit enter to erase all the content from the drive:  
`Clean`
4. Next, type the following command to create a primary partition:  
`Create Partition Primary`
5. After creating a primary partition, type the following command to select the main partition:  
`List Par`
6. Command Prompt will show the details of your USB drive.  
![format usb drive windows 11 cmd](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/format-usb-drive-windows-11-cmd.png)
7. Type the following command and hit enter to activate the partition:  
`Active`
8. Then type the following command to format the USB drive. It is important to format the drive in NTFS format as the [FAT32 format will cause the incorrect parameter error](https://www.makeuseof.com/windows-fix-parameter-is-incorrect-error/).  
`FORMAT FS=NTFS LABEL=&ldquo;BootableUSB&rdquo; QUICK OVERRIDE`
9. Once done, type **Exit** and hit enter to exit the Disk Part utility.

 Now you will need to mount the ISO image and then move its content to your USB drive.

![mount ISO image Windows 11 Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/mount-ISO-image-Windows-11-Command-Prompt.png)

1. To do this, type the following command and hit **Enter** to mount the Windows 11 ISO file:  
`PowerShell Mount-DiskImage -ImagePath "C:\Users\UserName\Downloads\Win11_English_x64v1.iso"`
2. In the above command, replace the file path with the location of your Windows 11 ISO.  
![cmd list volume](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/cmd-list-volume.png)
3. Once the ISO is mounted, type the following command to launch Diskpart.  
`Diskpart`
4. Next, type the following command to show the available volume.  
`List volume`
5. This will help you determine the Drive letter for the mounted ISO file. In the **Type column**, the mounted ISO will be listed as **DVD-ROM**. And the **Ltr column** lists the letter associated with the volume. Note down the details of the ISO volume as you will be using it moving forward.  
![list volume cmd windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/list-volume-cmd-windows-11.png)

1. Once you have the volume details for the mounted ISO, type the following command to exit Diskpart:  
`Exit`
2. Next, type the mounted ISO volume letter and hit enter. For example, if your mounted ISO volume letter is **J**, then type the following command and press Enter.  
`J:`
3. Type the following command to boot from CD:  
`cd boot`
4. Next, type the following command to apply the master boot code compatible with Bootmgr to the USB flash drive:  
`Bootsect /nt60 I:`
5. In the above command, replace **I** with the drive letter associated with your USB flash drive.  
![copy iso files to usb drive](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/copy-iso-files-to-usb-drive.png)
6. Next, type the following command and hit Enter to copy Windows 11 system files to the USB flash drive:  
`xcopy J:\*.* I:\ /E /F /H`
7. In the above command, replace **K:** and **I:** with your **Mounted ISO Volume** and **USB drive** letter, respectively.
8. The process may take a 5-10 minutes to complete. If the Command Prompt feels stuck, it is normal behaviour, so wait until the process is complete.
9. If successful, you will see a **Files (s) Copied** message.

 That’s it. Now you can use the USB bootable drive to clean install Windows 11\.

## Multiple Ways to Create a Windows 11 Bootable USB Drive

 With its Media Creation Tool, Microsoft makes it easy to create installaltion media. However, if you have a Windows 11 ISO image ready, you can use Rufus or the Command Prompt to create a Windows 11 bootable USB drive quickly. You can use the same to clean install Windows 11 on a new PC, troubleshoot your Windows computer or dual boot Windows 10 with Windows 11\.

 A Windows 11 bootable USB drive is useful to clean install your OS, or perform an upgrade. A bootable Windows USB also helps you troubleshoot your PC from critical errors and install Windows on multiple PCs offline.

 Microsoft makes it easy to create an installation media with its Media Creation Tool. In addition, you can also use Rufus and the Command Prompt to create one. In this guide, we show you the three different ways to create a USB flash drive installer for Windows 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-screen-lock-pin-on-meizu-21-like-a-pro-5-easy-ways-by-drfone-android/"><u>How To Remove Screen Lock PIN On Meizu 21 Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/failed-to-play-mov-movies-on-galaxy-m34-5g-by-aiseesoft-video-converter-play-mov-on-android/"><u>Failed to play MOV movies on Galaxy M34 5G</u></a></li>
<li><a href="https://win11.techidaily.com/8-strategies-to-solve-vmware-booting-woes-on-win11/"><u>8 Strategies to Solve VMware Booting Woes on Win11</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-permanently-quit-youtube-shorts-now/"><u>[New] Permanently Quit YouTube Shorts Now</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-global-giga-viewers-worlds-favorite-youtube-stars/"><u>[New] 2024 Approved  Global Giga-Viewers  World's Favorite YouTube Stars</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-reset-apple-id-and-apple-password-on-iphone-8-plus-by-drfone-ios/"><u>How to Reset Apple ID and Apple Password On iPhone 8 Plus</u></a></li>
<li><a href="https://win11.techidaily.com/a-complete-guide-on-using-w11s-automated-hdr-feature/"><u>A Complete Guide on Using W11's Automated HDR Feature</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-screenplay-genius-weaving-compelling-narratives-and-dialogues/"><u>In 2024, Screenplay Genius  Weaving Compelling Narratives and Dialogues</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/pro-photo-framegers-to-polish-pictures-online-for-2024/"><u>Pro Photo Framegers to Polish Pictures Online for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/reeling-in-tiktoks-challenge-is-reel-a-facebook-savior/"><u>Reeling in TikTok's Challenge: Is Reel a Facebook Savior?</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-approach-extracting-device-ids-from-windows-pcs/"><u>A Step-by-Step Approach: Extracting Device IDs From Windows PCs</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-apple-iphone-12-mini-drfone-by-drfone-virtual-ios/"><u>In 2024, Ways to stop parent tracking your Apple iPhone 12 mini | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/1719375739489-relaunch-google-chrome-on-win11-fixes-and-tips-here/"><u>Relaunch Google Chrome on Win11 – Fixes and Tips Here.</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/in-2024-how-to-generate-speech-from-text-the-best-text-to-speech-converters/"><u>In 2024, How To Generate Speech From Text | The Best Text-to-Speech Converters</u></a></li>
<li><a href="https://win11.techidaily.com/9-proven-remedies-for-perfectly-printing-your-powerpoint-presentations-in-windows/"><u>9 Proven Remedies for Perfectly Printing Your PowerPoint Presentations in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/1719347165719-restore-order-in-your-keyboard-chaos-with-these-9-fixes-for-broken-windows-shortcuts-and-combinations/"><u>Restore Order in Your Keyboard Chaos with These 9 Fixes for Broken Windows Shortcuts and Combinations.</u></a></li>
<li><a href="https://win11.techidaily.com/9-ways-to-fix-vmwares-failed-to-start-the-virtual-machine-error-in-windows-11/"><u>9 Ways to Fix VMware's Failed to Start the Virtual Machine Error in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719347016533-unlock-your-computers-print-command-solutions-for-faulty-wwinplusp-operations/"><u>Unlock Your Computer's Print Command: Solutions for Faulty WWin+P Operations.</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-neon-typography-made-easy-10-online-generators-to-try-now-for-2024/"><u>Updated Neon Typography Made Easy 10 Online Generators to Try Now for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-not-working-on-oppo-reno-10-5g-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Oppo Reno 10 5G? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/a-deeper-look-at-windows-11-efficiency-mastering-processes-and-customizing-themes/"><u>A Deeper Look at Windows 11 Efficiency: Mastering Processes and Customizing Themes</u></a></li>
<li><a href="https://win11.techidaily.com/a-closer-look-at-dxvks-impact-on-windows-gaming/"><u>A Closer Look at DXVK's Impact on Windows Gaming</u></a></li>
<li><a href="https://win11.techidaily.com/accelerated-action-overcoming-wwe-2k23-freezes-in-windows/"><u>Accelerated Action: Overcoming WWE 2K23 Freezes in Windows</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-how-to-record-audio-on-windows-10-5-easy-steps/"><u>In 2024, How to Record Audio on Windows 10 5 Easy Steps</u></a></li>
<li><a href="https://win11.techidaily.com/1719345925022-the-forgotten-tools-of-windows-11-dont-miss-them/"><u>The Forgotten Tools of Windows 11 - Don’t Miss Them</u></a></li>
<li><a href="https://win11.techidaily.com/a-step-by-step-solution-to-eradicate-error-code-740-on-win-11/"><u>A Step-by-Step Solution to Eradicate Error Code 740 on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/accelerate-outlook-performance-in-windows/"><u>Accelerate Outlook Performance in Windows</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-hourly-video-footage-gb-needed-per-day/"><u>In 2024, Hourly Video Footage  GB Needed Per Day</u></a></li>
<li><a href="https://win11.techidaily.com/1719369975560-break-free-from-google-chrome-glitch-on-windows-11-now/"><u>Break Free From Google Chrome Glitch on Windows 11 Now</u></a></li>
<li><a href="https://win11.techidaily.com/9-essential-steps-for-windows-hello-fingerprint-woes/"><u>9 Essential Steps for Windows Hello Fingerprint Woes</u></a></li>
<li><a href="https://win11.techidaily.com/7-annoying-wins-windows-11s-design-dissonance/"><u>7 Annoying Wins: Windows 11'S Design Dissonance</u></a></li>
<li><a href="https://win11.techidaily.com/8-easy-ways-to-unlock-windows-screen-setup-problems/"><u>8 Easy Ways to Unlock Windows Screen Setup Problems</u></a></li>
<li><a href="https://win11.techidaily.com/a-complete-guide-to-hdr-on-windows-11/"><u>A Complete Guide to HDR on Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-nokia-xr21-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Nokia XR21? | Dr.fone</u></a></li>
</ul></div>
