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
    liquid likes to close everything with a /> so that makes up ~15 errors and I have no way of fixing this without a liquid rewrite.
</p>

<div class="container">
    <div class="column">
        <h2>HTML</h2>
        <h3>Home</h3>

        <img src="/site/assets/images/validation/home.png" alt="home validation" height="400">

        <h3>About me validation</h3>

        <p>
            Warning errors will not be fixed due to an article class being inside of them that is suited better for sections and loaded through a 3rd party struct.
        </p>

        <img src="/site/assets/images/validation/about.png" alt="about me html" height="400">

        <h3>Artifact</h3>

        <img src="/site/assets/images/validation/artifacts.png" alt="artifacts html" height="400">

        <h3>Contact Me</h3>

        <img src="/site/assets/images/validation/contact.png" alt="contact html" height="400">

        <h3>Coursework</h3>

        <img src="/site/assets/images/validation/coursework.png" alt="coursework html" height="400">

        <h3>Creative Page</h3>

        <img src="/site/assets/images/validation/creative_page.png" alt="creative html" height="400">

        <h3>Modules</h3>

        <img src="/site/assets/images/validation/modules.png" alt="modules html" height="400">

        <h3>Animation and Music</h3>

        <img src="/site/assets/images/validation/animation.png" alt="animation html" height="400">
    </div>
    <div class="column">
        <h2>CSS</h2>
        <h3>Home</h3>

        <p>
          The CSS says it has an error because swap isn't a property, which is correct for basic css, but this website uses SCSS which uses server side functions that can be used. Hence the feature of switching the theems from dark to light. 
        </p>
        <img src="/site/assets/images/validation/homeCSS.png" alt="Home css" height="400">

        <h4>All pages use the same exact CSS because everything is built off the main file. I believe the only page that uses any other CSS is this page with the style tags, so here is this page verifying CSS</h4>

        <h3>Extra page</h3>
        <img src="/site/assets/images/validation/validationCSS.png" alt="Validation css" height="400">
    </div>
</div>


