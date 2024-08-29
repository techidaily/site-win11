---
title: "Unifying Data Points: Merging Text From Various Excel Cells Into a Single Cell"
date: 2024-08-28T00:49:38.822Z
updated: 2024-08-29T00:49:38.822Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/a7b063e2c5f1e938dc6e32e2ce85c52239dfc8e7739a5c0ead2c07ab91e735b6.png
---

## Unifying Data Points: Merging Text From Various Excel Cells Into a Single Cell

If you have a large worksheet in an Excel workbook in which you need to combine text from multiple cells, you can breathe a sigh of relief because you don't have to retype all that text. You can easily concatenate the text.

 Concatenate is simply a fancy way ot saying "to combine" or "to join together" and there is a special CONCATENATE function in Excel to do this. This function allows you to combine text from different cells into one cell. For example, we have a worksheet containing names and contact information. We want to [combine the Last Name and First Name columns](https://article-helps.techidaily.com/updated-2024-approved-elevate-your-drone-game-with-top-tier-lipo-tech/) in each row into the Full Name column.

 To begin, select the first cell that will contain the combined, or concatenated, text. Start typing the function into the cell, starting with an equals sign, as follows.

=CONCATENATE(

![01_entering_concatenate_function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/01_entering_concatenate_function.png) 

 Now, we enter the arguments for the CONCATENATE function, which tell the function which cells to combine. We want to combine the first two columns, with the First Name (column B) first and then the Last Name (column A). So, our two arguments for the function will be B2 and A2.

 There are two ways you can enter the arguments. First, you can type the cell references, separated by commas, after the opening parenthesis and then add a closing parenthesis at the end:

=CONCATENATE(B2,A2)

 You can also click on a cell to enter it into the CONCATENATE function. In our example, after typing the name of the function and the opening parenthesis, we click on the B2 cell, type a comma after B2 in the function, click on the A2 cell, and then type the closing parenthesis after A2 in the function.

 Press Enter when you're done adding the cell references to the function.

![02_adding_cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/02_adding_cells.png) 

 Notice that there is no space in between the first and last name. That's because the CONCATENATE function combines exactly what's in the arguments you give it and nothing more. There is no space after the first name in B2, so no space was added. If you want to add a space, or any other punctuation or details, you must tell the CONCATENATE function to include it.

![03_no_space_in_name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/03_no_space_in_name.png) 

 To add a space between the first and last names, we add a space as another argument to the function, in between the cell references. To do this, we type a space surrounded by double quotes. Make sure the three arguments are separated by commas.

=CONCATENATE(B2," ",A2)

 Press Enter.

![04_adding_space](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/04_adding_space.png) 

 That's better. Now, there is a space between the first and last names.

![05_concatenated_name_with_space](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/05_concatenated_name_with_space.png) 

Related: [How to Automatically Fill Sequential Data into Excel with the Fill Handle](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/) 

 Now, you're probably thinking you have to type that function in every cell in the column or manually copy it to each cell in the column. Actually, you don't. We've got another neat trick that will help you quickly copy the CONCATENATE function to the other cells in the column (or row). Select the cell in which you just entered the CONCATENATE function. The small square on the lower-right corner of the selected is called the fill handle. The fill handle allows you to [quickly copy and paste content to adjacent cells](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/) in the same row or column.

![06_fill_handle](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/06_fill_handle.png) 

 Move your cursor over the fill handle until it turns into a black plus sign and then click and drag it down.

![07_double_clicking_fill_handle](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/07_double_clicking_fill_handle.png) 

 The function you just entered is copied down to the rest of the cells in that column, and the cell references are changed to match the row number for each row.

![08_column_filled](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/08_column_filled.png) 

 You can also concatenate text from multiple cells using the ampersand (&) operator. For example, you can enter `=B2&" "&A2` to get the same result as `=CONCATENATE(B2," ",A2)` . There's no real advantage of using one over the other. although using the ampersand operator results in a shorter entry. However, the CONCATENATE function may be more readable, making it easier to understand what's happening in the cell.

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
<li><a href="https://facebook-video-footage.techidaily.com/updated-accelerate-how-to-swiftly-broadcast-playlists-for-2024/"><u>[Updated] Accelerate  How To Swiftly Broadcast Playlists for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-comprehensive-app-audit-insightful-through-az-capture-for-2024/"><u>[Updated] Comprehensive App Audit  Insightful Through AZ Capture for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-instagram-success-how-to-make-your-videos-captivate-audiences/"><u>[Updated] In 2024, Instagram Success  How to Make Your Videos Captivate Audiences</u></a></li>
<li><a href="https://win11.techidaily.com/easing-up-microsoft-store-accessibility-in-windows-11/"><u>Easing Up Microsoft Store Accessibility in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/efficient-data-handling-enabledisable-ntfs-compression-in-win11/"><u>Efficient Data Handling: Enable/Disable NTFS Compression in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-source-disk-unreadable-issue-in-windows-systems/"><u>Fixing Source Disk Unreadable Issue in Windows Systems</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/gif-geniuses-selection-top-tiktok-conversion-software/"><u>GIF Geniuses' Selection  Top TikTok Conversion Software</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-cure-inactive-usb-ports-and-devices-in-microsoft-os/"><u>How to Cure Inactive USB Ports & Devices in Microsoft OS</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-tecno-spark-20-proplus-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Tecno Spark 20 Pro+ Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-chromes-failed-virus-detected-error-on-windows/"><u>How to Fix Chrome's Failed - Virus Detected Error on Windows</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-apple-id-from-apple-iphone-15-plus-without-password-by-drfone-ios/"><u>How to Remove Apple ID from Apple iPhone 15 Plus without Password?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-forgotten-pin-of-your-xiaomi-redmi-a2plus-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Xiaomi Redmi A2+</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-capturing-virtual-conversations-in-real-time/"><u>In 2024, Capturing Virtual Conversations in Real Time</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-elevate-video-content-with-proven-strategies-for-youtube-shorts-growth/"><u>In 2024, Elevate Video Content with Proven Strategies for YouTube Shorts Growth</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-oppo-a1-5g-to-other-android-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Oppo A1 5G to Other Android Devices? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/jumpstart-your-typing-quick-fixes-to-reduce-lag-in-win-1011/"><u>Jumpstart Your Typing: Quick Fixes to Reduce Lag in WIN 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/making-oculus-quest-compatible-with-windows-vr-systems/"><u>Making Oculus Quest Compatible with Windows VR Systems</u></a></li>
<li><a href="https://win11.techidaily.com/navigating-through-the-maze-of-blue-screen-errors/"><u>Navigating Through the Maze of Blue Screen Errors</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-semaphore-expired-error-on-windows-1011/"><u>Overcoming 'Semaphore Expired Error' On Windows 10/11</u></a></li>
<li><a href="https://win11.techidaily.com/reconciling-microphone-and-xbox-app-on-1011-pcs/"><u>Reconciling Microphone and Xbox App on 10/11 PCs</u></a></li>
<li><a href="https://technical-tips.techidaily.com/rectifying-the-d3dx941dll-file-unavailability-proven-strategies-that-work/"><u>Rectifying the d3dx9_41.dll File Unavailability: Proven Strategies That Work</u></a></li>
<li><a href="https://win11.techidaily.com/reducing-system-idleness-altering-boot-timeout-in-win11/"><u>Reducing System Idleness: Altering Boot Timeout in Win11</u></a></li>
<li><a href="https://win11.techidaily.com/resolve-programming-discrepancies-with-no-troubleshoot-tool/"><u>Resolve Programming Discrepancies with No Troubleshoot Tool</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-error-cant-share-desktop-across-screens/"><u>Resolving Error: Can’t Share Desktop Across Screens</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolving-issues-how-to-prevent-ascent-from-crashing-in-your-web-browser/"><u>Resolving Issues: How to Prevent Ascent From Crashing in Your Web Browser</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-paudio-quirks-on-wos-an-audacity-guide/"><u>Resolving PAudio Quirks on WOS: An Audacity Guide</u></a></li>
<li><a href="https://youtube-data.techidaily.com/wing-video-comment-trails-on-youtube/"><u>Reviewing Video Comment Trails on YouTube</u></a></li>
<li><a href="https://extra-resources.techidaily.com/revolutionizing-image-capture-with-ios-11-updates/"><u>Revolutionizing Image Capture with iOS 11 Updates</u></a></li>
<li><a href="https://win11.techidaily.com/solutions-to-reset-lost-pin-after-a-software-glitch-in-windows-11/"><u>Solutions to Reset Lost PIN After a Software Glitch in Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/steps-to-stabilize-changing-printer-on-desktop-os/"><u>Steps to Stabilize Changing Printer on Desktop OS</u></a></li>
<li><a href="https://win11.techidaily.com/stopping-cmd-appearance-without-prior-notice/"><u>Stopping CMD Appearance Without Prior Notice</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-alleviating-usb-shortage-on-pcs/"><u>Strategies for Alleviating USB Shortage on PCs</u></a></li>
<li><a href="https://win11.techidaily.com/techniques-for-eradicating-onedrive-from-explorer-window/"><u>Techniques for Eradicating OneDrive From Explorer Window</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/the-best-bang-for-your-buck-exploring-performance-and-value-in-the-tp-archiever-a6-ac1200-router/"><u>The Best Bang for Your Buck: Exploring Performance and Value in the TP-Archiever A6 AC1200 Router</u></a></li>
<li><a href="https://win11.techidaily.com/the-ins-and-outs-of-socket-programming-with-python-servers-on-pcs/"><u>The Ins and Outs of Socket Programming with Python Servers on PCs</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-role-of-timestamps-in-content-longevity-and-popularity-for-2024/"><u>The Role of Timestamps in Content Longevity and Popularity for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-exploration-windows-display-breaks/"><u>The Ultimate Exploration: Windows Display Breaks</u></a></li>
<li><a href="https://win11.techidaily.com/the-ultimate-list-of-non-procreate-sketchers-for-pc-users/"><u>The Ultimate List of Non-Procreate Sketchers for PC Users</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-code-word-prefixes-for-software-execution/"><u>Unlocking Code Word Prefixes for Software Execution</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/unlocking-the-full-screen-potential-of-fb-videos-for-2024/"><u>Unlocking the Full Screen Potential of FB Videos for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/unraveling-the-enigma-of-windows-security-errors/"><u>Unraveling the Enigma of Windows Security Errors</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-efficiency-pro-tips-for-scanning-qr-codes-via-windows/"><u>Unveiling Efficiency: Pro Tips for Scanning QR Codes via Windows</u></a></li>
<li><a href="https://win11.techidaily.com/what-is-the-program-compatibility-troubleshooter-on-windows-11-and-how-do-you-use-it/"><u>What Is the Program Compatibility Troubleshooter on Windows 11, and How Do You Use It?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->