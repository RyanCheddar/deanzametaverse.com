# Club Day Poster

This is the source code for the AR experience available on the poster we had during the Fall 2023 Club Day, on the Developer's Guild table.

![Club Day](https://github.com/RyanCheddar/De-Anza-Metaverse-Club/blob/7eb50a04bfe2cd2459979b0fcfca2e533f5550a7/retroar/club_day.jpeg)

The experience utilizes [MindAR](https://hiukim.github.io/mind-ar-js-doc/), an augmented reality library that allows creating image tracked and face tracked AR experience with only one HTML file.

---

*targets.mind* is a compiled file containing tracking information about the original poster, which enables the code to track the poster. it was created using [this tool](https://hiukim.github.io/mind-ar-js-doc/tools/compile)

*Epic Hango.hlb* is a 3D model for the pseudo Windows 95 pop up that appears 8 seconds after the poster is detected for the first time. It was created using [TinkerCAD](https://www.tinkercad.com/), which is a really cool online 3D model editor.

*capybara.hlb* is a 3D model of a capybara. I have no clue where I got it from.

*poster.mp4* is the animated version of the poster, which is overlayed onto the physical poster in the user's camera view.

*index.html* is the HTML file that contains the entire AR experience. There are some comments in the JavaScript section of the file, and you can figure out the rest of the file in [MindAR](https://hiukim.github.io/mind-ar-js-doc/)'s documentation.

---

Here is the poster in case you want to try the AR experience. It works best when printed:

![Poster](https://github.com/RyanCheddar/De-Anza-Metaverse-Club/blob/7eb50a04bfe2cd2459979b0fcfca2e533f5550a7/retroar/poster.png)
