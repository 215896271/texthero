<p align="center">
   <a href="https://github.com/jbesomi/texthero/stargazers">
    <img src="https://img.shields.io/github/stars/jbesomi/texthero.svg?colorA=orange&colorB=orange&logo=github"
         alt="Github stars">
   </a>
   <a href="https://pypi.org/search/?q=texthero">
      <img src="https://img.shields.io/pypi/v/texthero.svg?colorB=brightgreen"
           alt="pip package">
   </a>
   <a href="https://pypi.org/project/texthero/">
      <img alt="pip downloads" src="https://img.shields.io/pypi/dm/texthero">
   </a>
   <a href="https://github.com/jbesomi/texthero/issues">
        <img src="https://img.shields.io/github/issues/jbesomi/texthero.svg"
             alt="Github issues">
   </a>
   <a href="https://github.com/jbesomi/texthero/blob/master/LICENSE">
        <img src="https://img.shields.io/github/license/jbesomi/texthero.svg"
             alt="Github license">
   </a>   
</p>

<p align="center">
    <img src=".github/logo_v1.0.png">
</p>

<p align="center">Text preprocessing, representation and visualization from zero to hero</p>

<p align="center">
    <img src=".github/demo.gif?raw=true" width="700">
</p>

<p align="center">
  <a href="#zero-to-hero">From zero to hero</a> •
  <a href="#installation">Installation</a> •
  <a href="#getting-started">Getting Started</a> •
  <a href="#documentation">Documentation</a> •
  <a href="#contributions">Contributions</a>
</p>


<h2 align="center">From zero to hero</h2>

Texthero is a python toolkit for quick handling of text data. Texthero is concise, simple to learn and integrates smoothly with Pandas.

Given a Pandas DataFrame with one or more _text_ columns, texthero help to preprocess the text data, map it into vectors using different algorithms and models and visualize it on screen.



<h2 align="center">Installation</h2>

```bash
pip install texthero
```

> ☝️Under the hoods, texthero make use of multiple NLP/mL toolkit such as Gensim, NLTK, SpaCy and Sklearn. You don't need to install them separately; pip will take care of that.

<h2 align="center">Getting started and examples</h2>

<h3>1. Clustering of TF-IDF vectors</h3>

```python
import texthero.texthero as hero

```

<h3>2. Most common words and top TF-IDF words</h3>

```python
import texthero.texthero as hero

```

<h3>3. Transformers representation and visualization [soon]</h3>

```python
import texthero.texthero as hero
```

<h2 align="center">Documentation</h2>

The way texthero is structured and his documentation follow the same principles of texthero: to provide a simple tool to text data handling. We put our best to keep the code concise, simple to read and understand.

Texthero is composed of three main components; preprocessing.py, representation.py and visualization.py.

<h3>⚒️Preprocessing</h3>

**Job:** prepare the **text** data for further analysis.

Exhaustive documentation: (preprocessing)[https://jbesomi.github.io/texthero/preprocessing.html]

<h3>📒Representation</h3>

**Job:** map text data into vectors and do dimensionality reduction.

Supported representation algorithms:
1. TF-IDF, Term Frequency–Inverse Document Frequency
2. TF, term frequency [soon]
3. Word2Vec from Gensim [soon]
4. GloVe [soon]
5. Transformers [soon]

Supported dimensionality reduction algorithms:
1. PCA, Principal Component Analysis
2. NMF, non-negative matrix factorization

Exhaustive documentation:

<h3>🔮Visualization</h3>

**Job:** collection of functions to both summarize the main facts regarding the data and visualize the results. This part is very opinionated and ideal for anyone that needs a quick solution to visualize on screen the text data for instance during a text exploratory data analysis (EDA).

Most common functions:
   - Text scatterplot. Handy when coupled with dimensionality reduction algorithms such as pca.
   - Most common words
   - Most common words between two entities [soon]

Exhaustive documentation:

<h2 align="center">Contributions</h2>

Any help, feedback and contribution are very welcome. You can simply fork this repository and [open an issue](issues).
