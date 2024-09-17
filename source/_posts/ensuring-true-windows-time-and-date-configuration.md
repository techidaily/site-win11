---
title: Ensuring True Windows Time & Date Configuration
date: 2024-09-11T23:40:43.028Z
updated: 2024-09-17T04:03:46.441Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Ensuring True Windows Time & Date Configuration
excerpt: This Article Describes Ensuring True Windows Time & Date Configuration
keywords: Windows Time Accuracy,Precise Windoze Clock,Validate WinTimeSync,Correct Windows Time Setup,Authenticate True DateTime,Ensure Correct WINDOWS Date,Verify True Windows Time
thumbnail: https://thmb.techidaily.com/5ef4b9be2cc03e1f5bba8134aa6b00b2355f4bf8946df71748d869f7b05769b2.jpg
---

## Ensuring True Windows Time & Date Configuration

 You’re using your Windows device and notice something strange in the date and time settings. Someone has changed the settings without your knowledge or permission. This makes it difficult to stay on schedule with tasks and activities. In this guide, we’ll show how to stop anonymous users from changing date and time settings on Windows computers.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How To Prevent Users From Changing the Date and Time on Windows

 There are two ways to prevent users from changing Windows date and time. The first is to use Group Policy Editor, a system administration tool designed to control computer behavior in an organization. While the second way is to use Registry Editor, which allows you to modify Windows registry settings.

 For both methods, you need administrative access to the computer to change it. Once you’ve made the changes, nobody can alter the date and time settings. Let’s look at each method in more detail.

## 1\. Use the Group Policy Editor

 If your computer is part of an organization and users often change the date and time, use Group Policy Editor to stop it. This will prevent those with limited access to the computer from altering the date and time. However, this method only works for Windows Pro, Enterprise, or Education Editions.

 So, if you have Windows Home Edition, this won’t work. In that case, you must first [activate the Group Policy Editor for Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/). If it seems complicated, skip it and try the next solution instead.

 Follow these steps to prevent users from changing the date and time:

1. Press **Win + R** on your keyboard to open the Run window.
2. Type **gpedit.msc** in the text box and press Enter. This will open the Group Policy Editor window.
3. On the left side of the window, navigate to the following path:  
Computer Configuration > Administrative Templates > System > Locale Services
4. In the right-side pane, double-click on **Disallow user override of locale settings**.  
![Disallow user override of locale settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/disallow-user-override-of-locale-settings.jpg)
5. In the pop-up window, check the **Enabled** radio button.
6. Then click **Apply** \> **OK** to save the changes.

 This will block anyone from changing the date and time settings on your computer. However, if you have administrative access to the computer, you can still alter the settings.

 If you want to revert to the default settings later, open Group Policy Editor again and change the value of Disallow user override of locale settings back to Not Configured or Disabled. This way, users can change the time and date again.

## 2\. Tweak the Registry Editor

 If you’re using Windows Home Edition or have disabled the Group Policy Editor, use the Registry Editor to protect date and time settings. This method is more advanced and has a higher risk of system damage.

 In that case, [back up your Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) before changing it. Doing so will restore settings if something goes wrong.

 Follow these steps to stop users from changing the time and date via the registry:

1. [Open the Run command dialog box](https://www.makeuseof.com/windows-open-run-command-dialog-box/).
2. Type **regedit** in the field and press Enter. This will [open the Registry Editor](https://www.makeuseof.com/windows-11-open-registry-editor/).
3. In the Registry Editor window, navigate to the following path:  
HKEY_CURRENT_USER\Software\Policies\Microsoft\Control Panel\International\
4. If the International folder doesn’t exist, create one. To do that, right-click on Control Panel and select **New** \> **Key**. Name it **International**.
5. Then right-click on **International** and select New > DWORD (32-bit) Value.
6. Name the newly created value **PreventUserOverrides**.
7. Double-click on the **PreventUserOverrides** DWORD value.  
![Use Registry Editor to Prevent Users From Chaning date and time settings](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/use-registry-editor-to-prevent-users-from-chaning-date-and-time-settings.jpg)
8. In the pop-up window, change the Value data to **1** and click **OK**.

 Once you’ve made the changes, close the Registry Editor window and restart your computer.

 To undo this restriction, delete the **PreventUserOverrides** DWORD value from the registry or change the value to **0**. Doing so will enable users to change the time and date again.

<!-- affiliate ads begin -->
<span id="1899850">
					<video width="486" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1899850.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14483-1899850">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1899850.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:304px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Felectronicx.pxf.io%2Fc%2F5597632%2F1899850%2F14483'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1899850/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Stop Windows Time and Date Changes

 Now stop unauthorized users from changing the date and time settings on your Windows computer. This keeps your tasks and activities on track. If necessary, you can always undo this restriction.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-clips.techidaily.com/new-become-an-expert-at-youtube-live-streams-with-google-meet/"><u>[New] Become an Expert at YouTube Live Streams with Google Meet</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-from-video-to-gif-seamless-process-for-vimeo-content/"><u>[New] In 2024, From Video to GIF Seamless Process for Vimeo Content</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-enhancing-zoom-with-a-chrome-os-device-for-2024/"><u>[Updated] Enhancing Zoom with a Chrome OS Device for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-omni-angle-equipment-for-immersive-shoots/"><u>[Updated] Omni-Angle Equipment for Immersive Shoots</u></a></li>
<li><a href="https://win11.techidaily.com/host-free-windows-based-gpt-clones-using-gpt4all/"><u>Host Free Windows-Based GPT Clones Using GPT4All</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-eliminate-microsoft-store-error-code-0-in-windows-11/"><u>How to Eliminate Microsoft Store Error Code 0 in Windows 11</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-sharefake-location-on-whatsapp-for-honor-x7b-drfone-by-drfone-virtual-android/"><u>How to Share/Fake Location on WhatsApp for Honor X7b | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-tecno-spark-20-pro-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass Tecno Spark 20 Pro FRP In 3 Different Ways</u></a></li>
<li><a href="https://win11.techidaily.com/leveraging-gpresult-for-dynamic-group-policy-reports/"><u>Leveraging GPResult for Dynamic Group Policy Reports</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-fixes-eradicating-freezing-issues-with-steam-on-win-11/"><u>Mastering Fixes: Eradicating Freezing Issues with Steam on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-windows-error-403-in-roblox/"><u>Navigating Windows Error 403 in Roblox</u></a></li>
<li><a href="https://techtrends.techidaily.com/seamless-combining-of-abbyy-and-automation-anywhere-enhancing-business-efficiency-through-innovative-software-synergy/"><u>Seamless Combining of ABBYY and Automation Anywhere: Enhancing Business Efficiency Through Innovative Software Synergy</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-oppo-reno-11-5g-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from Oppo Reno 11 5G</u></a></li>
<li><a href="https://win11.techidaily.com/sprint-past-slow-spots-enhance-win-outlook/"><u>Sprint Past Slow Spots: Enhance WIN Outlook</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    