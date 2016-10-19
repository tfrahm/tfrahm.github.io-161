---
layout: page
title: Workshops
permalink: /workshops/
---

<h2>Learn to Code with UNC's Women in Computer Science!</h2>

<h3>Sitterson Hall: Wednesday, September 28 - 6:30 PM</h3>

Rating: <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star-o"></i>

In this introductory information session, we learned about several nifty little tools to make coding fun and interactive and
to build a foundation from which we can begin to explore and develop our IT skills on our own time. Here's a brief overview:

<img src="/images/pong_game.jpg" alt="Pong Game" style="width:466px;height:666px;" class="right">

<ol>
    <li>
    <h5><strong>Scratch</strong></h5>
    </li>

    First, we were taught how to use <a href="https://scratch.mit.edu/">Scratch</a> to play around with code snippets and quickly create a fun little pong game. 
    There's a screenshot of my work-in-progress over to the right! When the code was running, it behaved like a basic pong game: the bat would fly around the forest, and
    bounce off the edges of the screen. The user's mouse controlled the magic wand at the bottom, and the goal ws to tap the bat with the magic wand
    before it could fly into the orange zone. To create this, we learned how to string together different bits of code to make objects (or "sprites") behave
    in different ways. So for example, this code here makes the balloons 'pop' when the bat flies into them!:
<br/><br/>
<img src="/images/balloon_code.jpg" alt="This code makes the balloons 'pop' when the bat flies into them!" style="width:200px;height:133px;">
<br/><br/>
     Pretty neat.
   
    <li>
    <h5><strong>Coding Bat</strong></h5>
    </li>
    
    Next we took a quick look at <a href="http://codingbat.com/java">Coding Bat</a>, a free website of live coding problems which can help us build skills in Java and/or Python. 
    We didn't spend much time on this one, but I hope to take another look at it in my free time!
    
    <li>
    <h5><strong>Project Euler</strong></h5>
    </li>

    Lastly, they told us about how coding can be used to perform all kinds of fancy math, and took us to a website called <a href="https://projecteuler.net/">Project Euler</a>.
    This site is esentially a series of complex mathematical problems which can be solved with increasingly difficult levels of computer programming
    knowledge. We were all given the chance to create an account, and then worked together to solve the first problem. We wrote the code below (in C#) to find the 
    sum of all the multiples of 3 or 5 below 1000:
    <br/><br/>
   
    {% highlight C# %}
    int result = 0;
    for (int i = 1; i < 1000; i++) {
        if (((i % 3) == 0) || ((i % 5) == 0)) {
            result += i;
        }
    }
    {% endhighlight %}
    
    <br/>
   (Answer: 233168) 
  

</ol>