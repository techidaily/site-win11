---
title: "Mastering Virtualization: Hyper-V Setup for Win11"
date: 2024-09-11T09:41:12.631Z
updated: 2024-09-12T09:41:12.631Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastering Virtualization: Hyper-V Setup for Win11"
excerpt: "This Article Describes Mastering Virtualization: Hyper-V Setup for Win11"
keywords: Virtual Setup Win11,Hyper-V Mastery,Win11 Hyper-V,Virtualization Win,Win11 Server Pro,Hyper-V Configuration,Win11 Virtualize
thumbnail: https://thmb.techidaily.com/5ba7b3f6e60e87bd15e4d0d59cd473305f169947afe8b79e803b03fc556698ce.jpg
---

## Mastering Virtualization: Hyper-V Setup for Win11

 Hyper-V is Microsoft's in-house virtualization solution for Windows 11\. It lets you create virtual machines and run them on virtual hardware. That said, if you want to use Hyper-V on your computer, you will need to enable it first.

 In this article, we show you the how to enable Hyper-V in Windows 11 and create virtual machines without third-party tools.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136624/26400" target="_top" id="2136624">
  <img src="//a.impactradius-go.com/display-ad/26400-2136624" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136624/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115949/19272" target="_top" id="2115949">
  <img src="//a.impactradius-go.com/display-ad/19272-2115949" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115949/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to Enable Hardware Virtualization in BIOS

 On compatible systems, you can enable Hardware Virtualization in BIOS. The below steps are for an HP computer. If you are using a custom-made PC or laptop from another manufacturer, refer to the user manual for detailed instruction. If not, refer to our general guide to [enter the BIOS on Windows](https://www.makeuseof.com/tag/enter-bios-computer/).

 To enable Hardware Virtualization in BIOS:

1. Shut down your PC if it is powered on.
2. Press the **Power** button to power on the system and start pressing the **Esc** key to view the **Startup Menu.**
3. In the **Startup Menu**, press **F10** to enter the **BIOS setup.**  
![Startup menu hp laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/Startup-menu-hp-laptop.jpg)
4. In the BIOS Setup Utility, use the arrow key and open the **Configuration** tab.

<!-- affiliate ads begin -->
<span id="1977028">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977028.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977028">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977028.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977028%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977028/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Next, use the down arrow key to highlight the **Virtualization Technology** option.  
![enable hardware virtualization bios hp laptop](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/01/enable-hardware-virtualization-bios-hp-laptoop.jpg)
6. Hit **Enter** and then select **Enabled** from the options.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123731/7443" target="_top" id="2123731">
  <img src="//a.impactradius-go.com/display-ad/7443-2123731" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123731/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<span id="1983582">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983582.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983582">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983582.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983582%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983582/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Command Prompt offers a fast and efficient way to perform repetitive tasks. You can use the DISM (Deployment Image Servicing and Management) command-line tool to access and install optional Windows features via Command Prompt.

 Follow these steps to enable Hyper-V on Windows 11 using Command Prompt:

1. Press the **Win** key, and type **cmd**. Then, right-click on **Command Prompt** and select **Run as Administrator.**
2. In the Command Prompt window, type the following command and hit Enter to execute:  
`DISM /Online /Enable-Feature /All /FeatureName:Microsoft-Hyper-V`
3. The Deployment Image Servicing and Management tool will start enabling the Hyper-V feature and show the progress on the Command Prompt.
4. Once the operation is completed successfully, you will need to restart your PC. So, press **Y** on your keyboard to confirm the action.

 After your PC restarts, you can open and [use the Hyper-V Manager to create virtual machines](https://www.makeuseof.com/tag/create-virtual-machine-using-windows-10-hyper-v/).

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115908/19272" target="_top" id="2115908">
  <img src="//a.impactradius-go.com/display-ad/19272-2115908" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115908/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123478/16836" target="_top" id="2123478">
  <img src="//a.impactradius-go.com/display-ad/16836-2123478" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123478/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once Hyper-V is up and running, you can configure some settings to optimize your virtual machines for optimal performance. Here are a few settings you can configure before creating a virtual machine. You can access these settings from the right pane in Hyper-V Manager.

* **Hyper-V Settings:** You can configure your virtual hard disk and virtual machine location, configure NUMA spanning storage migration, and allow enhanced session mode. On the user side, it lets you configure the virtual machine's keyboard and the mouse release key.
* **Virtual Switch Manager:** It lets you create External, Internal, or Private switches. Virtual switches are bound to the physical network adapter to access the network.
* **Integration services:** You can choose from and enable/disable a host of integration services, including Heartbeat, Key-Value pair exchange, Time synchronization, and Volume shadow copy requestor (VSS) to enhance the performance and functionality of your virtual machine.

![Windows admin center console home](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/windows-admin-center-console-home.jpg)

 While the MMC-based Hyper-V manager is functional and built into the OS, consider using the relatively new Windows Admin Center. It is a browser-based management app that lets you manage your servers, virtual machines, local users and groups, and more.

 Download [Windows Admin Center](https://www.microsoft.com/en-in/windows-server/windows-admin-center) from the official Microsoft page and run the installer to give it a go. Once installed, open the app, and it will launch in your default browser, giving you access to a host of management tools.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136620/26400" target="_top" id="2136620">
  <img src="//a.impactradius-go.com/display-ad/26400-2136620" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136620/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Many Ways to Enable Hyper-V in Windows 11

 Hyper-V is a type 1 hypervisor, which means it runs directly on a computer’s hardware. It comes pre-installed, free to use without restriction, and offers linear performance on a consumer-grade system.

 That said, dedicated virtual machines such as the VMWare WorkStation Pro is available on multiple platforms, can be used on older systems, and is more suitable for enterprise solutions. Check out our comparison comparing the three popular hypervisors to find the one that works for you.

 In this article, we show you the how to enable Hyper-V in Windows 11 and create virtual machines without third-party tools.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-screen-grab.techidaily.com/new-easy-peasy-screen-transitions-for-filmmakers-for-2024/"><u>[New] Easy-Peasy Screen Transitions for Filmmakers for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-audio-quality-boost-for-skype-calls/"><u>[Updated] In 2024, Audio Quality Boost for Skype Calls</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-best-screen-replayer-for-high-impact-youtubing-experience/"><u>[Updated] In 2024, Best Screen Replayer for High-Impact YouTubing Experience</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-from-black-and-white-to-color-classic-video-transition-tips/"><u>[Updated] In 2024, From Black-and-White to Color Classic Video Transition Tips</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-unlocking-the-art-of-iphones-upside-down-photos/"><u>[Updated] Unlocking the Art of iPhone's Upside-Down Photos</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathe-new-life-into-old-computers-without-windows/"><u>Breathe New Life Into Old Computers Without Windows</u></a></li>
<li><a href="https://win11.techidaily.com/conquering-error-0x800f082f-in-microsofts-dism-tool/"><u>Conquering Error 0X800F082F in Microsoft's DISM Tool</u></a></li>
<li><a href="https://win11.techidaily.com/direct-effortless-gameplay-capture-using-windows-and-intel-graphics/"><u>Direct, Effortless Gameplay Capture Using Windows and Intel Graphics</u></a></li>
<li><a href="https://win11.techidaily.com/disentangling-steam-timeout-problems-on-windows-with-rust-techniques/"><u>Disentangling Steam Timeout Problems on Windows with Rust Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/diving-into-character-inspector-with-win11/"><u>Diving Into Character Inspector with Win11</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-clearing-wins-cache-memory/"><u>Efficiently Clearing Win's Cache Memory</u></a></li>
<li><a href="https://win11.techidaily.com/efficiently-secure-your-browsing-in-win-11-using-microsofts-application-guard/"><u>Efficiently Secure Your Browsing in Win 11 Using Microsoft's Application Guard</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-your-security-posture-adding-passwords-to-text-files/"><u>Elevating Your Security Posture: Adding Passwords to Text Files</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-absence-of-monitor-post-bootup/"><u>Eliminating Absence of Monitor Post-Bootup</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-interrupted-by-breakpoint-error-in-windows/"><u>Eliminating Interrupted by Breakpoint Error in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-share-functionality-in-windows-11-and-11/"><u>Enhancing Share Functionality in Windows 11 and 11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/explore-creative-horizons-with-imaginative-snapchat-boomerang-techniques/"><u>Explore Creative Horizons with Imaginative Snapchat Boomerang Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-techniques-to-launch-windows-11s-restore-mode/"><u>Exploring Techniques to Launch Windows 11'S Restore Mode</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tune-your-windows-11-defenses-adding-new-filter-options-to-context-menu/"><u>Fine-Tune Your Windows 11 Defenses: Adding New Filter Options to Context Menu</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-notepad-strategies-for-a-responsive-windows-companion-app/"><u>Fixing Notepad: Strategies for a Responsive Windows Companion App</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-unclog-the-secondary-user-writes-access-issue/"><u>How to Unclog the Secondary User' Writes Access Issue</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-fade-out-in-audacity/"><u>In 2024, How to Fade Out in Audacity</u></a></li>
<li><a href="https://extra-tips.techidaily.com/individual-differences/"><u>Individual Differences</u></a></li>
<li><a href="https://win11.techidaily.com/interactive-sphere-expands-windows-for-iphonesipads-pcsmac-unveiled/"><u>Interactive Sphere Expands: Windows for iPhones/iPads, PCs/Mac Unveiled</u></a></li>
<li><a href="https://win11.techidaily.com/maintaining-your-sticky-notes-on-pc/"><u>Maintaining Your Sticky Notes on PC</u></a></li>
<li><a href="https://win11.techidaily.com/making-win1011-recycle-bin-error-free-quick-solutions/"><u>Making Win10/11 Recycle Bin Error-Free: Quick Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-window-11-taskbar-modifications/"><u>Mastering Window 11 Taskbar Modifications</u></a></li>
<li><a href="https://win11.techidaily.com/mastery-guide-to-resolving-windows-http-too-many-requests-issue/"><u>Mastery Guide to Resolving Windows' HTTP Too Many Requests Issue</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-store-woes-resolve-error-x80072f30-easily/"><u>Microsoft Store Woes, Resolve Error X80072F30 Easily</u></a></li>
<li><a href="https://win11.techidaily.com/minimizing-options-in-the-win-11-context-list/"><u>Minimizing Options in the Win 11 Context List</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/most-effective-mac-screen-recording-software-other-than-bandicam/"><u>Most Effective Mac Screen Recording Software, Other than Bandicam</u></a></li>
<li><a href="https://win11.techidaily.com/rediscovering-the-bygone-folder-interface/"><u>Rediscovering the Bygone Folder Interface</u></a></li>
<li><a href="https://win11.techidaily.com/reestablishing-memory-integrity-on-windows-11-amid-issues/"><u>Reestablishing Memory Integrity on Windows 11 Amid Issues</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-mute-read-out-mode-on-word-software/"><u>Remedying Mute Read-Out Mode on Word Software</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-based-inaccessibility-to-roblox-experience/"><u>Resolving Windows-Based Inaccessibility to Roblox Experience</u></a></li>
<li><a href="https://win11.techidaily.com/sleek-software-not-so-slick-the-throttling-of-your-pcs-speed/"><u>Sleek Software, Not So Slick: The Throttling of Your PC's Speed</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-git-workflow-github-desktop-and-windows-1011/"><u>Streamlining Your Git Workflow: GitHub Desktop & Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/synergizing-technology-the-role-of-ai-in-windows-11-dynamics/"><u>Synergizing Technology: The Role of AI in Windows 11 Dynamics</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-fixing-screen-alignment-in-windows-os/"><u>Tips for Fixing Screen Alignment in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-switching-assistants-helping-you-ditch-your-mac-os/"><u>Top 5 Switching Assistants Helping You Ditch Your Mac OS</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-future-on-windows-empower-your-pc-with-vivetool/"><u>Unlocking the Future on Windows: Empower Your PC with ViVeTool</u></a></li>
<li><a href="https://win11.techidaily.com/win11s-personalized-audio-settings-key-combinations-explained/"><u>Win11's Personalized Audio Settings: Key Combinations Explained</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-protected-mode-what-does-it-entail/"><u>Windows 11'S Protected Mode: What Does It Entail?</u></a></li>
<li><a href="https://win11.techidaily.com/winway-login-tips-removing-personal-emails/"><u>Winway Login Tips: Removing Personal Emails</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    