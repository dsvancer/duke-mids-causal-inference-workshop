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

Causal inference is a fundamental problem in many fields, including economics, epidemiology, and social sciences, where understanding the causal relationships between variables is crucial for informed decision-making. In many cases, randomized controlled trials (RCTs) are not feasible or ethical, and researchers must rely on observational data to draw causal conclusions. However, observational data are often confounded by unmeasured variables, making it challenging to separate causal from non-causal relationships. In this training, we will introduce the potential outcomes framework, which provides a foundation for causal inference. We will then discuss several popular methods for estimating causal effects, including propensity score matching, inverse propensity scoring, double machine learning, and TMLE. These methods aim to remove confounding bias and identify the causal effect of a treatment or intervention on an outcome variable. We will discuss the strengths and limitations of each method, as well as provide hands-on training to their applications in real-world scenarios.

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

