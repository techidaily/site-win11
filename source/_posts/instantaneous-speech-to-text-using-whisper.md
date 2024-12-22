---
title: Instantaneous Speech-to-Text Using Whisper
date: 2024-12-20T16:28:36.153Z
updated: 2024-12-22T17:02:27.138Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Instantaneous Speech-to-Text Using Whisper
excerpt: This Article Describes Instantaneous Speech-to-Text Using Whisper
keywords: Whisper to Text Quickly,Instant Speech Transcription,Immediate Voice-to-Text,Real-Time Audio Conversion,Speedy Speech Recognition,Whispered Words Analysis,Efficient Audio Translation
thumbnail: https://thmb.techidaily.com/7a686a1b526676a12878d5e404ff256d91c8737d5163c7ab05139a28f15cb6cd.jpg
---

## Instantaneous Speech-to-Text Using Whisper

 The very same people behind ChatGPT have created another AI-based tool you can use today to boost your productivity. We're referring to Whisper, a voice-to-text solution that eclipsed all similar solutions that came before it.

 You can use Whisper in your programs or the command line. And yet, that defeats its very purpose: typing without a keyboard. If you need to type to use it, why use it to avoid typing? Thankfully, you can now use Whisper through a desktop GUI. Even better, it can also transcribe your voice almost in real time. Let's see how you can type with your voice using Whisper Desktop.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What Is OpenAI's Whisper?

 OpenAI's Whisper is an Automatic Speech Recognition system (ASR for short) or, to put it simply, is a solution for converting spoken language into text.

 However, unlike older dictation and transcription systems, Whisper is an AI solution trained on over 680,000 hours of speech in various languages. Whisper offers unparalleled accuracy and, quite impressively, not only is it multilingual, but it can also translate between languages.

 More importantly, it's free and available as open source. Thanks to that, many developers have forked its code into their own projects or created apps that rely on it, like Whisper Desktop.

 If you'd prefer the "vanilla" version of Whisper and the versatility of the terminal instead of clunky GUIs, check our article on [how to turn your voice into text with OpenAI's Whisper for Windows](https://www.makeuseof.com/dictate-documents-openai-whisper/).

## Are Whisper and Whisper Desktop the Same?

 Despite its official-sounding name, Whisper Desktop is a third-party GUI for Whisper, made for everyone who'd prefer to click buttons instead of typing commands.

 Whisper Desktop is a standalone solution that doesn't rely on an existing Whisper installation. As a bonus, it uses an alternative, optimized version of Whisper, so it should perform better than the standalone version.

 You're on the other end of the spectrum, and instead of seeking an easier way to use Whisper than the terminal you're seeking ways to implement it in your own solutions? Rejoice, for [OpenAI has opened access to ChatGPT and Whisper APIs](https://www.makeuseof.com/what-chatgpt-and-whisper-apis-means-for-businesses/).

## Download & Install Whisper Desktop

 Although Whisper Desktop is easier to use than the standalone Whisper, its installation is more convoluted than repeatedly clicking Next in a wizard.

1. Visit [Whisper Desktop's official Github page](https://github.com/Const-me/Whisper). Look on the right, and click on the latest version under **Releases**.  
![Whisper Desktop Github Releases Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-github-releases-link.jpg)
2. Under **Assets**, click **WhisperDesktop.zip** and download it to your PC.  
![Whisper Desktop Github Download Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-github-download-link.jpg)
3. Extract the downloaded archive to a folder and use your file manager to visit it. Inside you will find the Whisper Desktop application. Double-click on it to run it.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5FWCFI3f_cs?si=Kt2Onr_E4c616tbH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Whisper Desktop App in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-app-in-file-explorer.jpg)
4. You also need a Whisper language model in **GCML** binary format. Whisper Desktop will provide you with two links for acquiring one. Skip the second link for generating your own model since it's a more complicated process. Click on **Hugging Face** to open that page in your default browser, from where you can download a ready-to-use file.  
![Whisper Desktop Language Model Links](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-language-model-links.jpg)
5. The version of Whisper Desktop we used while writing this article provided a link to an obsolete repository at Hugging Face. If you meet the same problem, notice a link to a **new location**. Click on it to visit the new repository.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Hugging Face Whisper Models New Location](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hugging-face-whisper-models-new-location.jpg)
6. Click on the link that will take you to the available **models**.  
![Hugging Face Available Models Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hugging-face-available-models-link.jpg)
7. From that list, click on either the **ggml-medium.bin** or **ggml-medium.en.bin**, depending on if you want multilingual or English-only support in Whisper.  
![Hugging Face Whisper Medium Model Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hugging-face-whisper-medium-model-link.jpg)
8. Finally, you should have reached your destination. Notice the line stating that this file is stored with Git LFS and is too big to display, but you can still download it. Click on **download** to do precisely that.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![Hugging Face Whisper Medium Model Download Link](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/hugging-face-whisper-medium-model-download-link.jpg)
9. When the file completes downloading, use your favorite file manager (File Explorer will do) to move the downloaded language model file into the same folder as Whisper Desktop.  
![Whisper Medium Model Placed in Whisper Desktop Folder in File Explorer](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-medium-model-placed-in-whisper-desktop-folder-in-file-explorer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/620kcQ7Dw7w?si=a5ussGs5HV7sG3hF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Transcribing With Whisper Desktop

 Transcribing with Whisper Desktop is easy, but you may still need one or two clicks to use the app.

 Rerun Whisper Desktop. Does it (still) miss the correct path to your downloaded language model? Click on the **button with the three dots** on the right of the field and manually select the file you downloaded from Hugging Face.

 From this spot, you can also use the drop-down menu next to **Model Implementation** to choose if you want to run Whisper on your GPU (**GPU**), on both the CPU and GPU (**Hybrid**), or only on the CPU (**Reference**).

![Whisper Desktop Selecting Model Implementation](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-selecting-model-implementation.jpg)

 The **Advanced** button leads to more options that affect how Whisper will run on your hardware. However, since the button clearly states they are advanced, we suggest you only tweak them if you are troubleshooting or know what you are doing. Setting the wrong options values here can impose a performance penalty or render the app unusable.

 Click on OK to move to the app's main interface.

![Whisper Desktop Advanced Options Changing Graphics Adapter](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-advanced-options-changing-graphics-adapter.jpg)

 If you already have a recording of your voice you want to turn into written text, click on **Transcribe File** and select it. Still, we will use Whisper Desktop for live transcription for this article.

 The options offered are straightforward. You can select the **language** Whisper will use, choose if you want to **translate** between languages and enable the app's **Debug Console**.

 Most English-speaking users can safely skip those options and only ensure the correct audio input is selected from the pull-down menu next to **Capture Device**.

 Make sure **Save to text file** and **Append to that file** are enabled to have Whisper Desktop save its output to a file without overwriting its content. Use the **button with the three dots** on the right of the file's path field to define said text file.

![Whisper Desktop Saving And Appending to Text File](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-saving-and-appending-to-text-file.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15Ju8Cb4UZ8?si=5wdiQXdz1BOxIkDH" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click on **Capture** to begin transcribing your speech to text.

 Whisper Desktop will show you three indicators for when it detects voice activity, when it's actively transcribing, and when the process is stalled.

 You can keep talking for as long as you like, and you should occasionally see the two first indicators flashing while the app turns your voice into text. Click **Stop** when done.

![Whisper Desktop Active Voice Transcribing](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/whisper-desktop-active-voice-transcribing.jpg)

 The text file you selected should open in your default text editor, containing in written form everything you said until you clicked **Stop**.

![Transcribed Text With Whisper Desktop in Typora](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/05/transcribed-text-with-whisper-desktop-in-typora.jpg)

 We should note that you can also do the opposite of what we saw here: convert any text to speech. This way you can listen to anything as if it were a podcast instead of tiring your eyes squinting at screens. For more info on that, check our article on [some of the best free online tools to download text-to-speech as MP3 audio](https://www.makeuseof.com/tag/download-text-to-speech-as-mp3-audio/).

## Whisper Desktop Voice-Typing Tips

 Although Whisper Desktop can be a lifesaver, enabling you to write with your voice much quicker than you could type, it's far from perfect.

 During our testing, we found that it may occasionally stutter, skip some words, fail to transcribe until you manually stop and restart the process, or get stuck in a loop and keep re-transcribing the same phrase repeatedly.

 We believe those are temporary glitches that will be fixed since the standalone Whisper doesn't exhibit the same issues.

 Apart from those minor bumps, turning your voice to text should be effortless with Whisper Desktop. Still, during our tests, we found that it can perform even better if...

1. Instead of uttering only two or three words and then pausing, Whisper can understand you better if you go on longer. Try to at least give it an entire sentence at a time.
2. For the same reason, avoid repeatedly starting and stopping the transcription process.
3. Whenever you realize you made a mistake, ignore it and keep going. Loading and unloading the language model seems to be the most time-consuming part of the process with the current state of Whisper and our available hardware. So, it's quicker to keep talking and then edit out your mistakes afterward.
4. As with the standalone version of Whisper, it's best to use the optimal language model for your available hardware. You can use up to the **medium** model if your GPU has 8GB of VRAM. For less VRAM, go for the smaller models. Only choose the slightly more accurate but also much more demanding **large** model if you use a GPU with 16GB of VRAM or more.
5. Remember that the larger the language model, the slower the transcription process. Don't go for a model larger than needed. You'll probably find Whisper Desktop can already "understand you" most of the time with the medium or smaller models, with only one or two errors per paragraph.

## Are You Still Typing? Use Your Voice With Whisper

 Despite requiring some time to set up, as you will see when you try it, Whisper Desktop performs much better than most alternatives, with much higher accuracy and better speed.

 After you start using it to type with your voice, your keyboard may look like a relic from ancient times long gone.

 You can use Whisper in your programs or the command line. And yet, that defeats its very purpose: typing without a keyboard. If you need to type to use it, why use it to avoid typing? Thankfully, you can now use Whisper through a desktop GUI. Even better, it can also transcribe your voice almost in real time. Let's see how you can type with your voice using Whisper Desktop.

<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-rapid-tiktok-downloads-flawless-mp4-format-conversions-for-2024/"><u>[New] Rapid TikTok Downloads Flawless MP4 Format Conversions for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-effortless-podcast-livestream-guide/"><u>[Updated] Effortless Podcast Livestream Guide</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-translating-views-into-dollars-on-youtube-via-cpm/"><u>[Updated] In 2024, Translating Views Into Dollars on YouTube via CPM</u></a></li>
<li><a href="https://blog-min.techidaily.com/1-top-8-efficient-ways-to-convert-mts-files-to-mp4-on-windows-and-mac/"><u>1. Top 8 Efficient Ways to Convert MTS Files to MP4 on Windows and Mac</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-accessing-and-saving-tweets-visuals-in-your-android-device/"><u>2024 Approved Accessing and Saving Tweets' Visuals in Your Android Device</u></a></li>
<li><a href="https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-xiaomi-civi-3-disney-100th-anniversary-edition-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Safe Mode - How to Turn off Safe Mode on Xiaomi Civi 3 Disney 100th Anniversary Edition? | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/controlling-windows-11-registry-editor-accessibility/"><u>Controlling Windows 11 Registry Editor Accessibility</u></a></li>
<li><a href="https://win11.techidaily.com/exploring-the-windows-11-registry-for-unseen-themes/"><u>Exploring the Windows 11 Registry for Unseen Themes</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-hidefake-snapchat-location-on-your-vivo-t2-5g-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-mystic-mastery-in-minimalist-photo-manipulations/"><u>In 2024, Mystic Mastery in Minimalist Photo Manipulations</u></a></li>
<li><a href="https://win11.techidaily.com/reversing-shadow-copy-suspension-error/"><u>Reversing Shadow Copy Suspension Error</u></a></li>
<li><a href="https://win11.techidaily.com/troubleshooting-non-functional-win11-activation-keys/"><u>Troubleshooting Non-Functional Win11 Activation Keys</u></a></li>
<li><a href="https://win11.techidaily.com/understanding-and-managing-windows-odbc-sources/"><u>Understanding and Managing Windows ODBC Sources</u></a></li>
<li><a href="https://win11.techidaily.com/win10-network-resolution-path-unreachable/"><u>Win10 Network Resolution: Path Unreachable</u></a></li>
</ul></div>

