---
title: Ceasing Voice-Activated AI on Windows 11
date: 2025-02-11T18:09:05.961Z
updated: 2025-02-16T02:07:29.895Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ceasing Voice-Activated AI on Windows 11
excerpt: This Article Describes Ceasing Voice-Activated AI on Windows 11
keywords: Voice Control Disabled,Windows 11 AI Offline,Turnoff WAIT 11,Deactivate AI Windows,Stop Cortana Windows,No Voice AI in Win 11,End Microsoft Voice AI
thumbnail: https://thmb.techidaily.com/71005eecdd2fec9bde2d87e54e71962fc2dc07f266aaf5068a5f2270c6aff62a.jpeg
---

## Ceasing Voice-Activated AI on Windows 11

 Windows Copilot, Microsoft's new AI assistant, can assist you with a variety of tasks, such as answering questions, changing system settings, and creating AI images. However, if you're not a fan of Copilot or simply don't need it, you can remove its taskbar icon or disable it entirely on your Windows 11 PC. Here, we'll show you how.

## How to Remove the Copilot Icon From the Windows 11 Taskbar

 By default, the Copilot icon appears in the Windows 11 taskbar. However, if you prefer not to have it there but still want to use it occasionally, it's easy to hide the Copilot icon. Simply right-click anywhere on an empty spot on your taskbar and select **Taskbar settings**. In the Settings window that appears, turn off the toggle next to **Copilot**.

![Remove Copilot Icon From Windows 11 Taskbar](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/remove-copilot-icon-from-windows-11-taskbar.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_wWybMqZEM?si=0nPjCQDLS2MCaQbG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This should remove the Copilot icon from the taskbar. You can still access Copilot by pressing the **Win + C** keyboard shortcut in Windows 11\.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 And that’s about it. Windows Copilot will be disabled on your PC. To re-enable it in the future, repeat the above steps and set the **TurnOffWindowsCopilot** DWORD value to 0\. You can also delete the **TurnOffWindowsCopilot** DWORD instead.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://common-error.techidaily.com/1723205352887-fixed-windows-smartscreen-cant-be-reached-right-now/"><u>[FIXED] Windows SmartScreen Can't Be Reached Right Now</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-amd-classic-bundle/"><u>[New] 2024 Approved AMD Classic Bundle</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-quickstream-simple-steps-for-live-podcast-broadcasting/"><u>[Updated] Quickstream Simple Steps for Live Podcast Broadcasting</u></a></li>
<li><a href="https://win-amazing.techidaily.com/biosecurity-policies-are-designed-to-address-the-full-spectrum-of-biological-threats-including-infectious-diseases-chemical-agents-and-radioactive-materials153/"><u>Biosecurity Policies Are Designed to Address the Full Spectrum of Biological Threats, Including Infectious Diseases, Chemical Agents, and Radioactive Materials</u></a></li>
<li><a href="https://win11.techidaily.com/discovering-the-art-of-international-mouse-usage-via-powertoys/"><u>Discovering the Art of International Mouse Usage via PowerToys</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-fix-windows-network-error-code-0x800704cf-ultimate-solution/"><u>How to Fix Windows Network Error Code 0X800704CF – Ultimate Solution</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-a-detailed-vpna-fake-gps-location-free-review-on-apple-iphone-se-2022-drfone-by-drfone-virtual-ios/"><u>In 2024, A Detailed VPNa Fake GPS Location Free Review On Apple iPhone SE (2022) | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-flawless-skin-in-fcpx-a-beginners-guide-to-plugin-free-retouching/"><u>New In 2024, Flawless Skin in FCPX A Beginners Guide to Plugin-Free Retouching</u></a></li>
<li><a href="https://win11.techidaily.com/professional-approach-to-rejuvenating-win11-dns-caches/"><u>Professional Approach to Rejuvenating Win11 DNS Caches</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-bluetooth-limitation-audio-alone-no-mutepause/"><u>Resolving Windows Bluetooth Limitation: Audio Alone, No Mute/Pause</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/seamless-integration-move-your-apple-music-playlists-to-youtube-music-and-back/"><u>Seamless Integration: Move Your Apple Music Playlists to YouTube Music and Back</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/social-simulacrum-sculpting-crafting-exaggerated-profiles/"><u>Social Simulacrum Sculpting Crafting Exaggerated Profiles</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-windows-update-hurdles-effortlessly/"><u>Tackling Windows Update Hurdles Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/win-logins-spotting-valid-and-invalid-credentials-entry-attempts/"><u>Win Logins: Spotting Valid and Invalid Credentials Entry Attempts</u></a></li>
</ul></div>

