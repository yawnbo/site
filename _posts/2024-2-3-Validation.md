---
layout: post
title: Validation
subtitle:
author: yawnbo
categories: midterm
banner:
  opacity: 0.618
  background: "#000"
  height: "100vh"
  min_height: "38vh"
  heading_style: "font-size: 4.25em; font-weight: bold; text-decoration: underline"
  subheading_style: ""
tags: 
top: 1
sidebar: []
---
<style>
    .container {
        display: flex;
    }

    .column {
        flex: 1;
        padding: 20px;
    }

    .column img {
        max-width: 100%;
        height: auto;
    }
</style>
<h2>Validation</h2>
<p>
    This website is really weird when dealing with validation, alot of the errors output are just info errors that are caused by how liquid and ruby handle the provided html, (liquid likes to close everything with a /> so that makes up ~15 errors) and others are really weird to fix because I have no clue how to. For example...
<p>

  <img src="/assets/images/validation/unclosed_span.png" alt="Unclosed span element" height="400">

<p>
  This code shows up with the error "Element div not allowed as child of element span in this context. (Suppressing further errors from this subtree.)" The problem is that I can't change chage the div to a span without the list breaking, and I can't change the outer span that contains the above code because it is in a label element itself. If you have a suggestion I will gladly implement it.
</p>

<h4>
  Note I have no way to fix how liquid handles html so "info" errors will be shown on all pages, along with the above mentioned div element, pictures will include anything below these.
</h4>

<div class="container">
    <div class="column">
        <h2>Column 1</h2>
        <h3>Home validation</h3>

        <img src="/assets/images/validation/home.png" alt="home validation" height="400">

        <h3>About me validation</h3>

        <p>
        This one has the errors "Section lacks heading. Consider using h2-h6 elements" because the website loads the page with a "post" framework and I think it want's headers 
        </p>

        <img src="/assets/images/validation/about.png" alt="about me validation" height="400">

    </div>
    <div class="column">
        <h2>Column 2</h2>
        <p>This is some text in column 2.</p>
        <img src="image2.jpg" alt="Image 2">
    </div>
</div>


