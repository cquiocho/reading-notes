![Alt Text](https://storage.needpix.com/rsynced_images/html-1695519_1280.png)

## HTML Text

**HTML Tags, also known as *markup*, are used to create web pages.**
**HTML Elements, are used to describe structure.**

#### Structural Markup:
  - Headings - `<h1>` thru `<h6>`, there are six levels of headings.
  - Paragraphs - `<p>``</p>`
  - Bold - `<b>``</b>`
  - Italic - `<i>``</i>`
  - Superscript - `<sup>``</sup>`
  - Subscript - `<sub>``</sub>`
  - Whitespace - used to make code easier to read. When a browser comes across two or more repeated spaces, it only displays as one. Known as *white space collapsing*.
  - Line Breaks - `<br />`, to add a line break on a new line or in the middle of a paragraph.
  - Horizontal Rules - `<hr />`, to create a break between themes, horizontal line.

  **Line Breaks and Horizontal Rules are known as *empty elements*, having only *one* tag.**

  #### Semantic Markup:

  *Text elements not inteded to affect the structure of a web page, but add extra information.*

  - Strong - `<strong>``</strong>`, indicates high importance resulting in **bold style**.
  - Emphasis - `<em>``</em>`, indicates subtle changes in meaning resulting in *italic style*.
  - Blockquote - `<blockquote>` `</blockquote>`, element used for longer quotes that can be viewed as its own paragraph.
  - Quotations - `<q>``</q>`, element used to add quotation marks.
  - Abbreviation - `<abbr>``</abbr>`, `title=` attribute used to specify full term.
  - Citation - `<cite>``</cite>`, referencing a source 
  - Definition - `<dfn>``</dfn>`, identifies new terminology in a document. Some browsers show effect in *italic*, otherwise no change in appearance. 
  - Author Details - `<address>``</address>`, used to contain contact details of an author of a page. Physical address, phone number and/or email address.
  - Insert - `<ins>``</ins>`, used to demonstrate content inserted in a document, appears as *underlined*.
  - Delete - `<del>``</del>`, used to demonstrate deleted content, appears as *strikethrough*.
  - Strikethrough - `<s>``</s>`, indicates something is no longer needed, yet should not be deleted. 

![Alt Text](https://p0.pxfuel.com/preview/920/519/697/abstract-php-c-analytics.jpg)

# CSS – Cascading Style Sheets
### CSS enhances how content is presented and adds a layer of style to the web page.
### CSS allows you to create rules that specify how an element should appear.

### **Contains TWO parts – Selector & Declaration**

- **Selectors** indicate which element the rule applies to.
- **Declarations** indicate how the element will be styled.

### **CSS declarations sit inside curly brackets { … } and is made up of TWO parts:**

- **Properties** indicates what aspect of the element will be changed
- **Values** indicate the specific setting for the property

![Alt Text](https://www.simplilearn.com/ice9/free_resources_article_thumb/X_Reasons_to_learn_Javascript.jpg)

# Programming with Javascript

## Javascript can be used in browsers to make websites interactive, interesting and user-friendly.

- Understand **basic programming concepts and terms**
- Learn the **language and vocabulary** 
- Familiarize with **how to apply** the language

### Javascript makes web pages more interactive by:

- *Accessing Content* - select any element, attribute or text.
- *Modify Content* - add elements, attributes and text.
- *Program Rules* - specify a set of steps or instructions.
- *React to Events* - specify what will run when a specific event has been triggered.   

**Script** - series of instructions that a computer will follow to achieve a goal.
*scripts are like receipes, handbooks or instrucional manuals*
*scripts are step-by-step instructions*

1. State your Goal
1. List the Tasks - Flowchart
1. Design the Script - List the Steps
1. Code Each Step

### Expressions & Operators

**Expressions evaluates into a single value.**

- Assign a value to a variable: 
  > var color = 'beige';

- Use two or more values to return a single value: 
  > var area = 3 * 2;

**Operators allow programmers to create a single value from one or more values.**

- *Assignment Operators* assign a value to a variable:
  > color = 'beige';

- *Arithmetic Operators* perform basic math:
  > area = 3 * 2;

- *String Operators* combine two strings:
  > greeting = 'Hi ' + 'Molly';

- *Comparison Operators* compare two values and return **true** or **false**:
  > buy = 3 > 5;

- *Logical Operators* combine expressions and return **true** or **false**:
  > buy = (5 > 3) && (2 < 4);

**Functions group a series of statements together to perform a specific task**

- *Function Declaration* - giving a name to the function and writing the statements needed to achieve the task inside curly braces.
  > function sayHello() {
  >    document.write('Hello!');
  > }

- *Calling the Function* - following function declaration, you can execute all of the statements within curly brackets with just one line of code.
  > sayHello();

- *Parameters* - specific information inside a function needed to perform the task. Inputted upon function declaration.
  > function getArea(width, height) {
  >    return width * height;
  > }

- *Arguments* - specific values or variables found in parenthesis following a function with parameters.
   
   1. Arguments with Values:
      > getArea(3, 5);

   1. Arguments with Variables:
      > wallWidth = 3
      > wallWidth = 5
      > getArea (wallWidth, wallHeight);

![Alt Text](https://cdn.pixabay.com/photo/2018/04/20/21/10/code-3337044_960_720.jpg)

# Operators and Loops

## Comparison Operators : Evaluating Conditions

### Evaluate a situation by comparing one value to another, result will be *true* or *false*.

- '==' - **Is equal to**. Compares two values to see if they are the same.
- '!=' - **Is not equal to**. Compares two values to see if they are not the same.
- '===' - **Strict equal to**. Compares two values to check that both the data type and value are the same.
- '!==' - **Strict not equal to**. Compares two values to check that both the data type and value are not the same.
- '>' - **Greater than**. Checks if the number on the left is greater than the number on the right.
- '<' - **Less than**. Checks if the number on the left is less than the number on the right.
- '>=' - **Greater than or equal to**. Checks if the number on the left is greater than or equal to the number on the right.
- '<=' - **Less than or equal to**. Checks if the number on the left is greater than or equal to the number on the right.

## Logical Operators

### Allows you to compare the results of more than one comparison operator.

- '&&' - Logical **and**. Tests more than one condition.
- '||' - Logical **or**. Tests at least one condition.
- '!' - Logical **not**.  Takes a single Boolean value and inverts it.

## Loops

### Will continuously check a condition until it returns false. There are three common types of loops:

1. **For** - Code will run for a specific number of times, usually set as a counter.
    - *Initialization* - Create a variable and set to 0.
    - *Condition* - Will run until the counter reaches a specific number.
    - *Update* - Each time the loop runs will add one to the counter.
1. **While** - Code will run for as long as the condition is true.
1. **Do While** - Code will continue to run even if the condition evaluates as false.


[<== Back to Main Readme](README.md)