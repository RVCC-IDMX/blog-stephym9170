---
title: Applying Color in UI Design
author: Stephanie Mayers
description: This article is about how you apply color in UI design
date: 2022-10-10T23:06:53.023Z
tags:
  - post
  - featured
image: /assets/blog/a-girl-coding.jpeg
imageAlt: (I would imagine this woman is doing some coding for an app)
---
<!--StartFragment-->

Applying color in UI design is the process of adding color and contrast to your project, with that being said you want to choose colors that work well with each other and provide balance. When applying color in UI design you should use the function hsl() whenever you can.

H﻿TML and CSS

Before attempting to apply color in UI design you should know the basics of css and html as they are both used when it comes to applying color. The html as always is used to add text, images, logos and more whilst the css as always is used for design. When working on the project, you should always develop your html and basic css first so that you have the layout, format and the substance of what you are creating. Since inside the css is where you will add the color and I would recommend adding the color last. 

Color

When it comes to color in CSS you should already be familiar with adding color using hex code, for example:

\`\``html

h1 {

 color: #000000;

}

\`\``

You may have also used rgb (red, green, blue), which is similar to the format of the color function you should use when applying color in UI design. When applying color in UI Design it is best to use the hsl (Hue, Saturation, and Light) function. An example of the coding for hsl is:

\`\``html

:root {

\--blue-100: 210 79% 15%;

\--blue-200: 210 79% 35%;

\--blue-300: 210 79% 55%;

\--blue-400: 210 79% 75%;

\--blue-500: 210 79% 95%;

}

h1{

 color: hsl(var(--gray-200));

}

\`\``

HSL (Hue, Saturation, Lightness)

According to \[web.dev](<https://web.dev/learn/css/color/>) hue describes the value on the color wheel, saturation is the vibrancy of the hue chosen, and lightness is the amount of black and white added. What this then means is that the number that you use for hue is the origin of the color you are going to use. When trying to find the hsl of a color, you can visit this website that will let you choose the color and provide you with the hsl of that color \[color hsl](<https://coolors.co/>) 

Tutorial

 You should definitely play around with this on CodePen, more specifically you should fork George’s code pen as it can be found here \[George’s codepen] (<https://georgefrancis.dev/writing/a-beginners-guide-to-applying-color-in-ui-design/>). 

Conclusion

Again, you should already be familiar with both html and css before applying color in UI design and even completing the tutorial mentioned above. Applying color in UI design is not as hard as it seems but it is very tedious as is all code so you want to be very careful and always have what you are applying the actual project at all times so you can see the changes being made step by step. From what I have experienced, I find using the hsl function for projects, whether you are building an app or a site helps not only to help it look pretty but to also provide more balance and contrast to the page.

<!--EndFragment-->