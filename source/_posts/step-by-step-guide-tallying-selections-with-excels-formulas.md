---
title: "Step-by-Step Guide: Tallying Selections with Excel's Formulas"
date: 2024-08-28T00:49:47.435Z
updated: 2024-08-29T00:49:47.435Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/a13a2db3e926587257ddbddaa8e6b2d5c7f6b5a5b0f13a0f229c89b6858d4777.jpg
---

## Step-by-Step Guide: Tallying Selections with Excel's Formulas

### Quick Links

* [Designate Cells for the Checkbox Controls](https://android-frp.techidaily.com/ultimate-guide-from-realme-gt-neo-5-frp-bypass-by-drfone-android/)
* [Use the COUNTIF Function](https://some-tips.techidaily.com/updated-the-metaverse-unraveled-explore-these-6-vivid-models/)
* [Optional: Hide the Result Cells](https://fox-friendly.techidaily.com/greatest-copyright-free-pubg-image-anthology/)

### Key Takeaways

 First, designate cells to hold "True" or "False" results based on the state of each checkbox. You can then count up the checkboxes by using Excel's COUNTIF function to count the number of "TRUE" results.

 If you [use Excel to create a checklist](https://android-location-track.techidaily.com/3-solutions-to-find-your-poco-f5-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/), you may want to count the number of checked or unchecked boxes. With a simple formula, you can tally them in a cell that adjusts as more boxes are marked or unmarked.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
##  Designate Cells for the Checkbox Controls

 When you check a box in Excel, the result of the check is True. For unchecked boxes, the result is False.

 So, before you create the formula to [count your checkboxes](https://blog-min.techidaily.com/how-to-rescue-lost-contacts-from-huawei-nova-y91-by-fonelab-android-recover-contacts/), you'll need to designate cells to hold the True or False result. You'll then use that result in your formula.

Related: [How to Count Checkboxes in Google Sheets](https://blog-min.techidaily.com/how-to-rescue-lost-contacts-from-huawei-nova-y91-by-fonelab-android-recover-contacts/) 

 Right-click your first checkbox and select "Format Control" in the shortcut menu.

![Format Control in the shortcut menu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/FormatControl-ExcelCountCheckboxes.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599952&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>Epubor Ultimate for Mac:Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->
 In the Format Control box that appears, go to the Control tab. In the Cell Link box, enter the cell where you want to display the True or False result. You can also select the cell in your sheet to populate that box.

 Click "OK" to save the change.

![Cell reference in the Cell Link box](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/CellLink-ExcelCountCheckboxes.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2019/10/Project-Manager-version-3-1600x900-768x419.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
 Follow the same process for the other checkboxes that you want to count in your sheet.

 You should then see the True result for checked boxes and False for unchecked boxes in the designated cells.

![Checked boxes displaying True](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/CheckedTrue-ExcelCountCheckboxes.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
 If you set the default Value for the checkbox as Unchecked, it won't display False unless you check the box and then uncheck it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
##  Use the COUNTIF Function

 Once you [have the checkboxes set up](https://techidaily.com/is-your-oppo-a58-4g-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/), go to the cell where you want to display the count.

 You'll then enter a formula for the [COUNTIF function](https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-redmi-note-12t-pro-for-free-drfone-by-drfone-virtual-android/) that displays a count for either True or False, depending on which you want to count.

Related: [How to Use the COUNT Function in Microsoft Excel](https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-redmi-note-12t-pro-for-free-drfone-by-drfone-virtual-android/) 

 As an example, we are counting the checked boxes in cells B2 through B11 using their results in cells C2 through C11\. So, you'll use the result cells in your formula as follows:

=COUNTIF(C2:C11,TRUE)

 You can see that we received the correct count of 6 for our checked boxes.

![COUNTIF True for checked boxes](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/COUNTIFTrue-ExcelCountCheckboxes.png) 

 To count the unchecked boxes instead, simply replace True with False in the formula:

=COUNTIF(C2:C11,FALSE)

![COUNTIF False for unchecked boxes](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/COUNTIFFalse-ExcelCountCheckboxes.png) 

 If you set the default Value for the checkbox as Mixed, it will not count toward the True or False result. It [displays as #N/A](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/) until the box is checked or unchecked.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
##  Optional: Hide the Result Cells

 It may not be ideal to display the True and False results in your sheet. It might be distracting from the data you want to see.

 If you have the results in a single column or row without any other data you need, you can simply [hide the column or row](https://apple-account.techidaily.com/in-2024-tips-and-tricks-for-apple-id-locked-issue-from-apple-iphone-6-by-drfone-ios/).

Related: [How to Hide Cells, Rows, and Columns in Excel](https://apple-account.techidaily.com/in-2024-tips-and-tricks-for-apple-id-locked-issue-from-apple-iphone-6-by-drfone-ios/) 

 Right-click the column or row and pick "Hide" in the shortcut menu.

![Hide in the column menu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/HideColumn-ExcelCountCheckboxes.png) 

 The formula for the checked or unchecked boxes will work just the same with the results hidden.

![Results column hidden in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/HiddenColumn-ExcelCountCheckboxes.png) 

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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-filtering-the-truth-in-your-insta-network/"><u>[New] 2024 Approved  Filtering the Truth in Your Insta Network</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-enhancing-your-stream-5-key-techniques-for-gamers-for-2024/"><u>[New] Enhancing Your Stream  5 Key Techniques for Gamers for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-hero-session-evolution-four-to-five-for-2024/"><u>[New] Hero Session Evolution  Four to Five for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-spark-your-imagination-with-14-stunning-text-animations/"><u>[New] Spark Your Imagination with 14 Stunning Text Animations</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-anime-emojis-and-animations-sprucing-up-your-tiktok-videos/"><u>[Updated] In 2024, Anime Emojis & Animations  Sprucing Up Your TikTok Videos</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-seamless-video-production-leveraging-windows-movie-maker-on-windows-8/"><u>2024 Approved  Seamless Video Production  Leveraging Windows Movie Maker on Windows 8</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/3-easy-ways-to-factory-reset-a-locked-apple-iphone-15-plus-without-itunes-by-drfone-ios/"><u>3 Easy Ways to Factory Reset a Locked Apple iPhone 15 Plus Without iTunes</u></a></li>
<li><a href="https://fox-access.techidaily.com/boosting-video-conference-quality-a-guide-to-using-zoom-and-skype-for-2024/"><u>Boosting Video Conference Quality  A Guide to Using ZOOM & SKYPE for 2024</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/bypassing-phone-lines-for-internet-top-alternative-approaches/"><u>Bypassing Phone Lines for Internet: Top Alternative Approaches</u></a></li>
<li><a href="https://win11.techidaily.com/devhome-demystified-guiding-you-through-win11-upgrades/"><u>DevHome Demystified: Guiding You Through Win11 Upgrades</u></a></li>
<li><a href="https://win11.techidaily.com/digital-dots-top-8-window-friendly-note-apps/"><u>Digital Dots: Top 8 Window-Friendly Note Apps</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-web-interaction-enable-mouse-gestures-in-microsofts-edge-browser/"><u>Elevate Your Web Interaction: Enable Mouse Gestures in Microsoft's Edge Browser</u></a></li>
<li><a href="https://win11.techidaily.com/eliminating-ms-resouce-text-error-on-windows-11/"><u>Eliminating Ms-Resouce Text Error on Windows 11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/expert-solutions-overcoming-dauntless-game-crashes-on-pc-machines/"><u>Expert Solutions: Overcoming Dauntless Game Crashes on PC Machines</u></a></li>
<li><a href="https://win11.techidaily.com/fine-tuning-startup-functionality-for-a-smooth-windows-11-launch/"><u>Fine-Tuning Startup Functionality for a Smooth Windows 11 Launch</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-iphoneipad-photo-import-error-a-compreayers-approach-on-w11/"><u>Fixing iPhone/iPad Photo Import Error: A Compreayer’s Approach on W11</u></a></li>
<li><a href="https://win11.techidaily.com/halt-unprompted-gaming-suggestions-on-windows-11/"><u>Halt Unprompted Gaming Suggestions on Windows 11</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ss-youtubes-power-25-steps-to-prominence-and-recognition-for-2024/"><u>Harness YouTube's Power  25 Steps to Prominence and Recognition for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-discord-installation-has-failed-error-on-windows-11-and-11/"><u>How to Fix the Discord “Installation Has Failed” Error on Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-vmware-bsod-error-on-windows-11/"><u>How to Fix VMware BSOD Error on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-repair-systemsettings-glitches-in-win11/"><u>How to Repair SystemSettings Glitches in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-revert-windows-11s-search-bar-to-a-search-icon/"><u>How to Revert Windows 11'S Search Bar to a Search Icon</u></a></li>
<li><a href="https://win11.techidaily.com/improve-visual-identification-displaying-this-pc-icon/"><u>Improve Visual Identification: Displaying 'This PC' Icon</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-economical-vr-headsets-from-the-east/"><u>In 2024, Economical VR Headsets From the East</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-motorola-moto-g23-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For Motorola Moto G23 Phones</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-itel-s23-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Itel S23 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/introducing-ed-inspired-visuals-to-windows/"><u>Introducing Ed-Inspired Visuals to Windows</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/inverter-box-by-jackery-an-in-depth-review-on-its-integrated-mains-outlet-feature/"><u>Inverter Box by Jackery: An In-Depth Review on Its Integrated Mains Outlet Feature</u></a></li>
<li><a href="https://win11.techidaily.com/master-compatibility-fixes-without-the-troubleshooter/"><u>Master Compatibility Fixes Without the Troubleshooter</u></a></li>
<li><a href="https://win11.techidaily.com/master-the-books-unlocking-potential-with-7-top-study-methods-on-a-windowed-computer/"><u>Master the Books: Unlocking Potential with 7 Top Study Methods on a Windowed Computer</u></a></li>
<li><a href="https://win11.techidaily.com/master-your-new-window-11-the-best-modifications-for-an-optimized-experience/"><u>Master Your New Window 11: The Best Modifications for an Optimized Experience</u></a></li>
<li><a href="https://win11.techidaily.com/masterful-remedies-for-windows-app-issues-7-steps-to-success/"><u>Masterful Remedies for Windows App Issues, 7 Steps to Success</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-microsoft-powertoys-in-win11-setup/"><u>Mastering Microsoft PowerToys in Win11 Setup</u></a></li>
<li><a href="https://win11.techidaily.com/maximize-productivity-with-sticky-notes-in-w11w10/"><u>Maximize Productivity with Sticky Notes in W11/W10</u></a></li>
<li><a href="https://win11.techidaily.com/mitigating-excessive-heat-on-windows-11-devices/"><u>Mitigating Excessive Heat on Windows 11 Devices</u></a></li>
<li><a href="https://win11.techidaily.com/navigate-back-to-your-copilot-in-ws11-spacecraft/"><u>Navigate Back to Your Copilot in WS11 Spacecraft</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-a-new-era-of-interactive-technology-between-pc-and-galaxy/"><u>Navigating a New Era of Interactive Technology Between PC & Galaxy</u></a></li>
<li><a href="https://win11.techidaily.com/optimizing-clipboard-utility-in-windows-11-pcs/"><u>Optimizing Clipboard Utility in Windows 11 PCs</u></a></li>
<li><a href="https://win11.techidaily.com/personalize-desk-view-including-this-pc-on-the-screen/"><u>Personalize Desk View: Including 'This PC' On the Screen</u></a></li>
<li><a href="https://win11.techidaily.com/quick-fixes-for-error-0x80041015-in-ms-word-and-excel/"><u>Quick Fixes for Error 0X80041015 in MS Word & Excel</u></a></li>
<li><a href="https://win11.techidaily.com/reclaiming-your-desktop-icon-order/"><u>Reclaiming Your Desktop Icon Order</u></a></li>
<li><a href="https://win11.techidaily.com/rectifying-fabricated-device-specification-error-in-win-11/"><u>Rectifying Fabricated Device Specification Error in Win 11</u></a></li>
<li><a href="https://win11.techidaily.com/regaining-access-fixing-frozen-windows-terminals-quickly/"><u>Regaining Access: Fixing Frozen Windows Terminals Quickly</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/reset-itunes-backup-password-of-apple-iphone-7-prevention-and-solution-drfone-by-drfone-ios/"><u>Reset iTunes Backup Password Of Apple iPhone 7 Prevention & Solution | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-windows-1011-uninstalls-that-fail/"><u>Resolving Windows 10/11 Uninstalls That Fail</u></a></li>
<li><a href="https://win11.techidaily.com/restoring-functionality-to-your-corrupted-windows-11-trash/"><u>Restoring Functionality to Your Corrupted WIndows 11 Trash</u></a></li>
<li><a href="https://win11.techidaily.com/solving-the-puzzle-of-a-unresponsive-discord-overlay-in-windows/"><u>Solving the Puzzle of a Unresponsive Discord Overlay in Windows</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-tecno-spark-10c-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Tecno Spark 10C FRP</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-tweak-indexer-in-windows/"><u>Steps to Tweak Indexer in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/streamline-workflows-with-windows-11-multitasking-tips/"><u>Streamline Workflows with Windows 11 Multitasking Tips</u></a></li>
<li><a href="https://win11.techidaily.com/streamlined-sound-system-upgrade-with-atmos-on-win-1011/"><u>Streamlined Sound System Upgrade with Atmos on Win 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/streamlining-sign-in-with-windows-hello-biometrics/"><u>Streamlining Sign-In with Windows Hello Biometrics</u></a></li>
<li><a href="https://win11.techidaily.com/tapping-into-hidden-taskbar-explorer-of-windows-11/"><u>Tapping Into Hidden Taskbar Explorer of Windows 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-7-phone-number-locators-to-track-zte-axon-40-lite-location-drfone-by-drfone-virtual-android/"><u>Top 7 Phone Number Locators To Track ZTE Axon 40 Lite Location | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/top-factors-for-choosing-windows-10-over-the-latest-operating-system-win11/"><u>Top Factors for Choosing Windows 10 over the Latest Operating System - Win11</u></a></li>
<li><a href="https://article-posts.techidaily.com/ultimate-zooid-design-starter-packs-for-2024/"><u>Ultimate Zooid Design Starter Packs for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unblock-selecthighlight-capabilities-in-windows-pdf-viewer/"><u>Unblock Select/Highlight Capabilities in Windows' PDF Viewer</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-app-execution-variants-and-usage/"><u>Understanding App Execution Variants & Usage</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-mystery-of-vanishing-printmanagement-in-windows/"><u>Unraveling the Mystery of Vanishing 'Printmanagement' In Windows</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-simple-guide-to-fcp-x-how-to-add-effects-in-3-steps/"><u>Updated Simple Guide to FCP X How To Add Effects in 3 Steps</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/webcam-mastery-creating-videos-on-macbook/"><u>Webcam Mastery  Creating Videos on MacBook</u></a></li>
</ul></div>
