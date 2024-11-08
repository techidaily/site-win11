---
title: "Stretching Your Password: Extending PINs in Windows OSes"
date: 2024-11-01T16:56:40.173Z
updated: 2024-11-07T22:59:49.261Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Stretching Your Password: Extending PINs in Windows OSes"
excerpt: "This Article Describes Stretching Your Password: Extending PINs in Windows OSes"
keywords: Password Length Tips,Secure PIN Strategies,Enhance Account Security,Optimize Windows Passwords,Extend PIN Safely,Increase Login Complexity,Boost OSes Password Rigor
thumbnail: https://thmb.techidaily.com/954afef8b3467f4a3bd6be4e616e7e9c0c40d6a5dfa6d1b3e758e9ac9f354ba6.jpg
---

## Stretching Your Password: Extending PINs in Windows OSes

 Windows Hello enables users to sign into Windows 11/10 accounts with PINs. That feature restricts users to four-character PINs by default. There isn’t an option available within the Change your PIN box to set a longer PIN that includes more than four characters.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to Extend the PIN Length by Editing the Registry

 Windows 11/10 Home doesn’t have any built-in setting for extending the minimum PIN length. So, many users will have to extend PIN length by creating a new PINComplexity registry key. Then you can set a new minimum PIN length value within that key. You can extend the Windows Hello PIN length by editing the registry as follows:

1. To view the file finder tool, press that utility’s **Win + S** keyboard shortcut.
2. Type **regedit** in the file search box and select its result to [open Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. Enter this path inside Registry Editor’s address bar and press **Return**:  
`HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\`
4. If the Microsoft key doesn’t have a PassportForWork subkey, you’ll need to set one up. To do so, right-click on the Microsoft key and select **New** \> **Key**.  
![The New > Key options](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/new-key-options3.jpg)
5. Type **PassportForWork** in the new key’s text box.

1. Next, right-click on the **PassportForWork** key to select the **New** and **Key** options on Registry Editor’s context menu.
2. Enter **PINComplexity** inside the key’s text box to set that name.
3. Right-click the **PINComplexity** key to select **New** \> **DWORD (32-bit) Value**.
4. Enter **MinimumPINLength** in the DWORD text box.  
![The MinimumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-dword.jpg)
5. Double-click the new **MinimumPINLength** DWORD you’ve created.

1. Select the **Decimal** option.
2. Then input a number higher than four in the **Value data** box and click **OK**. The value you enter there will be the new minimum character length for the Windows Hello PIN.  
![The Edit DWORD window for the MinimumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window4.jpg)
3. You can also set a maximum PIN length. To do so, right-click **PINComplexity** again and select the **DWORD (32-bit) Value** option on the **New** submenu.
4. Type **MaximumPINLength** into the DWORD’s text box.  
![A MaximumPINLength DWORD text box](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-text-box.jpg)
5. Double-click **MaximumPINLength** to view the **Value box** for that DWORD.
6. Click on the **Decimal** radio button.
7. Enter a number higher than the one set for the **MinimumPINLength** DWORD and select **OK**.  
![The Edit DWORD window for the MaximumPINLength DWORD](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/edit-dword-window-for-maximum-pin-length.jpg)
8. Finally, exit the Registry Editor window and restart your PC.

 Now you’ll see an “organization requires that you change your PIN message” when you try to sign in with the PIN usually entered. Click **OK** to view some options for setting a new PIN. Then input a longer identification number with the minimum number of characters required inside the **New** and **Confirm** PIN boxes.

![The change your PIN message](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/sign-in-message.jpg)

 If you’ve not set a Windows Hello PIN before, you can do so via Settings. Our guide to [setting a PIN in Windows](https://www.makeuseof.com/setup-remove-pin-windows-11/) includes instructions for how to do so. Your PIN must have the minimum number of characters set with the **PINComplexity** registry key.

## How to Extend the PIN Length With Group Policy Editor

 Windows Pro and Enterprise editions have a Group Policy Editor tool that includes options for setting minimum and maximum PIN lengths. So, you don’t need to manually edit the registry to set a minimum PIN length if you can access Group Policy Editor. This is how to extend Windows Hello’s PIN length with Group Policy Editor:

1. Press **Windows** logo key + **R** and enter **gpedit.msc** in Run.
2. Click on Run’s **OK** button to [access Group Policy Editor](https://www.makeuseof.com/windows-11-open-local-group-policy-editor/).
3. Double-click on **Computer Configuration** in the left sidebar.
4. Next, double-click **Administrative Templates** to extend it.  
![Administrative Templates in Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/administrative-templates.jpg)
5. Then click the arrow by **System** and select **PIN Complexity**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997630/19272" target="_top" id="1997630">
  <img src="//a.impactradius-go.com/display-ad/19272-1997630" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997630/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Double-click on the **Minimum PIN Length** policy.  
![The PIN Complexity policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/pin-complexity.jpg)
2. Click the **Enabled** radio button to activate a **Minimum PIN Length** box.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012401/19272" target="_top" id="2012401">
  <img src="//a.impactradius-go.com/display-ad/19272-2012401" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012401/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3. Then input a higher value in the **Minimum PIN Length** box.  
![The Minimum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-policy.jpg)
4. Select **Apply** and **OK** to set the new PIN length policy.
5. You can also set a max PIN length much the same by clicking the **Maximum PIN Length** policy, selecting **Enabled**, and inputting a new value. Then click on **Apply** and **OK** within the Maximum PIN length window.  
![The Maximum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-policy.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959707/19272" target="_top" id="1959707">
  <img src="//a.impactradius-go.com/display-ad/19272-1959707" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959707/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137201/26400" target="_top" id="2137201">
  <img src="//a.impactradius-go.com/display-ad/26400-2137201" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137201/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Extend Your Windows PIN to Make It More Secure

 Extending the minimum PIN length for logging in to Windows with one of the methods above is a good security measure. The longer your Windows Hello PIN is, the more secure your PC will be. However, an overly long PIN will be harder to remember. So, don’t make your PIN too long!

 Windows Hello also enables users to set alternative biometric authentication. Fingerprint or retina authentication types are more advanced Windows Hello features than PINs. However, you’ll need a PC that supports such biometric security features to enable them.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-8k-tv-showdown-highest-resolution-screens-compared/"><u>[New] 2024 Approved 8K TV Showdown Highest Resolution Screens Compared</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-accelerate-audio-playback-on-spotify-safely-and-effectively/"><u>[New] In 2024, Accelerate Audio Playback on Spotify Safely & Effectively</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-zooming-into-clarity-a-blueprint-for-crisp-screenshots-for-2024/"><u>[Updated] Zooming Into Clarity A Blueprint for Crisp Screenshots for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-high-end-drones-get-yours-now/"><u>2024 Approved High-End Drones Get Yours Now</u></a></li>
<li><a href="https://win11.techidaily.com/essential-techniques-to-modify-windows-11-account-hierarchy/"><u>Essential Techniques to Modify Windows 11 Account Hierarchy</u></a></li>
<li><a href="https://win-forum.techidaily.com/guide-to-overcome-total-drive-occupancy-problems-in-windows-10-computers/"><u>Guide to Overcome Total Drive Occupancy Problems in Windows 10 Computers</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-inventory-of-videography-items-for-exploration/"><u>In 2024, Inventory of Videography Items for Exploration</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-windows-fixes-unraveling-error-1152-on-pc/"><u>Mastering Windows Fixes: Unraveling Error 1152 on PC</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-to-activate-or-deactivate-fingerwritten-entry-in-windows/"><u>Quick Tips to Activate or Deactivate Fingerwritten Entry in Windows</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-itel-s23-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Itel S23 Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/reviving-lost-windows-a-compact-guide-to-resurrecting-hidden-panes-on-win-10/"><u>Reviving Lost Windows: A Compact Guide to Resurrecting Hidden Panes on Win 10</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-correct-error-0x800700e1-windows/"><u>Steps to Correct Error 0X800700E1 Windows</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-stop-overheating-in-computers-os-w11/"><u>Strategies to Stop Overheating in Computers OS: W11</u></a></li>
<li><a href="https://win11.techidaily.com/successfully-restarting-non-operational-obs-on-pc/"><u>Successfully Restarting Non-Operational OBS on PC</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-6-best-sim-unlock-services-that-actually-work-on-your-huawei-nova-y71-device-by-drfone-android/"><u>The 6 Best SIM Unlock Services That Actually Work On Your Huawei Nova Y71 Device</u></a></li>
<li><a href="https://win11.techidaily.com/three-essential-tweaks-for-windows-11-settings/"><u>Three Essential Tweaks for Windows 11 Settings</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlock-xiaomi-redmi-a2plus-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>Unlock Xiaomi Redmi A2+ Phone Password Without Factory Reset Full Guide Here</u></a></li>
</ul></div>

