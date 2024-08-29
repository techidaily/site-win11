---
title: Effective Strategies for Identifying and Calculating Vacant Cell Values in MS Excel
date: 2024-08-27 11:12:23
updated: 2024-08-29 10:55:57
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/microsoft_excel_hero_1200x675.jpg
---

## Effective Strategies for Identifying and Calculating Vacant Cell Values in MS Excel

### Quick Links

* [Count Blank Cells Using a Function](https://youtube-docs.techidaily.com/tandout-thumbnails-start-here-20-top-font-picks-for-2024/)
* [Count Blank Cells Using the Find Feature](https://desktop-recording.techidaily.com/updated-in-2024-audio-enthusiasts-guide-to-the-best-10-spotify-recorders/)

 The only thing worse than incorrect data in your spreadsheet is missing data. If you want to count the number of blank or empty cells in Microsoft Excel, we'll show you two quick and easy methods.

 By using a function, you can keep the number of blank cells parked in your sheet. This way, if you change your data, that count will adjust. If you prefer to simply see a fast [count of empty cells](https://video-capture.techidaily.com/new-efficiently-recording-your-xbox-adventures/), you can use Excel's built-in Find feature. Let's take a look at both.

Related: [How to Count Blank or Empty Cells in Google Sheets](https://video-capture.techidaily.com/new-efficiently-recording-your-xbox-adventures/) 

##  Count Blank Cells Using a Function

 The COUNT function in Microsoft Excel is handy for many scenarios. So with a variation of that function, you can count empty cells easily. The function is COUNTBLANK and here's how to use it.

 While the COUNTBLANK function in Google Sheets ignores cells that are empty (containing an empty string, 

        `""`
    
), Excel's version of the function does not make this distinction. Thus, COUNTBLANK will return a count of both blank and empty cells.

 Select the cell where you want to insert the function. This is the same cell that will display the count of blank cells. Type the following formula into the cell replacing the cell range with your own and hit Enter.

=COUNTBLANK(B2:F12)

 You should then see the number of empty cells in the range you selected for the formula.

![Use the COUNTBLANK function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/COUNTBLANK-ExcelCountBlanks.png) 

 If you want to adjust the cell range, this is also simple. Click the cell containing the function, go up to the Formula Bar, and place your cursor within the cell range. You can manually change the cell references in the range or drag in or out on the blue box. Then, press Enter.

![Use the COUNTBLANK function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/COUNTBLANK-ExcelCountBlanks.png) 

 You can also combine the COUNTBLANK function with itself to count the number of blank cells in different cell ranges of the same workbook. Type the following formula into the cell replacing the cell ranges with your own and press Enter.

=COUNTBLANK(B2:F12)+COUNTBLANK(J2:N12)

 Notice the cell ranges for each set are outlined in a different color making them easy to edit if needed.

![Use the COUNTBLANK function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/COUNTBLANK-ExcelCountBlanks.png) 

 And you get the total count in one cell for both sets of cell ranges.

![Use the COUNTBLANK function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/COUNTBLANK-ExcelCountBlanks.png) 

 If you use colors to differentiate data, you may also find it useful to [count colored cells in your spreadsheet](https://facebook-video-recording.techidaily.com/new-2024-approved-the-cryptic-collection-of-2023-auction-for-anonymity-artifacts/).

Related: [How to Check If a Cell Is Blank With ISBLANK in Excel](https://tech-savvy.techidaily.com/1723808302722-effortless-guide-setting-up-your-ps4-remote-play-on-android-devices-in-just-three-simple-steps/) 

##  Count Blank Cells Using the Find Feature

 If you would rather not keep [a formula](https://extra-resources.techidaily.com/2024-approved-crafting-visuals-in-ae-selecting-excellent-plugin-choices/) in your sheet, but merely see a quick count of blank cells, use the Find feature.

[Select the cells](https://buynow-tips.techidaily.com/exploring-a-ravaged-world-on-motorcycle-in-days-gone-our-comprehhavis-review/) that include the blanks you want to find. Go to the Home tab and click the Find & Select drop-down arrow in the Editing section of the ribbon. Choose "Find."

![Click Find and Replace and pick Find](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/HomeFind-ExcelCountBlanks.png) 

 When the Find and Replace window opens, leave the Find What box blank. Then, click "Options" to expand the section at the bottom.

![Click Options](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/FindReplaceOptions-ExcelCountBlanks.png) 

 Adjust the three drop-down boxes on the left side to use the following:

* **Within**: Sheet
* **Search**: By Rows or By Columns (per your preference)
* **Look In**: Values

![Adjust the Find feature options](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/FindBlanks-ExcelCountBlanks.png) 

 When you're ready, click "Find All." You'll then see the number of cells found on the bottom left of the window.

![Blank cells found](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/FindAllBlanks-ExcelCountBlanks.png) 

 You'll also see a list of those empty cells in your sheet. You can click one to go directly to it or click "Find Next" to move to each of the results in the list one at a time.

![Move to each blank cell](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/FindNext-ExcelCountBlanks.png) 

 Click "Close" when you finish.

 Counting blank or empty cells in your spreadsheet is easy to do. And if you want to make them stand out so you don't lose track of them, learn how to [highlight blanks in your Excel sheet](https://ios-unlock.techidaily.com/in-2024-iphone-12-pro-asking-for-passcode-after-ios-1714-update-what-to-do-by-drfone-ios/).

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
