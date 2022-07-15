- [1. Code Institute 5 Day Coding Challenge Day 1](#1-code-institute-5-day-coding-challenge-day-1)
  - [1.1. Challenge Overview](#11-challenge-overview)
    - [1.1.1. WHAT IS IT?](#111-what-is-it)
    - [1.1.2. WHAT DOES IT DO?](#112-what-does-it-do)
    - [1.1.3. HOW DO YOU USE IT?](#113-how-do-you-use-it)
    - [1.1.4. The three pillars of web development](#114-the-three-pillars-of-web-development)
      - [1.1.4.1. HTML](#1141-html)
      - [1.1.4.2. CSS](#1142-css)
    - [1.1.5. JavaScript](#115-javascript)
  - [1.2. HTML Overview](#12-html-overview)
    - [1.2.1. WHAT IS IT?](#121-what-is-it)
    - [1.2.2. WHAT DOES IT DO?](#122-what-does-it-do)
    - [1.2.3. HOW DO YOU USE IT?](#123-how-do-you-use-it)
    - [1.2.4. HTML Elements](#124-html-elements)
    - [1.2.5. Required HTML Elements](#125-required-html-elements)
  - [1.3. Using the Challenge Editor](#13-using-the-challenge-editor)
    - [1.3.1. WHAT IS IT?](#131-what-is-it)
    - [1.3.2. WHAT DOES IT DO?](#132-what-does-it-do)
    - [1.3.3. HOW DO YOU USE IT?](#133-how-do-you-use-it)
    - [1.3.4. Its nothing exciting](#134-its-nothing-exciting)
  - [1.4. Submitting Your Work](#14-submitting-your-work)
  - [1.5. Common HTML Elements](#15-common-html-elements)
    - [1.5.1. WHAT IS IT?](#151-what-is-it)
    - [1.5.2. WHAT DOES IT DO?](#152-what-does-it-do)
    - [1.5.3. WHEN DO YOU USE IT?](#153-when-do-you-use-it)

# 1. Code Institute 5 Day Coding Challenge Day 1

## 1.1. Challenge Overview
<br>

### 1.1.1. WHAT IS IT?
Challenge introduction

### 1.1.2. WHAT DOES IT DO?
Provides you with an overview of the languages, tools and project to be covered

### 1.1.3. HOW DO YOU USE IT?
Use it to give you an understanding of what to expect during the challenge

### 1.1.4. The three pillars of web development

#### 1.1.4.1. HTML
Html provides the content and structure to web applications

#### 1.1.4.2. CSS
CSS provides styling to the HTML changing how the HTML is displayed

### 1.1.5. JavaScript
Java Script provides the Logic and interactivity of the web app

## 1.2. HTML Overview

### 1.2.1. WHAT IS IT?
The Hypertext Markup Language (HTML)

### 1.2.2. WHAT DOES IT DO?
Forms the basis of nearly all Web content

### 1.2.3. HOW DO YOU USE IT?
Use HTML to format, arrange and display Web content

### 1.2.4. HTML Elements
Html uses Elements to define the structure of a website, some example of elements are
- Header
- Bold
- Table
- List
- Paragraph

Below is an example of a html element, it consists of
1. Opening Tag
2. The Content
3. Closing Tag

``` HTML
<h1>Heading</h1>
```

What happening?
1. Browser reads document
2. Browser find an opening tag h1
3. Browser prints all characters after the h1 with the h1 style
4. Browser finds closing tag h1
5. Browser stops printing in h1 style

HTML elements can contain other elements

```html
<p>
A Paragraph
<em> with emphasis </em>
</p>
```

In the example above the <p> element contains the <em> element or to put it another way the <em> element is a child of the <p> element. This is know as a nested relationship

### 1.2.5. Required HTML Elements

All html documents require three elements, these are:

- <html> this is the root node for the entire document all other elements are a child to this element.
- <head> this element contains supporting information for example the heading used in the browser tab
- <body> this element contain the actual content of what gets displayed on the screen

```html
<html>
    <head>
    </head>
    <body>
    </body>
</html>
```

## 1.3. Using the Challenge Editor

### 1.3.1. WHAT IS IT?
A web based integrated code editor that we will use for our code challenges

### 1.3.2. WHAT DOES IT DO?
An excellent tool that allows you to write solution code for challenges.

### 1.3.3. HOW DO YOU USE IT?
You will write, run, test and submit code in the challenge editor throughout the challenge series.

### 1.3.4. Its nothing exciting 

## 1.4. Submitting Your Work

- Click this test code until code passes then submit
- Do not submit code until all tests are passed otherwise your fail the challenge.

## 1.5. Common HTML Elements

### 1.5.1. WHAT IS IT?
The elements used to structure content

### 1.5.2. WHAT DOES IT DO?
The elements act as instructions to the browser as to how to display content.

### 1.5.3. WHEN DO YOU USE IT?
Whenever you want to create Web based content

``` html
<html>, <head>, <body> elements can only be used once in a page
```
``` html
<p> prints a space below to
```

``` html
there are 6 heading elements <h1> -> <h6>
```

``` html
<p> & <h1> are block elements
```

``` html
<em> is and inline element
```

elements can use attributes

``` html
<a href="www.google.com">Google</a>
```

``` html
<img src="" alt="" />
```

``` html
<ul> unordered list uses bullet points
```

``` html
<ol> ordered list are a sequential list using numbers
```

``` html
<div> <span> are used to organize the structure of the document but are semantically neutral so do not actually apply any styles by default to the content within them
```
