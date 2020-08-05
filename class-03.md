![Alt Text](https://storage.needpix.com/rsynced_images/html-1695519_1280.png)

## HTML Lists

- Ordered Lists - `<ol>``</ol>`, Each item in the list is numbered.
- Unordered Lists - `<ul>``</ul>`, list that begins with a bulletpoint.
    - List Item - `<li>``</li>`, each item in an ordered or unordered is placed between these tags.
- Definitions Lists - `<dl>``</dl>`, series of terms and their definitions.
    - Definition Term - `<dt>``</dt>`, contains the term being defined.
    - Definition - `<dd>``</dd>`, contains the definition.

- Nested Lists - A list within another list, will change bulletpoint style.

![Alt Text](https://p0.pxfuel.com/preview/920/519/697/abstract-php-c-analytics.jpg)

## Boxes

### Box Dimensions

*By default a box is sized just big enough to hold its contents.*

- Width & Height - To set your own box dimenstions. Specify size by:
  - Pixels - Most popular method, accurately controls size specifications.
  - Percentages - Size of box is relative to the browser window, or if within another box, a percentage of that containing box.
  - Ems - Size of box is based on the size of the text within it.

- Min-Width & Max-Width - Used to expand and shrink to fit screen size.
- Min-Height & Max-Height - Used to limit the height of a box.

- Overflow - This property instructs the browser what to do if the content exceeds the size of a box.
  - Hidden - This will simply hide content that does not fit.
  - Scroll - This will add a scrollbar to the box to view extra content.

  *Every box has three properties that can be adjusted to control appearance*

  - Border - Separates the edge of one box from another.
  - Margin - Sits outside of the edge of the border.
  - Padding - The space located between the border and any content contained within it.

  *Borders, margin and padding are added to the height and width of a box.*

  *Padding and margin properties add **white space** and **vertical margins** between items on a page.*

  - Border-Width - Value can be given in *pixels* or *thin, medium, thick*.
    - You may also control the individual border widths by using:
      - *border-top-width*
      - *border-right-width*
      - *border-bottom-width*
      - *border-left-width*
  
  - Border-Style - Control the specific style of border, 9 styles:
    - Solid - Single line.
    - Dotted - Series of square dots.
    - Dashed - Series of short lines.
    - Double - Two solid lines.
    - Groove - Appears to be carved into page.
    - Ridge - Appears to stick out from page.
    - Inset - Appears imbedded into page.
    - Outset - Looks to be coming out of screen.
    - Hidden/None   
  
    - You may also control the individual border styles by using:
      - *border-top-style*
      - *border-right-style*
      - *border-bottom-style*
      - *border-left-style*

  - Border-Color - You may specify color using RGB, hex codes or names.
    - You may also control the individual border color by using:
      - *border-top-color*
      - *border-right-color*
      - *border-bottom-color*
      - *border-left-color*

  - Shorthand Border - This property allows you to specify width, style and color in one property. Values should be coded in the stated order.

- Padding - Property used to specify how much space between the content and border.
  - You may specify different values for each side by using:
      - *padding-top*
      - *padding-right*
      - *padding-bottom*
      - *padding-left*

- Margins - Property used to specify how much space between boxes.
  - You may specify different values for each side by using:
      - *margin-top*
      - *margin-right*
      - *margin-bottom*
      - *margin-left*

*If one box sits on another box, the margins are collapsed and the larger of the two margins will be used.*

**Centering - Set both left-margin and right-margin to *auto*.**

**Display - This property allows you to turn an inline element in to a block-level element, vice versa and also used to hide an element.**
  1. inline - causes a block element to act inline
  1. block - causes inline element to act block
  1. inline-block - causes block to flow inline but retain other clock level features.
  1. none - hides an element from the page.

### CSS3 Properties

  - Border-Image - Applies an image to the border of a box.
  - Box-Shadow - Allows you to add a drop shadow around box.
  - Border-Radius - Creates rounded corners and more rounded box shapes.

![Alt Text](https://www.simplilearn.com/ice9/free_resources_article_thumb/X_Reasons_to_learn_Javascript.jpg)

## Arrays

*An array is a special type of variable that doesn't just store one value, it stores a **list of values**.*

*Consider using an array when you are working with a list or set of values that are related.*

### Values in an Array

- Values in an array are identified in a numbered list.
- Each item is given a *index* number, numbering starts at 0.
- To access an item, array name is specified along with the index number.
- Length property holds the number of items in the array. *Always remember that the array index starts at 0*.

- Push - Command that adds an item to the end of an array.
- Pop - Command that removes the last item in an array.

### If...Else Statements

- These statements will check a condition.
- If it is **true**, the first code block is executed.
- If it is **false**, the next code is executed instead.

### Switch Statements

- Starts with a *switch value* and a list of possible *cases*.
- Purpose is to present different values or messages depending on how the switch value is answered.
- There is a *default* option if none of the cases match.
- If a match is found, a specific case is run.
- A *break* statement is used to stop the rest of the switch statement.

## Loops

### Will continuously check a condition until it returns false. There are three common types of loops:

1. **For** - Code will run for a specific number of times, usually set as a counter.
    - *Initialization* - Create a variable and set to 0.
      > var i = 0;
    - *Condition* - Will run until the counter reaches a specific number.
      > i < 10;
    - *Update* - Each time the loop runs will add one to the counter.
      > i++
1. **While** - Code will run for as long as the condition is true.
1. **Do While** - Code will continue to run even if the condition evaluates as false.


[<== Back to Main Readme](README.md)