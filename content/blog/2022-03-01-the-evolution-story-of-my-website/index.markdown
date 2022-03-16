---
title: 'The Evolution Story of My Website'
layout: single-sidebar
date: '2022-03-01'
slug: blogdown
show_post_thumbnail: true
thumbnail_left: true  # for list-sidebar only
show_author_byline: true
draft: no
categories:
  - Blogdown
  - Rmarkdown
tags:
  - Blogdown
  - Rmarkdown
subtitle: 'A blog on how my website has evolved since I adapted blogdown.'
summary: 'This blog intends to display my website evolving path. Meanwhile, it also provides a roadmap for those who want to build website for yourself. '
lastmod: '2022-03-08T23:44:01-05:00'
featured: yes
disable_jquery: no
image:
  caption: ''
  focal_point: 'Smart'
  preview_only: no
projects: []
output:
  blogdown::html_page:
    toc: yes
    number_sections: false
    toc_depth: 3
---







<!-- adding here-bot cat -->
{{<here>}}  

# My website story  

If you are reading this blog, congratulations👏, you've already found my website. So, you don't need to continue reading this blog 😄.

Let me give you some back-scene stories of my website building history.   
I've always wanted to have my personal website so that I could have a place to chat and record my life. 

My first website was built back to my graduate school era (2011). It was completely built by `html` through **Dreamweaver**, with some `css` style helps from my friend. The website content is static and has no dynamic data exchanging feature at all. The site is simply a showcase to my studies and works. I hope maybe the recruiters and my future employers could know me more through my website.  Luckily, this simple `html` website, to some extent, helped me land my **first job** in US. 

Back to the old days, building a website required a huge amount of time to carve details in fonts, colors, and styles (e.g., `css`). Developers also need to tune in and monitor tons of `html` parameters. Building a website is an exhausting and time-consuming process. What's more, website maintainance makes the website-build job even harder. My first site was built and hosted on the school's platform. Unfortunately, soon after my graduation, it is expired and could never be retrieved. 


Many years later, I happened to learn `rmarkdown` and its R-package from 2019 RStudio conference. Later on, I found a new R package-`blogdown` developed by the same developer who developed `rmarkdown`. Being a long-time R-user, I surprisingly see it provides a tool for R-Users to build a website in R. **Amazing!!** Meanwhile, the connection between `git` and `RStudio` makes website building much easier and smoother. No `Dreamweaver` and `FTP` are needed. Just simply using [RStudio](www.rstudio.com) and [github](www.github.com), anyone can build his own site. 

When I saw it, I got excited. I immediately took in action. After many nights hard works and debugging, I finally built up my first `blogdown` website.The first version of my website was built through `blogdown` with easy theme-`hugo-lithium`. 

The [site](https://ouzhang.netlify.app) adapted a simple theme directly from Yihui Xie's **Blogdown** book.

<div class="figure" style="text-align: center">
<img src="img/first_webpage.jpg" alt="1st website look" width="80%" />
<p class="caption">Figure 1: 1st website look</p>
</div>

As you can see from the picture, it contains a simple layout with some minimum website functions. it's a good starting point but a professional website shouldn't look like that. There must be better themes to suit my needs-**professional and fancy**. 

Therefore, after some researches and googles, I found this theme-`Hugo-academic` (see below).  

<div class="figure" style="text-align: center">
<img src="img/hugo-academic.jpg" alt="Hugo Academic Template" width="80%" />
<p class="caption">Figure 2: Hugo Academic Template</p>
</div>


The template looks nice and professional, with many intriguing features. Without any hesitation, I decided to switch my website to this theme. However, complicated feature means troubles. Throughout the theme-switch process, I encountered hundreds of obstacles which lead to countless upsets and frustrations. 

To make it work, I had to rely on online searching and asking questions on [Stack Overflow](https://stackoverflow.com/) to solve/break every **brick wall** I bumped into. it's an unpleasant experience with `99%` of frustrations and `1%` of excitement. Finally, I made it worked. The website looks nice. You can find how fancy it is by checking the picture below or visiting my [old site](https://ouzhang.rbind.io/).      


<div class="figure" style="text-align: center">
<img src="img/second_webpage.jpg" alt="2nd website look" width="80%" />
<p class="caption">Figure 3: 2nd website look</p>
</div>

Frankly, I love my `Hugo Academic` theme website, it delivered everything I wanted and functioned well. However, since early 2021, `Hugo Academic` switches to `Wowchemy`. This transition makes existing website hard to be updated 😭. Error messages were bounced back every time when I tried to update website or added a new blog post. For that, I had to find a new theme for my website. 

Then, I found [Alison Hill](https://www.apreshill.com/) and the [Hugo Apéro](https://hugo-apero-docs.netlify.app/) theme she developed. Making a website theme switch isn't easy. Eventually after a month work, my website has a new look (see below).


<div class="figure" style="text-align: center">
<img src="img/current_webpage.jpg" alt="Current look" width="80%" />
<p class="caption">Figure 4: Current look</p>
</div>

This is a simple story about my website evolution. Throughout the whole process, I've encountered so many issues and  
I understand that it is a long way from knowing `rmarkdown` to having a beautiful website built. Therefore, I decide to layout all the information and resources I collected in the process and I hope these resources could provide a **roadmap** for those who want to build website by yourself but do not have luxuries in time to search them all. I wish by reviewing this blog post, readers could can cut the corners and get straight to the information you need so that save some of your time could be saved for more meaningful things. 


# Prerequisite

Before you build your website, a couple of key knowledge you'd better have: `Rmarkdown` and `git`. 

## R Markdown
For anyone who hasn't known `rmarkdown`, Yihui Xie's book is the best resource to read and learn. According to my personal experience, this is the most efficient resource to learn. It contains all the information you need. You really don't need to search any other materials. 

**Book Link:** [R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/)

## Git and Github with R  
After reading the book above, you need to know what are `git` and `github`, and how these two work with `RStudio`. To build up a website, you don't have to go over all the materials about `git`. [Jenny Bryan](https://www.rstudio.com/authors/jenny-bryan/)'s 2019 RStudio conference talk is a very good resource to start.

I personally recommend you to **patiently watch** this video material ([Happy Git and Gihub for the useR Tutorial](https://www.rstudio.com/resources/rstudioconf-2017/happy-git-and-gihub-for-the-user-tutorial/)).

If you have a bit more time, you can also read her book as well ([Happy Git and GitHub for the useR](https://happygitwithr.com/)).

# Create your Website like my 1st one
Once you've already possessed basic knowledge about `rmarkdown` and `git`, it's time to start your first website building. The first learning material I recommend is Yihui Xie's `Blogdown` book-[blogdown: Creating Websites with R Markdown](https://bookdown.org/yihui/blogdown/). You can read this book and follow the instruction in the book to construct your site. For those who only have limited time, you can also view Yihui's talks in 2017 and 2018 (See below).


[Introduction to Blogdown (R Package)| RStudio Webinar - 2017](https://www.youtube.com/watch?v=CjTLN-FXiFA&list=PLrN6_zSrrwJ5tkzB0VjSAdwSEpgIIlsOa&index=2&t=234s)

[Create and maintain websites with R Markdown and blogdown|2018](https://www.rstudio.com/resources/rstudioconf-2018/create-and-maintain-websites-with-r-markdown-and-blogdown/)

I also list his [2018 Talk Slide](https://slides.yihui.org/2018-blogdown-rstudio-conf-Yihui-Xie.html#1) for your information.


Once the website are built, you need find an online platform to deploy your website. `github` is a good platform, so is [rbind.io](https://support.rbind.io/about/). 

More useful information can be found from the intro blog-[Publish and share your own website for free with GitHub](https://medium.com/@svinkle/publish-and-share-your-own-website-for-free-with-github-2eff049a1cb5). 

I also list another informative intro blog post:
[Making a Website Using Blogdown, Hugo, and GitHub Pages](https://amber.rbind.io/2016/12/19/website/)

## Netlify 
Yihui highly recommend [Netlify](https://www.netlify.com/) as a website deploy platform in his book. `Netlify` is the platform where my website deploys. For those who have interests to know more, Yihui's `blogdown` book [Chapter 3.1](https://bookdown.org/yihui/blogdown/netlify.html) has details about `Netlify`. 

I also listed a useful blog post introducing the work flow with `Github` and `Netlify`:
[A Blogdown New Post Workflow with Github and Netlify](https://www.garrickadenbuie.com/blog/blogdown-netlify-new-post-workflow/)

I believe that the content I listed above covers enough knowledge for you to create your personal website like my first one. 

# Create your Website like my 2nd one
Someone may think my first website looks too simple and prefer the `Hugo Academic` theme. No problems. Here are useful information you need. Although, I personally think `Hugo Academic` development path is a bit inconsistent and hard to keep it up, although it is a very professional theme and good-looking. Please find the useful blog posts below.

Useful blog 1: [Building an academic website using blogdown](https://support.rbind.io/2017/06/16/academic-site-apreshill/)

Useful blog 2: [Tips for using the Hugo academic theme](https://lmyint.github.io/post/hugo-academic-tips/)

# Create your Website using Hugo Apèro Theme
At beginning, I found `Hugo Apèro` theme from [Alison Hill](https://www.apreshill.com)'s website. Her website was built by `Academic` theme. Since `Academic` becomes hard to update, she develops `Hugo Apèro` and adapt it as her website theme.

Dr. Alison Hill has a wonderful 2-hour online seminar introducing `blogdown` and `Hugo Apèro` theme. In this 2-hour seminar video, she patiently walk through the process of building a website, step-by-step. You can watch this seminar on YouTube and the link is listed below.

[Introduce yourself online using blogdown and Hugo Apèro](https://www.youtube.com/watch?v=RksaNh5Ywbo&list=PLrN6_zSrrwJ5tkzB0VjSAdwSEpgIIlsOa&index=3)

[Hugo Apèro](https://hugo-apero-docs.netlify.app/) also has its online template website for you to study and clone from [github](https://github.com/hugo-apero/hugo-apero). 

If you've already built your website in `Hugo Academic`, [Silvia Canelón](https://www.silviacanelon.com/) wrote a blog describing how she converted a Blogdown Site from `Hugo Academic` to `Hugo Apèro`.

Here is the blog: [Hello Hugo Apéro: Converting a Blogdown Site from Hugo Academic](https://www.silviacanelon.com/blog/2021-hello-hugo-apero/). 

But I highly suggest you **Not to do** it.

Silva's personal site and corresponding github repos are also a good resource for those who want to build up website using blogdown 😄.


I've also created a YouTube Playlist in which I listed all the useful Webinar videos for `Blogdown`. If you have some interests to know more, please refer this playlist below.

[Blogdown Tutorial YouTube Playlist](https://youtube.com/playlist?list=PLrN6_zSrrwJ5tkzB0VjSAdwSEpgIIlsOa)

# Something Extra
[Hugo](https://gohugo.io) has been mentioned in this blog many times. Yihui introduces `Hugo` in his `Blogdown` book on [Chapter 2](https://bookdown.org/yihui/blogdown/hugo.html). 

In summary, `Hugo` is the **static site generator** on which `blogdown` is based. The introduction is lengthy and the content is quiet complex, frankly speaking. 

A broad high-level review of the `Hugo` can be found on the YouTube. If you have some spare time, you can review it (See the link below).

[6-minute Hugo Intro](https://www.youtube.com/watch?v=qtIqKaDlqXo).

--- The End --- 



