---
layout: post
comments: true
number: 1
bajra_weekly: false
title: Getting Started with Bajra Weekly
author: Ankur Maharjan
nickname: ankur
tags: sample
---


- Fork the repo <a href="https://github.com/bajratech/bajratech.github.io.git" target="_blank">Bajra Weekly</a> to your github account
- Clone the repo from your account and create a new relevant branch
- To create a new post, all you need to do is create a file in the **`_posts`** directory
- Bajra Weekly requires blog post files to be named according to the following format:

  ```
  YEAR-MONTH-DAY-title.MARKUP
  ```
- Write your blog in previously created file. It is motivated to write your blogs on **`markdown`**
- Include following line in the file before writing the content of the post

  ```
  ---
  layout: post
  comments: true
  title: <title of the post>
  author: <your name>
  nickname: <nickname(include nickname.jpg file in public/images/author/ directory)>
  tags: <tags>
  coverimg: <coverimg (include coverimg.jpg file in public/images/posts/ directory)>
  ---

  ```
Example:

  ###### 2016-09-07-Getting Started with Bajra Weekly.md

  ```
  ---
  layout: post
  comments: true
  title: Getting Started with Bajra Weekly
  author: Ankur Maharjan
  nickname: ankur
  tags: sample blog
  coverimg: bajra
  ---

  The content of the post goes here.

  ```
- Once you are done, you can push it to your repo
- Then submit your pull request to the master branch of repo **`bajratech/bajratech.github.io`** from your github repo
- And lastly, inform **`Loomila Hada`** for cerification