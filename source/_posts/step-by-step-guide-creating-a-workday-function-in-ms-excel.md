---
title: "Step-by-Step Guide: Creating a Workday Function in MS Excel"
date: 2024-08-28 13:27:38
updated: 2024-08-29 11:10:42
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/58d1c82f33ff87a2a49ef482dc26ca840416cdee7dcea0bf9addd82da02902e0.jpg
---

## Step-by-Step Guide: Creating a Workday Function in MS Excel

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
