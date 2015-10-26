<!-- ========================================================== -->
[![dark_img]][readme] [![darcula_img]][readme] [![light_img]][readme]

[![plugin_img]][plugin_link] [![license_img]][license_link]

# ChroMATERIAL
ChroMATERIAL is a color scheme that expresses the chromatic nature of [Material Design][material] within JetBrain IDEs and Android Studio. In particular, ChroMATERIAL focuses on syntax highlighting of code within the IDE's code editor. 

It's uniqueness lies in the idea...

> **Enhance influence, not banality**

####Support

| Type          | Support |
| :-----------: | :------ |
| **IDEs**      | <kbd>Android Studio</kbd> <kbd>IntelliJ IDEA</kbd> <kbd> RubyMine</kbd> <kbd>WebStorm</kbd> <kbd>PhpStorm</kbd> <kbd>PyCharm</kbd> <kbd>AppCode</kbd> <kbd>CLion</kbd> <kbd>0xDBE</kbd> <br><sub><sup>ChroMATERIAL supports **Text Editor** changes only. <br>ChroMATERIAL + [Material Theme][chris-rm_theme] will modify the whole IDE!</sup></sub> |
|||
| **Languages** | <kbd>Java</kbd> <kbd>Android</kbd> <kbd>Groovy</kbd> <kbd>XML</kbd> <kbd>JSON</kbd> <kbd>HTML</kbd> <br><sub><sup>**Pull Requests** are welcome.</sup></sub> |
|||
| **Others**    | <kbd>Android Manifest</kbd> <kbd>Android Resources</kbd> <kbd>Gradle</kbd> <kbd>Logcat</kbd> <kbd>Property Files</kbd> <kbd>diff</kbd> <br><sub><sup>**Pull Requests** are welcome.</sup></sub> |

<!-- ========================================================== -->
#Screenshots

Standard syntax coloring...<br>
![chromaterial_color-range_main][img_normal]

Color syntax range...<br>
![chromaterial_color-range][img_range]
<br><sub><sup>**Note** these images contain code from [Google's Android Vision API][android-vision] barcode sample app. </sup></sub>

<!-- ========================================================== -->
#Installation

**Find Plugin**
 1. Open IDE and locate <kbd>File >> Settings >> Plugins</kbd> and click <kbd>Browse Repositories...</kbd>
 3. Search for and click <kbd>ChroMATERIAL</kbd> and click <kbd>Install plugin</kbd>

<!--
####Manual
Install ChroMATERIAL. This does NOT provide automatic updates.

**Retrieve from the Internet**
 1. Download <kbd>[ChroMATERIAL][jar] Jar file</kbd>.

**Install Color Scheme**
 2. Open IDE and locate <kbd>File >> Import Settings...</kbd>.
 3. Locate the <kbd>ChroMATERIAL Jar file</kbd> in the list, click <kbd>OK</kbd> 
 4. Check <kbd>Editor Colors</kbd> and click <kbd>OK</kbd>.
-->

**Use Color Scheme** 
 5. Locate <kbd>File >> Settings >> Editor >> Colors & Fonts >> Scheme</kbd> 
 6. Choose <kbd>ChroMATERIAL</kbd> and click <kbd>Apply</kbd> / <kbd>OK</kbd>.

###Optional

 - Modify the **font type** to your preference
 - Modify the **syntax highlighting** further to fit your particular tastes.
 
<!-- ========================================================== -->
#Roadmap

**Color Scheme Milestones**

|              | M1      | M2       | M3    |
| :----------: | :-----: | :------: | :---: |
| **Achieved** | ![yes]  | ![no]    | ![no] |
|              | Regular | Darcula<br>compatible  | Light |

**Milestone Notes**

|                  | M1  | M2  | M3  |
| :--------------: | --- | --- | --- |
| **Improvements** | Still needs to:<ul><li>Improve existing language support<li>Extend language support |   |   |
| **Notes**        |     | Minor changes needed:<ul><li>Syntax highlights remain<li>Background colors change |  Major changes needed:<ul><li>Syntax highlights change or rethought completely<li>Background colors change |

<!-- ========================================================== -->
#Special Thanks

 - Google for [Material Design][material] and the attention to color
 
 - [ChrisRM][chris-rm] for porting a [Material Theme][chris-rm_theme] over to all of JetBrain's IDEs. I have been wanting to create a Material color scheme for Android Studio for a while now, but always found starting this to be too cumbersome. With your inital color scheme, I was able to get started easily and finally got a look that I love. 

   From that point, I created ChroMATERIAL to further specific goals of mine.

<!-- ===================== References ========================= -->

<!-- images -->
[img_normal]: https://cloud.githubusercontent.com/assets/8707125/10559945/814a770c-7536-11e5-99d4-efd4d03ea3f5.PNG
[img_range]: https://cloud.githubusercontent.com/assets/8707125/10559946/814af8bc-7536-11e5-8666-102db39305f0.PNG
[yes]: https://cloud.githubusercontent.com/assets/8707125/10560554/6e30a660-7549-11e5-95ec-a07b0c049339.png
[no]: https://cloud.githubusercontent.com/assets/8707125/10560555/7263eddc-7549-11e5-8939-bfd2d6141f11.png

<!-- links -->
[material]: http://www.google.co.kr/design/spec/material-design/introduction.html#
[android-vision]: https://github.com/googlesamples/android-vision
[chris-rm]: https://github.com/ChrisRM
[chris-rm_theme]: https://github.com/ChrisRM/material-theme-jetbrains

<!-- files -->
[jar]: install/ChroMATERIAL.jar
[readme]: README.md

<!-- badges -->
[plugin_img]: https://img.shields.io/badge/JetBrain%20Plugin%20Repository%20ID-7998-blue.svg?style=flat-square
[plugin_link]: https://plugins.jetbrains.com/plugin/7998

[license_img]: https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square
[license_link]: LICENSE

[dark_img]: https://img.shields.io/badge/Dark%20Color%20Scheme-In%20Progress-yellow.svg?style=flat-square
[darcula_img]: https://img.shields.io/badge/Darcula%20Compatible%20Color%20Scheme-Future-red.svg?style=flat-square
[light_img]: https://img.shields.io/badge/Light%20Color%20Scheme-Future-red.svg?style=flat-square
