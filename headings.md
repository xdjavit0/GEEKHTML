---
layout: default
title: Markdown Guidelines
author: BCNGeeks
date: 21th June 2022
---

# HTML FORMATTING

## TABLE OF CONTENTS

- [HTML FORMATTING](#html-formatting)
  - [TABLE OF CONTENTS](#table-of-contents)
  - [FORMATTING INTRODUCTION](#formatting-introduction)
  - [HEADINGS](#headings)
    - [EXAMPLE](#example)
    - [IMPORTANCE OF HEADINGS](#importance-of-headings)
  - [PARAGRAPHS](#paragraphs)
    - [EXAMPLE](#example-1)
    - [DISPLAY](#display)
      - [EXAMPLE](#example-2)
  - [LINE BREAKS](#line-breaks)
    - [EXAMPLE](#example-3)

---

## FORMATTING INTRODUCTION

HTML Formatting is a process of formatting text for better look and feel. HTML provides us ability to format text without using CSS. There are many formatting tags in HTML. These tags are used to make text bold, italicized, or underlined.

---

## HEADINGS

A HTML heading or HTML h tag can be defined as a title or a subtitle which you want to display on the webpage. When you place the text within the heading tags `<h1>`.........`</h1>`, it is displayed on the browser in the bold format and size of the text depends on the number of heading.

There are six different HTML headings which are defined with the `<h1>` to `<h6>` tags, from highest level h1 (main heading) to the least level h6 (least important heading).

`<h1>` is the largest heading tag and h6 is the smallest one. So `<h1>` is used for most important heading and `<h6>` is used for least important.

### EXAMPLE

    <h1>Heading 1</h1>

    <h2>Heading 2</h2>

    <h3>Heading 3</h3>

    <h4>Heading 4</h4>

    <h5>Heading 5</h5>

    <h6>Heading 6</h6>

Here we are showing how to the heading tag works.

### IMPORTANCE OF HEADINGS

Search engines use the headings to index the structure and content of your web pages.
Users often skim a page by its headings.

It is important to use headings to show the document structure.
`<h1>` headings should be used for main headings, followed by `<h2>` headings, then the less important `<h3>`, and so on.

---

## PARAGRAPHS

The HTML `<p>` element defines a paragraph.

A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.

### EXAMPLE

    <p>This is a paragraph.</p>
    <p>This is another paragraph.</p>
Here, we are using de `<p>` tag to create 2 different paragraphs.

### DISPLAY

You cannot be sure how HTML will be displayed.
LarGe or small screens, and resized windows will create different results.

With HTML, you cannot change the display by adding extra spaces or extra lines in your HTML code.
The browser will automatically remove any extra spaces and lines when the page is displayed:

#### EXAMPLE

    <p>
    This paragraph
    contains         a lot of spaces
    in the source         code,
    but the        browser
    ignores it.
    </p>
In this example, we are showing that even if you write everything inside the tag with spaces, the display is gonna be a simple paragraph without the added spaces.

---

## LINE BREAKS

The HTML `<br>` element defines a line break.

Use `<br>` if you want a line break (a new line) without starting a new paragraph.
This tag is empty, which means that it has no end tag.

### EXAMPLE

    This is <br> a sentence <br> with line breaks

In this example we are showing how the tag `<br>` works and that the output is gonna be like this:

This is <br> a sentence <br> with line breaks.

---

