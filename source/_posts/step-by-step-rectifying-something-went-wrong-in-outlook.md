---
title: "Step-by-Step: Rectifying 'Something Went Wrong' In Outlook"
date: 2024-10-24T06:50:07.911Z
updated: 2024-10-26T22:53:50.897Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Step-by-Step: Rectifying 'Something Went Wrong' In Outlook"
excerpt: "This Article Describes Step-by-Step: Rectifying 'Something Went Wrong' In Outlook"
keywords: Fixing Outlook Errors,Outlook Issue Resolution,Correcting Outlook Mistakes,Troubleshooting Outlook Problems,Solving Outlook Glitches,Clearing Outlook Malfunctions,Repairing Outlook Errors Step-by-Step
thumbnail: https://thmb.techidaily.com/d27bd20369a0206f3a047b7bb4f9e0b9ec6c2aca32544460f90baebbc95c9231.jpg
---

## Step-by-Step: Rectifying 'Something Went Wrong' In Outlook

 Microsoft Outlook's somewhat vague "Something went wrong" error message may appear when you are trying to set up your account or using the app in general. Without a clear indication of what’s going wrong, fixing such Outlook errors can be tricky.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Edit Registry Files

 Autodiscover is a nifty feature that allows Outlook to automatically configure email account settings without requiring manual input from the user. If this service receives any unexpected results from the third-party web server, Outlook might display the "Something went wrong" error message. To resolve this, you will need to make a few changes to the registry files on your PC.

 As you may be aware, making incorrect changes to the registry files can render your system inoperable. Hence, it is advisable to [back up all of your registry files](https://www.makeuseof.com/tag/backup-restore-windows-registry/) or [create a restore point](https://www.makeuseof.com/windows-11-create-restore-point/) before proceeding.

1. Press **Win + R** to open the Run dialog box.
2. Type **regedit** in the box and press **Enter**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Paste the following path in the address bar at the top and press **Enter** to quickly navigate to the **AutoDiscover** key.  
`Computer\HKEY_CURRENT_USER\Software\Microsoft\Office\XX.0\Outlook\AutoDiscover`  
 Replace **XX.0** in the above path with your version of Office (**16.0** \= Office 365, Office 2019, and Office 2016, **15.0** \= Office 2013).
5. Right-click on the **AutoDiscover** key and select **New > DWORD (32-bit) Value**.  
![Create DWORD in Registry](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/create-dword-in-registry.jpg)

1. Rename the DWORD to **ExcludeHttpsRootDomain**.
2. Double-click the newly created DWORD and set its value to **1**.
3. Right-click on the **AutoDiscover** key again and select **New > DWORD (32-bit) Value**. Name the DWORD **ExcludeHttpsAutoDiscoverDomain**.
4. Double-click the **ExcludeHttpsAutoDiscoverDomain** DWORD and set its value to **1**.
5. Create two more DWORD values named **ExcludeSrvRecord** and **ExcludeLastKnownGoodUrl** and set their values to **1**.  
![AutoDiscover in Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/autodiscover-in-registry-editor.jpg)

 Restart your PC after this and check if you still get the “Something went wrong” error in Microsoft Outlook.

## 2\. Open Outlook in Safe Mode

 At times, third-party add-ins in Outlook can disrupt app processes and trigger such errors. To verify if this is the case, you can [try starting Outlook in safe mode](https://www.makeuseof.com/outlook-safe-mode/).

 If Outlook works as expected, it means one of your add-ins is causing the issue. To find the culprit, you'll need to disable all the add-ins and re-enable them one at a time. Here are the steps for the same.

1. In the Outlook app, click on **File > Options**.
2. In the **Outlook Options** window, select the **Add-ins** tab from the left sidebar.
3. Click the **Go** button next to **COM Add-ins**.
4. Clear all the checkboxes to disable your add-ins and then click **OK**.  
![Disable Outlook Add-Ins-1](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-outlook-add-ins-1.jpg)

 Restart the Outlook app and enable your add-ins one by one until the error occurs again. Once you find the troublesome add-in, consider removing it to avoid such issues.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135418/19272" target="_top" id="2135418">
  <img src="//a.impactradius-go.com/display-ad/19272-2135418" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135418/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Clear the Outlook Cache

 Outdated or corrupted cache data can cause Outlook to misbehave and display unusual errors. If this is the cause of your problems, clearing the Outlook app cache should get things going again. To do so, use these steps:

1. Press **Win + R** to open the Run command (see [how to open the Windows Run dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/) for more information).
2. Type **%localappdata%\\Microsoft\\Outlook** in the text box and press **Enter**.
3. In the **RoamCache** folder that opens, press **Ctrl + A** to select all the files, and click the **trash** icon at the top to delete them.  
![Delete Outlook Cache Data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/delete-outlook-cache-data.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915825/19272" target="_top" id="1915825">
  <img src="//a.impactradius-go.com/display-ad/19272-1915825" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915825/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/1062450/7443" target="_top" id="1062450">
  <img src="//a.impactradius-go.com/display-ad/7443-1062450" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/1062450/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Repair Your Outlook Profile

 Another reason why you may get the “Something went wrong” error in Outlook is if there is an issue with your Outlook profile. You can try repairing your Outlook profile to see if that restores normalcy. Here are the steps for the same.

1. Open the Outlook app and click the **File** menu at the top.
2. In the Info tab, click on **Account Settings** and select **Account Settings**.
3. Select your profile under the **Email** tab and click **Repair**.  
![Repair Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/repair-outlook-account.jpg)

 Allow Outlook to repair your profile and then restart the app.

## 5\. Remove and Re-Add Your Account

 If repairing your Outlook profile does not help, your next best option is to remove your email account from the Outlook app and add it back. Here's how to do it.

1. Open the Outlook app.
2. Navigate to **File > Info > Account Settings > Account Settings**.
3. Under the **Email** tab, select your account and click **Remove**.
4. Select **Yes** to continue.  
![Remove Outlook Account](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/remove-outlook-account.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139118/17108" target="_top" id="2139118">
  <img src="//a.impactradius-go.com/display-ad/17108-2139118" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139118/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once removed, click the **New** option under the **Email** tab and set up your account again.

## 6\. Remove Outlook Password From Credential Manager

 Are you getting the "Something went wrong" error while adding an account in Outlook? That might be caused by outdated data in the [Credential Manager](https://www.makeuseof.com/windows-credential-manager-guide/). You can try removing any Outlook entries from the Credential Manager to fix the issue.

1. Click the **magnifying icon** on the taskbar.
2. Type **credential manager** in the box and select the first result that appears.
3. Select **Windows Credentials**.
4. Select the entry related to your account and click **Remove**.  
![Remove Outlook Credentials From Windows PC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/remove-outlook-credentials-from-windows-pc.jpg)

## 7\. Run the Office Repair Tool

 Running Microsoft’s Office repair tool is an effective way to resolve issues with Office apps like Outlook. So, if the above tips don't help, you can run the Office repair tool as a last resort.

1. Press **Win + S** to open the search menu.
2. Type **Control Panel** in the box and press **Enter**.
3. Click the drop-down menu in the top right corner to select **Large icons**.
4. Click on **Programs and Features**.
5. Select **Microsoft Office suite** on the list and click the **Change** button at the top.
6. Select the **Quick Repair** option.
7. Click the **Repair** button.  
![Repair Microsoft Office](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-office.jpg)

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1815679/21290" target="_top" id="1815679">
  <img src="//a.impactradius-go.com/display-ad/21290-1815679" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1815679/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If the problem persists even after this, repeat the above steps to perform an **Online Repair**. This process may take a little longer, but it’s most likely to resolve the issue.

## Fixing Outlook's “Something Went Wrong” Error on Windows

 Encountering such errors in the Outlook app can affect your productivity and leave you frustrated. We hope that the solutions listed above have helped in resolving the “Something went wrong” error in Microsoft Outlook.

 That said, if all of the above tips prove ineffective, we recommend you contact the official Microsoft support team for further assistance.

 To help out, we have listed all the possible ways to fix the “Something went wrong” error in Outlook for Windows.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://some-guidance.techidaily.com/new-the-15-most-effective-live-sports-streaming-methods/"><u>[New] The 15 Most Effective Live Sports Streaming Methods</u></a></li>
<li><a href="https://win11.techidaily.com/confronting-cpu-crunches-how-to-manage-windows-resource-monitor/"><u>Confronting CPU Crunches: How to Manage Windows Resource Monitor</u></a></li>
<li><a href="https://buynow-info.techidaily.com/discover-the-capabilities-of-the-revolutionary-ampace-andes-1500-portable-energy-source/"><u>Discover the Capabilities of the Revolutionary Ampacē Andes 1500 Portable Energy Source</u></a></li>
<li><a href="https://driver-download.techidaily.com/fast-access-secure-your-asus-ac68-driver-downloads-at-no-cost/"><u>Fast Access: Secure Your Asus AC68 Driver Downloads at No Cost</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-update-error-0xc1900101-0x30017-in-windows-11-and-11/"><u>How to Fix the Update Error 0xC1900101 – 0X30017 in Windows 11 & 11</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-successfully-bypass-icloud-activation-lock-on-iphone-13-mini-by-drfone-ios/"><u>How to Successfully Bypass iCloud Activation Lock on iPhone 13 mini</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-nokia-g22-by-phone-number-drfone-by-drfone-virtual-android/"><u>How to Track Nokia G22 by Phone Number | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-vision-record-studio-2021/"><u>In 2024, Vision Record Studio 2021</u></a></li>
<li><a href="https://win11.techidaily.com/reducing-resource-overload-how-to-cut-down-dropboxs-power-use-on-windows/"><u>Reducing Resource Overload: How to Cut Down Dropbox's Power Use on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-functionality-of-your-windows-headset-mic/"><u>Regaining Functionality of Your Windows Headset Mic</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-shutdownrestart-malfunction-due-to-mischievous-windows-programs/"><u>Remedying Shutdown/Restart Malfunction Due to Mischievous Windows Programs</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-notifications-omission-in-windows/"><u>Resolving Notifications Omission in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/the-complete-guide-to-mastering-backdrop-blur-on-w11-photo-interface/"><u>The Complete Guide to Mastering Backdrop Blur on W11 Photo Interface</u></a></li>
<li><a href="https://win11.techidaily.com/the-definitive-guide-to-tackling-outlook-notification-issues/"><u>The Definitive Guide to Tackling Outlook Notification Issues</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-ultimate-guide-to-technology-according-to-toms-hardware/"><u>The Ultimate Guide to Technology According to Tom's Hardware</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-solving-laptop-mouse-freezing-issues/"><u>Ultimate Guide: Solving Laptop Mouse Freezing Issues</u></a></li>
<li><a href="https://tech-revival.techidaily.com/understanding-ai-simplified-explanation-of-artificnicial-intelligence/"><u>Understanding AI: Simplified Explanation of Artificnicial Intelligence</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlock-infinix-note-30-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>Unlock Infinix Note 30 Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-full-potential-of-your-windows-11-search-bar/"><u>Unlocking the Full Potential of Your Windows 11 Search Bar</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    