---
layout: post
comments: true
number: 3
title: Create and host your website for free
author: Ankur Maharjan
nickname: ankur
tags: github-pages website host
coverimg: github-pages
---

<div class="message"> "Tell the world all the great things you are building."</div>

![cover pic github pages](/public/images/posts/github-pages.jpg)

We all want to create our own portfolio sites, don’t we? I want to create one too without having to spend a penny, but the problem is that I often hesitate to build the site thinking about the server, database and of course, the hectic process of hosting. Why would I want to spend money for that? So, do we have a solution for this problem? The answer is a **`BIG YES`**. Do you want to create a website to showcase your portfolio, your project or your product? Do you don't want to go through all the dull process of hosting? And do you think if all these things can be done for free? Yes, it can be done and the ultimate solution is **Github pages**. Yes, the **`GitHub Pages`**!!

Let me explain it to you briefly. There are a lot of options out there to build a website nowadays. However, most of these options can be excessive and overwhelming even for a software developer who builds such websites. **Github pages** let you turn your repositories to the elegant website to showcase your portfolio, project, product, documentation or anything you want to share with the world. You don’t need to worry about the database, the server or the process of hosting. Trust me,  it’ll work fine.

![Github Pages](/public/images/posts/github-pages2.jpg)

Simply, we can say that GitHub Pages are the public web pages hosted for free through GitHub. GitHub users can create and host both **personal/ organization websites** (one allowed per user) and **project websites** (websites related to specific GitHub projects). You can create personal or organization site  by creating a repository with your GitHub username and adding web content to its master branch. On the other hand, for websites related to specific GitHub projects, Github looks for the web contents of your projects on a special branch i.e. gh-pages for the sites tied to the existing repository. This branch is independent from your code branch. It seems like this blog has become boring with all these theory stuffs. But don’t worry, you’ll be able to create and deploy both personal and project sites on Github in minutes at the end of this blog for free. Isn’t that cool? Therefore, just keep calm and read on.

> “The easiest way to quickly publish beautiful pages for you and your projects.”

## So, how does it work?

Github serves all your project sites from a personal URL tied to your username or organization.

```
`https://your-account.github.io`
```

Github looks for the web contents on the special branch i.e. gh-pages or master branch of the repository then automatically builds and deploys the site for you. Ok, this is something awesome. This allows you to focus on the content of your sites rather than worrying about building and deploying your site. Now, let’s move on to the interesting section.

## What are the steps then?
Let me tell you the simple steps to create and deploy your own personal/ organization site and project site in minutes. Let’s get started.

### A. Steps to create personal or organization site

1. **Create  a repository**

    Go to GitHub and create a new repository named username.github.io, where username is your username (or organization name) on GitHub. *If the first part of the repository doesn’t exactly match your username, it won’t work, so make sure to get it right.*

1. **Clone the repository**

    Go to the folder where you want to store your project and clone the repository you created.

1. **Add index.html**

    Enter the project folder and add an index.html file. You can add contents to index.html file. *(Or, you can download free templates, add your own flavours, update contents and add to the project folder. Just keep in mind that the project root must have index.html file.)*

1. **Push the repo**

    Now, it’s time to add, commit, and push your changes.

1. **And you’re done**

    Fire up a browser and go to `http://username.github.io`. You can see your site.

See, it’s too easy. You can take **Bajra Weekly** as an example of organization site hosted on GitHub. This blog is published on Github with the help of **Jekyll**. Jekyll is an open source tool to transform plain text to website and blog. You can try to create yours. If you want to create website for your project, you can view Section B below.

### B. Steps to create project site

1. **Repository Settings**

    Go to GitHub and create a new repository, or go to an existing one. Now, click on the Settings tab. For Project pages, the gh-pages branch is used to publish your site. This branch is not related to your code branch.

1. **Use Automatic Generator**

    Scroll down to the GitHub Pages module. Press the Launch automatic page generator button.

1. **Add Content**

    Use the editor to add content to your site. If you already have a README.md in your project, you can import that file by clicking a button on the right-hand side of the page. When you're done, click Continue to Layouts.

1. **Pick a theme**

    Choose one of the themes in the carousel at the top. When you're done, click the Publish button on the right-hand side.

1. **And you’re done**

    Fire up a browser and go to `https://username.github.io/repository`. You can see your project site.

So, what are you waiting for? Head over to [Github.com](https://github.com) and create your own website and host it for free on Github using **Github Pages**.