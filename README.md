# CCS style blocks

## 1. positioning

* **{ display: }**
    * none _(hide from the page)_
    * block _(block mapping)_
    * inline _(line display)_
    * inline-block  _(behaves externally as a row, and internally as a block)_
    * flex
        + flex-direction
        + flex-wrap
        + justify-content
        + align-items
        + align-content
    * grid
        + grid-template-columns
        + grid-template-rows
        + fr _(fraction)_
        + justify-items
        + align-items
        + grid-template-areas
* **{ position: }**
    * static
    * relative
    * absolute
    * fixed
    * sticky
    * inherit
* **{ float: }**
    * left
    * right
* **{ z-index: }**

___

## 2. block model and sizes

* **{ width: }**
* **{ height: }**
* **{ box-sizing: }**
    * content-box
    * border-box
* **{ margin: }**
    * 0 auto
    * N _(all sides)_
    * N N _(top-bottom | left-right)_
    * N N N _(top | left-right | bottom)_
    * N N N N _(top | right | bottom | left)_
* **{ border: }**
    * -color
    * -style
        + solid
        + dotted
        + dashed
        + double
* **{ padding: }**
    * -top
    * -right
    * -bottom
    * -left

___

## 3. typography (text properties)

* **{ font-family: }**
    * serif (Times)
    * sans-serif (Arial)
    * monospace (Courier)
    * cursive (italic)
    * fantasy
* **{ font-size: }**
* **{ color: }**
* **{ letter-spacing: }**
* **{ line-height: }**
* **{ text-align: }**
    * left
    * center
    * right
    * justify
* **{ font-weight: }**
    * 100 _(thin, hairline)_
    * 400 _(normal, regular, book)_
    * 600 _(semi bold, demi bold)_
    * 800 _(extra bold, ultra bold)_
* **{ text-decoration: }**
* **{ white-space: }**
* **{ text-overflow: }**
* **{ text-shadow: }**

___

## 4. display (design)

* **{ overflow: }**
    * visible
    * hidden
    * scroll
    * auto
    * initial
    * inherit
* **{ opacity: }**
    * 0
    * 0.5
    * 1
* **{ visibility: }**
    * visible
    * hidden
* **{ background-color: }**
* **{ background-image: }**
    * linear-gradient ()
    * radial-gradient ()
    * background-position
    * background-size
    * background-repeat
    * background-attachment
* **{ box-shadow: }**
    * Х
    * У
    * blur
    * spread
    * color

___

## 5. animation

* **@media:**
    + mobile first 
    + desktop first 
* **@keyframes animationName {...}**
    + animation-name: animationName;
    + animation-duration
    + animation-iteration-count
    + animation-direction
    + animation-timing-function
    + animation-delay
    + animation-play-state

## 6. other

