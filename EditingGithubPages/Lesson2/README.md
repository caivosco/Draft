Using web sites in GitHub
==========================

This project aims try different options of github's sites.

For example, The following text is a hiperlink toward must-read Machine Learning book
[Hands-on Machine Learning with Scikit-Learn and TensorFlow](http://shop.oreilly.com/product/0636920052289.do):

[![book](http://akamaicovers.oreilly.com/images/0636920052289/cat.gif)](http://shop.oreilly.com/product/0636920052289.do)

Simply open the [Jupyter](http://jupyter.org/) notebooks if you are interested in:

* Using [jupyter.org's notebook viewer](http://nbviewer.jupyter.org/github/ageron/handson-ml/blob/master/index.ipynb)
    * note: [github.com's notebook viewer](https://github.com/ageron/handson-ml/blob/master/index.ipynb) also works but it is slower and the math formulas are not displayed correctly,
* or by cloning this repository and running Jupyter locally. This option lets you play around with the code. In this case, follow the installation instructions below.

# Installation

First, you will need to install [git](https://git-scm.com/), if you don't have it already.

Next, clone this repository by opening a terminal and typing the following commands:

    $ cd $HOME  # or any other development directory you prefer
    $ git clone https://github.com/ageron/handson-ml.git
    $ cd handson-ml
    $ clear

If you want to go through chapter 16 on Reinforcement Learning, you will need to [install OpenAI gym](https://gym.openai.com/docs) and its dependencies for Atari simulations.

I suggest check my program on Reinforcement Learning based on Vidhya Article.

[Program of caivosco](https://github.com/caivosco/DL_1/blob/master/RL_Vidhya.ipynb)

[Check another file in this directory](https://github.com/caivosco/caivosco.github.io/blob/master/_config.yml)


If you are familiar with Python and you know how to install Python libraries, go ahead and install the libraries listed in `requirements.txt` and jump to the [Starting Jupyter](#starting-jupyter) section. If you need detailed instructions, please read on.
