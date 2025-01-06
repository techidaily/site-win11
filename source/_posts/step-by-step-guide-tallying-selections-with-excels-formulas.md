---
title: "Step-by-Step Guide: Tallying Selections with Excel's Formulas"
date: 2025-01-04T17:20:15.060Z
updated: 2025-01-06T16:53:57.329Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/a13a2db3e926587257ddbddaa8e6b2d5c7f6b5a5b0f13a0f229c89b6858d4777.jpg
---

## Step-by-Step Guide: Tallying Selections with Excel's Formulas

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [Designate Cells for the Checkbox Controls](https://android-frp.techidaily.com/ultimate-guide-from-realme-gt-neo-5-frp-bypass-by-drfone-android/)
* [Use the COUNTIF Function](https://some-tips.techidaily.com/updated-the-metaverse-unraveled-explore-these-6-vivid-models/)
* [Optional: Hide the Result Cells](https://fox-friendly.techidaily.com/greatest-copyright-free-pubg-image-anthology/)

### Key Takeaways

 First, designate cells to hold "True" or "False" results based on the state of each checkbox. You can then count up the checkboxes by using Excel's COUNTIF function to count the number of "TRUE" results.

 If you [use Excel to create a checklist](https://android-location-track.techidaily.com/3-solutions-to-find-your-poco-f5-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/), you may want to count the number of checked or unchecked boxes. With a simple formula, you can tally them in a cell that adjusts as more boxes are marked or unmarked.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To count the unchecked boxes instead, simply replace True with False in the formula:

=COUNTIF(C2:C11,FALSE)

![COUNTIF False for unchecked boxes](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/COUNTIFFalse-ExcelCountCheckboxes.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you set the default Value for the checkbox as Mixed, it will not count toward the True or False result. It [displays as #N/A](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/) until the box is checked or unchecked.

##  Optional: Hide the Result Cells

 It may not be ideal to display the True and False results in your sheet. It might be distracting from the data you want to see.

 If you have the results in a single column or row without any other data you need, you can simply [hide the column or row](https://apple-account.techidaily.com/in-2024-tips-and-tricks-for-apple-id-locked-issue-from-apple-iphone-6-by-drfone-ios/).

Related: [How to Hide Cells, Rows, and Columns in Excel](https://apple-account.techidaily.com/in-2024-tips-and-tricks-for-apple-id-locked-issue-from-apple-iphone-6-by-drfone-ios/) 

 Right-click the column or row and pick "Hide" in the shortcut menu.

![Hide in the column menu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/HideColumn-ExcelCountCheckboxes.png) 

 The formula for the checked or unchecked boxes will work just the same with the results hidden.

![Results column hidden in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/HiddenColumn-ExcelCountCheckboxes.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-hints.techidaily.com/new-beyond-the-screen-vrs-creative-applications/"><u>[New] Beyond the Screen VR's Creative Applications</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-capture-youtubes-iconic-icons-online-tools-desktop-software-and-commands/"><u>[New] In 2024, Capture YouTube's Iconic Icons Online Tools, Desktop Software & Commands</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-unraveling-video-opposites-a-comprehensible-guide-for-instavids/"><u>[Updated] 2024 Approved Unraveling Video Opposites A Comprehensible Guide for InstaVids</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-top-rated-webcam-recorder-applications-demystified/"><u>[Updated] Top-Rated WebCam Recorder Applications Demystified</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-mastering-facebook-livestreams-four-easy-steps/"><u>2024 Approved Mastering Facebook Livestreams Four Easy Steps</u></a></li>
<li><a href="https://win11.techidaily.com/easy-fixes-to-lower-desktop-window-managers-power-use/"><u>Easy Fixes to Lower Desktop Window Manager's Power Use</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-windows-security-lock-and-sleep-timer/"><u>Enhancing Windows Security: Lock & Sleep Timer</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-mobile-hotspot-not-working-in-windows-11/"><u>How to Fix the Mobile Hotspot Not Working in Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-apple-id-and-apple-password-on-apple-iphone-14-pro-max-by-drfone-ios/"><u>In 2024, How to Reset Apple ID and Apple Password On Apple iPhone 14 Pro Max</u></a></li>
<li><a href="https://win11.techidaily.com/mastering-gpu-settings-in-windows-11-and-11/"><u>Mastering GPU Settings in Windows 11 & 11</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-setting-up-windows-hello-for-sign-in/"><u>Step-By-Step: Setting up Windows Hello for Sign In</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-overcoming-verified-app-issues-in-windows/"><u>Strategies for Overcoming Verified App Issues in Windows</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-fix-robloxs-error-403-in-a-windows-sphere/"><u>Strategies to Fix Roblox's Error 403 in a Windows Sphere</u></a></li>
<li><a href="https://win11.techidaily.com/taming-closed-caption-glitches-a-win-10-solution/"><u>Taming Closed Caption Glitches: A Win 10 Solution</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/1125937-9781609251826-the-old-girls-book-of-dreams/"><u>The Old Girls' Book of Dreams | Free Book</u></a></li>
<li><a href="https://hardware-help.techidaily.com/toms-computer-gear-ultimate-guide/"><u>Tom's Computer Gear: Ultimate Guide</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlock-your-samsung-galaxy-m54-5gs-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>Unlock Your Samsung Galaxy M54 5Gs Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
</ul></div>

