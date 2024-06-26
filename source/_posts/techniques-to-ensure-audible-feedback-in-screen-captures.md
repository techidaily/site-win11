---
title: Techniques to Ensure Audible Feedback in Screen Captures
date: 2024-06-25T10:19:13.827Z
updated: 2024-06-26T10:19:13.827Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Techniques to Ensure Audible Feedback in Screen Captures
excerpt: This Article Describes Techniques to Ensure Audible Feedback in Screen Captures
keywords: Audio Verification Techniques,Sound Feedback Methods,Effective Clear Noise,Dialogue Clarity Boosting,Precision in Screen Capture,Audible Feedback Strategies,Enhancing Visibility Quality
thumbnail: https://thmb.techidaily.com/fb8053ac7214659fa378f042df998d4365da978dd3a640439d6ee68045b0a185.jpg
---

## Techniques to Ensure Audible Feedback in Screen Captures

 The screen recording feature in Microsoft PowerPoint can be useful for recording tutorials or training videos on your computer. But what if PowerPoint fails to capture the audio when you record the screen of your Windows computer?

 If you are annoyed by a similar issue, here are some troubleshooting tips that will help.

## 1\. Restart PowerPoint

 Temporary issues with PowerPoint can sometimes disrupt its ability to capture audio on your Windows computer. If it’s just a one-off glitch, simply closing and reopening PowerPoint should fix the problem.

 Press **Ctrl + Shift + Esc** to open the Task Manager. In the **Processes** tab, right-click on **Microsoft PowerPoint** and select the **End task** option.

![Close PowerPoint Using Task Manager on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/close-powerpoint-using-task-manager-on-windows.jpg)

 Right-click on the **PowerPoint** shortcut and select **Run as administrator**. After that, try to create a screen recording and see if PowerPoint records the audio this time.

## 2\. Allow Desktop Apps to Use Your Microphone

 Another reason why PowerPoint might fail to record audio is if you have denied desktop apps permission to access your microphone. Here's how you can change that.

1. Press **Win + I** to open the Settings app.
2. Head to **Privacy & security > App permissions > Microphone**.
3. Enable the toggle next to **Let desktop apps access your microphone**.  
![Allow Desktop Apps to Access Microphone on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/allow-desktop-apps-to-access-microphone-on-windows.jpg)

 Once you complete the above steps, all your desktop apps, including PowerPoint, should be able to use your microphone.

## 3\. Check Which Device Is Set as the Default Microphone on Windows

 Are there several audio devices connected to your Windows computer? If so, you need to ensure that you have selected the correct microphone on Windows.

 To view or change the default microphone on Windows, use these steps:

1. Click the **magnifying icon** on the taskbar to access the search menu.
2. Type **sound settings** in the box and press **Enter**.
3. Under the **Input** tab, select your preferred audio device.  
![Select Default Microphone in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-default-microphone-in-windows.jpg)

 Is your microphone not showing up in the Settings app? Apply the necessary [fixes to get Windows to detect your microphone](https://www.makeuseof.com/windows-not-detecting-microphone/).

## 4\. Disable Hardware Graphics Acceleration in PowerPoint

 While enabling the hardware graphics acceleration feature in PowerPoint can improve its performance, the feature may not work seamlessly all the time. When this happens, you are likely to run into all kinds of issues, including issues with the screen recorder.

 According to a post on [Microsoft Community](https://answers.microsoft.com/en-us/msoffice/forum/all/audio-not-working-on-my-ppt-recording/79c77eae-2f86-4c09-a3d6-5fc4b3d89c58), several users managed to fix this particular issue by disabling the hardware graphics acceleration in PowerPoint. You can also give it a try with these steps:

1. Open PowerPoint on your PC.
2. Click the **File** menu in the top left corner.
3. Select **Options** from the left pane.
4. In the PowerPoint Options window, use the left pane to switch to the **Advanced** tab.
5. Scroll down to the **Display** section.
6. Clear the checkboxes that read **Disable hardware graphics acceleration** and **Disable Slide Show hardware graphics acceleration**.
7. Click **OK** to apply the changes.  
![Disable Hardware Acceleration in PowerPoint](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-hardware-acceleration-in-powerpoint.jpg)

 Restart PowerPoint after this for changes to take effect.

## 5\. Run the Windows Recording Audio Troubleshooter

 Windows offers several useful troubleshooters for fixing common issues on your computer. In this case, running the Recording Audio troubleshooter can help. It can automatically detect any issues with PowerPoint's audio recording functionality and fix them.

 To run the Recording Audio troubleshooter:

1. Right-click on the **Start** icon and select **Settings** from the list.
2. Navigate to **System > Troubleshoot > Other troubleshooters**.
3. Click the **Run** button next to **Recording Audio**.  
![Recording Audio Troubleshooter on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/recording-audio-troubleshooter-on-windows.jpg)

 Allow the troubleshooter to find and fix any issues, and then check if PowerPoint can record the audio.

## 6\. Restart the Windows Audio Services

 Windows relies on certain audio services to capture and record your audio. Typically, these services start automatically every time you boot your computer.

 However, if one of these services encounters any problems, your apps and programs may fail to record the audio. In most cases, you can fix such issues by simply restarting the audio services on your PC.

 To do so, use these steps:

1. Press **Win + S** to open the search menu.
2. Type **services** in the search box and select the first result that appears.
3. In the Services window, locate the **Windows Audio** service. Right-click on it and select **Restart**.
4. Similarly, restart the **Windows Audio Endpoint Builder** service as well.  
![Restart Windows Audio Service](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/restart-windows-audio-service.jpg)

 Using the Services app isn't the only way to manage services on Windows. You can also use Task Manager, Command Prompt and PowerShell to [start, stop or restart services on Windows](https://www.makeuseof.com/how-to-start-stop-service-windows/).

## 7\. Start PowerPoint in Safe Mode

 One of your add-ins may be acting up and causing PowerPoint to malfunction. To check for this possibility, you need to open PowerPoint in safe mode. For that, press **Win + R** to open the Run dialog box. Type **PowerPnt /safe** in the text field and press **Enter**.

 After opening PowerPoint in safe mode, try creating a screen recording and see if it records audio as expected. If it does, it means one of your add-ins is causing the problem. To identify the one causing the issue, you will need to disable all of your add-ins and then re-enable them one at a time. Here’s how to do that.

1. In PowerPoint, click the **File** menu in the top left corner.
2. Select **Options** in the left pane.
3. In the PowerPoint Options window, switch to the **Add-ins** tab.
4. Click the drop-down menu next to **Manage** and select **COM Add-ins**.
5. Click the **Go** button.
6. Clear the checkboxes to disable add-ins and then click **OK**.  
![Disable Add-ins in PowerPoint](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/disable-add-ins-in-powerpoint.jpg)

 Restart PowerPoint after this, and then enable your add-ins one at a time until the issue occurs again. Once you find the faulty add-in, consider removing it.

## 8\. Update Microsoft PowerPoint

 Such issues can also occur if you are using an outdated version of PowerPoint. To update PowerPoint, navigate to **File > Account**. Click on **Update Options** and select **Update Now**.

![Update PowerPoint on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/update-powerpoint-on-windows.jpg)

 Wait for Microsoft Office to update PowerPoint, and the issue should not occur after that.

## 9\. Run the Office Repair Tool

 If PowerPoint still won’t record audio while recording the screen on Windows, you can run the Office repair tool as a last resort. Here are the steps for the same.

1. Press **Win + S** to open the search menu.
2. Type **control panel** in the text box and press **Enter**.
3. Click on **Programs and Features**.
4. Locate the **Microsoft Office suite** on the list. Right-click on it and select **Change**.
5. Select the **Quick Repair** option and hit the **Repair** button.  
![Repair Microsoft Office](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/repair-microsoft-office.jpg)

 If the problem persists even after this, you can run the Office repair tool again to perform an **Online Repair**. Note that this process may take a little longer to complete, as the tool will attempt a more thorough repair.

## Get PowerPoint to Record Your Audio Again on Windows

 It can be frustrating when PowerPoint stops recording audio on your Windows computer. In any case, one of the above tips should help fix the underlying issue for good.

 If you are annoyed by a similar issue, here are some troubleshooting tips that will help.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/setting-failed-logon-retry-timeframe-in-win-1011/"><u>Setting Failed Logon Retry Timeframe in Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/critical-guide-restoring-lost-logins-in-windows-11/"><u>Critical Guide: Restoring Lost Logins in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/masked-commands-the-win-1011-trickery-guide/"><u>Masked Commands: The Win 10/11 Trickery Guide</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-windows-update-experience-with-easy-fixes-here/"><u>Seamless Windows Update Experience With Easy Fixes Here</u></a></li>
<li><a href="https://win11.techidaily.com/entrusting-administration-to-command-line/"><u>Entrusting Administration to Command Line</u></a></li>
<li><a href="https://win11.techidaily.com/re-engaging-with-ms-store-a-stepwise-approach-to-windows-pcs/"><u>Re-Engaging with MS Store: A Stepwise Approach to Windows PCs</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-copy-and-paste-on-chrome-edge-and-firefox-windows/"><u>Restoring Copy & Paste on Chrome, Edge, and Firefox (Windows)</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-you-cast-your-apple-iphone-7-to-windows-pc-with-ease-drfone-by-drfone-ios/"><u>In 2024, How Can You Cast Your Apple iPhone 7 to Windows PC With Ease? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-clearing-the-path-for-smooth-fb-stories-posting-and-playback/"><u>[New] In 2024, Clearing the Path for Smooth FB Stories Posting and Playback</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-how-to-effortlessly-connect-zoom-with-gmail/"><u>2024 Approved  How to Effortlessly Connect Zoom with Gmail</u></a></li>
<li><a href="https://iphone-location.techidaily.com/in-2024-6-methods-to-protect-yourself-from-location-tracking-on-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, 6 Methods to Protect Yourself from Location Tracking on Apple iPhone 11 Pro Max | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-disclosing-the-top-10-hidden-story-enthusiasts/"><u>[New] 2024 Approved  Disclosing the Top 10 Hidden Story Enthusiasts</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-in-2024-top-10-best-free-video-compressors/"><u>Updated In 2024, Top 10 Best Free Video Compressors</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-cost-effective-engagement-separating-paid-likes-from-natural-growth/"><u>[Updated] Cost-Effective Engagement  Separating Paid Likes From Natural Growth</u></a></li>
<li><a href="https://techidaily.com/is-your-nokia-g42-5g-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Nokia G42 5G working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-itel-p55-5g-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location without Jailbreak On Itel P55 5G | Dr.fone</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>