---
title: Regaining Razer Devices Detection via Synapse
date: 2024-09-14T00:51:26.233Z
updated: 2024-09-16T17:45:44.946Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Regaining Razer Devices Detection via Synapse
excerpt: This Article Describes Regaining Razer Devices Detection via Synapse
keywords: Razer Synapse Recovery,Razer Device Tracking,Synapse Device Detection,Restore Razer Connection,Detect Razers Quickly,Re-Link Razer Devices,Synapse Device Regain
thumbnail: https://thmb.techidaily.com/740b68b56d6bbac7152f3eef9f605d6bffa61f7111e01d3d9d9931aeb1f4b3a1.jpg
---

## Regaining Razer Devices Detection via Synapse

 Razer Synapse is the official software for configuring Razer devices, such as keyboards and mice. However, Synapse sometimes doesn’t detect connected Razer devices. Consequently, users can’t configure their devices because they don’t show up in the Synapse software.

 The issue of Synapse not detecting devices is mostly reported for Razer mice and keyboards. However, that issue can also occur for Razer headphones, broadcast microphones, and other accessories that software will usually detect. This is how you can fix the Synapse software not detecting Razer devices within Windows 10 and 11.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## But First, Double-Check Device Compatibility With Razer Synapse

 First, before you hop into the troubleshooting steps, note that Synapse will not detect non-Razer devices. There are even some Razer products Synapse 3.0 and 2.0 don’t support. It might be the case Synapse isn’t detecting your hardware because it doesn’t support it. So, double-check your Razer Synapse software supports the device it’s not detecting.

 You can check supported hardware at the[Razer Synapse 3 supported device page](https://mysupport.razer.com/app/answers/detail/a%5Fid/4130/~/razer-synapse-3-supported-devices) . Click a category on that page to see if your device is listed there. You can also check compatibility for version 2.0 at the[Razer Synapse 2.0](https://mysupport.razer.com/app/answers/detail/a%5Fid/4131/~/razer-synapse-2.0-supported-devices) supported device page. If your device is listed among the supported hardware on one of those pages, your Synapse software should detect it.

## 1\. Run the Hardware and Devices Troubleshooter

 Windows has a Hardware and Devices troubleshooter that could identify and even resolve issues with the Razer device Synapse isn’t detecting. However, that troubleshooter isn’t visible within Settings. Nevertheless, you can run the Hardware and Devices troubleshooter from Command Prompt like this:

1. Make sure your Razer device is connected to your PC.
2. Click a**Type here to search** (magnifying glass) button or box on your Windows 11/10 taskbar.
3. To find Command Prompt, input the phrase**cmd** in the**Type here to search** box.
4. Select the Command Prompt app in the Windows search tool.
5. Execute this Hardware and Devices troubleshooter command:  
`msdt.exe -id DeviceDiagnostic`  
![The Hardware and Devices troubleshooter command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hardware-troubleshooter-command.jpg)
6. Click**Next** in the Hardware and Devices troubleshooter.  
![The Hardware and Devices troubleshooter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/the-hardware-and-devices-troubleshooter.jpg)
7. Select**Apply this fix** for resolutions the troubleshooter suggests.

## 2\. Plug the Razer Device into an Alternative USB Port

 This issue can occur because of USB port connection issues. Some users have revealed that plugging Razer devices into different USB ports on their PCs resolved the issue of synapse not detecting them. So, try unplugging your Razer device and plugging it into an alternative USB port. Also, plug the device directly into your PC without using any intermediary USB hubs.

 It’s also recommended to select a**Remove device** option in Settings before plugging your device into another port. To do that, press the**Windows** logo +**I** key, select**Bluetooth and devices** , and click**View more** **devices** . Then click the three-dot button for your Razer hardware and select**Remove device** . In Windows 10’s Settings app, you can select a Razer peripheral on the**Bluetooth & other devices** tab and press**Remove device** .

![The Remove device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/remove-device-option.jpg)

## 3\. Select Synapse’s Repair Option

 A lot of users have also said they’ve been able to fix Synapse not detecting devices by selecting a**Repair** option for that software. Synapse has a**Repair** option you can select on a Razer Gaming Software window. This is how you can select that option in Windows 11/10:

1. Bring up the Windows uninstaller utility in the Control Panel with a method in our guide for[opening Programs and Features on Windows](https://www.makeuseof.com/windows-open-programs-and-features-tool/) .
2. Then select Razer Synapse in Programs and Features.
3. Click the**Change** button for Razer Synapse.  
![The Change button for Synapse](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/change-button.jpg)
4. Select the**Repair** option in the window that opens.  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2135474/26400" target="_top" id="2135474">
  <img src="//a.impactradius-go.com/display-ad/26400-2135474" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2135474/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![The Repair button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-button.jpg)
5. Sign back into Razer Synapse after selecting**Repair** .
6. Then select**Restart** in Windows 11/10 before launching Synapse.

## 4\. Reinstall Razer Synapse

 Corrupted or missing Synapse modules can cause the issue of Synapse not detecting Razer devices. So, thoroughly uninstalling Synapse by erasing leftover data and reinstalling the software will often resolve that issue. Reinstall Razer Synapse as follows:

1. Open the Programs and Features applet.
2. Click Razer Synapse to select that software.
3. Select**Uninstall** in Programs and Features to open a Razer Gaming Software window.
4. Then click the**Uninstall** option in the window to remove Synapse.
5. Uninstall Cortex and any other associated Razer sub-programs.
6. Press the**Windows** logo key +**R** to access a Run command box.
7. Input this folder directory in Run and click**OK** :  
`C:\Program Files (x86)\Razer`  
![The Program Files > Razer folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/razer-directory.jpg)
8. Press**Ctrl** +**A** to select any remaining files in the Razer folder.

<!-- affiliate ads begin -->
<span id="1265663">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1265663.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/4482-1265663">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1265663.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmartinic.evyy.net%2Fc%2F5597632%2F1265663%2F4482'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1265663/4482" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Press the**Del** key to erase the selected files.

 Next, input this Razer directories path in Explorer’s address bar and hit**Enter** :

`C:\ProgramData\Razer`

![The ProgramData > Razer folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/razer-subfolder.jpg)

 Repeat steps eight and nine to delete all files in the Razer directories folder. Once done, restart your PC.

1. Click**Download Now** on the[Razer Synapse](https://razer.a9yw.net/c/119570/642901/10229?subId1=UUmuoUeUpU2022703&subId2=emuo&u=https%3A%2F%2Fwww.razer.com%2Fgb-en%2Fsynapse-3) page.
2. Double-click the downloaded**RazerSynapseInstaller\_V1.12.0.385.exe** file to open the setup wizard.  
![The Razer software installer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/razer-installer.jpg)
3. Select the**Synapse** checkbox along with other Razer software to reinstall, and click the**Install** option.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134223/18498" target="_top" id="2134223">
  <img src="//a.impactradius-go.com/display-ad/18498-2134223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134223/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Reinstall Mouse and Keyboard Device Drivers

 Another fix confirmed to work for this Synapse issue is to reinstall all Razer and HID-compliant mouse and keyboard devices. Applying that potential resolution can resolve device driver conflicts. You can reinstall HID mouse and keyboard drivers as follows:

1. Press the**Win +** **X** keyboard shortcut that brings up a Power User menu.
2. Click**Device Manager** to view that tool’s window.
3. Double-click**Mice and other pointing devices** to view peripherals for that category.
4. Right-click a Razer mouse and select**Uninstall device** \>**Uninstall** .  
![The Uninstall device option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/uninstall-device-option.jpg)
5. Repeat the previous step for all HID mice devices listed.

6. Then double-click the**Keyboards** category.  
![The Keyboards device category](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/keyboards-category.jpg)
7. Uninstall all Razer and HID keyboard devices listed there as outlined in step four.
8. Reboot the Windows PC for the automatic reinstallation of device drivers. You can also select**Action** and**Scan for hardware changes** in Device Manager to reinstall uninstalled peripherals.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115914/19272" target="_top" id="2115914">
  <img src="//a.impactradius-go.com/display-ad/19272-2115914" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115914/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 6\. Disable Antivirus Utilities

 Temporarily antivirus apps on your PC to ensure they aren’t blocking Synapse in any way. You can disable Windows Security’s real-time protection as outlined in our guide for[disabling Microsoft Defender](https://www.makeuseof.com/how-to-turn-off-microsoft-defender-windows-11/) . If there’s a third-party antivirus tool on your PC, turn off its shield via its system tray icon’s context menu.

![Real-time protection option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/real-time-protection-option2.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118318/7443" target="_top" id="2118318">
  <img src="//a.impactradius-go.com/display-ad/7443-2118318" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118318/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Launch Razer Synapse to see if it detects your devices after disabling antivirus software on your PC. If this potential resolution works, consider adding Razer Synapse to the[exclusion list in Windows Security](https://www.makeuseof.com/windows-11-security-exclusions/) or alternative security software. Then turn your antivirus protection back on.

## Configure Your Razer Devices in Synapse Again on Windows

 Those potential solutions will most likely resolve Synapse not detecting connected devices. Then you can reconfigure your Razer mouse, keyboard, or any other supported hardware with that software. However, any users who still need more troubleshooting guidance for this issue can submit a ticket to Razer’s support service by clicking the**Contact Support** button on this[Synapse 3 page](https://mysupport.razer.com/app/answers/detail/a%5Fid/3783/~/razer-synapse-3-support) .

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
<li><a href="https://extra-skills.techidaily.com/updated-ranked-best-voice-change-software-echo-magic-edition/"><u>[Updated] Ranked Best Voice Change Software Echo Magic Edition</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-splitting-content-introducing-chapters-in-vimeo/"><u>2024 Approved Splitting Content Introducing Chapters in Vimeo</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-poco-c65withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Poco C65with/without a PC</u></a></li>
<li><a href="https://win11.techidaily.com/integrating-reminders-seamlessly-in-windows-os/"><u>Integrating Reminders Seamlessly in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/master-plan-to-navigate-through-onedrive-error-messages/"><u>Master Plan to Navigate Through OneDrive Error Messages</u></a></li>
<li><a href="https://win-answers.techidaily.com/mastering-cs2-playability-how-to-combat-fps-dips-and-stutter-for-a-fluid-experience/"><u>Mastering CS2 Playability: How to Combat FPS Dips and Stutter for a Fluid Experience</u></a></li>
<li><a href="https://win11.techidaily.com/quick-guide-eradicating-windows-mail-problem-0x80072746/"><u>Quick Guide: Eradicating Windows Mail Problem 0X80072746</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-10-samsung-galaxy-a15-5g-android-sim-unlock-apk-by-drfone-android/"><u>Top 10 Samsung Galaxy A15 5G Android SIM Unlock APK</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-steps-resolving-windows-11s-0x80072efd-error/"><u>Troubleshooting Steps: Resolving Windows 11'S 0X80072EFD Error</u></a></li>
<li><a href="https://techidaily.com/v30t-support-forgotten-screen-lock-by-drfone-android-unlock-android-unlock/"><u>V30T support - Forgotten screen lock.</u></a></li>
</ul></div>

