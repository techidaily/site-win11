---
title: Control Data Cost Monitoring on Your Wi-Fi Network with Win11
date: 2024-11-30T16:46:19.325Z
updated: 2024-12-07T00:19:39.339Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Control Data Cost Monitoring on Your Wi-Fi Network with Win11
excerpt: This Article Describes Control Data Cost Monitoring on Your Wi-Fi Network with Win11
keywords: Wi-Fi Cost Tracking,Wi-Fi Expense Control,Win11 Wi-Fi Monitoring,Wi-Fi Data Analysis,Wi-Fi Network Savings,Win11 Security Audit,Wi-Fi Management Tools
thumbnail: https://thmb.techidaily.com/359889cca1fac1d0cab50a3e170aa122469e4b901fffff3859c0a0ef7a4f048d.jpg
---

## Control Data Cost Monitoring on Your Wi-Fi Network with Win11

 If you're using a capped internet connection, such as a mobile hotspot, you'd want to limit your Windows PC's background data usage. That way, you ensure that background processes, like OneDrive or Steam, do not use up all your data while your computer's on.

 But how do you configure your PC to treat a Wi-Fi network as a metered or unmetered connection? Luckily, Windows 11 provides a couple of different ways to enable or disable metered connections for a Wi-Fi network. Let's go over both of them in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. Enable or Disable Metered Connections for a Wi-Fi Network Using the Settings App

 The**Network & internet** section in the Settings app serves as a central location for all the network-related settings on Windows. You can visit that section to quickly enable or disable a metered connection for your computer's Wi-Fi network. Here are the steps for the same.

1. Open the**Start menu** and click the**gear-shaped icon** to[launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Select**Network & internet** from the left sidebar.
3. Click on**Wi-Fi** from the right pane.
4. Go to**Manage known networks** .
5. Select the network you want to configure.
6. Enable the toggle next to**Metered connection** to set the Wi-Fi network as metered. If you want to set the network as an unmetered connection, disable the toggle.  
![Enable or Disable Metered Connection in Windows 11 Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/enable-or-disable-metered-connection-in-windows-11-using-settings-app.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Note that you'll have to repeat the above steps for each Wi-Fi network separately. Following that, Windows will remember your network preferences.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Enable or Disable Wi-Fi Metered Connections via the Command Prompt

 If you're a power user who prefers to make system changes with a command-line tool, you can use the[Command Prompt](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) to enable or disable metered connection for a Wi-Fi network on Windows. Here's how you can go about it.

1. Right-click the**Start icon** or use the**Win + X** keyboard shortcut to open the Power User menu.
2. Select**Terminal (Admin)** from the list.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. In the terminal window, type the following command and press**Enter** to view a list of network profiles on your computer:  
`netsh wlan show profiles`  
![Network Profiles in Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/network-profiles-in-windows.jpg)
5. Note down the Wi-Fi network name for which you want to enable or disable the metered connection option.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

6. Next, run the following command to determine whether your connection is metered or unmetered.  
`netsh wlan show profile name="Wi-Fi Name"`  
 Make sure you replace**Wi-Fi Name** in the above command with the actual name of the network noted in the last step.
7. Under the**Cost settings** section, check the value next to the**Cost** field. If it reads**Fixed** , the network is set as a metered connection. Conversely, if it reads**Unrestricted** , it is designated as an unmetered connection.
8. Type the following command and press**Enter** to mark the network as a metered connection.  
`netsh wlan set profileparameter name="Wi-Fi Name" cost=Fixed`  
![Disable Metered Connection in Windows 11 Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/disable-metered-connection-in-windows-11-using-command-prompt.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Wy0uYNNdMDM?si=5ir7EHlr0CkpcYOT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you want to disable the metered connection for a network, run the following command instead.

`netsh wlan set profileparameter name="Wi-Fi Name" cost=Unrestricted`

 The Command Prompt should display a message once the network profile is updated. After that, you can close the terminal window.

 Aside from the above, you can view important details about your Wi-Fi network using the Command Prompt. If you're interested in doing that, check our guide on[the best commands to manage wireless networks on Windows](https://www.makeuseof.com/tag/commands-manage-wireless-networks-windows/) .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mHFtYJppXFk?si=ylFaAT4nXqCmlV8F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Efficiently Manage Your Data With Metered Connection

 Enabling or disabling the metered connection option for Wi-Fi networks in Windows is relatively simple, regardless of the method you use.

 If you have a limited data plan, you can also set a data usage limit for your Wi-Fi connection. This way, Windows will notify you when you approach the set data limit.

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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-gauging-storage-capacity-for-full-length-films/"><u>[New] 2024 Approved Gauging Storage Capacity for Full-Length Films</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-capture-the-crash-expert-surfer-cameras-review/"><u>[New] Capture the Crash - Expert Surfer Cameras Review</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-editing-excellence-the-ultimate-guide-to-top-notebooks/"><u>[New] Editing Excellence The Ultimate Guide to Top Notebooks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-google-collages-how-to-achieve-it-in-a-blink-of-an-eye/"><u>[New] In 2024, Google Collages How to Achieve It in A Blink of an Eye</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-tutorial-unmask-your-youtube-audience/"><u>[Updated] In 2024, Tutorial Unmask Your YouTube Audience</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-revealed-the-best-thumbnail-dimensions-for-maximum-viewership-growth/"><u>[Updated] Revealed! The Best Thumbnail Dimensions for Maximum Viewership Growth</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-mastering-morphvox-transformation-top-techniques-revealed/"><u>2024 Approved Mastering MorphVOX Transformation Top Techniques Revealed</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-any-vivo-x-fold-2-phone-password-using-emergency-call-by-drfone-android/"><u>In 2024, How To Unlock Any Vivo X Fold 2 Phone Password Using Emergency Call</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-the-linux-command-landscape-in-windows/"><u>Navigating the Linux Command Landscape in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/optimal-icon-sizes-on-windows-11-desktop/"><u>Optimal Icon Sizes on Windows 11 Desktop</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-utorrent-connection-failures-in-microsoft-systems/"><u>Overcoming uTorrent Connection Failures in Microsoft Systems</u></a></li>
<li><a href="https://tech-revival.techidaily.com/pioneering-the-next-wave-of-ai-dialogue-systems-insights-into-post-chatgpt-generative-innovations/"><u>Pioneering the Next Wave of AI Dialogue Systems: Insights Into Post-ChatGPT Generative Innovations</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-machine-top-winning-windows-2023-apps/"><u>Transform Your Machine: Top Winning Windows 2023 Apps</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-hidden-secrets-top-strategies-to-fix-lost-folders/"><u>Unlocking Hidden Secrets: Top Strategies to Fix Lost Folders</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-the-mystery-of-hidden-system-tools-in-os/"><u>Unlocking the Mystery of Hidden System Tools in OS</u></a></li>
<li><a href="https://win11.techidaily.com/windows-11s-restricted-editions-an-analysis-of-benefits/"><u>Windows 11’S Restricted Editions: An Analysis of Benefits</u></a></li>
</ul></div>

