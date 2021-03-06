*  __id__ referenced by ` # `,  __class__ referenced by ` . `
* __pseudo-class__: `a:link    { color: #FF0000; }`
  * `:active`, `:focus`, `:hover`, `:link`, `:visited`, `:first-letter`, `:first-line`, `:first-child`, `:nth-child(N)`
* __selector__   
   * group multiple selector `selector1, selector2, selector3`
   * selector2 inside selector1  `selector1 selector2`
   * selector2 directly inside selector1 ` selector1 > selector2 `
*  __font__:
    * `font-family: Garamond, "Times New Roman", serif;`
      * generic font names: serif, sans-serif, cursive, fantasy, monospace
    *  `font-size: 14pt;`, value:
      * units: pixels (`px`) vs. point (`pt`) vs. m-size (`em`)
      * vague font sizes: `xx-small`, `x-small`, `small`, `medium`, `large`, `x-large`, `xx-large`, `smaller`, `larger`
      * percentage font sizes, e.g.: `90%`, `120%`
    * `font-weight: bold;`    
      `font-style: italic;`
      * alt value ` normal ` 
*  __color__:
   *  property: ` color ` and `background-color`
   *  value:
      * color names (`red`): `aqua`, `black`, `blue`, `fuchsia`, 
         `gray`, `green`, `lime`, `maroon`, `navy`, `olive`, 
         `purple`, `red`, `silver`, `teal`, `white`, `yellow`
      * RGB codes (`rgb(128, 0, 196)`): red, green, and blue values from 0 (none) to 255 (full)
      * hex codes (`#FF8800`): RGB values in base-16 from 00 (0, none) to FF (255, full)
* __text__:
   * `text-align`: `left`, `right`, `center`, or `justify` 
      (which widens all full lines of the element so that they occupy its entire width)
   *  `text-decoration`: `underline`, `overline`, `line-through`, `blink`, or `none`
      * effects can be combined
   * `text-shadow: -2px 5px gray;` : shadow is specified as an X-offset, a Y-offset, and an optional color
   * `text-indent`
   * `line-height`, `word-spacing`, `letter-spacing`
* __border__: 
   * `h2 { border: 5px solid red; }`:
      *  thickness: specified in `px`, `pt`, `em`, or `thin`, `medium`, `thick`
      *  style: `none`, `hidden`, `dotted`, `dashed`, `double`, `groove`, `inset`, `outset`, `ridge`, `solid`
      *  color
      *  other properties:
         * `border-color`, `border-width`, `border-style`   
         * `border-bottom`, `border-left`, `border-right`, `border-top`
         * `border-bottom-color`
   * `border-radius: 12px;` 
* __padding__: `p { padding: 20px;}`, `p { padding-left: 200px; padding-top: 30px; }`
   * padding shares the background color of the element   
* __margin__: similar to padding in syntax
   * always transparent (they don't contain the element's background color, etc.)
   * `auto` margins: centering a block element
      * `p { margin-left: auto; margin-right: auto; width: 750px; }`
      * works best if `width` is set (otherwise, may occupy entire width of page)
      * to center inline elements within a block element, use `text-align: center`
* __dimensions__: `width`, `height`, or `max-width`, etc. with value in `px` `pt`, or percentage 
* list `ol { list-style-type: lower-roman; }` 
* __background__:

  ```css
    body {
      background-image: url("images/draft.jpg");
      background-repeat: no-repeat;
      background-position: 370px 20px;
    }
  ```
  * value of `background-repeat` can be `repeat` (default), `repeat-x`, `repeat-y`, or `no-repeat`
  * value of `background-position` consists of two tokens,
    each of which can be `top`, `left`, `right`, `bottom`, `center`,
    a percentage, or a length value in `px`, `pt`, etc
      * can also be negative




