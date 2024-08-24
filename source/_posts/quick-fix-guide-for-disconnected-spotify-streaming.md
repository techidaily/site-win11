---
title: Quick-Fix Guide for Disconnected Spotify Streaming
date: 2024-08-23T06:09:32.983Z
updated: 2024-08-24T06:09:32.983Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick-Fix Guide for Disconnected Spotify Streaming
excerpt: This Article Describes Quick-Fix Guide for Disconnected Spotify Streaming
keywords: Fix Disconnected Spotify,Quick Spotify Connect,Restore Spotify Sound,Reconnect Spotify Music,Spotify Connection Guide,Spotify Streaming Fix,Reset Spotify Audio
thumbnail: https://thmb.techidaily.com/f386bcd1cdef2e7eae82e10cf44eeb6665615e5a19222b7cb69d0ec540888707.jpg
---

## Quick-Fix Guide for Disconnected Spotify Streaming

 Spotify is one of the best Windows apps for streaming and downloading music. However, some Spotify users can’t stream and download music with that app because of error code 4\. Error code 4 is a Spotify connectivity issue with a message that says, “No internet connection detected.” Yet, users can usually still open and view websites when that issue arises.

 Users who need to fix error code 4 can’t utilize the Spotify app online. That means things like radio and streaming don’t work. This is how you can fix Spotify error code 4 on a Windows 10 or 11 PC.

## 1\. Run the Flush DNS Command

![The flushdns command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/flushdns-command.jpg)

 One confirmed solution for error code 4 is to flush the DNS cache. The DNS (Domain Name System) cache is a local storage repository of IP addresses on your PC. Your web browser retrieves DNS lookup data from that cache.

 Clearing the DNS cache will flush out and refresh its data. You can clear the DNS cache by running a flush DNS command in Command Prompt or Run. Check out our guide about[how to flush the DNS](https://www.makeuseof.com/flush-dns-cache-windows-11/) on Windows for further details about how to apply this solution.

## 2\. Select the HTTP Option in Spotify

 Spotify includes alternative proxy settings you can select to configure how that app connects with the Internet. Changing the proxy option to**HTTP** can reputedly resolve error code 4\. You can select the**HTTP** option in Spotify as follows:

1. Open your Spotify app.
2. Click the username button at the top of Spotify to view its menu.
3. Select**Settings** to view Spotify’s options.  
![The Settings menu option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-settings-option.jpg)
4. Click the**Proxy type** drop-down menu to select**HTTP** .  
![The HTTP option in Spotify](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/http-option.jpg)
5. Then select**Restart App** to apply.

## 3\. Change DNS Server Settings

 Error code 4 often occurs because Spotify can’t recognize your PC’s default DNS server set by your ISP. In such a scenario, the app can’t load required online resources correctly, resulting in error 4\. Many users have addressed that issue by changing their PCs’ DNS server to the universally recognized Google DNS.

 Our guide to[changing the DNS server in Windows](https://www.makeuseof.com/windows-11-alternate-ways-change-dns-server-settings/) post includes step-by-step guidelines for how to apply this solution via the Control Panel and Settings among other methods. You’ll need to set the preferred and alternative DNS server settings to Google addresses. Input**8.8.8.8** for the preferred DNS server and**8.8.4.4** for the alternative DNS setting.

![DNS server settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/dns-server-settings.jpg)

## 4\. Tweak the Registry

 Some Spotify users have confirmed tweaking a DWORD value in the registry resolved error 4 for them. Those users changed the EnableActiveProbing DWORD’s value, which was set to 0 (disabled) on their PCs. These are the steps for fixing error code 4 by editing the registry:

1. Press the search box’s**Win + S** hotkey.
2. To locate the Registry Editor, enter**regedit** inside the**Type here to search** box.
3. Select Registry Editor inside the search tool.
4. Next, click within the address bar at the top of Registry Editor to clear the current location in it.
5. Go to the Internet key by inputting the following path:  
`Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\NlaSvc\Parameters\Internet`
6. Then right-click the**EnableActiveProbing** DWORD and select**Modify** .  
![The Modify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/modify-option.jpg)
7. If**EnableActiveProbing** is set to**0** , clear the**Value data** box. Then input**1** inside that data box.  
![The Edit DWORD window for the EnableActiveProbing DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/edit-dword-window.jpg)
8. Select**OK** to save the new**EnableActiveProbing** value.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
## 5\. Exclude Spotify From Your Antivirus Software

 You might need to fix error code 4 because of antivirus software interference with the Spotify app. Both third-party antivirus apps and Windows Security can feasibly block Spotify’s internet connectivity. You can select to exclude Spotify from antivirus protection by adding it to an exception (trusted software) list most security apps include.

![Windows Security's app exclusion settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-security-s-exclusion-list-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
 Our article about[setting Windows Security exclusions](https://www.makeuseof.com/windows-11-security-exclusions/) includes instructions for adding software to that app’s exception list. If you’re utilizing a third-party antivirus tool, look for an exclusion list within its settings tab. The antivirus software’s website will also likely include guidelines for how to use its exclusion list.

## 6\. Turn Off the Windows Defender Firewall

 Windows Defender Firewall is a component of Windows Security for filtering network traffic. Turning that firewall off could resolve error 4 if Spotify isn’t allowed through it. You can turn off WDF as outlined in our guide to[disabling the Windows Defender firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) .

![The turn off firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-firewall-s-allow-app-settings.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
 Should this solution work, it’s not a good idea to keep the firewall disabled. Open Windows Defender Firewall’s allowed app list and select the Spotify checkboxes there to permit that app through it. Check out our how to guide about[allowing apps through the Windows firewall](https://www.makeuseof.com/how-to-allow-apps-windows-firewall/) for further details.

![The firewall's allowed apps settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/allowed-app-settings.jpg)

 Of course, numerous standalone third-party firewalls can block Spotify much the same. If you have installed a third-party firewall, try disabling it to see if that resolves error 4\. Then add Spotify to its allowed apps and turn the firewall back on if it does.

## 7\. Reinstall Spotify

 Reinstalling Spotify could resolve unknown reasons for error code 4 arising and will at least ensure you’re using the latest app version. However, note that reinstalling the app will wipe your Spotify playlists. Back up (export) any playlists you wish to keep so you can restore them. Then reinstall Spotify with the following steps:

1. Press the Start menu button and select**All apps** (in Windows 11).
2. Scroll down to the Spotify app on the Start menu.
3. Right-click Spotify and select**Uninstall** .  
![Spotify's Uninstall option on the Start menu](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-start-menu-s-uninstall-option.jpg)
4. If you’ve installed the desktop Spotify app, Programs and Features will open from which you can select the software and click**Uninstall** . Users who’ve installed the UWP Spotify app can select**Uninstall** on a confirmation prompt.
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Then open the[Spotify Windows](https://www.spotify.com/us/download/windows/) download page.
6. Click**Download** to get the installer for the desktop Spotify app.  
![The Download Spotify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/download-option.jpg)
7. Open the Explorer file manager along with the folder in which Spotify downloaded.
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
8. Double-click the**SpotifySetup.exe** file to bring up the setup wizard and install Spotify.

 Another option is to install the Spotify UWP (Universal Windows Platform) app on Microsoft Store. Click the**Get it From Microsoft Store** button on the linked Spotify download page to bring up that app’s MS store page. Then click the**Get in Store app** \>**Open Microsoft Store** options and select**Get** to install the UWP app.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/748964/4704" target="_top" id="748964"><img src="//a.impactradius-go.com/display-ad/4704-748964" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/748964/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Enjoy Spotify Music Online Again

 There’s a very good chance at least one Windows troubleshooting method in this guide will resolve Spotify error code 4 on your PC. They’re user-confirmed fixes that address the most common reasons for error 4 arising. With that app connection issue sorted, you can then enjoy all the best online music and radio Spotify has to offer again.

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
<li><a href="https://youtube-sure.techidaily.com/024-approved-premier-popularity-prognosticator-for-video-charts/"><u>[New] 2024 Approved  Premier Popularity Prognosticator for Video Charts</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-no-price-just-perfect-screen-recordings-on-android-for-2024/"><u>[New] No Price, Just Perfect Screen Recordings on Android for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-unleashing-the-power-of-hashtags-for-instagram-success/"><u>[Updated] 2024 Approved  Unleashing the Power of Hashtags for Instagram Success</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-androids-screen-shutter-select-the-best-eight-free-tools-for-2024/"><u>[Updated] Android's Screen Shutter - Select the Best Eight Free Tools for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/cant-install-lumafusion-on-mac-try-these-best-alternative-apps-for-2024/"><u>Cant Install Lumafusion on Mac? Try These Best Alternative Apps for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-audacitys-error-9999-on-win1011-systems/"><u>Decoding Audacity's Error 9999 on WIN10/11 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-windows-11s-undisclosed-interface-features/"><u>Decoding Windows 11'S Undisclosed Interface Features</u></a></li>
<li><a href="https://win11.techidaily.com/ensure-your-hardware-meets-new-windows-requirements/"><u>Ensure Your Hardware Meets New Windows Requirements</u></a></li>
<li><a href="https://win11.techidaily.com/essential-steps-for-exploring-and-expunging-windows-history/"><u>Essential Steps for Exploring and Expunging Windows History</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-noisy-recording-in-powerpoint-screen-casts-on-pc/"><u>Fixing Noisy Recording in PowerPoint Screen Casts on PC</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-windows-discord-overlay-failure-a-step-by-step-guide/"><u>Fixing Windows Discord Overlay Failure: A Step-by-Step Guide</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-vivo-y100t-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Vivo Y100t online without jailbreak</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-a-perfect-guide-to-remove-or-disable-google-smart-lock-on-realme-10t-5g-by-drfone-android/"><u>In 2024, A Perfect Guide To Remove or Disable Google Smart Lock On Realme 10T 5G</u></a></li>
<li><a href="https://win11.techidaily.com/intuitive-shorthand-for-power-buttons-on-modern-windows-11/"><u>Intuitive Shorthand for Power Buttons on Modern Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-resolution-of-win1110-store-issue-0x80072efd/"><u>Mastering the Resolution of Win11/10 Store Issue 0X80072EFD</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-ssd-capabilities-integrate-windows-and-fresh-optimization/"><u>Maximize SSD Capabilities: Integrate Windows & Fresh Optimization</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-your-valorant-download-speed-with-ease/"><u>Maximize Your Valorant Download Speed with Ease</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-the-graphic-problem-in-overwatch/"><u>Overcoming the Graphic Problem in Overwatch</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/pc-video-editing-made-easy-gopro-quik-and-similar-tools/"><u>PC Video Editing Made Easy GoPro Quik and Similar Tools</u></a></li>
<li><a href="https://win11.techidaily.com/pivotal-factors-to-keep-in-mind-for-reinstalling-windows/"><u>Pivotal Factors to Keep in Mind for Reinstalling Windows</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-errors-validating-windows-11-temporary-folder/"><u>Preventing Errors: Validating Windows 11 Temporary Folder</u></a></li>
<li><a href="https://win11.techidaily.com/propelling-linux-with-powerful-windows-integration/"><u>Propelling Linux with Powerful Windows Integration</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-faulty-input-devices-on-a-windows-system/"><u>Resolving Faulty Input Devices on a Windows System</u></a></li>
<li><a href="https://win11.techidaily.com/shut-off-windows-11-notifications-swiftly/"><u>Shut Off Windows 11 Notifications Swiftly</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-fixing-diagnostics-error-on-pc/"><u>Solutions for Fixing 'Diagnostics Error' On PC</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-journey-through-original-diablo/"><u>Step-by-Step Journey Through Original Diablo</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-entry-to-your-fileshare-onedrive-troubleshooting-guide/"><u>Streamline Entry to Your Fileshare: OneDrive Troubleshooting Guide</u></a></li>
<li><a href="https://win11.techidaily.com/the-essence-of-alias-names-for-application-launches/"><u>The Essence of Alias Names for Application Launches</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-a-408-request-timed-out-issue-for-smoother-web-experience/"><u>Troubleshooting a 408 Request Timed Out Issue for Smoother Web Experience</u></a></li>
<li><a href="https://win11.techidaily.com/uncover-windows-11-wallpaper-location-secret/"><u>Uncover Windows 11 Wallpaper Location Secret</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-full-capability-of-windows-11s-problem-solvers/"><u>Unlocking Full Capability of Windows 11'S Problem Solvers</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-powershell-tactics-to-reverse-error-message-about-disabled-scripts/"><u>Unlocking PowerShell: Tactics to Reverse Error Message About Disabled Scripts</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/untangling-blue-screen-issues-a-guide-to-overcoming-windows-10s-machine-check-exception-errors/"><u>Untangling Blue Screen Issues: A Guide to Overcoming Windows 10'S Machine Check Exception Errors</u></a></li>
<li><a href="https://buynow-help.techidaily.com/unveiling-the-potential-in-depth-look-at-ampages-new-andes-1500-power-unit/"><u>Unveiling the Potential: In-Depth Look at Ampage's New Andes 1500 Power Unit</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-secrets-to-theme-and-font-control-in-windows-11-notepad/"><u>Unveiling the Secrets to Theme and Font Control in Windows 11 Notepad</u></a></li>
<li><a href="https://win11.techidaily.com/why-and-how-to-ditch-integrated-video-on-windows/"><u>Why and How to Ditch Integrated Video on Windows</u></a></li>
</ul></div>
