![Alt Text](https://p0.pxfuel.com/preview/920/519/697/abstract-php-c-analytics.jpg)

## Forms

*Forms allow you to collect information and data from users.*

### Form Controls

*Types of form controls used to collect information are:*

- Adding Text:
    - Text Input - Single line input such as an email address or name.
    - Password Input - Masks characters entered.
    - Text Area - For messages and comments.

- Making Choices:
    - Radio Buttons - Select one from a number of options.
    - Checkboxes - Select or unselect one or more options.
    - Drop-down Boxes - Pick an option from a list.

- Submitting Forms:
    - Submit Button - Enter data from a form to another web page.
    - Image Button - Enter an image.
    - File Upload - Allows users to upload files to a website. 

### How Forms Work

  1. User fills a form and presses a button to submit information to the server.
  1. **Name** and **value** are sent to the server.
  1. The server processes the information and may also store the information. 
  1. Server creates a response to the user based on information received.

### Form Tags & Elements

> `<form>` - Form controls live inside this element.
  - Every form element requires an **action**.
  - Forms can be sent via two **methods**:
      - *get* - Default method where values are added to the end of the action attribute. Ideal for shorter forms or smaller amounts of data.
      - *post* - Values are sent in HTTP headers. Ideal for uploading files, larger amounts of data, sensitive information, more complex information.
 
 **example:** `<form action="http://web.address" method="get">`

> `<input>` - This element is used to create several form controls. Its value is determined by the type="" attribute.
    
**Text Input:**
 > *type="text"* - Type value for text input.
 - **name=** - Identifies name of text input.
 - **maxlength** - Attribute that limits the amount of characters entered.

 **example:** 
 >`<p>Username:`
 >`<input type="text" name="username" maxlength="4" />`
 >`</p>`

**Password Input:**
> *type="password"* - Type value for password input. Will blockout characters.

**Text Area:**
> `<textarea>` - This element creates a multiline text input.

 **example:** 
 >`<p>Tell me about your experience?</p>`
 >`<textarea name="comments" cols="20" rows="8">Comments here...</textarea>`

**Radio Button:**
> *type="radio"* - Pick from just one of the options given.
- **value=** - Indicates the selected option that will be sent to the server.
- **checked=** - Optional, may be used to pre-select an option.

**example:** `<input type="radio" name="pet" value="dog" checked="checked" />Dog`

**Checkbox:**
> *type="checkbox"* - Able to select or unselect multiple options.
- This input type uses the attributes **value=** and **checked+** as well.

**example:** `<input type="checkbox" name="pet" value="dog" checked="checked" />Dog`

**Drop Down List Box:**
> `<select>` - This element allows users to select an option from a list.
> `<option>` - This element is used to specify the option choices in the list.
- **selected** - Optional, may be used to pre-select and option, similar to **checked=**.

 **example:** 
 >`<p>What is your favorite color?</p>`
 >`<select name="colors">`
 >`<option value="red">Red</option>`
 >`<option value="blue">Blue</option>`
 >`</select>`

 **Multiple Select Box:**
- Allows users to select or unselect multiple options in a list.
- You can turn a drop down list into a drop down selct box by adding the **size** and **multiple** attributes.
- *size* - Used to turn the drop down list into a multiple option box.
- *multiple* - Allows users to select multiple options.

 **example:** 
 >`<p>What is your favorite color?</p>`
 >`<select name="colors" size="2" multiple="multiple>` 
 >`<option value="red">Red</option>`
 >`<option value="blue">Blue</option>`
 >`</select>`

**Uploading and Submitting Collected Information:**
> *type="file"* - Users are able to upload a file (images, videos, documents) with **file input box**. Method for file input should be **post**.

> *type="submit"* - Users can send information with a **submit button**. 

 **example:** 
 >`<p>Upload your resume.</p>`
 >`<input type="file" name="resume" /><br>` 
 >`<input type="submit" name="Upload" /><br>`

**Labeling Form Controls:**
> `<lable>` - Indicates the purpose of each form control and makes the form accessible to vision-impaired users.
- *for* - Attribute used to state what form control the lable belongs to.

 **examples:** 
 >`<lable>Age: <input type="text" name="age" /></lable>`
 >`<label for="male">Male</lable>`

 **Grouping Form Elements:**
 > `<fieldset>` - Used to group related form controls together. Used for longer forms and will appear within its own container.
> `<legend>` - An element that indentifies the the group of form controls, acts as a title for the form control contents.

 **example:** 
 >`<fieldset>`
 >`<legend>Contact details</legend>`
 >`<fieldset>`

**HTML5 Text Input:**
> *type="date"* - Input element attribute that will validate for a specific date.
> *type="email"* - Will check that input entered is in a valid email format.
> *type="url"* - Will verify that the input is a web page address.
> *type="search* - Used to create a single line text box for search queries.
- *placeholder* - Attribute that has a text value that will be shown in the text box until user inputs information.


![Alt Text](https://upload.wikimedia.org/wikipedia/commons/e/ea/CSS_text_representation.png)


## Lists, Tables and Forms

**Below are a list of several CSS properties that work with controlling the appearance of lists, tables and forms.**

### Lists

> list-style-type: Controls the shape and style of a bulletpoint (also known as markers). 
- Can be used on `<ol>, <ul> and <li>` elements.
    
    - *Ordered lists* can have the following values:
          - decimal - 
          - decimal-leading-zero
          - lower-alpha
          - upper-alpha
          - lower-roman
          - upper-roman
      
    - *Unordered Lists* can have the following values:
          - none
          - disc
          - circle
          - square

> list-style-image: To specify an image to act as a marker.
- - Can be used on `<ul> and <li>` elements.
   
**example:** 
>`url("images/star.png)>`

 > list-style-position: Indicates whether the marker should be *inside* or *outside* of the box.

### Tables

*Utilize the following CSS properties to style tables:*

- **width** - Set width of table.
- **padding** - Set the space between content and border.
- **text-transform** - Convert table headers to all uppercase.
- **letter-spacing** - Add additional styling to table headers.
- **font-size** - Add additional styling to table headers.
- **border-top** - Set borders to top of table headers.
- **border-bottom** - Set borders to bottom of table headers
- **text-align** - Align content to the left or right of table cells.
- **background-color** - Change the color of alternating table rows.
- **:hover** - Highlight a table row when mouse goes over it.

- **empty-cells** - This property will specify whether an empty cell's border will be shown. It can take one of three values:
    - *show*
    - *hide*
    - *inherit* - When a tabel is within another table, it will inherit the rules of the containing table.

- **border-spacing** - Controls the distance between adjacent cells.
- **border-collapse** - Prevents adjacent borders from creating a thicker border. It can take one of two values:
    - *collapse* - Merges into one border.
    - *seperate* - Borders will detach from each other.


### Forms

*Utilize the following CSS properties to style text inputs in forms:*

- **font-size** - Sets the font size entered by the user.
- **color** - Sets the text color of the input.
- **background color** - Sets the background color of the input.
- **border** - Adds a border to the edge of the input box.
- **border-radius** - Addes to create rounded corners to the input box.
- **:focus** - Used to change background color when the being used.
- **:hover** - Same styles used when hovered over.
- **background-image** - Adds a background image to the box.

*Utilize the following CSS properties to style submit buttons:*

- **color** - Changes color of text on button.
- **text-shadow** - Applies a three dimensional look to text.
- **border-bottom** - Used to give bottom border of button a thicker appearance.
- **background-color** - Used to make the button stand out from other items around it.
- **:hover** - Changes the appearance of button when hovered over.


![Alt Text](https://www.simplilearn.com/ice9/free_resources_article_thumb/X_Reasons_to_learn_Javascript.jpg)


## Events

*The browser recognizes different types of events. It is our JavaScript that responds to these events by:*

1. **Interactions create events.** 
1. **Events trigger code.**
1. **Code responds to users.**

### Event Handling

**There are *three steps* involved in getting JavaScript code to trigger. This is called *event handling*:**

1. Select the element node(s) that will be responded to.
1. Specify the event on the node that will trigger/fire the event. Also known as **binding** an event to a DOM node.
1. Call the code that you want to run when the event occurs.

### Binding an event to an element

1. **Traditional DOM Event Handlers:**

  - All browsers understand this method of creating an event handler.
  - Major drawback is only one function can be attached to each even handler.
  - Syntax used to bind an event to a handler:

`element.onevent = functionName;`

  1. Element - DOM element node to target.
  1. Event - Bound to target and preceded by the word **on**.
  1. Function - Name of function to call (no parenthesis needed).

1. **DOM Event Listeners:**

  - Are a more recent approach to handling events.
  - Able to run more than one function at a time.
  - Syntax to bind an event to an event listener:

`element.addEventListener('event', functionName [, Bookean]);`

  1. Element - DOM element node to target.
  1. **addEventListener**
  1. Event - Event to bind node(s) to in **quotation marks**.
  1. Code - Name of function to call.
  1. Event Flow - Also known as **event capturing** or **bubbling**, the event starts at the leas specific node an flows inwards to the most specific one.


[<== Back to Main Readme](README.md)

