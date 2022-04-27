---
layout: post
title:  "Using Weblate without linked vcs repository"
date:   2022-04-27 02:35:00 +0200
categories: localization weblate
---

> Disclaimer: This post is a temporary post create during the initialisation of this blog.
> Do not expect the content to be fully relevant or complete.

Some times ago, I started using [Weblate](https://weblate.org) to manage translations in some of my Symfony and Python
projects.

I've come across a little limitation explained in only one paragraph in the documentation.

### What I want to do

I want to be able to create a new translation component without linking it to a VCS repository.

### Is that possible?

Yes it's possible. I just forget how I did it the first time.

### How to proceed?

#### 1. Weblate documentation

In the documentation, I found the following paragraph which answer my question:

![Option "Upload translations files" visible](/assets/images/using-weblate-without-linked-vcs-repository-img-1.png)

**_Link: [https://docs.weblate.org/en/weblate-4.11.2/admin/projects.html#adding-translation-projects-and-components](https://docs.weblate.org/en/weblate-4.11.2/admin/projects.html#adding-translation-projects-and-components)_**

#### 2. Other ways

There is two ways to create a new `translation component` without vcs repository.

Click on `Add new translation component` and you will see these options:

![Options to choose to create component without vcs repository](/assets/images/using-weblate-without-linked-vcs-repository-img-2.png)

Choose the one which matches the most your need.
