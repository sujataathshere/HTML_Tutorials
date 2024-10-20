### What is the role of DOCTYPE in HTML ?
- DOCTYPE(Document Type) declaration specifies the version of HTML.
- DOCTYPE tells the browser which version of HTML it is & how to interpret the code.
- `<!DOCTYPE html>` HTML5 verion
- `<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "...">` HTML4 verion
- `<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "...">` HTML1 verion

### What are Meta Tags? What are the 5 types of meta tags?
- Meta tags in HTML are elements used to provide metadata or additional information about a web page.
- 5 Types of Meta Tags
    1. charset
    2. viewport
    3. description
    4. keywords
    5. author
1. Character Encoding
- This helps browsers to interpret the different characters in the document.
- The charset="UTF-8" attribute ensures that characters from different languages will be displayed correctly in the browser.
2. Responsive Design
- Viewport meta tag is crucial for creating mobile-friendly, responsive web designs for various screen sizes.
3. Description for SEO
- This meta tag provides description of the content of the page.
- Search engines may use this for search results.
4. Keywords for SEO
- This meta tag used to be important for search engines, but it's now less importance.
5. Author Infor
- This meta tag can be used to specify the author of the document.

### What is the difference between <div> & <span> element?
1. `<div>` Element
- It is a block-level element
- The `<div>`(division) element HTML is a container that is used to group & structure the content on a webpage.

2. `<span>` Element
- It is inline element
- The `<span>` element in HTML is an inline container used to apply styles or scripting to a specific section of text or content.
- `<p>Hello <span style="color:blue">World !!!</span></p>`

### What are the differences between Block-Level & Inline Elements ?
1. Block-Level Element
- It create "blocks" of content.
- By default it starts on a new line.
    `<p>Block level element</p>`
- You can set both width & height for block level elements
- Eg. `<div>, <p>, <h1>, <ul>, <li>, <tabke>, <form>, etc.`

2. Inline Element
- It's length depends on their content length.
- It do not start on a new line.
    `<p>Inline <strong>Element</strong></p>`
- You can't set width & height for inline elements.
- Eg. `<span>, <a>, <strong>, <em>, <img>, <input>, <br>, etc.`

### What are Semantic Elements in HTML? Is div a semantic element?
- Semantic elements in HTML are elements that provide meaning to the content they contain.
- Top 5 Semantic elements
    1. `<header>`
    2. `<main>`
    3. `<section>`
    4. `<footer>`
    5. `<address>`
- `<div>` is not a semantic element, bcoz div is a general-purpose structural element. It doesn't give any meaning to the content.
- `<progress>` It displays the progress of a task.
- `<nav>` It contains navigation links for a webpage.
- `<time>` It represents a specific period in time or a date.
- `<mark>` It highlights parts of the text for refence or emphasis.
- `<summary>` It provides a summary, caption, or legend for a `<details>` element.
- `<meter>` It represents a scalar measurement within a known range (like a gauge).
- `<figure>` It contains content like images, illustrations, diagrams, etc., along with a caption.
- `<details>` It represents additional information or controls that can be toggled open or closed.
- `<aside>` It contains content that is related to the main content but can be considered separate.
- `<article>` It represents a self-contained composition in a document, such as a blog post or a news article.

### What is the diff bet Absolute & Relative URLs ?
1. Absolute URLs
- It provide the complete web address of a resource.
- It typically used to link to resources on diff websites.

2. Relative URLs
- It specify the location of a resource in relation to the current document. Full url is not required.
- They are used when linking to resources within the same website.

### What are HTML Forms & what are its advantages ?
- `<form>...</form>` form tag
- Login form, Registration form, feedback form, etc. every form has one common things that Fill & Submit.

### What are HTML Form Elements & their Main Attributes ?
1. Form Element `<form>`
- It is the container of form elements.
2. Action Attribute
- It specifies the URL where the form data will be sent when it submitted.
3. Method Attribute
- It defines the HTTp method to be used when sending the form data.
4. Label Element `<label>`
- It is used to provide a label or description for an input field.
5. For Attribute
- It associate the label with a specific input field.
6. Input Element `<input>`
- It is used to create controls.
7. Type Attribute
- It specifies the type of input field.
8. Name Attribute
- It is used to define a name for the input field.

### What is SEO? What are 5 HTML Best Practices for SEO?
- SEO(Search Engine Optimization) is the practice of optimizing a website to improve its visibility & ranking in search engine results.
- 5 HTML Best Practices for SEO
1. Use Semantice HTML Elements 
- `<header> <main> <section> <footer> <address>`
2. Optimize Page Titles
- Use descriptive & very relevant title for your page
- It should be in a 1 line
3. Use Meta Description Tags
- Add a very consise & meta description
- Add a summary of the page content
- It should be in a 2/3 lines
4. Use Proper Heading Tags
- Make sure headings are relevant to the content 
5. Optimize Image Alt Attributes
- Use descriptive alt attributes so your images i aslo used for searched

### What is Responsive Design ?
- Responsive Design is a practice of creating web pages that adapt & display well on various devices & screen sizes.

# What is HTML ?
- It is the standard text formatting language used for creating & displaying pages on the internet

2. What are HTML tags ?
- HTML tags are used for placing the elements in the proper & appropriate format.
- The HTML tags need not be closed always
- Eg. `<html>, <img>, <head>, <table>, etc.`

3. What are HTML Attributes ?
- Attributes are the properties that can be added to an HTML tag that change the way the tag behaves or is displayed
- Attributes are added right after the name of the HTML tag, inside the brackets
- Eg. src, alt, height, weidth, etc. `<img src="">`

4. What is a Marquee in HTML ?
- For scrolling the text on the webpage, marquee is used
- It scrolls the images or text up, down, left, or right automatically
- Eg. `<marquee>`

5. How do you separate a section of texts in HTML ?
- `<br>` Tag -> It is used tto separate the line of text. It breaks the current line & shifts the flow of the text to a new line.
- `<p>` Tag -> It is used to write a paragraph of text.
- `<blockquote>` Tag -> It is used to define large quoted sections.

6. Define the list types in HTML ?
1. Ordered List
- It uses `<ol>` tag & each element of the list is written between `<li></li>` tags
- It displays elements in numbers, alphabets & roman format.
2. Unordered List
- It uses `<ul>` tag & each element of the list is written between `<li></li>` tags
- It displays elements in bullet, square format
3. Definition list
- It uses `<dl>, <dt>, <dd>` tags & displays elements in definition form like in a dictionary

7. How do you display a table in an HTML webpage?
- The HTML `<table>` tag is used to display data in a tabular format
- It is also used to manage the layout of the page, eg. header section, navigation bar, body content, footer section.
- `<table>, <tr>, <th>, <td>, <tbody>, <thead>, <tfooter>, etc.`

8. Why do we use a style sheet in HTML ?
- A style sheet helps in creating a well-defined template for an HTML webpage that is both consistent as wll as portable
- A single style sheet template can be linked to various web pages, which makes it easier to maintain & change the look of the website

9. 