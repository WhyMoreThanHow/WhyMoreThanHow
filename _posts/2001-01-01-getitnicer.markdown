---
layout: post
title:  "Get nicer top"
date:   2001-01-01 00:00:01 +0000
categories: jekyll update
---
![image](/images/PembsHills.gif)

[link to further down My Great Heading](#custom-id)

`YYYY-MM-DD-title.MARKUP`
#  One  
## Two
### Three etc
Before <br> 
after **bold** *itallic*
---

<big> direct HTML - permitted?</big>
<p align="center">centered content</p>
Can also <small> do small text </small> like this.

<div id="named"> Is this allowed?  By Jeyll?</div>
<div> <blink> test this</blink></div>

<p style="color:red;">A red paragraph.</p>
<p style="background-color:cyan; color:black">Another paragraph.</p>

    testindent - this appears as a blockquote without sidebar in PC

&nbsp; &nbsp; &nbsp; another indent attempt using multiple ampersand nbsp



<p>Please press <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>R</kbd> to re-render an MDN page.</p>
<label for="fuel">Fuel level:</label>

<meter id="fuel"
       min="0" max="100"
       low="33" high="66" optimum="80"
       value="50">
    at 50/100
</meter>
---

<!--- This is an HTML comment in Markdown -->

---

[//]: # (a workaround style for a comment in markdown)
 
---

[title](https://www.example.com)

![alt text](/NonProcessed/WhyMoreThanHow85x60.png)

>a blockqute
>
1. list
2. ordered

- unordered
- list

|ROW HEAD1 |HEAD2|
|---|---|
|TABLE ENTRY1|TABLE ENTRY2|


```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
Here's a sentence with a footnote. [^1]

a
z

[Can you go back to named id?](#named)
### My Great Heading {#custom-id}
term
: definition

~~The world is flat.~~

[^1]: This is the footnote.

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

<!---This comment will be visible in HTML source but ignored by the HTML parser-->
[//]:#(this comment should be ignored by markddown processor and will not appear in HTML source. It is a workaround)