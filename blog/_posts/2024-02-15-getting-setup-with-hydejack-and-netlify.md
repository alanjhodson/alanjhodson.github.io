---
layout: post
title: "Getting started with Hydejack and Netlify"
permalink: "/getting-setup-with-hydejack-and-netlify/"
description: "Getting the site setup using Hydejack and Netlify - A great way to start a new site and blog."
categories: [Github, Netlify, Jekyll]
image:
  path: /assets/img/getting-setup-with-hydejack-and-netlify/post_default_image.jpg
sitemap: true
hide_last_modified: true
comments: false
---

<!--excerpt-->

-  Table of Contents
{:toc}

## Intro

Many moons ago in the 90's I started my first IT gig as a webmaster. At the time there was no standards for HTML, stylesheets or much at all really and many sites were simple static pages viewed by a text based browser. A lot has changed since then and its been a little while since I last did any work with webhosting or software development. I wanted to start this site including getting back underway with my blog journey but didn't want to do what I'd done previously with Wordpress or pay for ongoing hosting and such. Having looked at a number of blogs of a number of peers in the industry I noted a few were using Github for storing their site content and making use of Jekyll. On the journey I looked at various themes, using Github Pages and also Netlify. 

Being a free option, I jumped in and built my site using Netlify which has a number of fantastic features, Jekyll and the [Beautiful Jekyll theme by Dean Attali](https://beautifuljekyll.com/). It was sure a learning curve, but there are some great tutorials out there and once I got the repository setup on Github and the sample content running I was underway. I'm maintaining a test version of the site also so that I can deploy any changes and make sure I'm happy before rolling them out and keeping a synced copy of my repository with versioning in a separate storage service. This can easily be done with something like Dropbox, Onedrive etc.

I toyed with the idea of setting up a hosting environment on my local Windows machine but decided to not go through that fun!

## Welcome to the Hydejack Theme

There are a number of sites built on the [Hydejack theme](https://hydejack.com/) which I thought would be a great starting point.  

For this site I am using the hydejack-pro theme as it gives me the following additional functionality over the free version:

-  Gridview for Blogs Posts
-  Dark Mode
-  Forms
-  Search

You can use the free version just as easily, the process is the same and could easily be deployed by forking from the Hydejack Github site but in my case with the Pro version, I simply created the repository per the documentation using the standard of username.github.io and then exported the theme from the supplied files.

Key thing for working with Hydejack is RTFM...

## Deploying to Netlify

Once I was happy with the basics of the site I updated the Github repository and setup a free Netlify account. From there I was able to point things toward my repository and build and publish the site. I had a little issue with the version of Ruby referenced in the build but once I sorted that everything came up. Finally, I was able to setup using my domain with Netlify and it did the rest - Brilliant.

Once happy, I merged to main, and changed my publishing again. I then opened a ticket with Github to remove the fork status from my original site.

## Reference sites

There are few really handy references who have worked with Hydejack and provided some customisations and guidance, a couple below worth checking out:

-  [Dan Tsekhanskiy](https://tseknet.com/blog/startblogging)
-  [DaeIn Lee](https://lazyren.github.io/devlog/how-i-customized-hydejack-theme.html)
-  [James Kindon](https://jkindon.com/)

Thanks to James who fielded a couple of daft questions but helped me get throught the basics with Github Pages before I sorted out Netlify.

## Handy Tools

Some tools I have found very useful in my adventures:

-  [Visual Studio Code](https://code.visualstudio.com/) for post editing with markdown
-  [Unstatic forms](https://un-static.com/) for handling the forms on the site
-  [Unsplash](https://unsplash.com/) for some of the images on the site
-  [Good Free Photos](https://www.goodfreephotos.com/) for free photos and other images

## Summary

After taking a break from work in December, this was a great way to get things moving again with a little tech project.