---
title: "Excel Tricks: Writing Your Own Function to Count Business Days"
date: 2024-08-28T00:49:17.306Z
updated: 2024-08-29T00:49:17.306Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/029ba41f4072a625a12663e242fe0241f864e3cc7e4fb5de060add9d7faf8df5.jpg
---

## Excel Tricks: Writing Your Own Function to Count Business Days

### Quick Links

* [Find the Workdays Between Two Dates in Excel](https://tech-recovery.techidaily.com/troubleshooting-the-pc-reset-failed-message-on-windows/)

 With Microsoft Excel's 

        `NETWORKDAYS`
    
 function, you can [count the number of workdays](https://youtube-web.techidaily.com/ed-2024-approved-ultimate-guide-to-the-best-10-video-saving-devices/) that fall between two specified dates. This function excludes Saturdays, Sundays, and optionally the specified holidays. We'll show you how to use it.

 This function can account for holidays in its calculation, but you must specify those holidays in a column, so be ready with a list of your holiday dates. Also, it's important you keep in mind that this function counts both the starting date and the ending [date in the calculation](https://extra-lessons.techidaily.com/kickstart-your-telegram-promotion-journey-tips-for-newbies/).

Related: [Use Excel to Calculate How Many Days Until an Event](https://youtube-web.techidaily.com/ed-2024-approved-ultimate-guide-to-the-best-10-video-saving-devices/) 

##  Find the Workdays Between Two Dates in Excel

 To get the number of workdays that fall between two dates, first, open your spreadsheet with Microsoft Excel.

 In your spreadsheet, click the cell where you want to display the resulting workday number.

![Select a cell to display the NETWORKDAYS result.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/1-select-networkdays-result-cell.png) 

 In the selected cell, type the following function and press Enter. In the function, replace `B2` with the cell that contains the starting date and `C2` with the cell containing the ending date.

=NETWORKDAYS(B2,C2)

![Type the NETWORKDAYS function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/2-enter-networkdays-function.png) 

 Excel will calculate the number of workdays between your dates and display the result in the selected cell. Note that this number includes both the starting date and the ending date.

![The result of the NETWORKDAYS function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/3-excel-networkdays-function-result.png) 

 If you'd like to exclude any holidays from your calculation, then first, specify your holidays in a column. Like so:

![Enter the holidays in a column.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/4-specify-holidays.png) 

 Click the cell where you want to get the result, type the following function, and press Enter. In this function, replace `B2` with the cell that contains the starting date, `C2` with the cell that contains the ending date, and `E2:E6` with the range where you've specified your holidays.

=NETWORKDAYS(B2,C2,E2:E6)

![Use NETWORKDAYS with holidays.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/5-networkdays-with-holidays.png) 

 Excel will display the result in your selected cell. Note that this count excludes your specified holidays but includes the starting and the ending date.

![NETWORKDAYS' result with holidays.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/6-networkdays-with-holidays-result.png) 

 And that's how you can use an Excel function to quickly find the number of days someone has worked between any two dates. Very useful!

---

 Do you want to [find the number of full days between two dates in Excel](https://some-approaches.techidaily.com/new-top-10-hidden-gems-for-enhancing-canva-images/)? If so, there's a quick way to do that.

Related: [How to Find the Number of Days Between Two Dates in Microsoft Excel](https://some-approaches.techidaily.com/new-top-10-hidden-gems-for-enhancing-canva-images/)

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



<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->