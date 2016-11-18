---
layout: post
title:  "1st assignment - Client Based Programming"
date:   2016-11-15 17:00:00
comments: true
categories: jekyll update
---
### 1. What do you think of pre-compiling your CSS?

>When you get the hang of it, the structure becomes more organized and shortened in the long run, which both
>limits the risk for errors and lets you alter code more efficient. It also offers developers to use e.g. variables and functions
> in css-related purposes. Compared to regular css, which soon extends to large amounts of code, where you often can't avoid
> scrapping the DRY- philosophy, pre-compiling is preferred in most cases, in my opinion. The main con I think is the extended amount of
> files that are to be used when pre-compiling, but if you learn to keep the different files organized, the pros exceeds the cons.

### 2. What do you think of static site generators?

> Great for reducing the time it takes to duplicate your web site's different, almost identical, html- files. This in my opinion makes
> developing more efficient and organized. In addition, it shortens loading time for the client and has a high security level. Apart from the below mentioned
> limitations, I'd say my experience is similar to the css pre-processors.

### 3. What type of projects are they suitable for?

> Projects with a larger amount of complex content, such as extensive databases, should not use static site generators.
> Rather, a static site is more suitable for less "dynamic" sites with information and/or presentations.

### 4. What is robots.txt and how have you configure it for your site?

> Robots.txt-files are used to give instructions to web robots on what access they, or specific robots, have on your web site.
> Robots scan web sites for content, which can vary depending on the robot's goal, for example, both search engines and spammers use them.
> Robot-txt:s are also called Robots Exclusion Protocols. For now, I've allowed full access to all robots on this web site
> to broaden accessibility, and due to the fact that "badbots" often ignore robots.txt- files anyway.

### 5. What is humans.txt and how have you configure it for your site?

> Humans.txt.files used to give the client access to information about the web site's authors/teams/developing software and more.
> Such information could quite quickly occupy space on the web site that could be more suitable for other content. I configured my
> humans.txt-file with information about the creator, special thanks to the course team, and when the site was lastly updated.

### 6. How did you implement comments to blog posts?

> Through the usage of [Disqus](https://disqus.com/), i.e. by creating a disqus.html- file with the Disqus universal code, place this in  the _includes-folder,
> then include this file in the layout for posts and finally put "comments: true" in the desired post md- file.

### 7. What is Open Graph and how do you make use of it?

> The Open Graph Protocol is used to give a web site certain "standard attributes" to present its content in social media, such as facebook.
> By setting default url, identity image, the type of the content (e.g. website or video) in your head.html, you'll get a standardized presentation
> of your content when sharing it in social media.
