---
layout: default
title: HOW TO
author: BCNGeeks
date: 21th June 2022
---


# HOW TO

## Table of Contents

- [HOW TO](#how-to)
  - [Table of Contents](#table-of-contents)
  - [Getting started with HTML](#getting-started-with-html)
    - [The anatomy of an element](#the-anatomy-of-an-element)
    - [An exemple](#an-exemple)
    - [Nesting elements](#nesting-elements)
    - [Comments](#comments)

## Getting started with HTML

### The anatomy of an element

- The opening tag: This consists of the name of the element (in this example, p for paragraph), wrapped in opening and closing angle brackets. This opening tag marks where the element begins or starts to take effect. In this example, it precedes the start of the paragraph text.
- The content: This is the content of the element. In this example, it is the paragraph text.
- The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This marks where the element ends. Failing to include a closing tag is a common beginner error that can produce peculiar results.

<!-- end of the list -->

### An exemple

    <!DOCTYPE html>
    <html>
    <head>
    <title>Page Title</title>
    </head>
    <body>

    <h1>My First Heading</h1>
    <p>My first paragraph.</p>

    </body>
    </html>

What's mean's the tags?

- The `<!DOCTYPE html>` declaration defines that this document is an HTML5 document.
- The `<html>` element is the root element of an HTML page.
- The `<head>` element contains meta information about the HTML page.
- The `<title>` element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab).
- The `<body>` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
- The `<h1>` element defines a large heading.
- The `<p>` element defines a paragraph.

<!-- end of the list -->
---
### Nesting elements

Elements can be placed within other elements. This is called nesting. If we wanted to state that our cat is very grumpy, we could wrap the word very in a `<strong>` element, which means that the word is to have stronger text formatting:

    <p>My cat is <strong>very</strong> grumpy.</p>
You will get this:
<p>My cat is <strong>very</strong> grumpy.</p>

There is a right and wrong way to do nesting. In the example above, we opened the p element first, then opened the strong element. For proper nesting, we should close the strong element first, before closing the p.

The following is an example of the wrong way to do nesting:

    <p>My cat is <strong>very grumpy.</p></strong>

 You will get this: <p>My cat is <strong>very grumpy.</p></strong>

The tags have to open and close in a way that they are inside or outside one another. With the kind of overlap in the example above, the browser has to guess at your intent. This kind of guessing can result in unexpected results.

---

### Comments

HTML has a mechanism to write comments in the code. Browsers ignore comments, effectively making comments invisible to the user. The purpose of comments is to allow you to include notes in the code to explain your logic or coding. This is very useful if you return to a code base after being away for long enough that you don't completely remember it. Likewise, comments are invaluable as different people are making changes and updates.

EX:

    <!-- Here you can write what you want to comment -->
