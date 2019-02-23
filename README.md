# HTML tutorial

- What HTML is
- Structure of a HTML Document
- How to create webpage
- Text, links, lists and images
- Various other HTML tags
- Adding CSS to a webpage
- Adding JavaScript to a webpage

### 1. What is HTML?

HTML STANDS FOR: Hyper Text Markup Language

##### 3 Awesome Technologies

###### HTML

The structure of a web page

###### CSS

The styling of a web page

###### JavaScript

Making a web page interactive

##### HTML Tags

```html
<p> Paragraph text</p>
<a> Link to another page </a>
<h1> Headings </h1>
<blockquote> Quotes </blockquote>
<img>
```

##### HTML Syntax

HTML is a Markup Language We use tags <> to mark content up

- HTML uses tags <> </> to present content
- There are many different tags
- Tags can contain attributes <p class="myclass">
- Tags can be nested in other tags
- Tags are normally indented when nested for readability

### 2. HTML Basics

The Head and Body

##### Head and Body tags

- The <head> tag contains all the 'extra' information about a web page
    - Meta data
    - CSS & JavasScript references
- The <body> contains all visual content
    - Headings, images, paragraphs etc

##### Structuring Headings

- Heading tags range from h1 to h6

##### The img Tag

- '<img>'
- Specify where the image is stored using the 'src' attribute
- '<img src="image-source-path.jpg">'

##### HTML Links

###### The Anchor Tag

- '<a href="link-source">'
- Internal - links to pages in own website
- External - links to other websites
- Downloads - links to files
- Anchors - links to specific areas on a page

##### HTML Lists

###### Types of Lists

- Unordered list - '<ul> + <li>'
- Ordered list - '<ol> + <li>'
- Definition list - '<dl> + <dt> + <dd>'


##### The div tag

- div stands for 'division'
- Used to divide content into logical sections

##### ID's and Classes

- And ID is a UNIQUE identifier, used once on a page
    - E.g. header, about
- A Class is an identifier of an element which can be used multiple times on a page
    - E.g. Comment(when there are multiple comments)
- Both are used for JS and CSS

##### Adding CSS to HTML

###### 3 Ways to Add CSS

1. Inline styling using the style attribute
2. Within '<style>' tags in the *head* of the document
3. By linking up a stylesheet in the head

##### Adding JavaScript to HTML

###### How to Add JavaScript

1. In the '<script>' tag in the head or body
2. By linking a .js file in the head or body
3. Inline(not a good practise)