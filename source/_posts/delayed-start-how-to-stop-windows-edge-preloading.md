---
title: "Delayed Start: How to Stop Windows Edge Preloading"
date: 2024-12-06T04:36:12.559Z
updated: 2024-12-06T18:32:37.919Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Delayed Start: How to Stop Windows Edge Preloading"
excerpt: "This Article Describes Delayed Start: How to Stop Windows Edge Preloading"
keywords: Stopping Windows Edge Load,Ending Edge Preload Delay,Avoid Edge Starting Late,Reduce Windows Edge Time,Mitigate Edge Preloading Issue,Stop Edge Start Lag,Speed Up Windows Edge Launch
thumbnail: https://thmb.techidaily.com/b02903fae7318467ee1d2a7ec684be197bec9e28a2f1680afb2687afaf4dfa29.jpg
---

## Delayed Start: How to Stop Windows Edge Preloading

 Microsoft Edge is the default browser in Windows and comes pre-installed on the operating system without any easy way of getting rid of it. The browser uses "tab preloading," which preloads the Start and New Tab page while you sign in to your PC.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
9. **Restart** your PC for the policy changes to take effect and disable the tab preloading feature.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## 3\. How to Disable Edge Tab Preloading Using CMD or PowerShell

 If you find the Registry Editor method too cumbersome, you can use the Command Prompt or PowerShell to modify the Registry and disable Edge tab preloading. Here’s how to do it:

1. [Open the Command Prompt with administrator privileges](https://www.makeuseof.com/windows-run-command-prompt-admin/) on your PC.
2. Execute the following commands to add two new registry entries:  
`reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\Main" /v AllowPrelaunch /t REG_DWORD /d 00000000 /f  
 reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\MicrosoftEdge\TabPreloader" /v AllowTabPreloading /t REG_DWORD /d 00000000 /f`
3. **Close** the Command Prompt window and **restart** your PC.  
![Disable Microsoft Edge Tab Preloading Using CMD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-cmd.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. How to Disable Edge Tab Preloading Using the Ultimate Windows Tweaker App

 You can also use a third-party app like the Ultimate Windows Tweaker to disable Edge tab preloading in Windows 11\. Download the [Ultimate Windows Tweaker](https://www.thewindowsclub.com/ultimate-windows-tweaker-4-windows-10) app and install it on your PC. After that, repeat the following steps:

1. Press **Win + S** to open the Windows Search app. Type **Ultimate Windows Tweaker** and then click on the **Run as administrator** option.
2. Click on the **Search For Tweaks** option. Type “**edge tab**” in the search box and click on the **Go** button.  
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker.jpg)
3. Click on the **Disable Edge Tab Preloading** checkbox to enable it. Then, click on the **Apply Tweaks** button.  
![Disable Microsoft Edge Tab Preloading Using Ultimate Windows Tweaker 2](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-microsoft-edge-tab-preloading-using-ultimate-windows-tweaker-2.jpg)
4. **Close** the Ultimate Windows Tweaker app and **restart** your PC to apply the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KF793jv1LIc?si=fJOogQJ2f8JUfTzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Disable Edge Tab Preloading for Good on Windows 11

 Edge tab preloading serves no useful purpose if you use other browsers. You can disable it using the Group Policy Editor or the Registry Editor. Lastly, if you want a GUI app to disable the feature, you can use the Ultimate Windows Tweaker app.

 For Edge lovers, it is a boon, but if you don’t use the default browser and prefer something else, it is a waste of resources. Fortunately, you can easily disable Edge's tab preloading in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-the-future-shaped-by-quantum-hdr-tech/"><u>[New] 2024 Approved The Future Shaped by Quantum HDR Tech</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-compact-mobile-smoothie-recorder-gadget/"><u>[New] Compact Mobile Smoothie Recorder Gadget</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-ultimate-ranking-of-8-swift-recorders/"><u>[Updated] 2024 Approved Ultimate Ranking of 8 Swift Recorders</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-step-by-step-securely-attach-a-link-to-your-tiktok-profile/"><u>[Updated] In 2024, Step-by-Step Securely Attach a Link to Your TikTok Profile</u></a></li>
<li><a href="https://win-premium.techidaily.com/2024-zoom/"><u>2024年にぴったり! Zoom 録画対策トップ３テクニック - 使いこなしガイド</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-printer-problems-fast-win11-fixed/"><u>Eliminate Printer Problems Fast: Win11 Fixed</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-nokia-g310-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Nokia G310 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/guarding-your-gateway-identifying-authenticity-in-windows-apps/"><u>Guarding Your Gateway: Identifying Authenticity in Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-access-and-master-windows-11-component-services/"><u>How to Access & Master Windows 11' Component Services</u></a></li>
<li><a href="https://win11.techidaily.com/hyper-v-integration-establishing-a-linux-environment-on-windows-host/"><u>Hyper-V Integration: Establishing a Linux Environment on Windows Host</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-access-your-apple-iphone-6-plus-when-you-forget-the-passcode-by-drfone-ios/"><u>In 2024, How to Access Your Apple iPhone 6 Plus When You Forget the Passcode?</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-facebook-dating-for-your-honor-x8b-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location On Facebook Dating for your Honor X8b | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlock-apple-id-from-your-apple-iphone-15-without-security-questions-by-drfone-ios/"><u>In 2024, How to Unlock Apple ID From your Apple iPhone 15 without Security Questions?</u></a></li>
<li><a href="https://win11.techidaily.com/pro-tips-for-background-deletion-in-paint-3d/"><u>Pro Tips for Background Deletion in Paint 3D</u></a></li>
<li><a href="https://win11.techidaily.com/radiant-christmas-themes-dazzling-windowscapades/"><u>Radiant Christmas Themes: Dazzling Windowscapades</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/scopri-il-top-programma-di-riproduzione-delloperating-system-windows-10/"><u>Scopri Il Top Programma Di Riproduzione Dell'Operating System Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-immediate-edge-tabs-in-win11/"><u>Sidestep Immediate Edge Tabs in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-keyboard-issues-in-windows-10/"><u>Tackling Keyboard Issues in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-review-of-linksys-wrt3200acm-router-unleashing-the-potential-of-open-source-wifi-solutions/"><u>The Ultimate Review of Linksys WRT3200ACM Router: Unleashing the Potential of Open Source WiFi Solutions</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    