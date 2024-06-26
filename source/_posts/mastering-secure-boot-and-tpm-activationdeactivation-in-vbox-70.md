---
title: Mastering Secure Boot and TPM Activation/Deactivation in VBox 7.0
date: 2024-06-25T09:46:27.362Z
updated: 2024-06-26T09:46:27.362Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastering Secure Boot and TPM Activation/Deactivation in VBox 7.0
excerpt: This Article Describes Mastering Secure Boot and TPM Activation/Deactivation in VBox 7.0
keywords: Secure Boot Mastery,TPM Control Guide,VMBoost 7 Security,TPM Enablement Tips,VBox Secure Startup,Advanced TPM Activation,VBox 7.0 TPM Management
thumbnail: https://thmb.techidaily.com/abb5b783422357ac326d246e72e8c7f9c8f3c9e301b0d6289c4da0aac55fb642.jpg
---

## Mastering Secure Boot and TPM Activation/Deactivation in VBox 7.0

 VirtualBox released version 7.0 in October 2022\. It is the first hypervisor to support the emulation of TPM chips along with all the other system components. VirtualBox also offers a Secure Boot feature in EFI mode for virtual machines. The main reason behind these two features was Microsoft's list of elaborate system requirements for Windows 11.

 Without emulation of the TPM 2.0 chip, users couldn't install Windows 11 on a virtual machine. But with VirtualBox 7.0 it is possible to enable Secure Boot and TPM for any Windows virtual machine. This post will elaborate on the methods to enable or disable TPM and Secure Boot for any VirtualBox virtual machine.

## Why Does Windows 11 Need TPM and Secure Boot?

 Windows 11 needs both a TPM chip and Secure Boot to offer robust protection against threats and not allow any malware to run when the system boots up. Secure Boot only allows signed drivers to load and the TPM chip helps in BitLocker drive data protection. So, both these features are pretty important from a security standpoint. Check out our guide on[what Secure Boot is and how it works](https://www.makeuseof.com/what-is-secure-boot-how-does-it-work/) for more information.

 While Windows 11 can work without Secure Boot and a TPM 2.0 chip, it won't be able to offer that extra layer of system protection it would do otherwise. Many features like Core-isolation, Data Encryption won't work. If you want to enable or disable these features for Windows 10 or 11 virtual machines, you can do so in VirtualBox 7.0.

## How to Enable or Disable Secure Boot and TPM Support in VirtualBox 7.0

 Repeat the following steps to enable TPM 2.0 and Secure Boot in VirtualBox.

1. Press the**Win** key and search VirtualBox. Click on the first relevant search result to launch the app.
2. Click on a Windows virtual machine and then click on the**Settings** icon.
3. Navigate to the**System** settings option.
4. Find the**TPM** option. If it is set to none, click on the**arrow** icon to open the drop-down menu.
5. Select the TPM**v2.0** option from the list. Windows 11 won't work with anything lower but if you are using Windows 10 then you can pick**v1.2** from the list.
6. Scroll down and locate the**Extended Features** section. Click on the**Enable EFI (special OSes only)** option check box.
7. Then click on the**Enable Secure Boot** option check box.  
![Enable Secure Boot and TPM Support in VirtualBox 7.0](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/enable-secure-boot-and-tpm-support-in-virtualbox-7-0.jpg)
8. Now, click on the**OK** button. The settings window will close automatically.
9. Go to the top area and click on the**Start** button to power on the Windows virtual machine.
10. Now, press the Win key and search Security. Open the**Windows security** app.
11. Navigate to the left-hand side menu and click on the**Device Security** option. Here, all Windows security features will be active.
12. To disable TPM and Secure Boot, reopen the virtual machine settings and set the TPM version to**None** . Uncheck the**Enable EFI (special OSes only)** option check box. Click on**OK** to save the changes.

### An Alternative Method to Check if TPM Is Active in the Windows Virtual Machine

Here's how to check TPM on Windows 11 virtual machine:

1. Press the**Win + R** key to launch the Run command box (see[how to open Windows Run](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more ways). Type**TPM.msc** and press the**Enter** key.  
![check TPM on Windows 11 virtual machine 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-1.jpg)
2. TPM utility will launch. Navigate to the Manufacturer Information section.  
![check TPM on Windows 11 virtual machine 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/check-tpm-on-windows-11-virtual-machine-2.jpg)
3. If the Specification version entry showcases 2.0, it means that TPM chip emulation is successful.

## Manage TPM and Secure Boot Features in VirtualBox With Ease

 You can choose to keep both features active or not. After installing Windows 11 as a virtual machine, you can turn TPM and Secure Boot off and not face any issues with the operating system. However, remember that these are important from a security perspective.


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
<li><a href="https://win11.techidaily.com/enhancing-windows-11-with-personal-touches/"><u>Enhancing Windows 11 with Personal Touches</u></a></li>
<li><a href="https://win11.techidaily.com/total-extraction-of-wsl-from-windows-11-screens/"><u>Total Extraction of WSL From Windows 11 Screens</u></a></li>
<li><a href="https://win11.techidaily.com/wu-and-orchestrator-the-pillars-of-update-routine/"><u>WU & Orchestrator: The Pillars of Update Routine</u></a></li>
<li><a href="https://win11.techidaily.com/cleaning-slates-in-windows-the-3-reset-routes/"><u>Cleaning Slates in Windows: The 3 Reset Routes</u></a></li>
<li><a href="https://win11.techidaily.com/take-control-of-your-system-utilizing-alomware-tools-effectively/"><u>Take Control of Your System: Utilizing AlomWare Tools Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-nvidia-settings-failure-to-save/"><u>Overcoming NVIDIA Settings Failure to Save</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-notes-with-obsidians-visual-approach/"><u>Streamlining Notes with Obsidian's Visual Approach</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-screen-unresponsive-message-in-windows-1111/"><u>Fixing Screen Unresponsive Message in Windows 11/11</u></a></li>
<li><a href="https://win11.techidaily.com/from-vanished-panes-to-visible-windows-essential-steps-for-recovering-hidden-screens-6-ways/"><u>From Vanished Panes to Visible Windows: Essential Steps for Recovering Hidden Screens (6 Ways)</u></a></li>
<li><a href="https://win11.techidaily.com/win11-steps-to-correct-steam-file-privileges-failure/"><u>Win11 Steps to Correct Steam File Privileges Failure</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-can-we-unlock-our-realme-gt-3-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our Realme GT 3 Phone Screen?</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/reset-itunes-backup-password-of-iphone-xs-prevention-and-solution-drfone-by-drfone-ios/"><u>Reset iTunes Backup Password Of iPhone XS Prevention & Solution | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-step-by-step-tutorial-engaging-in-a-call-on-snapchat/"><u>In 2024, Step-By-Step Tutorial  Engaging in a Call on Snapchat</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-discovering-the-6-best-call-voice-boosters-on-both-android-and-iphone-devices/"><u>Updated Discovering the 6 Best Call Voice Boosters on Both Android and iPhone Devices</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-enhance-your-videography-youtube-studio-edition-techniques/"><u>[Updated] In 2024, Enhance Your Videography  YouTube Studio Edition Techniques</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-professional-audio-editing-software-is-a-powerful-tool-for-us-to-make-an-amazing-video-in-this-article-you-will-learn-the-8-best-professional-audio-/"><u>In 2024, Professional Audio Editing Software Is a Powerful Tool for Us to Make an Amazing Video. In This Article, You Will Learn the 8 Best Professional Audio Editing Software. Check This Article to Find More</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exploring-the-dynamics-of-fb-video-speeds/"><u>2024 Approved  Exploring the Dynamics of FB Video Speeds</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-crafting-and-channelizing-imovie-productions-on-youtube/"><u>[New] Crafting and Channelizing iMovie Productions on YouTube</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-the-vhs-effect-in-fcp-a-beginners-guide-to-retro-editing/"><u>New 2024 Approved The VHS Effect in FCP A Beginners Guide to Retro Editing</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/easily-connect-to-the-cloud-and-post-from-your-camera-roll-for-2024/"><u>Easily Connect to the Cloud and Post From Your Camera Roll for 2024</u></a></li>
</ul></div>
