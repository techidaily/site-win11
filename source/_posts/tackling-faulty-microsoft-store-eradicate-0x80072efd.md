---
title: "Tackling Faulty Microsoft Store: Eradicate 0X80072EFD"
date: 2024-06-25T11:43:35.269Z
updated: 2024-06-26T11:43:35.269Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Tackling Faulty Microsoft Store: Eradicate 0X80072EFD"
excerpt: "This Article Describes Tackling Faulty Microsoft Store: Eradicate 0X80072EFD"
keywords: Microsoft Store Errors,XAS0072EFDC Fix,Error Code 0X80072efd,Microsoft Purchase Issue,Windows Store Faulty,Fixing Store Glitches,Microsoft Online Shopping Errors
thumbnail: https://thmb.techidaily.com/9333e7c75e292a0b83b1e16b6df5d6742dede6cee3e1ad9fc6da9c95dfc95571.jpg
---

## Tackling Faulty Microsoft Store: Eradicate 0X80072EFD

 Users have reported a 0x80072EFD Microsoft Store error on support forums that can arise in Windows 11 or 10\. Those users see a "server stumbled" or "check your internet connection" message with a 0x80072EFD error code inside MS Store after launching that app. When this error pops up, users can't utilize the Microsoft Store.

 The 0x80072EFD error is often a connection-related one. However, it occurs even when users can surf the web in their browsers. If you need to fix the 0x80072EFD error, try fixing it with these potential resolutions.

## 1\. Run the Windows Store App Troubleshooter

 Running the Windows Store App troubleshooter is a straightforward potential resolution for the 0x80072EFD error to start with. That troubleshooting tool might detect issues and give you a fix. You can open and run the Windows Store App troubleshooter like this:

1. Press**Start** and click the menu shortcut to open Settings.
2. Select the**Troubleshoot** section of Settings.
3. Click on**Other trouble-shooters** to look through the troubleshooting tools.
4. Select Windows Store Apps'**Run** option to bring up that troubleshooting tool.  
![The troubleshooter list in Settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/troubleshooter-list-in-windows-11.jpg)
5. Go through and apply any suggestions the troubleshooter offers.  
![The Windows Store Apps troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/windows-store-apps.jpg)

**Internet Connections** is another troubleshooter that may be useful for fixing the Microsoft Store's 0x80072EFD error. So, consider running that troubleshooter if the Windows Store Apps option doesn't help.

 Note that the troubleshooting tools are accessible in the**Update & Security** category in the Settings app if you use Windows 10\. Click the**Troubleshoot** tab and**Additional troubleshooters** option to access them from there. Then press the**Run this troubleshooter** buttons for Windows Store Apps or Internet Connections.

## 2\. Refresh the SoftwareDistribution Folder

 SoftwareDistribution is a folder for temporarily storing Windows update files. Sometimes refreshing that folder by renaming it can resolve error**0x80072EFD** . Rename the SoftwareDistribution folder like this:

1. Hold down the**Windows** key and press**S** to access a search utility.
2. Type in**cmd** to find a Command Prompt app.
3. Open Command Prompt with elevated permissions by clicking its**Run as administrator** option in the search tool.
4. Turn off some services by executing these separate commands:  
`net stop wuauserv  
net stop cryptSvc  
net stop bits  
net stop msiserver`
5. To rename SoftwareDistribution, type in the following and hit**Enter** :  
`ren C:\Windows\SoftwareDistribution SoftwareDistribution.old`  
![The rename SoftwareDistribution.old folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/rename-softwaredistribution-old-folder.jpg)
6. Also, rename a catroot2 directory with this command:  
`ren C:\Windows\System32\catroot2 catroot2.old`  
![The rename catroot2 command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/rename-catroot2-command.jpg)
7. Restart the turned-off services by inputting and executing the following commands:  
`net start wuaserv  
net start cryptSvcc  
net start bits  
net start msiserver`
8. Then bring up your Start menu to select**Restart** .

## 3\. Reset the Microsoft Store's Cache

 Microsoft store has a cache in which data accumulates. Resetting or clearing that cache's data is a reliable solution to various Microsoft Store issues. So, we recommend users try doing that when troubleshooting the 0x80072EFD error. You can clear that cache in Settings, as covered in our[guide for resetting apps](https://www.makeuseof.com/windows-reset-app/) in Windows 11 and Windows 10.

![The Reset button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-button.jpg)

## 4\. Turn Off Proxy Server

 Some users who've needed to fix error 0x80072EFD have confirmed they resolved that issue by turning off the proxy server setting. That's because a proxy server generated a Microsoft Store connection issue on those users' PCs. You can check if a proxy server is enabled on your PC and disable it in the following steps:

1. Start the Run dialogue by pressing**Win** +**R** .
2. Type**inetcpl.cpl** inside Run's command box and click**OK** to open Internet Options.
3. Select**Connections** \>**LAN settings** to reach a**Use a proxy server** setting.  
![The LAN settings button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/advanced-tab.jpg)
4. Uncheck the checkbox for**Use a proxy server** if it's selected.
5. Click the**Automatically detect settings** option to select it.  
![The Use a proxy server for your LAN checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/use-a-proxy-server-option.jpg)
6. Select the Local Area Network window's**OK** option.

## 5\. Double-Check the Time Settings in Windows

 An incorrect region time on your PC is another potential cause for error 0x80072EFD. Users have confirmed they've fixed error 0x80072EF by adjusting time settings on their PCs. The Microsoft Store's time tracking needs to sync with the PC's set regional time. So, have a look through your time settings as follows:

1. [Open up Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) , and click that app's**Time & language** tab.
2. Click**Date & time** to view those settings.  
![The Date & time navigation option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/date-time-tab.jpg)
3. Select to turn off the**Set time zone** option there.
4. Make sure the correct time zone for your location is selected in the**Time Zone** drop-down menu.  
![The Set the time zone automatically option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/set-the-time-automatically-option.jpg)
5. Then press the**Sync now** button.  
![The Sync now button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/sync-now-button.jpg)

 Alternatively, you can manually set the time by disabling the Set the time automatically option. Press the**Change** button for the**Set the date and time manually** option. Check the date and exact time for your location via online sources, and then enter it inside the**Change date & time** box.

## 6\. Enable TLS Protocols

 TLS is an encryption protocol that ensures your data privacy online. It's widely used and is essential for security when your computer communicates with internet servers.

1. Open Internet Options as specified in the first two steps for the fourth resolution.
2. Then select**Advanced** inside the Internet Options window.
3. Scroll down to the**Security** section on the**Advanced** tab.
4. Select the**TLS 1.0** ,**1.1** ,**1.2** , and**1.3** checkboxes there.  
![The Advanced tab in Internet Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/the-advanced-tab.jpg)
5. Click**Apply** to set the protocol options.
6. Select**OK** to exit the Internet Options window.

## 7\. Reregister Microsoft Store

 You can't reinstall Microsoft Store like other apps. However, reregistering it with PowerShell is similar to reinstalling. If other potential solutions don't fix the 0x80072EFD error, reregistering MS Store is worth a try. This is how you can register that app:

1. Activate the**Type here to search** box with that tool's**Windows** +**S** hotkey.
2. Enter**PowerShell** within that tool's search box.
3. Launch Windows PowerShell with elevated permissions by clicking that search result's**Run as administrator** option.
4. Input this command for reregistering MS Store and hit**Return** to execute:  
`Get-AppxPackage -AllUsers *WindowsStore* | Foreach {Add-AppxPackage -DisableDevelopmentMode -Register "$($_.InstallLocation)\AppXManifest.xml"}`  
![The reregister MS Store command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reregister-ms-store-command.jpg)
5. Wait until you're sure the command has finished.
6. Then exit PowerShell, and select the**Restart** option.

## 8\. Reset Your Network

 Resetting network settings in Windows is another 0x80072EFD error fix that's worked for some users. Note that this measure will erase Wi-Fi and Ethernet connection details, so you'll need to re-establish your connection after applying it. You can apply this potential fix as covered in our[how-to reset networks in Windows 11](https://www.makeuseof.com/reset-network-settings-windows-11/) guide.

![The Reset now button for networks](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/12/reset-now-network-option.jpg)

## Get Shopping in Microsoft Store Again

 The 0x80072EFD error isn't always easy to fix, and you may have to try applying quite a few potential resolutions to get it sorted. However, many Microsoft Store users have fixed the 0x80072EFD error with the solutions in this guide. So, maybe one of those potential fixes will also work on your PC.

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
<li><a href="https://win11.techidaily.com/clear-communication-how-to-test-microphone-on-windows-pre-call/"><u>Clear Communication: How to Test Microphone on Windows Pre-Call</u></a></li>
<li><a href="https://win11.techidaily.com/1719376947968-regain-your-account-in-microsoft-store-now/"><u>Regain Your Account in Microsoft Store, Now!</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-snap-open-apps-in-windows-11/"><u>Swiftly Snap Open Apps in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unable-to-display-errors-in-microsoft-store/"><u>Overcoming 'Unable to Display' Errors in Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/mending-ms-store-malfunctions-error-code-0x80072f17-solution/"><u>Mending MS Store Malfunctions: Error Code 0X80072f17 Solution</u></a></li>
<li><a href="https://win11.techidaily.com/construct-a-stunning-slide-show-with-windows-11s-free-methods/"><u>Construct a Stunning Slide Show with Windows 11'S FREE Methods</u></a></li>
<li><a href="https://win11.techidaily.com/no-illusions-allowed-true-tales-of-unmasking-windows-ploys/"><u>No Illusions Allowed: True Tales of Unmasking Windows Ploys</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-process-for-downloading-adobe-on-microsoft-store/"><u>The Complete Process for Downloading Adobe on Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-note-visibility-in-win-11/"><u>Maximizing Note Visibility in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/advanced-image-editing-techniques-for-subject-isolation/"><u>Advanced Image Editing: Techniques for Subject Isolation</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-samsung-galaxy-s24plus-drfone-by-drfone-virtual-android/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Samsung Galaxy S24+? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-a-step-by-step-approach-to-ad-revenue-in-youtube-videos/"><u>[New] 2024 Approved  A Step-by-Step Approach to Ad Revenue in YouTube Videos</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-honor-x8b-drfone-by-drfone-virtual-android/"><u>In 2024, Unova Stone Pokémon Go Evolution List and How Catch Them For Honor X8b | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unveiling-the-art-of-slow-motion-utilizing-online-platforms-and-photos/"><u>[New] Unveiling the Art of Slow Motion  Utilizing Online Platforms & Photos</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-2024-approved-mac-video-editor-showdown-the-best-options-for/"><u>Updated 2024 Approved Mac Video Editor Showdown The Best Options For</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/2024-approved-hear-the-difference-effective-strategies-for-silencing-background-chatter-online/"><u>2024 Approved Hear the Difference Effective Strategies for Silencing Background Chatter Online</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-unveiling-igtv-your-ultimate-tutorial/"><u>In 2024, Unveiling IGTV  Your Ultimate Tutorial</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-make-your-videos-pop-expert-advice-on-resizing-for-social-media-success-for-2024/"><u>Updated Make Your Videos Pop Expert Advice on Resizing for Social Media Success for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-storytelling-in-cinema-from-idea-to-actuality/"><u>In 2024, Storytelling in Cinema  From Idea to Actuality</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-apple-iphone-15-pro-max-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Change Your Apple iPhone 15 Pro Max Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
</ul></div>
