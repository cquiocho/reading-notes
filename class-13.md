![Alt Text](https://p0.pxfuel.com/preview/920/519/697/abstract-php-c-analytics.jpg)


## The Past, Present & Future of Local Storage for Web Applications

*Why are cookies ineffective?*

- Included with every HTTP request slowing down the application by sending the same information over and over for no necessary reason.
- Included with every HTTP request sending unencrypted data over the internet.
- Are only limited to 4KB of data, enough to slow down the application and not enough information to be useful.

**The Goals of HTML5 Storage**

- Provide a standardized API.
- Able to be implemented natively. 
- Able to be used in multiple browsers.
- Not having to rely on third-party plugins.

*HTML5 is also referred to as **Local Storage** or **DOM Storage**.*

**What is HTML5 Storage?**

- Way for web pages to store named key/value pairs locally in the browser.
- Data remains even if page is navigated away from, closed or exited.
- Data is never transmitted to the web server unless sent manually.
- Implemented natively in web browsers without the need of third party plugins.

*HTML5 is based on key/value pairs.*

*Data is stored as a string, anything other thans strings require use of functions like `parseInt()` or `parseFloat()` to coerce the data into JS datatype*

**Standardized HTML5 default storage is 5 megabytes.**

### Saving Information into Local Storage

- Step 1: Turn data into JSON.
  
  > `var stringDogs = JSON.stringify(dogArray);`

- Step 2: Put JSON data into Local Storage. It will take **two** items:
  1. Key - Which can be anything.
  1. Value - JSON data.
  
  > `localStorage.setItem('dogs', stringDogs);`

- Step 3: Get JSON data out of Local Storage.  

  > `var whoLetTheDogsOut = localStorage.getItem('dogs');`
    `console.log('my get items are:', whoLetTheDogsOut);`  

- Step 4: Parse the recalled JSON data.

  > `var parseDogs = JSON.parse(whoLetTheDogsOut);`
    `console.log('my parse items are:', parseDogs);` 

  *option: use console.log to verify **set**,**get**, **parsed** information.*


[<== Back to Main Readme](README.md)