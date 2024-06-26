---
title: "Mastery Guide: Skipping PIN on Window's Win11 Cast"
date: 2024-06-25T11:26:08.912Z
updated: 2024-06-26T11:26:08.912Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Mastery Guide: Skipping PIN on Window's Win11 Cast"
excerpt: "This Article Describes Mastery Guide: Skipping PIN on Window's Win11 Cast"
keywords: Win11 Cast Secure Access,Skip PIN in Windows,Win11 PIN Bypassing Guide,Secure Casting W11,Easy Win11 Pin Bypass,Streamline Win11 Cast,Optimize Win11 Security
thumbnail: https://thmb.techidaily.com/90cf06f9730c5591652ae4f421f62950743940a3b49411aac162c7581850732b.jpg
---

## Mastery Guide: Skipping PIN on Window's Win11 Cast

 Windows requires a PIN when projecting your computer onto another screen, such as a projector or a second monitor. Doing so prevents others from accessing your private information or projecting their content onto your computer.

 However, if you’re the only person using your computer, you may find this extra security measure unnecessary. Let’s explore how to disable the "require PIN for pairing" setting when projecting to your PC in Windows 11\.

## 1\. Using Windows Settings

 Windows has a built-in app that allows you to change various settings. You can use this app to turn off the “require PIN for pairing” setting when projecting to your PC. Here’s how to do it:

1. [Open the Settings menu](https://www.makeuseof.com/windows-ways-to-open-system-settings/).
2. From the left sidebar, select the **System** tab.
3. Scroll down to the **Projecting to this PC** section and click on it.

 On the next page, look for the **Require a PIN for pairing** setting. Click on its drop-down menu, and you’ll see three options:

* **Never:** Never ask for a PIN for pairing when projecting to this PC.
* **First Time:** Require a PIN the first time you’re projecting to this PC.
* **Always:** Always requiring a PIN for pairing when projecting to this PC.

 Choose the **Never** option and exit the Settings window. The settings will be saved automatically, and you won’t need to enter a PIN when projecting your computer onto another display.

 If you don’t see **Require a PIN for pairing** in the **Projecting to this PC** section, the feature is disabled on your computer.

 To enable this feature, click on the **Optional features** link. You can also navigate to **Settings** \> **Apps** \> **Optional features** to access the same page. Doing so will open the optional features window.

![Add the Wireless Display optional feature](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/add-the-wireless-display-optional-feature.jpg)

 Click the **Add an optional feature** button and search for **Wireless Display**. You should see the Wireless Display feature listed in the search results. Check the box next to it and click **Next** \> **Install**.

![Add an optional feature](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/add-an-optional-feature.jpg)

 Once the feature is installed, return to the Projecting to this PC section in Settings. You should now see the “require a PIN for pairing” setting. Choose the **Never** option and close the window.

## 2\. Using the Group Policy Editor

 Another option is to use the Group Policy Editor. This method requires you to have a Pro or Enterprise Windows version. However, you can [activate the Group Policy Editor in Windows Home Edition](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 Once you’ve done that, follow these steps to turn off the feature:

1. Press **Win + R** on your keyboard to open the Run dialog box.
2. Type **gpedit.msc** in the text field and press **Enter**. This will open the Group Policy Editor window.
3. From the left sidebar, navigate to the following path:  
`Computer Configuration > Administrative Templates > Windows Components > Connect​`
4. On the right side of the window, look for **Require pin for pairing** and double-click on it. Doing so will open the policy settings page.  
![Disable the Require pin for pairing policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-the-require-pin-for-pairing-policy.jpg)
5. Select the **Enabled** radio button and select **Never** from the drop-down menu.  
![Never Require Pin For Pairing in GPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/never-require-pin-for-pairing-in-gpe.jpg)
6. Click **Apply** \> **OK** to save the changes.

 After that, exit out of the window. When projecting your computer onto another screen, you won’t need a PIN anymore.

## 3\. Using the Registry Editor

 If you can’t access the Group Policy Editor, you can use the Registry Editor to disable the “Require PIN for Pairing” setting. This method involves editing the Windows registry, so [creating a system restore point](https://www.makeuseof.com/windows-11-create-restore-point/) and [backing up the registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before proceeding is essential. That way, you can easily restore your computer if anything goes wrong.

 Once you’ve done that, follow these steps to turn off the feature:

1. Press the **Windows** key to open the Start menu.
2. Type **regedit** in the search bar and hit **Enter** to open the Registry Editor.
3. If the User Account Control window prompts, click **Yes** to give the program permission.
4. In the left sidebar, navigate to this path:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Connect`
5. If you don’t see the Connect key at this location, right-click on Windows and select **New > Key**. Name it **Connect** and press **Enter**.
6. Now, right-click on Connect and select **New** \> **DWORD (32-bit) Value**.
7. Name the value **RequirePinForPairing** and press **Enter**. Doing so will create a new DWORD in the registry.
8. Double-click on this newly created value to open its Properties window.  
![Tweak Registry to Disable Require PIN for Pairing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/tweak-registry-to-disable-require-pin-for-pairing.jpg)
9. Set the **Value data** to **0** and click **OK** to save the changes.

 Once you've done that, exit the Registry Editor window and restart your computer. After restart, you won't need a PIN when projecting your computer onto another screen.

 To turn the feature back on, follow the same steps but set the **Value data** to **1**. This will enable the required PIN for pairing settings when projecting to a Windows 11 PC​​​​​.

## 4\. Using a REG File

 The fourth and final option is to use a REG file. This method is for those who have little or no experience with the Registry Editor. The REG file contains instructions that edit the Windows registry on your behalf. If you'd rather use this method, here’s what you need to do:

1. Right-click on Start and select **Run** from the menu.
2. Type **Notepad** in the text field and press **Enter**.
3. In the Notepad window, type or copy-paste the following code lines:  
`<code>Windows Registry Editor Version 5.00  

[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Connect]  
"RequirePinForPairing"=dword:00000001`
4. Click **File** and select **Save as** from the menu.
5. In the Save As window, click the **Save as type** drop-down menu and select **All files**.
6. Name the file **DisableRequirePin.reg** and select **Desktop** from the left sidebar.  
![Disable the Required PIN for Pairing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-the-required-pin-for-pairing.jpg)
7. Now click **Save** and exit Notepad. You'll find the REG file on your desktop.
8. Double-click on it and select **Yes** when prompted. This will edit the registry on your behalf.

 Once done, restart your computer and the settings will be saved automatically. You won't need to enter a PIN when projecting your PC onto another screen.

 If you ever want to re-enable this feature, repeat the same steps as above and use this code in Notepad:

`<code>Windows Registry Editor Version 5.00  
  
[HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\Connect]  
"RequirePinForPairing"=dword:00000003`

 Save the file with the **EnableRequirePin.reg** filename and double-click on it to edit the registry.

 After that, restart your computer and the setting will be enabled. You'll now need to enter a PIN each time you project the PC onto another screen.

## Project to a Windows 11 PC Without Requiring a PIN

 Projecting your PC onto another display is a useful feature that allows you to mirror or extend your computer screen. Now you know how to do so without needing to enter your PIN every time.

 However, if you’re the only person using your computer, you may find this extra security measure unnecessary. Let’s explore how to disable the "require PIN for pairing" setting when projecting to your PC in Windows 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/fixing-frozen-grammarly-app-a-windows-users-guide/"><u>Fixing Frozen Grammarly App: A Windows User's Guide</u></a></li>
<li><a href="https://win11.techidaily.com/old-school-keys-new-horizon-initiate-windows-11-with-windows-7-key/"><u>Old-School Keys, New Horizon: Initiate Windows 11 with Windows 7 Key</u></a></li>
<li><a href="https://win11.techidaily.com/deleting-windows-bt-directory-purpose-and-process/"><u>Deleting Windows ~BT Directory: Purpose & Process</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-and-correcting-error-0x80004004-on-defender/"><u>Deciphering and Correcting Error 0X80004004 on Defender</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-mouse-pointer-prominence-in-windows-11/"><u>Enhancing Mouse Pointer Prominence in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/confirming-the-health-of-your-windows-11-setup/"><u>Confirming the Health of Your Windows 11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/1719322242538-mastering-printer-troubles-reactivating-missing-wwinplusp-on-windows/"><u>Mastering Printer Troubles: Reactivating Missing WWin+P on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/a-novices-guide-to-windows-11-sound-capture/"><u>A Novice's Guide to Windows 11 Sound Capture</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-microsofts-safe-mode-only-constraint/"><u>Navigating Through Microsoft's Safe Mode Only Constraint</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-strategies-for-effective-storage-of-chats-and-calls-on-facebook/"><u>In 2024, Strategies for Effective Storage of Chats and Calls on Facebook</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-mastering-tiktok-crafting-video-content-with-background-melodies/"><u>[Updated] Mastering TikTok  Crafting Video Content with Background Melodies</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/neat-screen-capture-utility-win10/"><u>Neat Screen Capture Utility, Win10</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-apple-iphone-6s-plus-drfone-by-drfone-virtual-ios/"><u>Spoofing Life360 How to Do it on Apple iPhone 6s Plus? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-cutting-edge-strategies-for-youtube-split-screen-videos/"><u>[New] In 2024, Cutting-Edge Strategies for YouTube Split-Screen Videos</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-extract-youtube-trailers-and-more-for-2024/"><u>[Updated] How to Extract YouTube Trailers & More for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/crafting-perfect-instagram-story-cover-pages-for-2024/"><u>Crafting Perfect Instagram Story Cover Pages for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-windows-10s-top-rated-free-dvd-players-2023-edition-for-2024/"><u>New Windows 10S Top-Rated Free DVD Players (2023 Edition) for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/2024-approved-embedding-youtube-playlists-with-minimal-complexity-and-maximum-impact/"><u>2024 Approved  Embedding YouTube Playlists with Minimal Complexity and Maximum Impact</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-adding-oomph-to-your-videos-a-tutorial-on-finding-and-using-free-sound-effects-in-final-cut-pro/"><u>Updated In 2024, Adding Oomph to Your Videos A Tutorial on Finding and Using Free Sound Effects in Final Cut Pro</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>