---
title: A Stepwise Approach to Win11's Hyper-V Activation
date: 2024-07-13T11:08:33.419Z
updated: 2024-07-14T11:08:33.419Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Stepwise Approach to Win11's Hyper-V Activation
excerpt: This Article Describes A Stepwise Approach to Win11's Hyper-V Activation
keywords: Win11Hyper-VStep,ActivateWin11VM,VMActivationGuide,Hyper-VWinActivation,StepwiseVMSetup,Win11VMConfigure,EnableWinHyper-V
thumbnail: https://thmb.techidaily.com/662c307b916403e88dc997e74395824da6bd2c6533fd74096afaf9205f685325.jpg
---

## A Stepwise Approach to Win11's Hyper-V Activation

 Hyper-V is Microsoft's in-house virtualization solution for Windows 11\. It lets you create virtual machines and run them on virtual hardware. That said, if you want to use Hyper-V on your computer, you will need to enable it first.

 In this article, we show you the how to enable Hyper-V in Windows 11 and create virtual machines without third-party tools.

## What Are the Use Cases for Hyper-V?

 Hyper-V is a native virtualization tool that allows you to run multiple operating systems on your system virtually without affecting your host OS.

 With Hyper-V, you don’t have to rely on third-party hypervisor solutions such as VirtualBox and VMware Workstation. [Hyper-V has plenty of use cases for individuals](https://www.makeuseof.com/tag/reasons-start-using-virtual-machine/), and even more for organizations.

 Some Hyper-V virtual machine use cases include:

* Run and test software for an older version of Windows or non-Windows OS
* Test software on multiple operating systems using multiple virtual machines on a single host system.
* Offers disaster recovery features including live migration and failover clustering for increased uptime.
* Create and run virtual machines in isolation for improved security.

## Prerequisites to Enable Hyper-V on Windows 11

![check Windows 11 edition](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/check-Windows-11-edition.png)

 Hyper-V is available as an optional feature on Windows 11 Pro, Enterprise, and Education. To check your edition of Windows, go to **Settings > System > About**. Then, check the **Windows specifications** section to find your Windows edition.

 If you have the Home edition, here’s how to [install Hyper-V on Windows 11 Home](https://www.makeuseof.com/install-hyper-v-windows-11-home/). All you have to do is run a bat script to install Hyper-V on non-compatible systems.

 Depending on how many virtual machines and types of applications you intend to run, you may need more resources to run the virtual machines smoothly.

 In addition, you need to enable Hardware Virtualization in BIOS. It is an essential feature to run virtual machines on your Windows system but often disabled by default.

## How to Enable Hardware Virtualization in BIOS

 On compatible systems, you can enable Hardware Virtualization in BIOS. The below steps are for an HP computer. If you are using a custom-made PC or laptop from another manufacturer, refer to the user manual for detailed instruction. If not, refer to our general guide to [enter the BIOS on Windows](https://www.makeuseof.com/tag/enter-bios-computer/).

 To enable Hardware Virtualization in BIOS:

1. Shut down your PC if it is powered on.
2. Press the **Power** button to power on the system and start pressing the **Esc** key to view the **Startup Menu.**
3. In the **Startup Menu**, press **F10** to enter the **BIOS setup.**  
![Startup menu hp laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/Startup-menu-hp-laptop.jpg)
4. In the BIOS Setup Utility, use the arrow key and open the **Configuration** tab.
5. Next, use the down arrow key to highlight the **Virtualization Technology** option.  
![enable hardware virtualization bios hp laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hardware-virtualization-bios-hp-laptoop.jpg)
6. Hit **Enter** and then select **Enabled** from the options.
7. Press **F10** to save the changes and exit **BIOS**.
8. Your PC will restart and apply the changes. This may take a while, so wait till your system is fully restarted.

 After restart, you can enable Hyper-V on Windows 11\. Here’s how to do it.

## 1\. Turn On Hyper-V in Windows 11 Via Control Panel

![enable hyper v windows features control panel](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-windows-features-control-panel.png)

 You can enable Hyper-V using the Windows Features dialog. You can access Windows Features to [add or remove optional features in Windows 11](https://www.makeuseof.com/how-to-add-remove-optional-features-windows-11/) from the Control Panel. Here’s how to do it.

1. Press **Win + R** to open **Run**.
2. Type **control** and click **OK** to open the Control Panel.
3. In the Control Panel, go to **Programs > Programs and Features.**
4. In the left pane, click on **Turn Windows features on or off.**
5. In the **Windows Features** dialog, select **Hyper-V.** If you expand Hyper-V, you will see **Hyper-V Management Tools** and **Hyper-V Platforms.**
6. Make sure both the options are selected and click **OK**. Since these are optional features, Windows will begin to install and enable them on your PC. This process may take some time to complete.
7. Once completed, click on **Restart Now** to restart, and apply the changes.

 After the restart, search for **Hyper-V** and click on **Hyper-V Manager** to create virtual machines in Windows 11\.

## 2\. Add Hyper-V to Windows 11 Using Command Prompt

![enable hyper v command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-command-prompt.png)

 Command Prompt offers a fast and efficient way to perform repetitive tasks. You can use the DISM (Deployment Image Servicing and Management) command-line tool to access and install optional Windows features via Command Prompt.

 Follow these steps to enable Hyper-V on Windows 11 using Command Prompt:

1. Press the **Win** key, and type **cmd**. Then, right-click on **Command Prompt** and select **Run as Administrator.**
2. In the Command Prompt window, type the following command and hit Enter to execute:  
`DISM /Online /Enable-Feature /All /FeatureName:Microsoft-Hyper-V`
3. The Deployment Image Servicing and Management tool will start enabling the Hyper-V feature and show the progress on the Command Prompt.
4. Once the operation is completed successfully, you will need to restart your PC. So, press **Y** on your keyboard to confirm the action.

 After your PC restarts, you can open and [use the Hyper-V Manager to create virtual machines](https://www.makeuseof.com/tag/create-virtual-machine-using-windows-10-hyper-v/).

## 3\. Enable Hyper-V Using PowerShell

![enable hyper v windows 11 powershell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hyper-v-windows-11-powershell.png)

 If you prefer Windows PowerShell over Command Prompt, you can also enable Hyper-V using the shell application.

 However, unlike Command Prompt, PowerShell uses the enable-WindowsOptional features cmdlet to enable optional features in a Windows image.

 To enable Hyper-V using PowerShell:

1. Press the **Win** key, and type **powershell**. Then, right-click on **PowerShell** and select **Run as Administrator.**
2. In the PowerShell window, type the following shell command and hit Enter:  
`Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V-All`
3. PowerShell will run the cmdlet and initiate the Hyper-V enabling process. If successful, you will be asked to restart your PC.
4. Type **Y** to confirm, and your PC will restart to apply the changes and enable a new feature.

## How to Disable Hyper-V in Windows 11

 While Hyper-V is safe to enable and use, you can disable it as easily using PowerShell. Useful if the virtualization tool causes conflict with your antivirus solution and other apps.

 To disable Hyper-V using PowerShell:

* Open **PowerShell** as administrator.
* In the PowerShell window, type the following command and press Enter:  
`Disable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V-All`
* Wait for the success message to appear and close PowerShell.
* Restart your PC to apply the changes.

## How to Configure Hyper-V Settings

![hyper v manager windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hyper-v-manager-windows-11.jpg)

 Once Hyper-V is up and running, you can configure some settings to optimize your virtual machines for optimal performance. Here are a few settings you can configure before creating a virtual machine. You can access these settings from the right pane in Hyper-V Manager.

* **Hyper-V Settings:** You can configure your virtual hard disk and virtual machine location, configure NUMA spanning storage migration, and allow enhanced session mode. On the user side, it lets you configure the virtual machine's keyboard and the mouse release key.
* **Virtual Switch Manager:** It lets you create External, Internal, or Private switches. Virtual switches are bound to the physical network adapter to access the network.
* **Integration services:** You can choose from and enable/disable a host of integration services, including Heartbeat, Key-Value pair exchange, Time synchronization, and Volume shadow copy requestor (VSS) to enhance the performance and functionality of your virtual machine.

![Windows admin center console home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-admin-center-console-home.jpg)

 While the MMC-based Hyper-V manager is functional and built into the OS, consider using the relatively new Windows Admin Center. It is a browser-based management app that lets you manage your servers, virtual machines, local users and groups, and more.

 Download [Windows Admin Center](https://www.microsoft.com/en-in/windows-server/windows-admin-center) from the official Microsoft page and run the installer to give it a go. Once installed, open the app, and it will launch in your default browser, giving you access to a host of management tools.

## Many Ways to Enable Hyper-V in Windows 11

 Hyper-V is a type 1 hypervisor, which means it runs directly on a computer’s hardware. It comes pre-installed, free to use without restriction, and offers linear performance on a consumer-grade system.

 That said, dedicated virtual machines such as the VMWare WorkStation Pro is available on multiple platforms, can be used on older systems, and is more suitable for enterprise solutions. Check out our comparison comparing the three popular hypervisors to find the one that works for you.

 In this article, we show you the how to enable Hyper-V in Windows 11 and create virtual machines without third-party tools.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-stream.techidaily.com/in-2024-unveiling-the-best-purchasers-of-monetized-youtube-channels/"><u>In 2024, Unveiling the Best Purchasers of Monetized YouTube Channels</u></a></li>
<li><a href="https://fox-helps.techidaily.com/avoiding-threats-while-grabbing-gratis-vlc-player-for-apple-machines-for-2024/"><u>Avoiding Threats While Grabbing Gratis VLC Player for Apple Machines for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/best-free-and-cheap-mp3-editor-for-mac-for-2024/"><u>Best Free and Cheap MP3 Editor for Mac for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/powerful-tactics-for-using-windows-explorer-not-ls/"><u>Powerful Tactics for Using Windows Explorer, Not LS</u></a></li>
<li><a href="https://win11.techidaily.com/reactivate-windows-file-explorer-efficiently/"><u>Reactivate Windows File Explorer Efficiently</u></a></li>
<li><a href="https://win11.techidaily.com/reducing-cpuram-drain-from-consuming-video-content/"><u>Reducing CPU/RAM Drain From Consuming Video Content</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-steps-for-hardware-alerts-in-windows/"><u>Troubleshooting Steps for Hardware Alerts in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/taming-the-chaos-of-mbr-errors-with-data-interpretation/"><u>Taming the Chaos of MBR Errors with Data Interpretation</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-to-admin-command-center-on-windows/"><u>Navigating to Admin Command Center on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/swift-keyboard-mastery-with-typingaid/"><u>Swift Keyboard Mastery with TypingAid</u></a></li>
<li><a href="https://win11.techidaily.com/the-pathway-to-using-windows-11-toolbars-effectively/"><u>The Pathway to Using Window's 11 Toolbars Effectively</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-monochrome-troubles-with-store-app/"><u>Overcoming Monochrome Troubles with Store App</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-oppo-a38-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Oppo A38 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-to-address-app-support-issues-on-newer-windows/"><u>Techniques to Address App Support Issues on Newer Windows</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-the-ultimate-guide-for-virtual-reality-content-android-friendly/"><u>[Updated] The Ultimate Guide for Virtual Reality Content (Android-Friendly)</u></a></li>
<li><a href="https://win11.techidaily.com/reduce-delay-in-windows-11-keys-7-proven-methods/"><u>Reduce Delay in Windows 11 Keys: 7 Proven Methods</u></a></li>
<li><a href="https://win11.techidaily.com/regain-access-to-microsoft-store-features-on-pcs/"><u>Regain Access to Microsoft Store Features on PCs</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-2024-approved-how-to-choose-a-nice-gopro-for-vlogging/"><u>New 2024 Approved How to Choose A Nice GoPro for Vlogging?</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-with-ease-open-mouse-prop-in-win11/"><u>Navigating with Ease: Open Mouse Prop in Win11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-unstuck-video-streams-from-photobooth-screens/"><u>2024 Approved  Unstuck Video Streams From Photobooth Screens</u></a></li>
<li><a href="https://win11.techidaily.com/top-12-redundant-windows-extras-for-removal/"><u>Top 12 Redundant Windows Extras for Removal</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-curating-customized-instagram-highlight-banners/"><u>2024 Approved  Curating Customized Instagram Highlight Banners</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-fixing-broken-internet-connections-6-strategies-for-windows-users/"><u>The Art of Fixing Broken Internet Connections - 6 Strategies for Windows Users</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-your-way-to-windows-11-group-policies/"><u>Streamline Your Way to Windows 11 Group Policies</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-dual-display-dominance-top-videographer-verdict/"><u>[Updated] In 2024, Dual Display Dominance  Top Videographer Verdict</u></a></li>
<li><a href="https://win11.techidaily.com/protecting-the-default-windows-clock-configuration/"><u>Protecting the Default Windows Clock Configuration</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-can-we-bypass-motorola-moto-g24-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Motorola Moto G24 FRP?</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-no-browser-scenarios-in-new-oss/"><u>Overcoming No-Browser Scenarios in New OSs</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-the-guide-to-video-opposite-on-snapchat-for-2024/"><u>[Updated] The Guide to Video Opposite on Snapchat for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/refreshing-gpu-functionality-in-windows-10-and-11-easy-fixes/"><u>Refreshing GPU Functionality in Windows 10 & 11 Easy Fixes</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-unleash-your-creativity-a-guide-to-android-video-editing-apps/"><u>New Unleash Your Creativity A Guide to Android Video Editing Apps</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-non-previewable-file-trouble-on-outlook-365-pc/"><u>Overcoming Non-Previewable File Trouble on Outlook 365 PC</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-expert-approved-free-video-splitting-tools/"><u>Updated 2024 Approved Expert-Approved Free Video Splitting Tools</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-getting-past-windows-update-hitches/"><u>Quick Fixes: Getting Past Windows Update Hitches</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-blue-screen-error/"><u>Strategies for Overcoming Blue Screen Error</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-top-five-protocols-for-documenting-youtube-live-broadcasts/"><u>[New] In 2024, Top Five Protocols for Documenting YouTube LIVE Broadcasts</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-unidentified-component-in-windows-lsass/"><u>Quick Fixes for Unidentified Component in Windows Lsass</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-document-gameplay-secrets-in-galaxy-androids/"><u>In 2024, Document Gameplay Secrets in Galaxy Androids</u></a></li>
<li><a href="https://win11.techidaily.com/remedial-actions-for-incorrect-app-configuration/"><u>Remedial Actions for Incorrect App Configuration</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-reactivating-a-greyed-out-secure-boot-in-bios/"><u>Steps for Reactivating a Greyed Out Secure Boot in BIOS</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-navigating-cross-track-dynamics-in-logic-pro-x/"><u>[Updated] Navigating Cross-Track Dynamics in Logic Pro X</u></a></li>
</ul></div>
