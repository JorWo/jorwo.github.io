---
layout: essay
type: essay
title: "Is Bootstrap Really Better?"
# All dates must be YYYY-MM-DD format!
date: 2023-02-23
published: true
labels:
  - HTML
  - CSS
  - Bootstrap 5
---

<img width="500px" class="mx-auto" src="../img/image.jpg">

## Pure HTML and CSS is a Pain in the Butt

Writing pure HTML and CSS can sometimes be a chore. HTML is the backbone code of websites and on its own, it does not look too great. By itself, HTML looks like a document in Microsoft Word or Google Docs. It has a plain white background with underlined, bold, and italicized text along with some bullet points This is where CSS comes in; you can style HTML with CSS to add eye-catching and maybe even jaw-dropping elegance to websites. CSS is what gives a website its life and color. In CSS, designing anything is possible, as long as you have the skill to write that code. CSS itself has a high skill ceiling with many moving parts and can be tedious to write. This is where UI frameworks, or more specifically CSS frameworks come in.

## What is Bootstrap 5?

Bootstrap 5 is a popular CSS framework developed by a person working for Twitter. Bootstrap comes with a large library of premade classes for your HTML to make styling with CSS easier. You could practically never write a single line of CSS. By adding a specific class to an HTML element, such as a div, you immediately apply all the CSS associated with that keyword. You can add multiple Bootstrap classes to apply multiple CSS styling. Not only does Bootstrap come with classes to style your HTML, but it also has premade components such as buttons, navigation bars, dropdowns, modals, tooltips, image carousels, and much more. Bootstrap has a boatload of features to make styling with CSS less tedious.

## The Caveats of Bootstrap 5

As great as Bootstrap sounds, there are still some caveats. When it comes to using margin and padding, Bootstrap limits the quantifier for the amount of margin/padding at sizes 1, 2, 3, 4, and 5. This means that you cannot have a margin or padding greater than size 5 and when it comes to pixel-perfect layout positions, you cannot achieve it was a size of 1.5 or 1.25. In those cases, you are better off using pure CSS. Another caveat, albeit nitpicky, is in their large library of built-in components such as buttons and a navigation bar. When a website uses a Bootstrap component, it is easy to tell that the person used Bootstrap, without looking at the code. The components have a distinct style to them, even with their customizability by using different classes to change the look of a Bootstrap component. Sometimes it can get really confusing and difficult when you want to design a component such as a navigation bar in a certain way that it is much easier to build it yourself with pure HTML and CSS. However, since Bootstrap is built with CSS, you can modify their CSS classes directly, but it is not always so straightforward. At the very least, Bootstrap offers documentation on how to customize their classes with SASS, an extension to CSS. Bootstrap can really limit how creative and unique your website can look, but it does offer some time saved over styling with pure CSS.

## The Best Way to Utilize Bootstrap 5

In my own opinion, it is best to use Bootstrap 5 together with CSS to make styling your HTML components easier and quicker, and give you the customization and pixel-perfect measurements you want, in order to create a unique website. I think learning about SASS to customize Bootstrap classes will be very helpful in making unique websites. Lately, a new CSS framework has been on the rise, called Tailwind CSS, and it seems to offer more customizability than Bootstrap 5.
