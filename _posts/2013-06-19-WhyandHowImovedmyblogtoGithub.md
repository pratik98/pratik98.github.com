---
layout: post
title:  "Why and How I moved my blog to Github"
date:   2013-06-19 12:06:11
categories: Technical
---

Why
=====
i started blogging long back in 2009 or 2010, i don't remember exactly. i chose blogger for no particular reason. might be i was not aware of wordpress then. i have seen many people moving their blog from blogger to wordpress. but i didnt. for me both are the same. may be wordpress have better UI and Themes and all. but i certainly didnt want to put that much effort in moving to wordpress. 
blogger and wordpress both are database driven CMS. you dont design anything. you just use the services provided by them. ofcourse you can make your own theme but you need to learn wordpress templet system for that and who wants to do that!

As an Engineer, i love to build things. non-tech guys can use these CMS but as developer i just felt dirty to use that for my personal site where I should be showing off my skills. greater joy of life is in building things, not in searching or finding them. As i quote [kevin](http://www.ksornberger.com/),
> _"I figure it's kind of like a good carpenter buying all his wood furniture from Ikea. It's easy and works, but you can't be very proud to have it in your house."_

I recently came across some websites and blogs which are made with static website generators. 
static website generator is blog aware static website tool. it allows custom design. you can have your own custom CSS. you can _handcraft_ your blog. [jekyll] [jekyll] is one of the most popular ruby based blog aware static website generator.you can write your blog post in textfiles using markup like [Markdown][markdown] and jekyll will convert that texfile into web presentable HTML and will wrap your stylesheet CSS to it. pretty awesome.

 Thus you have all the liberty to customize the website any way you want. You can add/replace and modify all the pages and you can have complete control of what is posted. With Jekyll, adding a new blog post to your site is as simple as adding a [Markdown][markdown] text file to the "_posts" folder sitting in your master folder. 

* Other Advantages of having Static Websites:
=============================================
	* Fast
	* Free Hosting on Github
	* Easy Blogging (It's like running website from your computer)
	* you own your Data (it's saved locally.)
	* Customized Design and custom domain support
	* that proud feeling which wordpress users will never get ;)

you can integrate plugins like [disqus](http://www.disqus.com) too.

Typical jekyll Workflow for me:

<pre>
>cd website/folder/on/computer

>jekyll serve -w

> Add your content to texfile using markdown and save it with ".md" or ".markdown" 
extension.

> put this file in "_post" folder.

> git commit

> git push 
</pre>
<br />

How
===
There are many ways you can use jekyll. i will simply give you links of tutorials which worked for me.
* [Official Docs] [jekyll]
* [install jekyll on windows](http://www.madhur.co.in/blog/2011/09/01/runningjekyllwindows.html)
* [start blogging](http://www.ksornberger.com/blog/blogging-with-jekyll-and-github/)
* [Markdown] [markdown]

you can fork any repo from [the list](https://github.com/mojombo/jekyll/wiki/Sites) of websites made with jekyll. feel free to use [source](https://github.com/pratik98/pratik98.github.com/) of this website too.
don't forget to post link of your jekyll powered blog in comments when you make one.

Adios.

[jekyll]:http://www.jekyllrb.com
[markdown]:http://daringfireball.net/projects/markdown