---
title: Hello
layout: page
---

# Simple JS Image Classifier (BTS or EXO)

This is an example of a vision classifier using JavaScript using the [Gradio JavaScript Client](https://www.gradio.app/guides/getting-started-with-the-js-client) and API documentation found in the "Use via API" tab at the bottom of the page of the [Hugging Face Space](https://huggingface.co/spaces/yowashi/bts_or_exo). The model was trained in this [Colab notebook](https://colab.research.google.com/drive/12VwYUVl5gfWHYco2m-cQx89NnT_IDLpp). As you can see in the finetuning output, the error rate converges at 0.25 so this model is by no means good. Goes to show that the task of distinguishing BTS from EXO is not easy.

The original examples of vision classifiers do not work anymore because of changes in how to use the Hugging Face API, so this is a new example that works with the current API (25/07/01). This website is deployed using GitHub Pages. Out of the GitHub Pages supported themes listed [here](https://pages.github.com/themes/), I liked the aesthetic of the [Minima](https://github.com/jekyll/minima) theme for writers the most but I to use [Tactile](https://github.com/pages-themes/tactile) theme for this example and it didn't work (25/07/01). The html files `2multi.html` and `3parallel.html` can be ignored (25/07/01).

Note to myself: GitHub Pages take a while to update even after the GitHub Action completes. Sometimes this may be because caching. It may help to add an easter egg every commit.
TODO: ["As of 2023, BTS is the best-selling musical act in South Korean history according to the Circle Chart, having sold in excess of 40 million albums."](https://en.wikipedia.org/wiki/BTS). It would be a good idea to have a model that could tell the members apart. A multiclass classification model like the dog breeds model would work. I'm curious to see how well the model does.

Chapter 2 of the book asks us to write our first blog post about our deep learning journey.
"What's surprised you? What opportunities do you see for deep learning in your field (or a domain you're interested in?) What obstacles do you see?"
2025-07-05:
The ease of getting a model POC deployed with just a few lines of code surprised me. The material has been suprisingly engaging as well and I think that can be attributed to the top-down approach of teaching. I am learning to think of fun personal problems again - a skill that I haven't exercised in a while. If my field was music I would see the opportunity of using deep learning to recommend music to people. I find the idea of an objectively good recommendation not necessarily being a useful recommendation interesting. How do you know whether a customer would have discovered music without the recommendation? I really wonder what data at Spotify looks like. The obstacle of interpretability is one that I find hard to navigate. I think there will continue to be a big reliance on showing trends in outputs of models but not necessarily knowing EXACTLY why those outputs are being outputted given the input.

If music recommendations worked really really well then people would discover music that they wouldn't have otherwise. Essentially a music recommender would be doing the job of a person at a record store. There would be no positive feedback loops that would result in a customer's music taste becoming extremely refined.
