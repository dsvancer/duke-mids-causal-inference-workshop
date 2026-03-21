# Welcome

Hosted by Duke University, Duke campus, Gross Hall

<br>

<p align="center">
<img 
  src="/assets/mids_logo_white.png" 
  alt="Base Binder" 
  style="width:350px;height:auto;"
>
</p>

# About the Workshop

**Abstract**

Causal inference is a fundamental problem in many fields, including economics, epidemiology, and social sciences, where understanding the causal relationships between variables is crucial for informed decision-making. In many cases, randomized controlled trials (RCTs) are not feasible or ethical, and researchers must rely on observational data to draw causal conclusions. However, observational data are often confounded by unmeasured variables, making it challenging to separate causal from non-causal relationships. 

<br>

In this workshop, we will introduce the potential outcomes framework, which provides a foundation for causal inference. We will then discuss several popular methods for estimating causal effects, including propensity score matching, inverse propensity weighting, and double machine learning. These methods aim to remove confounding bias and identify the causal effect of a treatment or intervention on an outcome variable. 

<br>

We will discuss the strengths and limitations of each method, as well as provide hands-on training to their applications in real-world scenarios using Python.

## Launching Workshop Materials
Click on the Binder button or link below to build your personal copy of the workshop material and code along with us!

[![Binder](http://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dsvancer/duke-mids-causal-inference-workshop/main?urlpath=lab/tree/welcome.ipynb)


OR access the material at the following URL:

<a 
  href="https://mybinder.org/v2/gh/dsvancer/duke-mids-causal-inference-workshop/main?urlpath=lab/tree/welcome.ipynb" target="_blank">
  https://mybinder.org/v2/gh/dsvancer/duke-mids-causal-inference-workshop/main?urlpath=lab/tree/welcome.ipynb
</a>

### Cloning this Workshop and Creating a Virtual Environment (MacOS)
With VSCode or your Pythong IDE of choice, clone this public repository and download python 3.13 or higher if needed.

In the terminal, navigate to the main folder `duke-mids-causal-inference-workshop` and then run the following:
- python3.13 -m venv .venv
- source .venv/bin/activate
- pip install --upgrade pip
- pip install -r binder/requirements.txt

## Learning More About Causal Inference
Below are free online resources to build foundational knowledge of causal reasoning and applied causal ML. I highly recommend them!
- [The Effect](https://theeffectbook.net/)
  - **The Effect** is a book intended to introduce the concepts of research design and causality in the context of observational data. The book is written in an intuitive and approachable way and doesn’t overload on technical detail. It focuses heavily on causal reasoning, which is the most important skill to develop before jumping into machine learning and statistical modeling
- [Causal Inference for the Brave and True](https://matheusfacure.github.io/python-causality-handbook/landing-page.html)
  - A light-hearted yet rigorous approach to learning impact estimation and sensitivity analysis. Everything in Python and with as many memes as can be found
- [Causal Artifical Intelligence](https://causalai-book.net/)
  - This textbook offers a comprehensive treatment of the principles, algorithms, and tools necessary for building causally intelligent systems. It bridges probability theory, causal inference, machine learning, and decision-making under uncertainty, providing a unified roadmap for addressing fundamental challenges in modern AI, including safety, generalization, robustness, and explainability
- [Modern Causal Inference](https://alejandroschuler.github.io/mci/introduction-to-modern-causal-inference.html)
  - We're not in Kansas anymore...




