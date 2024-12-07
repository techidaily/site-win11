---
title: Deactivating Windows Copilot Mechanism
date: 2024-11-30T10:03:49.709Z
updated: 2024-12-07T04:00:57.460Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deactivating Windows Copilot Mechanism
excerpt: This Article Describes Deactivating Windows Copilot Mechanism
keywords: Deactivate AutoAssist,Turn Off Microsoft Pilot,Disable PC Assistant,Cease Automatic Aid,End Windows Helper,Stop System Guide,Shut Down Autopilot Windows
thumbnail: https://thmb.techidaily.com/8009d92085bbb2b59b0e3b6dadde39baefbadc66eb27ccbe212107fc43a67273.jpg
---

## Deactivating Windows Copilot Mechanism

 Windows Copilot, Microsoft's new AI assistant, can assist you with a variety of tasks, such as answering questions, changing system settings, and creating AI images. However, if you're not a fan of Copilot or simply don't need it, you can remove its taskbar icon or disable it entirely on your Windows 11 PC. Here, we'll show you how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Remove the Copilot Icon From the Windows 11 Taskbar

 By default, the Copilot icon appears in the Windows 11 taskbar. However, if you prefer not to have it there but still want to use it occasionally, it's easy to hide the Copilot icon. Simply right-click anywhere on an empty spot on your taskbar and select **Taskbar settings**. In the Settings window that appears, turn off the toggle next to **Copilot**.

![Remove Copilot Icon From Windows 11 Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-copilot-icon-from-windows-11-taskbar.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DEqoiNArwjQ?si=oaL_lgnI-RxY5Qy_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This should remove the Copilot icon from the taskbar. You can still access Copilot by pressing the **Win + C** keyboard shortcut in Windows 11\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Completely Disable Copilot via Group Policy Settings

 Although hiding the Copilot is quite easy, it does not turn it off completely, and you might inadvertently access it. Fortunately, you can turn off Copilot completely via the Local Group Policy Editor on PCs running the Professional, Education, or Enterprise edition of Windows 11\.

 If you are using Windows 11 Home, skip to the Registry Editor method below or use a [workaround to enable the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the search box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **User Configuration > Administrative Templates > Windows Components > Windows Copilot**.
5. Double-click the **Turn off Windows Copilot** policy on your right.
6. Select the **Enabled** option.
7. Hit **Apply** followed by **OK**.  
![Turn Off Windows Copilot Using the Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-group-policy-editor.jpg)

 Once you complete the above steps, Copilot will be disabled on your Windows 11 PC and you won't be able to access it even with the keyboard shortcut. If you want to re-enable Copilot later, repeat the above steps and set the **Turn off Windows Copilot** policy to **Not configured** or **Disabled**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Completely Disable Copilot by Modifying Registry Files

 Another way to disable Copilot on Windows 11 involves modifying registry files. However, since editing the registry can be risky, you should follow the steps carefully. Also, be sure to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/). This will allow you to restore the registry files in case something goes wrong.

 Once you’ve done that, here’s what you need to do to disable Copilot via the Registry Editor:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter** to open the Registry Editor.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_CURRENT\_USER > Software > Policies > Microsoft > Windows**.
5. Right-click the **Windows** key and select **New > Key**. Name it **WindowsCopilot**.
6. Right-click on the **WindowsCopilot** DWORD, go to **New**, and select **DWORD (32-bit) Value** from the submenu. Name the DWORD **TurnOffWindowsCopilot**.
7. Double-click the **TurnOffWindowsCopilot** DWORD, type **1** in the text field, and click **OK**.
8. Restart your PC for the changes to take effect.  
![Turn Off Windows Copilot Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/turn-off-windows-copilot-using-the-registry-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 And that’s about it. Windows Copilot will be disabled on your PC. To re-enable it in the future, repeat the above steps and set the **TurnOffWindowsCopilot** DWORD value to 0\. You can also delete the **TurnOffWindowsCopilot** DWORD instead.

## Get Rid of Copilot on Windows 11

 While Windows Copilot is a powerful tool, not everyone may want to use it. Fortunately, it’s possible to get rid of it. The above steps will help you achieve your goal, whether you want to keep Copilot out of sight or turn it off entirely.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-blog.techidaily.com/n-2024-leverage-timestamps-tactics-to-skyrocket-video-views/"><u>[New] In 2024, Leverage Timestamps Tactics to Skyrocket Video Views</u></a></li>
<li><a href="https://win11.techidaily.com/cranking-cadence-select-tools-that-elevate-pc-sound-past-limit/"><u>Cranking Cadence: Select Tools That Elevate PC Sound Past Limit</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-erase-an-apple-iphone-15-plus-without-apple-id-by-drfone-ios/"><u>How to Erase an Apple iPhone 15 Plus without Apple ID?</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-expert-insights-into-youtube-thumbnail-design/"><u>In 2024, Expert Insights Into YouTube Thumbnail Design</u></a></li>
<li><a href="https://techtrends.techidaily.com/key-factors-for-choosing-the-perfect-smartwatch-before-you-buy/"><u>Key Factors for Choosing the Perfect Smartwatch Before You Buy</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/new-in-2024-top-9-free-tv-streaming-services-or-sites-to-use/"><u>New In 2024, Top 9 Free TV Streaming Services or Sites To Use</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-connection-woes-link-your-airpods-to-windows-11-with-ease/"><u>Overcoming Connection Woes: Link Your AirPods to Windows 11 with Ease</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-1011-files-removing-the-lockdown/"><u>Overcoming Windows 10/11 Files: Removing the Lockdown</u></a></li>
<li><a href="https://win11.techidaily.com/reimagining-os-functionality-with-ai-integration/"><u>Reimagining OS Functionality with AI Integration</u></a></li>
<li><a href="https://win-dash.techidaily.com/steelseries-engine-free-download-on-windows-10/"><u>SteelSeries Engine: FREE Download on Windows 10</u></a></li>
<li><a href="https://win-guides.techidaily.com/ultimate-solutions-why-your-iphones-shared-albums-may-be-missing-and-how-to-display-them/"><u>Ultimate Solutions: Why Your iPhone's Shared Albums May Be Missing and How to Display Them</u></a></li>
<li><a href="https://win11.techidaily.com/unpacking-windows-11s-enhanced-update-schedule-what-it-means-for-users/"><u>Unpacking Windows 11’S Enhanced Update Schedule: What It Means For Users</u></a></li>
<li><a href="https://win11.techidaily.com/winning-at-roblox-minimize-latency-for-max-fps/"><u>Winning at Roblox: Minimize Latency for Max FPS</u></a></li>
<li><a href="https://win11.techidaily.com/winxpvista7-users-redefine-mouse-trail-style/"><u>WinXP/Vista/7 Users: Redefine Mouse Trail Style</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    