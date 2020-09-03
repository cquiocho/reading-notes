![Alt Text](https://storage.needpix.com/rsynced_images/html-1695519_1280.png)

## Images

<a href="http://www.unsplash.com">Image Website</a>

### Adding Images

- To add an image, you must use an `<img>` element and must have the following attributes:
  - **src** - This is where you find the image. It can be an absolute URL or relative URL.
  - **alt** - This provides a text description of the image.
  - **title** - Provides additional information of the image.

`<img src="images/location" alt="text description" title="additional info" />`

### Height and Width of Images

- It is very common to see an `<img>` element use the following attributes:
  - **height** - Specifies height of the image in pixels.
  - **width** - Specifies width of the image in pixels.

*It is recommended to only adjust width or height, not both.*

### Position of Images

- Where an image is placed in the code will affect where it is displayed.
  - Before a paragraph `<img><p>`.
  - Inside the start of a paragraph `<p><img>`.
  - Middle of a paragraph `<p><img></p>`.

### Rules for Creating Images

1. Save images in the right format.
  - Websites mainly use jpeg, gif or png format.
1. Save images at the right size.
  - Save in the same width and height as it will appear on the website.
1. Measure images in pixels.
  - Images dispalyed on screens are in pixels. Measure in pixels and not in centimeters or inches.

- *JPEG* - Preferred format when there are many colors in a picture.
- *GIF or PNG* - Preferred format for images with few colors. 

**Avoid cropping images. Best to source images that are the correct shape and size**

### Transparency

**Partially transparent images requires using one of two formats:**
  
  1. *Transparent GIF* - Straight edges and is 100% transparent.
  1. *Transparent PNG* - Diagonal or rounded edges, semi-opaque or drop shadow.


![Alt Text](https://p0.pxfuel.com/preview/920/519/697/abstract-php-c-analytics.jpg)


### Color – RGB Values, Hex Codes, Color Names

### **Characteristics of Color:**

- **Hue** is the visual appearance of the color.
- **Saturation** is the amount of gray in a color. Maximum saturation would have no gray.
- **Brightness** is the amount of black in a color. Maximum brightness would have no black. 

### **The contrast between text color and background color is extremely important**

- **Low Contrast** – Text is harder to read when there is low contrast between text and background.
- **High Contrast** – Text is easier to read when there is high contrast between text and background.
- **Medium Contrast** – For long spans of text, reducing contrast improves readability.

### **Additional Characteristics:**
- **Opacity** - Not transparent or translucent. **RGBA**
- **Transparency** – Able to see through. **HSLA**


![Alt Text](https://upload.wikimedia.org/wikipedia/commons/e/ea/CSS_text_representation.png)


## Text

### Typeface Terminology

- Serif - Have extra details on the end of the main strokes.
- Sans-Serif - Have straight ends to letters and have a cleaner design.
- Monospace - Every letter is the same width.
- Cursive - Have joining strokes or handwriting styles.
- Fantasy - Decorative and often used for titles.

### Typeface Techniques

- Font-Family - Property allows you to specify typeface.
- Font-Size - Property that adjusts size in pixels, percentage or ems.
- Font-Face - Allows you to use a font even if it isn't installed on the browser.
- Font-Weight - Creates bold text. Has two values: normal and bold.
- Font-Style - Creates italic text. Values: normal, italic, oblique.
- Text-Transform - Values: uppercase, lowercase, capitalize.
- Text Decoration - Values: none, underline, overline, line-through, blink.
- Line-Height - *Leading* use for the vertical space between lines of text.
- Letter-Spacing - *Kerning* use for the space between each letter.
- Word-Spacing - Property that changes the spacing between words.
- Text-Align - Values: left, right, center, justify.
- Vertical -Align - Primariy used with inline elements and an image. Values: baseline, sub, super, top, middle, bottom, text-top, text-bottom.
- Text-Indent - Allows you to indent the first line of text.

- First-Letter / First-Line - Pseudo-element that allows you to specify different values for the first letter or first line of text.
- Link / Visited - Allows for links that have and have not been visited.


[<== Back to Main Readme](README.md)