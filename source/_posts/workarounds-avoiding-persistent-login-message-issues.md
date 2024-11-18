---
title: "Workarounds: Avoiding Persistent Login Message Issues"
date: 2024-11-15T20:03:46.169Z
updated: 2024-11-17T17:50:00.561Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Workarounds: Avoiding Persistent Login Message Issues"
excerpt: "This Article Describes Workarounds: Avoiding Persistent Login Message Issues"
keywords: Logout Troubleshooting,Steady Sign-In Errors,Fixing Login Rejections,Bypassing Access Denials,Eliminating Login Blocks,Avoiding Persistent Logins,Escape Signin Issues
thumbnail: https://thmb.techidaily.com/e5791482249db05b2c83cd0dadb655c84a6fd60d498599c2c81d00c0991581e6.jpg
---

## Workarounds: Avoiding Persistent Login Message Issues

 The network credentials on your PC are important because they prevent others from using your computer across the network. While this feature is essential to protect your important files and improve the overall security of your system, it can sometimes cause issues as well.

 A common problem is when the network credential manager keeps displaying the "Enter network credentials" dialog, even when you enter the correct credentials. In this guide, we will walk you through some troubleshooting methods you can try to fix this issue for good.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Modify the Advanced Sharing Settings

 An incorrectly set Advanced Sharing setting is one of the most common causes of this error. Ideally, your PC should be allowed to manage homegroup connections. You can also use the Advanced Sharing settings page to disable password-protected sharing, which will allow you to share files without needing to log in.

 Here is how you can configure the Advanced Sharing settings correctly:

1. Locate the network icon on your taskbar and right-click on it.
2. Choose **Network and Internet settings** from the context menu.  
![Network and Internet settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/network-and-internet-settings.jpg)
3. In the following window, select **Network and Sharing Center**.
4. Choose **Change advanced sharing settings** option in the left pane.
5. Now, enable the **Allow Windows to manage homegroup connections (recommended)** option under Homegroup connections.
6. Click **Save changes** (you will need administrative access for this).
7. Now, expand the **All Networks** section and enable the **Turn off password protected sharing** option.  
![Turn off password sharing option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/turn-off-pasword-sharing.jpg)
8. Hit the **Save changes** button to complete the process.

 After you've transferred the files, re-enable password-protected sharing so that others don't get easy access to your PC.

## 2\. Use Your Microsoft Account Credentials or the Computer's Name

 You can also try logging onto the target PC using the Microsoft account credentials instead of the local username and password.

 Alternatively, you can also try using the name of the computer you are using alongside your username in the text field associated with the Username. Do not enter a space, bar, or any other symbol between the names.

 If the problem is associated with the credentials, one of these two methods is likely to help you get rid of it for good.

## 3\. Manually Add the Credentials of the Target Computer to the Credential Manager

 Another way to fix the issue is by manually adding the credentials of the targeted computer in the Credential Manager and seeing if that makes a difference.

 Here is how you can do that:

1. Type "Credential Manager" into Windows Search and click **Open**.
2. Select **Windows Credential** and click on **Add a Windows Credential**.  
![Windows credentials](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/windows-credentials-1.jpg)
3. Now, add the username, computer name, and password of the computer you are trying to access. Check if you can now share files with the other device successfully.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027162/19272" target="_top" id="2027162">
  <img src="//a.impactradius-go.com/display-ad/19272-2027162" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027162/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Create a New User Account on Both Devices

 There are times when user accounts become corrupt and stop you from performing certain actions. If this has happened, either on your PC or the target computer, it can interrupt the file-sharing process.

 To fix this problem, first, try [switching to a different user account](https://www.makeuseof.com/windows-11-switch-user-accounts/) on your own computer and see if that works. If this strategy fails, then we recommend [creating a new user account](https://www.makeuseof.com/windows-11-create-local-user-account/) on both devices with the same username and password. Make sure that both accounts have administrative privileges. While you are at it, we also suggest temporarily disabling any third-party antivirus program that you might be using, as it can sometimes block network access.

 If the root of your issue was a corrupt user account, this should be enough to fix the issue.

## 5\. Restart the Credential Manager Service

 The issue might also be with the Credential Manager service itself instead of the targeted computer or the network settings of your device. In this method, we will first enable the Credential Manager service if the service is disabled.

 If it is working already, then we will proceed with restarting the service and see if that does the trick.

 Here is what you need to do:

1. Press **Win** \+ **R** to open Run.
2. Type services.msc in the Run and click **Enter**.
3. In the following window, look for the Credential Manager service and right-click on it.
4. Choose **Properties** from the context menu.
5. If the service is disabled, click on the **Start button** to enable it.
6. In case it is working already, click on the **Stop button**, wait for a few seconds, and then hit the **Start button**.
7. ![Credential Manager properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/credential-manager-properties.jpg)  
 Make sure that the Startup type is set to **Automatic**.  
![Credential Manager service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/credential-manager-service.jpg)
8. Click **Apply** \> **OK** to save the changes.

 Now try connecting to the targeted computer and see if you can do so without any problems.

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/1943750/22993" target="_top" id="1943750">
  <img src="//a.impactradius-go.com/display-ad/22993-1943750" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943750/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Make Changes to the Local Security Policy

 Several users also managed to fix the problem by modifying the settings of the "Accounts: Limit local account use of blank passwords to console logon only" policy. Here is how you can give it a try too:

1. Press the **Win** \+ **R** keys together to open Run.
2. Type "secpol.msc" in Run and click **Enter**.
3. In the following window, navigate to the following location:  
Local Policies > Security Options > Accounts: Limit local account use of blank passwords to console logon only
4. Choose **Disabled** and click **Apply** \> **OK** to save the changes.  
![Make changes to the Local Security Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/change-security-policy.jpg)
5. Restart your computer and check if the issue is resolved.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100534/7443" target="_top" id="2100534">
  <img src="//a.impactradius-go.com/display-ad/7443-2100534" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100534/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151868/7443" target="_top" id="2151868">
  <img src="//a.impactradius-go.com/display-ad/7443-2151868" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151868/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Try Using Safe Mode With Networking

 If the credentials you are entering and all the network configurations on the system are correct, something might have gone wrong on a system level.

 In this case, you can boot into Safe Mode to determine the cause of the issue. Safe Mode starts Windows with only the basic set of drivers and apps — the ones that are essential for the operating system to function.

 There are several types of Safe Mode including Minimal, Alternate Shells, Active Directory Repair, and Network. In this method, we will be booting Windows into Safe Mode with Networking. This mode launches Windows with the drivers and programs required to connect the system to the internet or other devices over the network.

 If the error at hand does not appear in Safe Mode, then there is a chance that malware or other software issues are causing the problem.

 Here is what you need to do:

1. Head over to the Start menu and click on the **Power button**.
2. Choose **Restart** while holding the **Shift key**.
3. Wait for the Windows to boot into the recovery mode and then choose **Troubleshoot** \> **Advanced Options**.
4. Navigate to **Startup Settings** \> **Restart**.
5. In the following window, press the **F5 key** on your keyboard to boot into Safe Mode with Networking.  
![Pick safe mode with Networking option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/Tweak-Startup-Settings-1.jpg)
6. Once you are logged into Safe Mode, try connecting to the device you were previously trying to connect to. If the error does not appear in Safe Mode, then you might want to report this issue to Microsoft’s official support team and wait for a fix from their side.

 In case you cannot access this Windows state using the steps outlined above, you can try [other ways of booting into Safe Mode](https://www.makeuseof.com/windows-11-boot-safe-mode/).

## Share Data Over Network Without Issues

 Windows has made it simpler to share your files and other data across networks, but there are times when you run into unexpected errors. Hopefully, one of the methods mentioned above did the trick for you in fixing the issue under consideration.

 A common problem is when the network credential manager keeps displaying the "Enter network credentials" dialog, even when you enter the correct credentials. In this guide, we will walk you through some troubleshooting methods you can try to fix this issue for good.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-stream.techidaily.com/new-explore-the-top-7-innovative-apps-for-effortless-youtube-live-broadcasts-on-iphone-and-android/"><u>[New] Explore the Top 7 Innovative Apps for Effortless YouTube LIVE Broadcasts on iPhone and Android</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-the-ultimate-list-of-discord-bots-to-amplify-your-server/"><u>[New] The Ultimate List of Discord Bots to Amplify Your Server</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-engage-audiences-with-impactful-podcast-descriptions-for-2024/"><u>[Updated] Engage Audiences with Impactful Podcast Descriptions for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-gifs-that-speak-volumes-unveiling-6-critical-strategies-for-memetic-design/"><u>[Updated] GIFs That Speak Volumes Unveiling 6 Critical Strategies for Memetic Design</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-analyzing-user-feedback-the-latest-on-lg-bp350-display-tech/"><u>2024 Approved Analyzing User Feedback The Latest on LG BP350 Display Tech</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-apple-iphone-14-drfone-by-drfone-virtual-ios/"><u>3 Ways to Fake GPS Without Root On Apple iPhone 14 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-a-personalized-experience-with-ms-store-themes/"><u>Crafting a Personalized Experience with MS Store Themes</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-diagnostic-tool-usage-creating-shortcuts-in-windows-1011/"><u>Efficient Diagnostic Tool Usage: Creating Shortcuts in WIndows 10/11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-photos-from-samsung-galaxy-a05s-by-fonelab-android-recover-photos/"><u>How to Rescue Lost Photos from Samsung Galaxy A05s?</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-craft-the-perfect-thumbnail-top-9-budget-friendly-tools/"><u>In 2024, Craft the Perfect Thumbnail Top 9 Budget-Friendly Tools</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-files-attributes-date-editing-techniques/"><u>Mastering Windows Files' Attributes: Date Editing Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/mend-the-disconnected-link-top-9-solutions-to-revive-your-bluetooth-in-win-11/"><u>Mend the Disconnected Link: Top 9 Solutions to Revive Your Bluetooth in Win 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/online-free-audio-file-convertor-mp3opus-to-ogg-conversion-by-movavi-kostenloos/"><u>Online Free Audio File Convertor: Mp3/Opus to Ogg Conversion by Movavi - Kostenloos!</u></a></li>
<li><a href="https://win11.techidaily.com/rapid-remedy-top-9-tips-for-a-stable-wwe-2k23-on-pc/"><u>Rapid Remedy: Top 9 Tips for a Stable WWE 2K23 on PC</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-windows-firewall-4-effective-strategies/"><u>Restoring Window's Firewall - 4 Effective Strategies</u></a></li>
<li><a href="https://win11.techidaily.com/specialized-application-of-local-policies-on-a-lone-users-profile/"><u>Specialized Application of Local Policies on a Lone User's Profile</u></a></li>
<li><a href="https://article-helps.techidaily.com/the-right-platform-for-content-creation-podcast-or-video/"><u>The Right Platform for Content Creation? Podcast or Video?</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-nearby-sharing-across-oses/"><u>The Ultimate Guide to Nearby Sharing Across OSes</u></a></li>
<li><a href="https://win11.techidaily.com/top-9-innovations-in-the-latest-windows-11-updates/"><u>Top 9 Innovations in the Latest Windows 11 Updates</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    