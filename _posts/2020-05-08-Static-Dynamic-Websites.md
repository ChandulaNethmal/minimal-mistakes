---
title: "Static Vs. Dynamic Websites"
header:
  overlay_color: "#000"
  overlay_filter: "0.4"
  overlay_image:  "assets/images/static_dynamic/stat-dynamic_1.jpg"
  teaser: "assets/images/static_dynamic/stat-dynamic_1.jpg"
  og_image: "assets/images/static_dynamic/stat-dynamic_1.jpg"
categories:
  - Programming
  - Web
tags:
  - Web Designing
  - Static
  - Dynamic
  - Jekyll
toc: true
---
Nowadays, the word "Website" is a very common thing, even among primary school chilren. We are going to discuss about a basic categorization of websites. 

## What is a Website?
Nowadays, the word "Website" is a very common thing, even among primary school chilren. Everyone in the society is benefitted with different types of websites in their day-to-day life with or without a knowledge on this. 

![Unsplash image 9]({{ site.url }}{{ site.baseurl }}/assets/images/static_dynamic/stat-dynamic_1.jpg)
Before get in to our major topic, we need to discuss some basics. Let's start with the following three terms.

* web page: 
A document written in a statdard format which can be displayed in a web browser such as Firefox, Google Chrome.  These are also often called just "pages".

* Web server:
A computer that hosts a website on the Internet.

* Domain name:
A domain name is a dedicated string for identification that defines a realm of administrative authority or control within the Internet. 

Basically a website is a combination of set of web pages and related content that is identified by a common domain name and published on at least one web server. Applications of websites are in a broad range and ownerships of those websites also vary from organizational level to private blog site level.  

All publicly accessible websites collectively constitute the World Wide Web. Other than those public websites there are also private websites that can only be accessed on a private network, such as a company's internal website for its employees.

Websites are typically dedicated to a particular topic or purpose, such as news, education, commerce, entertainment, or social networking. Hyperlinking between web pages guides the navigation of the site, which often starts with a home page.
Web sites can be categorized in to basic two branches as Static websites and Dynamic websites. In this post, we are focusing on discuss about static websites since this blog is based on a static web site.    

![Unsplash image 9]({{ site.url }}{{ site.baseurl }}/assets/images/static_dynamic/stat_dyn.png)

## What is a Dynamic website?

Dynamic websites are  contain Web pages that are generated in real-time. These pages include Web scripting code, such as PHP or ASP. When a dynamic page is accessed, the code within the page is parsed on the Web server and the resulting HTML is sent to the client's Web browser.

Most large websites are dynamic, since they are easier to maintain than static websites.

## What is a Static Site?

A static website contains Web pages with fixed content. That means, each page displays the same information to every visitor.

![Unsplash image 9]({{ site.url }}{{ site.baseurl }}/assets/images/static_dynamic/stat.png)

Since static Web pages contain fixed code,the content of each page does not change unless it is manually updated by the webmaster. This works well for small websites, but it can make large sites with hundreds or thousands of pages difficult to maintain. Therefore, larger websites typically use dynamic pages, which can be updated by simply modifying a database record. Static sites that contain a lot of pages are often designed using templates. This makes it possible to update several pages at once, and also helps provide a consistent layout throughout the site.

### Advantages of a static website

- Provide improved security over dynamic websites (dynamic websites are at risk to web shell attacks if a vulnerability is present).
- Improved performance for end users compared to dynamic websites.
- Fewer or no dependencies on systems such as databases or other application servers.
- Cost savings from utilizing cloud storage, as opposed to a hosted environment.

### Disadvantages of a static website
- Dynamic functionality must be performed on the client side.
- Even a small change to some Websites with large nuber of pages may bit difficult.

## Static Site Generators

Basically, static site generators are command-line tools that generate the creation of the final HTML page forward from the point the user requests it to the point you write the content. When you make any update to a page, generators will build you the new page, which can then be served as-is to every user who requests it as we discussed in the above sections. There are several popular ststic-site generators you will find as follows.

1. Jekyll
2. Gatsby
3. Hugo
4. Hexo
5. Nuxt

Here, I am going to coninue our discussion with Jekyll since this site is built with Jekyll generator.

## What  is Jekyll?

![Unsplash image 10]({{ site.url }}
{{ site.baseurl }}/assets/images/jekyll-logo.png)

Jekyll is a simple, blog-aware, static site generator for personal, project, or organization sites. Written in Ruby by Tom Preston-Werner, GitHub's co-founder, it is distributed under the open source MIT license.Instead of using databases, Jekyll takes the content, renders Markdown or Textile and Liquid templates
and produces a complete, static website ready to be served by Apache HTTP Server, Nginx or another web server.

Jekyll is the engine behind GitHub Pages, a GitHub feature that allows users to host websites based on their GitHub repositories for no additional cost.Jekyll is flexible and can be used in combination with front-end frameworks such as Bootstrap,Semantic UI and many others.
