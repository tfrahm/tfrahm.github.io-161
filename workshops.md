---
layout: page
title: Workshops
permalink: /workshops/
---
<h2>RailsBridge Triangle Intro to Programming with Ruby on Rails!</h2>

<h3>Sitterson Hall: Friday, December 2, 6 - 9:00 PM & Saturday, December 3, 9:00 AM - 4:30 PM</h3>

Rating: <i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star-half-o"></i>

This workshop was hosted by the cool folks over at <a href="http://railsbridgetriangle.com/">RailsBridge Triangle</a>.
We began with a pizza party and installfest on Friday night (and yes, to my surprise it did actually take THREE HOURS to install all
of the necessary software), and then spent a full day Saturday at an introductory course to Ruby on Rails. We covered A LOT of stuff. Here's a brief overview:

**Installfest** - here's a list of all the cool stuff we installed and worked with: 

<img src="/images/terminal.PNG" alt="Terminal running Rails server" style="width:600px;height:600px;" class="right">
 
 - <a href="https://www.ruby-lang.org/en/">Ruby</a> - programming language
 - <a href="http://rubyonrails.org/">Rails</a> - framework for doing stuff with Ruby
 - <a href="https://git-scm.com/">Git</a> - version control system (Yay!)
 - <a href="https://github.com/">GitHub</a> - git repository hosting site 
 - <a href="https://dashboard.heroku.com/">Heroku</a> - application server
 - <a href="http://www.sublimetext.com/2">Sublime Text 2</a> - text editor
 - <a href="https://rubygems.org/">"Ruby gems"</a> - bits of code

**Intro to Rails**
 
To learn Rails, the code master people had us complete a practical project: we created a voting app, aka "suggestotron".
The app (when complete) allowed us to view and list topics, vote on the topics, create new topics, edit existing topics, and destroy topics.

Here's what my finished app looked like:

<img src="/images/tip-topics_app.PNG" alt="Tip-Topics App" style="width:410px;height300px;">

Along the way, we learned some basic Ruby syntax and web development tools (i.e. source control, editor, console, local servers). Check out my
nifty new terminal running a rails server up above!

This workshop covered SO MUCH STUFF and I'm sure I've already forgotten half of it. But I feel confident that (even if it takes time)
I *could* learn how to code with Ruby and I know that there's a super supportive community of nice coders out there willing to help me!

Similarly to 161, the workshop was set up so that we were able to work through the steps
independently, wiht TAs on standby whenever we had a question to ask. I really enjoyed this workshop, 
and found that a lot of the things I learned in 161 this semester were super applicable, which
made me feel awesome and knowledgeable compared to a lot of people. Free food and t-shirts are always a plus,as well!

My only critique is that it's the weekend before finals week, so I wasn't able to concentrate on the learning 
experience as fully as I would have wished. That said, it was tons of fun and I hope to attend some more similar workshops
in the future!

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Me: &quot;I love git.&quot;<a href="https://twitter.com/nclikenc">@nclikenc</a>: &quot;Why don&#39;t you marry it?&quot;<br>Me: &quot;I just can&#39;t commit.&quot;<a href="https://twitter.com/hashtag/RBTworkshop2016?src=hash">#RBTworkshop2016</a></p>&mdash; Tabitha Frahm (@TabithaFrahm) <a href="https://twitter.com/TabithaFrahm/status/805130375991357441">December 3, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

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