---
layout: post
title:  "Time Travel & Transfiguration"
date:   2016-10-24 12:00:00
categories: INLS161
author: "Tabitha"
---
#### **Assignment 3 (or Transfiguration 101):**

<img src="/images/wand.png" border="0" alt="magic wand" style="width:250px;height:375px" class ="right">

For this assignment, I wrote a script to convert an essay that I wrote from .md to HTML, DOCX, ODT, and PDF.

<!--- A brief description (abstract) of your written work -->
The essay is titled: *Why Heracliteans Cannot Travel to the Past*, and is a paper I wrote for my undergraduate Metaphysics course while attending NCSU. 
It discusses the logical paradoxes involved in past-time travel, based on a Heraclitean metaphysical conception of time.

<!--- A description of what you did to get it into multiple formats -->
I "transfigured" the document from markdown to other formats with pandoc using some fancy code!

For example, this will convert my document from .md to PDF: `pandoc -o time-travel.pdf time-travel.md`. 

`pandoc` is the file converter. 

`-o` specifies the output. 

Pandoc has the ability convert to and from loads of different file-types!

<!--- A list of the files in your blog post. Link these! -->
Here is a list of links to all the different files I created:

* <a href="https://github.com/inls161/assignment-3-tfrahm/blob/master/time-travel.md">time-travel.md</a>
* <a href="https://github.com/inls161/assignment-3-tfrahm/blob/master/time-travel.html">time-travel.html</a>
* <a href="https://github.com/inls161/assignment-3-tfrahm/blob/master/time-travel.docx">time-travel.docx</a>
* <a href="https://github.com/inls161/assignment-3-tfrahm/blob/master/time-travel.odt">time-travel.odt</a>
* <a href="https://github.com/inls161/assignment-3-tfrahm/blob/master/time-travel.pdf">time-travel.pdf</a>

<!--- Links to all of your source and output files, and your script on Github. -->
Already super cool. But to make the process even simpler, I wrote the code into a script that can do all of these conversions at once - <span class="spark" font-size="12px">just like magic!</span>

Here's a link to my script on Github: 
<a href="https://github.com/inls161/assignment-3-tfrahm/blob/master/tfrahm-convert-docs.sh">
ABRACADABRA!
</a>

And here's a link to my Cloud9 Editor: 
<a href="https://ide.c9.io/tfrahm/assignment-3">
ALAKAZAM!
</a>

Go check it out!

<!--- Share your Cloud9 workspace with me and place a link to your Editor in the post. 
<!--- I should be able to run your script so you need to give me read-write permissions. -->

<br/>

<!--- Reflections on any challenges you encountered, 'aha' moments you had, etc. -->
**Reflection:**

At first, using pandoc seemed overwhelming - simply because I've never used anything like it before.
However, the more I worked with it the more I found that it is actually pretty intuitive.

A difficult part of this assignment for me was actually working with Markdown. I tend to throw formatting 
on my documents like rainbow sprinkles on an ice cream cone. 
Markdown demands much simpler formatting, which was difficult to adjust to at first - but I think 
it could actually make me a much more efficient writer since
I won't waste so much time getting distracted by fonts and spacing and pretty colors.

My favorite part of this assignment, though, was the scripting. Writing my script, 
I felt like Tom Riddle creating his magical-horcrux-diary. I think I've gained a lot of insight into how computer
programs work and how it is they interact with users. As Rowling says,
"Never trust anything that can think for itself if you can't see where it keeps its brain."

I really enjoyed learning how to make the terminal spit out fancy colors, but the greatest
challenge I faced while writing my script was creating an if/else statement to remove the file extension (if needed) from `$OUTPUT`.

How do you cast a spell when you don't know the words? Consult other wizards, that's how! I spent a LOT of time reading through
<a href="http://stackoverflow.com/">Stack Overflow</a> to figure this one out. (Thanks, fam.) 