---
title: How to Prevent Desktop Input via Wired Connection on PC
date: 2024-09-05T08:31:30.458Z
updated: 2024-09-06T08:31:30.458Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Prevent Desktop Input via Wired Connection on PC
excerpt: This Article Describes How to Prevent Desktop Input via Wired Connection on PC
keywords: Prevent Desktop Keyboard Input,Block USB Ports,Stop External Device Use,Secure PC From Hacking,Disable KVM Switch,Eliminate Remote Access,Shield Against Port Scanning
thumbnail: https://thmb.techidaily.com/27ed488072176012a10baf6e8c8b898cb859756da493550354750054c99fba0b.jpg
---

## How to Prevent Desktop Input via Wired Connection on PC

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

## How to Find Your Laptop Keyboard in Device Manager

 Whether you want to disable your laptop keyboard temporarily or permanently, you will need to uninstall the input device from Device Manager.

 For this, you’ll need to identify the integrated keyboard in Device Manager. Since Device Manager will list all the recognized keyboards, including external keyboards, here’s how you can identify your laptop keyboard from the list.

 To identify the built-in keyboard in Device Manager:

1. Press **Win + R** to open **Run**.
2. Type **devmgmt.msc** and click **OK** to open Device Manager.
3. In Device Manager, expand the **Keyboards** section.  
![device manager keyboards 1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/device-manager-keyboards-1.jpg)
4. Right-click on the first keyboard entry **(HID/Standard)** and select **Properties**.
5. In the **General** tab, check the **Location** section. If it says **Location 1** or **Plugged into keyboard port**, it is likely your laptop’s internal keyboard.
6. Bluetooth and USB keyboards will show **On Bluetooth Low Energy** and **On US Input Device**, respectively as its location.

 If you don't find your keyboard listed, make sure you have [set Device Manager to show hidden devices.](https://www.makeuseof.com/view-hidden-devices-in-windows/)

## How to Disable the Laptop Keyboard Temporarily

 To disable your laptop’s keyboard temporarily:

1. Right-click on all the **HID** and **PS/2 Keyboard** entries with the **Properties Location** set to **Location 1** or **Plugged into keyboard.**  
![uninstall keyboard device device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/uninstall-keyboard-device-device-manager.jpg)
2. Next, select **Uninstall Device** from the context menu.
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134243/18498" target="_top" id="2134243">
  <img src="//a.impactradius-go.com/display-ad/18498-2134243" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134243/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Click **Yes** to confirm the action.
4. That’s it. You have disabled your laptop’s internal keyboard successfully.

 That said, this is a temporary solution. As soon as you restart your system, Windows will look for the connected but unrecognized devices and install the necessary drivers to make them functional.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137206/26400" target="_top" id="2137206">
  <img src="//a.impactradius-go.com/display-ad/26400-2137206" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137206/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How to Disable Your Laptop Keyboard Permanently

![disable ps 2 port 18042prt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/disable-ps-2-port-18042prt-command-prompt.jpg)

<!-- affiliate ads begin -->
<span id="1983473">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983473.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983473">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983473.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983473%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983473/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you want to disable your laptop keyboard permanently, you can disable your laptop’s built-in keyboard driver PS/2 i8042prt service using the Command Prompt. We'll use the sc command-line utility to configure the service and set its start parameter to disabled.

 To disable the laptop keyboard permanently:

1. Press the **Win key** and type **cmd** in the Windows search bar.
2. Right-click on **Command Prompt** and select **Run as Administrator**. Click **Yes** when the UAC prompt appears.
3. In the Command Prompt window, type the following command and press Enter:  
`sc config i8042prt start= disabled`
4. When the success message appears, close the Command Prompt, and restart your PC. After the restart, your laptop keyboard will stop registering any inputs.

 Note that, for this to work, you will need to uninstall your keyboard from Device Manager as shown above and restart your PC.

 If you change your mind and want to re-enable the keyboard, you can use the following command in an [elevated Command Prompt](https://www.makeuseof.com/windows-11-open-command-prompt/).

`sc config i8042prt start= auto`

 Once you see the success message, restart your PC to apply the changes.

## Disable the Built-in Keyboard Using an Incompatible Driver

 Another quirky solution to disable a built-in keyboard is to install an incompatible driver for the input device. Here's how to do it.

1. Open Device Manager and expand the **Keyboard** section.
2. Right-click on your laptop keyboard device and select **Update driver**.  
![Update the Relevant Keyboard Driver in Windows Device Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/5-update-the-relevant-keyboard-driver-in-windows-device-manager.jpg)
3. Select **Browse my computer for drivers**.  
<!-- affiliate ads begin -->
<span id="1155462">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1155462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1155462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1155462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1155462%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1155462/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)
4. Next, select **Let me pick from a list of available drivers on my computer**.  
![update driver keyboard pick from list of available drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-keyboard-pick-from-list-of-available-drivers-device-manager.jpg)
5. Uncheck the **Show compatible hardware** option.
6. Select a random manufacturer under the **Manufacturer** column.  
![install incompatible keyboard driver windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-incompatible-keyboard-driver0windows.jpg)
7. Click **Next**. Click **Yes** if an **Update Driver Warning** dialog appears.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130533/26400" target="_top" id="2130533">
  <img src="//a.impactradius-go.com/display-ad/26400-2130533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130533/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Once installed, close Device Manager and reboot your computer.

 After the restart, your laptop keyboard will stop working. If you need to install the correct driver again to enable the keyboard, right-click on the keyboard device and select **Update driver**. Next, select **Search automatically for drivers**. Windows will look for a compatible driver and install it.

![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123740/7443" target="_top" id="2123740">
  <img src="//a.impactradius-go.com/display-ad/7443-2123740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Alternatively, select **Browse my computer for drivers** in the Update Drivers dialogue. Next, select **Let me pick from a list of available drivers on my computer**. Make sure the **Show compatible hardware** option is enabled. Select an **HID Keyboard Device** driver from the list and click **Next**.

![install compatible hardware driver keyboard device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-compatible-hardware-driver-keyboard-device-manager.jpg)

 Wait for the driver to install. Once done, reboot your computer, and the keyboard will start working again.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134489/18498" target="_top" id="2134489">
  <img src="//a.impactradius-go.com/display-ad/18498-2134489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134489/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Disable Your Laptop Keyboard Permanently on Windows

 The built-in chiclet keyboard on your laptop is the primary input method available, so there is no way to disable it with a single click. Also, you wouldn’t want to disable your keyboard accidentally. If you determine your keyboard to have gone rogue and typing on its own, you can permanently disable it using the Command Prompt and Device Manager.

 That said, apart from the hardware issues, your laptop keyboard can act up for many other reasons. To fix your keyboard, check for pending driver updates, use the built-in troubleshooter, or simply disable the individual keys.

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-platform-precision-examining-obs-against-twitch-hub/"><u>[New] 2024 Approved  Platform Precision  Examining OBS Against Twitch Hub</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-premier-mac-studio-for-high-quality-recordings/"><u>[New] Premier Mac Studio for High-Quality Recordings</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ut-a-halt-on-surprise-youtube-videos/"><u>[New] Put a Halt on Surprise YouTube Videos</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-experts-choice-best-6-video-grabber-tools-for-mac/"><u>[Updated] Expert's Choice  Best 6 Video Grabber Tools for Mac</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-enhance-your-vlogs-pacing-using-jump-cuts/"><u>[Updated] In 2024, How to Enhance Your Vlog's Pacing Using Jump Cuts</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-epic-zombie-battles-our-favorites-revealed/"><u>2024 Approved  Epic Zombie Battles  Our Favorites Revealed</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-master-commanders-unleashed-ranking-7-total-war-champions/"><u>2024 Approved  Master Commanders Unleashed  Ranking 7 Total War Champions</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-realme-narzo-n53-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>Can I recover permanently deleted photos from Realme Narzo N53</u></a></li>
<li><a href="https://win11.techidaily.com/cure-voice-command-issues-reactivation-techniques-for-win11/"><u>Cure Voice Command Issues: Reactivation Techniques for Win11</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-the-path-to-exceptional-windows-wallpapers/"><u>Decoding the Path to Exceptional Windows Wallpapers</u></a></li>
<li><a href="https://win11.techidaily.com/fast-focus-furious-fighting-efficient-gameplay-fixes-for-bf2/"><u>Fast Focus, Furious Fighting: Efficient Gameplay Fixes for BF2</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tune-your-windows-sleep-timer/"><u>Fine-Tune Your Window's Sleep Timer</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-external-monitor-not-detected-issue-in-windows/"><u>Fixing External Monitor Not Detected Issue in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-inactive-notifications-from-phone-link-app-in-windows-environment/"><u>Fixing Inactive Notifications From Phone Link App in Windows Environment</u></a></li>
<li><a href="https://win11.techidaily.com/future-on-display-the-premium-laptops-at-ifa-2023/"><u>Future on Display: The Premium Laptops at IFA 2023</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-fixing-roblox-error-code-403-on-pc/"><u>Guide to Fixing Roblox Error Code 403 on PC</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-itel-a60-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Itel A60 Phones with/without a PC</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-track-imei-number-of-realme-gt-neo-5-se-through-google-earth-by-drfone-android/"><u>How To Track IMEI Number Of Realme GT Neo 5 SE Through Google Earth?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/ideal-action-cameras-for-stabilized-shots-for-2024/"><u>Ideal Action Cameras for Stabilized Shots for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-a-comprehensive-guide-to-icloud-unlock-on-apple-iphone-14-plus-online-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to iCloud Unlock On Apple iPhone 14 Plus Online</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-lava-blaze-2-pro-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Lava Blaze 2 Pro via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-fade-techniques-to-pare-down-audio-intensity-in-logic-pro/"><u>In 2024, Fade Techniques to Pare Down Audio Intensity in Logic Pro</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-access-your-apple-iphone-12-pro-max-when-you-forget-the-passcode-drfone-by-drfone-ios/"><u>In 2024, How to Access Your Apple iPhone 12 Pro Max When You Forget the Passcode? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-or-minimize-windows-11-taskbar/"><u>Maximize or Minimize Windows 11 Taskbar</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-top-text-animation-tools/"><u>New 2024 Approved Top Text Animation Tools</u></a></li>
<li><a href="https://win11.techidaily.com/notetaking-without-installation-in-windows-11/"><u>Notetaking Without Installation in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/old-meets-new-again-seven-core-windows-characteristics-evolving/"><u>Old Meets New Again: Seven Core Windows Characteristics Evolving</u></a></li>
<li><a href="https://win11.techidaily.com/reconnect-and-stay-connected-eight-ways-to-enhance-win11-point/"><u>Reconnect and Stay Connected: Eight Ways to Enhance Win11' Point</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-alerts-on-desktop-applets/"><u>Restoring Alerts on Desktop Applets</u></a></li>
<li><a href="https://tech-hub.techidaily.com/risks-of-relying-on-chatgpt-for-essential-text-summaries/"><u>Risks of Relying on ChatGPT for Essential Text Summaries</u></a></li>
<li><a href="https://win11.techidaily.com/sidestep-installation-blockers-for-effective-win-11-uninstalls/"><u>Sidestep Installation Blockers for Effective Win 11 Uninstalls</u></a></li>
<li><a href="https://win11.techidaily.com/solving-frustrating-asana-issues-with-a-step-by-step-guide/"><u>Solving Frustrating Asana Issues with a Step-by-Step Guide</u></a></li>
<li><a href="https://data-wizards.techidaily.com/stellar-becomes-the-first-data-recovery-company-to-recover/"><u>Stellar Becomes The First Data Recovery Company To Recover</u></a></li>
<li><a href="https://win11.techidaily.com/stop-chromes-spontaneous-tab-triggers-on-windows-desktop/"><u>Stop Chrome's Spontaneous Tab Triggers on Windows Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-decrease-cpu-strain-from-tiworkerexe-processes/"><u>Strategies to Decrease CPU Strain From TiWorker.exe Processes</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-reactivating-lost-pin-access-in-windows-11/"><u>Troubleshooting: Reactivating Lost Pin Access in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unleash-the-power-of-efficient-directory-creation-with-newest-windows-oses/"><u>Unleash the Power of Efficient Directory Creation with Newest Windows OSes</u></a></li>
<li><a href="https://win11.techidaily.com/win-wise-utorrent-speeding-up-downloads-made-simple/"><u>Win-Wise uTorrent: Speeding Up Downloads Made Simple</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>