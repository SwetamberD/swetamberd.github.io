---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
order: 1
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
            right: 0;
            top: 0;
            margin-top: 20px;
            width: 150px; /* You can adjust the size of the logo */
        }
    </style>
</head>
<body>
    <div class="content">
        <p><strong><a href="https://srmap.edu.in/">SRM University - AP, Amaravati, Andhra Pradesh (India)</a></strong><br>
        (A part of <strong>Computational Materials and Soft Matter Physics</strong> group)</p>

        <p>Our research lies at the intersection of dynamical systems, chaos, and non-equilibrium physics, aiming to understand how physical systems interact with their environment. These interactions give rise to emergent phenomena across various scales of length, time, and energy, from the formation of chemical patterns to the functioning of biological cells essential for life. Our aim is to understand the fundamental physics of these processes in order to inform and guide experiments toward designing synthetic systems. To tackle these challenges, we leverage a diverse set of analytical methods and computational tools.</p>

        <img src="{{ site.baseurl }}/images/srmap-logo-2.png" alt="SRM University - AP" class="logo">
    </div>
</body>
</html>


