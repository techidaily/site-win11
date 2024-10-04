---
title: "Win 10/11: Strategies for Applying GPO to One User Account"
date: 2024-09-28T17:03:45.993Z
updated: 2024-10-03T18:19:40.272Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Win 10/11: Strategies for Applying GPO to One User Account"
excerpt: "This Article Describes Win 10/11: Strategies for Applying GPO to One User Account"
keywords: Win 10 GPO Tips,Win 11 GPO Guide,Apply GPO Single-User,Windows GPO Strategy,Individual User GPO,GPO Settings for OnePC,Single PC GPO Application
thumbnail: https://thmb.techidaily.com/34062c0c76761441d1daaab882479cf039a7dd266a5c393fca1f08310200c903.jpg
---

## Win 10/11: Strategies for Applying GPO to One User Account

 When applying a local group policy to your PC, you may not want it to paint over all users. The answer is to apply local group policy to a specific user or set of users. This way you can control which features are accessible to specific user accounts.

 It also makes it easy to apply and modify controls and appearances for individual users, and you’ll get a quick glance at which policies apply to which users. Here’s how to apply local group policy to specific user accounts on Windows 10 and 11\.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What Is the Local Group Policy?

 Group Policy is a Windows feature that gives you more control over the things user accounts are able to do and have access to. Changing Group Policy changes how the system works for different sets of users. We’ve covered [what Group Policy is and how you can use it](https://www.makeuseof.com/tag/windows-group-policy/), with examples, in much more detail separately.

## How to Apply a Local Group Policy to a Specific User Account

 First off, you must have Windows 10 Pro, Enterprise, or Education editions to access the Local Group Policy Editor. Here’s how to set up what’s called a [Microsoft Saved Console](https://www.makeuseof.com/microsoft-management-console-how-to-use-it/) (MSC) for a specific user.

1. Press **Win + R**, type “mmc” into the box, and hit **OK**. This will open the Microsoft Management Console.
2. You will be presented with a UAC prompt. Click on **Yes**.
3. In the Microsoft Management Console window that opens up, go to **File > Add/Remove Snap-in**.  
![Adding a snap-in to the Microsoft Saved Console](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/01-add-remove-snap-in-microsoft-saved-console.jpg)
4. Look for and select **Group Policy Object Editor**; click on the **Add** button to add it to the **Selected snap-ins** pane; and click **OK**.  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130532/26400" target="_top" id="2130532">
  <img src="//a.impactradius-go.com/display-ad/26400-2130532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130532/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Adding Group Policy Object Editor for a specific user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/02-add-group-policy-object-editor-microsoft-saved-console.jpg)
5. Next you will be asked to select a Group Policy Object. Click on **Browse**.  

<!-- affiliate ads begin -->
<span id="2135472">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135472%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135472/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![Select the Group Policy Object for a specific user](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/03-select-group-policy-object.jpg)

<!-- affiliate ads begin -->
<span id="1770544">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770544.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770544">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770544.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770544%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770544/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

1. Switch to the **Users** tab in the window that pops up.  
![Select user-specific Group Policy](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/06/04-msc-select-user-group-policy.jpg)
2. Select the user account for which you want to create a custom Local Group Policy, then click **OK**.
3. Click on the **Finish** button, and then on the **Add or Remove Snap-ins** window, click **OK** on the bottom right.
4. The Group Policy for the specific user should appear in the console window.
5. Go to **File > Save As** and select a location you want to save the MSC. You can rename it here.
6. Once you’re done, click on the **Save** button.

 You’ve now created a user-specific Local Group Policy MSC. Whenever you need to configure policy settings that apply just to this specific user, double-click the file you just created and make the policy changes you need. Don’t forget to save the console settings when finished.

<!-- affiliate ads begin -->
<span id="1993654">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993654.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993654">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993654.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993654%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993654/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Easily Control What Windows Users Have Access To

 By utilizing Local Group Policy, you have greater control over what functionality you accord to a specific user or set of users. A simple change at this level can make your job much easier when applying restrictions and granting freedoms to Windows users.

 It also makes it easy to apply and modify controls and appearances for individual users, and you’ll get a quick glance at which policies apply to which users. Here’s how to apply local group policy to specific user accounts on Windows 10 and 11\.

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-dive-into-the-world-of-expertise-with-youtubes-top-10-makeup-vloggers-for-2024/"><u>[New] Dive Into the World of Expertise with YouTube's Top 10 Makeup Vloggers for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-easy-paths-to-profitable-youtube-business-channels-top-10-list/"><u>[Updated] Easy Paths to Profitable YouTube Business Channels, Top 10 List!</u></a></li>
<li><a href="https://win11.techidaily.com/debate-time-which-is-more-user-friendly-chocolatey-or-wm/"><u>Debate Time: Which Is More User-Friendly, Chocolatey or WM?</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-charge-notifications-in-win-1011/"><u>Fine-Tuning Charge Notifications in Win 10/11</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-samsung-galaxy-a24-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Samsung Galaxy A24 If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://buynow-help.techidaily.com/hulus-subscription-key-factors-that-count/"><u>Hulu’s Subscription: Key Factors That Count</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-amplify-watcher-count-simplified-tactics-exposed/"><u>In 2024, Amplify Watcher Count Simplified Tactics Exposed</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-realme-12-proplus-5g-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Realme 12 Pro+ 5G via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-ultimate-guide-to-applying-vhs-filters-on-computers/"><u>In 2024, Ultimate Guide to Applying VHS Filters on Computers</u></a></li>
<li><a href="https://win11.techidaily.com/quick-tips-to-upgrade-mouses-double-tap-velocity/"><u>Quick Tips to Upgrade Mouse’s Double-Tap Velocity</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/radpowers-radcity-5plus-assessed-a-biking-beast-that-packs-a-punch-but-carries-some-extra-kilos/"><u>RadPower's RadCity 5+ Assessed: A Biking Beast that Packs a Punch but Carries Some Extra Kilos</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-lost-dll-d3dx939-in-windows-11/"><u>Restoring Lost DLL: D3DX9_39 in Windows 11</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-convergence-of-two-giants-palm-2-meets-bard/"><u>The Convergence of Two Giants: PaLM 2 Meets Bard</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-strategies-for-powerful-windows-file-navigation/"><u>Ultimate Strategies for Powerful Windows File Navigation</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-the-root-cause-of-file-creation-problem-error-30005/"><u>Understanding the Root Cause of File Creation Problem - Error 30005</u></a></li>
</ul></div>

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
    