---
layout: post
title: Documentation
---

* Do not remove this line (it will not be displayed) 
{:toc}

# Features

## Customizable theme
The theme can be customized just by changing few variables in **_config.yml** file.

## Inline CSS
Since the style used in this theme is very less, I'm inlining it. This will save a request and hence speeds up website loading.

Website loads lightning fast because css pertaining to pages are separated from the css ertaining to posts. All the general css goes to main.css and css for posts go to post.css


## Prose editing ready
You can edit or add blog posts easily using [Prose](http://prose.io).

## Pre-installed Disqus comments
Disqus is already installed. All you have to do is to sign up with Disqus, get the **disqus-shortname** and update it in the **_config.yml** file.


# Installation
Fork the ``master`` branch and delete ``gh-pages`` branch in it. This is important because ``gh-pages`` branch is used here only to host the blog. You should be using the master branch as the source and create a fresh ``gh-pages`` branch.

## How to delete old **gh-pages** branch?
After forking the repository, click on **branches**.

![delete gh-pages branch](http://blog.webjeda.com/images/delete-github-branch.png)

Delete ``gh-pages`` branch.
![delete gh-pages branch](http://blog.webjeda.com/images/delete-github-branch-2.png)

You have to create a new ``gh-pages`` branch using the master branch. Go back to the forked repository and create ``gh-pages`` branch.

![create gh-pages branch](http://blog.webjeda.com/images/create-gh-pages-branch.JPG)

Now, go to settings and check the **Github Pages** section. You should see a URL where the blog is hosted.

This process will host the theme as a **Project Page**. You can also download the files for local development. 

Default theme will look like this


![webjeda yudish jekyll theme]({{site.baseurl}}/images/yudish-jekyll-theme.png)

This theme is responsive.

![webjeda yudish jekyll responsive theme]({{site.baseurl}}/images/yudish-responsive-jekyll-theme.png)
{: style="text-align:center" }

# Customization
Theme can be customized by changing the brand color in **_config.yml**.

``brand-color: '#3498db'``

![webjeda yudish customized jekyll theme]({{site.baseurl}}/images/yudish-jekyll-theme-2.png)

Remember, while developing locally, every change you make in **_config.yml** is applied only if you restart ``jekyll serve`` process.

## Font 
The default font is Robota.


# Development
Make changes to the **master** branch and create a pull request. Do not use **gh-pages** branch as it is used to host the theme.

# License
MIT License

# Changelog
<pre>
version 1.0 - Stability tests and minor fixes.

version 0.9 - SEO improvements.
  
version 0.8 - Minimal design, small and compressed css, built in disqus comments, compressed html, superfast loading UI.
</pre>