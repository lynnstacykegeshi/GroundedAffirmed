---
author: author
authorLink: ""
categories:
- category
date: "2022-06-24T18:28:32+02:00"
description: Descrizione da rivedere se è un doppione subtitle
draft: false
featured: false
hiddenFromHomePage: false
hiddenFromSearch: false
lastmod: "2022-06-24T18:28:32+02:00"
license: ""
lightgallery: false
math:
  enable: false
resources:
- name: featured-image
  src: featured-image.png
sidebar: true
slug: code-sample
subtitle: Insert a subtitle here
tags:
- tag1
- tag2
- tag3
- tag4
title: Code Sample
toc: false
weight: null
---

The following are two code samples using syntax highlighting.

<!--more-->

The following is a code sample using triple backticks ( ``` ) code fencing provided in Hugo. This is client side highlighting and does not require any special installation.

```javascript
    var num1, num2, sum
    num1 = prompt("Enter first number")
    num2 = prompt("Enter second number")
    sum = parseInt(num1) + parseInt(num2) // "+" means "add"
    alert("Sum = " + sum)  // "+" means combine into a string
```

The following is a code sample using the "highlight" shortcode provided in Hugo. This is server side highlighting and requires Python and Pygments to be installed.

{{< highlight javascript >}}
    var num1, num2, sum
    num1 = prompt("Enter first number")
    num2 = prompt("Enter second number")
    sum = parseInt(num1) + parseInt(num2) // "+" means "add"
    alert("Sum = " + sum)  // "+" means combine into a string
{{</ highlight >}}

And here is the same code with line numbers:

{{< highlight javascript "linenos=inline">}}
    var num1, num2, sum
    num1 = prompt("Enter first number")
    num2 = prompt("Enter second number")
    sum = parseInt(num1) + parseInt(num2) // "+" means "add"
    alert("Sum = " + sum)  // "+" means combine into a string
{{</ highlight >}}
