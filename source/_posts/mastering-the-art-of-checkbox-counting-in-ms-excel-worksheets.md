---
title: Mastering the Art of Checkbox Counting in MS Excel Worksheets
date: 2024-08-28T00:48:06.558Z
updated: 2024-08-29T00:48:06.558Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/microsoft_excel_hero_1200x675.jpg
---

## Mastering the Art of Checkbox Counting in MS Excel Worksheets

### Quick Links

* [Designate Cells for the Checkbox Controls](https://android-frp.techidaily.com/ultimate-guide-from-realme-gt-neo-5-frp-bypass-by-drfone-android/)
* [Use the COUNTIF Function](https://some-tips.techidaily.com/updated-the-metaverse-unraveled-explore-these-6-vivid-models/)
* [Optional: Hide the Result Cells](https://fox-friendly.techidaily.com/greatest-copyright-free-pubg-image-anthology/)

### Key Takeaways

 First, designate cells to hold "True" or "False" results based on the state of each checkbox. You can then count up the checkboxes by using Excel's COUNTIF function to count the number of "TRUE" results.

 If you [use Excel to create a checklist](https://android-location-track.techidaily.com/3-solutions-to-find-your-poco-f5-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/), you may want to count the number of checked or unchecked boxes. With a simple formula, you can tally them in a cell that adjusts as more boxes are marked or unmarked.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Designate Cells for the Checkbox Controls

 When you check a box in Excel, the result of the check is True. For unchecked boxes, the result is False.

 So, before you create the formula to [count your checkboxes](https://blog-min.techidaily.com/how-to-rescue-lost-contacts-from-huawei-nova-y91-by-fonelab-android-recover-contacts/), you'll need to designate cells to hold the True or False result. You'll then use that result in your formula.

Related: [How to Count Checkboxes in Google Sheets](https://blog-min.techidaily.com/how-to-rescue-lost-contacts-from-huawei-nova-y91-by-fonelab-android-recover-contacts/) 

 Right-click your first checkbox and select "Format Control" in the shortcut menu.

![Format Control in the shortcut menu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/FormatControl-ExcelCountCheckboxes.png) 

 In the Format Control box that appears, go to the Control tab. In the Cell Link box, enter the cell where you want to display the True or False result. You can also select the cell in your sheet to populate that box.

 Click "OK" to save the change.

![Cell reference in the Cell Link box](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/CellLink-ExcelCountCheckboxes.png) 

 Follow the same process for the other checkboxes that you want to count in your sheet.

 You should then see the True result for checked boxes and False for unchecked boxes in the designated cells.

![Checked boxes displaying True](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/CheckedTrue-ExcelCountCheckboxes.png) 

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
 If you set the default Value for the checkbox as Unchecked, it won't display False unless you check the box and then uncheck it.

##  Use the COUNTIF Function

 Once you [have the checkboxes set up](https://techidaily.com/is-your-oppo-a58-4g-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/), go to the cell where you want to display the count.

 You'll then enter a formula for the [COUNTIF function](https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-redmi-note-12t-pro-for-free-drfone-by-drfone-virtual-android/) that displays a count for either True or False, depending on which you want to count.

Related: [How to Use the COUNT Function in Microsoft Excel](https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-redmi-note-12t-pro-for-free-drfone-by-drfone-virtual-android/) 

 As an example, we are counting the checked boxes in cells B2 through B11 using their results in cells C2 through C11\. So, you'll use the result cells in your formula as follows:

=COUNTIF(C2:C11,TRUE)

 You can see that we received the correct count of 6 for our checked boxes.

![COUNTIF True for checked boxes](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/COUNTIFTrue-ExcelCountCheckboxes.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To count the unchecked boxes instead, simply replace True with False in the formula:

=COUNTIF(C2:C11,FALSE)

![COUNTIF False for unchecked boxes](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/COUNTIFFalse-ExcelCountCheckboxes.png) 

 If you set the default Value for the checkbox as Mixed, it will not count toward the True or False result. It [displays as #N/A](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/) until the box is checked or unchecked.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Optional: Hide the Result Cells

 It may not be ideal to display the True and False results in your sheet. It might be distracting from the data you want to see.

 If you have the results in a single column or row without any other data you need, you can simply [hide the column or row](https://apple-account.techidaily.com/in-2024-tips-and-tricks-for-apple-id-locked-issue-from-apple-iphone-6-by-drfone-ios/).

Related: [How to Hide Cells, Rows, and Columns in Excel](https://apple-account.techidaily.com/in-2024-tips-and-tricks-for-apple-id-locked-issue-from-apple-iphone-6-by-drfone-ios/) 

 Right-click the column or row and pick "Hide" in the shortcut menu.

![Hide in the column menu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/HideColumn-ExcelCountCheckboxes.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 The formula for the checked or unchecked boxes will work just the same with the results hidden.

![Results column hidden in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/HiddenColumn-ExcelCountCheckboxes.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
 Counting the number of completed tasks, incomplete orders, or something similar is easy to do with the COUNTIF function and a bit of checkbox manipulation in Excel.

 For more, check out how to [use checkboxes in your Word documents](https://instagram-clips.techidaily.com/updated-spark-dialogue-with-personalized-and-creative-story-inquiries/) too.

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-steps-to-record-your-gameplay-on-a-nintendo-switch/"><u>[New] In 2024, Steps to Record Your Gameplay on a Nintendo Switch</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-industry-standard-guide-implementing-stopwatches-in-video-streaming-software-for-2024/"><u>[New] Industry Standard Guide  Implementing Stopwatches in Video Streaming Software for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-techniques-for-gh-video-logging/"><u>[New] Techniques for GH Video Logging</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-mov-file-keeping-hacks-for-new-win-11-users/"><u>[Updated] 2024 Approved  .MOV File Keeping Hacks for New Win 11 Users</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-discovering-the-best-screen-recording-programs-for-win11-for-2024/"><u>[Updated] Discovering the Best Screen Recording Programs for Win11 for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-fb-cover-videos-strategies-for-maximum-impact/"><u>[Updated] In 2024, FB Cover Videos  Strategies for Maximum Impact</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-streamlining-video-calls-leveraging-zoom-on-windows-10-pcs/"><u>[Updated] In 2024, Streamlining Video Calls  Leveraging Zoom on Windows 10 PCs</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-techniques-for-perfect-chroma-key-compositing/"><u>[Updated] Techniques for Perfect Chroma Key Compositing</u></a></li>
<li><a href="https://buynow-info.techidaily.com/2024s-high-performance-cell-signal-improvers-find-the-best-one-to-upgrade-your-connection/"><u>2024'S High-Performance Cell Signal Improvers: Find the Best One to Upgrade Your Connection</u></a></li>
<li><a href="https://extra-information.techidaily.com/accurate-ranking-top-10-gratuitous-srt-file-tools/"><u>Accurate Ranking  Top 10 Gratuitous Srt File Tools</u></a></li>
<li><a href="https://location-social.techidaily.com/does-find-my-friends-work-on-vivo-y27s-drfone-by-drfone-virtual-android/"><u>Does find my friends work on Vivo Y27s | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-data-handling-enabledisable-ntfs-compression-in-win11/"><u>Efficient Data Handling: Enable/Disable NTFS Compression in Win11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/elevating-your-itunes-media-library-with-recordings-for-2024/"><u>Elevating Your iTunes Media Library with Recordings for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/essential-non-windows-tools-for-quick-and-precise-screen-sniping-techniques/"><u>Essential Non-Windows Tools For Quick and Precise Screen Sniping Techniques</u></a></li>
<li><a href="https://win11.techidaily.com/essential-windows-cmd-shortcuts-for-streamlined-workflow/"><u>Essential Windows Cmd Shortcuts for Streamlined Workflow</u></a></li>
<li><a href="https://extra-information.techidaily.com/expert-insights-leveraging-inshot-for-editing-devices/"><u>Expert Insights  Leveraging Inshot for Editing Devices</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-latest-upgrade-for-your-intel-ac-9560-wireless-card-software/"><u>Get the Latest Upgrade for Your Intel AC 9560 Wireless Card Software</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-official-csr-bluetooth-device-driver-here/"><u>Get Your Official CSR Bluetooth Device Driver Here</u></a></li>
<li><a href="https://win11.techidaily.com/guidelines-for-restoring-lost-wifi-connections-on-windows/"><u>Guidelines for Restoring Lost WiFi Connections on Windows</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-correct-the-non-operational-windows-search-error/"><u>How to Correct the Non-Operational Windows Search Error</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-find-ispoofer-pro-activation-key-on-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>How to Find iSpoofer Pro Activation Key On Motorola Moto E13? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-unlock-the-lock-screen-on-my-samsung-by-drfone-android-unlock-android-unlock/"><u>How to Unlock the Lock Screen on my Samsung</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-y200-phone-without-pin-by-drfone-android/"><u>How to Unlock Vivo Y200 Phone without PIN</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-use-system-restore-to-revert-windows/"><u>How to Use System Restore to Revert Windows</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-xiaomi-civi-3-disney-100th-anniversary-edition-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Xiaomi Civi 3 Disney 100th Anniversary Edition PC | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-scripting-striking-film-epilogues/"><u>In 2024, Scripting Striking Film Epilogues</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-top-10-professional-360-degree-cameras-2023-update/"><u>In 2024, Top 10 Professional 360 Degree Cameras -2023 Update</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-lava-yuva-2-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Lava Yuva 2 Pro | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/index-of-varied-photographic-and-videography-instruments-for-2024/"><u>Index of Varied Photographic and Videography Instruments for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/installation-procedures-windows-11-and-vmware-workstation-17/"><u>Installation Procedures: Windows 11 & VMWare Workstation 17</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-textbooks-top-8-effective-learning-techniques-for-windows/"><u>Master the Textbooks: Top 8 Effective Learning Techniques for Windows</u></a></li>
<li><a href="https://sound-issues.techidaily.com/no-more-silent-world-restoring-sounds-to-cyberpunk-2077-on-windows-11/"><u>No More Silent World: Restoring Sounds to Cyberpunk 2077 on Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/read-this-guide-to-find-a-reliable-alternative-to-fake-gps-on-motorola-edge-40-neo-drfone-by-drfone-virtual-android/"><u>Read This Guide to Find a Reliable Alternative to Fake GPS On Motorola Edge 40 Neo | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/rejuvenate-old-pcs-with-windows-11-to-go-and-rufus-tutorial/"><u>Rejuvenate Old PCs with Windows 11, To Go & Rufus Tutorial</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reliable-user-guide-to-fix-samsung-galaxy-s23-ultra-running-slow-and-freezing-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reliable User Guide to Fix Samsung Galaxy S23 Ultra Running Slow and Freezing | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-error-cant-share-desktop-across-screens/"><u>Resolving Error: Can’t Share Desktop Across Screens</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-league-disconnects-in-windows-os/"><u>Resolving League Disconnects in Windows OS</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-multi-zip-operations-on-windows-systems/"><u>Seamless Multi-Zip Operations on Windows Systems</u></a></li>
<li><a href="https://win11.techidaily.com/seamless-prime-viewing-fixing-windows-11-audio-subtitle-discrepancies/"><u>Seamless Prime Viewing: Fixing Windows 11 Audio-Subtitle Discrepancies</u></a></li>
<li><a href="https://win11.techidaily.com/securing-steam-readwrite-success-in-os-x/"><u>Securing Steam Read/Write Success in OS X</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-for-function-keys-not-adjusting-display-brighness-on-win-11/"><u>Solutions for Function Keys Not Adjusting Display Brighness on Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-the-steam-lag-in-windows-11-gaming-environment/"><u>Solutions to the Steam Lag in Windows 11 Gaming Environment</u></a></li>
<li><a href="https://win11.techidaily.com/swiftly-salvaging-deleted-files-from-your-system/"><u>Swiftly Salvaging Deleted Files From Your System</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-clearing-black-pixels-in-winsteam/"><u>Techniques for Clearing Black Pixels in WinSteam</u></a></li>
<li><a href="https://win11.techidaily.com/the-obsidian-edge-cutting-edge-visual-notes-methodology/"><u>The Obsidian Edge: Cutting-Edge Visual Notes Methodology</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-guide-to-buying-windows-11-keys/"><u>The Ultimate Guide to Buying Windows 11 Keys</u></a></li>
<li><a href="https://win11.techidaily.com/top-5-solutions-for-overcoming-hypervisorbsod-in-windows/"><u>Top 5 Solutions for Overcoming HYPERVISOR_BSOD in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/transforming-windows-11-select-6-must-install-android-apps/"><u>Transforming Windows 11: Select 6 Must-Install Android Apps</u></a></li>
<li><a href="https://win11.techidaily.com/unleashing-your-potential-with-top-notch-fps-counters-for-windows-11-gamers/"><u>Unleashing Your Potential with Top-Notch FPS Counters for Windows 11 Gamers</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/unlock-instagram-speed-mastering-video-and-likes/"><u>Unlock Instagram Speed - Mastering Video and Likes</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-pc-potential-top-tips-to-troubleshoot-broken-keyboard-commands-in-windows/"><u>Unlocking PC Potential: Top Tips to Troubleshoot Broken Keyboard Commands in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/unplugging-issues-keeping-usbs-active-on-windows-11/"><u>Unplugging Issues: Keeping USBs Active on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-character-viewer-in-windows-11/"><u>Unveiling the Character Viewer in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/what-to-do-if-googles-nearby-share-app-is-not-working-on-windows/"><u>What to Do if Google’s Nearby Share App Is Not Working on Windows</u></a></li>
</ul></div>
