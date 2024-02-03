---
title: "Developing and Deploying a Portfolio."
date: 2024-02-03T01:21:59+05:30
github_link: "https://github.com/sathvik9105/"
author: "Sathvik Pasuvula"
tags:
  - Portfolio
  - Hugo
  - amfoss
image: /images/hugo.svg
description: "A summary of my blog post."
toc : false
---

# Task 2: Building My Portfolio Website using hugo themes and deploying through GitHub pages.

In this task, I was asked to create my own portfolio website using a hugo theme and deploy it using github pages. Hugo is a powerful open-source static website generator. This task is really special to me as I've created a webpage for the first time ever in my life. I've briefed the steps I've followed in this process of creating and hosting the portfolio website.

## Installing HUGO and Creating Server

To install HUGO in my linux terminal, I referred <a href="https://gohugo.io/installation/linux/" style="color: red;">Install Linux Guide</a> .So I ran following commands in the terminal; It created a local server for me to use and customize the portfolio.
1. `sudo apt install hugo`
2. `hugo server -D`
 
## Theme Selection

For my portfolio website, After going through many themes, I finally chose <span style="color: yellow;">**Hugo Profile**</span> theme as I found it perfect for a portfolio structure and I liked the theme, colours, design.

## Customization
To cutsomize my portfolio, I had to make changes in **config.toml** file.  
Following are the customizations I made in my portfolio: 
1. Rewriting details
2. Adjusting Layouts
3. Deleting unnecessary parts
4. Including usable links

## Content Creation

I wanted my portfolio to showcase my interests, background and work. To achieve this, I've included content in the following sections:  
- About me
- Education
- Projects 
- COntact me
- Blog

I wanted my website to be user-friendly. So if a person lands on my portfolio site, they'll see my latest projects right away. I've ensured that the navigation menu at the top is easy to use, so they can explore my works, skills, education, and contact info easily. Lastly, I've placed buttons inviting you to reach me out.


## Challenges and Solutions

While building my portfolio, I faced a few challenges, such as adjusting layouts which I resolved by watching youtube tutorials and using google browser.

## GitHub Pages Hosting

While hosting my portfolio website using Github Pages, I faced a small challenge. I got an error message (error 404 page not found) when I first attempted to host the portfolio website. The issue was that Hugo had already created a `public` directory for me. So I deleted `public` directory and ran this command `git submodule add` and everything worked perfectly.
To host the website, I used [Host HUGO website with Github Pages](https://youtu.be/LIFvgrRxdt4?si=8FpecldaZ8U-7F5q) video. 

## Conclusion

Building my portfolio website with Hugo and hosting it on GitHub Pages was a great and new learning experience to me. I gained valuable insights and developed slight interest towards web development. 

## Links

1. Blog Repository (used for storing portfolio code):
  - [blog](https://github.com/sathvik9105/blog)

2. Repository for deploying your portfolio:
  - [sathvik9105.github.io](https://github.com/sathvik9105/sathvik9105.github.io)

3. Live Portfolio:
  - [View Portfolio](https://swayam-agrahari.github.io/)

4. Blog:
  - [Blog Post](https://swayam-agrahari.github.io/blogs/markdown-syntax/)


---
*Acknowledgments: This portfolio is solely made with my knowledge and my ability to use Internet.*
