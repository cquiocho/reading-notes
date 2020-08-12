![Alt Text](https://upload.wikimedia.org/wikipedia/commons/e/ea/CSS_text_representation.png)

## Layouts

*Block Level Elements* - Start on a new line and will take up an entire line on the page.
  - example: `<section>` and `<div>`

*Inline Level Elements* - Flow in between surrounding text and will only take up as much space needed.
  - example: `<span>` and `<img>`

*Parent Element* - The outer block level element that has another block level element inside of it.

### Positioning Schemes

#### There are 5 positioning schemes:

  - Normal Flow - Also known as *static positioning*, is the default behavior unless the browser is told to do something else. Every block element appears on a new line.

  - Relative Positioning - Moves an element to the top, right, bottom or left of where it would have been by default.

  - Absolute Positioning - Element is taken out of normal flow and is positioned in relation to its containing element. It will move as users scroll through the page.

  - Fixed Positioning - Positions the element in relation to the browser window. It is taken out of normal flow and will not move as users scroll through the page.

  - Floating Elements - Element is taken out of normal flow and positions it to the left or right of a containing box allowing content to flow around it. It is important to use the width property with this positioning.

*When using relative, fixed or absolute positioning boxes can overlap.*

*Using the z-index allows you to control what box sits on top, the box with the higher index (10 v. 5) will be on top.*

**Clearing Floats - This property states that no element within the same containing element should touch the left or right sides of a box. This property assists with improper positioning.
  - Has four values: left, right, both, none

### Screen Sizes & Resolutions

*There are different sizes of screens which will show different amounts of information. Designs need to work on these various sizes.*

*Resolution refers to the number of dots per inch on a screen*

**Due to various sizes and resoulutions, designers often create pages that are *960 - 1000 pixels* wide.**

#### Fixed Layouts
  - Fixed width layout designs do not change size whether the user increases or decreases browser size. Measurements are in pixels.

#### Liquid Layouts
  - Liquid layout designs stretch and contract with changes in browser size. Measurements tent to use percentages.


[<== Back to Main Readme](README.md)