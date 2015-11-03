# <small>Using</small> Musical Scales <small>to Build</small> Harmonious Typography

## Musical Intervals & Math

### Every <em>Note</em><br> Is a <em>Number</em>

---

![images/trombone.gif](images/trombone.gif)

---

![images/harp.gif](images/harp.gif)

---

![images/xylophone.gif](images/xylophone.gif)

### Every <em>Note</em><br> Is a <em>Number</em>

Every musical note is a number: a frequency vibrating a certain number of times per second (measured in hertz).

### Every <em>Octave</em><br> Increases <em>2</em>&times;

| Concert A = 440Hz | A<sup>5</sup> = 880Hz |
| --- | --- |
| Middle C ~= 131Hz | C<sup>4</sup> ~=262Hz |

---

![images/wave.svg](images/wave.svg)
![images/wave-x2.svg](images/wave-x2.svg)

### Every <em>Fifth</em><br> Increases ~<em>1.5</em>&times;

| A<sup>3</sup> = 220Hz | E<sup>4</sup> ~=330Hz |
| --- | --- |

---

![images/wave.svg](images/wave.svg)
![images/wave-x1.5.svg](images/wave-x1.5.svg)

### Every <em>Half-Step</em> Increases <em>1.0595</em>&times;

Every half-step (the building block of Western scales) is a 1.0595&times; increase.

All other intervals work as exponents of the half-step interval.

  * A (440Hz) &times; 1.0595 = A<sup>#</sup> (466.16Hz) &times; 1.0595 = B (493.88Hz)
  * A (440Hz) &times; 1.0559<sup>2</sup> = B (493.88Hz)

## Typography & Modular Scales

### <em>Modular Scales</em><br> in <em>Sass</em>

  * [Modular Scale](http://www.modularscale.com/)
  * [Sassline](https://sassline.com/)
  * [Typesettings](http://typesettings.io/)
  * [Type Scale](http://type-scale.com/)
  * [Gridlover](http://www.gridlover.net/)
  * [ALA: More Meaningful Typography](http://alistapart.com/article/more-meaningful-typography)

### Literal<br> <em>Modular Scales</em>

  * Every interval is the same
  * A musical half-step scale is literally modular *~play half-step scale~*
  * A musical whole-step scale is literally modular *~play whole-step scale~*

### Non-literal / quasi-modular scales

  * Major & minor scales are created by alternating whole- & half-step scales (WWHWWWH) / (WHWWHWW)
  * These patterns repeat every octave, creating a non-literal / organic modular scale.

### Non-literal / quasi-modular scales

ALA article above briefly discusses a “double-stranded modular scale” which also avoids the single increment limit of literal modular scales, but is less adjustable than music-based type scales.

## See & Hear

### Interval: Octave

<div class="text-block interval octave">
  <p class="heading-octave">Notes Are Numbers</p>
  <p class="paragraph-octave">Every musical note is a number: a frequency vibrating a certain number of times per second (measured in hertz).</p>
</div>
<button id="interval-octave" class="play-button">Play</button>

### Interval: Fifth

<div class="text-block interval fifth">
  <p class="heading-fifth">Notes Are Numbers</p>
  <p class="paragraph-fifth">Every musical note is a number: a frequency vibrating a certain number of times per second (measured in hertz).</p>
</div>
<button id="interval-fifth" class="play-button">Play</button>

### Interval: Third

<div class="text-block interval third">
  <p class="heading-third">Notes Are Numbers</p>
  <p class="paragraph-third">Every musical note is a number: a frequency vibrating a certain number of times per second (measured in hertz).</p>
</div>
<button id="interval-third" class="play-button">Play</button>

### Scale: Major Scale

<div class="text-block scale major-scale">
  <p class="heading-1">Heading 1</p>
  <p class="heading-2">Heading 2</p>
  <p class="heading-3">Heading 3</p>
  <p class="blockquote">Blockquote</p>
  <p class="paragraph">Paragraph</p>
</div>
<button id="scale-major" class="play-button">Play</button>

### Scale: Pentatonic

<div class="text-block scale pentatonic">
  <p class="heading-1">Heading 1</p>
  <p class="heading-2">Heading 2</p>
  <p class="heading-3">Heading 3</p>
  <p class="blockquote">Blockquote</p>
  <p class="paragraph">Paragraph</p>
</div>
<button id="scale-pentatonic" class="play-button">Play</button>

### Scale: Major Triad

<div class="text-block scale major-triad">
  <p class="heading-1">Heading 1</p>
  <p class="heading-2">Heading 2</p>
  <p class="heading-3">Heading 3</p>
  <p class="blockquote">Blockquote</p>
  <p class="paragraph">Paragraph</p>
</div>
<button id="scale-major-triad" class="play-button">Play</button>

### Responsive musical scales

  * By decreasing the number of notes per octave, you can increase font sizes more quickly, taking advantage of larger screens.
  * By increasing the number of notes per octave, you can slow the growth of font sizes, keeping content visible on small screens.

## Intro to TypeTuner

### TypeTuner

Point audience to my [TypeTuner library](http://typetuner.com) &amp; quickly overview public functions/mixins

## Thanks!

### James Steinbach

[@jdsteinbach](https://twitter.com/jdsteinbach)

[jdsteinbach.com](https://jdsteinbach.com)
