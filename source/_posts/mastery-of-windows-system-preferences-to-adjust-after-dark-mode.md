---
title: Mastery of Windows System Preferences to Adjust After Dark Mode
date: 2024-06-25T09:48:14.760Z
updated: 2024-06-26T09:48:14.760Z
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
<li><a href="https://win11.techidaily.com/immediate-solution-fixing-windows-auto-detect-proxy-errors/"><u>Immediate Solution: Fixing Windows' Auto Detect Proxy Errors</u></a></li>
<li><a href="https://win11.techidaily.com/explore-the-finest-free-media-tools-for-windows-pcs/"><u>Explore the Finest Free Media Tools for Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/keyboard-connoisseurs-guide-to-file-details/"><u>Keyboard Connoisseur's Guide to File Details</u></a></li>
<li><a href="https://win11.techidaily.com/windows-a-deep-dive-into-data-consumption-patterns/"><u>Windows: A Deep Dive Into Data Consumption Patterns</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-user-initiated-windows-screen-shift/"><u>Stopping User-Initiated Windows Screen Shift</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-and-set-up-windows-sandbox-in-windows-11/"><u>How to Enable and Set Up Windows Sandbox in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-broken-usb-connections-on-windows-systems/"><u>Tackling Broken USB Connections on Windows Systems</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-top-7-skype-hacker-to-hack-any-skype-account-on-your-samsung-galaxy-a54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Skype Hacker to Hack Any Skype Account On your Samsung Galaxy A54 5G | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-palette-perfection-in-11-step-by-step-lessons/"><u>[Updated] Palette Perfection in 11 Step-by-Step Lessons</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-is-ipogo-not-working-on-oppo-find-n3-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Oppo Find N3? Fixed | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-top-5-audio-capture-methods-in-windows-11-operating-system/"><u>[Updated] Top 5 Audio Capture Methods in Windows 11 Operating System</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-in-depth-insights-on-preserving-ps4-gaming-history/"><u>[New] In 2024, In-Depth Insights on Preserving PS4 Gaming History</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/the-ultimate-list-5-free-mov-video-merger-software-options-for-2024/"><u>The Ultimate List 5 Free MOV Video Merger Software Options for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-the-beginners-guide-to-weekly-virtual-office-hours/"><u>2024 Approved  The Beginner's Guide to Weekly Virtual Office Hours</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-streamlining-screenshot-tasks-in-minutes/"><u>[New] In 2024, Streamlining Screenshot Tasks in Minutes</u></a></li>
</ul></div>
