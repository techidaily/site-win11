---
title: Reverting Back to Original Touch Key Settings on Windows
date: 2024-10-11T23:02:40.029Z
updated: 2024-10-15T22:20:49.844Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reverting Back to Original Touch Key Settings on Windows
excerpt: This Article Describes Reverting Back to Original Touch Key Settings on Windows
keywords: Windows Touch Reset,Restore Touch Screen Defaults,Change PC Touch Key Placement,Revert Windows Key Layout,Adjust Touch Keys on Windows,Optimize Touch Settings Windows,Customize Windows Key Positioning
thumbnail: https://thmb.techidaily.com/843a2530bd30cf31b24741cc2e56b474bee5d065dd6fb56cbf786d1e09002e10.jpg
---

## Reverting Back to Original Touch Key Settings on Windows

 Are you using a Windows touchscreen device and experiencing keyboard issues? This often occurs when certain keys are difficult to use or scrolling becomes tricky because the keyboard pops up in the wrong spot.

 To help with this issue, we'll explain two methods to reset the default opening position of your touch keyboard in Windows 11\. The first method requires running a batch file, while the second involves tweaking the Windows Registry Editor.

Let's explore each one.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Tweak Registry Editor to Reset Touch Keyboard Default Open Position

 The Registry Editor is an advanced tool and requires caution when editing. But if you want to reset the default opening position of the touch keyboard efficiently, this is the method to use. However, as I have said before, you have to be especially careful when editing the Registry Editor as any mistake could cause serious damage.

 It is always a good idea to[create a system restore point](https://www.makeuseof.com/use-system-restore-windows/) or to take a[backup of the registry editor](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before starting. This can help if something goes wrong. It is now time to reset the default open position of the touch keyboard. To do so, follow these steps:

1. Press**Win + R** on your keyboard to open the Run dialog box.
2. Type**regedit** in the text box and press Enter. This will launch the Registry Editor.
3. Click**Yes** if the UAC (User Account Control) window asks for permission.
4. Once you're in the Registry Editor, navigate to this location:  
`HKEY_CURRENT_USER\Software\Microsoft\TabletTip\1.7`  
 Alternatively, you can copy and paste the given path into the Registry Editor's address bar. This will take you to the specified location.
5. On the left side of the menu, select the**1.7** folder.  
![Tweak Registry Editor to Reset Touch Keyboard Default Open Position](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/tweak-registry-editor-to-reset-touch-keyboard-default-open-position.jpg)
6. Then go to its corresponding right pane, where you will find the**OptimizedKeyboardRelativeXPositionOnScreen** REG\_DOWRD value. Right-click on the key and delete it.
7. Similarly, delete the**OptimizedKeyboardRelativeYPositionOnScreen** key value in the same folder.

 After deleting both values, close the Registry Editor and restart your PC to apply the changes. Now, when you open the touch keyboard, it will start showing up at the default opening position.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972684/19272" target="_top" id="1972684">
  <img src="//a.impactradius-go.com/display-ad/19272-1972684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Run a Batch File to Reset the Touch Keyboard's Default Open Position

 Resetting the default opening position of your touch keyboard can be done quickly and easily by running a batch file. This method is especially useful if you prefer to automate the reset process instead of manually tweaking the registry editor. Here is how to do it.

 To get started, you first need to open the Notepad application. For this, you can type "Notepad" in either Windows Search or the Run dialog box and press**Enter** .

 Once you're in Notepad, copy and paste the following code into it:

`@echo off  
REG Delete "HKCU\SOFTWARE\Microsoft\TabletTip\1.7" /V OptimizedKeyboardRelativeXPositionOnScreen /F  
REG Delete "HKCU\SOFTWARE\Microsoft\TabletTip\1.7" /V OptimizedKeyboardRelativeYPositionOnScreen /F  
taskkill /f /im explorer.exe  
start explorer.exe`

 Now click**File** in the upper-left corner and select**Save As** from the menu list.

![Run Batch File to Reset Touch Keyboard Default Open Position](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/run-batch-file-to-reset-touch-keyboard-default-open-position.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087253/19272" target="_top" id="2087253">
  <img src="//a.impactradius-go.com/display-ad/19272-2087253" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087253/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the File name field, type "ResetTouch.bat", and choose**All Files** from the Save as type. After that, select Desktop from the left-hand side and click**Save** .

 Once the batch file is saved, close the Notepad window. Next, double-click**ResetTouch.bat** on your Desktop to run it. This should reset your touch keyboard's default open position.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044585/7443" target="_top" id="2044585">
  <img src="//a.impactradius-go.com/display-ad/7443-2044585" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044585/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Resetting the Default Position of the Touch Keyboard

 If you're using a Windows touchscreen device, typing with a touch keyboard can be easy. However, you might have noticed an inconvenience where the keyboard opens in an awkward position.

 This can make typing on specific keys difficult, especially if you're used to accessing the keyboard from a certain spot. To fix this issue, refer to this guide on resetting the default open position of your touch keyboard.

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
<li><a href="https://eaxpv-info.techidaily.com/updated-endless-creativity-free-youtube-art-resources-for-2024/"><u>[Updated] Endless Creativity FREE YouTube Art Resources for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-twitter-videos-shared-directly-from-phones-for-2024/"><u>[Updated] Twitter Videos Shared Directly From Phones for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-5-must-know-elements-of-influential-titles/"><u>2024 Approved 5 Must-Know Elements of Influential Titles</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/cheetah-dual-arm-tv-mount-review-a-well-built-mount-for-budget-shoppers/"><u>Cheetah Dual Arm TV Mount Review: A Well-Built Mount for Budget Shoppers</u></a></li>
<li><a href="https://win11.techidaily.com/consistent-windows-display-avoid-background-shifts/"><u>Consistent Windows Display: Avoid Background Shifts</u></a></li>
<li><a href="https://win11.techidaily.com/detailed-guide-customizing-local-gpos-for-individual-users/"><u>Detailed Guide: Customizing Local GPOs for Individual Users</u></a></li>
<li><a href="https://win11.techidaily.com/eschew-premature-edge-tab-activation-win11-style/"><u>Eschew Premature Edge Tab Activation, Win11 Style</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fake-gps-on-samsung-galaxy-s23plus-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>In 2024, How To Fake GPS On Samsung Galaxy S23+ For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-magixs-legacy-in-vectors-finding-future-software/"><u>In 2024, Magix's Legacy in Vectors Finding Future Software</u></a></li>
<li><a href="https://extra-resources.techidaily.com/intova-x-reviewed-cutting-edge-action-capture/"><u>Intova X Reviewed Cutting-Edge Action Capture</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/optimizing-content-sharing-from-twitters-to-snaps/"><u>Optimizing Content Sharing From Twitters to Snaps</u></a></li>
<li><a href="https://win11.techidaily.com/steps-for-unblocking-steam-play-link-errors/"><u>Steps for Unblocking Steam Play Link Errors</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-eliminating-error-code-0x80070522-client-rights-upgrade/"><u>Strategies for Eliminating Error Code 0X80070522: Client Rights Upgrade</u></a></li>
<li><a href="https://win11.techidaily.com/unison-vs-phone-link-top-windows-phone-app-ranking/"><u>Unison Vs. Phone Link: Top Windows Phone App Ranking</u></a></li>
</ul></div>

