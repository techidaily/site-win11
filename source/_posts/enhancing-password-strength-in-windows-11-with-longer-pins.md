---
title: Enhancing Password Strength in Windows 11 with Longer Pins
date: 2024-06-25T11:32:37.077Z
updated: 2024-06-26T11:32:37.077Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Enhancing Password Strength in Windows 11 with Longer Pins
excerpt: This Article Describes Enhancing Password Strength in Windows 11 with Longer Pins
keywords: Win11 Secure Passwords,Extended Pin Lengths,Strong Password Policy,Tips for Better Security,Windows 11 Pinning,Enhance PIN Safety,Boosting Windows Authentication
thumbnail: https://thmb.techidaily.com/18316e8f71e11f28b59d175ffaa88b6b208294f15c9d92c3f00bf91d9310afa1.jpg
---

## Enhancing Password Strength in Windows 11 with Longer Pins

 Windows Hello enables users to sign into Windows 11/10 accounts with PINs. That feature restricts users to four-character PINs by default. There isn’t an option available within the Change your PIN box to set a longer PIN that includes more than four characters.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.

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

1. Double-click on the **Minimum PIN Length** policy.  
![The PIN Complexity policy settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/pin-complexity.jpg)
2. Click the **Enabled** radio button to activate a **Minimum PIN Length** box.
3. Then input a higher value in the **Minimum PIN Length** box.  
![The Minimum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/minimum-pin-length-policy.jpg)
4. Select **Apply** and **OK** to set the new PIN length policy.
5. You can also set a max PIN length much the same by clicking the **Maximum PIN Length** policy, selecting **Enabled**, and inputting a new value. Then click on **Apply** and **OK** within the Maximum PIN length window.  
![The Maximum PIN Length policy window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/maximum-pin-length-policy.jpg)

## Extend Your Windows PIN to Make It More Secure

 Extending the minimum PIN length for logging in to Windows with one of the methods above is a good security measure. The longer your Windows Hello PIN is, the more secure your PC will be. However, an overly long PIN will be harder to remember. So, don’t make your PIN too long!

 Windows Hello also enables users to set alternative biometric authentication. Fingerprint or retina authentication types are more advanced Windows Hello features than PINs. However, you’ll need a PC that supports such biometric security features to enable them.

 So, it doesn’t seem users can set longer, more secure PINs for signing in to Windows. However, there are two ways to set a new minimum PIN length for the Hello PIN sign-in method. This is how you can extend the PIN length in Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/navigating-windows-to-connect-to-a-network/"><u>Navigating Windows to Connect to a Network</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-not-writable-file-problems-in-windows-11/"><u>Solutions for Not Writable File Problems in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-why-steam-cant-synch-files-in-pc-settings/"><u>Unraveling Why Steam Can't Synch Files in PC Settings</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-reactivate-deactivated-windows-updates/"><u>Steps to Reactivate Deactivated Windows Updates</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-file-handling-in-win-11-by-adding-movecopy-menus/"><u>Elevate Your File Handling in Win 11 by Adding Move/Copy Menus</u></a></li>
<li><a href="https://win11.techidaily.com/alter-viewer-angle-in-windows-setup/"><u>Alter Viewer Angle in Windows Setup</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-chaos-into-clarity-with-obsidian-visual-techniques/"><u>Transforming Chaos Into Clarity with Obsidian Visual Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/deciphering-the-unseen-initiating-windows-secret-self-profile-editor/"><u>Deciphering the Unseen: Initiating Windows' Secret Self-Profile Editor</u></a></li>
<li><a href="https://win11.techidaily.com/teams-growth-without-the-heavy-load/"><u>Teams Growth Without the Heavy Load</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-enable-and-set-up-windows-sandbox-in-windows-11/"><u>How to Enable and Set Up Windows Sandbox in Windows 11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-essential-steps-for-perfect-tiktok-clips-for-2024/"><u>[Updated] Essential Steps for Perfect TikTok Clips for 2024</u></a></li>
<li><a href="https://ai-voice.techidaily.com/new-top-6-darth-vader-ai-generators-for-all-platforms-for-2024/"><u>New Top 6 Darth Vader AI Generators for All Platforms for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/2024-approved-pixel-perfect-calculating-aspect-ratios-with-ease/"><u>2024 Approved Pixel Perfect Calculating Aspect Ratios with Ease</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/mastering-content-creation-essential-tips-for-snapchat-success-for-2024/"><u>Mastering Content Creation  Essential Tips for Snapchat Success for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-synthesis-of-song-elements-the-crossfade-approach/"><u>[Updated] 2024 Approved  Synthesis of Song Elements  The Crossfade Approach</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-mobile-masterpieces-best-video-invitation-creators-for-ios-and-android/"><u>Updated Mobile Masterpieces Best Video Invitation Creators for iOS and Android</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-how-to-safely-archive-chats-and-calls-from-whatsapp-for-2024/"><u>[New] How to Safely Archive Chats and Calls From WhatsApp for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-tecno-spark-go-2023-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Tecno Spark Go (2023) Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-cutting-edge-watermarking-tips-to-ensure-photo-security-on-instagram/"><u>[Updated] Cutting-Edge Watermarking  Tips to Ensure Photo Security on Instagram</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/2024-approved-the-role-and-relevance-of-pfp-in-tiktok-culture/"><u>2024 Approved  The Role and Relevance of PFP in TikTok Culture</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>