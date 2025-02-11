---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: "About"
permalink:/About/
name: "About"
weight: 1
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=0.5">
    <style>
        .content {
            text-align: justify;
            position: relative;
        }
        .logo {
            position: absolute;
            right: 4px; /* Slightly shifts the logo left */
            top:   10px; /* Slightly shifts the logo up */
            width: 160px; /* Adjust logo size */
        }
        .news-links {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="content">
        <p><img src="{{ site.baseurl }}/images/srmap-logo-2.png" alt="SRM University - AP" class="logo"></p>
        <p style="font-size: 24px; font-weight: bold;">Dynamical Systems Theory Group</p>
        <p>at <strong><a href="https://srmap.edu.in/"> SRM University - AP, Amaravati (India)</a></strong></p>

        <p>Our research lies at the intersection of dynamical systems and non-equilibrium physics,
        aiming to understand how physical systems interact with their environment.
        These interactions give rise to emergent phenomena across various scales of length, time, and energy,
        from the formation of self assembly patterns in chemical reactions to the functioning of
        biological cells essential for life. Our aim is to understand the dynamical mechanism
        of these processes in order to inform and guide experiments toward
        designing synthetic systems. To tackle these challenges, we leverage
        a diverse set of analytical methods and computational tools.</p>

<div class="news-links">
    <h3>News</h3>
    <div class="news-item" style="display: flex; justify-content: space-between; max-width: 600px;">
        <div class="news-date" style="min-width: 150px;">February 14, 2025</div>
        <div class="news-link"><a href="https://arxiv.org/abs/your-paper-id">New paper on the arxiv (under review)</a></div>
    </div>
    <div class="news-item" style="display: flex; justify-content: space-between; max-width: 600px;">
        <div class="news-date" style="min-width: 150px;">January 6, 2025</div>
        <div class="news-link"><a href="https://iopscience.iop.org/article/10.1088/1751-8121/ad8f06/meta">Paper published</a></div>
    </div>
</div>