---
layout: post
title: First round with Jekyll
---

**TL;DR** Jekyll : cheap and you'll save time in the long-long run. 

# Why use Jekyll?

Jekyll has the dual honors of being difficult to get started with and as a
static-website generator, also having pretty limited functionality. So why
bother?  While there are lots non-shallow reasons for going with
Jekyll, frankly a big part of it is social signalling. Jekyll is akin to vim,
linux and obscure indie bands in that, due to its inaccessibility, there is social
value in adopting it. Also open source cli apps always gives you the feeling
that you are the person in control and are THE BOSS, not conforming to what THE
MAN wants from you.

Here are some better reasons to use Jekyll.

* Free hosting! Github supports jekyll, so you don't have to worry about
  buying your own domain and all the trouble that goes with that. Just host
  your repo on github, push and voila, github will create a site for you.

* Easy managment of new content. For example to create a new blog post all I
  had to do was write it in markdown, put it in my posts folder and just git
  push to get it online. If I wanted to preview it before publishing, I can 
  use `jekyll serve` to see what the site would look like beforehand.

* Jekyll forces you to learn. I knew practically nothing about
  html/css/liquid/yaml before this, but by cloning [Micah Cowell's
  repo](https://github.com/getmicah) (He's the one who made this excellent
  theme), and by runnning `jekyll serve --watch`, I was able to make small
  modifications, see the changes immediately, and in the process, learn what
  each code snippet did.

* Static websites are fast and don't require much bandwith. This low cost, at
  the expense of interactivity, is the reason why github is ok with hosting
  them for free.

# Some gripes with Jekyll

For some reason the default theme did not work on my mac. So I spent a long and
frustrating time trying to track down what bug caused this. I never did find
it. Eventually I realized that every other theme I downloaded worked so I just
forgot about it. Pretty annoying when the **default** theme doesn't work
though. 

# You should use Jekyll if
<div id="shortlist">
<ul>

<li>You are a poor CS student who can't afford hosting.</li>

<li>Won't be seen dead using anything other than a cli tool.</li>

<li>Want to learn html/css etc, and want something decent looking as the end
product.</li>

<li>Want a blog you can update just by editing text files, not having to bother
going through any third-party site.</li>

<li>Like being able to see the internals of the tools you work with, and being
able to contribute to their development or modifying them.</li>

<li>Love <a href="https://daringfireball.net/projects/markdown/">
markdown</a></li>

</ul>
</div>

# You should stay away from Jekyll if
<div id="shortlist">
<ul>
<li>
A part of your soul dies everytime you touch the command line</li>
<li> You need <em>any</em> interaction with the user. </li>
</ul>
</div>
<br>

You can checkout jekyll [here](https://jekyllrb.com/) and Micah Cowell's site [here](https://micahcowell.com/). 
