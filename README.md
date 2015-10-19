<!-- ========================================================== -->
# ChroMATERIAL
ChroMATERIAL is a color scheme that expresses the chromatic nature of [Material Design][material] within IntelliJ and Android Studio. In particular, ChroMATERIAL focuses on syntax highlighting of code within the IDE's code editor. 

It's uniqueness lies in the idea...

> **Enhance influence, not banality**

<!-- ========================================================== -->
#Screenshots

A normal display of syntax highlighting...
![chromaterial_color-range_main][img_normal]

A range of syntax highlighting...
![chromaterial_color-range][img_range]

**Note** these images contain code from [Google's Android Vision API][android-vision] barcode sample app.

<!-- ========================================================== -->
#Installation

 1. Download [ChroMATERIAL][jar] Jar file
 2. Open IDE
 
   `File` >> `Import Settings...`

 3. Locate downloaded ChroMATERIAL Jar file

   Check `Editor Colors` >> `OK`

 4. `File` >> `Settings` >> `Editor` >> `Colors & Fonts`

   `Scheme` >> Choose `ChroMATERIAL`
 
 
**Optional**

 - Modify the font type to your preference
 - Modify the syntax highlighting to fit your particular tastes
 
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
 
 - [ChrisRM][chris-rm] for porting a [Material Theme][chris-rm_theme] over to all of JetBrain's IDEs. I have been wanting to create a Material color scheme for Android Studio for a while now, but always found starting this to be too combersome. With your inital color scheme, I was able to get started easily and finally got a look that I love. 

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
[jar]: ChroMATERIAL.jar
