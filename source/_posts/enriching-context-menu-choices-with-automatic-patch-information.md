---
title: Enriching Context Menu Choices with Automatic Patch Information
date: 2024-08-15T23:37:59.437Z
updated: 2024-08-16T23:37:59.437Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enriching Context Menu Choices with Automatic Patch Information
excerpt: This Article Describes Enriching Context Menu Choices with Automatic Patch Information
keywords: Menu Enhancement,Auto Patch Info,Context UI Upgrade,Patch Detection Tool,Quick Fix Options,Menu Customization,Real-Time Update Aid
thumbnail: https://thmb.techidaily.com/cdf09465082716a317b2f16f4ef99338eb56d0b864c0910b3b97914866d756b0.jpg
---

## Enriching Context Menu Choices with Automatic Patch Information

 Microsoft regularly releases patch updates for both Windows 10 and 11 every month. These patch updates typically address security vulnerabilities and fix Windows bugs and issues. Although those updates are usually automatically installed, sometimes your PC will miss the memo. And sometimes, the update itself is an optional download.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.

## Add a Check for Updates Shortcut to the Context Menu

 Windows 11 doesn’t include any built-in options for adding shortcuts to the desktop’s right-click context menu. However, you can still add a **Check for Updates** shortcut for the **Windows Update** tab to that menu by [manually editing the registry](https://www.makeuseof.com/tag/what-is-the-windows-registry-editor-and-how-do-i-use-it-makeuseof-explains/). Once done, you can open the **Windows Update** tab directly from the desktop’s context menu.

 To add that context menu shortcut, edit the registry as follows:

1. Right-click the **Start** button and select the **Run** shortcut to launch that accessory.
2. [Open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/) by typing **regedit** in the **Open** box and clicking **OK**.
3. Then navigate to the **Computer** \> **HKEY\_CLASSES\_ROOT** \> **DesktopBackground** \> **Shell** registry key.
4. Right-click the **Shell** key to select the **New** submenu option.
5. Select the **Key** option.  
![The Key option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/key-option.png)

1. Type **Check for Updates** to be the new key’s name.
2. Right-click the **Check for Updates** key and select **New** on the context menu.
3. Click the **Key** option again.
4. Now input **command** for the new key’s name.
5. Select the **Check for Updates** key, and then right-click a space on the right side of the Registry Editor to select **New > String Value**.  
![The String Value option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/string-value-option.png)

1. Type **SettingsURI** to be the new string’s name.
2. Double-click **SettingsURI** to open an Edit String window.
3. Type **ms-settings:windowsupdate-action** within the Value data box, and click **OK**.  
![The Edit String window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/edit-string-window.png)
4. Right-click the **command** key and select the **New** \> **String Value** options.
5. Enter the string title **DelegateExecute**, and press the **Return** key.  
![The DelegateExecute string for the command key](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/delegateexecute_string.png)
6. Double-click the **DelegateExecute** string to bring up its Value data box.
7. Type **{556FF0D6-A1EE-49E5-9FA4-90AE116AD744}** in the Value data text box, and press the **OK** button.
8. Close the Registry Editor’s window.

 Now right-click an area of your Windows 11 desktop and select **Show more options** to bring up the classic context menu. If you’ve edited the registry correctly, that menu will include a **Check for Updates** option. Select that option to open Settings’ **Windows Update** tab. Then you can click the **Check for updates** button on that tab.

![The Check for Updates context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/check-for-updates-context-menu-option.png)

 Alternatively, press the **Shift** + **F10** hotkey to bring up the classic context menu without right-clicking the desktop. That keyboard shortcut opens the classic context menu at the top left of the desktop. Then you can select **Check for Updates** from there to bring up the tab shown below.

![The Windows Update tab](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2021/11/check_for_updates_button.png)

 This registry trick works much the same on Windows 10\. The only difference is that you won’t need to select **Show more options**. As Windows 10’s desktop context menu is the classic one, it doesn’t include **Show more options**. You can select **Check for Updates** on its primary context menu.

 If you ever want to remove the **Check for Updates** shortcut from the context menu, open the **Shell** key in the Registry Editor again. Then right-click the **Check for Updates** key to select **Delete**.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1596691/17882" target="_top" id="1596691"><img src="//a.impactradius-go.com/display-ad/17882-1596691" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1596691/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Add a Windows Update Submenu to the Context Menu With Winaero Tweaker

 Winaero Tweaker is a freely available customization software for Windows with which you can customize the context menu in many ways. That software has an option you can select to add a **Windows Update** submenu to the context menu, which includes a **Check for updates** shortcut. This is how you can add a **Check for updates** shortcut to the desktop’s right-click menu with Winaero Tweaker:

1. Go to this [Winaero Tweaker webpage](https://winaero.com/download-winaero-tweaker/) in your browsing software.
2. Next, click the **Click here to download file** link.
3. Install and run the Winaero Tweaker software with the downloaded setup file. This [Winaero Tweaker customization guide](https://www.makeuseof.com/windows-11-winaero-tweaker-guide/) includes full installation instructions for that software.
4. Double-click the **Context menu** category within Winaero Tweaker’s left sidebar.
5. Click on the **Windows Update** setting.  
![The Add Windows Update submenu to Desktop context menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-context-menu-option.jpg)
<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. Select the **Add Windows Update submenu to Desktop context menu** option.

 Now look at the new Windows Update submenu on the desktop’s context menu. Press **Shift** \+ **F10** to view the classic context menu. Move the cursor over the **Windows Update** submenu to view its options. There you can select a **Check for updates** option to bring up the **Check for updates** button.

![The Windows Update submenu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-windows-update-submenu.jpg)
<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->

 The **Windows Update** submenu also has four other shortcuts to update settings. Click **Update history** to view the installed update list. Or select **Advanced options** to bring up the additional settings for updates. The **Restart options** shortcut opens the settings for scheduling update times.

 Winaero Tweaker also has a customization option for adding a **Windows Update** shortcut to the Control panel. To access that option, click **Settings and** **Control Panel** \> **Add Windows Update** in Winaero Tweaker’s sidebar. Click the **Add Windows Update to Control Panel\\System and Security** checkbox to select that option.

![The Add Windows Update to Control Panel option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/the-add-windows-update-to-control-panel-option.jpg)
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then you’ll see a **Windows Update** shortcut within the Control Panel. [Open the Control Panel](https://www.makeuseof.com/windows-11-open-control-panel/) and click the **System and Security** category. Clicking the **Windows Update** shortcut there will open the **Settings** tab with the **Check for updates** button.

![The Windows Update Control Panel shortcut](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/09/windows-update-in-control-panel.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Keep an Eye Out For New Windows Updates

 So, now you can select a handy **Check for Updates** shortcut on your desktop’s context menu. That shortcut will save you from having to manually open Settings and its **Windows Update** tab whenever you need to check for updates. Instead, you can simply click the **Check for Updates** context menu option to open the update tab directly from the desktop.

 Select that shortcut to keep an eye out for new updates regularly. When optional updates are available, you’ll see them listed on the tab with **Download and install** options. Clicking **Check for updates** will automatically download and install available updates.

 To ensure your Windows 11/10 PC has all the patch updates available for it, it’s a good idea to check for new ones via Settings. The **Windows Update** tab includes a **Check for updates** button. You can add a shortcut for that tab to the desktop’s context menu with the method below.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>


<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-seamless-tactic-for-igtv-stories-integration/"><u>[New] In 2024, Seamless Tactic for IGTV Stories Integration</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-inside-look-analyzing-androids-photoshop-substitute-lightroom/"><u>[New] Inside Look  Analyzing Android's Photoshop Substitute, Lightroom</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-supercharge-your-social-media-best-apps-for-post-and-followers/"><u>[Updated] 2024 Approved  Supercharge Your Social Media  Best Apps for Post & Followers</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-generate-10-official-travel-ready-passport-images-no-money-down/"><u>[Updated] Generate 10 Official Travel-Ready Passport Images, No Money Down</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-quantum-hdr-explained-the-ultimate-resource/"><u>2024 Approved  Quantum HDR Explained  The Ultimate Resource</u></a></li>
<li><a href="https://win11.techidaily.com/5-clear-signals-its-time-for-windows-reset/"><u>5 Clear Signals It's Time for Windows Reset</u></a></li>
<li><a href="https://win11.techidaily.com/achieving-seamless-warhammer-gaming-on-windows-stop-stuttering/"><u>Achieving Seamless Warhammer Gaming on Windows: Stop Stuttering</u></a></li>
<li><a href="https://windows11.techidaily.com/addressing-win1011-system-breakdown-code-0xc0000001/"><u>Addressing Win10/11 System Breakdown: Code 0xC0000001</u></a></li>
<li><a href="https://win11.techidaily.com/analyzing-surface-laptop-go-3-processor-boost-and-critique/"><u>Analyzing Surface Laptop Go 3: Processor Boost and Critique</u></a></li>
<li><a href="https://win11.techidaily.com/bridge-android-and-windows-gameplay-unification-with-google-play/"><u>Bridge Android and Windows: Gameplay Unification with Google Play</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/bypass-iphone-7-plus-activation-lock-with-a-professional-tool-by-drfone-ios-unlock-ios-unlock/"><u>Bypass iPhone 7 Plus activation lock with a professional tool</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/emblematic-italian-hands-everyday-expressions/"><u>Emblematic Italian Hands: Everyday Expressions</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-11-quality-over-novelties/"><u>Enhancing Windows 11: Quality over Novelties</u></a></li>
<li><a href="https://win11.techidaily.com/essential-tips-to-run-the-sfc-tool-successfully/"><u>Essential Tips to Run the SFC Tool Successfully</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-updater-error-0x80246007-in-windows-versions-1011/"><u>Fixing Updater Error 0X80246007 in Windows Versions 10/11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-iphone-x-data-from-ios-itunes-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How to Recover iPhone X Data From iOS iTunes? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-nokia-c22-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Nokia C22 online without jailbreak</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-dissecting-deceptive-accounts-in-your-ad-audience/"><u>In 2024, Dissecting Deceptive Accounts in Your Ad Audience</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-downloading-samfw-frp-tool-30-for-realme-gt-neo-5-by-drfone-android/"><u>In 2024, Downloading SamFw FRP Tool 3.0 for Realme GT Neo 5</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-stream-anything-from-realme-narzo-60x-5g-to-apple-tv-drfone-by-drfone-android/"><u>In 2024, How To Stream Anything From Realme Narzo 60x 5G to Apple TV | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-honor-v-purse-drfone-by-drfone-android/"><u>In 2024, How To Use Allshare Cast To Turn On Screen Mirroring On Honor V Purse | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-update-problem-with-error-0xca00a009/"><u>Mitigating Update Problem with Error 0xCA00A009</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/mobile-artistry-ios-and-androids-creme-de-la-creme-of-image-stickers/"><u>Mobile Artistry  IOS and Android's Crème De La Crème of Image Stickers</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-dism-failure-0x800f082f/"><u>Resolving Windows' DISM Failure 0X800F082F</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-stalled-email-notifications-in-windows-environment/"><u>Reviving Stalled Email Notifications in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-windows-experience-7-fixes-for-broken-apps/"><u>Seamless Windows Experience: 7 Fixes for Broken Apps</u></a></li>
<li><a href="https://win11.techidaily.com/speedy-disabling-of-windows-11-alerts/"><u>Speedy Disabling of Windows 11 Alerts</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-activating-newly-redesigned-widget-tool/"><u>Step-by-Step Guide: Activating Newly Redesigned Widget Tool</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-recognize-non-appearing-hdd/"><u>Strategies to Recognize Non-Appearing HDD</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-a-productive-win-11-taskbar/"><u>The Ultimate Guide to a Productive Win 11 Taskbar</u></a></li>
<li><a href="https://win11.techidaily.com/top-4-techniques-for-mac-address-discovery-in-windows-11/"><u>Top 4 Techniques for Mac Address Discovery in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-boot-on-windows-sound-service-reboot-needs/"><u>Troubleshooting Boot-On Windows Sound Service Reboot Needs</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-responsive-touchpad-gestures-on-windows/"><u>Troubleshooting Non-Responsive Touchpad Gestures on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/turbo-windows-11-app-opening-secrets-revealed/"><u>Turbo Windows 11 App Opening Secrets Revealed</u></a></li>
<li><a href="https://techidaily.com/undeleted-lost-videos-from-m6-pro-4g-by-fonelab-android-recover-video/"><u>Undeleted lost videos from M6 Pro 4G</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlock-your-poco-f5-pro-5gs-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>Unlock Your Poco F5 Pro 5Gs Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-webs-best-vertical-video-editing-software-updated-2023/"><u>Updated In 2024, Webs Best Vertical Video Editing Software (Updated 2023)</u></a></li>
<li><a href="https://win11.techidaily.com/windows-save-location-glitch-quick-guide/"><u>Windows Save Location Glitch: Quick Guide</u></a></li>
</ul></div>
