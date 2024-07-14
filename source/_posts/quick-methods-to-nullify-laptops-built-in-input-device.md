---
title: Quick Methods to Nullify Laptop's Built-In Input Device
date: 2024-07-13T10:20:47.865Z
updated: 2024-07-14T10:20:47.865Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Quick Methods to Nullify Laptop's Built-In Input Device
excerpt: This Article Describes Quick Methods to Nullify Laptop's Built-In Input Device
keywords: Lactopad Offsetting,BIOS Tweaking,USB Override,Device Disabling,Hardware Switching,Laptop Keyboard Nullify,Input Method Erase
thumbnail: https://thmb.techidaily.com/b458df85a4bb141857a3c4d2de6e35b07f50e405e5e03af8173f938324bb194b.png
---

## Quick Methods to Nullify Laptop's Built-In Input Device

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
3. Click **Yes** to confirm the action.
4. That’s it. You have disabled your laptop’s internal keyboard successfully.

 That said, this is a temporary solution. As soon as you restart your system, Windows will look for the connected but unrecognized devices and install the necessary drivers to make them functional.

## How to Disable Your Laptop Keyboard Permanently

![disable ps 2 port 18042prt command prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/07/disable-ps-2-port-18042prt-command-prompt.jpg)

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
![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)
4. Next, select **Let me pick from a list of available drivers on my computer**.  
![update driver keyboard pick from list of available drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-keyboard-pick-from-list-of-available-drivers-device-manager.jpg)
5. Uncheck the **Show compatible hardware** option.
6. Select a random manufacturer under the **Manufacturer** column.  
![install incompatible keyboard driver windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-incompatible-keyboard-driver0windows.jpg)
7. Click **Next**. Click **Yes** if an **Update Driver Warning** dialog appears.
8. Once installed, close Device Manager and reboot your computer.

 After the restart, your laptop keyboard will stop working. If you need to install the correct driver again to enable the keyboard, right-click on the keyboard device and select **Update driver**. Next, select **Search automatically for drivers**. Windows will look for a compatible driver and install it.

![update driver search automatically for drivers device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-driver-search-automatically-for-drivers-device-manager.jpg)

 Alternatively, select **Browse my computer for drivers** in the Update Drivers dialogue. Next, select **Let me pick from a list of available drivers on my computer**. Make sure the **Show compatible hardware** option is enabled. Select an **HID Keyboard Device** driver from the list and click **Next**.

![install compatible hardware driver keyboard device manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/install-compatible-hardware-driver-keyboard-device-manager.jpg)

 Wait for the driver to install. Once done, reboot your computer, and the keyboard will start working again.

## Disable Your Laptop Keyboard Permanently on Windows

 The built-in chiclet keyboard on your laptop is the primary input method available, so there is no way to disable it with a single click. Also, you wouldn’t want to disable your keyboard accidentally. If you determine your keyboard to have gone rogue and typing on its own, you can permanently disable it using the Command Prompt and Device Manager.

 That said, apart from the hardware issues, your laptop keyboard can act up for many other reasons. To fix your keyboard, check for pending driver updates, use the built-in troubleshooter, or simply disable the individual keys.

 Sometimes you don't want your laptop's keyboard to take inputs. This is usually because you're plugging in an external keyboard, either because the built-in one is broken or you just want a larger typing space with a full-sized keyboard.

 However, since the keyboard is an integral part of your portable computer, disabling its primary input method is a little tricky. Here, we show you how to temporarily and permanently disable the laptop keyboard on Windows 10 and 11\.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/elevate-desktop-aesthetics-with-a-custom-weather-icon-in-windows-11/"><u>Elevate Desktop Aesthetics with a Custom Weather Icon in Windows 11</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-from-viewers-to-earnings-youtube-earning-basics/"><u>2024 Approved  From Viewers to Earnings  YouTube Earning Basics</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-microsofts-activation-error-code-0x8007251d/"><u>Tackling Microsoft's Activation Error Code 0X8007251d</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-guide-to-embedding-app-shortcuts-in-windows-11/"><u>Step-by-Step Guide to Embedding App Shortcuts in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/beginning-the-speedy-support-function-of-w11/"><u>Beginning the Speedy Support Function of W11</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-harness-the-potential-of-instagram-videos-for-brand-growth/"><u>[New] Harness the Potential of Instagram Videos for Brand Growth</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-youtube-cover-pics-made-easy-top-5-free-downloader-lists/"><u>2024 Approved  YouTube Cover Pics Made Easy – Top 5 Free Downloader Lists</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-from-samsung-galaxy-a34-5g-by-drfone-android/"><u>How to Bypass FRP from Samsung Galaxy A34 5G?</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-game-bar-screen-recorder-alternatives/"><u>[Updated] Game Bar Screen Recorder Alternatives</u></a></li>
<li><a href="https://extra-tips.techidaily.com/iphone-filmmaking-essentials-creating-and-changing-video-speed-dynamics/"><u>IPhone Filmmaking Essentials  Creating and Changing Video Speed Dynamics</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-prime-vr-options-enhancing-drone-operations/"><u>[Updated] In 2024, Prime VR Options Enhancing Drone Operations</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-apple-iphone-13-drfone-by-drfone-ios/"><u>How to Unlock Apple iPhone 13? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-professional-filmmaking-secrets-the-ultimate-guide-to-11-color-edits/"><u>[Updated] Professional Filmmaking Secrets  The Ultimate Guide to 11 Color Edits</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/preparation-to-beat-giovani-in-pokemon-go-for-poco-x6-drfone-by-drfone-virtual-android/"><u>Preparation to Beat Giovani in Pokemon Go For Poco X6 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-methods-to-tackle-programming-problems-on-vistawindows-7/"><u>Efficient Methods to Tackle Programming Problems on Vista/Windows 7</u></a></li>
<li><a href="https://win11.techidaily.com/security-straightforward-quick-ways-to-suspend-user-accounts-in-win11/"><u>Security Straightforward: Quick Ways to Suspend User Accounts in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/unclogging-a-stuck-windows-11-settings-bar-the-search-solution/"><u>Unclogging a Stuck Windows 11 Settings Bar - The Search Solution</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-error-x70-on-windows-file-and-folder-restoration-guide/"><u>Eradicating Error X70 on Windows: File and Folder Restoration Guide</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-the-isdonedll-error-in-windows-11-and-11x/"><u>Dealing with the ISDone.dll Error in Windows 11 & 11X</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-from-jump-cuts-to-smooth-moves-3-final-cut-pro-transition-methods/"><u>New In 2024, From Jump Cuts to Smooth Moves 3 Final Cut Pro Transition Methods</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-in-2024-customize-twitter-video-snapshot/"><u>[New] In 2024, Customize Twitter Video Snapshot</u></a></li>
<li><a href="https://win11.techidaily.com/embracing-deity-interactions-with-your-windows-11-pc/"><u>Embracing Deity Interactions with Your Windows 11 PC</u></a></li>
<li><a href="https://win11.techidaily.com/craft-a-quick-fix-to-skip-windows-login-dialogs/"><u>Craft a Quick Fix to Skip Windows Login Dialogs</u></a></li>
<li><a href="https://win11.techidaily.com/crafting-a-flawlessly-new-windows-experience-in-11th-gen/"><u>Crafting a Flawlessly New Windows Experience in 11Th Gen</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshoot-steam-disconnect-in-windows-os/"><u>Troubleshoot Steam Disconnect in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-winget-a-guide-for-windows-11-users/"><u>Reviving Winget: A Guide for Windows 11 Users</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/trailblazers-of-the-cinematic-visual-and-auditory-fusion/"><u>Trailblazers of the Cinematic, Visual & Auditory Fusion</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-turning-on-copy-and-paste-operations-in-edges-security-shield-w11/"><u>Steps for Turning on Copy & Paste Operations in Edge's Security Shield W11</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-chaos-into-clarity-with-obsidian-visual-techniques/"><u>Transforming Chaos Into Clarity with Obsidian Visual Techniques</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-google-pixel-8-pro-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Google Pixel 8 Pro Phone</u></a></li>
<li><a href="https://win11.techidaily.com/adjusting-retry-interval-for-unsuccessful-login-attempts/"><u>Adjusting Retry Interval for Unsuccessful Login Attempts</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-unlocking-ig-potential-strategies-for-accumulating-1000plus-likesmonth/"><u>[New] In 2024, Unlocking IG Potential  Strategies for Accumulating 1,000+ Likes/Month</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-freespace-a-comprehensive-windows-approach/"><u>Enhancing FreeSpace: A Comprehensive Windows Approach</u></a></li>
<li><a href="https://win11.techidaily.com/a-deep-dive-into-windows-11s-8-confusing-features/"><u>A Deep Dive Into Windows 11’S 8 Confusing Features</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-reverse-viewing-crafts-creative-youtube-video-methods/"><u>[Updated] Reverse Viewing Crafts  Creative Youtube Video Methods</u></a></li>
<li><a href="https://win11.techidaily.com/unblock-your-pcs-usb-troubleshooting-guide-for-windows-users/"><u>Unblock Your PC's USB: Troubleshooting Guide for Windows Users</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-step-by-step-guide-to-convert-avis-into-gifs-via-filmora-software/"><u>[Updated] Step-by-Step Guide to Convert AVIs Into GIFs via Filmora Software</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensive-solution-for-geforce-now-error-xc0f1103f-on-windows-11/"><u>Comprehensive Solution for GeForce Now Error: Xc0f1103f on Windows 11</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ssential-youtube-equipment-for-starting-your-channel/"><u>[New] Essential YouTube Equipment For Starting Your Channel</u></a></li>
<li><a href="https://win11.techidaily.com/the-end-of-an-era-microsofts-abandonment-of-windows-7-and-81/"><u>The End of an Era: Microsoft's Abandonment of Windows 7 and 8.1</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-s-best-video-to-gif-converters-a-comprehensive-guide/"><u>Updated S Best Video to GIF Converters A Comprehensive Guide</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-smart-picklist-top-value-free-livestream-software-and-apps-reviewed-this-year/"><u>[New] Smart Picklist  Top Value Free Livestream Software & Apps Reviewed This Year</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-inoperative-touchscreen-actions-in-windows/"><u>Addressing Inoperative Touchscreen Actions in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/clarifying-computer-storage-c-d-distinctions/"><u>Clarifying Computer Storage: C, D Distinctions</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-pioneering-tools-to-embellish-photos-with-words/"><u>In 2024, Pioneering Tools to Embellish Photos with Words</u></a></li>
<li><a href="https://some-tips.techidaily.com/top-picks-for-your-next-shot-in-4k-reflective-tech-for-2024/"><u>Top Picks for Your Next Shot in 4K Reflective Tech for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-file-handling-in-win-11-by-adding-movecopy-menus/"><u>Elevate Your File Handling in Win 11 by Adding Move/Copy Menus</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-icon-recovery-step-by-step-guide/"><u>Windows 11 Icon Recovery: Step-by-Step Guide</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-best-vertical-video-apps-for-ios-and-android/"><u>New In 2024, Best Vertical Video Apps for iOS and Android</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-elevate-video-branding-incorporating-watermarks-into-youtube-media/"><u>[Updated] 2024 Approved  Elevate Video Branding  Incorporating Watermarks Into YouTube Media</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/addressing-hearing-gaps-in-video-content-sharing/"><u>Addressing Hearing Gaps in Video Content Sharing</u></a></li>
<li><a href="https://win11.techidaily.com/7-strategies-to-rectify-chromes-profile-problems-on-desktop/"><u>7 Strategies to Rectify Chrome's Profile Problems on Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-remove-programs-without-permission-in-windows/"><u>Steps to Remove Programs Without Permission in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-simple-way-to-self-empty-the-recycle-bin-on-windows/"><u>The Simple Way to Self-Empty the Recycle Bin on Windows</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-forgot-your-apple-id-password-and-email-from-iphone-12-pro-max-heres-the-best-fixes-by-drfone-ios/"><u>In 2024, Forgot Your Apple ID Password and Email From iPhone 12 Pro Max? Heres the Best Fixes</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-oppo-reno-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Simple and Effective Ways to Change Your Country on YouTube App Of your Oppo Reno 11 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-unsuccessful-image-saving-on-win11-pc/"><u>Addressing Unsuccessful Image Saving on Win11 PC</u></a></li>
</ul></div>
