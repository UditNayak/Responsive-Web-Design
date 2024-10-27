# Cat Photo App

HTML tags give a webpage its structure. You can use HTML tags to add photos, buttons, and other elements to your webpage.
<br>
In this project, I learned the most common HTML tags by building your own cat photo app.
<br>

## Here is the preview of What i am going to Build.
![Preview 1](preview1.png)
![Preview 2](preview2.png)

## Tags
- Headings
    ```html
    <h1>CatPhotoApp</h1>
    <h2>Cat Photos</h2>
    ```
- Paragraph
    ```html
        <p>See more cat photos in our gallery.</p>
    ```
- Comments
    ```html
        <!-- TODO: Add Link to Cat Photos  -->
    ```

### Main element
- HTML5 has some elements that identify different content areas. These elements make your HTML easier to read and help with Search Engine Optimization (SEO) and accessibility.
- The `main` element is used to represent the main content of the body of an HTML document.
- Content inside the main element should be unique to the document and should not be repeated in other parts of the document.
```html
<main>
  <h1>Most important content of the document</h1>
  <p>Some more important content...</p>
</main>
```

##### Nesting & Indentation
- In the previous step, you put the `h1`, `h2`, comment, and `p` elements inside the main element. This is called `nesting`.
- Nested elements should be placed two spaces further to the right of the element they are nested in.

### Image Tag
- You can add images to your website by using the img element. img elements have an opening tag **without a closing tag**.
- An element without a closing tag is known as a `void element`.

```html
<img src="cat.jpg" alt="A cat">
```

### Anchor Tag
```html
<a href="https://www.freecodecamp.org">click here to go to freeCodeCamp.org</a>
```
- You can turn any text into a link, such as the text inside of a p element.
```
<p>See more <a href="https://freecatphotoapp.com">cat photos</a> in our gallery.</p>
```
- To open links in a new tab, you can use the `target` attribute on the anchor (a) element.
- The `target` attribute specifies where to open the linked document. `target="_blank"` opens the linked document in a new tab or window.
```
<p>See more <a href="https://freecatphotoapp.com" target="_blank">cat photos</a> in our gallery.</p>
```
- Other types of content (e.g. images) can also be turned into a link by wrapping it in anchor tags.

### Section Tag
- The `section` element is used to define sections in a document, such as chapters, headers, footers, or any other sections of the document. It is a semantic element that helps with SEO and accessibility.
```
<section>
  <h2>Section Title</h2>
  <p>Section content...</p>
</section>
```

### Unorder List (ul)
```html
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>
```

### Figure Element
The `figure` element represents self-contained content and will allow you to associate an image with a caption.

#### figcaption
A figure caption (figcaption) element is used to add a caption to describe the image contained within the figure element.
**Example Code**
```
<figure>
  <img src="image.jpg" alt="A description of the image">
  <figcaption>A cute cat</figcaption>
</figure>
```

#### `figure` vs `img`

### *em* Tag
To place emphasis on a specific word or phrase, you can use the `em` element.
- Basically it makes an text *Italic*

### **strong** Tag
The `strong` element is used to indicate that some text is of strong importance or urgent.
- Basically **Bold**


### ordered list (ol)
The code for an ordered list (ol) is similar to an unordered list, but list items in an ordered list are numbered when displayed.
```
<ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
</ol>
```

### Form 
The `form` element is used to get information from a user like their name, email, and other details.

#### Action attribute
The action attribute indicates where form data should be sent.

Here is an example of a form element with an action attribute:

**Example Code**
```
<form action="/submit-url"></form>
```
In the example, action="/submit-url" tells the browser that the form data should be sent to the path /submit-url.

#### Input
The input element allows you several ways to collect data from a web form. 
- Like img elements, input elements are a void element and do not need closing tags.

