---
title: Filter Out Superfluous Updates From Your Windows PC
date: 2024-06-25T11:40:52.479Z
updated: 2024-06-26T11:40:52.479Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Filter Out Superfluous Updates From Your Windows PC
excerpt: This Article Describes Filter Out Superfluous Updates From Your Windows PC
keywords: Windows Update Filter,Unnecessary Windows Updates,Exclude Redundant Windows Updates,Streamline Windows Patches,Avoid Superfluous Windows Patches,Opt Out Windows Updates,Efficient Windows Updating
thumbnail: https://thmb.techidaily.com/310ebf5ae5294b3c09bff886e3c558b63079bc0b815690abddeb6c6ade1d7933.JPG
---

## Filter Out Superfluous Updates From Your Windows PC

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
6. Click **Apply** \> **OK** to save the changes.

 Now, tips and suggestions notifications will be completely disabled on your computer. To re-enable the feature, follow the same steps and select the **Not Configured** or **Disabled** radio button instead.

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/dismantling-the-barriers-to-switching-out-of-s-mode/"><u>Dismantling the Barriers to Switching Out of S Mode</u></a></li>
<li><a href="https://win11.techidaily.com/cure-for-local-security-guard-off-error-message/"><u>Cure for 'Local Security Guard Off' Error Message</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-eradicating-system-call-failed-problem-in-windows-11/"><u>Steps for Eradicating System Call Failed Problem in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/1719219819181-explore-the-full-capabilities-of-windows-snip-and-sketch-tool/"><u>Explore the Full Capabilities of Windows' Snip & Sketch Tool.</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-rectifying-spotifys-code-4-error/"><u>Deciphering and Rectifying Spotify's Code 4 Error</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-desktop-on-windows-11-with-vibrant-backdrops/"><u>Transform Your Desktop on Windows 11 with Vibrant Backdrops</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reactivate-deactivated-menu-items-on-windows/"><u>Steps to Reactivate Deactivated Menu Items on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/from-browsers-to-desktops-website-conversion-guide/"><u>From Browsers to Desktops: Website Conversion Guide</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-tutorial-to-edit-windows-files-metadata-dates/"><u>The Complete Tutorial to Edit Windows Files' Metadata Dates</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-explore-the-spectrum-of-light-with-windows-hdr-video-capabilities/"><u>[Updated] Explore the Spectrum of Light with Windows' HDR Video Capabilities</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-flawless-gameplay-controlling-games-via-switch-pro-controller-in-steam-for-2024/"><u>[Updated] Flawless Gameplay  Controlling Games via Switch Pro Controller in Steam for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-convert-webm-to-mp4-with-ease-best-tools-revealed-for-2024/"><u>Updated Convert WebM to MP4 with Ease Best Tools Revealed for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/feathered-salsa-dancer/"><u>Feathered Salsa Dancer</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-you-play-hevc-h-265-files-on-samsung-galaxy-a24-by-aiseesoft-video-converter-play-hevc-video-on-android/"><u>How do you play HEVC/H.265 files on Samsung Galaxy A24?</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/initiate-your-facebook-analysis-journey/"><u>Initiate Your Facebook Analysis Journey</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-honor-v-purse-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on Honor V Purse Devices</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-anonymous-surveillance-methods-hiding-private-data-effectively-for-2024/"><u>[New] Anonymous Surveillance Methods  Hiding Private Data Effectively for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-youtube-to-insta-a-video-posting-guide/"><u>[New] In 2024, From YouTube to Insta  A Video Posting Guide</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-itel-p55plus-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Itel P55+ FRP Locks</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>