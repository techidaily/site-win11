---
title: A Simple Guide to Finding Out What Model You Run on Windows
date: 2024-07-02T13:04:46.478Z
updated: 2024-07-03T13:04:46.478Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes A Simple Guide to Finding Out What Model You Run on Windows
excerpt: This Article Describes A Simple Guide to Finding Out What Model You Run on Windows
keywords: Windows OS Model Info,Determine Windows Version,Identify Windows System Type,Discover Windows Installation,Find Windows Edition,Uncover Windows Suite,Windows Desktop Specification
thumbnail: https://thmb.techidaily.com/5835b7f75acb6f437f70d9b6865adddf58cf9307d1c89bac2789b98350d1bacd.jpg
---

## A Simple Guide to Finding Out What Model You Run on Windows

 Whether you want to find the correct hardware upgrade for your computer or want to fix an issue, knowing about your computer model name can come in handy in various situations. Here are 6 quick ways to check your computer model name on Windows.

## 1\. Using the Settings App

![Checking System Name in the Settings menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-name.jpg)

 The quickest way to check your computer model name and number is through the Settings app. Simply, launch the**Settings app** (see [how to open the Settings app on Windows](https://www.makeuseof.com/windows-ways-to-open-system-settings/) ) and choose**System** from the left sidebar. You'll see your computer model name at the top of the System window.

## 2\. Using the System Information App

 The System Information is the go-to place to [check your system information on Windows 11](https://www.makeuseof.com/windows-11-check-system-information/) . You can use it to know about your computer's hardware resources, components, and software environment.

 To see your computer model name using the System Information app, follow the below instructions:

1. Press the**Win + S** hotkeys to open**Windows Search.**
2. In the search bar, type**System Information** and choose**Open** from the right pane.  
![Typing System Information in Windows Search](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-information.jpg)
3. Choose**System Summary** from the left sidebar.
4. Check the**System Model** row in the right pane to know about your computer model name.  
![Checking System Model in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-model.jpg)

## 3\. Using the DirectX Diagnostic Tool

 The DirectX Diagnostic Tool contains information about the DirectX components and drivers installed on your computer. You can also use this tool to get information like System model, BIOS, Processor, Memory, Page file, and more.

 Here's how to use the DirectX Diagnostic Tool to know about your system model name:

1. Use one of the [many ways to open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. In the text field, type**dxdiag** and click**OK.**
3. Click the**System** tab in the DirectX Diagnostic Tool.
4. Under the System Information section, you can check your computer model name next to the**System Model** option.  
![System Model option in the DirectX Diagnostic Tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-model-option.jpg)

## 4\. Using the Command-Line Tools

 If you're an advanced Windows user, you can use the command-line tools, Windows PowerShell and Command Prompt, to know everything about your computer. Here's how to use the Command Prompt to check your computer model name:

1. Open the Windows Search, type**Command Prompt** in the search bar, and press Enter.
2. In the Command Prompt window, type**wmic csproduct get name** , and press Enter.  
![System model checking command in Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/system-model-checking-command.jpg)

You'll see the model name on the console screen.

 Now, to view the model name using Windows PowerShell, launch Windows PowerShell, type the following command, and press Enter.

`Get-CimInstance -ClassName Win32_ComputerSystem`

![Command to Check System name in Windows PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/command-to-check-system-name.jpg)

 In case you want to check your computer serial number, execute the following command in the PowerShell window.

`Get-CimInstance -ClassName Win32_bios`

![Command to Check System Serial number in PowerShell](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/command-to-check-system-serial-number.jpg)

## 5\. Using the Manufacturer's Assistant App

![Checking System name using HP Support Assistant](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/hp-support-assistant.jpg)

 Most manufacturers nowadays offer an assistant app using which you can check your computer model name and number. For instance, if you're using an HP laptop, you can download the [HP Support Assistant app](https://support.hp.com/us-en/help/hp-support-assistant) to know everything about your computer.

 Similarly, you can download the assistant app of your manufacturer to check your computer's name.

## 6\. By Entering the BIOS

 The Basic Input / Output System, aka BIOS, lets you configure basic computer settings like boot order, hardware components, and more. You can also use the BIOS menu to know every tiny detail about your computer.

 Here's how to [enter the BIOS menu on Windows](https://www.makeuseof.com/tag/enter-bios-computer/) and check your computer model name:

1. Open the Settings app, and choose**Windows Update** from the left sidebar.
2. Choose the**Advanced options.**
3. Under**Additional options,** select the**Recovery** option.
4. Click the**Restart now** button next to**Advanced startup.** Your computer will not boot into Recovery mode.  
![Restart now button next to Advanced startup](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/restart-now-button.jpg)
5. Navigate to**Troubleshoot** \>**Advanced options** \>**UEFI Firmware Settings** \>**Restart.**
6. Usually, your computer will now boot straight into UEFI BIOS. But in some manufacturers like HP, you'll be welcomed with a**Startup** **Menu.** Choose**System Information** from the menu.  
![Choosing System Information from the Startup menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/choosing-system-information.JPG)
7. You can check your computer name in the System Information section.  
![Checking Product name in System Information](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/checking-product-name.JPG)

## Get to Know Your Computer's Model on Windows

 These were all the working ways using which you can know your computer model name. However there are many other methods to check the name, but the ones mentioned above are among the quickest and easiest.

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
<li><a href="https://win11.techidaily.com/rog-ally-in-question-how-does-asus-stack-up/"><u>ROG Ally in Question: How Does ASUS Stack Up?</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-common-windows-11-pitfalls/"><u>Addressing Common Windows 11 Pitfalls</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-automatic-network-proxy-fixes/"><u>Mastering Windows' Automatic Network Proxy Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-for-remedying-outlook-failures/"><u>Essential Steps for Remedying Outlook Failures</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fix-guide-to-tackle-black-screens-on-windows-11/"><u>Quick-Fix Guide to Tackle Black Screens on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-color-management-glitches/"><u>Navigating Through Windows' Color Management Glitches</u></a></li>
<li><a href="https://win11.techidaily.com/growth-plans-for-windows-hard-drive-without-data-loss/"><u>Growth Plans for Windows Hard Drive without Data Loss</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-removing-null-space-in-your-system-drive/"><u>Step-by-Step Guide: Removing Null Space in Your System Drive</u></a></li>
<li><a href="https://win11.techidaily.com/configuring-windows-11-biometrics-permissions/"><u>Configuring Windows 11 Biometrics Permissions</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-2024-approved-boost-your-gameplay-auditory-experience-add-music-to-kinemaster-strategically/"><u>Updated 2024 Approved Boost Your Gameplay Auditory Experience Add Music to KineMaster Strategically</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/the-art-of-slow-motion-a-guide-for-instagrams-next-viral-reels-for-2024/"><u>The Art of Slow-Motion  A Guide for Instagram's Next Viral Reels for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-enhance-vr-experience-advanced-gopro-4k-editing/"><u>[New] In 2024, Enhance VR Experience  Advanced GoPro 4K Editing</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-tackle-typical-youtube-short-challenges/"><u>In 2024, Tackle Typical YouTube Short Challenges</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-2024-approved-premiering-popularity-amazon-prime-tweets-of-23/"><u>[New] 2024 Approved  Premiering Popularity  Amazon Prime Tweets of '23</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-yearly-insights-the-most-impactful-social-graphs/"><u>2024 Approved  Yearly Insights - The Most Impactful Social Graphs</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-special-features-virtual-location-on-motorola-edge-40-neo-drfone-by-drfone-virtual-android/"><u>In 2024, How To Use Special Features - Virtual Location On Motorola Edge 40 Neo? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-from-struggle-to-success-a-collection-of-best-practices-for-fb-profiles/"><u>[New] 2024 Approved  From Struggle to Success  A Collection of Best Practices for FB Profiles</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/easy-mastery-of-movie-capturing-from-pc-mac-and-mobile-devices-for-2024/"><u>Easy Mastery of Movie Capturing  From PC, Mac & Mobile Devices for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-explore-top-7-live-streaming-iosandroid-apps-perfect-for-youtube-channel-creators/"><u>[New] Explore Top 7 Live Streaming iOS/Android Apps Perfect for YouTube Channel Creators</u></a></li>
</ul></div>
