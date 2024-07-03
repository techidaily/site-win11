---
title: Removing Default Homescreen From Windows 11 Setup
date: 2024-06-25T11:33:55.803Z
updated: 2024-06-26T11:33:55.803Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Removing Default Homescreen From Windows 11 Setup
excerpt: This Article Describes Removing Default Homescreen From Windows 11 Setup
keywords: Remove Home Screen Windows 11,Windows 11 Initial Setup,Deactivate Default Desktop,Win11 Startup Avoidance,Homescreen Removal Guide,Customize Windows 11 Launch,Personalized Win11 Screenscape
thumbnail: https://thmb.techidaily.com/bf6ce710c3b83bd0300511eb0a114987cd6a644274eb54a39fdf9870b6c3de78.jpg
---

## Removing Default Homescreen From Windows 11 Setup

### Key Takeaways

* You can remove the Home page from the Settings app in Windows 11 using the Group Policy Editor or the Registry Editor.
* The Group Policy Editor is only available in certain editions of Windows, but there are workarounds for enabling it in the Home edition.
* It's important to back up registry files or create a restore point before making changes, as incorrect modifications can cause serious issues.

 The Home page in the Settings app displays interactive cards that provide information about the system and offer shortcuts to common settings. However, if you're not a fan of the new Home section, removing it from the Settings app is possible with two quick methods.

 You can hide the Home page using the Group Policy Editor or the Registry Editor. This guide will walk you through both methods.

## 1\. Use the Group Policy Editor to Remove the Home Page

 The Local Group Policy Editor on Windows makes modifying various advanced system settings easy. Among the many options, it allows you to manage the pages shown in the Settings app. So, you can use the Local Group Policy Editor to hide the Home tab from the Windows 11 Settings app.

 The Group Policy Editor is only accessible on the Professional, Education, and Enterprise editions of Windows. If you are using Windows Home, you can [enable the Local Group Policy Editor in Windows](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) with workarounds.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Control Panel**.
5. Double-click the **Settings Page Visibility** policy in the right pane.
6. Select the **Enabled** option.
7. In the Options box, type **hide:home** in the text field next to Settings Page Visibility.
8. Click **Apply** followed by **OK**.  
![Settings Page Visibility Policy on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/settings-page-visibility-policy-on-windows.jpg)

 The Home page will be hidden on the Settings app. If you want to view the Home tab at any point, repeat the above steps and set the **Settings Page Visibility** policy to **Disabled** or **Not configured**.

## 2\. Use the Registry Editor to Remove the Home Page

 Can't access the Group Policy Editor on your Windows PC? You can also remove the Home tab from the Windows 11 Settings app by making a few changes to the registry files.

 As you may already know, registry files store critical settings for Windows and your apps. Making incorrect changes to the registry can lead to serious problems. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/use-system-restore-windows/) before proceeding. This will allow you to restore the Windows registry to its previous state if something goes wrong.

 To hide the Home tab from the Settings app using Registry Editor, follow these steps:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > Explorer**.
5. Right-click the **Explorer** key, click **New**, and select **String Value** from the submenu. Rename it to **SettingsPageVisibility**.
6. Double-click the **SettingsPageVisibility** value to edit it.
7. Type **hide:home** in the Value data field and click **OK**.  
![Edit a String Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-a-string-value-in-registry-editor.jpg)

 Restart your PC after completing the above steps. Then, open Settings to confirm the Home page is hidden. To restore the removed Home tab later, repeat the above steps and delete the **SettingsPageVisibility** string value.

## Get the Classic Windows 11 Settings Look

 While the Home screen provides quick and easy access to frequently used settings, you may prefer the older classic view. So, hide it from view and recover it when necessary.

 The Home page in the Settings app displays interactive cards that provide information about the system and offer shortcuts to common settings. However, if you're not a fan of the new Home section, removing it from the Settings app is possible with two quick methods.

 You can hide the Home page using the Group Policy Editor or the Registry Editor. This guide will walk you through both methods.

## 1\. Use the Group Policy Editor to Remove the Home Page

 The Local Group Policy Editor on Windows makes modifying various advanced system settings easy. Among the many options, it allows you to manage the pages shown in the Settings app. So, you can use the Local Group Policy Editor to hide the Home tab from the Windows 11 Settings app.

 The Group Policy Editor is only accessible on the Professional, Education, and Enterprise editions of Windows. If you are using Windows Home, you can [enable the Local Group Policy Editor in Windows](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) with workarounds.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Control Panel**.
5. Double-click the **Settings Page Visibility** policy in the right pane.
6. Select the **Enabled** option.
7. In the Options box, type **hide:home** in the text field next to Settings Page Visibility.
8. Click **Apply** followed by **OK**.  
![Settings Page Visibility Policy on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/settings-page-visibility-policy-on-windows.jpg)

 The Home page will be hidden on the Settings app. If you want to view the Home tab at any point, repeat the above steps and set the **Settings Page Visibility** policy to **Disabled** or **Not configured**.

## 2\. Use the Registry Editor to Remove the Home Page

 Can't access the Group Policy Editor on your Windows PC? You can also remove the Home tab from the Windows 11 Settings app by making a few changes to the registry files.

 As you may already know, registry files store critical settings for Windows and your apps. Making incorrect changes to the registry can lead to serious problems. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/use-system-restore-windows/) before proceeding. This will allow you to restore the Windows registry to its previous state if something goes wrong.

 To hide the Home tab from the Settings app using Registry Editor, follow these steps:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > Explorer**.
5. Right-click the **Explorer** key, click **New**, and select **String Value** from the submenu. Rename it to **SettingsPageVisibility**.
6. Double-click the **SettingsPageVisibility** value to edit it.
7. Type **hide:home** in the Value data field and click **OK**.  
![Edit a String Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-a-string-value-in-registry-editor.jpg)

 Restart your PC after completing the above steps. Then, open Settings to confirm the Home page is hidden. To restore the removed Home tab later, repeat the above steps and delete the **SettingsPageVisibility** string value.

## Get the Classic Windows 11 Settings Look

 While the Home screen provides quick and easy access to frequently used settings, you may prefer the older classic view. So, hide it from view and recover it when necessary.

 The Home page in the Settings app displays interactive cards that provide information about the system and offer shortcuts to common settings. However, if you're not a fan of the new Home section, removing it from the Settings app is possible with two quick methods.

 You can hide the Home page using the Group Policy Editor or the Registry Editor. This guide will walk you through both methods.

## 1\. Use the Group Policy Editor to Remove the Home Page

 The Local Group Policy Editor on Windows makes modifying various advanced system settings easy. Among the many options, it allows you to manage the pages shown in the Settings app. So, you can use the Local Group Policy Editor to hide the Home tab from the Windows 11 Settings app.

 The Group Policy Editor is only accessible on the Professional, Education, and Enterprise editions of Windows. If you are using Windows Home, you can [enable the Local Group Policy Editor in Windows](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) with workarounds.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Control Panel**.
5. Double-click the **Settings Page Visibility** policy in the right pane.
6. Select the **Enabled** option.
7. In the Options box, type **hide:home** in the text field next to Settings Page Visibility.
8. Click **Apply** followed by **OK**.  
![Settings Page Visibility Policy on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/settings-page-visibility-policy-on-windows.jpg)

 The Home page will be hidden on the Settings app. If you want to view the Home tab at any point, repeat the above steps and set the **Settings Page Visibility** policy to **Disabled** or **Not configured**.

## 2\. Use the Registry Editor to Remove the Home Page

 Can't access the Group Policy Editor on your Windows PC? You can also remove the Home tab from the Windows 11 Settings app by making a few changes to the registry files.

 As you may already know, registry files store critical settings for Windows and your apps. Making incorrect changes to the registry can lead to serious problems. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/use-system-restore-windows/) before proceeding. This will allow you to restore the Windows registry to its previous state if something goes wrong.

 To hide the Home tab from the Settings app using Registry Editor, follow these steps:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > Explorer**.
5. Right-click the **Explorer** key, click **New**, and select **String Value** from the submenu. Rename it to **SettingsPageVisibility**.
6. Double-click the **SettingsPageVisibility** value to edit it.
7. Type **hide:home** in the Value data field and click **OK**.  
![Edit a String Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-a-string-value-in-registry-editor.jpg)

 Restart your PC after completing the above steps. Then, open Settings to confirm the Home page is hidden. To restore the removed Home tab later, repeat the above steps and delete the **SettingsPageVisibility** string value.

## Get the Classic Windows 11 Settings Look

 While the Home screen provides quick and easy access to frequently used settings, you may prefer the older classic view. So, hide it from view and recover it when necessary.

 The Home page in the Settings app displays interactive cards that provide information about the system and offer shortcuts to common settings. However, if you're not a fan of the new Home section, removing it from the Settings app is possible with two quick methods.

 You can hide the Home page using the Group Policy Editor or the Registry Editor. This guide will walk you through both methods.

## 1\. Use the Group Policy Editor to Remove the Home Page

 The Local Group Policy Editor on Windows makes modifying various advanced system settings easy. Among the many options, it allows you to manage the pages shown in the Settings app. So, you can use the Local Group Policy Editor to hide the Home tab from the Windows 11 Settings app.

 The Group Policy Editor is only accessible on the Professional, Education, and Enterprise editions of Windows. If you are using Windows Home, you can [enable the Local Group Policy Editor in Windows](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) with workarounds.

1. Press **Win + S** to access the search menu.
2. Type **gpedit.msc** in the box and select the first result that appears.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. In the Local Group Policy Editor window, use the left pane to navigate to **Computer Configuration > Administrative Templates > Control Panel**.
5. Double-click the **Settings Page Visibility** policy in the right pane.
6. Select the **Enabled** option.
7. In the Options box, type **hide:home** in the text field next to Settings Page Visibility.
8. Click **Apply** followed by **OK**.  
![Settings Page Visibility Policy on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/settings-page-visibility-policy-on-windows.jpg)

 The Home page will be hidden on the Settings app. If you want to view the Home tab at any point, repeat the above steps and set the **Settings Page Visibility** policy to **Disabled** or **Not configured**.

## 2\. Use the Registry Editor to Remove the Home Page

 Can't access the Group Policy Editor on your Windows PC? You can also remove the Home tab from the Windows 11 Settings app by making a few changes to the registry files.

 As you may already know, registry files store critical settings for Windows and your apps. Making incorrect changes to the registry can lead to serious problems. Hence, it’s a good idea to [back up all the registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/use-system-restore-windows/) before proceeding. This will allow you to restore the Windows registry to its previous state if something goes wrong.

 To hide the Home tab from the Settings app using Registry Editor, follow these steps:

1. Press **Win + R** to open the Run dialog.
2. Type **regedit** in the text box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Microsoft > Windows > CurrentVersion > Policies > Explorer**.
5. Right-click the **Explorer** key, click **New**, and select **String Value** from the submenu. Rename it to **SettingsPageVisibility**.
6. Double-click the **SettingsPageVisibility** value to edit it.
7. Type **hide:home** in the Value data field and click **OK**.  
![Edit a String Value in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/edit-a-string-value-in-registry-editor.jpg)

 Restart your PC after completing the above steps. Then, open Settings to confirm the Home page is hidden. To restore the removed Home tab later, repeat the above steps and delete the **SettingsPageVisibility** string value.

## Get the Classic Windows 11 Settings Look

 While the Home screen provides quick and easy access to frequently used settings, you may prefer the older classic view. So, hide it from view and recover it when necessary.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/next-gen-access-management-for-windows-administrators/"><u>Next-Gen Access Management for Windows Administrators</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-initial-load-issues-in-lol/"><u>Overcoming Initial Load Issues in LOL</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-efficiency-essential-strategies-for-windows-11-users/"><u>Mastering Efficiency: Essential Strategies for Windows 11 Users</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-workflow-coloring-without-conflict-on-windows/"><u>Streamlining Your Workflow: Coloring Without Conflict on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-to-resolving-common-fall-guys-connectivity-issues-windows/"><u>Quick Guide to Resolving Common Fall Guys Connectivity Issues (Windows)</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-zoom-error-code-1132-in-windows-10-and-11/"><u>How to Fix Zoom Error Code 1132 in Windows 10 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/ensuring-a-smooth-operational-flow-for-wsl-after-win-11s-installation/"><u>Ensuring a Smooth Operational Flow for WSL After Win 11'S Installation</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-to-connect-to-a-network/"><u>Navigating Windows to Connect to a Network</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-enhance-your-channels-image-adding-watermarks-and-logos-to-video-posts/"><u>[New] 2024 Approved  Enhance Your Channel's Image  Adding Watermarks & Logos to Video Posts</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-eye-catching-youtube-most-followed-channels/"><u>2024 Approved  Eye-Catching YouTube  Most Followed Channels</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-google-pixel-fold-drfone-by-drfone-virtual-android/"><u>5 Hassle-Free Solutions to Fake Location on Find My Friends Of Google Pixel Fold | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/discovering-the-most-innovative-youtube-channel-names-a-vloggers-must-have-list-maximum-length-156-characters/"><u>Discovering the Most Innovative Youtube Channel Names  A Vlogger's Must-Have List (Maximum Length  156 Characters)</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-make-a-mark-with-your-first-cool-mac-video-post-on-youtube/"><u>[Updated] 2024 Approved  Make a Mark with Your First Cool Mac Video Post on YouTube</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-infinix-hot-40-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Infinix Hot 40 Pro | Dr.fone</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-capturing-moving-images-mirrorless-versus-dslr/"><u>In 2024, Capturing Moving Images  Mirrorless Versus DSLR</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-decibel-documentation-system-captures-voice-for-2024/"><u>[New] Decibel Documentation  System Captures Voice for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-best-value-for-money-in-budget-4k-cameras-(1000/"><u>[Updated] Best Value for Money in Budget 4K Cameras (<$1,000)</u></a></li>
</ul></div>
