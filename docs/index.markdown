---
layout: page
title: "About"
permalink: /About
name: "About"
weight: 1
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=0.8">
    <title>About</title>
    <style>
        .content {
            text-align: justify;
            hyphens: auto;
            position: relative;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        .logo {
            float: right;
            margin-left: 10px;
            width: 160px;
        }
        a {
            color: #3471eb;
            text-decoration: underline;
        }
        .news-links {
            margin-top: 20px;
        }
        .news-links h2 {
            color: #663300;
            margin-bottom: 15px;
        }
        .news-item {
            max-width: 600px;
            margin-top: 10px;
        }
        .news-item > div {
            display: flex;
            align-items: center;
            gap: 15px; /* Increased gap for more space between date and entry */
        }
        .news-date {
            width: 100px; /* Adjusted for alignment */
            text-align: left;
            font-weight: bold;
        }
        .news-link {
            flex-grow: 1;
        }
        .news-link a {
            color: #0066cc;
            text-decoration: none;
        }
        .news-link a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="content">
        <p><img src="{{ site.baseurl }}/images/srmap-logo-2.png" alt="SRM University - AP" class="logo"></p>
        <p style="font-size: 22px; font-weight: bold;">Dynamical Systems Theory Group</p>
        <p>at <strong><a href="https://srmap.edu.in/"> SRM University - AP, Amaravati (India)</a></strong></p>

        <p>Our research lies at the intersection of dynamical systems and non-equilibrium physics,
        aiming to understand how physical systems interact with their environment.
        These interactions give rise to emergent phenomena across various scales of length, time, and energy,
        from the formation of self-assembly patterns in chemical reactions to the functioning of
        biological cells essential for life. Our aim is to understand the dynamical mechanisms
        of these processes in order to inform experiments toward
        designing synthetic systems. To tackle these challenges, we leverage
        a diverse set of analytical methods and computational tools.</p>

        <p><span style="color: #006600;"> We currently have bachelor's, master's, and PhD positions available. If interested, please reach out to discuss potential projects.</span></p>

        <div class="news-links">
            <h2>News</h2>

            <div class="news-item">
                <div>
                    <div class="news-date">May 5</div>
                    <div class="news-link">
                        <a href="https://journals.aps.org/pre/" target="_blank">
                            Paper accepted in <em>Phys. Rev. E</em>
                        </a>
                    </div>
                </div>
            </div>

            <div class="news-item">
                <div>
                    <div class="news-date">March 7</div>
                    <div class="news-link">
                        <a href="https://patents.google.com/" target="_blank">
                            New patent published
                        </a>
                    </div>
                </div>
            </div>

            <div class="news-item">
                <div>
                    <div class="news-date">Feb 13</div>
                    <div class="news-link">
                        <a href="https://arxiv.org/abs/2502.09361" target="_blank">
                            New Preprint available
                        </a>
                    </div>
                </div>
            </div>

            <div class="news-item">
                <div>
                    <div class="news-date">Jan 6</div>
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