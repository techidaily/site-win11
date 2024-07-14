---
title: "Locating Group Policies: A User's Guide for Win Users"
date: 2024-07-13T10:38:20.870Z
updated: 2024-07-14T10:38:20.870Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Locating Group Policies: A User's Guide for Win Users"
excerpt: "This Article Describes Locating Group Policies: A User's Guide for Win Users"
keywords: Win Policy Find,Group Policy Locator,Windows Policy Guide,Win Policy Help,Group Policy Assist,PC Policy Management,User's Group Policy
thumbnail: https://thmb.techidaily.com/df6d6f7af97a6f2a263dcbc0519760a864ba0996ca5b9b75ea6d971b44c71c22.jpg
---

## Locating Group Policies: A User's Guide for Win Users

 Changing a group policy is something that many Windows users will have to do at some point in their life. However, knowing the path to a particular setting in the Local Group Policy Editor (LGPE) is not so simple, considering the sheer scale of the folders and subfolders within the tool.

 In this guide, we're going to show you three ways to search for the group policies you need so you don't get lost.

## 1\. Search Using the Local Group Policy Editor's Filter Option

 Press **Win + S** to bring up Windows Search, search for **edit group policy**, and click on **Edit group policy** in the search results. This will launch the LGPE.

 Only the Pro and Enterprise editions of Windows come with the LGPE pre-installed, but there is a way you can [access the LGPE on Home editions](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/).

 In the left pane, right-click the **Administrative Templates** folder (it's the only folder that allows you to search this way), and click **Filter On** to enable filtering. Right-click the folder again, and this time, select **Filter Options**.

![the menu that shows up when you right-click Administrative Templates in the Loca Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/lgpe-search-filter-option.jpg)

 In the Filter Options dialog box, make sure to check the **Enable Keyword Filters** checkbox. Next, in the text box next to **Filter for word(s)**, enter the search terms for the policy or, if you know it, the exact name of the policy.

![the Filter Options dialog box with the Enable Keywords and filter text box part showing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/lgpe-search-filter-options-search-phrase-windows.jpg)

 In the dropdown next to that filter text box, you can choose the following options:

* **Any**: The policy you’re searching for contains one or more of the words entered in the filter text box.
* **All**: The policy you’re searching for contains each word entered in the filter text box.
* **Exact**: The policy you're searching for contains the exact phrase entered in the filter text box.

 Next, check the **Enable Requirement Filters** checkbox and click the **Select All** button (this means you want to search for the policy on all platforms). Then, click **OK**.

![the Filter Options dialog box showing the requirements section](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/lgpe-search-filter-option-requirements-filters.jpg)

 Back in the LGPE, you should start to see the folders and policies decrease in number since others have been filtered out. To quickly find the policy you were searching for, click **All Settings**.

![All Settings selected in the Local Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/lgpe-search-filter-results-windows.jpg)

 While editing, keep in mind that changing the right [group policies can make your PC better](https://www.makeuseof.com/tag/12-ways-windows-group-policy-can-make-pc-better/), or, if you tweak the wrong one, make it worse.

## 2\. Search Using the Group Policy Website

 Besides using filters in the LGPE, you can also use the [Group Policy Search](https://gpsearch.azurewebsites.net/) website. While on the site, click the **filter icon** in the top left corner and uncheck all the products you don’t want to include in the search.

![filtering out products on the Group Policy Search website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/gps-website-filters.jpg)

 Click on the search box at the top, enter the search terms for the policy, and hit the **Enter** key. If you want to do an exact search, be sure to put the search string within quotes, like “disable context menu,” for example.

![searching for a group policy on the Group Policy Search website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/gps-website-searching-policy.jpg)

 The search policy will appear in the second column, so click on it to reveal more information about it in a pop-up. You will see where to find the policy in the LGPE directly under the heading.

![the search results on the Group Policy Search website](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/gps-website-searching-policy-results.jpg)

 Where it says **Key**, you can see where to find the setting in the Registry Editor.

## 3\. Search Using the Group Policy Settings Reference

 If you prefer something offline and a little easier to access compared to searching with the LGPE's filters and the Group Policy Search website, Microsoft has a document you can use. So, download the [Group Policy Settings Reference](https://www.microsoft.com/en-us/download/details.aspx?id=25250) sheet and open it in Excel.

 To search for a policy, click on the **filter icon** next to the **Policy Setting Name** heading in the **C** column. In the text box that says **Search**, type in search terms for the policy you want to find, and then hit the **Enter** key.

![searching the group policy reference sheet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/group-policy-reference-sheet-text-filter.jpg)

 The policies that match the search terms will appear in column **C**. You can find the location of the policy in column **E** under the **Policy Path** heading.

![the results of searching for a group policy in the reference sheet](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/wm/2023/06/group-policy-reference-sheet-policy-path.jpg)

 That’s the folder you need to look at in the LGPE to find the policy that you need to edit.

## Find the Group Policy You Need on Windows

 Now you should be able to find the group policies you need to make your PC better. We know how overwhelming it can be to use the Local Group Policy Editor, but with these tools, it should become a little easier. And if your edits don't take effect right away, there’s a way for you to manually refresh the LGPE to apply the settings immediately.

 In this guide, we're going to show you three ways to search for the group policies you need so you don't get lost.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://win11.techidaily.com/boot-time-essentials-configuring-windows-startups/"><u>Boot Time Essentials: Configuring Windows Startups</u></a></li>
<li><a href="https://win11.techidaily.com/dealing-with-video-reset-error-on-windows-systems/"><u>Dealing with Video Reset Error on Windows Systems</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ring-youtube-uploads-in-adobe-premiere-for-2024/"><u>Mastering YouTube Uploads in Adobe Premiere for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-innovative-free-chat-platforms-with-shared-screen-viewing/"><u>In 2024, Innovative Free Chat Platforms with Shared Screen Viewing</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-sluggishness-fixing-edge-speed-woes-in-windows-10plus11/"><u>Overcoming Sluggishness: Fixing Edge Speed Woes in Windows 10+11</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-easy-passes-to-friends-tiktok-live-events/"><u>[New] 2024 Approved  Easy Passes to Friends' TikTok Live Events</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-the-toolbar-in-microsoft-pc-manager-on-windows-11/"><u>How to Use the Toolbar in Microsoft PC Manager on Windows 11</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-unveiling-the-leading-mac-speech-recorders-our-curated-list-of-5/"><u>[New] In 2024, Unveiling The Leading Mac Speech Recorders  Our Curated List of 5</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-recovery-mode-on-microsoft-devices/"><u>Accessing Recovery Mode on Microsoft Devices</u></a></li>
<li><a href="https://printer-issues.techidaily.com/troubleshooting-hp-errors/"><u>Troubleshooting HP Errors</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-hue-harmonization-handbook-for-experts/"><u>In 2024, Hue Harmonization Handbook for Experts</u></a></li>
<li><a href="https://win11.techidaily.com/expert-advice-regaining-original-windows-configs/"><u>Expert Advice: Regaining Original Windows Configs</u></a></li>
<li><a href="https://win11.techidaily.com/windows-guide-spotting-active-tcp-connections/"><u>Windows Guide: Spotting Active TCP Connections</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-signal-failures-windows-steam-fix-guide/"><u>Addressing Signal Failures: Windows Steam Fix Guide</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-top-15-ff-extensions-for-easy-fb-video-download-for-2024/"><u>[Updated] Top 15 FF Extensions For Easy FB Video Download for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlink-your-iphone-15-plus-from-your-apple-id-by-drfone-ios/"><u>In 2024, How To Unlink Your iPhone 15 Plus From Your Apple ID</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-in-2024-the-quintessential-guide-to-websites-that-whisper-peace-into-your-psyche/"><u>New In 2024, The Quintessential Guide to Websites That Whisper Peace Into Your Psyche</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-photos-from-poco-by-fonelab-android-recover-photos/"><u>How to Rescue Lost Photos from Poco ?</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-snappy-business-ideas-for-profit-for-2024/"><u>[Updated] Snappy Business Ideas for Profit for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/breathe-life-into-your-dormant-device-speakers/"><u>Breathe Life Into Your Dormant Device Speakers</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-windows-update-error-0x80246007-in-windows-11-and-11/"><u>How to Fix the Windows Update Error 0X80246007 in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/guide-to-window-11-custom-taskbar-sizing/"><u>Guide to Window 11 Custom Taskbar Sizing</u></a></li>
<li><a href="https://win11.techidaily.com/connect-your-games-across-screens-win-11-and-android-via-google-linkup/"><u>Connect Your Games Across Screens: Win 11 & Android via Google Linkup</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-your-typing-experience-speed-up-windows-keyboard-delay/"><u>Enhance Your Typing Experience: Speed Up Windows Keyboard Delay</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-analyzing-youtubes-process-for-selective-comment-showcasing/"><u>2024 Approved  Analyzing YouTube's Process for Selective Comment Showcasing</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-ultimate-guide-securely-integrating-tiktok-profile-links/"><u>[Updated] Ultimate Guide  Securely Integrating TikTok Profile Links</u></a></li>
<li><a href="https://win11.techidaily.com/guide-enable-data-transfer-operations-in-edges-protective-mode-win-11/"><u>Guide: Enable Data Transfer Operations in Edge's Protective Mode, Win 11</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-cutting-edge-pfp-trends-enhancing-your-tiktok-impact/"><u>In 2024, Cutting-Edge PFP Trends Enhancing Your TikTok Impact</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-how-to-record-a-gotomeeting-session-on-pcs-and-smartphones-for-2024/"><u>[Updated] How to Record a GoToMeeting Session on PCs and Smartphones for 2024</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-oppo-find-n3-flip-screen-sharing-drfone-by-drfone-android/"><u>How To Do Oppo Find N3 Flip Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/innovative-methodologies-for-embedding-musicality-within-instagram-tv-experiences/"><u>Innovative Methodologies for Embedding Musicality Within Instagram TV Experiences</u></a></li>
<li><a href="https://win11.techidaily.com/best-practices-for-addressing-system-call-failed-on-pcs/"><u>Best Practices for Addressing System Call Failed on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-hyper-v-in-windows-11-steps-to-follow/"><u>Enabling Hyper-V in Windows 11: Steps to Follow</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-end-scene-excellence-your-guide-to-yt-outro-mastery/"><u>[Updated] End Scene Excellence  Your Guide to YT Outro Mastery</u></a></li>
<li><a href="https://win11.techidaily.com/detailed-walkthrough-restoring-default-search-features-in-windows-11/"><u>Detailed Walkthrough: Restoring Default Search Features in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/mend-freezing-clicks-your-action-plan-for-windows/"><u>Mend Freezing Clicks: Your Action Plan for Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-pattern-locks-are-unsafe-secure-your-nubia-red-magic-8s-proplus-phone-now-with-these-tips-by-drfone-android/"><u>In 2024, Pattern Locks Are Unsafe Secure Your Nubia Red Magic 8S Pro+ Phone Now with These Tips</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-move-contacts-from-vivo-v29-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways to Move Contacts From Vivo V29 to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-gaming-experience-with-these-ultimate-strategies-for-win-11/"><u>Elevate Your Gaming Experience with These Ultimate Strategies for Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/unlock-the-gateway-command-windows-11s-appsunlocked/"><u>Unlock the Gateway: Command Windows 11'S AppsUnlocked</u></a></li>
<li><a href="https://win11.techidaily.com/bypassing-the-lock-essential-tpm-hacks-for-windows-11/"><u>Bypassing the Lock: Essential TPM Hacks for Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11-h2-update-rolls-out-more-options/"><u>Windows 11 H2 Update Rolls Out More Options</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-advanced-strategies-for-quiet-capturing/"><u>[Updated] Advanced Strategies for Quiet Capturing</u></a></li>
<li><a href="https://win11.techidaily.com/windows-terminal-tailoring-the-visual-experience/"><u>Windows Terminal: Tailoring the Visual Experience</u></a></li>
<li><a href="https://win11.techidaily.com/expert-tips-for-mastering-3d-painting-shortcuts/"><u>Expert Tips for Mastering 3D Painting Shortcuts</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-value-in-vcplusplus-release-packages/"><u>Unlocking the Value in VC++ Release Packages</u></a></li>
<li><a href="https://win11.techidaily.com/equalize-internet-pace-syncing-laptop-and-mobile-phones/"><u>Equalize Internet Pace: Syncing Laptop & Mobile Phones</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-screen-brilliance-adjustments-in-windows-11/"><u>Mastering Screen Brilliance Adjustments in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-dxgi-failures-on-windows-1011/"><u>Addressing DXGI Failures on Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-the-art-of-correcting-error-740-on-winos/"><u>Mastering the Art of Correcting Error 740 on WINOS</u></a></li>
<li><a href="https://win11.techidaily.com/master-autominimize-windows-woes-no-more/"><u>Master AutoMinimize: Windows Woes No More</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-simplified-guide-enhancing-skype-experience-via-zoom/"><u>[New] 2024 Approved  Simplified Guide  Enhancing Skype Experience via Zoom</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-record-screen-on-huawei-mate-10-20-p20-and-p10-using-a-built-in-recorder/"><u>[New] 2024 Approved  Record Screen On Huawei Mate 10, 20, P20 and P10 Using a Built-In Recorder</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-essential-know-how-for-video-filter-integration-on-digital-platforms/"><u>2024 Approved  Essential Know-How for Video Filter Integration on Digital Platforms</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-typing-managing-filter-keys-on-pcs/"><u>Elevate Your Typing: Managing Filter Keys on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-windows-safe-slumber-techniques/"><u>Understanding Window's Safe Slumber Techniques</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-10-open-source-video-editing-software-options-for-linux-for-2024/"><u>New 10 Open-Source Video Editing Software Options for Linux for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/boosting-performance-trimming-high-memorycpu-usage-by-news-and-interests-apps-on-windows/"><u>Boosting Performance: Trimming High Memory/CPU Usage by News & Interests Apps on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-the-code-of-windowsstore-folder-protection/"><u>Breaking the Code of WindowsStore Folder Protection</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-get-your-pc-to-recognize-razer-devices-again/"><u>How to Get Your PC to Recognize Razer Devices Again</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-power-indicator-designs-for-win-users/"><u>Masterful Power Indicator Designs for Win Users</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-likes-vs-ticks-can-likes-outshine-tiktoks-popularity-for-2024/"><u>[New] Likes Vs. Ticks  Can Likes Outshine TikTok's Popularity for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-find-your-custom-box-top-10-online-stores-offering-tailored-packaging/"><u>[New] Find Your Custom Box  Top 10 Online Stores Offering Tailored Packaging</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-xiaomi-redmi-note-12-pro-4g-phone-frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Xiaomi Redmi Note 12 Pro 4G Phone FRP Lock</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/instant-impact-or-rapid-rhythm-youtube-shorts-vs-tiktok-for-quick-content/"><u>Instant Impact or Rapid Rhythm  YouTube Shorts Vs. TikTok for Quick Content</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-the-xbox-stranded-glitch-on-win11/"><u>Overcoming the Xbox Stranded Glitch on Win11</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-the-risks-of-keygen-malware-in-modern-windows-systems/"><u>Understanding the Risks of Keygen Malware in Modern Windows Systems</u></a></li>
</ul></div>
