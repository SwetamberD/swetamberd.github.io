---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: "About"
permalink:/About
name: "About"
weight: 1
---

<!DOCTYPE html>  <html lang="en">
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
            right: 4px;
            top: 10px;
            width: 160px;
        }
        a {
            color: #3471eb;
            text-decoration: none;
        }
        .news-links {
            margin-top: 20px;
        }
        .news-item {
            max-width: 800px;
        }
        .news-date {
            width: 200px;
            text-align: left;
            font-weight: bold;
        }
        .news-link {
            flex-grow: 1;
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
            <h2 style="color: green;">News</h2>
            <div class="news-item">
                <div style="display: flex; align-items: center; gap: 5px;">
                    <div class="news-date">February 13, 2025</div>
                    <div class="news-link">
                        <a href="https://arxiv.org/abs/2502.09361" target="_blank">
                            New Preprint available
                        </a>
                    </div>
                </div>

                <div style="display: flex; align-items: center; gap: 5px; margin-top: 10px;">
                    <div class="news-date">January 6, 2025</div>
                    <div class="news-link">
                        <a href="https://iopscience.iop.org/article/10.1088/1751-8121/ad8f06/meta" target="_blank">
                            Paper published in <em>J. Phys. A: Math. Theor.</em>
                        </a>
                    </div>
                </div>
            </div>
        </div>

    </div>
</body>
</html>