---
title: Overcoming the Code 4 Spotify Error on W10/W11 Systems
date: 2024-06-25T11:44:41.491Z
updated: 2024-06-26T11:44:41.491Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming the Code 4 Spotify Error on W10/W11 Systems
excerpt: This Article Describes Overcoming the Code 4 Spotify Error on W10/W11 Systems
keywords: Fix Spotify Code 4 on Windows,Spotify Error Resolution Windows,Overcoming Spotify Errors W10/W11,Stop Spotify Connection Failure WinOS,Troubleshoot Spotify Code 4 Windows,Eliminate Spotify Connect Issue W10/W11,Remedy Spotify Error on Windows PCs
thumbnail: https://thmb.techidaily.com/e1e53d68e6a8bd97bb49ce774576b58cc661b7caf15fc6fdb1157408db40b882.jpg
---

## Overcoming the Code 4 Spotify Error on W10/W11 Systems

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

## 5\. Exclude Spotify From Your Antivirus Software

 You might need to fix error code 4 because of antivirus software interference with the Spotify app. Both third-party antivirus apps and Windows Security can feasibly block Spotify’s internet connectivity. You can select to exclude Spotify from antivirus protection by adding it to an exception (trusted software) list most security apps include.

![Windows Security's app exclusion settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/windows-security-s-exclusion-list-settings.jpg)

 Our article about[setting Windows Security exclusions](https://www.makeuseof.com/windows-11-security-exclusions/) includes instructions for adding software to that app’s exception list. If you’re utilizing a third-party antivirus tool, look for an exclusion list within its settings tab. The antivirus software’s website will also likely include guidelines for how to use its exclusion list.

## 6\. Turn Off the Windows Defender Firewall

 Windows Defender Firewall is a component of Windows Security for filtering network traffic. Turning that firewall off could resolve error 4 if Spotify isn’t allowed through it. You can turn off WDF as outlined in our guide to[disabling the Windows Defender firewall](https://www.makeuseof.com/windows-11-disable-microsoft-defender-firewall/) .

![The turn off firewall settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/the-firewall-s-allow-app-settings.jpg)

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
5. Then open the[Spotify Windows](https://www.spotify.com/us/download/windows/) download page.
6. Click**Download** to get the installer for the desktop Spotify app.  
![The Download Spotify option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/download-option.jpg)
7. Open the Explorer file manager along with the folder in which Spotify downloaded.
8. Double-click the**SpotifySetup.exe** file to bring up the setup wizard and install Spotify.

 Another option is to install the Spotify UWP (Universal Windows Platform) app on Microsoft Store. Click the**Get it From Microsoft Store** button on the linked Spotify download page to bring up that app’s MS store page. Then click the**Get in Store app** \>**Open Microsoft Store** options and select**Get** to install the UWP app.

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
<li><a href="https://win11.techidaily.com/overcoming-the-absence-of-battery-life-duration-in-pcs-running-win-11/"><u>Overcoming the Absence of Battery Life Duration in PCs Running Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/maximizing-space-windows-11s-disk-defragmentation-guide/"><u>Maximizing Space: Windows 11'S Disk Defragmentation Guide</u></a></li>
<li><a href="https://win11.techidaily.com/digital-retrofit-modernizing-windows-11-with-a-98-twist/"><u>Digital Retrofit: Modernizing Windows 11 with a '98 Twist</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensively-unveiling-windows-11s-narrator-commands/"><u>Comprehensively Unveiling Windows 11'S Narrator Commands</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-obstacles-hindering-discord-setup-success/"><u>Eliminating Obstacles Hindering Discord Setup Success</u></a></li>
<li><a href="https://win11.techidaily.com/insight-into-windows-11s-new-automated-data-safeguarding/"><u>Insight Into Windows 11’S New Automated Data Safeguarding</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-error-code-a00f425d-on-windows-11-camera-app/"><u>Resolving Error Code A00F425D on Windows 11 Camera App</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-making-your-mark-with-video-content-in-captivate/"><u>[New] Making Your Mark with Video Content in Captivate</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-pause-life360-location-sharing-for-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>In 2024, How To Pause Life360 Location Sharing For Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-fast-setup-moving-media-from-pc-to-your-iphone/"><u>2024 Approved  Fast Setup  Moving Media From PC To Your iPhone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/in-2024-audio-harmony-in-editing-perfecting-the-dance-between-music-and-visuals-in-final-cut-pro-x/"><u>In 2024, Audio Harmony in Editing Perfecting the Dance Between Music and Visuals in Final Cut Pro X</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-apple-vs-android-the-face-id-and-galaxy-recognition-race/"><u>[New] Apple Vs. Android  The Face ID and Galaxy Recognition Race</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-and-where-to-find-a-shiny-stone-pokemon-for-nokia-c12-drfone-by-drfone-virtual-android/"><u>In 2024, How and Where to Find a Shiny Stone Pokémon For Nokia C12? | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unbox-and-discover-samsungs-ue590-4k-freesync-marvel-for-2024/"><u>Unbox and Discover  Samsung's UE590 4K, FreeSync Marvel for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-iphone-se-2022-data-from-ios-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover iPhone SE (2022) Data From iOS iCloud | Dr.fone</u></a></li>
</ul></div>
