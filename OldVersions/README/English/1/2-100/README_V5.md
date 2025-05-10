
***

<details open><summary><p><b>Click/tap here to expand/collapse this entire article (README)</b></p></summary>

<details open><summary><p><b>Click/tap here to expand/collapse the logo section</b></p></summary>

<img src="Flag-Simulator_PlaceholderLogo.svg" alt="Flag Simulator placeholder logo failed to load" width="747" height="804" title="Flag Simulator Placeholder Logo">

**Note:** This flag is for vanity purposes only. It is not meant to signal support for anything. A new logo will be created in the future, although this project will have multiple logos (for different app icons)

</details>

# Flag Simulator

<details open><summary><p><b>Click/tap here to expand/collapse the title section</b></p></summary>

Flag Simulator is the ultimate vexillology software piece, which lets you do anything you would ever want to do with a flag.

It is intended to be an improvement over [:octocat: `Krikienoid/FlagWaver`](https://github.com/krikienoid/flagwaver/)

</details>

***

## Table of Contents

- [00.00 - Title](#Flag-Simulator)
- [00.01 - Table of contents](#Table-of-contents)
- [00.02 - Read this article in a different language](#Read-this-article-in-a-different-language)
- [00.03 - This repository](#This-repository)
- [01.00 - Features](#Features)
- - [01.01 - Featured flags](#Featured-flags)
- - [01.02 - Flag physics](#Flag-physucs)
- - [01.03 - Flag direction](#Flag-direction)
- - [01.04 - Wind direction](#Wind-direction)
- - [01.05 - Wind control](#Wind-control)
- - [01.06 - Barometric pressure](#Barometric-pressured)
- - [01.07 - Different backgrounds](#Different-backgrounds)
- - [01.08 - Background videos](#Background-videos)
- - [01.09 - Export](#Export)
- - [01.10 - Embed into a webpage](#Embed-into-a-webpage)
- - [01.11 - Database of flags](#Database-of-flags)
- - [01.12 - Upload custom flags](#Upload-custom-flags)
- - [01.13 - Pennants](#Pennants)
- - [01.14 - Multiple flags](#Multiple-flags)
- - [01.15 - Information on each flag](#Information-on-each-flag)
- - [01.16 - FlagW file (waving flag data file)](#FlagW-file-waving-flag-data-file)
- - [01.17 - Flag burning](#Flag-burning)
- - [01.18 - Information on religious flags](#Information-on-religious-flags)
- - [01.19 - Flag tearing](#Flag-tearing)
- - [01.20 - Half mast](#Half-mast)
- - [01.21 - Waving/lowering](#Waving-lowering)
- - [01.22 - Customizable flag poles](#Customizable-flag-poles)
- - [01.23 - Totem pole library](#Totem-pole-library)
- - [01.24 - Flag poles](#Flag-poles)
- - [01.25 - SVG, PNG, JPEG, GIF, TIFF, BMP, WEBP, NETP, ICO, GIF_C200, among other supported formats](#SVG-PNG-JPEG-GIF-TIFF-BMP-WEBP-NETP-ICO-GIF-C200-among-other-supported-formats)
- - [01.26 - Various buttons](#Various-buttons)
- - [01.27 - Ability to send an army to take down the flag](#Ability-to-send-an-army-to-take-down-the-flag)
- - [01.28 - Offline functionality](#Offline-functionality)
- - [01.29 - Rain and weather effects](#Rain-and-weather-effects)
- - [01.30 - Play audio (national anthems, and anthem library)](#Play-audio-national-anthems-and-anthem-library)
- - [01.31 - Simulate real weather (with weather services, and data files for weather events)](#Simulate-real-weather-with-weather-services-and-data-files-for-weather-events))
- - [01.32 - Flag construction mode](#Flag-construction-mode)
- - [01.33 - Flag folding](#Flag-folding)
- - [01.34 - Lighting, lighting modes](#Lighting-lighting-modes)
- - [01.35 - Shine a light](#Shine-a-light)
- - [01.36 - Flashlight (movable with cursor/finger)](#Flashlight-movable-with-cursor-finger)
- - [01.37 - Customizable flashlight, different light colors, sizes, strengths of light](#Customizable-flashlight-different-light-colors-sizes-strengths-of-light)
- - [01.38 - Flag weaving](#Flag-weaving)
- - [01.39 - Buy an actual flag (based on the one shown)](#Buy-an-actual-flag-based-on-the-one-shown))
- - [01.40 - FIAV flag](#FIAV-flag)
- - [01.41 - Default flag](#Default-flag)
- - [01.42 - Homepage](#Homepage)
- - [01.43 - Fire arrows](#Fire-arrows)
- - [01.44 - Other items to throw](#Other-items-to-throw)
- - [01.45 - Flag Emoji mode](#Flag-Emoji-mode)
- - [01.46 - Flag Emoji import](#Flag-Emoji-import)
- - [01.47 - Flag search (search for a flag, Emojis also work as a search option)](#Flag-search-search-for-a-flag-Emojis-also-work-as-a-search-option)
- - [01.48 - User interface skins](#User-interface-skins)
- - [01.49 - Censorship modes for hate flags, Socialist/Communist flags, terrorist flags, etc](#Censorship-modes-for-hate-flags-Socialist-Communist-flags-terrorist-flags-etc)
- - [01.50 - Age rating](#Age-rating)
- - [01.51 - Desktop application (with ports in Python, Java, C, and Rust)](#Desktop-application-with-ports-in-Python-Java-C-and-Rust)
- - [01.52 - Web application (with ports in Ruby, JavaScript, PHP, and WebAssembly)](#Web-application-with-ports-in-Ruby-JavaScript-PHP-and-WebAssembly)
- - [01.53 - Mobile application (with ports in Java, Kotlin, Swift, and C)](#Mobile-application-with-ports-in-Java-Kotlin-Swift-and-C)
- - [01.54 - Flag text and copy text from flag](#Flag-text-and-copy-text-from-flag)
- - [01.55 - ASCII mode, with text color toggle](#ASCII-mode-with-text-color-toggle)
- - [01.56 - Creating large flags (up to worlds largest)](#Creating-large-flags-up-to-worlds-largest)
- - [01.57 - Size limit: whatever your system can handle (even 1,000,000m by 1,000,000m would be allowed) theoretical end at 9,223,372,036,854,775,807 (2^64) square pixels](#Size-limit-whatever-your-system-can-handle-even-1-000-000m-by-1,000-000m-would-be-allowed-theoretical-end-at-9-223-372-036-854-775-807-2-64-square-pixels)
- - [01.58 - Flag code dictionary](#Flag-code-dictionary)
- - [01.59 - Flag creator: Your own flag (built-in editor) add description, colors, shapes, graphics, text mode, description, and flag code](#Flag-creator-Your-own-flag-built-in-editor-add-description-colors-shapes-graphics-text-mode-description-and-flag-code)
- - [01.60 - Color modes: monochrome, 4 bit, 5 bit, 6 bit, 7 bit, 8 bit, 12 bit, 16 bit, 24 bit, 32 bit, 48 bit, 64 bit](#Color-modes-monochrome-4-bit-5-bit-6-bit-7-bit-8-bit-12-bit-16-bit-24-bit-32-bit-48-bit-64-bit)
- - [01.61 - Filters](#Filters)
- - [01.62 - Slideshow mode](#Slideshow-mode)
- - [01.63 - Customize the area around the flag pole](#Customize-the-area-around-the-flag-pole)
- - [01.64 - Multiple flag poles](#Multiple-flag-poles)
- - [01.65 - Flag pole size](#Flag-pole-size)
- - [01.66 - Flag pole material (metal, wood, etc.)](#Flag-pole-material-metal-wood-etc-)
- - [01.67 - Flag pole material download](#Flag-pole-material-download)
- - [01.68 - Dimensional modes: 2D, 3D, 4D](#Dimensional-modes-2D-3D-4D)
- - [01.69 - Scissors, knives, and swords](#Scissors-knives-and-swords)
- - [01.70 - Acid raid effect](#Acid-raid-effect)
- - [01.71 - Fun facts about Vexillology in the UI](#Fun-facts-about-Vexillology-in-the-UI)
- - [01.72 - Accessories menu and the ability to import new ones (built-in: scissors, knives, swords, fire arrows, flashlight)](#Accessories-menu-and-the-ability-to-import-new-ones-built-in-scissors-knives-swords-fire-arrows-flashlight)
- - [01.73 - Accessory files: a specialized data file for the project](#Accessory-files-a-specialized-data-file-for-the-project)
- - [01.74 - Transparency level](#Transparency-level)
- - [01.75 - Flag stamps](#Flag-stamps)
- [02.00 - Feedback](#Feedback)
- - [02.01 - Feedback from 2025, April](#Feedback-from-2025-April)
- [03.00 - Databases](#Databases)
- - [03.01 - Flags Of The World (FOTW)](#Flags-Of-The-World-FOTW)
- [04.00 - Variants](#Variants)
- - [04.01 - Web applications](#Web-Applications)
- - [04.02 - Desktop applications](#Desktop-Applications)
- - [04.03 - Mobile applications](#Mobile-Applications)
- - [04.04 - Snapcraft](#Snapcraft)
- [05.00 - Current development target](#Current-development-target)
- [06.00 - Repository plan](#Repository-plan)
- [07.00 - LIBraries](#LIBraries)
- [08.00 - Installation](#Installation)
- [09.00 - Authors](#Authors)
- [10.00 - Credits](#Credits)
- [11.00 - Documentation](#Documentation)
- [12.00 - Vexillological humor](#Vexillological-humor)
- [13.00 - Concept from 2025.04.23](#Concept-2025.04.23)
- [14.00 - Common tags](#Common-tags)
- [15.00 - File Info](#File-info)
- [16.00 - File History](#File-history)
- [17.00 - Footer](#Footer)
- - [17.99 - EOF](#EOF)

***

<!-- /%/2001_TRANSLATE_SECTION.BEGIN\%\ !-->

## Read this article in a different language

<details open><summary><p><b>Click/tap here to expand/collapse the language switcher section</b></p></summary>

**Sorted by:** `A-Z`

[Sorting options unavailable](https://github.com/seanpm2001/Flag-Simulator/)

( [af Afrikaans](/.github/README_AF.md) Afrikaans | [sq Shqiptare](/.github/README_SQ.md) Albanian | [am አማርኛ](/.github/README_AM.md) Amharic | [ar عربى](/.github/README_AR.md) Arabic | [hy հայերեն](/.github/README_HY.md) Armenian | [az Azərbaycan dili](/.github/README_AZ.md) Azerbaijani | [eu Euskara](/.github/README_EU.md) Basque | [be Беларуская](/.github/README_BE.md) Belarusian | [bn বাংলা](/.github/README_BN.md) Bengali | [bs Bosanski](/.github/README_BS.md) Bosnian | [bg български](/.github/README_BG.md) Bulgarian | [ca Català](/.github/README_CA.md) Catalan | [ceb Sugbuanon](/.github/README_CEB.md) Cebuano | [ny Chichewa](/.github/README_NY.md) Chichewa | [zh-CN 简体中文](/.github/README_ZH-CN.md) Chinese (Simplified) | [zh-t 中國傳統的）](/.github/README_ZH-T.md) Chinese (Traditional) | [co Corsu](/.github/README_CO.md) Corsican | [hr Hrvatski](/.github/README_HR.md) Croatian | [cs čeština](/.github/README_CS.md) Czech | [da dansk](README_DA.md) Danish | [nl Nederlands](/.github/README_NL.md) Dutch | [**en-us English**](/.github/README.md) English |  [EO Esperanto](/.github/README_EO.md) Esperanto | [et Eestlane](/.github/README_ET.md) Estonian | [tl Pilipino](/.github/README_TL.md) Filipino | [fi Suomalainen](/.github/README_FI.md) Finnish |  [fr français](/.github/README_FR.md) French | [fy Frysk](/.github/README_FY.md) Frisian | [gl Galego](/.github/README_GL.md) Galician | [ka ქართველი](/.github/README_KA) Georgian | [de Deutsch](/.github/README_DE.md) German | [el Ελληνικά](/.github/README_EL.md) Greek | [gu ગુજરાતી](/.github/README_GU.md) Gujarati | [ht Kreyòl ayisyen](/.github/README_HT.md) Haitian Creole | [ha Hausa](/.github/README_HA.md) Hausa | [haw Ōlelo Hawaiʻi](/.github/README_HAW.md) Hawaiian | [he עִברִית](/.github/README_HE.md) Hebrew | [hi हिन्दी](/.github/README_HI.md) Hindi | [hmn Hmong](/.github/README_HMN.md) Hmong | [hu Magyar](/.github/README_HU.md) Hungarian | [is Íslenska](/.github/README_IS.md) Icelandic | [ig Igbo](/.github/README_IG.md) Igbo | [id bahasa Indonesia](/.github/README_ID.md) Icelandic | [ga Gaeilge](/.github/README_GA.md) Irish | [it Italiana/Italiano](/.github/README_IT.md) | [ja 日本語](/.github/README_JA.md) Japanese | [jw Wong jawa](/.github/README_JW.md) Javanese | [kn ಕನ್ನಡ](/.github/README_KN.md) Kannada | [kk Қазақ](/.github/README_KK.md) Kazakh | [km ខ្មែរ](/.github/README_KM.md) Khmer | [rw Kinyarwanda](/.github/README_RW.md) Kinyarwanda | [ko-south 韓國語](/.github/README_KO_SOUTH.md) Korean (South) | [ko-north 문화어](README_KO_NORTH.md) Korean (North) (NOT YET TRANSLATED) | [ku Kurdî](/.github/README_KU.md) Kurdish (Kurmanji) | [ky Кыргызча](/.github/README_KY.md) Kyrgyz | [lo ລາວ](/.github/README_LO.md) Lao | [la Latine](/.github/README_LA.md) Latin | [lt Lietuvis](/.github/README_LT.md) Lithuanian | [lb Lëtzebuergesch](/.github/README_LB.md) Luxembourgish | [mk Македонски](/.github/README_MK.md) Macedonian | [mg Malagasy](/.github/README_MG.md) Malagasy | [ms Bahasa Melayu](/.github/README_MS.md) Malay | [ml മലയാളം](/.github/README_ML.md) Malayalam | [mt Malti](/.github/README_MT.md) Maltese | [mi Maori](/.github/README_MI.md) Maori | [mr मराठी](/.github/README_MR.md) Marathi | [mn Монгол](/.github/README_MN.md) Mongolian | [my မြန်မာ](/.github/README_MY.md) Myanmar (Burmese) | [ne नेपाली](/.github/README_NE.md) Nepali | [no norsk](/.github/README_NO.md) Norwegian | [or ଓଡିଆ (ଓଡିଆ)](/.github/README_OR.md) Odia (Oriya) | [ps پښتو](/.github/README_PS.md) Pashto | [fa فارسی](/.github/README_FA.md) |Persian  [pl polski](/.github/README_PL.md) Polish | [pt português](/.github/README_PT.md) Portuguese | [pa ਪੰਜਾਬੀ](/.github/README_PA.md) Punjabi | No languages available that start with the letter Q | [ro Română](/.github/README_RO.md) Romanian | [ru русский](/.github/README_RU.md) Russian | [sm Faasamoa](/.github/README_SM.md) Samoan | [gd Gàidhlig na h-Alba](/.github/README_GD.md) Scots Gaelic | [sr Српски](/.github/README_SR.md) Serbian | [st Sesotho](/.github/README_ST.md) Sesotho | [sn Shona](/.github/README_SN.md) Shona | [sd سنڌي](/.github/README_SD.md) Sindhi | [si සිංහල](/.github/README_SI.md) Sinhala | [sk Slovák](/.github/README_SK.md) Slovak | [sl Slovenščina](/.github/README_SL.md) Slovenian | [so Soomaali](/.github/README_SO.md) Somali | [[es en español](/.github/README_ES.md) Spanish | [su Sundanis](/.github/README_SU.md) Sundanese | [sw Kiswahili](/.github/README_SW.md) Swahili | [sv Svenska](/.github/README_SV.md) Swedish | [tg Тоҷикӣ](/.github/README_TG.md) Tajik | [ta தமிழ்](/.github/README_TA.md) Tamil | [tt Татар](/.github/README_TT.md) Tatar | [te తెలుగు](/.github/README_TE.md) Telugu | [th ไทย](/.github/README_TH.md) Thai | [tr Türk](/.github/README_TR.md) Turkish | [tk Türkmenler](/.github/README_TK.md) Turkmen | [uk Український](/.github/README_UK.md) Ukrainian | [ur اردو](/.github/README_UR.md) Urdu | [ug ئۇيغۇر](/.github/README_UG.md) Uyghur | [uz O'zbek](/.github/README_UZ.md) Uzbek | [vi Tiếng Việt](/.github/README_VI.md) Vietnamese | [cy Cymraeg](/.github/README_CY.md) Welsh | [xh isiXhosa](/.github/README_XH.md) Xhosa | [yi יידיש](/.github/README_YI.md) Yiddish | [yo Yoruba](/.github/README_YO.md) Yoruba | [zu Zulu](/.github/README_ZU.md) Zulu ) Available in 110 languages (108 when not counting English and North Korean, as North Korean has not been translated yet [Read about it here](/OldVersions/Korean(North)/README.md))

Translations in languages other than English are machine translated and are not yet accurate. No errors have been fixed yet as of March 21st 2021. Please report translation errors [here](https://github.com/seanpm2001/<repoName>/issues/). Make sure to backup your correction with sources and guide me, as I don't know languages other than English well (I plan on getting a translator eventually) please cite [wiktionary](https://en.wiktionary.org) and other sources in your report. Failing to do so will result in a rejection of the correction being published.

Note: due to limitations with GitHub's interpretation of markdown (and pretty much every other web-based interpretation of markdown) clicking these links will redirect you to a separate file on a separate page that isn't the intended page. You will be redirected to the [.github folder](/.github/) of this project, where the README translations are hosted.

Translations are currently done with Bing translate and DeepL. Support for Google Translate translations is coming to a close due to privacy concerns.

</details> <!-- End of language switcher section !-->

<!-- /%/2001_TRANSLATION_SECTION.END\%\ !-->

***

<!-- /%/2001_THIS_REPOSITORY_SECTION.BEGIN\%\ !-->

## This repository

<details open><summary><p><b>Click/tap here to expand/collapse the this repository section</b></p></summary>

[`View all files`](/ROOTFILES.base)

| 📁️ Type 📄️ | 🔍️ Location 🔎️ | ℹ️ Purpose ℹ️ |
|---|---|---|
| 📁️ Folder/directory | [`/.github/`](/.github/) | GitHub repository configuration data |
| 📁️ Folder/directory | [`/.gitlab/`](/.gitlab/) | GitLab repository configuration data |
| 📁️ Folder/directory | [`/Docs/`](/Docs/) | For Flag Simulator documentation (redirect) |
| 📁️ Folder/directory | [`/LIB/`](/LIB/) | For Flag Simulator libraries |
| 📁️ Folder/directory | [`/OldVersions/`](/OldVersions/) | For archived old versions of files in this repository |
| 📁️ Folder/directory | [`/RepoData/`](/RepoData/) | For general repository data (metadata, description) |
| ⚙️ Configuration file | [`/.editorconfig`](/.editorconfig) | Editor Config file |
| ⚙️ Configuration file | [`/.gitattributes`](/.gitattributes) | Git Attributes file |
| ⚙️ Configuration file | [`/.gitignore`](/.gitignore) | Git Ignore file |
| 🌐️ Webpage file | [`/404.html`](/404.html) | 404 page |
| 🖼️ Image file | [`/404.jpeg`](/404.jpeg) | Image within 404 page |
| ⬇️ Markdown file | [`/404.md`](/404.md) | 404 Jekyll page |
| 👤️ Authors file | [`/AUTHORS`](/AUTHORS) | For displaying the authors of the project (plain text) |
| 👤️ Authors file | [`/AUTHORS.md`](/AUTHORS.md) | For displaying the authors of the project (Markdown) |
| 🤖️ Automation configuration file | [`/AUTOMATE2001.yaml`](/AUTOMATE2001.yaml) | For configuring the AUTOMATE2001 software tool to automate tasks on this repository. |
| 🤖️ Automation configuration file | [`/AUTOMATE2001.yml`](/AUTOMATE2001.yml) | For configuring the AUTOMATE2001 software tool to automate tasks on this repository (copy) |
| 📋️ Repository list file | [`/Flag-Simulator_REPOLIST.urll`](/Flag-Simulator_REPOLIST.urll) | For displaying a list of all repositories in this project group. |
| 🖼️ Image file | [`/Flag-Simulator_PlaceholderLogo.svg`](/Flag-Simulator_PlaceholderLogo.svg) | A placeholder logo of a light blue flag |
| ✒️ Citation file | [`/CITATION.cff`](/CITATION.cff) | For enabling others to site this repository. |
| 👥️ Contributions file | [`/CONTRIBUTING.md`](/CONTRIBUTING.md) | For listing instructions on what can/cannot be contributed to this project. |
| 💳️ License file | [`/COPYINGL`](/COPYINGL) | A license hub that explains license usage for this project. |
| 👤️ Credits file | [`/Credits`](/Credits) | For displaying the credits for the project (plain text) |
| 👤️ Credits file | [`/Credits.wiki`](/Credits.wiki) | For displaying the credits for the project (WikiText) |
| 🖼️ Image file | [`/DRM-free_label.en.svg`](/DRM-free_label.en.svg) | An image file that emphasizes this projects Anti-DRM stance. |
| 1️⃣️ Initial file | [`/INITIAL_COMMIT.txt`](/INITIAL_COMMIT.txt) | A file that was generated alongside the repository, and represents the first commit |
| 🔺️ Installation file | [`/INSTALL`](/INSTALL) | A file that gives instructions on how to install this project (plain text) |
| 🔺️ Installation file | [`/INSTALL.rst`](/INSTALL.rst) | A file that gives instructions on how to install this project (reStructuredText) |
| 🖥️ Linux Desktop entry file | [`/K.desktop`](/K.desktop) | A Linux desktop entry file for this project, allowing it to be easily launched on UNIX-like systems |
| 💳️ License file | [`/LICENSE-GPL.py`](/LICENSE-GPL.py) | A GNU GPL3 license file for this project, with a Python file extension |
| 💳️ License file | [`/LICENSE-GPL.py3`](/LICENSE-GPL.py3) | A GNU GPL3 license file for this project, with a Python file extension |
| 💳️ License file | [`/LICENSE-GPL.pyt`](/LICENSE-GPL.pyt) | A GNU GPL3 license file for this project, with a Python file extension |
| 💳️ License file | [`/LICENSE-GPL.txt`](/LICENSE-GPL.txt) | A GNU GPL3 license file for this project, with the Plain Text file extension |
| 💳️ License file | [`/LICENSE-GPL.pyw`](/LICENSE-GPL.pyw) | A GNU GPL3 license file for this project, with a Python file extension |
| 💳️ License file | [`/LICENSE-GPL3.py`](/LICENSE-GPL3.py) | A GNU GPL3 license file for this project, with a Python file extension |
| 💳️ License file | [`/LICENSE-GPL3.py3`](/LICENSE-GPL3.py3) | A GNU GPL3 license file for this project, with a Python file extension |
| 💳️ License file | [`/LICENSE-GPL3.pyt`](/LICENSE-GPL3.pyt) | A GNU GPL3 license file for this project, with a Python file extension |
| 💳️ License file | [`/LICENSE-GPL3.txt`](/LICENSE-GPL3.txt) | A GNU GPL3 license file for this project, with the Plain Text file extension |
| 💳️ License file | [`/LICENSE-GPL3.pyw`](/LICENSE-GPL3.pyw) | A GNU GPL3 license file for this project, with a Python file extension |
| 💳️ License file | [`/LICENSE.py`](/LICENSE.py) | A GNU GPL3 license file for this project, with a Python file extension |
| 💳️ License file | [`/LICENSE.py3`](/LICENSE.py3) | A GNU GPL3 license file for this project, with a Python file extension |
| 💳️ License file | [`/LICENSE.pyt`](/LICENSE.pyt) | A GNU GPL3 license file for this project, with a Python file extension |
| 💳️ License file | [`/LICENSE.txt`](/LICENSE.txt) | A GNU GPL3 license file for this project, with the Plain Text file extension |
| 💳️ License file | [`/LICENSE.pyw`](/LICENSE.pyw) | A GNU GPL3 license file for this project, with a Python file extension |
| ⭐️ README file | [`/README.md`](/README.md) | The main README.md file for this project, explaining how to use this project, and where to start. |
| 📜️ Rootfiles list file | [`/ROOTFILES.base`](/ROOTFILES.base) | The ROOTFILES base file for this project, listing all files and folders at the root of this repository. |
| 🛡️ Security file | [`/SECURITY.md`](/SECURITY.md) | For listing security information for this project. |
| 🖼️ Image file | [`/SponsorButton.png`](/SponsorButton.png) | An image file that shows the GitHub sponsor button in this project. |
| 1️⃣️ Initial file | [`/Temolate-Python-Other.md`](/Template-Python-Other.md) | An initial file, indicating which branch of the generation template was used to create this repository. |
| ⚙️ Configuration file | [`/_config.yml`](/_config.yml) | A configuration file for the Jekyll theme on this project. |
| 🖥️ Windows Desktop entry file | [`/desktop.ini`](/desktop.ini) | The Windows desktop entry file for this project. |
| 🔨️ Makefile | [`/makefile.mk`](/makefile.mk) | The main GNU Make build file for this project. |
| 📃️ Pull request template | [`/pull_request_template.md`](/pull_request_template.md) | The pull request template file for this project, a template for starting a Git pull request. |
| **📁️ Type 📄️** | **🔍️ Location 🔎️** | **ℹ️ Purpose ℹ️** |

</details> <!-- End of this repository section !-->

<!-- /%/2001_THIS-REPOSITORY_SECTION.END\%\ !-->

***

## Features

<details open><summary><p><b>Click/tap here to expand/collapse the features section</b></p></summary>

### Featured flags

<details open><summary><p><b>Click/tap here to expand/collapse the featured flags section</b></p></summary>

- [ ] Developed?

Featured flag (default flag upon starting program on certain days)

Examples:

- May 5th: Flag of Mexico 🇲🇽️
- August 24th: Flag of Ukraine 🇺🇦️

### Flag physics

<details open><summary><p><b>Click/tap here to expand/collapse the flag physics section</b></p></summary>

- [ ] Developed?

Change the physics of the flag.

- [ ] Flag direction
- [ ] Wind direction
- [ ] Wind control
- [ ] Pressure

### Flag direction

<details open><summary><p><b>Click/tap here to expand/collapse the flag direction section</b></p></summary>

- [ ] Developed?

Change the orientation in which the flag is hung.

</details> <!-- End of feature:flag direction section !-->

### Wind direction

<details open><summary><p><b>Click/tap here to expand/collapse the wind direction section</b></p></summary>

- [ ] Developed?

Change the direction that the wind is blowing in

</details> <!-- End of feature:wind direction section !-->

### Wind control

<details open><summary><p><b>Click/tap here to expand/collapse the wind control section</b></p></summary>

- [ ] Developed?

Change the speed, cycle, and gusts of the wind.

</details> <!-- End of feature:wind control section !-->

### Barometric pressure

<details open><summary><p><b>Click/tap here to expand/collapse the barometric pressure section</b></p></summary>

- [ ] Developed?

Apply different degrees of barometric pressure to the flag environment.

</details> <!-- End of feature:barometric pressure section !-->

### Different backgrounds

<details open><summary><p><b>Click/tap here to expand/collapse the different backgrounds section</b></p></summary>

- [ ] Developed?

Change the background scenery from a collection of built-in images, or upload your own.

For desktop/mobile apps, a folder called `/Backgrounds/Custom/Images/` will be created.

</details> <!-- End of feature:different backgrounds section !-->

### Background videos

<details open><summary><p><b>Click/tap here to expand/collapse the background videos section</b></p></summary>

- [ ] Developed?

Change the background scenery from a collection of built-in videos, or upload your own.

For desktop/mobile apps, a folder called `/Backgrounds/Custom/Videos/` will be created.

</details> <!-- End of feature:background videos section !-->

### Export

<details open><summary><p><b>Click/tap here to expand/collapse the export section</b></p></summary>

- [ ] Developed?

Export your flag to a separate file in either FlagW or another image format.

</details> <!-- End of feature:export section !-->

### Embed into a webpage

<details open><summary><p><b>Click/tap here to expand/collapse the embed into a webpage section</b></p></summary>

- [ ] Developed?

Embed your custom waving flag into a webpage, program, or social media post.

</details> <!-- End of feature:embed into a webpage section !-->

### Database of flags

<details open><summary><p><b>Click/tap here to expand/collapse the database of flags section</b></p></summary>

- [ ] Developed?

Choose from a database of flags, or upload your own. Built-in sources will contain all national flags, while expanions are available to include flags from FOTW (Flags Of The World)

</details> <!-- End of feature:database of flags section !-->

### Upload custom flags

<details open><summary><p><b>Click/tap here to expand/collapse the upload custom flags section</b></p></summary>

- [ ] Developed?

Upload a custom image to use as a flag.

</details> <!-- End of feature:upload custom flags section !-->

### Pennants

<details open><summary><p><b>Click/tap here to expand/collapse the pennants section</b></p></summary>

- [ ] Developed?

Fly a pennant in place of a flag.

</details> <!-- End of feature:pennants section !-->

### Multiple flags

<details open><summary><p><b>Click/tap here to expand/collapse the multiple flags section</b></p></summary>

- [ ] Developed?

Fly multiple flags at once, either on the same pole, or on separate poles.

</details> <!-- End of feature:multiple flags section !-->

### Information on each flag

<details open><summary><p><b>Click/tap here to expand/collapse the information on each flag section</b></p></summary>

- [ ] Developed?

Get information on each flag from a built-in database, and learn the meaning of each flag, its history, and its guidelines.

</details> <!-- End of feature:information on each flag section !-->

### FlagW file (waving flag data file)

<details open><summary><p><b>Click/tap here to expand/collapse the FlagW file section</b></p></summary>

- [ ] Developed?

A custom file format for displaying a waving flag.

| File type |
|---|
| `*.flagw` |

The file can contain flag poles, flags, and description data individually, or altogether.

</details> <!-- End of feature:FlagW file section !-->

### Flag burning

<details open><summary><p><b>Click/tap here to expand/collapse the Flag burning section</b></p></summary>

- [ ] Developed?

A built-in animation that adds a burning animation to flags. Users can choose whether it burns permanently without causing damage, or if burns the flag, and even if it burns the pole.

</details> <!-- End of feature:flag burning section !-->

### Information on religious flags

<details open><summary><p><b>Click/tap here to expand/collapse the Information on religious flags section</b></p></summary>

- [ ] Developed?

Built-in information on religious flags, and their guidelines. For example, the Flag of Saudi Arabia cannot be flown at half-mast, as it contains a religious symbol on it (the shahada) and is considered disrespectful to Islam to put this symbol down.

</details> <!-- End of feature:information on religious flags section !-->

### Flag tearing

<details open><summary><p><b>Click/tap here to expand/collapse the flag tearing section</b></p></summary>

- [ ] Developed?

A built-in animation that lets you tear pieces of the flag. Choose the type of material first.

- Cloth
- Paper
- Vinyl
- ETC

</details> <!-- End of feature:flag tearing section !-->

### Half mast

<details open><summary><p><b>Click/tap here to expand/collapse the half mast section</b></p></summary>

- [ ] Developed?

Lower the flag to half-mast to indicate mourning.

</details> <!-- End of feature:half mast section !-->

### Raising/lowering

<details open><summary><p><b>Click/tap here to expand/collapse the raising/lowering section</b></p></summary>

- [ ] Developed?

Raise/lower the flag.

</details> <!-- End of feature:raising/lowering section !-->

### Customizable flag poles

<details open><summary><p><b>Click/tap here to expand/collapse the customizable flag poles section</b></p></summary>

- [ ] Developed?

Customize the graphics of the flag pole, its material, and its appearance.

</details> <!-- End of feature:customizable flag poles section !-->

### Totem pole library

<details open><summary><p><b>Click/tap here to expand/collapse the totem pole library section</b></p></summary>

- [ ] Developed?

Customize the flag pole by giving it a Totem Pole style. A Totem Pole graphics library will be built-in.

</details> <!-- End of feature:totem pole library section !-->

### Flag poles

<details open><summary><p><b>Click/tap here to expand/collapse the flag poles section</b></p></summary>

- [ ] Developed?

Change between flag pole mode, and flag lying on the ground mode.

</details> <!-- End of feature:flag poles section !-->

### SVG, PNG, JPEG, GIF, TIFF, BMP, WEBP, NETP, ICO, GIF_C200, among other supported formats

<details open><summary><p><b>Click/tap here to expand/collapse the image file format support section</b></p></summary>

- [ ] Developed?

Allows for importing and exporting flags through various file formats.

- [ ] Support for importing/exporting flags as SVG
- [ ] Support for importing/exporting flags as SVG (animated)
- [ ] Support for importing/exporting flags as PNG
- [ ] Support for importing/exporting flags as PNG (animated)
- [ ] Support for importing/exporting flags as JPEG
- [ ] Support for importing/exporting flags as GIF
- [ ] Support for importing/exporting flags as GIF (animated)
- [ ] Support for importing/exporting flags as TIFF
- [ ] Support for importing/exporting flags as BMP
- [ ] Support for importing/exporting flags as WEBP
- [ ] Support for importing/exporting flags as NETP
- [ ] Support for importing/exporting flags as ICO
- [ ] Support for importing/exporting flags as GIF_C200

</details> <!-- End of feature:image file format support section !-->

### Various buttons

<details open><summary><p><b>Click/tap here to expand/collapse the various buttons section</b></p></summary>

- [ ] Developed?

A set of buttons on the UI that do various things, such as change dimensions, open up flag pole or flag libraries, open up accessories, change the background, and more.

</details> <!-- End of feature:various buttons section !-->

### Ability to send an army to take down the flag

<details open><summary><p><b>Click/tap here to expand/collapse the ability to send an army to take down the flag section</b></p></summary>

- [ ] Developed?

A button that lets the user summon a custom army to try and take down the flag. Users can add a garrison to their flag to make it a fight, or just have the enemy come and take it down. The user can choose which flag the enemy flies in its place, and what the enemy does with the flag.

</details> <!-- End of feature:ability to send an army to take down the flag section !-->

### Offline functionality

<details open><summary><p><b>Click/tap here to expand/collapse the offline functionality section</b></p></summary>

- [ ] Developed?

Allow the program to work completely offline.

</details> <!-- End of feature:offline functionality section !-->

### Rain and weather effects

<details open><summary><p><b>Click/tap here to expand/collapse the rain and weather effects section</b></p></summary>

- [ ] Developed?

Display various weather types, and allow the flag to be simulated or not alongside them, as a decorative piece, or as a functional piece. Choose whether the flag is damaged or not from this.

- [ ] Rain effects
- [ ] Hail effects
- [ ] Lightning effects
- [ ] Snow effects

</details> <!-- End of feature:rain and weather effects section !-->

### Play audio (national anthems, and anthem library)

<details open><summary><p><b>Click/tap here to expand/collapse the play audio section</b></p></summary>

- [ ] Developed?

Play custom audio for the flag, or use a built-in library, mostly consisting of background music and anthems.

- [ ] Anthem library
- [ ] Ambient library
- [ ] Sound effect library

Choose to play flag sound effects

</details> <!-- End of feature:play audio section !-->

### Simulate real weather (with weather services, and data files for weather events)

<details open><summary><p><b>Click/tap here to expand/collapse the simulate real weather section</b></p></summary>

- [ ] Developed?

Simulate weather on your flag with weather services, and data files from current, past, and future weather events (unknown file format)

</details> <!-- End of feature:simulate real weather section !-->

### Flag construction mode

<details open><summary><p><b>Click/tap here to expand/collapse the flag construction mode section</b></p></summary>

- [ ] Developed?

Go into flag construction mode, and see flag construction sheets, and how they go into making a flag.

</details> <!-- End of feature:flag construction section !-->

### Flag folding

<details open><summary><p><b>Click/tap here to expand/collapse the flag folding section</b></p></summary>

- [ ] Developed?

Fold up your flag, and unfold it.

</details> <!-- End of feature:flag folding section !-->

### Lighting, lighting modes

<details open><summary><p><b>Click/tap here to expand/collapse the lighting, lighting modes section</b></p></summary>

- [ ] Developed?

Adjust the lighting around your flag, and change the lighting mode.

</details> <!-- End of feature:lighting, lighting modes section !-->

### Shine a light

<details open><summary><p><b>Click/tap here to expand/collapse the shine a light section</b></p></summary>

- [ ] Developed?

Shine a light on your flag with a searchlight.

</details> <!-- End of feature:shine alight section !-->

### Flashlight (movable with cursor/finger)

<details open><summary><p><b>Click/tap here to expand/collapse the flashlight section</b></p></summary>

- [ ] Developed?

A custom accessory, which gives the user a flashlight, which is movable with a cursor or a finger, which will position the light onto the flag. Gesture support coming soon.

</details> <!-- End of feature:flashlight section !-->

### Customizable flashlight, different light colors, sizes, strengths of light

<details open><summary><p><b>Click/tap here to expand/collapse the customizable flashlight section</b></p></summary>

- [ ] Developed?

Customize the flash light accessory by giving it different colored lights, different sizes (and therefore different amounts of light) along with different strengths of light.

</details> <!-- End of feature:customizable flashlight section !-->

### Flag weaving

<details open><summary><p><b>Click/tap here to expand/collapse the flag weaving section</b></p></summary>

> ***Not to be confused with flag waving***

- [ ] Developed?

Design and weave a flag within the program, through flag construction mode.

</details> <!-- End of feature:flag weaving section !-->

### Buy an actual flag (based on the one shown)

<details open><summary><p><b>Click/tap here to expand/collapse the buy an actual flag section</b></p></summary>

- [ ] Developed?

A third-party feature, which allows the user to go out and buy a flag either from the flag library, or through a custom upload. Through the flag library, a catalog of flag websites will be shown that can allow the user to buy a similar flag. The mechanics for buying a custom flag are not yet known. Both options result in a physical flag being delivered to the user.

</details> <!-- End of feature:buy an actual flag section !-->

### FIAV flag

<details open><summary><p><b>Click/tap here to expand/collapse the FIAV flag section</b></p></summary>

- [ ] Developed?

When the option to not choose a flag based on what day of the year it is is not checked, or is unavailable due to time settings, the FIAV flag (International Federation of Vexillological Associations) can be chosen as a default flag to show.

</details> <!-- End of feature:FIAV flag section !-->

### Default flag

<details open><summary><p><b>Click/tap here to expand/collapse the default flag section</b></p></summary>

- [ ] Developed?

Change the default flag on the homepage to a different flag, and choose whether it appears each time. Include an option that lets the last flag shown be displayed.

</details> <!-- End of feature:default flag section !-->

### Homepage

<details open><summary><p><b>Click/tap here to expand/collapse the homepage section</b></p></summary>

- [ ] Developed?

A flag homepage for the program.

</details> <!-- End of feature:homepage section !-->

### Fire arrows

<details open><summary><p><b>Click/tap here to expand/collapse the fire arrows section</b></p></summary>

- [ ] Developed?

An accessory that allows fire arrows to be shot at the flag. Similar to the flag burning effect, users can choose whether the fire actually does damage, and also can choose if the arrow can pierce the flag or not.

</details> <!-- End of feature:fire arrows section !-->

### Other items to throw

<details open><summary><p><b>Click/tap here to expand/collapse the other items to throw section</b></p></summary>

- [ ] Developed?

More accessories for different items to throw at the flag.

</details> <!-- End of feature:other items to throw section !-->

### Flag Emoji mode

<details open><summary><p><b>Click/tap here to expand/collapse the flag Emoji mode section</b></p></summary>

- [ ] Developed?

Enable flag Emoji mode to show flag Emojis as waving flags.

</details> <!-- End of feature:flag Emoji mode section !-->

### Flag Emoji import

<details open><summary><p><b>Click/tap here to expand/collapse the flag Emoji import section</b></p></summary>

- [ ] Developed?

Import different flag Emoji styles, and wave them as flags.

</details> <!-- End of feature:flag Emoji support section !-->

### Flag search (search for a flag, Emojis also work as a search option)

<details open><summary><p><b>Click/tap here to expand/collapse the flag search section</b></p></summary>

- [ ] Developed?

Search for a flag through a text search within the program, or with an Emoji, which will also work as a search option. Regional Indicator Letters are also a valid search query.

</details> <!-- End of feature:flag search section !-->

### User interface skins

<details open><summary><p><b>Click/tap here to expand/collapse the user interface skins section</b></p></summary>

- [ ] Developed?

Add a different user interface to the program by choosing a different skin, stored as a data file.

</details> <!-- End of feature:user interface skins section !-->

### Censorship modes for hate flags, Socialist/Communist flags, terrorist flags, etc

<details open><summary><p><b>Click/tap here to expand/collapse the censorship modes section</b></p></summary>

- [ ] Developed?

Censorship settings to enable/disable flags, such as flags of hate groups, flags of Socialist/Communist groups, flags associated with terrorism, flags associated with religion, or another reason.

</details> <!-- End of feature:censorship modes section !-->

### Age rating

<details open><summary><p><b>Click/tap here to expand/collapse the age rating section</b></p></summary>

- [ ] Developed?

Choose an age rating for this project, based on the [:octocat: `Open Media Rating System`](https://github.com/seanpm2001/Open-Media-Rating-System/)

</details> <!-- End of feature:age rating section !-->

### Desktop application (with ports in Python, Java, C, and Rust)

<details open><summary><p><b>Click/tap here to expand/collapse the desktop application section</b></p></summary>

- [ ] Developed?

Develop desktop applications for this project. [See below](#Variants)

</details> <!-- End of feature:desktop application section !-->

### Web application (with ports in Ruby, JavaScript, PHP, and WebAssembly)

<details open><summary><p><b>Click/tap here to expand/collapse the web application section</b></p></summary>

- [ ] Developed?

Develop web applications for this project. [See below](#Variants)

</details> <!-- End of feature:web application section !-->

### Mobile application (with ports in Java, Kotlin, Swift, and C)

<details open><summary><p><b>Click/tap here to expand/collapse the mobile application section</b></p></summary>

- [ ] Developed?

Develop mobile applications for this project. [See below](#Variants)

</details> <!-- End of feature:mobile application section !-->

### Flag text and copy text from flag

<details open><summary><p><b>Click/tap here to expand/collapse the flag text and copy text from flag section</b></p></summary>

- [ ] Developed?

Copy the text from the flag, and copy other pieces of text related to the flag.

</details> <!-- End of feature:flag text section !-->

### ASCII mode, with text color toggle

<details open><summary><p><b>Click/tap here to expand/collapse the ASCII mode section</b></p></summary>

- [ ] Developed?

Enter ASCII mode, to have the flag be shown purely with text, along with a toggle to enable different text colors. Also export as ASCIInema video files.

</details> <!-- End of feature:ASCII mode section !-->

### Creating large flags (up to worlds largest)

<details open><summary><p><b>Click/tap here to expand/collapse the creating large flags section</b></p></summary>

- [ ] Developed?

Create large flag graphics via the flagw file format, and the flag displayer. See below: size limit.

</details> <!-- End of feature:creating large flags section !-->

### Size limit: whatever your system can handle (even 1,000,000m by 1,000,000m would be allowed) theoretical end at 9,223,372,036,854,775,807 (2^64) square pixels

<details open><summary><p><b>Click/tap here to expand/collapse the size limit section</b></p></summary>

- [ ] Developed?

Create flags from either 1x1 pixels up to 9,223,372,036,854,775,807 square pixels (? dimensions) the default setting is defined in the image file chosen.

</details> <!-- End of feature:size limit section !-->

### Flag code dictionary

<details open><summary><p><b>Click/tap here to expand/collapse the Flag code dictionary section</b></p></summary>

- [ ] Developed?

View a dictionary that shows the flag code for various flags.

</details> <!-- End of feature:flag code dictionary section !-->

### Flag creator: Your own flag (built-in editor) add description, colors, shapes, graphics, text mode, description, and flag code

<details open><summary><p><b>Click/tap here to expand/collapse the Flag creator section</b></p></summary>

- [ ] Developed?

Enter the flag creator, where you can create your own flag, with a built-in vector and Bitmap graphics editor. Therr is a toggle between vector and bitmap. A description can be added, colors can be customized, shapes and other graphics can be appended, text can be entered, a different font can be chosen, the flag can be given a description, and the flag can even be given its own flag code.

</details> <!-- End of feature:flag creator section !-->

### Color modes: monochrome, 4 bit, 5 bit, 6 bit, 7 bit, 8 bit, 12 bit, 16 bit, 24 bit, 32 bit, 48 bit, 64 bit

<details open><summary><p><b>Click/tap here to expand/collapse the Color modes section</b></p></summary>

- [ ] Developed?

Change the color mode of the program, or just the flag. Available option:

- [ ] Monochrome (2 color) mode
- [ ] 4 bit (16 color) mode
- [ ] 5 bit (32 color) mode
- [ ] 6 bit (64 color) mode
- [ ] 7 bit (128 color) mode
- [ ] 8 bit (256 color) mode
- [ ] 12 bit (4096 color) mode
- [ ] 16 bit (65536 color) mode
- [ ] 24 bit (16777216 color) mode
- [ ] 32 bit (4294967296 color) mode
- [ ] 48 bit (281474976710656 color) mode
- [ ] 64 bit (9223372036854775807 color) mode

</details> <!-- End of feature:color modes section !-->

### Filters

<details open><summary><p><b>Click/tap here to expand/collapse the filters section</b></p></summary>

- [ ] Developed?

Choose between different filters to display your flag alongside.

- [ ] Confetti filter
- [ ] Other

</details> <!-- End of feature:filters section !-->

### Slideshow mode

<details open><summary><p><b>Click/tap here to expand/collapse the slideshow mode section</b></p></summary>

- [ ] Developed?

Enter slideshow mode, and showcase a slideshow of flags, flag backgrounds, or both.

</details> <!-- End of feature:slideshow mode section !-->

### Customize the area around the flag pole

<details open><summary><p><b>Click/tap here to expand/collapse the customize the area around the flag pole section</b></p></summary>

- [ ] Developed?

Customize the area around the flag pole by adding different objects (such as accessories) and other graphics around the base.

</details> <!-- End of feature:customize the area around the flag pole section !-->

### Multiple flag poles

<details open><summary><p><b>Click/tap here to expand/collapse the multiple flag poles section</b></p></summary>

- [ ] Developed?

Add support for multiple flag poles at once.

</details> <!-- End of feature:multiple flag poles section !-->

### Flag pole size

<details open><summary><p><b>Click/tap here to expand/collapse the flag pole size section</b></p></summary>

- [ ] Developed?

Change the size of the flag pole, both perimeter, width, and height

</details> <!-- End of feature:flag pole size section !-->

### Flag pole material (metal, wood, etc.)

<details open><summary><p><b>Click/tap here to expand/collapse the flag pole material section</b></p></summary>

- [ ] Developed?

Change the material of the flag pole, to a material such as metal, wood, plastic, stone, or something else.

</details> <!-- End of feature:flag pole material section !-->

### Flag pole material download

<details open><summary><p><b>Click/tap here to expand/collapse the flag pole material download section</b></p></summary>

- [ ] Developed?

Download the material file for the flag pole.

</details> <!-- End of feature:flag pole material download section !-->

### Dimensional modes: 2D, 3D, 4D

<details open><summary><p><b>Click/tap here to expand/collapse the Dimensional modes section</b></p></summary>

- [ ] Developed?

Change the dimensions of the program with a toggle to either 2D, 3D or 4D

</details> <!-- End of feature:dimensional modes section !-->

### Scissors, knives, and swords

<details open><summary><p><b>Click/tap here to expand/collapse the Scissors, knives, and swords section</b></p></summary>

- [ ] Developed?

Use scissors, knives, and swords as accessories to attack the flag(s)

</details> <!-- End of feature:scissors knives and swords section !-->

### Acid raid effect

<details open><summary><p><b>Click/tap here to expand/collapse the Acid rain effect section</b></p></summary>

- [ ] Developed?

Enable the acid rain effect to have acid rain come down on your flag(s).

</details> <!-- End of feature:acid rain effect section !-->

### Fun facts about Vexillology in the UI

<details open><summary><p><b>Click/tap here to expand/collapse the fun facts about vexillology section</b></p></summary>

- [ ] Developed?

Showcase fun facts about vexillology within the programs user interface.

</details> <!-- End of feature:fun factS about vexillology section !-->

### Accessories menu and the ability to import new ones (built-in: scissors, knives, swords, fire arrows, flashlight)

<details open><summary><p><b>Click/tap here to expand/collapse the accessories menu section</b></p></summary>

- [ ] Developed?

Enable the accessories menu to use different accessories, and to import new accessories for use in the program.

Built-in accessories include:

- [ ] Scissors
- [ ] Knives
- [ ] Swords
- [ ] Fire arrows
- [ ] Flashlight

</details> <!-- End of feature:accessories menu section !-->

### Accessory files: a specialized data file for the project

<details open><summary><p><b>Click/tap here to expand/collapse the accessory files section</b></p></summary>

- [ ] Developed?

Use accessory files to enable custom effects into the program, and use different accessories besides the 5 built-in ones.

A gun accessory will be included separately, and will not be built-in, to keep the main program more friendly to a wider audience (although the flag of Mozambique will still be built in, despite having a gun on it)

</details> <!-- End of feature:accessory files section !-->

### Transparency level

<details open><summary><p><b>Click/tap here to expand/collapse the transparency level section</b></p></summary>

- [ ] Developed?

Change the transparency/opacity of the flag, the flagpole, or both.

</details> <!-- End of feature:transparency level section !-->

### Flag stamps

<details open><summary><p><b>Click/tap here to expand/collapse the flag stamps section</b></p></summary>

- [ ] Developed?

Suggested by [:octocat: `@MemeWallaWalla`](https://github.com/memewallawalla/)

A work in progress feature that involves flag stamps.

</details> <!-- End of feature:flag stamps section !-->

---

_End of feature listing._

</details> <!-- End of Features section !-->

***

## Feedback

<details open><summary><p><b>Click/tap here to expand/collapse the Feedback section</b></p></summary>

Feedback for this project.

### Feedback from 2025, April

<details open><summary><p><b>Click/tap here to expand/collapse the feedback from 2025, April section</b></p></summary>

Reminder that this project suits a limited audience

Feature idea: Flag stamps

**Reference:**

> [`Early preview documents used to gather feedback (from 2025, April 28th to 2025, May 4th)`](/Docs/Idea-List/1-100/)

</details> <!-- End of Feedback from 2025, April section !-->

[:octocat: `Send feedback`](https://github.com/seanpm2001/Flag-Simulator/discussions/)

_End of feedback_

</details> <!-- End of feedback section !-->

***

## Databases

<details open><summary><p><b>Click/tap here to expand/collapse the Databases section</b></p></summary>

Custom databases that can be used within the Flag Simulator project.

### Flags Of The World (FOTW)

<details open><summary><p><b>Click/tap here to expand/collapse the Flags of the World (FOTW) database section</b></p></summary>

Repository listing:

- [:octocat: `Flag-Simulator_DB_FOTW`](https://github.com/seanpm2001/Flag-Simulator_DB_FOTW/)
- - [:octocat: `Flag-Simulator_DB_FOTW_Docs`](https://github.com/seanpm2001/Flag-Simulator_DB_FOT_Doc/)

</details> <!-- End of FOTW database section !-->

---

_End of database listing._

</details> <!-- End of Databases section !-->

***

## Variants

<details open><summary><p><b>Click/tap here to expand/collapse the Variants section</b></p></summary>

See: [`Flag-Simulator_REPOLIST.urll`](/Flag-Simulator_REPOLIST.urll/)

### Web Applications

<details open><summary><p><b>Click/tap here to expand/collapse the Web Applications section</b></p></summary>

- [:octocat: `Flag-Simulator_WebApp_JavaScript`](https://github.com/seanpm2001/Flag-Simulator_WebApp_JavaScript/)
- - [:octocat: `Flag-Simulator_WebApp_JavaScript_Docs`](https://github.com/seanpm2001/Flag-Simulator_WebApp_JavaScript_Docs/)
- [:octocat: `Flag-Simulator_WebApp_Ruby`](https://github.com/seanpm2001/Flag-Simulator_WebApp_Ruby/)
- - [:octocat: `Flag-Simulator_WebApp_Ruby_Docs`](https://github.com/seanpm2001/Flag-Simulator_WebApp_Ruby_Docs/)
- [:octocat: `Flag-Simulator_WebApp_PHP`](https://github.com/seanpm2001/Flag-Simulator_WebApp_PHP/)
- - [:octocat: `Flag-Simulator_WebApp_PHP_Docs`](https://github.com/seanpm2001/Flag-Simulator_WebApp_PHP_Docs/)
- [:octocat: `Flag-Simulator_WebApp_WebAssembly`](https://github.com/seanpm2001/Flag-Simulator_WebApp_WebAssembly/)
- - [:octocat: `Flag-Simulator_WebApp_WebAssembly_Docs`](https://github.com/seanpm2001/Flag-Simulator_WebApp_WebAssembly_Docs/)

</details> <!-- End of Web Applications section !-->

### Desktop Applications

<details open><summary><p><b>Click/tap here to expand/collapse Desktop Web Applications section</b></p></summary>

- [:octocat: `Flag-Simulator_DesktopApp_Python`](https://github.com/seanpm2001/Flag-Simulator_DesktopApp_Python/)
- - [:octocat: `Flag-Simulator_DesktopApp_Python_Docs`](https://github.com/seanpm2001/Flag-Simulator_DesktopApp_Python_Docs/)
- [:octocat: `Flag-Simulator_DesktopApp_Java`](https://github.com/seanpm2001/Flag-Simulator_DesktopApp_Java/)
- - [:octocat: `Flag-Simulator_DesktopApp_Java_Docs`](https://github.com/seanpm2001/Flag-Simulator_DesktopApp_Java_Docs/)
- [:octocat: `Flag-Simulator_DesktopApp_C`](https://github.com/seanpm2001/Flag-Simulator_DesktopApp_C/)
- - [:octocat: `Flag-Simulator_DesktopApp_C_Docs`](https://github.com/seanpm2001/Flag-Simulator_DesktopApp_C_Docs/)
- [:octocat: `Flag-Simulator_DesktopApp_Rust`](https://github.com/seanpm2001/Flag-Simulator_DesktopApp_Rust/)
- - [:octocat: `Flag-Simulator_DesktopApp_Rust_Docs`](https://github.com/seanpm2001/Flag-Simulator_DesktopApp_Rust_Docs/)

</details> <!-- End of Desktop Applications section !-->

### Mobile Applications

<details open><summary><p><b>Click/tap here to expand/collapse the Mobile Applications section</b></p></summary>

- [:octocat: `Flag-Simulator_MobileApp_Java`](https://github.com/seanpm2001/Flag-Simulator_MobileApp_Java/)
- - [:octocat: `Flag-Simulator_MobileApp_Java_Docs`](https://github.com/seanpm2001/Flag-Simulator_MobileApp_Java_Docs/)
- [:octocat: `Flag-Simulator_MobileApp_Kotlin`](https://github.com/seanpm2001/Flag-Simulator_MobileApp_Kotlin/)
- - [:octocat: `Flag-Simulator_MobileApp_Kotlin_Docs`](https://github.com/seanpm2001/Flag-Simulator_MobileApp_Kotlin_Docs/)
- [:octocat: `Flag-Simulator_MobileApp_Swift`](https://github.com/seanpm2001/Flag-Simulator_MobileApp_Swift/)
- - [:octocat: `Flag-Simulator_MobileApp_Swift_Docs`](https://github.com/seanpm2001/Flag-Simulator_MobileApp_Swift_Docs/)
- [:octocat: `Flag-Simulator_MobileApp_C`](https://github.com/seanpm2001/Flag-Simulator_MobileApp_C/)
- - [:octocat: `Flag-Simulator_MobileApp_C_Docs`](https://github.com/seanpm2001/Flag-Simulator_MobileApp_C_Docs/)

</details> <!-- End of Mobile Applications section !-->

### Snapcraft

<details open><summary><p><b>Click/tap here to expand/collapse the Snapcraft section</b></p></summary>

**Will there be a Snapcraft version?**

- Not officially. I won't create one, as I have grown to dislike snapcraft a whole lot since I began using Ubuntu back in 2020, but I wouldn't oppose a community snap build if it was developed by someone else. Snapcraft may be convenient for portability between different Linux distributions, but it goes against free software standards, as it is proprietary, doesn't give the user a choice on things like updates, and is additionally generally more unstable than a normal Debian or RPM package.

</details> <!-- End of Snapcraft section !-->

### Current development target

<details open><summary><p><b>Click/tap here to expand/collapse the Current development target section</b></p></summary>

**Current development target**

The current targets for development are Debian, Ubuntu, and Raspberry Pi OS. Other platforms will also be tested, but will be lower priority for now.

**Desktop and Mobile application support**

| 🖥️ OS | 🎯️ Target? |
|---|---|
| Windows 12 (beta) | ❌️ |
| Windows 11 | ❌️ |
| Windows 10 | ❌️ |
| MacOS | ❌️ |
| iOS 15 and up | ❓️ |
| Android 10 and up | ❓️ |
| ChromeOS | ❌️ |
| FreeBSD | ❌️ |
| NetBSD | ❌️ |
| OpenBSD | ❌️ |
| Dragonfly BSD | ❌️ |
| Debian 7 | ✅️ |
| Debian 8 | ✅️ |
| Debian 9 | ✅️ |
| Ubuntu 16.04 and up | ✅️ |
| Kubuntu 16.04 and up | ❓️ |
| Lubuntu 16.04 and up | ❓️ |
| Xubuntu 16.04 and up | ❓️ |
| PureOS | ❓️ |
| Fedora 31 and up | ❌️ |
| Red Hat Linux | ❌️ |
| Gentoo Linux | ❌️ |
| Arch Linux | ❌️ |
| Raspberry Pi OS | ✅️ |
| 🖥️ OS | 🎯️ Target? |

| Legend |
|---|
| ❌️ | Not currently supported |
| ❓️ | Undecided, planned for future |
| ✅️ | Supported, current priority |
| Legend |

**Web application support**

| 🚂️ Engine | 🎯️ Target? |
|---|---|
| Gecko | ✅️ |
| Chromium | ❌️ |
| Trident | ❌️ |
| Presto | ❌️ |
| Goanna | ✅️ |

| 🌐️ Browser | 🎯️ Target? |
|---|---|
| Mozilla Firefox | ✅️ |
| Google Chrome | ❌️ |
| Google Chromium | ❌️ |
| Safari | ❌️ |
| Opera | ❌️ |
| Brave | ❌️ |
| DuckDuckGo | ✅️ |
| Microsoft Edge | ❌️ |
| Microsoft Internet Explorer | ❌️ |
| Samsung Internet | ❌️ |
| Pale Moon | ✅️ |
| Vivaldi | ❌️ |
| LadyBird | ❓️ |
| Waterfox | ✅️ |
| Bliss Browser | ❓️ |
| Dillo | ❌️ |
| Line Mode Browser | ❌️ |
| Tor | ❓️ |
| iCab | ❌️ |
| Basilisk | ❌️ |
| SeaMonkey | ❌️ |
| LibreWolf | ❌️ |
| K-Meleon | ❌️ |

| Legend |
|---|
| ❌️ | Not currently supported |
| ❓️ | Undecided, planned for future |
| ✅️ | Supported, current priority |
| Legend |

</details> <!-- End of Current development targets section !-->

### Repository plan

<details open><summary><p><b>Click/tap here to expand/collapse the repository plan section</b></p></summary>

**Repository plan**

The core Flag Simulator repository will contain some of the key media resources (such as logos, some of the essential flags, icons, wallpapers) while the database repositories will hold the rest. Desktop Applications, Mobile Applications, and Web Applications will be programmed to use these resources (maybe as submodules)

</details> <!-- End of Repository plan section !-->

***

### Libraries

<details open><summary><p><b>Click/tap here to expand/collapse the LIBraries section</b></p></summary>

**Internal LIBraries**

<details open><summary><p><b>Click/tap here to expand/collapse the Internal LIBraries section</b></p></summary>

- [`LIB/Accessories`](/LIB/Accessories/)
- [`LIB/Audio`](/LIB/Audio/)
- [`LIB/Background-Images`](/LIB/Background-Images/)	
- [`LIB/Background-Videos`](/LIB/Background-Videos/)	
- [`LIB/Construction-Sheets`](/LIB/Construction-Sheets/)
- [`LIB/Flag-Poles`](/LIB/Flag-Poles/)
- [`LIB/Flags`](/LIB/Flags/)
- [`LIB/Logos`](/LIB/Logos/)
- [`LIB/Flags`](/LIB/Shaders/)
- [`LIB/UI`](/LIB/UI/)
- [`LIB/Weather`](/LIB/Weather/)

</details> <!-- End of Internal LIBraries section !-->

**Third-party LIBraries**

<details open><summary><p><b>Click/tap here to expand/collapse the Third-party LIBraries section</b></p></summary>

- None decided on yet

</details> <!-- End of 3rd party LIBraries section !-->

_End of LIBrary listing._

</details> <!-- End of LIBraries section !-->

***

### Installation

<details open><summary><p><b>Click/tap here to expand/collapse the Installation section</b></p></summary>

See: [`INSTALL.rst`](/INSTALL.rst) [OUTDATED, as of 2025, Wednesday, May 7th)

</details> <!-- End of installation section !-->

***

### Credits

<details open><summary><p><b>Click/tap here to expand/collapse the Credits section</b></p></summary>

See: [`CREDITS.wiki`](/CREDITS.wiki) [OUTDATED, as of 2025, Wednesday, May 7th)

</details> <!-- End of Credits section !-->

***

### Authors

<details open><summary><p><b>Click/tap here to expand/collapse the Authors section</b></p></summary>

See: [`AUTHORS.md`](/AUTHORS.md) [OUTDATED, as of 2025, Wednesday, May 7th)

</details> <!-- End of Authors section !-->

***

### Documentation

<details open><summary><p><b>Click/tap here to expand/collapse the Documentation section</b></p></summary>

Documentation is housed in a separate repository.

- [:octocat: `Click/tap here to go to the Flag Simulator documentation repository`](https://github.com/seanpm2001/Flag-Simulator_Docs/)

</details> <!-- End of Documentation section !-->

***

### Vexillological humor

Cannot directly link to these sources, due to ethical issues (DRM)

- Reddit: r/vexillologycirclejerk
- Unknown/various: The Big Bang Theory: Fun with Flags
- [:octocat: `Suggest another`](https://github.com/seanpm2001/Flag-Simulator/discussions/)

***

## Concept 2025.04.23

<details open><summary><p><b>Click/tap here to expand/collapse the Concept 2025.04.23 section</b></p></summary>

```
2025.04.23
Flag-Simulator
Flag-Simulator_Docs

Flag-Simulator_WebApp_JavaScript ✔️
Flag-Simulator_WebApp_JavaScript_Docs ✔️
Flag-Simulator_WebApp_Ruby ✔️
Flag-Simulator_WebApp_Ruby_Docs ✔️
Flag-Simulator_WebApp_PHP ✔️
Flag-Simulator_WebApp_PHP_Docs ✔️
Flag-Simulator_WebApp_WebAssembly ✔️
Flag-Simulator_WebApp_WebAssembly_Docs ✔️
Flag-Simulator_DesktopApp_Python ✔️
Flag-Simulator_DesktopApp_Python_Docs ✔️
Flag-Simulator_DesktopApp_Java ✔️
Flag-Simulator_DesktopApp_Java_Docs ✔️
Flag-Simulator_DesktopApp_C ✔️
Flag-Simulator_DesktopApp_C_Docs ✔️
Flag-Simulator_DesktopApp_Rust ✔️
Flag-Simulator_DesktopApp_Rust_Docs ✔️
Flag-Simulator_MobileApp_Java ✔️
Flag-Simulator_MobileApp_Java_Docs ✔️
Flag-Simulator_MobileApp_Kotlin ✔️
Flag-Simulator_MobileApp_Kotlin_Docs ✔️
Flag-Simulator_MobileApp_Swift ✔️
Flag-Simulator_MobileApp_Swift_Docs ✔️
Flag-Simulator_MobileApp_C ✔️
Flag-Simulator_MobileApp_C_Docs ✔️

Featured flag (default flag upon starting program on certain days)

May 5th: Flag of Mexico
August 24th: Flag of Ukraine

Improvement over Krikenoid/FlagWaver

Features

Flag physics
Flag direction
Wind direction
Wind control
Different backgrounds
Background videos
Export
Embed into a webpage
Database of flags
Upload custom flags
Pennants
Information on each flag
FlagW file (waving flag data file)
Flag burning
Information on religious flags
Flag tearing
Half mast
Raising/lowering
Customizable flag poles
Flag poles
SVG, PNG, JPEG, GIF, TIFF, BMP, WEBP, NETP, ICO, GIF_C200, among other supported formats
Various buttons
Ability to send an army to take down the flag
Offline functionality
Rain and weather effects
Play audio (national anthems, and anthem library)
Simulate real weather (with weather services, and data files for weather events)
Flag construction mode
Flag folding
Lighting, lighting modes
Shine a light
Flashlight (movable with cursor/finger)
Customizable flashlight, different light colors, sizes, strengths of light
Flag weaving
Buy an actual flag (based on the one shown)
VIAF flag
Default flag
Homepage
Fire arrows
Other items to throw
Flag Emoji mode
Flag Emoji import
Flag search (search for a flag, Emojis also work as a search option)
User interface skins
Censorship modes for hate flags, Socialist/Communist flags, terrorist flags, etc
Age rating
Desktop application (with ports in Python, Java, C, and Rust)
Web application (with ports in Ruby, JavaScript, PHP, and WebAssembly)
Mobile application (with ports in Java, Kotlin, Swift, and C)
Flag text and copy text from flag
ASCII mode, with text color toggle
Creating large flags (up to worlds largest)
Size limit: whatever your system can handle (even 1,000,000m by 1,000,000m would be allowed) theoretical end at 9,223,372,036,854,775,807 (2^64) square pixels
Flag code dictionary
Flag creator: Your own flag (built-in editor) add description, colors, shapes, graphics, text mode, description, and flag code
Color modes: monochrome, 4 bit, 5 bit, 6 bit, 7 bit, 8 bit, 12 bit, 16 bit, 24 bit, 32 bit, 48 bit, 64 bit
Filters
Slideshow mode
Customize the area around the flag pole
Multiple flag poles
Flag pole size
Flag pole material (metal, wood, etc.)
Flag pole material download
Dimensional modes: 2D, 3D, 4D
Scissors, knives, and swords
Acid raid effect
Fun facts about Vexillology in the UI
Accessories menu and the ability to import new ones (built-in: scissors, knives, swords, fire arrows, flashlight)
Accessory files: a specialized data file for the project
Gun accessory will be included separately, and will not be built-in, to keep the main program more friendly to a wider audience (although the flag of Mozambique will still be built in, despite having a gun on it)

Flagwaver feature 2025.04.27
Transparency level

---

Feedback on Flag Simulator (2025, April 28th)

Reminder that this project suits a limited audience

Flag stamps

Trying to be careful with naming forks, due to usernames. I always check the spelling of the name, and will usually do all lowercase or uppercase, if I can’t determine where a first name, middle name, or last name start or end, or if one exists. I do the same for the repository name as well

Flag simulator 2025.04.28

Totem pole library

---

Flag Simulator 2025.04.30

Flag-Simulator_DB_FOTW ✔️
Flag-Simulator_DB_FOTW_Docs ✔️

---

Flag simulator 2025.05.01 (imported 2025.05.02)

Feature checklist in README
```

</details> <!-- End of Concept 2025.04.23 section !-->

***

## Common tags

<details open><summary><p lang="en">Click/tap here to expand/collapse this section</p></summary>

Common tags for this project.

| [:octocat: `#flag`](https://github.com/topics/flag/) | [:octocat: `#flags`](https://github.com/topics/flags/) | [:octocat: `#flagwaver`](https://github.com/topics/flagwaver/) | [:octocat: `#flag-simulator`](https://github.com/topics/flag-simulator/) | [:octocat: `#flag-simulator-project`](https://github.com/topics/flag-simulator-project/) | [:octocat: `#flag-simulator-development`](https://github.com/topics/flag-simulator-development/) | [:octocat: `#flag-simulator-docs`](https://github.com/topics/flag-simulator-docs/) | [:octocat: `#flag-simulator-documentation`](https://github.com/topics/flag-simulator-documentation/) | [:octocat: `#seanpm2001-flag-simulator`](https://github.com/topics/seanpm2001-flag-simulator/) | [:octocat: `#vexillology`](https://github.com/topics/vexillology/) |

</details> <!-- End of Common tags section !-->

***

<!-- /%/2001_FILE_INFO_SECTION.BEGIN\%\ !-->

### File info

<details open><summary><p lang="en">Click/tap here to expand/collapse this section</p></summary>

- **File type:** `Markdown document (*.md *.mkd *.mdown *.markdown)`
- **File version:** `5 (2025, Friday, May 9th at 06:32 pm PST)`
- **Line count (including blank lines and compiler line):** `01,768`
- **Word count:** `11,025`
- **Character count (with spaces):** `074,943 characters`
- **Character count (without spaces)** `064,435 characters`
- **Current article language:** `English (EN_USA) for main article` / `Markdown (CommonMark)` / `HTML (HTML 5.3)`
- **Encoding:** `UTF-8 (Emoji 12.0 or higher recommended)`
- **All times are UTC-7 (PDT/Pacific Time)** `(Please also account for DST (Daylight Savings Time) for older/newer entries up until it is abolished/no longer followed)`

> **Note** _On 2022, Sunday, March 13th at 2:00 am PST, the time jumped ahead 1 hour to 3:00 am._

> **Note** **You may need special rendering support for the `<details>` HTML tag being used in this document**

View this segment [in a separate file](/Segments/File-info/README.md)

</details> <!-- End of File info section !-->

<!-- /%/2001_FILE_INFO_SECTION.END\%\ !-->

***

# File history

<details open><summary><p><b>Click/tap here to expand/collapse the file history section</b></p></summary>

---

## Version 1 (2025, Monday, May 5th at 09:55 pm PST)

<details open><summary><p><b>Click/tap here to expand/collapse the file history section entry for version 1</b></p></summary>

> **Note:** _This is the first version._

> **Changes:**

- [x] Started the file
- [x] Referenced the placeholder logo
- [x] Added the title section
- [x] Added the Features section
- [x] Added the Flag physics section
- [x] Added the Flag direction section
- [x] Added the Wind direction section
- [x] Added the Wind control section
- [x] Added the Barometric pressure section
- [x] Added the Different backgrounds section
- [x] Added the Background videos section
- [x] Added the Export section
- [x] Added the Embed into a webpage section
- [x] Added the Database of flags section
- [x] Added the Upload custom flags section
- [x] Added the Pennants section
- [x] Added the Information on each flag section
- [x] Added the FlagW file (waving flag data file) section
- [x] Added the Flag burning section
- [x] Added the Information on religious flags section
- [x] Added the Flag tearing section
- [x] Added the Half mast section
- [x] Added the Raising/lowering section
- [x] Added the Customizable flag poles section
- [x] Added the Flag poles section
- [x] Added the SVG, PNG, JPEG, GIF, TIFF, BMP, WEBP, NETP, ICO, GIF_C200, among other supported formats section
- [x] Added the Various buttons section
- [x] Added the Ability to send an army to take down the flag section
- [x] Added the Offline functionality section
- [x] Added the Rain and weather effects section
- [x] Added the Play audio (national anthems, and anthem library) section
- [x] Added the Simulate real weather (with weather services, and data files for weather events) section
- [x] Added the Flag construction mode section
- [x] Added the Flag folding section
- [x] Added the Lighting, lighting modes section
- [x] Added the Shine a light section
- [x] Added the Flashlight (movable with cursor/finger) section
- [x] Added the Customizable flashlight, different light colors, sizes, strengths of light section
- [x] Added the Flag weaving section
- [x] Added the Buy an actual flag (based on the one shown) section
- [x] Added the VIAF flag section
- [x] Added the Default flag section
- [x] Added the Homepage section
- [x] Added the Fire arrows section
- [x] Added the Other items to throw section
- [x] Added the Flag Emoji mode section
- [x] Added the Flag Emoji import section
- [x] Added the Flag search (search for a flag, Emojis also work as a search option) section
- [x] Added the User interface skins section
- [x] Added the Censorship modes for hate flags, Socialist/Communist flags, terrorist flags, etc section
- [x] Added the Age rating section
- [x] Added the Desktop application (with ports in Python, Java, C, and Rust) section
- [x] Added the Web application (with ports in Ruby, JavaScript, PHP, and WebAssembly) section
- [x] Added the Mobile application (with ports in Java, Kotlin, Swift, and C) section
- [x] Added the Flag text and copy text from flag section
- [x] Added the ASCII mode, with text color toggle section
- [x] Added the Creating large flags (up to worlds largest) section
- [x] Added the Size limit: whatever your system can handle (even 1,000,000m by 1,000,000m would be allowed) theoretical end at 9,223,372,036,854,775,807 (2^64) square pixels section
- [x] Added the Flag code dictionary section
- [x] Added the Flag creator: Your own flag (built-in editor) add description, colors, shapes, graphics, text mode, description, and flag code section
- [x] Added the Color modes: monochrome, 4 bit, 5 bit, 6 bit, 7 bit, 8 bit, 12 bit, 16 bit, 24 bit, 32 bit, 48 bit, 64 bit section
- [x] Added the Filters section
- [x] Added the Slideshow mode section
- [x] Added the Customize the area around the flag pole section
- [x] Added the Multiple flag poles section
- [x] Added the Flag pole size section
- [x] Added the Flag pole material (metal, wood, etc.) section
- [x] Added the Flag pole material download section
- [x] Added the Dimensional modes: 2D, 3D, 4D section
- [x] Added the Scissors, knives, and swords section
- [x] Added the Acid raid effect section
- [x] Added the Fun facts about Vexillology in the UI section
- [x] Added the Accessories menu and the ability to import new ones (built-in: scissors, knives, swords, fire arrows, flashlight) section
- [x] Added the Accessory files: a specialized data file for the project section
- [x] Added the Transparency level section
- [x] Added the Flag stamps section
- [x] Added the Feedback from 2025, April section
- [x] Added the Databases section
- [x] Added the Variants section
- [x] Added the Web Applications section
- [x] Added the Desktop Applications section
- [x] Added the Mobile Applications section
- [x] Added information on development targets
- [x] Added the Concept 2025.04.23 section
- [x] Added the File info section
- [ ] No other changes in version 1

</details> <!-- End of V1:File History !-->

---

## Version 2 (2025, Tuesday, May 6th at 05:40 pm PST)

<details open><summary><p><b>Click/tap here to expand/collapse the file history section entry for version 2</b></p></summary>

> **Note:** _This is the second version._

> **Changes:**

- [x] Updated information on development targets
- [x] Updated the File info section
- [x] Added the File History section
- [x] Added the Snapcraft section
- [x] Added the Current development targets section
- [x] Added the Repository plan section
- [x] Added dropdown support to all sections
- [x] Added the Footer section
- [ ] No other changes in version 2

</details> <!-- End of V2:File History !-->

---

## Version 3 (2025, Wednesday, May 7th at 06:38 pm PST)

<details open><summary><p><b>Click/tap here to expand/collapse the file history section entry for version 3</b></p></summary>

> **Note:** _This is the third version._

> **Changes:**

- [x] Updated the File info section
- [x] Updated the File History section
- [x] Added the Documentation section
- [x] Added the LIBraries section
- [x] Added the Installation section
- [x] Added the Credits section
- [x] Added the Authors section
- [x] Updated the current development target section
- [ ] No other changes in version 3

</details> <!-- End of V3:File History !-->

---

## Version 4 (2025, Thursday, May 8th at 07:34 pm PST)

<details open><summary><p><b>Click/tap here to expand/collapse the file history section entry for version 4</b></p></summary>

> **Note:** _This is the fourth version._

> **Changes:**

- [x] Updated the File info section
- [x] Updated the File History section
- [x] Added the Table of contents section
- [x] Added the Language switcher section
- [x] Added the This repository section
- [x] Added the Common tags section
- [x] Added the Footer section
- [ ] No other changes in version 4

</details> <!-- End of V4:File History !-->

---

## Version 5 (2025, Friday, May 9th at 06:32 pm PST)

<details open><summary><p><b>Click/tap here to expand/collapse the file history section entry for version 5</b></p></summary>

> **Note:** _This is the fifth version, and the final consecutive version for now._

> **Changes:**

- [x] Updated the File info section
- [x] Updated the File History section
- [x] Updated the Table of contents section
- - [x] Added remaining feature sections
- - [x] Added link to Vexillological humor section
- [x] Added the Vexillological humor section
- [ ] No other changes in version 5

</details> <!-- End of V5:File History !-->

_End of file history section._

</details> <!-- End of File History !-->

<!-- /%/2001_FOOTER_SECTION.BEGIN\%\ !-->

# Footer

You have reached the bottom of this page.

###### EOF

<!-- /%/2001_FOOTER_SECTION.END\%\ !-->

---

_End of article._

</details> <!-- End of Article !-->

***
