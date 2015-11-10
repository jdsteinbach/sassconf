# <small>Using</small> Musical Scales <small>to Build</small> Harmonious Typography

## Musical Intervals & Math

### Every <em>Note</em><br> Is a <em>Number</em>

Every musical note is a number: a frequency vibrating a certain number of times per second (measured in hertz).

---

![images/trombone.gif](images/trombone.gif)

---

![images/harp.gif](images/harp.gif)

---

![images/xylophone.gif](images/xylophone.gif)

### An <em>Octave</em><br> Increases <em>2</em>&times;

| Concert A = 440Hz | A<sup>5</sup> = 880Hz |
| --- | --- |
| Middle C ~= 131Hz | C<sup>4</sup> ~=262Hz |

---

![images/wave.svg](images/wave.svg)
![images/wave-x2.svg](images/wave-x2.svg)

### A <em>Fifth</em><br> Increases ~<em>1.5</em>&times;

| A<sup>3</sup> = 220Hz | E<sup>4</sup> ~=330Hz |
| --- | --- |
| C<sup>3</sup> ~= 131Hz | G<sup>3</sup> ~=196Hz |

---

![images/wave.svg](images/wave.svg)
![images/wave-x1.5.svg](images/wave-x1.5.svg)

### A <em>Half-Step</em> Increases <em>1.0595</em>&times;

The half-step is the building block of scales.

All intervals are exponents of the half-step.

---

| A (440Hz) | &times; | 1.0595 | = | A<sup>#</sup> (466.16Hz) |
|:---:|:---:|:---:|:---:|:---:|
| A<sup>#</sup> (466.16Hz) | &times; | 1.0595 | = | B (493.88Hz) |
| | | | | |
| A (440Hz) | &times; | 1.0595<sup>2</sup> | = | B (493.88Hz) |

## Typography & Modular Scales

### <em>Single-Stranded</em> <span>Modular Scales</span>

  * Every interval is the same
  * A musical half-step scale is literally modular <button id="scale-half-step" class="play-button" data-speed="1.25">Play</button>

  * A musical whole-step scale is literally modular <button id="scale-whole-step" class="play-button" data-speed="1.25">Play</button>


### <em>Multi-Stranded</em> <span>Modular Scales</span>

  * Major & minor scales are created by alternating whole & half steps (WWHWWWH) / (WHWWHWW) <button id="scale-major" class="play-button" data-speed="1.5">Play</button>
  * These patterns repeat every octave, creating a mult-stranded modular scale. <button id="scale-minor" class="play-button" data-speed="1.5">Play</button>

### <em>Modular Scales</em><br> in <em>Sass</em>

  * [Modular Scale](http://www.modularscale.com/)
  * [Sassline](https://sassline.com/)
  * [Typesettings](http://typesettings.io/)
  * [Type Scale](http://type-scale.com/)
  * [Gridlover](http://www.gridlover.net/)
  * [ALA: More Meaningful Typography](http://alistapart.com/article/more-meaningful-typography)

## See & Hear

### Interval: <em>Octave</em>

<div class="text-block interval octave">
  <p class="heading-octave">Notes Are Numbers</p>
  <p class="paragraph-octave">Every musical note is a number: a frequency vibrating a certain number of times per second (measured in hertz).</p>
</div>
<button id="interval-octave" class="play-button">Play</button>

### Interval: <em>Fifth</em>

<div class="text-block interval fifth">
  <p class="heading-fifth">Notes Are Numbers</p>
  <p class="paragraph-fifth">Every musical note is a number: a frequency vibrating a certain number of times per second (measured in hertz).</p>
</div>
<button id="interval-fifth" class="play-button">Play</button>

### Interval: <em>Third</em>

<div class="text-block interval third">
  <p class="heading-third">Notes Are Numbers</p>
  <p class="paragraph-third">Every musical note is a number: a frequency vibrating a certain number of times per second (measured in hertz).</p>
</div>
<button id="interval-third" class="play-button">Play</button>

### Scale: <em>Major Scale</em>

<div class="text-block scale major-scale">
  <p class="heading-1">Heading 1</p>
  <p class="heading-2">Heading 2</p>
  <p class="heading-3">Heading 3</p>
  <p class="blockquote">Blockquote</p>
  <p class="paragraph">Paragraph</p>
</div>
<button id="scale-major" class="play-button" data-speed="1.5">Play</button>

### Scale: <em>Pentatonic</em>

<div class="text-block scale pentatonic">
  <p class="heading-1">Heading 1</p>
  <p class="heading-2">Heading 2</p>
  <p class="heading-3">Heading 3</p>
  <p class="blockquote">Blockquote</p>
  <p class="paragraph">Paragraph</p>
</div>
<button id="scale-pentatonic" class="play-button" data-speed="1.25">Play</button>

### Scale: <em>Major Triad</em>

<div class="text-block scale major-triad">
  <p class="heading-1">Heading 1</p>
  <p class="heading-2">Heading 2</p>
  <p class="heading-3">Heading 3</p>
  <p class="blockquote">Blockquote</p>
  <p class="paragraph">Paragraph</p>
</div>
<button id="scale-major-triad" class="play-button">Play</button>

### <em>Responsive</em> <span>Musical Scales</span>

More notes per octave: better for small screens

Fewer notes per octave: better for large screens

---

![Broken Headline Size 1](images/facebook.jpg)
![Broken Headline Size 2](images/entrepreneurs.jpg)
![Broken Headline Size 3](images/improbability.jpg)

## Intro to TypeTuner

### TypeTuner.com

```
@include set-hierarchy( $list );
@include add-breakpoint(
  $label,
  $min-width,
  $font-size,
  $line-height,
  $scale
);
@include remove-breakpoint( $label );
@include type-tune( extend | class );
```

## Thanks!

### James Steinbach

[jdsteinbach.com](https://jdsteinbach.com)

[@jdsteinbach](https://twitter.com/jdsteinbach/)

[github.com/jdsteinbach](https://github.com/jdsteinbach/)

### Resources

* [typetuner.com](http://typetuner.com)
* [jdsteinbach.com/sassconf](http://jdsteinbach.com/sassconf/)
* [webtypography.net](http://webtypography.net)
* [A More Modern Scale for Web Typography](http://typecast.com/blog/a-more-modern-scale-for-web-typography)
