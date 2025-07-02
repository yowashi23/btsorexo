---
title: Hello
layout: page
---

# Simple JS Image Classifier (BTS or EXO)

This is an example of a vision classifier using JavaScript using the [Gradio JavaScript Client](https://www.gradio.app/guides/getting-started-with-the-js-client) and API documentation found in the "Use via API" tab at the bottom of the page of the [Hugging Face Space](https://huggingface.co/spaces/yowashi/bts_or_exo). The model was trained in this [Colab notebook](https://colab.research.google.com/drive/12VwYUVl5gfWHYco2m-cQx89NnT_IDLpp). As you can see in the finetuning output, the error rate converges at 0.25 so this model is by no means good. Goes to show that the task of distinguishing BTS from EXO is not easy.

The original examples of vision classifiers do not work anymore because of changes in how to use the Hugging Face API, so this is a new example that works with the current API (25/07/01). This website is deployed using GitHub Pages. Out of the GitHub Pages supported themes listed [here](https://pages.github.com/themes/), I liked the aesthetic of the [Minima](https://github.com/jekyll/minima) theme for writers the most but I used the [Tactile](https://github.com/pages-themes/tactile) theme for this example. The html files `2multi.html` and `3parallel.html` can be ignored (25/07/01). Note to myself: GitHub Pages take a while to update even after the GitHub Action completes.