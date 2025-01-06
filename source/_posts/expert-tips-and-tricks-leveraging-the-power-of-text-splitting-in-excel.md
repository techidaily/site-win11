---
title: "Expert Tips and Tricks: Leveraging the Power of Text Splitting in Excel"
date: 2025-01-03T17:49:47.581Z
updated: 2025-01-06T16:17:19.764Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/ef9be7780d43a1d277262443e1e1ad4f9cd5011c4e9a9bd97f972e7408a7d734.jpg
---

## Expert Tips and Tricks: Leveraging the Power of Text Splitting in Excel

### Quick Links

* [Text to Columns with Delimited Text](https://vp-tips.techidaily.com/updated-2024-approved-photographic-albums-with-soundscape-features/)
* [Text to Columns with Fixed Width Text](https://youtube-web.techidaily.com/treaming-giants-rivalry-facebook-vs-youtube-and-spaces-for-2024/)
* [Converting US Dates to European Format](https://techno-recovery.techidaily.com/from-novice-to-pro-harnessing-the-power-of-emojis-on-your-iphone/)
* [Converting International Number Formats](https://apple-account.techidaily.com/why-apple-account-disabled-on-your-apple-iphone-se-2022-how-to-fix-by-drfone-ios/)

 Excel's Text to Columns feature splits text in a cell into multiple columns. This simple task can save a user the heartache of manually separating the text in a cell into several columns.

 We'll start with a simple example of splitting two samples of data into separate columns. Then, we'll explore two other uses for this feature that most Excel users are not aware of.

##  Text to Columns with Delimited Text

 For the first example, we will use Text to Columns with delimited data. This is the more common scenario for splitting text, so we will start with this.

 In the sample data below we have a list of names in a column. We would like to [separate the first and last name into different columns](https://blog-min.techidaily.com/how-to-remove-google-frp-lock-on-oppo-a18-by-drfone-android-unlock-remove-google-frp/).

![Sample data for Text to Columns](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/sample-data.png) 

 In this example, we would like the first name to remain in column A for the last name to move to column B. We already have some information in column B (the Department). So we need to insert a column first and give it a header.

![Column inserted for last names](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/column-added.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Next, select the range of cells containing the names and then click Data > Text to Columns

![Text to Columns button on the Data tab.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/data-text-to-columns.png) 

 This opens a wizard in which you'll perform three steps. Step one is to specify how the content is separated. Delimited means the different pieces of text you want to pull apart are separated by a special character such as space, comma, or slash. That's the one we're going to choose here. (We'll talk about the fixed width option in the next section.)

![Step 1 of the Text to Columns wizard](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/step-one.png) 

 In the second step, specify the delimiter character. In our simple example data, the first and last names are delimited by a space. So, we're going to remove the check from the "Tab" and add a check to the "Space" option.

![Step 2 of the Text to Columns wizard](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/step-two.png) 

 In the final step, we can format the content. For our example, we do not need to apply any formatting, but you could do things like specify whether the data is in the text or date format, and even set it up so that one format converts to another during the process.

 We will also leave the destination as $A$2 so that it splits the name from its current position, and moves the last name into column B.

![Step 3 of the Text to Columns wizard](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/step-three.png) 

 When we click "Finish" on the wizard, Excel separates the first and last names and we now have our new, fully populated Column B.

![Names split into different columns](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/separated-names.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Wy0uYNNdMDM?si=5ir7EHlr0CkpcYOT" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Text to Columns with Fixed Width Text

 In this example, we will split text that has a fixed width. In the data below, we have an invoice code that always begins with two letters followed by a variable number of numeric digits. The two-letter code represents the client and the numeric value after it represents the invoice number. We want to separate the first two characters of the invoice code from the numbers that succeed it and deposit those values into the Client and Invoice No columns we've set up (columns B and C). We also want to keep the full invoice code intact in Column A.

![Sample data for fixed width text](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/fixed-width-data.png) 

 Because the invoice code is always two characters, it has a fixed width.

 Start by selecting the range of cells containing the text you want to split and then clicking Data > Text to Columns.

![Text to Columns button on the Data tab.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/data-text-to-columns.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 On the first page of the wizard, select the "Fixed Width" option and then click "Next."

![Splitting text with a fixed width](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/fixed-width.png) 

 On the next page, we need to specify the position(s) in the column to split the content. We can do this by clicking in the preview area provided.

**Note:** Text to Columns sometimes provides a suggested break(s). This can save you some time, but keep an eye on it. The suggestions are not always correct.

 In the "Data Preview" area, click where you want to insert the break and then click "Next."

![Insert column break in Text to Columns](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/insert-column-break.png) 

 In the final step, type cell B2 (=$B$2) in the Destination box and then click "Finish."

![Set a destination for split cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/destination-set.png) 

 The invoice numbers are successfully separated into columns B and C. The original data remains in column A.

![Splitting text with a fixed width](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/fixed-width.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 So, we've now looked at splitting content using delimiters and fixed widths. We've also looked at splitting text in place and splitting it to different places on a worksheet. Now let's look at two extra special uses of Text to Columns.

##  Converting US Dates to European Format

 One fantastic use of Text to Columns is to convert date formats. For example, converting a US date format to European or vice versa.

 I live in the UK so when I import data into an Excel spreadsheet, sometimes they are stored as text. This is because the source data is from the US and the date formats do not match the regional settings configured in my installation of Excel.

 So, its Text to Columns to the rescue to get these converted. Below are some dates in US format that my copy of Excel has not understood.

![US date formats to convert](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/us-dates.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fo4lNZ84x9Q?si=WdcYPZp-9VJnZEnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 First, we're going to select the range of cells containing the dates to convert and then click Data > Text to Columns.

![Text to Columns button on the Data tab.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/data-text-to-columns.png) 

 On the first page of the wizard, we'll leave it as delimited and on the second step, we'll remove all the delimiter options because we don't actually want split any content.

![All delimiter character options unchecked](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/all-delimiters-unchecked.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 On the final page, select the Date option and use the list to specify the date format of the data you have received. In this example, I will select MDY---the format typically used in the US.

![Selecting the MDY format for dates](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/mdy-format.png) 

 After clicking "Finish," the dates are successfully converted and are ready for further analysis.

![US dates converted to UK format](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/converted-dates.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Converting International Number Formats

 In addition to being a tool for converting different date formats, Text to Columns can also convert international number formats.

 Here in the UK, a decimal point is used in number formats. So for example, the number 1,064.34 is a little more than one thousand.

 But in many countries, a decimal comma is used instead. So that number would be misinterpreted by Excel and stored as text. They would present the number as 1.064,34.

 Thankfully when working with international number formats in Excel, our good friend Text to Columns can assist us with converting these values.

 In the example below, I have a list of numbers formatted with a decimal comma. So my regional settings in Excel have not recognized them.

![European number formats for converting](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/european-number-formats.png) 

 This process is almost identical to the one we used for converting dates. Select the range of values, head to Data > Text to Columns, select the delimited option, and remove all the delimiter characters. On the final step of the wizard, this time we're going to choose the "General" option and then click the "Advanced" button.

![Advanced options at step 3 of the wizard](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/advanced-button.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In the settings window that opens, enter the character you want to use in the Thousand separator and Decimal separator boxes provided. Click "OK" and then click "Finish" when you get back to the wizard.

![Specifying the decimal and thousand separator](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/advanced-options.png) 

 The values are converted and now recognized as numbers for further calculation and analysis.

![Numbers converted by Text to Columns](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/03/converted-numbers.png) 

---

 Text to Columns is more powerful than people realize. Its classic use to separate content into different columns is incredibly useful. Especially when working with data we receive from others. The lesser-known abilities to convert date and international number formats are magic.

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
<li><a href="https://youtube-web.techidaily.com/n-2024-from-end-to-start-annoying-yourself-with-yt-playlist-upside-down/"><u>[New] In 2024, From End to Start Annoying Yourself with YT Playlist Upside-Down</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-incorporating-background-scenes-for-visual-depth/"><u>2024 Approved Incorporating Background Scenes for Visual Depth</u></a></li>
<li><a href="https://extra-information.techidaily.com/arctic-athleticism-revealed-the-top-of-the-line-in-olympic-snowboard-cross/"><u>Arctic Athleticism Revealed The Top of the Line in Olympic Snowboard Cross</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016424304-getting-your-modern-warfare-voice-chat-up-and-running-again-solutions-inside/"><u>Getting Your Modern Warfare Voice Chat Up and Running Again – Solutions Inside</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/how-to-elevate-your-tablet-experience-with-the-space-saving-amazon-basics-stand/"><u>How to Elevate Your Tablet Experience with the Space-Saving Amazon Basics Stand!</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-reorder-dual-display-setups/"><u>How to Reorder Dual Display Setups</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-samsung-galaxy-a15-4g-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Samsung Galaxy A15 4G Location Settings | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/insider-knowledge-navigating-the-world-of-windows-keys-and-deals/"><u>Insider Knowledge: Navigating the World of Windows Keys & Deals</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/kioxias-cutting-edge-optical-ssds-deliver-blistering-speeds-and-unprecedented-distance-capabilities-up-to-40-meters-away-from-the-processor/"><u>Kioxia's Cutting-Edge Optical SSDs Deliver Blistering Speeds and Unprecedented Distance Capabilities: Up to 40 Meters Away From the Processor</u></a></li>
<li><a href="https://win11.techidaily.com/rename-user-home-path-a-windows-11-guide/"><u>Rename User Home Path - A Windows 11 Guide</u></a></li>
<li><a href="https://win11.techidaily.com/stifling-windows-11-folder-tab-noises/"><u>Stifling Windows 11 Folder Tab Noises</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-to-overcome-error-0x80070141-in-windows-systems/"><u>Strategies to Overcome Error 0X80070141 in Windows Systems</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-tips-addressing-crashes-in-pc-versions-of-starfield-adventure/"><u>Troubleshooting Tips: Addressing Crashes in PC Versions of Starfield Adventure</u></a></li>
<li><a href="https://win11.techidaily.com/uniting-platforms-your-pc-and-galaxy-phone-via-flow/"><u>Uniting Platforms – Your PC and Galaxy Phone Via Flow</u></a></li>
<li><a href="https://win11.techidaily.com/winning-tips-resolving-chrome-profiles-failures/"><u>Winning Tips: Resolving Chrome Profiles Failures</u></a></li>
</ul></div>

