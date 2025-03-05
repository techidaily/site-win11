---
title: "Navigate Through Error Code 31: Restoring Your Internet Connection"
date: 2025-02-25T16:26:39.533Z
updated: 2025-03-04T19:15:15.255Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Navigate Through Error Code 31: Restoring Your Internet Connection"
excerpt: "This Article Describes Navigate Through Error Code 31: Restoring Your Internet Connection"
keywords: Fix Error 31,Connectivity Recovery,DNS Resolution,Router Troubleshoot,Network Reset Guide,Web Issue Solve,Internet Restore Tips
thumbnail: https://thmb.techidaily.com/cf88e87b734b5b9f59ddbd2f8f99680f9b1ec3ba8de831308f2fd3fe15c5bbed.jpg
---

## Navigate Through Error Code 31: Restoring Your Internet Connection

 Are you encountering an error message on Windows that reads "network adapter error code 31: this device is not working properly"? This error often occurs due to a corrupted or incorrect version of the network adapter driver installed on your PC.

 As such, let's explore all the ways to fix the network adapter error code 31 on Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Check for Any Pending Network Driver Updates

 First off, check to see if your network driver has any pending updates. While you can update the drivers for the device connected to your computer using Device Manager, we don't recommend it, as Device Manager often fails to find the most recent updates for the driver.

 You will most likely find the latest network driver on your computer manufacturer's website, so check who made your PC and visit their website for details. If you use an external network adapter, visit the adapter manufacturer's website instead.

 Additionally, you can also find new drivers using your manufacturer's proprietary system management tool. For example, with Lenovo and HP computers, you can use the Lenovo Vantage and HP Support Assistant utility to find and install new drivers for your network adapter and other devices.

## 2\. Perform a Driver Roll Back

 If you believe a recent driver update is causing the error, you can use the**Roll Back Driver** option to perform a rollback and reinstall the previous version of the network adapter driver.

To perform a network driver rollback:

1. Press**Win + R** to open Run.
2. Type**devmgmt** .**msc** and click**OK** to open Device Manager.
3. In Device Manager, expand the**Network Adapters** section.  
![device manager network adapter properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/device-manager-network-adapter-properties.jpg)
4. Right-click on your network device and select**Properties** .

5. In the**Properties** dialog, open the**Driver** tab.  
![device manager network driver roll back driver](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/device-manager-network-driver-roll-back-driver-1.jpg)
6. Click the**Roll Back Driver** button. If the option is**greyed out** , your computer doesn't have an older driver to perform a rollback. Check your manufacturer's website to see if they have older drivers in an archive.

7. Next, in the confirmation dialog, give a reason and click**Yes** .
8. Once the driver rollback is complete, check if the problem is resolved. If not, check if you can perform another rollback for the network device driver to see if that helps.

## 3\. Perform a Network Reset

 Windows 10 and 11 feature a "network reset" option. This will remove and reinstall the network drivers and other networking components to their factory defaults to help you fix network adapter issues on your computer.

To perform a network reset:

1. Press**Win + I** to open**Settings** .
2. Open the**Network & internet** tab in the left pane.
3. Click on**Advanced network settings** .
4. ![advanced network settings windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/advanced-network-settings-windows-11.jpg)  
 Next, click on**Network reset** .

5. ![advanced network settings windows 11 network reset](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/advanced-network-settings-windows-11-network-reset.jpg)  
 Click on**Reset now** and click**Yes** to rest your network settings.  

![advanced network settings windows 11 network reset reset now](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/advanced-network-settings-windows-11-network-reset-reset-now.jpg)
6. Your PC will restart during the process.

## 3\. Delete the Corrupted Network Config File on Older Machines

![delete config value registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/delete-config-value-registry-editor.jpg)

 On an older Windows Vista or XP computer, you can resolve the issue by tweaking a registry entry. You need to delete a corrupt config key in Registry Editor and then uninstall the device from Device Manager to fix the error.

 The following steps only apply to a Windows computer running Vista or XP.

1. Press**Win + R** to open**Run** .
2. Type**regedit** and click**OK** to open**Registry Editor** .
3. In Registry Editor, navigate to the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Network\`
4. In the right pane, locate the**Config** value.
5. Next, right-click on the**Config** value and select**Delete** .
6. Click**Yes** to confirm the action.

 Once the key is deleted, you'll need to remove and reinstall the network driver. You can do it using Device Manager, as shown in the step below.

 Note that modifications to some registry entries may fail due to insufficient permission issues. If you get an error when deleting the Config value, take full ownership of the registry key and then try again. Our guide on[how to take full ownership of registry keys on Windows 10](https://www.makeuseof.com/windows-10-full-ownership-registry/) will work on older systems too.

## 4\. Reinstall Your Network Adapter Driver

 You can manually uninstall your network adapter device and driver to perform a network reset on older Windows versions. You can use the reliable Device Manager to uninstall your network devices.

1. Open Device Manager (see[how to open Device Manager](https://www.makeuseof.com/windows-open-device-manager/) for detailed steps).
2. Next, expand the**Network Adapters** section.
3. Right-click on the network adapter and select**Uninstall Device.**  
![uninstall network device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-network-device-device-manager.jpg)
4. In the confirmation dialog, check the**Attempt to remove the driver for this device** option.  

![uninstall network driver device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/uninstall-network-driver-device-device-manager.jpg)
5. Click**Uninstall** to confirm the action.

 Once uninstalled, restart your PC. After the restart, Windows will automatically detect connected but unrecognized devices and install the necessary drivers.

 If Windows fails to install the driver, open**Device Manager** , right-click on your network adapter and select**Update driver** . You can also download the latest drivers from your computer manufacturer's website, as shown in step one.

## 6\. Perform a System Restore

 This error can occur if Windows modifies your network adapter settings during an update. You can use a restore point to undo the changes and restore the computer to its earlier state. Since Windows automatically creates a new restore point before installing an update, you should be able to find a recent restore point to undo the changes.

To perform a restore point:

1. Press the**Win** key and type**restore point.**
2. Click on**Create a restore point** from the search result.
3. In the**System Protection** dialog, click the**System Restore** button.  
![system properties system restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-properties-system-restore.jpg)
4. In the**System Restore** dialog, click**Next** to view all the available restore points. Additionally, check the**Show more restore points** option to view older restore points.

5. Select the most recent restore point and click**Next** .  
![system properties system restore](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-properties-system-restore.jpg)
6. Confirm your restore point and read the description to understand what apps and data on your PC are affected.
7. Click**Finish** to initialize the system restore process. Your PC will restart and may take some time to finish. Your PC will restart and show a system restore success or failure message.

 If the restore process fails, try it again. At times, it may take more than one attempt to get it right. If the computer is restored, it should hopefully restore the old network driver configuration and fix the error.

## Fix the Network Adapter Code 31 Error on Windows

 Network adapter code 31 is one of the many errors that can cause your network adapter to malfunction. To fix the error, check if you have the latest network adapter driver installed. If necessary, perform a driver rollback, clean up corrupt registry value or perform a system restore.

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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-in-depth-metaverse-engagement-examples/"><u>[New] 2024 Approved In-Depth Metaverse Engagement Examples</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-zero-cost-youtube-meetings-easy-to-host/"><u>[New] 2024 Approved Zero Cost Youtube Meetings Easy to Host</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-advanced-tech-roundup-nine-innovative-mic-recorders-for-web-23/"><u>[Updated] 2024 Approved Advanced Tech Roundup Nine Innovative Mic Recorders for Web ('23)</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-complete-roadmap-implementing-subtitle-track-within-mp4s/"><u>[Updated] Complete Roadmap Implementing Subtitle Track Within MP4s</u></a></li>
<li><a href="https://win11.techidaily.com/controlling-user-authentication-w11-from-a-domain-perspective/"><u>Controlling User Authentication: W11 From a Domain Perspective</u></a></li>
<li><a href="https://win11.techidaily.com/customize-windows-using-spotlight-pictures-for-dynamic-backdrops/"><u>Customize Windows: Using Spotlight Pictures for Dynamic Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-for-installing-kali-linux-on-pc/"><u>Essential Tips for Installing Kali Linux on PC</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-the-contrast-a-closer-look-at-gpt-4-vs-gpt-35/"><u>Exploring the Contrast: A Closer Look at GPT-4 Vs. GPT-3.5</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>How to use Snapchat Location Spoofer to Protect Your Privacy On Apple iPhone XR? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-productivity-filter-mastery-and-style-upgrade-in-windows-11s-task-manager/"><u>Maximizing Productivity: Filter Mastery & Style Upgrade in Windows 11'S Task Manager</u></a></li>
<li><a href="https://win11.techidaily.com/proposing-top-changes-for-the-taskbar-in-next-gen-windows-11-ux/"><u>Proposing Top Changes for the Taskbar in Next-Gen Windows 11 UX</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-local-sam-service-deactivated-message/"><u>Resolving 'Local SAM Service Deactivated' Message</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/revolutionary-videography-toolset-for-vimeo-users-for-2024/"><u>Revolutionary Videography Toolset for Vimeo Users for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/six-creative-strategies-for-using-chatgpt-in-your-writing-process/"><u>Six Creative Strategies for Using ChatGPT in Your Writing Process</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-approach-augmenting-virtual-memory-on-windows-11/"><u>Step-by-Step Approach: Augmenting Virtual Memory on Windows 11</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/step-by-step-fix-for-initialization-error-on-your-windows-10-pc/"><u>Step-by-Step Fix for 'Initialization Error' On Your Windows 10 PC</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-audio-workflow-win-five-free-editors/"><u>Streamline Audio Workflow: Win Five Free Editors</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-visual-experience-with-in-built-color-tuning-win11/"><u>Streamline Visual Experience with In-Built Color Tuning (Win11)</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/top-10-mobile-vr-headsets/"><u>Top 10 Mobile VR Headsets</u></a></li>
</ul></div>

