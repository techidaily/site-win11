---
title: Win11 Wi-Fi Data Metric Control Guide
date: 2024-06-25T11:22:58.813Z
updated: 2024-06-26T11:22:58.813Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Win11 Wi-Fi Data Metric Control Guide
excerpt: This Article Describes Win11 Wi-Fi Data Metric Control Guide
keywords: Win11 Wi-Fi Guide,Data Monitoring Win11,Wi-Fi Management Tool,Win11 Network Diagnostics,Data Usage Control Win11,Win11 Wi-Fi Optimization,Metric Analysis Win11
thumbnail: https://thmb.techidaily.com/75030bd59360efbfc2946329061573b90f37300b7251c4b711e0f5f10f28322c.jpg
---

## Win11 Wi-Fi Data Metric Control Guide

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to[launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the[Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.
6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

## Efficiently Manage Your Data With Metered Connection

 Enabling or disabling the metered connection option for Wi-Fi networks in Windows is relatively simple, regardless of the method you use.

 If you have a limited data plan, you can also set a data usage limit for your Wi-Fi connection. This way, Windows will notify you when you approach the set data limit.


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
<li><a href="https://win11.techidaily.com/correcting-unexpected-reference-to-token-in-win10win11/"><u>Correcting Unexpected Reference to Token in Win10/Win11</u></a></li>
<li><a href="https://win11.techidaily.com/leading-edge-lives-beyond-windows-11-expectations/"><u>Leading-Edge Lives: Beyond Windows 11 Expectations</u></a></li>
<li><a href="https://win11.techidaily.com/the-art-of-image-editing-efficiently-removing-backdrops/"><u>The Art of Image Editing: Efficiently Removing Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/delving-deep-into-windows-booting-mechanics-and-settings/"><u>Delving Deep Into Windows' Booting Mechanics and Settings</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-comic-experience-with-windows-11-techniques/"><u>Maximizing Comic Experience with Windows 11 Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/journey-to-greatness-your-ultimate-new-pc-apps/"><u>Journey to Greatness: Your Ultimate New PC Apps</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-gaming-displays-from-going-opaque-on-win-os/"><u>Preventing Gaming Displays From Going Opaque on WIN OS</u></a></li>
<li><a href="https://win11.techidaily.com/windows-subsystem-for-android-is-going-away-what-should-you-do-now/"><u>Windows Subsystem for Android Is Going Away: What Should You Do Now?</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-a-faulty-esc-key-in-windows-10-and-beyond/"><u>Troubleshoot a Faulty Esc Key in Windows 10 and Beyond</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-in-2024-auditory-landmarks-pinpointing-button-induced-sounds-in-software/"><u>New In 2024, Auditory Landmarks Pinpointing Button-Induced Sounds in Software</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-necessary-details-for-twitter-video-submissions-aspect-ratio-for-2024/"><u>[New] Necessary Details for Twitter Video Submissions (Aspect Ratio) for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-edge-of-innovation-secure-these-7-must-have-devices/"><u>2024 Approved  The Edge of Innovation  Secure These 7 Must-Have Devices</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-breaking-through-boundaries-with-hdr-in-editing/"><u>2024 Approved  Breaking Through Boundaries with HDR in Editing</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/the-essential-review-of-screen-recorders-for-mp4/"><u>The Essential Review of Screen Recorders for MP4</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-the-ultimate-list-10-best-video-editing-apps-for-vloggers-for-2024/"><u>Updated The Ultimate List 10 Best Video Editing Apps for Vloggers for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-free-online-video-editing-10-best-trimming-tools-and-software/"><u>In 2024, Free Online Video Editing 10 Best Trimming Tools and Software</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/tunetales-music-and-speech-review/"><u>TuneTales  Music and Speech Review</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-screensphere-comprehensively-global-plus-locally-connected/"><u>2024 Approved  ScreenSphere  Comprehensively Global + Locally Connected</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-audio-visual-vanguard-evaluating-the-best-classroom-recorders/"><u>[New] 2024 Approved  Audio-Visual Vanguard  Evaluating the Best Classroom Recorders</u></a></li>
</ul></div>
