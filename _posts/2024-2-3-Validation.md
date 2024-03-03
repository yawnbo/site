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
    This website is really weird when dealing with validation, alot of the errors output are just info errors that are caused by how liquid and ruby handle the provided html, (liquid likes to close everything with a /> so that makes up ~15 errors)

<h4>
  Note I have no way to fix how liquid handles html so "info" errors will be shown on all pages.
</h4>

<div class="container">
    <div class="column">
        <h2>Column 1</h2>
        <h3>Home</h3>

        <img src="/assets/images/validation/home.png" alt="home validation" height="400">

        <h3>About me validation</h3>

        <p>
        All ones past this include errors that say they require headings, even though if you look into the code, they all clearly have headings. Could maybe be due to html validator running through liquid before html loading? Im not sure
        </p>

        <img src="/assets/images/validation/about.png" alt="about me html" height="400">

        <h3>Artifact</h3>

        <img src="/assets/images/validation/artifacts.png" alt="artifacts html" height="400">

        <h3>Contact Me</h3>

        <img src="/assets/images/validation/contact.png" alt="contact html" height="400">

        <h3>Coursework</h3>

        <img src="/assets/images/validation/coursework.png" alt="coursework html" height="400">

        <h3>Creative Page</h3>

        <img src="/assets/images/validation/creative_page.png" alt="creative html" height="400">

        <h3>Modules</h3>

        <img src="/assets/images/validation/modules.png" alt="modules html" height="400">
    </div>
    <div class="column">
        <h2>Column 2</h2>
        <p>This is some text in column 2.</p>
        <img src="image2.jpg" alt="Image 2">
    </div>
</div>


