Welcome to the journey of Software Development

HTML Topics
1. HTML Basics:
. What is HTMl?
HTML stands for HyperText Markup Language. It is the standard markup language used to define the structure and content of web pages.HTML uses a system of tags and elements (such as headings, paragraphs, links, images, and forms) to tell web browsers how content should be organized and displayed. When a browser loads a web page, it reads the HTML code and parses it into a Document Object Model (DOM) to render the visual page you see on screen.

. Define HTML Structure
<!-- HTML Structure -->

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width='device-width', initial-scale=1.0">
    <meta name="Learn hub" content="HTML Tutorials">
    <meta name="hub:description" content="HTML Tutorials">
    <meta image="hub:image" content="HTML Tutorials">
    <title>Learn Hub</title>
</head>

<body>

</body>



<!DOCTYPE html>: The declaration that informs the browser this is an HTML5 document.
<html lang="en">: The root element that wraps all the code on the page.
<head>: The container for metadata (data about the page) that is not directly visible to the user—such as the page title, character encoding, SEO tags, and links to stylesheets.
<body>: The container for all visible content that users see and interact with—such as headings, text, images, buttons, forms, and navigation bars.

2. Text Elements

.Headings:

Headings provide an organized document outline for both users and machines. Browsers apply default styling (larger font sizes and bold weights) based on the heading level:
<h1>: Main page title or primary topic (highest importance).
<h2>: Major section headings.
<h3>: Sub-sections under an <h2>.
<h4> to <h6>: Further subdivisions of content (used less frequently).

. Paragraphs

The <p> tag in HTML defines a paragraph. It is a block-level element used to represent a distinct block of text. 

. Line Breaks

The <br> tag in HTML produces a line break within text.

The <hr> tag is for semantic thematic breaks/topic shifts, rendered as a horizontal divider.

. Bold & Italic tag

Bold <b> and Italic <i> are just visual styling tags with no added importance. <b> tag make content bold and <i> tag makes text italicized.

3. Attributes 
HTML attributes are special modifier keywords placed inside an element's opening tag that provide additional configuration, behavior, styling, or metadata.

. id 
Unique identifier for a single element on the page.

. Class
Reusable identifier to group multiple elements.

. Style
Inline CSS styling applied directly to the element.

.title
Advisory text displayed as a native hover tooltip.

4. Links

. anchor tag
In HTML, the <a> (anchor) tag is used to create hyperlinks. It transforms text or elements into clickable links.

. Internal Links 
Link between pages on your own site (e.g., href="/about-us.html").
. External Links
External Links: Point outside of your website to absolute URLs (e.g., https://google.com).
. open link in new tab
By default, the browser opens the link in the current window. Using the target="_blank" attribute forces the browser to open the link in a completely new tab.

5. Images

. img tag
In HTML, the <img> tag is used to embed an external image directly into a webpage.
. src & alt attributes
The src (Source) to locate the image file, and alt (Alternative Text) for accessibility and fallback scenarios.
src (Source): Contains the URL or relative file path pointing to the image file (e.g., .jpg, .png, .svg, .webp, .gif).
alt (Alternative Text): Provides a text description of the image.
. Image size
HTML allows you to set the image dimensions directly using width and height attributes.

6. Lists
Lists in HTML are block-level structural elements used to group related items together.
. Ordered List: <ol>
Groups items where the sequence matters (renders with sequential numbers or letters).
. Unordered List: <ul>
Groups items where the sequence does not matter (renders with bullet points).
. Nested List:
A nested list means a list inside another list, and the inner/outer lists can be either <ol> or <ul>.

7. Tables 
. table 
In HTML, the <table> element is used to display structured, multi-dimensional spreadsheet-like data (rows and columns).
. tr, td, th
Inside the table, <tr> defines a row, <th> defines a header cell, and <td> defines a standard data cell.

8. Form
. form
An HTML Form is a container (<form>) used to collect user input and submit it to a server or process it using JavaScript. It holds various interactive controls—such as text fields, dropdowns, text areas, checkboxes, and buttons—allowing users to enter data like credentials, profile info, or feedback.
. input Types
Single-line user input field
Uses the type attribute (text, email, password, checkbox, radio, file, number, etc.) to define behavior.
. textarea
Multi-line text entry field
Unlike <input>, it requires a closing tag (</textarea>) and can expand for long text (e.g., code snippets, bios).
. select & option
Dropdown selection menu
<select> creates the dropdown container; <option> tags define each selectable choice.
. button
Clickable action control
Default behavior inside a form is type="submit". Can also be type="button" (for JS actions) or type="reset".
. label
Captions an input element
Connects to an input via for="input_id" to boost accessibility and click area.
. required attribute
Client-side validation flag
A boolean attribute that stops form submission if the field is left empty.



9. Div & Spann
. div
block-level container used to group larger structural elements.
. span  
An inline-level container used to style or isolate smaller inline text or content.


In HTML, every element has a default display behavior that dictates how it interacts with surrounding content in the document flow:

Block Elements: Always start on a new line and stretch to occupy the full width of their parent container.
Inline Elements: Stay on the same line (flowing inside text) and only take up as much width as their content requires.


10. HTML 5 Basics
. Semantic tag
<header></header>
Introductory content. Typically contains the site logo, site title, or a container for the top navigation.
<nav></nav>
Navigational links. Used for main site menus or important table-of-contents lists.
<main></main>
The primary, unique content of the page. (Rule: A document must not have more than one <main> visible at a time.)
<article></article>
A self-contained, independent piece of content that could theoretically be syndicated on its own (e.g., a blog post, a news story, a forum comment).
<section></section>
A thematic grouping of content, usually identifiable by a distinct heading (<h2>). Think of it like chapters in a book.
<footer></footer>
losing metadata for its nearest section or the whole page. Usually contains copyright info, legal links, or author details.

. Audio & Video
HTML5 provides native playback capabilities standardizing media across the web.
. iframe
An <iframe> creates a mini-browser window inside your page to embed external URLs securely. Commonly used for embedding YouTube videos, Google Maps, or third-party payment widgets.
. Canvas Basics
The <canvas> element is a blank rectangular area on the screen. By itself, it does nothing. It relies entirely on a JavaScript API (like the Canvas 2D API or WebGL) to draw pixels, render charts, build web games, or manipulate images frame-by-frame.

SEO Basics
. title Tag
Defines the primary headline of the page shown in search engine results and browser tabs.
. meta description
Provides a concise summary snippet displayed beneath the title on search results pages.
. semantic structure
Organizes content logically using meaningful tags (<h1>–<h6>, <main>, <article>), helping search bots understand topic hierarchy and relevance.