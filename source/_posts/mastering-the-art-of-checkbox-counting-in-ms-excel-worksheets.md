---
title: Mastering the Art of Checkbox Counting in MS Excel Worksheets
date: 2025-01-03T19:48:42.992Z
updated: 2025-01-06T20:36:43.904Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/microsoft_excel_hero_1200x675.jpg
---

## Mastering the Art of Checkbox Counting in MS Excel Worksheets

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qn1XkPJde9Y?si=i6ZJARXO8sJhy2FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [Designate Cells for the Checkbox Controls](https://android-frp.techidaily.com/ultimate-guide-from-realme-gt-neo-5-frp-bypass-by-drfone-android/)
* [Use the COUNTIF Function](https://some-tips.techidaily.com/updated-the-metaverse-unraveled-explore-these-6-vivid-models/)
* [Optional: Hide the Result Cells](https://fox-friendly.techidaily.com/greatest-copyright-free-pubg-image-anthology/)

### Key Takeaways

 First, designate cells to hold "True" or "False" results based on the state of each checkbox. You can then count up the checkboxes by using Excel's COUNTIF function to count the number of "TRUE" results.

 If you [use Excel to create a checklist](https://android-location-track.techidaily.com/3-solutions-to-find-your-poco-f5-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/), you may want to count the number of checked or unchecked boxes. With a simple formula, you can tally them in a cell that adjusts as more boxes are marked or unmarked.

##  Designate Cells for the Checkbox Controls

 When you check a box in Excel, the result of the check is True. For unchecked boxes, the result is False.

 So, before you create the formula to [count your checkboxes](https://blog-min.techidaily.com/how-to-rescue-lost-contacts-from-huawei-nova-y91-by-fonelab-android-recover-contacts/), you'll need to designate cells to hold the True or False result. You'll then use that result in your formula.

Related: [How to Count Checkboxes in Google Sheets](https://blog-min.techidaily.com/how-to-rescue-lost-contacts-from-huawei-nova-y91-by-fonelab-android-recover-contacts/) 

 Right-click your first checkbox and select "Format Control" in the shortcut menu.

![Format Control in the shortcut menu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/FormatControl-ExcelCountCheckboxes.png) 

 In the Format Control box that appears, go to the Control tab. In the Cell Link box, enter the cell where you want to display the True or False result. You can also select the cell in your sheet to populate that box.

 Click "OK" to save the change.

![Cell reference in the Cell Link box](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/CellLink-ExcelCountCheckboxes.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Follow the same process for the other checkboxes that you want to count in your sheet.

 You should then see the True result for checked boxes and False for unchecked boxes in the designated cells.

![Checked boxes displaying True](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/CheckedTrue-ExcelCountCheckboxes.png) 

 If you set the default Value for the checkbox as Unchecked, it won't display False unless you check the box and then uncheck it.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/dKjioJQaUh8?si=Ls_AeuvGsSyL5ny2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Optional: Hide the Result Cells

 It may not be ideal to display the True and False results in your sheet. It might be distracting from the data you want to see.

 If you have the results in a single column or row without any other data you need, you can simply [hide the column or row](https://apple-account.techidaily.com/in-2024-tips-and-tricks-for-apple-id-locked-issue-from-apple-iphone-6-by-drfone-ios/).

Related: [How to Hide Cells, Rows, and Columns in Excel](https://apple-account.techidaily.com/in-2024-tips-and-tricks-for-apple-id-locked-issue-from-apple-iphone-6-by-drfone-ios/) 

 Right-click the column or row and pick "Hide" in the shortcut menu.

![Hide in the column menu](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/09/HideColumn-ExcelCountCheckboxes.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-bidding-adieu-to-instagram-your-complete-deletion-manual/"><u>[New] In 2024, Bidding Adieu to Instagram Your Complete Deletion Manual</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-top-5-uavs-for-elevating-your-gopro-videos-and-movies-for-2024/"><u>[New] Top 5 UAVs for Elevating Your GoPro Videos and Movies for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-unlocking-creativity-in-youtube-video-splitting-for-2024/"><u>[Updated] Unlocking Creativity in YouTube Video Splitting for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-a-comprehensive-look-at-vrs-strengths-and-weaknesses/"><u>2024 Approved A Comprehensive Look at VR's Strengths and Weaknesses</u></a></li>
<li><a href="https://win11.techidaily.com/tver/"><u>画面録画機能を使ってTVer番組視聴法：パソコンでの設定ガイド</u></a></li>
<li><a href="https://howto.techidaily.com/authentication-error-occurred-on-itel-p55plus-here-are-10-proven-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Authentication Error Occurred on Itel P55+? Here Are 10 Proven Fixes | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/deciphring-and-diagnosing-predominant-windows-anydesk-problems/"><u>Deciphring and Diagnosing Predominant Windows AnyDesk Problems</u></a></li>
<li><a href="https://howto.techidaily.com/fix-motorola-moto-g84-5g-android-system-webview-crash-2024-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Motorola Moto G84 5G Android System Webview Crash 2024 Issue | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/top-10-iphone-and-android-video-editing-apps-for-gopro-for-2024/"><u>Top 10 iPhone & Android Video Editing Apps for GoPro for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/transform-your-music-collection-convert-doobie-brothers-dvds-to-high-quality-mp4mp3-files/"><u>Transform Your Music Collection: Convert Doobie Brothers' DVDs to High-Quality MP4/MP3 Files</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1723013134928-troubleshooting-frozen-screens-in-rocket-league-solutions-inside/"><u>Troubleshooting Frozen Screens in Rocket League – Solutions Inside!</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-incompatible-sound-codes-on-samsung-tvs-simple-solutions-for-audio-issues/"><u>Troubleshooting Incompatible Sound Codes on Samsung TVs - Simple Solutions for Audio Issues</u></a></li>
<li><a href="https://win11.techidaily.com/ultimate-guide-solving-the-mp4-playback-issue-in-vlc-on-your-windows-pc/"><u>Ultimate Guide: Solving the MP4 Playback Issue in VLC on Your Windows PC</u></a></li>
<li><a href="https://win11.techidaily.com/unauthorized-tutorial-steps-to-modify-someone-elses-youtube-content/"><u>Unauthorized Tutorial: Steps to Modify Someone Else's YouTube Content</u></a></li>
<li><a href="https://win11.techidaily.com/windows-10movjpeg/"><u>Windows 10向けMOVファイルからの高品質JPEGへの変換手順</u></a></li>
<li><a href="https://win11.techidaily.com/windowsiphoneandroidtop5/"><u>Windows、iPhone、Android用動画連結手法TOP5 - スムーズな映像編集</u></a></li>
</ul></div>

