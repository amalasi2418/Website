---
title: Hello World
author: Abhinav Malasi
date: '2021-07-19'
slug: hello-world
excerpt: The first assignment for any coding lessons back in 90's was printing "Hello World". I guess, this should definitely be a good starting point for this blog.
categories:
  - base R
layout: single-sidebar
tags:
  - R Tutorial
---
Hello and welcome to my blog. If you are interested in learning R then you are at the right place. Let's start small and build from there.

The first thing I remember about coding is "Hello World" text. When I 
started to learn coding, the very first assignment was to print the "Hello World" text.

So, here I begin my very first post by printing this very text using base R commands.

The text can be directly printed using the `print` command.

```{R}
print("Hello World")
```

Or, the character string can be assigned to an object which can be used for printing.

```{R}
a <- "Hello World"
a # print the value assigned to the object
print(a)
```

or, use the `paste` commands of base R.

```{R}
paste("Hello", "World", sep=" ")
paste0("Hello"," ","World")
```