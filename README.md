# Dropcap-CSS
A collection of CSS dropcap styles.

## What is Dropcap CSS?
I used to have this project called [The Annotation](https://theannotation.com), a publication that was part of Medium's early publications process, and while I was building it I realized there really wasn't an easy way to create drop caps. Obviously, not in Medium becasue, let's face it, they're locked in with their design, but in general. Why aren't drop caps more generally supported. They're beautiful pieces of art that deserve to be recognize! They spread a publications brand, add flair, and simply at times are stunning, so I decided to cook up a few CSS/SVG publication designs and throw them into a css file. 

## How does it work?

Just download/pull the css file, or use the sketch file attached to customize your dropcaps even more! 
```
<link rel="stylesheet" href="dropcap.css">
```
All of the styles are *classes*, and currently I'm working on the naming structure. Right now though, if you want to impliment a style, the basic format is:
```.dc-yourdesiredstyle ```.

## How to impliment it in HTML

From the lovely [CSS Tricks](https://css-tricks.com/snippets/css/drop-caps/)

> 
### HTML
```
<p>
<span class="dc-firstcharacter">L</span> orem ipsum dolor sit amet, consectetur adipiscing elit. Mauris tristique lobortis orci ac lacinia. Fusce eu purus eget diam vehicula auctor nec eu elit. Morbi consequat facilisis orci vel malesuada. Donec ultrices molestie sollicitudin. Aliquam pharetra libero enim. Donec et suscipit massa. Donec dui odio, dignissim non sodales et, tincidunt a sapien. Phasellus elit nibh, adipiscing sed blandit vel, interdum et arcu.
</p>
```
### CSS
```
.dc-firstcharacter {
  color: #903;
  float: left;
  font-family: Georgia;
  font-size: 75px;
  line-height: 60px;
  padding-top: 4px;
  padding-right: 8px;
  padding-left: 3px;
}
```

<hr>

If you want to see more of my work, this is [my website](https://tristanisham.com). I'll make this more readable later. It's 1:48 in the morning and I'm exhausted.

Also, follow me on [Twitter](https://twitter.com/TristanIsham).
