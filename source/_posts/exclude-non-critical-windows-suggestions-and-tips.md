---
title: Exclude Non-Critical Windows Suggestions and Tips
date: 2025-02-02T17:42:47.325Z
updated: 2025-02-04T06:16:37.092Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Exclude Non-Critical Windows Suggestions and Tips
excerpt: This Article Describes Exclude Non-Critical Windows Suggestions and Tips
keywords: Exclude Windows Advice -,Essential Windows Tips -,Prioritize Critical Windows -,Filter Non-Critical Suggestions -,Highlight Important Windows -,Focus on Crucial Windows Advice -,Disregard Minor Windows Tips -
thumbnail: https://thmb.techidaily.com/014d79402613effc6daacc66a3f2a300ba2df5a4c6f73b5cf48b17efe5272ad6.jpg
---

## Exclude Non-Critical Windows Suggestions and Tips

 Are you tired of constantly seeing tips and suggestions on your computer screen? Want to mute them and concentrate on your work uninterrupted? Don’t worry - the process is quick and straightforward.

 In this article, we’ll discuss how to turn off or disable tips and suggestions notifications on Windows 11\.

## How to Turn Off or Disable Tips and Suggestions Notifications in Windows 11

 Tips and suggestions provide quick guides to Windows and its features. But if you find them annoying, you can turn them off. Here are two easy methods to turn off tips and suggestions notifications on Windows 11\.

### 1\. How to Turn Off Tips and Suggestions Using System Settings

 To turn off tips and suggestions on your computer, you can use the System Settings. This is the easiest and quickest way to mute these notifications. Here's how to do it:

1. Press **Win + I** to open the Settings window.
2. From the left panel, click on the **System** tab.
3. In the System Settings sub-panel, click on the **Notifications** section.  
![Open System Notification Section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/open-system-notification-section.jpg)
4. Next, scroll down to the bottom and expand **Additional settings**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Get tips and suggestions when using Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/get-tips-and-suggestions-when-using-windows.jpg)
5. You will see a checkbox labeled **Get tips and suggestions when using Windows**. Uncheck it to turn off this feature.

 Now, you will not see any tips and suggestions notifications on your computer. If later you wish to re-enable this feature, follow the same steps outlined above and check the "Get tips and suggestions when using Windows" checkbox. Doing this will enable tips and suggestions notifications on your computer.

### 2\. Turn Off Tips and Suggestions Using a REG File

 If the system setting is unresponsive, you can use a REG file instead. This procedure creates a REG file with the necessary commands. Although it may seem complex, it is actually quite simple.

 Here are the steps to follow:

1. [Open the Notepad application](https://www.makeuseof.com/windows-11-open-notepad/).
2. Copy and paste the following code into it:  
`Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\ContentDeliveryManager]  
"SubscribedContent-338389Enabled"=dword:00000000`
3. Now save the file with the **.reg** extension.
4. Double-click on the file you just created to open it, and click **Yes** in the confirmation dialog box that appears.

 This will turn off tips and suggestions notifications in Windows 11\. To enable these notifications once again, delete the file you just created. Alternatively, double-click on it and click **No** in the confirmation dialog.

## How to Disable Tips and Suggestions Notifications in Windows 11

 If you prefer to disable tips and suggestions notifications on your computer completely, there are several options available. You can utilize the Group Policy Editor, modify the registry editor, or create a REG file. Let's explore each method in detail to disable this feature.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 1\. Disable Tips and Suggestions Notifications Using Group Policy Editor

 To turn off notifications for tips and suggestions, access the Group Policy Editor. This tool is available for Windows Pro, Education, and Enterprise users. However, it won't work if you use Windows Home Edition.

 In such cases, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). Once done, follow the steps below to disable notifications for tips and suggestions:

1. Press **Win + R** to open the Run window.
2. Type **gpedit.msc** in the Run dialog box and press Enter. This will launch the Group Policy Editor window on your screen.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > Windows Components > Cloud Content​
4. On the right side of the window, double-click on the **Do not show Windows tips** policy.  
![Do not Show Windows Tips](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/do-not-show-windows-tips.jpg)
5. From the box that appears, select the **Enabled** radio button.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Click **Apply** \> **OK** to save the changes.

 Now, tips and suggestions notifications will be completely disabled on your computer. To re-enable the feature, follow the same steps and select the **Not Configured** or **Disabled** radio button instead.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 2\. Disable Tips and Suggestions Notifications Using the Registry Editor

 If you can’t access the Group Policy Editor or activate it, you can modify the registry editor to disable these notifications. The procedure is slightly more technical and requires caution while making changes. It may even wreck your computer system, so proceed cautiously.

 To avoid risks, [create a registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) first. That way, you can restore the original settings if required. Once you have taken these precautionary steps, follow the instructions below to disable tips and suggestions notifications:

1. Press the **Windows** key to open the Start Menu.
2. Type **regedit** in the search box and select the **Registry Editor** app from the search results.
3. If the UAC window appears, click **Yes** to grant permission.
4. In the Registry Editor window, navigate to the following path:  
HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\CloudContent
5. If the **CloudContent** key is missing, create a new one. To do this, right-click on the Windows folder and select **New** \> **Key**. Name it **CloudContent**.
6. On the right side of the window, right-click on an empty area and select **New** \> **DWORD (32-bit) Value**.
7. Name the value **DisableSoftLanding** and hit Enter.  
![Disable Tips and Suggestions Notifications Using the Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-tips-and-suggestions-notifications-using-the-registry-editor.jpg)
8. Double-click on this newly created entry and set its Value data to **1**.
9. Click **OK** to save the changes. Now, exit the registry editor window and restart your computer.

 After restarting, tips and suggestions notifications will be disabled on your computer. If you want to enable the feature, follow the same steps and change the Value data to **0**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3\. Disable Tips and Suggestions Notifications Using a REG File

 You can also create a REG file to turn off tips and suggestions notifications on your Windows PC. This method is quite similar to the one we discussed above. However, the process is easier for those with little experience editing registry files.

 To disable tips and suggestions notifications using a REG file, follow the steps outlined below:

1. Search for **Notepad** and select the result from the list.
2. Copy and paste the code below into the Notepad window.  
`Windows Registry Editor Version 5.00  

[HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows\CloudContent]  
"DisableSoftLanding"=dword:00000001`
3. Save the file with the .reg extension. Make sure that the Save as type field is set to **All files**.
4. Now, double-click on the file and click **Yes** at the prompt.

 That’s it! Tips and suggestions feature is now disabled on your computer.

## Stop the Windows Tips and Suggestions Notifications

 We hope that this article helped you understand how to turn off or disable tips and suggestions notifications in Windows 11\. All it takes are a few clicks or a simple REG file to enable or disable this feature.

 In this article, we’ll discuss how to turn off or disable tips and suggestions notifications on Windows 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-mastering-video-size-for-standout-instagram-content/"><u>[Updated] 2024 Approved Mastering Video Size for Standout Instagram Content</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-beyond-boxes-crafting-memorable-receiving-moments/"><u>[Updated] In 2024, Beyond Boxes Crafting Memorable Receiving Moments</u></a></li>
<li><a href="https://tech-haven.techidaily.com/discover-the-6-premier-chatbot-extensions-elevating-visual-studio-code-development/"><u>Discover the 6 Premier Chatbot Extensions Elevating Visual Studio Code Development</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-essential-guide-8-excellent-priceless-3d-video-experience/"><u>In 2024, Essential Guide 8 Excellent, Priceless 3D Video Experience</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-exquisite-innovations-in-desktop-tech/"><u>In 2024, Exquisite Innovations in Desktop Tech</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-prime-portable-canvas-apps-for-windows-free-and-charged/"><u>In 2024, Prime Portable Canvas Apps for Windows Free and Charged</u></a></li>
<li><a href="https://win11.techidaily.com/microsofts-strategy-behind-extended-updates-for-windows-11/"><u>Microsoft's Strategy Behind Extended Updates for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-psx-non-starting-issues-in-newest-ws11-builds/"><u>Overcoming PSX Non-Starting Issues in Newest WS11 Builds</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unity-graphical-glitches-fixed-failure-to-initialize-solutions/"><u>Overcoming Unity Graphical Glitches - Fixed Failure to Initialize Solutions</u></a></li>
<li><a href="https://win-webster.techidaily.com/pasos-facilmente-descifrados-instale-e-imagine-su-pc-con-la-ultima-version-de-windows-en-una-unidad-ssd-nvme/"><u>Pasos Fácilmente Descifrados: Instale E Imagine Su PC Con La Última Versión De Windows en Una Unidad SSD-NVMe</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-microsoft-store-functionality-on-windows-devices/"><u>Reclaiming Microsoft Store Functionality on Windows Devices</u></a></li>
<li><a href="https://win11.techidaily.com/rethink-renewal-why-not-go-beyond-windows/"><u>Rethink Renewal: Why Not Go Beyond Windows?</u></a></li>
<li><a href="https://solve-lab.techidaily.com/running-a-computer-without-a-dedicated-graphics-unit-insights-and-solutions-from-yl-software-experts/"><u>Running a Computer Without a Dedicated Graphics Unit: Insights and Solutions From YL Software Experts</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-overcome-windows-11s-camera-app-failures-error-afc/"><u>Steps to Overcome Windows 11'S Camera App Failures: Error AFC</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-commands-define-wins-cli/"><u>Streamlining Your Commands: Define Win's CLI</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-manual-for-windows-users-using-imessage/"><u>The Ultimate Manual for Windows Users: Using iMessage</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-7-phone-number-locators-to-track-vivo-x90s-location-drfone-by-drfone-virtual-android/"><u>Top 7 Phone Number Locators To Track Vivo X90S Location | Dr.fone</u></a></li>
</ul></div>

