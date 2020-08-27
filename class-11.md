![Alt Text](https://upload.wikimedia.org/wikipedia/commons/e/ea/CSS_text_representation.png)


## Controlling the Size & Alignment of Images using CSS

You can control the **size** of an image by using the following properties:
> - width
> - height

*Pixels are the recommended method of measurement for image resizing.*

You can **align** images using the following properties:
> - float
> - align-left
> - align-right

**By default, images are inline elements.**

Centering an image requires the following steps:
  - Turn the image into a **block-level** element by using `display: block;`
  - On the **containing element** use `text-align: center;`
  - On the **image** use `margin-left: auto;` & `margin-right: auto;`

Using an image as a background requires the use of:
> - `background-image: url("img/photo.jpg);`

*The background image placement is dependent on where you place it. For instance,in the **body** for entire background or in an element such as a **paragraph**.

Repeating background images use the `background-repeat` property:
> - `background-repeat: repeat;` - repeated **horizontally** and **vertically**.
> - `background-repeat: repeat-x;` - repeated **horizontally** only.
> - `background-repeat: repeat-y;` - repeated **vertically** only.
> - `background-repeat: no-repeat;` - image only shown **once**.

The `background-attachment` property specifies whether it sstays in place or moves up and down the page:
> - fixed - image stays in same position on the page.
> - scroll - image moves up and down as the user scrolls.

If an image is not being repeated, you can specify where the background image should be placed with `background-position`:
> - left top
> - left center
> - left bottom
> - center top
> - center center
> - center bottom
> - right top
> - right center
> - right bottom

Background Shorthand order:
1. background-color
1. background-image
1. background-repeat
1. background-attachment
1. background-position

*You may miss any value if you do not want to specify it*


![Alt Text](https://p0.pxfuel.com/preview/920/519/697/abstract-php-c-analytics.jpg)


## Practical Infomation

### Search Engine Optimization (SEO)

**SEO improves website visibility on search engines.**

- On-Page Techniques - Methods used on the web page to improve search engine rating. There are **seven** key place where keywords can be placed:
1. Page Title - `<title>`
1. URL / Web Address
1. Headings - `<h1>`
1. Text - **Repeat keywords** in main body of text. 
1. Link Text - Use keywords in text that create **links**.
1. Image Alt Text - Accurate image **descriptions**.
1. Page Descriptions - `<meta>`

**There are SIX steps that can help with identifying correct keywords to use:**
1. Brainstorm - List the words.
1. Organize - Group into different categories or lists.
1. Research - Use tools like: adwords.google.com, wordtracker.com, keyworddiscovery.com.
1. Compare - Check out the competition.
1. Refine - Pick specific keywords to focus on.
1. Map - Decide where to place the keywords.

**Domain Names & Hosting**

*Putting your website on the web requires a domain name and web hosting.*

- **Domain Name** - Web address.
- **Web Hosting** - You will need to upload your site to a web server. 
- **FTP - File Transfer Protocol**: allows you to transfer files locally to the web server hosting your site.


![Alt Text](https://storage.needpix.com/rsynced_images/html-1695519_1280.png)


## Audio & Video Elements

[Video and Audio APIs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Video_and_audio_APIs)

**Usage is very similar to image properties, however it requires the use of the following element tags:**
> - `<audio>`
> - `<video>`


[<== Back to Main Readme](README.md)