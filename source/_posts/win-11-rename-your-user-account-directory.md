---
title: "Win 11: Rename Your User Account Directory"
date: 2024-08-16T00:14:39.016Z
updated: 2024-08-17T00:14:39.016Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win 11: Rename Your User Account Directory"
excerpt: "This Article Describes Win 11: Rename Your User Account Directory"
keywords: Win XP Renaming,Win PC NewName,QuickWinRenameUser,ChangePCDirectory,SetWinAccountPath,XPUserRenamingTip,WindowsUserDirChange
thumbnail: https://thmb.techidaily.com/2597cd92a0acd8548892430a7d1a31aad74db81001d653dab278938ebfa823a1.jpg
---

## Win 11: Rename Your User Account Directory

### Key Takeaways

* Windows 11 creates a default user profile folder based on the first five characters of your account name, but you can change it using a registry hack.
* Changing the user profile folder name can cause issues with some Microsoft Store apps, but signing out and signing back in may fix the problem.
* To change the user profile folder name, create a new administrator account, modify the registry entries associated with your user account, and then rename the user profile folder in File Explorer.

 When you create a new user account in Windows 11, the operating system automatically creates a new user profile folder in C:\\Users\\Username. However, this default user profile folder name is not always what you want.

 Windows, by default, will use the first five characters of your user account name as the profile folder name. If you don’t like the user profile folder name, you can change it using a registry hack. Here, we show you how to change the name of the user profile folder in Windows 11\.

## But First, Some Potential Issues That May Arise From These Steps

 While the registry hack should help you successfully change your user account folder name, it can lead to some complications. For example, some of your Microsoft Store apps, including OneDrive and Outlook, can stop working.

 Try to sign out and sign in to your app as a quick fix. If that does not work, you’ll need to move the existing path and define the new correct path after changing the user folder name.

 Also, [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and exercise extreme caution while changing your user name folder. Incorrect modification to the Windows Registry can cause serious issues and may require reinstallation of the operating system.

## How to Create a New Administrator User Account in Windows 11

 To change your current user profile name, log into a different administrator account. You cannot modify an existing user account profile path from the same account.

 To do this, you can [enable and use the built-in administrator account in Windows 11](https://www.makeuseof.com/windows-11-enable-disable-built-in-administrator-account/). If not, follow these steps to create a new administrator account in Windows 11\.

 To create a new administrator account:

1. Press **Win + I** to open **Settings**.
2. Open the **Accounts** tab in the left pane.
3. Click on **Family & other users** in the right pane.  
![Windows 11 add user account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/Windows-11-add-user-account.png)
4. Click **Other users.** This option is useful to create a local user account without a Microsoft Account.  
![Add other user account in Windows 11](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/add-other-user-account-windows-11.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
5. Next, click on **I don’t have this person’s sign-in information.**  
![Creating a local user account without a Microsoft account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/create-local-user-account-without-Microsoft-account.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->

1. Click on **Add a user** **without a Microsoft account.**
2. Type a name for the user account. Leave the password field empty and click **Next**.
3. Click on the new user account and click **Change account type.**
4. Click the drop-down for **Account type** and select **Administrator**.
5. Click **OK** to save the changes.

 Now, you can log in with your new administrator account. To do this, click **Start**, then click on the user profile name, and select **Sign out.** Next, sign in with the new administrator account.

<!-- affiliate ads begin -->
<a href="https://checkout.devart.com/order/checkout.php?PRODS=5023555&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/45b430710ad04765a6afd58d9d9fafca/products/dotConnect_O.png" border="0">dotConnect for Oracle is an ADO.NET data provider for Oracle with Entity Framework Support.</a>
<!-- affiliate ads end -->
## How to Change the User Profile Folder Name Using the Registry Editor

 You can modify the registry entries associated with your user account to change the user profile folder name in Windows 11\.

 This process involves modifying your registry entries, so we recommend you create a restore point. You can [use the restore point to restore your PC](https://www.makeuseof.com/use-system-restore-windows/) if something goes wrong during the process.

 To change the user profile folder name:

1. Sign out from your current user account and log in with a built-in or newly created administrator account
2. Next, press **Win + R** to open the **Run** dialog.
3. Type **netplwiz** and click **OK** to open the **User Accounts** dialog.
4. Here, select your **user account** and click on **Properties**.  
![User accounts properties.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/user-accounts-properties.jpg)
5. In the **User Properties** dialog, you’ll see your **User name** and **Full name.**

1. Type a name for your user name, click **OK** and **Apply**.  
![user account user name](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/user-acount-user-name.jpg)
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
2. Close the **User Account** dialog and perform a restart.
3. Next, open the Command Prompt. To do this, press **Win + R,** type **cmd,** and click **OK**.  
![SID command prompt user account.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/SID-command-prompt-user-account.png)
4. In the Command Prompt window, type the following command to view **SID (Security Identifier)** for all user accounts:  
`wmic useraccount get name,SID`
5. Here, note the **SID** for the user account you want to change the user profile folder name. In this case, the **SID** for the username **tashr** is **S-1-5-21-200486166-247335145-1769094253-1001.**

 Now that we have the SID, we must enter it into the Registry Editor. To do that, follow these steps:

1. Press **Win + R**, type **regedit,** and click **OK** to open **Registry Editor.**
2. In the Registry Editor, navigate to the following location:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\ProfileList`
3. Inside the **ProfileList** key, locate and click on the key name identical to the **SID** you noted earlier.
4. In the right pane, right-click on **ProfileImagePath** value and select **Modify**.  
![Modify profile image path in the registry editor.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/modify-profile-image-path-registry-editor.png)
5. Enter a name you want for the profile folder and click **OK**.  
![add new name profile image path registry editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/add-new-name-profile-image-path-registry-editor.png)
6. Close the Registry Editor and Command Prompt window if open.
7. Next, press **Win + E** to open File Explorer and navigate to **C:\\Users\\.**  
![Rename user profile folder name.](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/02/rename-user-profile-folder-name.png)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
8. Select your **user profile** and press **F2** to rename it. Enter a new name for your user profile (it must match the user name entered in the Registry Editor).
9. Click away and then click **Continue** to save the changes.

 You may sometimes encounter the "You can’t perform this action" error when renaming the folder. This error often occurs if you switch to a different administrator account without signing out from the primary user account. Alternatively, restart your PC and repeat the steps to rename the user profile folder without the error.

 Next, log out from your current account and sign in to the user account with the new user folder name. Open File Explorer and navigate to **C:\\Users\\**, and you should be able to use the previous profile with the new pathname.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729320&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/2_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
## Renaming the Default User Profile Folder in Windows 11, Made Easy

 While you can rename the user account in Windows 11 using the Control Panel, doing so will not change the user profile folder name. You need to modify the ProfileImagePath value in the Registry Editor with a different administrator account. Once done, you can remove the new administrator user account to declutter your login screen.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-brain-mechanisms-guiding-high-stakes-business-conclusions/"><u>[New] 2024 Approved  Brain Mechanisms Guiding High-Stakes Business Conclusions</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-elevating-your-content-with-engaging-haul-creation/"><u>[New] In 2024, Elevating Your Content with Engaging Haul Creation</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-seamless-tweeting-expert-video-conversion-software/"><u>[New] Seamless Tweeting  Expert Video Conversion Software</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-audio-interface-innovations-for-optimal-podcasting/"><u>[Updated] Audio Interface Innovations for Optimal Podcasting</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-elevate-your-video-rankings-with-effective-seo-tactics-for-2024/"><u>[Updated] Elevate Your Video Rankings with Effective SEO Tactics for 2024</u></a></li>
<li><a href="https://os-tips.techidaily.com/eat-healthy-foods-rich-in-omega-3-fatty-acids-foods-high-in-omega-3s-have-shown-promising-results-when-it-comes-to-reducing-depressive-symptoms-these-includ19/"><u>Eat Healthy Foods Rich in Omega-3 Fatty Acids: Foods High in Omega 3’S Have Shown Promising Results when It Comes to Reducing Depressive Symptoms. These Include Fish Oils (Salmon or Tuna), Flaxseed Oil Capsules, Walnuts & Soybeans Amongst Other Sources</u></a></li>
<li><a href="https://win11.techidaily.com/eliminate-x80072f30-quick-fix-for-windows-store-problems/"><u>Eliminate X80072F30: Quick Fix for Windows Store Problems</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/enchanting-viewers-the-art-of-crafting-engaging-youtube-description-templates/"><u>Enchanting Viewers  The Art of Crafting Engaging YouTube Description Templates</u></a></li>
<li><a href="https://win11.techidaily.com/essential-fixes-for-non-complying-windows-scripts/"><u>Essential Fixes for Non-Complying Windows Scripts</u></a></li>
<li><a href="https://win11.techidaily.com/fixes-for-absence-of-rockalldll-in-windows-os/"><u>Fixes for Absence of Rockalldll in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-controlling-installer-service-in-windows/"><u>Guide to Controlling Installer Service in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/improve-energy-monitoring-full-charge-alerts-for-a-more-efficient-win11/"><u>Improve Energy Monitoring: Full Charge Alerts for a More Efficient Win11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-can-you-transfer-files-from-oneplus-nord-n30-se-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How Can You Transfer Files From OnePlus Nord N30 SE To iPhone 15/14/13? | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-how-to-make-any-tiktok-audio-the-ultimate-cellphone-sound/"><u>In 2024, How To Make Any TikTok Audio, the Ultimate Cellphone Sound</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-itel-a60-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, iSpoofer is not working On Itel A60? Fixed | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-asus-rog-phone-7-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Asus ROG Phone 7 Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://win11.techidaily.com/insight-into-windows-11s-new-automated-data-safeguarding/"><u>Insight Into Windows 11’S New Automated Data Safeguarding</u></a></li>
<li><a href="https://win11.techidaily.com/keep-your-window-pc-always-unlocked/"><u>Keep Your Window PC Always Unlocked</u></a></li>
<li><a href="https://win11.techidaily.com/key-techniques-for-win10-blue-screen-resolution/"><u>Key Techniques for Win10 Blue Screen Resolution</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-windows-accessibility-features/"><u>Navigating Through Windows' Accessibility Features</u></a></li>
<li><a href="https://win11.techidaily.com/personalized-pixels-designing-unique-displays-on-each-monitor-of-windows/"><u>Personalized Pixels: Designing Unique Displays on Each Monitor of Windows</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-modify-indexer-in-windows/"><u>Step-by-Step: Modify Indexer in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-disable-protected-app-ban-on-windows/"><u>Steps to Disable Protected App Ban on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-git-operations-with-github-desktop-and-windows-1011/"><u>Streamlining Git Operations with GitHub Desktop & Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/swift-keystrokes-in-win-os-a-guide-to-eliminate-delay/"><u>Swift Keystrokes in WIN OS: A Guide to Eliminate Delay</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-search-service-not-available-on-windows/"><u>Tackling Search Service Not Available on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-artisans-approach-to-perfect-slide-printouts-from-powerpoint-in-windows/"><u>The Artisan's Approach to Perfect Slide Printouts From PowerPoint in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-sound-surge-5-apps-to-take-windows-volume-well-above-100/"><u>The Sound Surge: 5 Apps to Take Windows' Volume Well Above 100%%</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/transform-your-channels-look-for-free-for-2024/"><u>Transform Your Channel's Look for Free for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/trouble-removing-epic-games-hub-from-windows-11-a-quick-guide/"><u>Trouble Removing Epic Games Hub From Windows 11: A Quick Guide</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-office-outlook-alerts-in-windows/"><u>Troubleshooting Non-Functional Office Outlook Alerts in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-disruptions-preventing-unexpected-crashes-in-dwarf-fortress/"><u>Unraveling Disruptions: Preventing Unexpected Crashes in Dwarf Fortress</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-when-windows-cant-locate-powershell-console/"><u>What to Do When Windows Can't Locate PowerShell Console</u></a></li>
<li><a href="https://win11.techidaily.com/windows-installation-manual-for-chatgpt/"><u>Windows Installation Manual for ChatGPT</u></a></li>
<li><a href="https://win11.techidaily.com/windows-users-save-your-keys-from-failure/"><u>Windows Users: Save Your Keys From Failure</u></a></li>
</ul></div>
