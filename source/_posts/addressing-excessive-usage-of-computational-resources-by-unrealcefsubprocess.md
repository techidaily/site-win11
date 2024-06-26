---
title: Addressing Excessive Usage of Computational Resources by UnrealCEFSubprocess
date: 2024-06-25T10:00:31.265Z
updated: 2024-06-26T10:00:31.265Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Addressing Excessive Usage of Computational Resources by UnrealCEFSubprocess
excerpt: This Article Describes Addressing Excessive Usage of Computational Resources by UnrealCEFSubprocess
keywords: UnrealComputeOveruse,SubprocessResourceExcess,ComputationalEfficiency,ResourceConsumptionUnreal,ExcessiveUsageResources,CPULoadLimitSubprocess,GPUIntensiveTasks
thumbnail: https://thmb.techidaily.com/8581bfa31a5d038a1f8f5ee676586f0437981f1b9f6527b07717a27989fe2446.jpg
---

## Addressing Excessive Usage of Computational Resources by UnrealCEFSubprocess

 Is the UnrealCEFSubprocess process consuming hefty CPU and RAM resources in the Task Manager, causing your games to crash? Does it keep straining your hardware even after you close all the active programs and apps? You may also have seen it multiply in the Task Manager, which might have made you believe it's a virus.

 There's no need to worry; it's not a virus but a legitimate process belonging to Valorant. Below, we'll discuss why this process consumes many system resources and how you can reduce its resource usage to relieve the strain on your hardware.

## Why Does the UnrealCEFSubprocess Process Consume High CPU and RAM Resources?

 UnrealCEFSubprocess is a legitimate Valorant process, so it shouldn't overload your system resources. If this process starts to strain your hardware and cause CPU, RAM, or GPU usage to spike in the Task Manager, it's either not functioning correctly, or other processes are interfering with it.

 As many users pointed out in a[Reddit thread](https://www.reddit.com/r/ValorantTechSupport/comments/z66n1b/unrealcefsubprocessexe%5Fmultiplying%5Fand%5Fputting/) , one of the major causes of high resource consumption by this process is the interference from Windows' built-in security suite, Windows Defender, and third-party antivirus software, primarily AVG antivirus and Avast antivirus. If you are using security software, then it might be causing the issue.

## Can You Disable the UnrealCEFSubprocess Process via the Task Manager?

 Disabling the UnrealCEFSubprocess process could adversely affect your active gaming session in Valorant. The gaming elements this process controls or handles will crash and behave abnormally. Because of this, we do not advocate closing it down.

 Furthermore, Valorant or the Riot client will automatically relaunch this process the next time you open them, so disabling only the process won't solve the issue. Therefore, we recommend that you fix the underlying problem rather than only disabling this process.

## How to Stop the UnrealCEFSubprocess Process From Taking Up Too Much RAM and CPU

 The easiest way to reduce UnrealCEFSubprocess's CPU and RAM consumption is to[permanently disable Windows Defender](https://www.makeuseof.com/permanently-disable-microsoft-defender-windows-11/) , the built-in security software in Windows, and uninstall any third-party antivirus software you currently use. Even though doing this is easy and quick, we don't recommend it. Why is that?

 The Windows Defender and third-party antivirus software installed on your laptop are a solid defense against viruses and malware. They prevent any potentially harmful agents from wreaking havoc on your device. If you delete or disable them, you will remove your frontline fighters and allow enemies to attack your territory with no fear.

 These security suites would likely have already quarantined many threats and blocked potentially harmful files from affecting your computer. Disabling or deleting them can release these threats and remove restrictions on malicious files. Consequently, this could negatively affect your computer in the long run.

 Considering the risks associated with it, it would be wise not to disable security software right away. Instead of that, you can whitelist the UnrealCEFSubprocess process in them. Whitelisting any file instructs security software not to interfere with it. Therefore, whitelisting the file associated with this process will prevent antivirus programs from interfering with it.

 Consequently, you will be successful in reducing resource consumption without compromising your security.

### How to Whitelist UnrealCEFSubprocess From Windows Defender

 Follow these steps to whitelist UnrealCEFSubprocess from Windows Defender:

1. Type**"Windows Security"** in Windows Search and open the**Windows Security** app.  
![Open Windows Security from Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/1-open-windows-security-from-windows-search.jpg)
2. Go to the**Firewall and network protection** tab on the left.
3. Click on the**Allow an app through the firewall** link on the right side of the screen.  
![Click on the Allow an App Through the Firewall Link in Windows Security App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/2-click-on-the-allow-an-app-through-the-firewall-link-in-windows-security-app.jpg)
4. Click on**Change settings** .
5. Click on**Allow another app** .  
![Click on Allow Another App in the Windows Defender Firewall Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/3-click-on-allow-another-app-in-the-windows-defender-firewall-settings.jpg)

1. In the**Add an app** window, click on the**Browse** button.  
![Click on the Browse Button in the Add an App Window in the Windows Defender Firewall Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/4-click-on-the-browse-button-in-the-add-an-app-window-in-the-windows-defender-firewall-settings.jpg)
2. Then, go to the following path:  
`C:\Program Files\Riot Games\VALORANT\live\Engine\Binaries\Win64`
3. Here, select**UnrealCEFSubProcess** from the list.  
![Select UnrealCEFSubprocess to Create an Exclusion for It](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-select-unrealcefsubprocess-to-create-an-exclusion-for-it.jpg)
4. Then, click on**Add** .  
![Click on the Add Button After Selecting the Relevant Process](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/6-click-on-the-add-button-after-selecting-the-relevant-process.jpg)
5. After that, check the**Public** and**Private** boxes next to the**UnrealCEFSubProcess** process and click**OK** .  
![Click OK After Checking the Public and Private Boxes Next to the UnrealCEFSubprocess in the Windows Firewall Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/7-click-ok-after-checking-the-public-and-private-boxes-next-to-the-unrealcefsubprocess-in-the-windows-firewall-settings.jpg)
6. Restart your computer after whitelisting this process.

**I** f you have installed Valorant in a different folder or your operating system resides on a different drive, change the path above to reflect the proper location.

### How to Whitelist UnrealCEFSubprocess From Avast Antivirus

 Follow these steps to whitelist UnrealCEFSubprocess from Avast Antivirus:

1. Launch Avast Antivirus.
2. Click the**Menu** button (represented by three horizontal lines stacked over each other) in the top-right of the screen.
3. Go to**Settings** .  
![Go to Settings in Avast Antivirus App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/8-go-to-settings-in-avast-antivirus-app.jpg)
4. Go to the**Exceptions** tab in the**General** settings.
5. Click on**Add Exception** .  
![Click on Add Exception in the General Settings in Avast Antivirus App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/9-click-on-add-exception-in-the-general-settings-in-avast-antivirus-app.jpg)
6. Click**Browse** in the**Add exception** window.  
![Click Browse in the Add Exception Window in Avast Antivirus App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/10-click-browse-in-the-add-exception-window-in-avast-antivirus-app.jpg)
7. Navigate to the following path if you haven't changed the default installation path when installing Valorant:  
`C:\Program Files\Riot Games\VALORANT\live\Engine\Binaries\Win64`
8. Check the box beside**UnrealCEFSubprocess** and click**OK** .  
![Click OK After Checking the Box Beside UnrealCEFSubprocess in Avast Antivirus App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/11-click-ok-after-checking-the-box-beside-unrealcefsubprocess-in-avast-antivirus-app.jpg)
9. After that, restart your computer once, and hopefully, the process won't overtax your computer's resources anymore.

### How to Whitelist UnrealCEFSubprocess From AVG Antivirus

 The interface of AVG antivirus is almost identical to Avast antivirus. So, you can whitelist UnrealCEFSubprocess from it by following the steps outlined above. Once you have whitelisted the file,[restart your computer](https://www.makeuseof.com/windows-restart-methods/) once, and hopefully, the resource consumption by this process will decrease significantly.

 According to some users, whitelisting the UnrealCEFSubprocess file from AVG antivirus doesn't always reduce its resource consumption. Due to this, users had to delete AVG antivirus from their computers. So, if whitelisting the file doesn't reduce the load on your hardware, you can delete the AVG antivirus.

 Before doing that,[turn on Windows Defender](https://www.makeuseof.com/turn-on-microsoft-defender/) if it's off, or install alternative antivirus software to replace AVG and keep your computer safe from incoming threats.

 If you use an antivirus software other than the two listed above and the UnrealCEFSubprocess process consumes more than half of your system resources, you need to whitelist the UnrealCEFSubprocess file there as well. If you are not familiar with the whitelisting process, visit the antivirus software's official website.

## Don't Let the UnrealCEFSubprocess Process Overburden Your Hardware

 The UnrealCEFSubprocess process consumes a lot of resources, which leaves barely any resources for other processes. Consequently, your games and apps will take a long time to load and crash frequently—enough to ruin your gaming experience.

 You should now better understand why this process consumes a lot of resources and what you can do to fix it. Therefore, whitelist the UnrealCEFSubprocess process in your security program, and if that does not solve the issue, disable or uninstall your antivirus.


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
<li><a href="https://win11.techidaily.com/steps-to-handle-no-device-drivers-issue-in-system-setup/"><u>Steps to Handle 'No Device Drivers' Issue in System Setup</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-fixing-inverted-text-input-windows-wise/"><u>Strategies for Fixing Inverted Text Input Windows-Wise</u></a></li>
<li><a href="https://win11.techidaily.com/reclaim-control-over-your-screen-amidst-the-dark/"><u>Reclaim Control Over Your Screen Amidst the Dark</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-heat-in-windows-11-pcs/"><u>Troubleshooting Heat in Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/stay-on-top-of-your-windows-11-devices-with-our-5-crucial-uptime-methods/"><u>Stay on Top of Your Windows 11 Devices with Our 5 Crucial Uptime Methods</u></a></li>
<li><a href="https://win11.techidaily.com/passwords-and-files-a-comprehensive-guide-to-windows-1011/"><u>Passwords and Files: A Comprehensive Guide to Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/reclaim-your-lost-windows-secrets-for-restoring-hidden-panes-on-win-1011-with-ease/"><u>Reclaim Your Lost Windows! Secrets for Restoring Hidden Panes on Win 10/11 with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-the-workflow-of-windows-11s-backup-feature/"><u>Understanding The Workflow of Windows 11'S Backup Feature</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-file-write-error-in-windows-11-os/"><u>Resolving File Write Error in Windows 11 OS</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-full-spatial-capability-with-windows-11-settings/"><u>Unleash Full Spatial Capability with Windows 11 Settings</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-cloud-savings-guide-comparing-costs-and-top-deals/"><u>2024 Approved  Cloud Savings Guide  Comparing Costs & Top Deals</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/in-2024-the-ultimate-list-top-10-free-video-trimmers-for-windows-10/"><u>In 2024, The Ultimate List Top 10 Free Video Trimmers for Windows 10</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-image-all-screen-website-view/"><u>[Updated] 2024 Approved  Image All-Screen Website View</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-does-apples-m1-compare-to-traditional-editing-workstations-in-2024/"><u>How Does Apple’s M1 Compare to Traditional Editing Workstations, In 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-unleash-the-power-of-slow-mo-top-video-editing-software-revealed/"><u>New In 2024, Unleash the Power of Slow Mo Top Video Editing Software Revealed</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-audio-exploration-the-comprehensible-review-of-pazera/"><u>[New] Audio Exploration  The Comprehensible Review of Pazera</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-free-tools-top-5-screen-recorder-apps-for-chrome-devices/"><u>[New] In 2024, Free Tools  Top 5 Screen Recorder Apps for Chrome Devices</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-deactivating-instagrams-igtv-feature/"><u>[Updated] In 2024, Deactivating Instagram's IGTV Feature</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-slidecasting-simplified-a-modern-webcam-approach/"><u>[New] 2024 Approved  Slidecasting Simplified  A Modern, Webcam Approach</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-freedom-in-fun-10-excellent-offline-gaming-on-android-devices/"><u>2024 Approved  Freedom in Fun  10 Excellent Offline Gaming on Android Devices</u></a></li>
</ul></div>
