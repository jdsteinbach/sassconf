# <small>Using</small> Musical Scales <small>to Build</small> Harmonious Typography

## Musical Intervals & Math

### Every musical note is a number

Every musical note is a number: a frequency vibrating a certain number of times per second (measured in hertz).

### Between any octave on a musical scale, the frequency doubles.

| Concert A = 440Hz | A<sup>5</sup> = 880Hz |
| --- | --- |
| Middle C ~= 131Hz | C<sup>4</sup> ~=262Hz |

### Every fifth is ~1.5&times;.

| A<sup>3</sup> = 220Hz | E<sup>4</sup> ~=330Hz |
| --- | --- |

### Every half-step is a 1.0595&times; increase.

Every half-step (the building block of Western scales) is a 1.0595&times; increase.

All other intervals work as exponents of the half-step interval.

  * A (440Hz) &times; 1.0595 = A<sup>#</sup> (466.16Hz) &times; 1.0595 = B (493.88Hz)
  * A (440Hz) &times; 1.0559<sup>2</sup> = B (493.88Hz)

## Typography & Modular Scales

### Current state of modular scale Sass libraries

  * [Modular Scale](http://www.modularscale.com/)
  * [Sassline](https://sassline.com/)
  * [Typesettings](http://typesettings.io/)
  * [Type Scale](http://type-scale.com/)
  * [Gridlover](http://www.gridlover.net/)
  * [ALA: More Meaningful Typography](http://alistapart.com/article/more-meaningful-typography)

### Literal modular scales

  * Every interval is the same
  * A musical half-step scale is literally modular *~play half-step scale~*
  * A musical whole-step scale is literally modular *~play whole-step scale~*

### Non-literal / quasi-modular scales

  * Major & minor scales are created by alternating whole- & half-step scales (WWHWWWH) / (WHWWHWW)
  * These patterns repeat every octave, creating a non-literal / organic modular scale.

### Non-literal / quasi-modular scales

ALA article above briefly discusses a “double-stranded modular scale” which also avoids the single increment limit of literal modular scales, but is less adjustable than music-based type scales.

## See & Hear

### Single Intervals

#### Octave

#### Fifth

#### Major Third

### Scales

#### Major-scale

#### Pentatonic

#### Major Triad

### Responsive musical scales

  * By decreasing the number of notes per octave, you can increase font sizes more quickly, taking advantage of larger screens.
  * By increasing the number of notes per octave, you can slow the growth of font sizes, keeping content visible on small screens.

## Intro to TypeTuner

### Point audience to my [TypeTuner](http://typetuner.com) library & quickly overview public functions/mixins

## Thanks!

### James Steinbach

[@jdsteinbach](https://twitter.com/jdsteinbach)

[jdsteinbach.com](https://jdsteinbach.com)
