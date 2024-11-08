---
title: Strategies to Maintain Windows Time Settings
date: 2024-11-01T21:33:48.125Z
updated: 2024-11-07T21:22:15.551Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Strategies to Maintain Windows Time Settings
excerpt: This Article Describes Strategies to Maintain Windows Time Settings
keywords: Windows Time Controls,Setting Windows Clock,Update Time on Windows,Windows Date Adjustment,Set PC Time Windows,Correct Windows Timing,Manage Windows Schedule
thumbnail: https://thmb.techidaily.com/efe03172267db8e41dde950b174798601940a22588399da557fc77a3f3ce0d36.jpeg
---

## Strategies to Maintain Windows Time Settings

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105874/7443" target="_top" id="2105874">
  <img src="//a.impactradius-go.com/display-ad/7443-2105874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105874/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Use the Group Policy Editor

 If your computer is part of an organization and users often change the date and time, use Group Policy Editor to stop it. This will prevent those with limited access to the computer from altering the date and time. However, this method only works for Windows Pro, Enterprise, or Education Editions.

 So, if you have Windows Home Edition, this won’t work. In that case, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems complicated, skip it and try the next solution instead.

 Follow these steps to prevent users from changing the date and time:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **gpedit.msc** in the text box and press Enter. This will open the Group Policy Editor window.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > System > Locale Services
4. In the right-side pane, double-click on **Disallow user override of locale settings**.  
![Disallow user override of locale settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disallow-user-override-of-locale-settings.jpg)
5. In the pop-up window, check the **Enabled** radio button.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/857869/11832" target="_top" id="857869">
  <img src="//a.impactradius-go.com/display-ad/11832-857869" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/857869/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

## 2\. Tweak the Registry Editor

 If you’re using Windows Home Edition or have disabled the Group Policy Editor, use the Registry Editor to protect date and time settings. This method is more advanced and has a higher risk of system damage.

 In that case, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it. Doing so will restore settings if something goes wrong.

 Follow these steps to stop users from changing the time and date via the registry:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the field and press Enter. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. In the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Software\Policies\Microsoft\Control Panel\International\
4. If the International folder doesn’t exist, create one. To do that, right-click on Control Panel and select **New** \> **Key**. Name it **International**.
5. Then right-click on **International** and select New > DWORD (32-bit) Value.
6. Name the newly created value **PreventUserOverrides**.
7. Double-click on the **PreventUserOverrides** DWORD value.  
![Use Registry Editor to Prevent Users From Chaning date and time settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-registry-editor-to-prevent-users-from-chaning-date-and-time-settings.jpg)
8. In the pop-up window, change the Value data to **1** and click **OK**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049390/7443" target="_top" id="2049390">
  <img src="//a.impactradius-go.com/display-ad/7443-2049390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049390/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037319/7443" target="_top" id="2037319">
  <img src="//a.impactradius-go.com/display-ad/7443-2037319" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037319/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://extra-hints.techidaily.com/cinematic-hope-the-top-10-inspirational-films/"><u>Cinematic Hope The Top 10 Inspirational Films</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-guide-to-downloading-and-installing-hp-officejet-4650-drivers-on-windows-systems/"><u>Easy Guide to Downloading and Installing HP OfficeJet 4650 Drivers on Windows Systems</u></a></li>
<li><a href="https://some-techniques.techidaily.com/exploring-microsofts-copilot-its-journey-through-windows-11/"><u>Exploring Microsoft's Copilot: Its Journey Through Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-resolve-corrupted-file-on-windows-a-step-by-step-approach/"><u>How To Resolve 'Corrupted File' On Windows: A Step-by-Step Approach</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-vivo-x-fold-2-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Vivo X Fold 2 via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-securing-privacy-efficient-blur-techniques-in-images/"><u>In 2024, Securing Privacy Efficient Blur Techniques in Images</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-3-step-guide-to-exceptional-gopro-videos/"><u>In 2024, The 3-Step Guide to Exceptional GoPro Videos</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-device-performance-a-guide-to-hardware-widgets/"><u>Maximize Device Performance: A Guide to Hardware Widgets</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-windows-xps-problematic-error-x80300024/"><u>Overcoming Windows XP's Problematic Error X80300024</u></a></li>
<li><a href="https://win11.techidaily.com/taking-coding-to-new-heights-maximizing-use-of-dev-drive-in-win11/"><u>Taking Coding to New Heights: Maximizing Use of Dev Drive in Win11</u></a></li>
<li><a href="https://apple-account.techidaily.com/the-easy-way-to-remove-an-apple-id-from-your-macbook-for-your-apple-iphone-se-2022-by-drfone-ios/"><u>The Easy Way to Remove an Apple ID from Your MacBook For your Apple iPhone SE (2022)</u></a></li>
<li><a href="https://win11.techidaily.com/tips-for-stopping-windows-safe-screen-change/"><u>Tips for Stopping Windows Safe Screen Change</u></a></li>
<li><a href="https://win11.techidaily.com/top-10-solutions-for-non-responsive-wireless-mice-windows/"><u>Top 10 Solutions for Non-Responsive Wireless Mice (Windows)</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-tips-for-fixing-resident-evil-village-startup-errors/"><u>Troubleshooting Tips for Fixing Resident Evil Village Startup Errors</u></a></li>
<li><a href="https://win11.techidaily.com/turn-off-windows-count-for-each-app-opener/"><u>Turn Off Windows Count for Each App Opener</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/vrij-vanafragans-jpg-tot-bmp-onlineconverter-met-movavi-zonder-kosten/"><u>Vrij Vanafragans JPG-Tot-BMP Onlineconverter Met Movavi - Zonder Kosten</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    