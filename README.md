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
            
###Finally
Made with  ❤  by  zippytalk
