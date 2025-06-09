# Frontend Mentor - QR code component

![Design preview for the QR code component coding challenge](/images-readme/preview.jpg)

# What has learned?

* `overflow`
  * sets the desired hebavior when content doesn't fit in the parent elementt box (overflows)
  * visible(default) hidden clip (userd in combination with `overflow-clip-margin` scroll) auto
  * Flexbox with column flex direction also fixes the overflow issue

* `font` property

<table>
  <tbody><tr>
    <th width="15%">Property</th>
    <th>Description</th>
    <th>Values</th>
  </tr>
  <tr>
    <td>font</td>
    <td>Sets all the font properties in one declaration</td>
    <td><i>font-style, 
      font-variant, 
      font-weight, 
      font-size/line-height, 
      font-family, 
      </i>caption, 
      icon, 
      menu, 
      message-box, 
      small-caption, 
      status-bar, 
	inherit</td>
  </tr>
  <tr>
    <td>font-family
    </td>
    <td>Specifies the font family for text</td>
    <td><i>family-name, 
      generic-family, 
	</i>inherit</td>
  </tr>
  <tr>
    <td>font-size</td>
    <td>Specifies the font size of text</td>
    <td>xx-small, 
      x-small, 
      small, 
      medium, 
      large, 
      x-large, 
      xx-large, 
      smaller, 
      larger<i>, 
      length, 
      %, 
	</i>inherit</td>
  </tr>
  <tr>
    <td>font-style
    </td>
    <td>Specifies the font style for text</td>
    <td>normal, 
      italic, 
      oblique, 
	inherit</td>
  </tr>
  <tr>
    <td>font-variant
    </td>
    <td>Specifies whether or not a text should be displayed in a small-caps font</td>
    <td>normal, 
      small-caps, 
	inherit</td>
  </tr>
  <tr>
    <td>font-weight
    </td>
    <td>Specifies the weight of a font</td>
    <td>normal, 
      bold, 
      bolder, 
      lighter, <br>
      100, 
      200, 
      300, 
      400, 
      500, 
      600, 
      700, 
      800, 
      900, 
	inherit<br>
	<strong>Careful, many of these are not supported!</strong></td>
  </tr>
</tbody></table>
* `min-height`: min-height have NO effect until minmizing window to certain size 

* inline vs inline block vs block

  * inline 
    * displays an element as an inline element, height and widhth properties will have no effect(image is an exception)
    * Examples are `span` `a` `img` and formatting tags such as `em` `strong` `i` `small`
  * Inline-block
    * displays an element as an inline element except height and widhth properties will have effect
  * block
    * starts a new line and takes up the full width available, it occupies the entire width of its parent element
    * Examples are `div` `h1` `p` `li` `secion`  

  

* responsive automatically height and width adjusted image without overflowing parent element

  ```
  img {
  	display: block;
  	max-width: 100%;
  	height: auto;
  }
  ```

* Margin vs Padding
  * Margins create extra space around an element, while padding creates extra space within an element.
  
  * Use combination of margin and padding to set the outer space outside the card and inner space between card and child 
  
    ![margin and padding](/images-readme/WX20250608-205800@2x.png)  
