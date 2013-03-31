*  __id__ referenced by ` # `,  __class__ referenced by ` . `
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
* list `ol { list-style-type: lower-roman; }`

