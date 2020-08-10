![Alt Text](https://www.simplilearn.com/ice9/free_resources_article_thumb/X_Reasons_to_learn_Javascript.jpg)


## Objects

**In an object, variables and functions take on new names.**

**JavaScript stores the information in objects.**

**You can have objects inside of objects.**

> In an object, **variables** become known as **properties**.
  - *Properties* tell us information about the object. 
      - Examples would be: *A name of a hotel, how many total rooms, how many booked rooms, if it has a fitness center and the available room types.*

> In an object, **functions** become known as **methods**.
  - *Methods* are tasks and operations that are related to the object.
      - Examples would be: *Checking how many rooms are available by substracting booked rooms from total rooms.*

**An object consists of *keys* and *values*.**

**An object cannot have keys with the same name.**

**A value of a property (key) can be a *string*, *number*, *Boolean*, *array* or *another object*.**

**The value of a method is always a *function*.**

> Literal Notation is the easiest and most popular way to create objects.

- The object is the **curly braces and their contents**.
- The object is stored in a **variable** (eg. var hotel).
- Separate each key from its value using a **colon**.
- Separate each property and method with a **comma** (not after last value).
- Always remember that *strings* live in quotes and *arrays* live in square brackets.

> Dot Notation allows you to access a property or method of an object.

- Use the name of the object, followed by a period, then the name of the property or method you would like to access.

- The period is called the **member operator**.

`var hotelName = hotel.name;`
`var roomsFree = hotel.checkAvailability();`

> You can also access a property or method of an object with square brackets and parenthesis.
  - Necessary to access keys with special characters.

`var hotelName = hotel['name'];`
`var roomsFree = hotel['checkAvailability']();`

**Contextual "this." is the keyword used to identify a key within the object.**


![Alt Text](https://www.simplilearn.com/ice9/free_resources_article_thumb/X_Reasons_to_learn_Javascript.jpg)


## DOM - Document Object Model

**The Document Object Model (DOM) communicates how a browser will create a model/copy of an HTML page and allows JavaScript to access and update the HTML content of the web page.**

> The DOM is not part of the HTML and is not part of JavaScript.
  - The DOM is a separate set of rules.
  - The DOM is implemented by browser makers.
  - The DOM is comprised of two primary areas.
      1. When the browser loads a web page, it creates a **DOM tree**, which is a model of the web page in memory.
      1. Is able to make changes and redefine information within the DOM tree with JavaScript which updates what is loaded in the browser web page.

> An attribute of `id` or the like should be identified in the HTML.
> Retrieve a document from the DOM: `var parent = document.getElementByID();`
> If creating a new element: `var listItem = document.createElement('li');`
> Fill the new element with content: `listItem.textContent = 'I am text content';`
> Append it to the DOM: `parent.appendChild(listItem);`


[<== Back to Main Readme](README.md)

