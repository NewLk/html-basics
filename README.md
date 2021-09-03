# HTML Basics
HTML (HyperText Markup Language) is the most basic building block of the Web. It defines the meaning and structure of web content.

HTML uses "markup" to annotate text, images, and other content for display in a Web browser. HTML markup includes special "elements" such as `<head>`, `<title>`, `<body>`, `<header>`, `<footer>`, `<article>`, `<section>`, `<p>`, `<div>`, `<span>`, `<img>`, `<aside>`, `<audio>`, `<canvas>`, `<datalist>`, `<details>`, `<embed>`, `<nav>`, `<output>`, `<progress>`, `<video>`, `<ul>`, `<ol>`, `<li>` and many others.

## Tags
An HTML element is set off from other text in a document by "tags", which consist of the element name surrounded by "<" and ">". The name of an element inside a tag is case insensitive. That is, it can be written in uppercase, lowercase, or a mixture. For example, the `<title>` tag can be written as `<Title>`, `<TITLE>`, or in any other way.

## How to properly structure a page in HTML
When we first built our index page (code version available on the branch my_first_tags), this is how the code in it looked like:

    <h1>Welcome To My Website</h1>
    <p>This is my very first website</p>

Althogh, the correct structure for an HTML page would be:

    <!DOCTYPE html>
    <html>
        <head>
            <title>Title of the document</title>
        </head>

        <body>
            <h1>Welcome To My Website</h1>
            <p>This is my very first website</p>
        </body>
    
    </html>

Since you can still visualize your webpage on your browser the same way you formatted it when you don't use this structure, it seems pretty much unnecessary. Because of that, this is a question that came to my mind:

**is it necessary to write HEAD, BODY, and HTML tags?**

Fortunately, I found a very good answer on [StackOverflow](https://stackoverflow.com/questions/5641997/is-it-necessary-to-write-head-body-and-html-tags "Go to the discusion").

### HTML <!DOCTYPE> Declaration

The `<!DOCTYPE html>` declaration is used to inform a website visitor's browser that the document being rendered is an HTML document. While not actually an HTML element itself, every HTML document should being with a DOCTYPE declaration to be compliant with HTML standards.

[Read more on the subject](https://html.com/tags/doctype/#ixzz75LvhlpOp "HTML.com")

### HTML `<html>` Tag

The `<html>` tag represents the root of an HTML document.

The `<html>` tag is the container for all other HTML elements (except for the <!DOCTYPE> tag).

**Note**: You should always include the lang attribute inside the `<html>` tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

### HTML `<head>` Tag

The `<head>` element is a container for metadata (data about data) and is placed between the `<html>` tag and the `<body>` tag.

Metadata is data about the HTML document. Metadata is not displayed.

Metadata typically define the document title, character set, styles, scripts, and other meta information.

The following elements can go inside the `<head>` element:

- [<title>](https://www.w3schools.com/tags/tag_title.asp "W3Schools") (required in every HTML document)
- `<style>`
- `<base>`
- `<link>`
- `<meta>`
- `<script>`
- `<noscript>`

### HTML `<body>` Tag

The `<body>` tag defines the document's body.

The `<body>` element contains all the contents of an HTML document, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.

Note: There can only be one `<body>` element in an HTML document.

## References
- [Modern HTML & CSS From The Beginning (Including Sass)](https://www.udemy.com/share/1013eA3@DWujVyuW9i5f-Dd9vFBhD86NyAiX2TpDEJvqmdQPdTj_DEH0dJGaMbm1QgGJVd4JvA==/ "Udemy Course") - A paid course on [Udemy](https://www.udemy.com/)
- [DevDocs](https://devdocs.io/html/ "Go to the website") - A website that combines multiple API documentations in a fast, organized, and searchable interface
- [HTML.com](https://html.com/ "Go to the website") - HTML.com helps web developers of all stripes and skill levels craft the best HTML and CSS possible