---
title: Preventing Cortana Activation in Windows 11
date: 2024-09-11T23:33:32.538Z
updated: 2024-09-16T23:50:07.968Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Preventing Cortana Activation in Windows 11
excerpt: This Article Describes Preventing Cortana Activation in Windows 11
keywords: Stop Cortana,Disable Cortana Win11,Cortana Off Windows 11,Cortana Activation Prevention,Turn Off Cortana Windows 11,Deactivate Cortana in Win11,Cortana Shutdown for Windows 11
thumbnail: https://thmb.techidaily.com/d3f8a164ff7cec81bd719ff1860ad4b428bdab1ff70424914ce34922d708e742.jpg
---

## Preventing Cortana Activation in Windows 11

 Windows Copilot, Microsoft's new AI assistant, can assist you with a variety of tasks, such as answering questions, changing system settings, and creating AI images. However, if you're not a fan of Copilot or simply don't need it, you can remove its taskbar icon or disable it entirely on your Windows 11 PC. Here, we'll show you how.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Remove the Copilot Icon From the Windows 11 Taskbar

 By default, the Copilot icon appears in the Windows 11 taskbar. However, if you prefer not to have it there but still want to use it occasionally, it's easy to hide the Copilot icon. Simply right-click anywhere on an empty spot on your taskbar and select **Taskbar settings**. In the Settings window that appears, turn off the toggle next to **Copilot**.

![Remove Copilot Icon From Windows 11 Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-copilot-icon-from-windows-11-taskbar.jpg)

 This should remove the Copilot icon from the taskbar. You can still access Copilot by pressing the **Win + C** keyboard shortcut in Windows 11\.

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

 And that’s about it. Windows Copilot will be disabled on your PC. To re-enable it in the future, repeat the above steps and set the **TurnOffWindowsCopilot** DWORD value to 0\. You can also delete the **TurnOffWindowsCopilot** DWORD instead.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130528/26400" target="_top" id="2130528">
  <img src="//a.impactradius-go.com/display-ad/26400-2130528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130528/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Get Rid of Copilot on Windows 11

 While Windows Copilot is a powerful tool, not everyone may want to use it. Fortunately, it’s possible to get rid of it. The above steps will help you achieve your goal, whether you want to keep Copilot out of sight or turn it off entirely.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-video-recordings.techidaily.com/new-comparing-youtube-policies-with-creative-commons/"><u>[New] Comparing YouTube Policies with Creative Commons</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-watch-over-instagrams-friendship-shifts/"><u>[New] Watch Over Instagram's Friendship Shifts</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-honor-x8b-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Honor X8b? | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/fleeting-films-on-the-friendly-social-for-2024/"><u>Fleeting Films on the Friendly Social for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-maximum-performance-upgrade-to-new-geforce-rtx-2080-ti-graphics-drivers/"><u>Get Maximum Performance: Upgrade to New GeForce RTX 2080 Ti Graphics Drivers</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-can-i-get-more-stardust-in-pokemon-go-on-xiaomi-redmi-note-13-proplus-5g-drfone-by-drfone-virtual-android/"><u>How can I get more stardust in pokemon go On Xiaomi Redmi Note 13 Pro+ 5G? | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-call-logs-from-motorola-moto-g-stylus-2023-by-fonelab-android-recover-call-logs/"><u>How to retrieve erased call logs from Motorola Moto G Stylus (2023)?</u></a></li>
<li><a href="https://extra-support.techidaily.com/podcast-dominance-through-effective-seo-strategies-for-2024/"><u>Podcast Dominance Through Effective SEO Strategies for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/solving-the-issue-handbrake-cannot-rip-dvds-a-comprehensive-guide/"><u>Solving the Issue: HandBrake Cannot Rip DVDs – A Comprehensive Guide</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-capturing-audio-from-tunein-radio-app-on-windows-11/"><u>Step-by-Step Guide: Capturing Audio From TuneIn Radio App on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/teams/"><u>Teamsミーティングの録画編集：効果的なソフトウェアと技術ガイド</u></a></li>
<li><a href="https://win11.techidaily.com/the-insightful-guide-to-unlocking-the-secrets-of-cpi-files-an-easy-step-by-step-opener/"><u>The Insightful Guide to Unlocking the Secrets of CPI Files: An Easy Step-by-Step Opener</u></a></li>
<li><a href="https://win11.techidaily.com/top-2024-video-audio-editing-software-and-apps-recommendations/"><u>Top 2024 Video Audio Editing Software & Apps - Recommendations</u></a></li>
<li><a href="https://win11.techidaily.com/top-questions-answered-exploring-the-features-of-a-complimentary-video-transformation-tool/"><u>Top Questions Answered: Exploring the Features of a Complimentary Video Transformation Tool</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-movie-magic-for-minis-teach-your-child-to-create-their-own-films/"><u>Updated Movie Magic for Minis Teach Your Child to Create Their Own Films</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    