![Alt Text](https://storage.needpix.com/rsynced_images/html-1695519_1280.png)

## HTML Links

### Common Types of Links:
> Links from one website to another
> Links from one page to another on the same website
> Links from one part of a web page to another part of the same page
> Links that open in a new browser window
> Links that start up you email and address a new email to someone

#### Links are created by:
  1. Using the `<a>``</a>` element.
  1. Using the *href* attribute.
  1. Using a *page link*.
  1. Using a *link text* that explains where.

Example: `<a href="http://www.imdb.com">IMDB</a>`

**URL - Uniform Resource Locator**

- Linking to other sites require an:
    - *Absolute* URL, full website address.
- Linking to other pages on the same site:
    - *Relative* URL, also known as shorthand.
- Email Links require:
    - *mailto:* in the href attribute: `<a href="mailto:james@hot.com>`
- Opening links in a new window requires:
    - *target* attribute: `<a href="http://website" target="_blank">`
- Linking to a specific part of the same page uses:
    - *id* attribute: `<h1 id="top"></hi>` - `<a href="#top"></a>`
- Linking to a specific part of another page uses:
    - *id* attribute that identify specific parts of the page using # symbol. `<a href="http://website.com/#bottom>`

*Use `../` to go back a directory in a relative URL.*

![Alt Text](https://p0.pxfuel.com/preview/920/519/697/abstract-php-c-analytics.jpg)

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


![Alt Text](https://www.simplilearn.com/ice9/free_resources_article_thumb/X_Reasons_to_learn_Javascript.jpg)

## Functions

**Functions group a series of statements together to perform a specific task.**

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


![Alt Text](http://res.publicdomainfiles.com/pdf_view/70/13929280214608.png)

## 6 Reasons for Pair Programming

### What is Pair Programming?

**A common technique that utilizes several software engineering practices that dramatically improve the quality of code developers produce. These include:**
  - Iterative Loops
  - Code Reviews
  - Fast Feedback
  - Error Checking
  - Linting

### How does it work?

**Commonly involves two roles:**
  
  - *Driver* - The programmer who is typing and handling the mechanics of coding, managing the text editor, switching files, version control and writing code.
  
  - *Navigator* - Guides the driver but does not write code. They foresee what comes next, how to convert an algorithm into code, scans for typos and bugs and utilizes their computer to look up solutions and documentation.

### Why?

**Pair programming utilizes four fundamental skills needed to lean a new language:**

1. Listening - Hearing and interpreting vocabulary.
1. Speaking - Using the words to communicate an idea.
1. Reading - Understanding the written language.
1. Writing - Producing the written language.

### 6 Reasons

1. Greater Efficiency:
    - Produces higher-quality code that doesn't require very much troubleshooting and debugging.
    - Find and create solutions faster.
    - Enhances technical skills.
    - Improves team communication.
    - Increases enjoyability in the workplace.

1. Engaged Collaboration:
    - Coding is more engaging.
    - Programmers are more focused.
    - Difficult to procrastinate working as a team.
    - Help is readily available by relying on each other.
    - Boosts overall confidence.

1. Learning from Fellow Students:
    - Different approaches to problem solving.
    - Exposure to different skill sets.
    - Helps to solidify understanding.

1. Social Skills:
    - Improves communication.
    - Improves interpersonal skills.

1. Job Interview Readiness:
    - A common step in interview processes involves pair programming.
    - Improves ability to work with and learn from others.

1. Work Environment Readiness:
    - Familiarity with pair programming.


[<== Back to Main Readme](README.md)
