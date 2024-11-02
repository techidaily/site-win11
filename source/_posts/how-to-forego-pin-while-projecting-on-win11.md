---
title: How to Forego PIN While Projecting on Win11
date: 2024-10-30T03:54:32.290Z
updated: 2024-11-01T22:10:24.670Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Forego PIN While Projecting on Win11
excerpt: This Article Describes How to Forego PIN While Projecting on Win11
keywords: Win11 Screen Projection WITHOUT Pin,ByPass PIN Win11 Display,Win11 Without Password Projec,No PIN Projecting Win11,Bypass PIN on Win11 Show,Display Win11 No Pin Needed,Free Win11 Screen Cast No Pin
thumbnail: https://thmb.techidaily.com/c89ca4d2db8c8241f93b3a96e44489938109c01f6c557fc5515bb23aae45515d.JPG
---

## How to Forego PIN While Projecting on Win11

 Windows requires a PIN when projecting your computer onto another screen, such as a projector or a second monitor. Doing so prevents others from accessing your private information or projecting their content onto your computer.

 However, if you’re the only person using your computer, you may find this extra security measure unnecessary. Let’s explore how to disable the "require PIN for pairing" setting when projecting to your PC in Windows 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1610918/18409" target="_top" id="1610918">
  <img src="//a.impactradius-go.com/display-ad/18409-1610918" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://coinrule.sjv.io/i/5597632/1610918/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Never Require Pin For Pairing in GPE](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/never-require-pin-for-pairing-in-gpe.jpg)
6. Click **Apply** \> **OK** to save the changes.

<!-- affiliate ads begin -->
<span id="1160850">
					<video width="576" height="324" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1160850.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1160850">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1160850.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1160850%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1160850/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After that, exit out of the window. When projecting your computer onto another screen, you won’t need a PIN anymore.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111981/7443" target="_top" id="2111981">
  <img src="//a.impactradius-go.com/display-ad/7443-2111981" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111981/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<span id="1424531">
					<video width="864" height="NaN" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424531.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424531">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424531.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424531%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424531/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Project to a Windows 11 PC Without Requiring a PIN

 Projecting your PC onto another display is a useful feature that allows you to mirror or extend your computer screen. Now you know how to do so without needing to enter your PIN every time.

 However, if you’re the only person using your computer, you may find this extra security measure unnecessary. Let’s explore how to disable the "require PIN for pairing" setting when projecting to your PC in Windows 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-dissecting-youtube-policies-and-creative-commons-licensing-dichotomy-for-2024/"><u>[New] Dissecting YouTube Policies and Creative Commons Licensing Dichotomy for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-efficiently-uploading-youtube-vids-to-insta-profile/"><u>[Updated] In 2024, Efficiently Uploading YouTube Vids to Insta Profile</u></a></li>
<li><a href="https://some-approaches.techidaily.com/5-best-dvd-creators-for-macos-sierra-for-2024/"><u>5 Best DVD Creators for macOS Sierra for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/free-hp-sound-card-software-update-fast-and-simple-installation/"><u>Free HP Sound Card Software Update: Fast and Simple Installation</u></a></li>
<li><a href="https://win11.techidaily.com/from-ordinary-to-extraordinary-crafting-winning-slideshows-and-perfecting-images-in-win11-photos-app/"><u>From Ordinary to Extraordinary: Crafting Winning Slideshows & Perfecting Images in Win11 Photos App</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-make-your-printer-work-again-on-pc/"><u>How to Make Your Printer Work Again on PC</u></a></li>
<li><a href="https://win11.techidaily.com/ifttt-mastery-for-enhanced-productivity/"><u>IFTTT Mastery for Enhanced Productivity</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-how-to-record-a-podcast-on-iphone-or-ipad-best-for-interviews-and-travel/"><u>In 2024, How To Record a Podcast on iPhone or iPad (Best for Interviews & Travel)</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/intuitive-puzzle-quests-on-ios-platforms-games-inspired-by-the-room-and-myst/"><u>Intuitive Puzzle Quests on iOS Platforms: Games Inspired by 'The Room' & 'Myst'</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-converting-mkv-videos-to-mp4-in-windows/"><u>Mastering the Art of Converting MKV Videos to MP4 in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/powerful-tools-for-data-handling-mastering-archive-creation-on-pc/"><u>Powerful Tools for Data Handling: Mastering Archive Creation on PC</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-microsoft-store-failure-code-x800704cf/"><u>Rectifying Microsoft Store Failure Code X800704CF</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/remove-the-lock-screen-fingerprint-of-your-realme-12plus-5g-by-drfone-android/"><u>Remove the Lock Screen Fingerprint Of Your Realme 12+ 5G</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-legacy-computers-with-the-latest-microsoft-os/"><u>Reviving Legacy Computers with the Latest Microsoft OS</u></a></li>
<li><a href="https://fox-that.techidaily.com/speed-hacks-quickly-enhance-safari-performance-on-iphone-heres-how/"><u>Speed Hacks: Quickly Enhance Safari Performance on iPhone Here's How</u></a></li>
<li><a href="https://win11.techidaily.com/the-7-best-windows-11-widgets-for-productivity/"><u>The 7 Best Windows 11 Widgets for Productivity</u></a></li>
<li><a href="https://hardware-help.techidaily.com/update-your-msi-b35tomahawk-motherboard-with-latest-drivers-ensure-compatibility-on-windows-11-and-7-systems/"><u>Update Your MSI B35ˈTOMAHAWK Motherboard with Latest Drivers: Ensure Compatibility on Windows 11 & 7 Systems</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-how-to-add-audio-to-avi/"><u>Updated 2024 Approved How to Add Audio to AVI</u></a></li>
<li><a href="https://win11.techidaily.com/windows-admin-launching-cmd-with-elevated-privileges/"><u>Windows Admin: Launching CMD with Elevated Privileges</u></a></li>
</ul></div>

