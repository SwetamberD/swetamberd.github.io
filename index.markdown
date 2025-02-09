---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
order: 1
---
---
layout: page
order: 1
title: "SRM University - AP Research"
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=0.5">
    <title>{{ page.title }}</title>
    <style>
        .content {
            text-align: justify;
            position: relative;
        }
        .logo {
            position: absolute;
            left: 0;
            top: -20px; /* Adjusts the logo's vertical position */
            margin-left: 20px; /* Shifts the logo slightly to the left */
            width: 150px; /* Adjust logo size */
        }
    </style>
</head>
<body>
    <div class="content">
        <p><strong><a href="https://srmap.edu.in/">SRM University - AP, Amaravati, Andhra Pradesh (India)</a></strong><br>
        (A part of <strong>Computational Materials and Soft Matter Physics</strong> group)</p>

        <p>Our research lies at the intersection of dynamical systems, chaos, and non-equilibrium physics, aiming to understand how physical systems interact with their environment. These interactions give rise to emergent phenomena across various scales of length, time, and energy, from the formation of chemical patterns to the functioning of biological cells essential for life. Our aim is to understand the fundamental physics of these processes in order to inform and guide experiments toward designing synthetic systems. To tackle these challenges, we leverage a diverse set of analytical methods and computational tools.</p>

        <p>Check out some of our recent Jekyll posts: 
            <ul>
                <li><a href="{{ site.baseurl }}/posts/post1.html">Post 1</a></li>
                <li><a href="{{ site.baseurl }}/posts/post2.html">Post 2</a></li>
                <li><a href="{{ site.baseurl }}/posts/post3.html">Post 3</a></li>
            </ul>
        </p>

        <img src="{{ site.baseurl }}/images/srmap-logo.png" alt="SRM University - AP" class="logo">
    </div>
</body>
</html>



