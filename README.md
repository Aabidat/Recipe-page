# Jollof Rice Recipe Page

In this assignment, i built a recipe page for Jollof Rice, built with HTML and CSS as part of building my CSS foundation at Hackerboost.

## Overview

I built this project to practice organizing different types of content such as text, images, lists, and tables, and to use CSS to create a clean, professional, and appetizing layout. I chose Jollof Rice because it is a dish I love and one that is loved across West Africa.


## Features

- Semantic HTML structure using `<article>`, `<header>`, `<section>`, `<footer>`, `<ul>`, `<ol>`, and `<table>` elements
- A custom warm color palette built with CSS variables, including a cream background, burgundy headings, and golden amber highlights
- A nutrition table with clean row dividers and a soft box shadow
- Entrance animations that make each section fade up into place as the page loads, plus a separate fade and zoom animation on the hero image
- Responsive spacing using `rem` units throughout

## Extra Features I added

- Entrance animations on page load using CSS `@keyframes`, with each section fading in at a staggered delay
- A subtle box shadow on the nutrition table for depth

## What I Learned

This project taught me how to work with `rem` units and how they scale relative to the root font size, which makes spacing and typography more consistent and accessible than fixed pixel values. I also learned a lot about color theory, particularly how to choose colors that sit close together on the color wheel so a palette feels cohesive rather than clashing. On top of that, I got much more comfortable writing CSS keyframes, learning that `animation-delay` only works when paired with an actual `animation` property, and that the `from` and `to` states in a keyframe need to be in the correct order for the animation to play the way I intend.

## Challenges

The most challenging part of this project was getting my CSS animations to work correctly. I ran into several small but important mistakes along the way, such as forgetting the "s" in `forwards`, setting `animation-delay` without an `animation` property, and writing my keyframe states backwards so elements faded out instead of in. Debugging these one at a time taught me to read animation syntax much more carefully.

## Built With

- HTML5
- CSS3
- Google Fonts — Playfair Display and Lato

