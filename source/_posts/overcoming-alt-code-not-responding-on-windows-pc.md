---
title: Overcoming ALT Code Not Responding on Windows PC
date: 2024-07-13T10:28:02.186Z
updated: 2024-07-14T10:28:02.186Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Overcoming ALT Code Not Responding on Windows PC
excerpt: This Article Describes Overcoming ALT Code Not Responding on Windows PC
keywords: Fix Alt Code Error,Resolve ALT 255,Overcome Windows Alt Failure,Correct AltCode Response Issue,Stop ALT 255 Not Working,Prevent Windows Alt Code Non-Response,Heal Windows Alt Not Responding
thumbnail: https://thmb.techidaily.com/efbab3d097792aa66f0bd2cf2071c3ef92d9d9dc79fa36684145aac317075ce9.jpg
---

## Overcoming ALT Code Not Responding on Windows PC

 ALT codes are a great way to quickly enter special characters, symbols, and letters into your documents or other text fields. However, sometimes they don't work as expected and can be difficult to troubleshoot.

 If you are experiencing problems with ALT codes on your Windows system, there are several steps you can take to try and get them working again. This guide will explain what causes this problem and how to fix it.

## What Causes Windows ALT Codes to Not Work?

 ALT codes are characters that you can use to create various symbols and special characters on your computer, but they may not always work on Windows. If you're having trouble getting ALT codes to work, there are a few potential causes that could be behind the issue.

 The most common reason for ALT codes not working is that the number lock setting has been turned off. This setting controls how numbers on the numeric keypad function, so check it if you're having trouble with your ALT codes.

 Another cause of this problem is incorrect language settings on Windows. If your language settings don't match the keyboard layout you're using, then it's possible your input won't be interpreted properly by Windows.

 The problem may also occur due to conflicting background programs, outdated software drivers, or hardware compatibility glitches. If you are experiencing this issue, here are some tips for resolving it.

## 1\. Turn On Mouse Keys

 If you need to use ALT codes on Windows but find that they are not working, you might want to enable Mouse Keys when NUM LOCK is ON. This is an easy fix for many ALT code problems.

 The method involves pressing the**left ALT + left SHIFT + NUM LOCK** keys simultaneously on your keyboard. In the popup menu that appears, click**Yes** and Mouse Keys will be enabled.

 Doing this should allow you to use ALT codes again, as it will enable you to type characters by clicking the numeric keypad with the mouse cursor. This is especially useful if your laptop does not have a separate number pad or if you’re using a smaller keyboard without one.

## 2\. Modify the System Settings

 If the above solution does not work, it means the keyboard shortcut is disabled in the Ease of Access Centre. In such a case, you can manually make the changes either through the Control Panel or via Windows Settings. Here's how to do it:

1. Press**Win + I** on your keyboard to [launch the Windows Settings](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select the**Accessibility** tab in the left pane.
3. On the right side, click**Mouse** under the Interaction section.
4. Click the toggle to enable the**Mouse keys** .  
![Turn On the Mouse keys](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/turn-on-the-mouse-keys.jpg)
5. Check the box next to**Only use mouse keys when Num lock is on** .

 After performing the steps above, close the window and restart your computer. At the next system startup, try using ALT codes again to see if it resolves the issue.

## 3\. Tweak the Registry Editor

 If the above solutions do not work, it seems that your registry has an entry that prevents you from adding Unicode characters. In that case, you may need to enable Unicode character input.

 This is a more advanced solution and requires some familiarity with the Windows registry editor.

 If you are uncomfortable working with your computer's registry, get professional assistance. You should also [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before making any changes.

To get started, follow these steps:

1. Press**Win + R** on your keyboard to [open the Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) .
2. In the text field, type "regedit" and press Enter or click the**OK** button.
3. When a UAC window appears on the screen, click**Yes** .  
![Enable HexNumpad in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-hexnumpad-in-registry.jpg)
4. After opening the Registry Editor, navigate to the following directory. Alternatively, you can copy and paste the given location in the registry address field and hit**Enter** on your keyboard:  
HKEY_CURRENT_USER\Control Panel\Input Method
5. Now right-click on**Input Method** and choose**New > String Value** .
6. Once you have created the string value, name it**EnableHexNumpad** and press**Enter** to save it.
7. Double-click on EnableHexNumpad, and a pop-up window will appear.
8. In the Value data field, set**1** and click**OK** to save your changes.

 Once you've completed the above steps, close Registry Editor and restart your computer. Upon restarting, hold down the right Alt key and press the + (plus) key on your numeric keypad. Then enter the hex code, and release the Alt key to enter any character.

## 4\. Remove the Problematic Application

 If you have installed any third-party applications that might be causing problems with the ALT codes, then uninstalling them could also help fix this issue. To do this, follow these steps:

1. Press**Win + X** and select**Installed apps** from the top of the list.
2. Look for the program that is causing the error.
3. Once you find it, click the three dots and click**Uninstall** .
4. Then follow the onscreen instructions to complete the process.

## 5\. Try a Different Keyboard Layout

 If you’re still having issues with ALT codes, you can try switching to a different keyboard layout. Here's how to do it:

1. Open the Control Panel (see [how to open the Control Panel on Windows](https://www.makeuseof.com/windows-11-open-control-panel/) ).
2. Then go to**Clock and Region > Region** . Alternatively, type**intl.cpl** in the Run dialog box and press**Enter** .  
![Try a Different Keyboard Layout](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/try-a-different-keyboard-layout.jpg)
3. Under the**Formats** tab, select a different language from the list.

 After selecting one, click**Apply** , then**OK** , and restart your computer. Now try using ALT codes again to see if they work now.

## 6\. Troubleshoot With a Clean Boot

 If none of the above solutions work, you can try [performing a clean boot on Windows](https://www.makeuseof.com/clean-boot-windows-11/) . This will start your computer with only essential services and programs running, which can help identify any potential conflicts or issues with startup items that may be causing ALT codes to malfunction.

1. Open the MSConfig tool (see [how to open MSConfig on Windows](https://www.makeuseof.com/windows-11-open-msconfig/) ) and select the**General** tab.
2. Check the**Selective startup** box.
3. Make sure that the box**Load startup items** is unchecked.  
![Perform-a-Clean-Boot-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Perform-a-Clean-Boot-1.jpg)
4. The next step is to click on the**Services** tab.
5. Click**Hide all Microsoft services** , then click**Disable all** .  
![Hide all Microsoft services](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/10/Hide-all-Microsoft-services.jpg)
6. Click the**Apply** button to save the changes.
7. Go to the**Startup** tab and click**Open Task Manager** .
8. On the Startup tab, right-click each service and disable it.
9. After making changes to System Configuration, click**OK** .

## Troubleshooting Windows ALT codes

 ALT codes are a useful tool to have when it comes to typing special characters, but outdated software drivers or conflicting background programs may prevent it from working properly. In this case, you can rely on the information above to help you resolve the problem.


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
<li><a href="https://win11.techidaily.com/set-personalized-idle-lock-on-windows/"><u>Set Personalized Idle Lock on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-successfully-reconnecting-win11-to-5g-wi-fi/"><u>Steps for Successfully Reconnecting Win11 to 5G Wi-Fi</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-oneplus-ace-2-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On OnePlus Ace 2 | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-your-easy-guide-to-proficient-voice-recording-on-a-mac-for-non-tech-savvy-individuals/"><u>New In 2024, Your Easy Guide to Proficient Voice Recording on a Mac for Non-Tech Savvy Individuals</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-best-6-social-media-platforms-for-business/"><u>2024 Approved  Best 6 Social Media Platforms for Business</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-the-ultimate-guide-to-zdsoft-video-recording/"><u>[New] The Ultimate Guide to ZDSoft Video Recording</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-polaroid-xs-review-capturing-life-in-full-hd/"><u>[New] Polaroid XS Review  Capturing Life in Full HD</u></a></li>
<li><a href="https://extra-resources.techidaily.com/a-kinemaster-editors-roadmap-for-flawless-transitions/"><u>A Kinemaster Editor's Roadmap for Flawless Transitions</u></a></li>
<li><a href="https://win11.techidaily.com/setting-up-your-image-snap-shot-size/"><u>Setting Up Your Image Snap Shot Size</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-qt-engine-initialization-problem-in-software/"><u>Rectifying Qt Engine Initialization Problem in Software</u></a></li>
<li><a href="https://win11.techidaily.com/revolutionize-desktop-efficiency-with-wmdesk/"><u>Revolutionize Desktop Efficiency with WmDesk</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-htc-u23-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On HTC U23? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-access-tackling-onedrive-logins-in-windows/"><u>Reviving Access: Tackling OneDrive Logins in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/tactics-to-overcome-windows-lunar-client-launch-problem/"><u>Tactics to Overcome Windows Lunar Client Launch Problem</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-unauthorized-save-errors-in-windows/"><u>Overcoming Unauthorized Save Errors in Windows</u></a></li>
<li><a href="https://android-unlock.techidaily.com/a-complete-guide-to-oem-unlocking-on-vivo-t2-pro-5g-by-drfone-android/"><u>A Complete Guide To OEM Unlocking on Vivo T2 Pro 5G</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-your-workflow-coloring-without-conflict-on-windows/"><u>Streamlining Your Workflow: Coloring Without Conflict on Windows</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-leverage-google-voices-features-secure-and-capture-every-call-interaction-for-2024/"><u>Updated Leverage Google Voices Features Secure and Capture Every Call Interaction for 2024</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/updated-best-4-eminem-voice-generator-apps-for-pc-mac-mobile-and-online/"><u>Updated Best 4 Eminem Voice Generator Apps for PC, Mac, Mobile, and Online</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-windows-security-add-safe-websites-now/"><u>Optimize Windows Security: Add Safe Websites Now</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-the-ultimate-guide-to-basic-hdr-imaging/"><u>In 2024, The Ultimate Guide to Basic HDR Imaging</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-mastering-idevice-screen-recording-techniques-for-youtube/"><u>In 2024, Mastering iDevice Screen Recording Techniques for YouTube</u></a></li>
<li><a href="https://win11.techidaily.com/tackling-top-windows-11-challenges-with-ease/"><u>Tackling Top Windows 11 Challenges with Ease</u></a></li>
<li><a href="https://extra-information.techidaily.com/why-picshot-your-gateway-to-hassle-free-collages/"><u>Why Picshot? Your Gateway to Hassle-Free Collages</u></a></li>
<li><a href="https://win11.techidaily.com/say-goodbye-to-troubleshooting-woes-on-vistawindows-7/"><u>Say Goodbye to Troubleshooting Woes on Vista/Windows 7</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-windows-ram-cache-cleanse-procedures/"><u>Step-by-Step: Windows RAM Cache Cleanse Procedures</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-10-leading-free-online-recording-tools-expert-opinions/"><u>[New] In 2024, 10 Leading Free Online Recording Tools - Expert Opinions</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-explore-the-power-of-repeated-imagery-in-your-instagram-content/"><u>[New] 2024 Approved  Explore the Power of Repeated Imagery in Your Instagram Content</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-avoid-dwarf-fortress-freezes-on-windows-systems/"><u>Steps to Avoid Dwarf Fortress Freezes on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-asana-app-performance-on-windows-systems/"><u>Reviving Asana App Performance on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/revitalize-gpu-settings-on-windows-11-pcs/"><u>Revitalize GPU Settings on Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-and-personalize-windows-11-files-via-added-movecopy/"><u>Streamline and Personalize Windows 11 Files via Added 'Move'/'Copy'</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-storage-windows-1011-automatic-file-deletion/"><u>Streamlining Storage: Windows 10/11 Automatic File Deletion</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-cost-free-match-mastery-how-to-stream-and-slice/"><u>2024 Approved  Cost-Free Match Mastery  How to Stream and Slice</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-eliminate-windows-1011-camera-app-error-a00f429f/"><u>Steps to Eliminate Windows 10/11 Camera App Error A00F429F</u></a></li>
</ul></div>
