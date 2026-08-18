# Kagaz

**https://angadseth.github.io/kagaz/**

PDF tools that run entirely in your browser. Nothing is uploaded, nothing is stored —
close the tab and it is gone. The counter at the foot of every page measures bytes
uploaded and requests to other origins, and both stay at zero.

This repository holds **only the built site**. It is republished from a private source
repository on every change, as a fresh commit each time, so there is nothing here to
read but compiled output and no history worth walking.

`.nojekyll` is load-bearing: without it GitHub Pages hands the site to Jekyll, which
ignores every directory beginning with an underscore — including `_astro/`, where all
the JavaScript and CSS lives. Every page would load and nothing on it would work.
