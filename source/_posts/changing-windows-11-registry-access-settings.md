---
title: Changing Windows 11 Registry Access Settings
date: 2025-02-14T22:06:02.166Z
updated: 2025-02-15T21:17:01.525Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Changing Windows 11 Registry Access Settings
excerpt: This Article Describes Changing Windows 11 Registry Access Settings
keywords: Win11 Reg Edit,Setup Reg Changes,Update Windows Reg Key,Adjust Win11 Reg Values,Customize Win11 Registry,Modify Windows Configurations,RegKey Adjustments Win11
thumbnail: https://thmb.techidaily.com/043a6e9400628e90ba868e49367a439edaed6ed2655e7384611850ca4beac263.jpg
---

## Changing Windows 11 Registry Access Settings

 Although the Registry Editor on Windows makes it easy for administrators to access critical settings and configurations, making incorrect changes to registry files can cause the system to become unstable and compromise its security. This is a common concern among Windows users who share their computers with others.

 Fortunately, it’s possible to disable (or enable) Registry Editor access on your Windows 11 PC. Let's see how.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. How to Disable or Enable Registry Editor Access via the Group Policy Editor

 The most straightforward way to block access to the Registry Editor on Windows is via the Group Policy Editor. However, it’s important to note that this tool is only available on Windows Pro, Education, and Enterprise editions. If you happen to be using Windows Home, refer to our guide on [how to access the Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press **Win + R** to open the Run dialog box.
2. Type **gpedit.msc** in the box and press **Enter**.
3. In the Local Group Policy Editor window, use the left pane to navigate to **User Configuration > Administrative Templates > System**.
4. Double-click the **Prevent access to registry editing tools** policy in the right pane.
5. Select the **Enabled** option.
6. Click **Apply** followed by **OK**.  
![Block Registry Editor Access via Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/block-registry-editor-access-via-group-policy-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_O8m9KphYzs?si=jITthzeyX_Kmt9X2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Following this, users will see the “Registry editing has been disabled by your administrator” message when they attempt to access the Registry Editor. If you want to re-enable Registry Editor later, repeat the above steps and set the **Prevent access to registry editing tools** policy to **Not configured** or **Disabled**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/T-ssCD10v2M?si=WVWGNayUiCAkMZzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. How to Disable or Enable Registry Editor Access via the Registry Editor

 Another way to restrict the Registry Editor access on Windows involves using the Registry Editor itself. Here are the steps you can follow.

1. Click the **search icon** on the taskbar to access the search menu.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when [the User Account Control (UAC) prompt](https://www.makeuseof.com/windows-11-disable-user-account-control-prompt/) appears.
4. In the Registry Editor window, use the left pane to navigate to **HKEY\_CURRENT\_USER > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies**.
5. Right-click on the **Policies** key and select **New > Key**. Name it **System**.
6. Right-click on the **System** key and select **New > DWORD (32-bit) Value**. Name it **DisableRegistryTools**.
7. Double-click the newly created DWORD, type **1** in the Value data field, and hit **OK**.  
![Block Registry Editor Access via Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/block-registry-editor-access-via-registry-editor.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YfEPmG_O6F8?si=93ZTVtH_zjFRz5eh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Once you complete the above steps, the Registry Editor will be disabled on your PC.

 Although you cannot access the Registry Editor to reverse the above changes, it's still possible to re-enable Registry Editor access. For that, you will have to [create and run a REG file](https://www.makeuseof.com/windows-registry-file-guide/). Here’s how you can go about it.

1. Press **Win + S** to open the search menu.
2. Type **notepad** in the search box and press **Enter**.
3. In the notepad window, paste the following command.  
`Windows Registry Editor Version 5.00  
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System] "DisableRegistryTools"=dword:00000000`  
![Create Reg File to Enable Registry Editor Access on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/create-reg-file-to-enable-registry-editor-access-on-windows.jpg)
4. Click the **File** menu and select **Save as**.
5. Select **Desktop** in the **Save as** dialog box.
6. Enter a suitable name followed by ".reg" and hit **Save**. For instance, you could name the file **ReEnableRegistry.reg** or something similar.
7. Use one of the many [ways to open the Command Prompt with admin rights](https://www.makeuseof.com/windows-run-command-prompt-admin/).
8. Type the following command in the console and hit **Enter**. Make sure you replace the **\[username\]** in the following command with your actual username.  
`cd C:\Users\[username]\Desktop`
9. Paste the following command, replace **FileName** with the actual name of the REG file, and press **Enter**.  
`regedit.exe /s FileName.reg`

 Once you run the above command, the Registry Editor will become accessible again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Allowing or Disallowing Registry Editor Access on Windows

 Blocking access to the Registry Editor is an effective way to protect your system from registry mishaps. Nonetheless, if you opt to re-enable access to the Registry Editor on your PC, make sure to exercise caution to avoid messing up the Windows Registry.

 Fortunately, it’s possible to disable (or enable) Registry Editor access on your Windows 11 PC. Let's see how.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-navigating-recordings-in-windows-11-a-compreayers-guide/"><u>[Updated] 2024 Approved Navigating Recordings in Windows 11 A Compreayer's Guide</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-the-key-ingredients-for-successful-instagram-unboxing-reels/"><u>[Updated] The Key Ingredients for Successful Instagram Unboxing Reels</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unlock-the-power-of-any-video-with-these-free-online-editors/"><u>[Updated] Unlock the Power of Any Video With These Free Online Editors</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/best-free-iphone-xr-imei-checker-by-drfone-ios/"><u>Best Free iPhone XR IMEI Checker</u></a></li>
<li><a href="https://screen-capture.techidaily.com/boosting-stream-consistency-with-obs-fixes-for-2024/"><u>Boosting Stream Consistency with OBS Fixes for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-troubleshooting-guide-fixing-the-infamous-body-stream-error-in-7-steps/"><u>ChatGPT Troubleshooting Guide: Fixing the Infamous Body Stream Error in 7 Steps</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-printer-problems-fast-win11-fixed/"><u>Eliminate Printer Problems Fast: Win11 Fixed</u></a></li>
<li><a href="https://solve-manuals.techidaily.com/enhance-your-marketing-analytics-using-the-cookiebot-platform/"><u>Enhance Your Marketing Analytics Using the Cookiebot Platform</u></a></li>
<li><a href="https://win11.techidaily.com/guarding-your-gateway-identifying-authenticity-in-windows-apps/"><u>Guarding Your Gateway: Identifying Authenticity in Windows Apps</u></a></li>
<li><a href="https://win11.techidaily.com/hyper-v-integration-establishing-a-linux-environment-on-windows-host/"><u>Hyper-V Integration: Establishing a Linux Environment on Windows Host</u></a></li>
<li><a href="https://win11.techidaily.com/installing-virtualbox-on-windows-set-up-the-dependencies-first-for-error-free-installation/"><u>Installing VirtualBox on Windows? Set Up the Dependencies First for Error-Free Installation</u></a></li>
<li><a href="https://win11.techidaily.com/methodology-to-rectify-managed-chromium-and-microsoft-edge-configurations/"><u>Methodology to Rectify Managed Chromium & Microsoft Edge Configurations</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-stuck-keyboard-arrows-effective-troubleshooting-tips-inside/"><u>Overcome Stuck Keyboard Arrows - Effective Troubleshooting Tips Inside!</u></a></li>
<li><a href="https://fox-http.techidaily.com/prime-android-space-savers-compendium-for-2024/"><u>Prime Android Space-Savers Compendium for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/pro-tips-for-background-deletion-in-paint-3d/"><u>Pro Tips for Background Deletion in Paint 3D</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-immediate-edge-tabs-in-win11/"><u>Sidestep Immediate Edge Tabs in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/switch-to-shadows-making-paint-dark/"><u>Switch to Shadows: Making Paint Dark</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-review-of-linksys-wrt3200acm-router-unleashing-the-potential-of-open-source-wifi-solutions/"><u>The Ultimate Review of Linksys WRT3200ACM Router: Unleashing the Potential of Open Source WiFi Solutions</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-vlog-editing-made-easy-top-14-software-for-creating-engaging-content/"><u>Updated In 2024, Vlog Editing Made Easy Top 14 Software for Creating Engaging Content</u></a></li>
</ul></div>

