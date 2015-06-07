# Zipwrite
Simple javascript plugin for creating **typing effect** on webpages.
###Installation
Add the path to the zipwrite javascript file
```html
<script src="/path/to/zipwrite.js" type="text/javascript"></script>
```
###Usage
Simply set the class name to **zipWriter** and add shuffle words to get started
```html
<span class="zipWriter" shuffle='["good", "geeky", "nerdy", "awesome"]'>
</span>
```
###Attributes
You can add the **attributes** directly to the html elements.
However default values are set for all the elements.
```html
  <span
     class="zipWriter"
     stoptime="2000"
     shuffle='[ "nerdy.", "simple.", "pretty.", "fun!" ]'
     rewrite="2"
     cursor-width="0.09"
     cursor-color="#666"
     blink="true"
     shuffle-color="cool">
  </span>
```
* ```cursor-width```: Used to define the width of the cursor that prints the shuffle words.
                      The metric used to measure is **'em'**.The default value is set to 0.09.
* ```cursor-color```: Used to define the color of the cursor that prints the shuffle words.
                      The default value is set to **#666**.
* ```blink```       : blink as stated sets the blinking property of the cursor.
                      The default value is set to **true**.
* ```shuffle-color```: Used to define the colors for the words to be shuffled.The default value is **random**.
                       There are two options **"random"** and "**cool**".
* ```rewrite```:       The time at which a displayed word is deleted is defined by rewrite. It is measured in **ms**.
                      The default value set is *2*.
* ```stoptime```:     stoptimes defines the period in which a shuffled words is displayed for.
                      The default value is set to **2000ms**.
            
###License
The MIT License (MIT)

Copyright (c) <2015> <Meher Panguluri>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

Made with  ❤  by  zippytalk
