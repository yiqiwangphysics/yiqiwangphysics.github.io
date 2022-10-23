---
layout: post
title:  How to build a personal website
date:   2022-08-08 16:40:16
description: Guide to build personal website with no SWE experience
tags: random
categories: skill tool
---


I decided to build my personal website a week ago and did some research on different options for people who do not have SWE expertise with lots of HTML coding experience.
Here are a few options I found be approachable:
#### Website Options
<ul>
  <li>Google site: Free but less customizable.</li>
  <li>Commercial: easy graphical interface, lots of useful modules and templates, but not free if you want to connect to your own domain, like Wix, or WordPress.</li>
  <li>GitHub Page: Free and plenty of open source templates, slightly challenging as you need some basic HTML knowledge.</li>
</ul>
Feel it would be fun to learn something new and more comfortable building new architecture from the base, as you may notice on the website footer, I chose the last.

#### More Steps
Starting with an existing template is always a shortcut. [Github topics](https://github.com/topics/personal-website) provide several clean and concise open-source templates. And you could also find templates from others' GitHub page if they make theirs public. They also come with detailed README files or articles or even videos to guide you through how to use the template. Follow the instructions, and you are all set!

#### Tips
Here I will share some issues I have encountered and some tools/websites I find to be useful:

- To compile and run the website locally, you have to configure your packages correctly. For instance, this template requires installed Ruby and Bundler. For macOS users, you should check your installed Ruby by `ruby -v` and `which ruby` in your terminal. Please not use the system Ruby for [the following reasons](https://www.freecodecamp.org/news/do-not-use-mac-system-ruby-do-this-instead/). A version manager helps if you're juggling multiple projects and can't update all at once. For a guide that compares version managers and shows the best way to install Ruby, please check [this article](https://mac.install.guide/ruby/index.html). Ah Ha, now you are ready to compile your website locally and make changes in files and see its effect in no time! :smiley:
- Like your website, [Atom](https://atom.io) is a good app to use to manage a project. You could keep tracking all changes you staged and all changes you commit to master before you deploy your changes in GitHub.
- Markdown and Html are still needed to customize your website more than the template. Here are some useful references if you are new to [Markdown](https://www.w3schools.com/html/html_styles.asp) or [HTML](https://www.w3schools.com/html/html_styles.asp) or [Markdown Emoji](https://gist.github.com/rxaviers/7360908).
- For HTML, there are [special characters](https://www.html.am/reference/html-special-characters.cfm) reserved in HTML. That is because these are the characters that make up the HTML language. If you use one of these characters in an article, the browser will try to interpret it as HTML. Therefore, you should use the entity name or entity number when you want to output any of these reserved characters.

#### Domain
You could connect your Github page to your personal domain. The domain I registered is from the [Google domain](https://domains.google/?gclid=Cj0KCQjwrs2XBhDjARIsAHVymmStoNKEfhFv-t_uL7XyhHznQ58uVs-YupQMi4Gu5szADC-Fcemzb1caAv65EALw_wcB&gclsrc=aw.ds).
