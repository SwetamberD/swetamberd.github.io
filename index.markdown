---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
order: 1
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ page.title }}</title>
    <style>
        .content {
            text-align: justify;
        }
        .logo {
            float: right;
            margin-left: 20px;
            margin-top: -10px; /* Adjusts the logo's vertical alignment */
        }
        .header {
            display: flex;
            align-items: center;
        }
    </style>
</head>
<body>
    <div class="content">
        <div class="header">
            <p><strong><a href="https://srmap.edu.in/">SRM University - AP, Amaravati, Andhra Pradesh (India)</a></strong><br>
            (A part of <strong>Computational Materials and Soft Matter Physics</strong> group)</p>
            <img src="{{ site.baseurl }}/images/srmap-logo.png" alt="SRM University - AP" class="logo">
        </div>

        <p>Our research lies at the intersection of dynamical systems, chaos, and non-equilibrium physics, aiming to understand how physical systems interact with their environment.</p>
        
        <p>These interactions give rise to emergent phenomena across various scales of length, time, and energy, from the formation of chemical patterns to the functioning of biological cells essential for life.</p>
        
        <p>Our aim is to understand the fundamental physics of these processes in order to inform and guide experiments toward designing synthetic systems. To tackle these challenges, we leverage a diverse set of analytical methods and computational tools.</p>
    </div>
</body>
</html>

