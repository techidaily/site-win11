---
title: Mastery of Windows System Preferences to Adjust After Dark Mode
date: 2024-06-25T11:24:20.312Z
updated: 2024-06-26T11:24:20.312Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Mastery of Windows System Preferences to Adjust After Dark Mode
excerpt: This Article Describes Mastery of Windows System Preferences to Adjust After Dark Mode
keywords: Dark Mode Settings,Windows PC Configurations,Night Mode Systems,OS Preference Tweaks,Dusk Display Controls,System Bias Adjustment,Dark Interface Options
thumbnail: https://thmb.techidaily.com/6e815c1b64efb14276b71fc721777a9cc6b2edabdceffdbe6557dc25c31661ee.jpg
---

## Mastery of Windows System Preferences to Adjust After Dark Mode

 There are times when you need to step away from your PC, and if you’re gone long enough, the screen will automatically dim. Windows does this to preserve your battery, and you can adjust when your display should darken in the Power Options menu by editing the **Dim display after** option.

 If for some reason you can’t see the **Dim display after** option in the Power Options menu, or it’s there and you want to remove it, you can use PowerShell or the Registry Editor to show or hide it. Here’s how.

## How to Show or Hide the “Dim Display After” Option Using PowerShell

 First, launch Windows PowerShell. There are many [ways to open PowerShell on Windows](https://www.makeuseof.com/windows-open-command-prompt-powershell/), but the easiest method is to press **Win + S** to open Windows Search. Then, enter **powershell** in the search box and click on **Windows PowerShell** when it appears in the search results.

![windows powershell in the windows search results](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/windows-powershell-search.jpg)

 In PowerShell, enter the following command to show the **Dim Display after** option in the Power Options menu:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee -ATTRIB_HIDE

 To hide it, enter the following command:

powercfg -attributes SUB_VIDEO 17aaa29b-8b43-4b94-aafe-35f64daaf1ee +ATTRIB_HIDE

 After entering the command you want, hit the **Enter** key on your keyboard for PowerShell to execute it. Afterward, the **Dim display after** option should appear or disappear accordingly in the Power Options menu.

## How to Show or Hide the “Dim display after” Option Using the Registry Editor

 Considering how vital the [Windows Registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/) is for the smooth operation of Windows, you might want to [back up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before you edit it. Afterward, open the Registry Editor by pressing **Win + R**, typing **regedit** in the text box, and clicking **OK**.

![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/regedit.jpg)

 Click **Yes** to bypass the UAC prompt.

 In the address bar of the Registry Editor, copy and paste the following text into it:

HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Power\PowerSettings\7516b95f-f776-4464-8c53-06167f40cc99\17aaa29b-8b43-4b94-aafe-35f64daaf1ee

 On the right panel, double-click the **Attributes** entry to open it up for editing.

![the attributes entry in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/regedit-dim-display-after-attributes-entry.jpg)

 Then, in the **Value data** text box, enter **1** to hide **Dim display after** in the Power Options menu or **2** to show it.

![modifying the attributes dword in the windows registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/win-attributes-dword.jpg)

 Now you can open the Power Options menu (see [how to open the power options on Windows 10](https://www.makeuseof.com/windows-10-open-power-options/)) and check under **Display** to see if the **Dim display after** option is there or not.

## Controlling the “Dim Display After” Option in the Power Options Menu

 Now that you know how to show or hide **Dim display after**, you know what to do when you can’t find it in the Power Options menu or need to remove it. We recommend keeping it hidden and then bringing it up whenever you need it. This will make sure that no one messes with this important display setting when you’ve set it up perfectly.

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
<li><a href="https://win11.techidaily.com/streamlined-windows-a-start-free-of-ads/"><u>Streamlined Windows: A Start Free of Ads</u></a></li>
<li><a href="https://win11.techidaily.com/microsoft-teams-screen-share-issues-quick-fixes/"><u>Microsoft Teams Screen Share Issues: Quick Fixes</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-overcoming-windows-11-screensaver/"><u>The Ultimate Guide: Overcoming Windows 11 Screensaver</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-most-effective-windows-to-do-apps/"><u>Navigating the Most Effective Windows To-Do Apps</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-repeated-sign-in-alerts-team-collaboration-edition/"><u>Avoiding Repeated Sign-In Alerts: Team Collaboration Edition</u></a></li>
<li><a href="https://win11.techidaily.com/simple-steps-to-acquire-and-implement-microsoft-stores-application-bundles/"><u>Simple Steps to Acquire & Implement Microsoft Store's Application Bundles</u></a></li>
<li><a href="https://win11.techidaily.com/unwrapping-and-solving-isdonedll-failures-in-w10w11-oses/"><u>Unwrapping and Solving ISDone.dll Failures in W10/W11 OSes</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-photoshop-wont-launch-in-windows-1011/"><u>Troubleshooting PhotoShop Won't Launch in Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/reward-system-reboot-for-your-favorite-titles/"><u>Reward System Reboot for Your Favorite Titles</u></a></li>
<li><a href="https://win11.techidaily.com/flicker-free-windows-experience-step-by-step-guide/"><u>Flicker-Free Windows Experience: Step-by-Step Guide</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-restart-nubia-red-magic-8s-proplus-without-power-button-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Restart Nubia Red Magic 8S Pro+ Without Power Button | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-honor-100-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Honor 100 Pro | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/discovering-youtubes-green-magic-for-effective-filming-for-2024/"><u>Discovering Youtube's Green Magic for Effective Filming for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-the-ultimate-list-of-best-most-affordable-recorders/"><u>[New] 2024 Approved  The Ultimate List of Best, Most Affordable Recorders</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-tecno-pova-6-pro-5g-location-on-skout-drfone-by-drfone-virtual-android/"><u>How to Change Tecno Pova 6 Pro 5G Location on Skout | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-car-locator-apps-for-samsung-galaxy-a23-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Car Locator Apps for Samsung Galaxy A23 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/from-inquiry-to-insight-best-practices-for-story-based-polls/"><u>From Inquiry to Insight  Best Practices for Story-Based Polls</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-professional-motion-blur-techniques-for-digital-artists/"><u>[New] Professional Motion Blur Techniques for Digital Artists</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/a-step-by-step-to-mastering-instagram-chat-videos-for-2024/"><u>A Step-by-Step to Mastering Instagram Chat Videos for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/harmonizing-sounds-with-imagery-professional-strategies-to-boost-your-videography-for-2024/"><u>Harmonizing Sounds with Imagery Professional Strategies to Boost Your Videography for 2024</u></a></li>
</ul></div>
