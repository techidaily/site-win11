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


