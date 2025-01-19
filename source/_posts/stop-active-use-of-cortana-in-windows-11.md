---
title: Stop Active Use of Cortana in Windows 11
date: 2025-01-17T19:16:11.378Z
updated: 2025-01-19T02:22:53.975Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Stop Active Use of Cortana in Windows 11
excerpt: This Article Describes Stop Active Use of Cortana in Windows 11
keywords: Cortana Disabling Guide,Windows 11 Cortana Off Switch,Stop Cortana Activation Windows 11,Turn Off Cortana Windows 11,Disable Cortana in Windows 11,End Cortana Use in Windows 11,Windows 11 Cortana Shutdown Methods
thumbnail: https://thmb.techidaily.com/46162ff1d50cb6f1b35f044048a0b2464ebecd738e59505ca40bf7c4a2c48673.png
---

## Stop Active Use of Cortana in Windows 11

 Windows Copilot, Microsoft's new AI assistant, can assist you with a variety of tasks, such as answering questions, changing system settings, and creating AI images. However, if you're not a fan of Copilot or simply don't need it, you can remove its taskbar icon or disable it entirely on your Windows 11 PC. Here, we'll show you how.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to Remove the Copilot Icon From the Windows 11 Taskbar

 By default, the Copilot icon appears in the Windows 11 taskbar. However, if you prefer not to have it there but still want to use it occasionally, it's easy to hide the Copilot icon. Simply right-click anywhere on an empty spot on your taskbar and select **Taskbar settings**. In the Settings window that appears, turn off the toggle next to **Copilot**.

![Remove Copilot Icon From Windows 11 Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-copilot-icon-from-windows-11-taskbar.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qbuund2HKOQ?si=NaGHqIrx8hSL7gWV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 And that’s about it. Windows Copilot will be disabled on your PC. To re-enable it in the future, repeat the above steps and set the **TurnOffWindowsCopilot** DWORD value to 0\. You can also delete the **TurnOffWindowsCopilot** DWORD instead.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Get Rid of Copilot on Windows 11

 While Windows Copilot is a powerful tool, not everyone may want to use it. Fortunately, it’s possible to get rid of it. The above steps will help you achieve your goal, whether you want to keep Copilot out of sight or turn it off entirely.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-accessible-steps-to-proficiently-watch-facebook-live-feeds/"><u>[New] In 2024, Accessible Steps to Proficiently Watch Facebook Live Feeds</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-joke-jamboree-7-hilarious-plot-ideas-for-youtube-stars/"><u>[New] In 2024, Joke Jamboree 7 Hilarious Plot Ideas for YouTube Stars</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/he-ultimate-strategy-for-increasing-youtube-traffic/"><u>[New] The Ultimate Strategy for Increasing YouTube Traffic</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-meme-crafters-den/"><u>[Updated] Meme Crafter's Den</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/2024-approved-winters-chill-and-your-videos-selecting-heated-backdrops/"><u>2024 Approved Winter's Chill & Your Videos Selecting Heated Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-methods-for-graphics-driver-reinstatement-on-win1011/"><u>Efficient Methods for Graphics Driver Reinstatement on Win10/11</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-search-experience-with-fast-setup-for-bing-chat/"><u>Enhance Your Search Experience with Fast Setup for Bing Chat</u></a></li>
<li><a href="https://win11.techidaily.com/escape-problem-in-windows-effective-troubleshooting-steps/"><u>Escape Problem in Windows: Effective Troubleshooting Steps</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-uniting-data-units-windows-11-edition/"><u>Guide to Uniting Data Units: Windows 11 Edition</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-poco-m6-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Change Location on TikTok to See More Content On your Poco M6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-migrate-android-data-from-realme-c33-2023-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Migrate Android Data From Realme C33 2023 to New Android Phone? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/paving-your-way-to-a-working-charmap-on-windows/"><u>Paving Your Way to a Working CharMap on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-service-links-solutions-for-malwarebytes-failures/"><u>Reviving Service Links: Solutions for Malwarebytes Failures</u></a></li>
<li><a href="https://win11.techidaily.com/secure-connection-establishing-intels-network-protocols-in-windows/"><u>Secure Connection: Establishing Intel's Network Protocols in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-combat-wi-fi-woes-for-lol-in-windows/"><u>Steps to Combat Wi-Fi Woes for LoL in Windows</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-ultimate-guide-to-the-best-2024-hevc-converters-for-pcs-and-mac-systems/"><u>The Ultimate Guide to the Best 2024 HEVC Converters for PCs & MAC Systems</u></a></li>
<li><a href="https://article-posts.techidaily.com/top-live-streaming-hardware-encoder-and-equipment-you-should-know-for-2024/"><u>Top Live Streaming Hardware Encoder and Equipment You Should Know for 2024</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-and-solving-kodi-network-errors-failed-directory-access/"><u>Troubleshooting and Solving Kodi Network Errors: Failed Directory Access</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-windows-sound-issue-generic-device-alert/"><u>Troubleshooting Windows Sound Issue: Generic Device Alert</u></a></li>
</ul></div>

