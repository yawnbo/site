---
layout: post
title: Validation
subtitle:
author: yawnbo
categories: midterm
banner:
  image:
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

<h2>Validation</h2>
<p>
    This website is really weird when dealing with validation, alot of the errors output are just info errors that are caused by how liquid and ruby handle the provided html, (liquid likes to close everything with a /> so that makes up ~15 errors) and others are really weird to fix because I have no clue how to. For example...
<p>

  <img src="/assets/images/validation/unclosed_span.png" alt="Unclosed span element" height="400">

<p>
  This code shows up with the error "Element div not allowed as child of element span in this context. (Suppressing further errors from this subtree.)" The problem is that I can't change chage the div to a span without the list breaking, and I can't change the outer span that contains the above code because it is in a label element itself. If you have a suggestion I will gladly implement it.
</p>

<h3>Home validation</h3>
<p>
  
