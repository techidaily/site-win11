---
title: Trick to Avoid PIN When Casting Screen in Windows 11
date: 2024-10-02T03:53:14.614Z
updated: 2024-10-03T21:37:26.529Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Trick to Avoid PIN When Casting Screen in Windows 11
excerpt: This Article Describes Trick to Avoid PIN When Casting Screen in Windows 11
keywords: PIN Protection Tips,No More Pin Entry,Secure Screen Cast,Cast Without PIN,Password-Free Screens,Safe Windows Casting,Avoid PIN Casting
thumbnail: https://thmb.techidaily.com/2ba5849aea90d4e5d7bbd18adc2a2c9c0f1eeac29f573eb68f13f17cdd7b780f.jpg
---

## Trick to Avoid PIN When Casting Screen in Windows 11

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

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/947746/11832" target="_top" id="947746">
  <img src="//a.impactradius-go.com/display-ad/11832-947746" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/947746/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<span id="1983588">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983588.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983588">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983588.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983588%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983588/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After that, exit out of the window. When projecting your computer onto another screen, you won’t need a PIN anymore.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126493/26400" target="_top" id="2126493">
  <img src="//a.impactradius-go.com/display-ad/26400-2126493" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126493/26400" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136536/16384" target="_top" id="2136536">
  <img src="//a.impactradius-go.com/display-ad/16384-2136536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136536/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-disseminate-vimeo-videos-widely/"><u>[New] 2024 Approved Disseminate Vimeo Videos Widely</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-cross-platform-filmography-syncing-smartphones-and-systems/"><u>[New] Cross-Platform Filmography Syncing Smartphones and Systems</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-youth-inspiration-tales-of-overcoming-challenges/"><u>[New] Youth Inspiration Tales of Overcoming Challenges</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-crafting-compelling-youtube-profile-definitions/"><u>2024 Approved Crafting Compelling YouTube Profile Definitions</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-integrating-skype-into-zoom-meetings-made-simple/"><u>2024 Approved Integrating Skype Into Zoom Meetings Made Simple</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-xiaomi-redmi-note-12-pro-5g-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Xiaomi Redmi Note 12 Pro 5G without App | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/cracking-the-code-windows-versioning-insight/"><u>Cracking the Code: Windows Versioning Insight</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-windows-1111-ui-for-auto-check-updates/"><u>Enabling Windows 11/11 UI for Auto-Check Updates</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-infinix-smart-8-pro-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Infinix Smart 8 Pro | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/keep-it-burning-ensuring-an-everlasting-snapchat-connection/"><u>Keep It Burning Ensuring an Everlasting Snapchat Connection</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-xbox-mic-troubleshooting-in-windows-11-platforms/"><u>Mastering Xbox Mic Troubleshooting in Windows 11 Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-network-navigation-for-the-elusive-mac-on-windows-11/"><u>Navigating Network Navigation for the Elusive MAC on WIndows 11</u></a></li>
<li><a href="https://win11.techidaily.com/perfecting-ui-fidelity-on-newest-windows-release/"><u>Perfecting UI Fidelity on Newest Windows Release</u></a></li>
<li><a href="https://win11.techidaily.com/quickly-link-tofrom-bing-chat-in-windows-11-search-field/"><u>Quickly Link To/From Bing Chat in Windows 11 Search Field</u></a></li>
<li><a href="https://techidaily.com/remove-infinix-lock-screen-without-password-infinix-hot-40-pro-by-drfone-android-unlock-android-unlock/"><u>Remove Infinix Lock Screen without Password(Infinix Hot 40 Pro)</u></a></li>
<li><a href="https://win11.techidaily.com/time-tracker-tweaks-top-apps-to-modify-file-timestamps-on-pc/"><u>Time Tracker Tweaks: Top Apps to Modify File Timestamps on PC</u></a></li>
<li><a href="https://win11.techidaily.com/transform-windows-into-a-personalized-oasis-8-winbubble-upgrades/"><u>Transform Windows Into a Personalized Oasis: 8 WinBubble Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/turning-phones-into-windows-audio-input/"><u>Turning Phones Into Windows Audio Input</u></a></li>
<li><a href="https://apple-account.techidaily.com/unlock-apple-id-without-phone-number-on-iphone-14-by-drfone-ios/"><u>Unlock Apple ID without Phone Number On iPhone 14</u></a></li>
</ul></div>

