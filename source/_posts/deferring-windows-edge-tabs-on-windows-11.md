---
title: Deferring Windows Edge Tabs on Windows 11
date: 2024-12-06T13:49:43.141Z
updated: 2024-12-13T08:27:39.582Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Deferring Windows Edge Tabs on Windows 11
excerpt: This Article Describes Deferring Windows Edge Tabs on Windows 11
keywords: Defer Edge Tabs,Windows 11 Delaying Tabs,Postpone Windows Tab Activation,Windows Edge Tabs Pause,Tabs Onset Deferral Win11,Windows 11 Tab Stagger,Hold Off Windows Tab Start
thumbnail: https://thmb.techidaily.com/8e847bcd25e1bb956f9c0d5ed5c3e1ee40f922a7b0a9cd027835fb97af58ec95.jpg
---

## Deferring Windows Edge Tabs on Windows 11

 Microsoft Edge is the default browser in Windows and comes pre-installed on the operating system without any easy way of getting rid of it. The browser uses "tab preloading," which preloads the Start and New Tab page while you sign in to your PC.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.

## 1\. How to Disable Edge Tab Preloading Using the Group Policy Editor

 Windows Pro, Education, and Enterprise users get the perks of the Group Policy Editor by default. You can use it to configure system policies on your PC and personalize it. If you're on Windows Home, check out [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before continuing.

 Repeat the following steps to disable Edge tab preloading using the Group Policy Editor:

1. Press **Win + S** to open Windows Search. Type **gpedit.msc** in the text box and press the **Enter** key to open the Group Policy Editor.
2. Click on the **User Configuration** option in the left-hand side pane.
3. Navigate to **Administrative Templates > Windows Components > Microsoft Edge**.
4. Find the “**Allow Microsoft Edge to start and load the Start and New Tab page at Windows startup and each time Microsoft Edge is closed**” policy. Right-click on it and select the **Edit** option from the context menu.  
![Disable Microsoft Edge Tab Preloading Using GPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-gpe.jpg)
5. Click on the **Enabled** radio button.
6. Scroll down and click on the drop-down list next to the **Configure tab preloading** option. Select the **Prevent tab preloading** option.
7. Click on the **Apply** button. Then click on the **OK** button to save the changes.  
![Disable Microsoft Edge Tab Preloading Using GPE 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-gpe-2.jpg)
8. **Exit** the Group Policy Editor window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9. **Restart** your PC for the policy changes to take effect and disable the tab preloading feature.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5gTm5KxtQ0?si=onF1rBS2nEM5nLGg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Disable Edge Tab Preloading Using the Registry Editor

 If you use the Home version of Windows 11, it may be easier to take a different approach instead of going through the Group Policy Editor method. If you want, you can tweak the registry manually to disable the Edge tab preloading feature in Windows 11\. Repeat the following steps to do so:

 Before making changes to the Windows Registry, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) for safety purposes.

1. Press **Win + R** to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/). Type **regedit** in the text box and press the **Enter** key.
2. Go to the address bar at the top and click on it. Paste the following path in the text box and press the **Enter** key:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main
3. Go to the right-hand side section and right-click on the empty area. Select **New > DWORD (32-bit) Value**.
4. Click on the newly created DWORD value and name it “**AllowPrelaunch**”.
5. Right-click on the **AllowPrelaunch** value and select the **Modify** option from the context menu.
6. Go to the **Value Data** field and type **0** in it. Set the **Base** to **Hexadecimal** and click on the **OK** button.  
![Disable Microsoft Edge Tab Preloading Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-registry-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Now, you need to create a new subkey and add a new DWORD value:

1. Right-click on the Microsoft Edge key and select the **New > Key** option.
2. Name the key “**TabPreloader**” and click on it to select it.
3. Go to the right-hand side section and right-click on it. Select **New > DWORD (32-bit) Value**.
4. Click on the DWORD value and name it “**AllowTabPreloading**”.
5. Right-click on the **AllowTabPreloading** value and select the **Modify** option.
6. Go to the **Value Data** field and type **0** in it. Set the **Base** to **Hexadecimal** and click on the **OK** button.  
![Disable Microsoft Edge Tab Preloading Using Registry Editor 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-registry-editor-2.jpg)
7. **Close** the Registry Editor window.
8. **Restart** your PC to apply the changes made to the registry.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. How to Disable Edge Tab Preloading Using CMD or PowerShell

 If you find the Registry Editor method too cumbersome, you can use the Command Prompt or PowerShell to modify the Registry and disable Edge tab preloading. Here’s how to do it:

1. [Open the Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) on your PC.
2. Execute the following commands to add two new registry entries:  
`reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main" /v AllowPrelaunch /t REG_DWORD /d 00000000 /f  
 reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\TabPreloader" /v AllowTabPreloading /t REG_DWORD /d 00000000 /f`
3. **Close** the Command Prompt window and **restart** your PC.  
![Disable Microsoft Edge Tab Preloading Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-cmd.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DEqoiNArwjQ?si=oaL_lgnI-RxY5Qy_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. How to Disable Edge Tab Preloading Using the Ultimate Windows Tweaker App

 You can also use a third-party app like the Ultimate Windows Tweaker to disable Edge tab preloading in Windows 11\. Download the [Ultimate Windows Tweaker](https://www.thewindowsclub.com/ultimate-windows-tweaker-4-windows-10) app and install it on your PC. After that, repeat the following steps:

1. Press **Win + S** to open the Windows Search app. Type **Ultimate Windows Tweaker** and then click on the **Run as administrator** option.
2. Click on the **Search For Tweaks** option. Type “**edge tab**” in the search box and click on the **Go** button.  
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker.jpg)
3. Click on the **Disable Edge Tab Preloading** checkbox to enable it. Then, click on the **Apply Tweaks** button.  
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker-2.jpg)
4. **Close** the Ultimate Windows Tweaker app and **restart** your PC to apply the changes.

## Disable Edge Tab Preloading for Good on Windows 11

 Edge tab preloading serves no useful purpose if you use other browsers. You can disable it using the Group Policy Editor or the Registry Editor. Lastly, if you want a GUI app to disable the feature, you can use the Ultimate Windows Tweaker app.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://video-capture.techidaily.com/updated-deciding-between-obs-and-streamlabs-for-live-broadcasting-for-2024/"><u>[Updated] Deciding Between OBS and Streamlabs for Live Broadcasting for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-dividing-footage-top-splitcams-worth-in-review/"><u>[Updated] In 2024, Dividing Footage Top SplitCam's Worth in Review?</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-twice-the-joy-television-looping-of-online-video/"><u>[Updated] In 2024, Twice the Joy Television Looping of Online Video</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-inside-polarr-the-powerhouse-photo-toolkit-for-2024/"><u>[Updated] Inside Polarr The Powerhouse Photo Toolkit for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/combating-windows-errors-fixed-error-x80072f17-in-microsoft-store/"><u>Combating Windows Errors: Fixed Error X80072F17 in Microsoft Store</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-defeating-error-code-0x80246007-in-w10w11-os/"><u>Decoding and Defeating Error Code 0X80246007 in W10/W11 OS</u></a></li>
<li><a href="https://tech-hub.techidaily.com/dialogue-design-innovation-tailoring-bots-through-gpt/"><u>Dialogue Design Innovation: Tailoring Bots Through GPT</u></a></li>
<li><a href="https://win11.techidaily.com/elevating-file-security-with-powertoys-locksmith-expertise/"><u>Elevating File Security with PowerToys' Locksmith Expertise</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-proxy-settings-in-windows-11-os/"><u>Guide to Proxy Settings in Windows 11 OS</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/how-to-stream-high-efficiency-video-coding-hevcav1-content-with-your-plex-setup/"><u>How to Stream High-Efficiency Video Coding (HEVC/AV1) Content with Your Plex Setup</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-find-ispoofer-pro-activation-key-on-xiaomi-redmi-k70e-drfone-by-drfone-virtual-android/"><u>In 2024, How to Find iSpoofer Pro Activation Key On Xiaomi Redmi K70E? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-realme-c67-5g-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Realme C67 5G Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/installing-custom-weather-symbol-in-windows-11-notification-area/"><u>Installing Custom Weather Symbol in Windows 11 Notification Area</u></a></li>
<li><a href="https://win11.techidaily.com/muting-chrome-banners-pop-ups-and-sounds-win/"><u>Muting Chrome Banners, Pop-Ups & Sounds (Win)</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/-fix-bring-youtube-music-to-your-imovie-projects-for-2024/"><u>Quick Fix Bring YouTube Music to Your iMovie Projects for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/screen-anomaly-during-team-sessions/"><u>Screen Anomaly During Team Sessions?</u></a></li>
<li><a href="https://win11.techidaily.com/seeking-lightweight-web-access-browser-ram-consumption-tested-and-rated/"><u>Seeking Lightweight Web Access: Browser RAM Consumption Tested & Rated</u></a></li>
<li><a href="https://win11.techidaily.com/sticky-paperless-window-based-note-app-winners-non-writing/"><u>Sticky Paperless: Window-Based Note App Winners (Non-Writing)</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unleashing-creativity-in-ar-a-comprehensive-guide-to-lut-tools/"><u>Unleashing Creativity in AR A Comprehensive Guide to LUT Tools</u></a></li>
</ul></div>

