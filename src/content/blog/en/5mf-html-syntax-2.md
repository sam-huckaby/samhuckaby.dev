---
layout: ../../../layouts/post.layout.astro
title: '5-Minute Fundamentals: HTML Syntax (Part 2)'
pubDate: 2023-07-02
date: 2023-07-02
description: 'A recap of a 5-Minute Fundamental overview of HTML attributes and code assists.'
author: 'Sam Huckaby'
youtube: 'https://youtu.be/E7qkzut7io0'
image:
    url: '/logo_pile.png' 
    alt: 'The Crash Course Pile.'
tags: ["5-minute-fundamentals"]
---

# 5-Minute Fundamentals: HTML Attributes, Code Cleanliness, and Built-In Browser Tools

Welcome! Today we're going to delve deeper into HTML syntax, understanding its basic methodology, certain tools, and some good habits that can make it seem less intimidating. Even after learning the fundamentals of HTML syntax, it can still be a bit challenging to feel comfortable writing it. This sentiment is totally normal, especially if HTML is your first language or just your first templating languages.

After reading this blog, you're going to look at HTML in a different light. We will dive into fresh concepts surrounding attributes and code cleanliness. You will also learn about a hidden tool built into your browser that will allow you to investigate the HTML of other websites. But first, let's proceed with an essential aspect of HTML tags – attributes.

## Attributes in HTML Tags – What Are They?

Attributes are additional properties that provide supplemental information about HTML tags. Essentially, they are integral to the significance and functionality of an HTML element. An `img` image tag showcases an appropriate example:

```html
<img src="URL HERE" />
```

The `src` attribute is crucial because it tells the HTML tag where to source the image to be displayed. Another valid example is an `input` tag, which by default is set to text input. However, by adding a `type` attribute, it can be adjusted to a submit button form or a number pad input. Attributes will be vital in your journey as a coder, especially when delving into more interactive languages like JavaScript or Python. For the time being, understand how they suture with a tag and always fit within the angle brackets.

As a note, they must always be AFTER the tag name as well (in this case `img`).

![](https://cdn.videotap.com/fdETTRuUItlpcRHQse7I-86.29.png)## Embracing Code Hygiene

Not unlike our daily routines, code hygiene is equally crucial. Although it's a debatable topic among developers (more on that in a future blog), here, we'll address the fundamental technique of indentation as a means of double-checking our HTML.

HTML is a paired language meaning that for every opening tag, there must be a closing tag. Adding an indentation level right after each opening tag can greatly aid in keeping track of this pairing. Your personal preference of using spaces or tabs is irrelevant, granted your tabs are set to convert into four spaces.

![](https://cdn.videotap.com/ixikAYhmj8bEV9R3ikhS-138.05.png)Most text editors allow customization for this. Opening a tag, pressing `Enter` to go to the next line, and then hitting `Tab` will indent your cursor. The next line will contain the next tag. To close a tag, reduce your indent by one and then add the closing tag. You should be able to draw a straight line on your screen from the opening to closing tag without touching any other tags in between. Sounds simple, right?

This technique enables your HTML to be clean, readable, and easily understandable by anyone who has a peek.

![](https://cdn.videotap.com/RKmuFYYZRTrE0EQD4zIa-151.png)## A Zoo of HTML in the Wild

Ever felt the curiosity to observe more examples of HTML? The internet is a vast zoo waiting for you to explore it in full. The amazing aspect is that you can reveal the HTML of any website almost instantaneously. Want to see this in action? Let's open the inspector within the developer tools, a set of hidden tools built into almost all browsers.

We'll use a Chrome-based browser for this demonstration, which includes not just Chrome but also Edge, Opera, and more. First, we navigate to a website (we'll use `samhuckaby.dev` for this purpose). We right-click anywhere on the page and select `Inspect`.

![](https://cdn.videotap.com/apZICkCzfqU3aBqCWfQy-264.13.png)And voila! You're now an undercover coder, inspecting websites. Everything you observe is the HTML, among other aspects, of the website you're on. This is the local copy the website granted your browser on visiting, meaning you can also - get ready for the secret - edit it!

Try right-clicking on an element, like the “By Sam Huckaby” tagline in the header and click “Inspect” on it. The browser will highlight that section of the HTML in the pane to the right, and you can double click the text there to edit it (clicking on another part of the pane to finish editing).

> Remember, these changes are reflected only on your local copy. They won't alter the actual website, so feel free to experiment, without worrying about any repercussions.

Experimenting with other websites and their code can be a fantastic learning experience. It can help you understand how experienced developers structure websites, gain more insights about style information, and more. That about wraps it up for now; keep exploring and happy hacking!
