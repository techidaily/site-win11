---
title: How to Fix the “Side-by-Side Configuration Is Incorrect” Error on Windows
date: 2024-06-25T11:40:23.906Z
updated: 2024-06-26T11:40:23.906Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes How to Fix the “Side-by-Side Configuration Is Incorrect” Error on Windows
excerpt: This Article Describes How to Fix the “Side-by-Side Configuration Is Incorrect” Error on Windows
keywords: WinErrorFixer,ConfigWindowsErr,SideBySideErrorRepair,ResolveWinConfigIssue,FixWinSideBySide,WindowsConfigCorrection,ErrorWindowsSides
thumbnail: https://thmb.techidaily.com/ef372663750da3323ed4b8491ee9b4b175fd85bfcc73dd50c99f11aa454f80c7.jpg
---

## How to Fix the “Side-by-Side Configuration Is Incorrect” Error on Windows

 It's frustrating when you can't launch your favorite apps and programs on Windows due to the "Side-by-side configuration is incorrect" error. While determining the exact cause of this error can be difficult, it is possible to resolve it.

 In most cases, the “Side-by-side configuration is incorrect” error occurs due to a damaged Visual C++ package or a compatibility issue. However, there can be other reasons for it. So, what can you do to resolve this unforeseen error on Windows? Let's find out.

## 1\. Reinstall Microsoft Visual C++ Packages

 Problems with the current Visual C++ packages on your PC can often result in the “Side-by-side configuration is incorrect” error on Windows. If that's the case, you must reinstall the problematic Visual C++ package on your computer. To do so, you'll need to find its version number using Event Viewer. Here's how you can go about it.

1. Press**Win + S** to open the search menu.
2. Type**event viewer** in the search box and select the first result that appears.
3. Use the left pane to navigate to**Custom Views > Summary page events** .  
![Event Viewer on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Event-Viewer-on-Windows.jpg)
4. Choose the most recent side-by-side error from the middle pane and note down the version number under the**General** tab.
5. Open up your web browser and head over to the[Microsoft Visual C++ Redistributable download page](https://learn.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170) .
6. Download and install the Visual C++ package corresponding to your version number.

 Restart your PC after this (see[how to restart your Windows PC](https://www.makeuseof.com/windows-restart-methods/) ) and try to launch your app or program one more time.

## 2\. Run the SFC and DISM Scans

 Corrupted or missing system files on your computer can also trigger such errors. Fortunately, Windows includes a useful command-line utility called SFC (or System File Checker) scan for such occasions. It can automatically detect any damaged system files on your PC and replace them with their cached versions.

To run the SFC scan on your computer:

1. Press**Win + X** to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt shows up.
4. In the console, type**sfc /scannow** and press**Enter** .  
![Run SFC Scan on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Run-SFC-Scan-on-Windows.jpg)

 Wait for the scan to complete and then run the DISM (or Deployment Image Servicing and Management) scan by entering the following command:

`DISM.exe /Online /Cleanup-image /Restorehealth`

 After the process is complete, exit the Command Prompt window and restart your PC. The error should not appear anymore after the reboot.

## 3\. Run the Program Compatibility Troubleshooter

 If the “Side-by-side configuration is incorrect” error only appears when you try to launch a specific program, you can run the program compatibility troubleshooter on Windows. It’ll try to fix any compatibility issues with your program and help you fix the error. Here’s how you can run it.

1. Right-click on your app or program that’s producing the error and select**Troubleshoot compatibility** .
2. In the Program Compatibility Troubleshooter window, select**Troubleshoot program** .
3. Mark the checkbox that reads **The program worked in earlier versions of Windows but won’t install or run now** and hit**Next** .
4. Follow the on-screen prompts to run the troubleshooter and see if the error occurs again.  
![Program Compatibility Troubleshooter Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Program-Compatibility-Troubleshooter-Windows.jpg)

## 4\. Repair the Problematic App

 If the Windows troubleshooter fails to find any problems, you can try repairing the problematic app on Windows. Here's how to do it.

1. Press**Win + I** to open the Settings app.
2. Navigate to the**Apps** tab.
3. Go to**Installed apps** .
4. Scroll down to locate the problematic app on the list. Click the**three-dot menu icon** next to it and select**Advanced options** .
5. Scroll down to the Reset section and click on**Repair** .  
![Repair App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Repair-App-on-Windows.jpg)

 You should see a right checkmark next to the Repair button once the process is complete.

 Alternatively, you can repair your apps and programs from Control Panel. To learn more about this, check our guide on[how to repair apps and programs on Windows](https://www.makeuseof.com/windows-repair-apps-programs/) and follow the steps outlined there.

## 5\. Reinstall the Problematic App

 Repairing the app may not help much if the existing app data is corrupted or missing. In that case, your only option is to uninstall the problematic app and install it again.

1. Press**Win + S** to open the search menu.
2. Type in the name of your app or program and select**Uninstall** from the right pane.
3. Select**Uninstall** again to confirm.  
![Uninstall App on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Uninstall-App-on-Windows.jpg)

 Head over to Microsoft Store and install the app again. Following this, the error should not bother you.

## 6\. Scan for Malware

 If your computer is infected with malware, you may encounter such errors when launching apps and programs. To check for this possibility, you can run a full system scan of your PC with Windows Defender. You can also use one of the[best third-party antivirus programs for Windows](https://www.makeuseof.com/tag/best-antivirus-for-windows-10/) for this.

 If the scan uncovers anything suspicious, take the recommended steps to fix the issue and reboot your PC after that.

## 7\. Install Pending Windows Updates

 Microsoft regularly releases updates for the Windows operating system. Aside from new features and security patches, these updates also bring much-needed fixes for bugs and other errors. You can try updating Windows to its most recent version to see if that makes a difference.

 Press**Win + I** to open the Settings app and navigate to the**Windows Update** section. Click on**Check for updates** to download and install pending updates.

![Check for System Updates on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/Check-for-System-Updates-on-Windows.jpg)

## 8\. Perform a System Restore

 Windows System Restore performs a backup of the entire system on a regular basis. You can use it to revert your system to a point before the error first started appearing.

To perform a system restore on Windows:

1. Press**Win + R** to open the Run dialog box.
2. Type**sysdm.cpl** in the box and press**Enter** .
3. In the System Properties window, switch to the**System Protection** tab.
4. Click on**System Restore** .
5. Click**Next** .
6. Select a restore point before the first appeared and hit**Next** .
7. Check all the details and hit**Finish** .  
![System Restore Dialog on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/11/System-Restore-Dialog-on-Windows.jpg)

 Windows will restart and revert to the specified restore point. Following that, the error should be resolved.

## Start Using Your Apps Again

 By applying the above fixes, you should be able to fix the “Side-by-side configuration is incorrect” error in no time. However, if none of the solutions work, you may have to reset your Windows computer as a last resort.


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
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-windows-error-0x80073d26/"><u>Unraveling the Mystery of Windows' Error 0X80073D26</u></a></li>
<li><a href="https://win11.techidaily.com/essentials-for-enabling-win11-on-5ghz-networks-effortlessly/"><u>Essentials for Enabling Win11 on 5GHz Networks Effortlessly</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-admins-rights-issue-in-win-os/"><u>Bypassing Admins Rights Issue in Win OS</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-unidentified-hdd-situations/"><u>Navigating Through Unidentified HDD Situations</u></a></li>
<li><a href="https://win11.techidaily.com/free-notetaking-on-windows-easy-and-effective/"><u>Free Notetaking on Windows: Easy and Effective</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-troubleshooting-winerror-0x80071a90/"><u>Understanding & Troubleshooting WinError 0X80071A90</u></a></li>
<li><a href="https://win11.techidaily.com/fix-the-gap-how-to-locate-and-utilize-hidden-windows-11-enhancements/"><u>Fix the Gap: How to Locate & Utilize Hidden Windows 11 Enhancements</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-write-unavailable-issue-in-windows/"><u>Eradicating 'Write Unavailable' Issue in Windows</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-discords-premier-love-and-fun-sites/"><u>2024 Approved  Discord's Premier Love and Fun Sites</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-xiaomi-redmi-12-5g-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Xiaomi Redmi 12 5G? Look No Further | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-unlock-perfect-lighting-best-video-brightening-apps-for-mobile/"><u>New In 2024, Unlock Perfect Lighting Best Video Brightening Apps for Mobile</u></a></li>
<li><a href="https://extra-support.techidaily.com/photo-motion-smear-for-realism-in-adobe-for-2024/"><u>Photo Motion Smear for Realism in Adobe for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-poco-x5-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Poco X5 | Dr.fone</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ading-flv-to-youtube-video-converters-for-2024/"><u>10 Leading FLV to YouTube Video Converters for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-unmask-tiktok-on-devices-best-watermark-apps-for-iphone-and-android-for-2024/"><u>[Updated] Unmask TikTok on Devices  Best Watermark Apps for iPhone & Android for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-vivo-y02tmirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Vivo Y02TMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/5-best-photo-editing-app-for-android-phone/"><u>5 Best Photo Editing App for Android Phone</u></a></li>
</ul></div>
