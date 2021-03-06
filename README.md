# math_class

### Background

Welcome to the landing page of the _Contently Math Class_! The hope here is that we can all have fun while diving into some of the knowledge and technique that allows for thinking _quantitatively_.

To achieve this, we will make use of the _Python programming language_. Please note that this is not meant to be a "how to write Python" class. I.e. our focus will be not on the code but on the numbers, and we will generally write simplistic representations of our desired logic. That said, you will gain exposure to writing analytical Python through these courses. 

### Tools

Each lesson's content will be delivered in the form of a _Jupyter notebook_. This is a browser-based, interactive coding tool that allows you to keep code, charts, and text in the same place. _GitHub_ will be used for distributing these notebooks - you can in fact view the notebooks right through GitHub but you'll have to run Jupyter locally if you wish to interact with them. If you have any questions on how to use Jupyter, please don't hesitate to reach out at any time. I imagine you will pick this up pretty quickly.

That said, it's hard to beat a good 'ol fashioned pen and paper for math, and if you'd like to participate in this way you should feel free to do so! This will work for many, though not all, of the classes. You're welcome to try to follow along in another language, too. Note that this would likely leave you on your own with respect to implementation details, which could become problematic as we get farther along. But you should feel free to experiment as you wish - you can always come back to working in Python. Please see [here](https://github.com/lermana/math_class/blob/master/python_resources.md) for a list of resources to help you further your Python, and feel free to update it with your thoughts and recommendations!

If you do wish to use Python, I would recommend using at least version 3.6. You will also need to install the `jupyter` package. Additionally, the following analytical libraries would be helpful to have ready to go:
- `numpy`
- `scipy`
- `matplotlib`
- `pandas`
- `sklearn`
- `statsmodels`
- `requests` (this is for HTTP - always handy to have installed)

The simplest approach for folks who don't already have a good Python setup is likely to download and install the _Anaconda_ Python distribution, which will include all of these packages and also many others. You can download that [here](https://www.google.com/url?q=https%3A%2F%2Frepo.continuum.io%2Farchive%2FAnaconda3-2018.12-MacOSX-x86_64.pkg&sa=D&ust=1547655216810000&usg=AFQjCNE5LRmMSVTwl_SzMrp3iGGaA-Maaw). 

Otherwise, once Python 3.6+ is installed, you can either run `pip install -r requirements.txt` from within this directory or go ahead and just individually install each of the above packages.

### Docker Setup (Thanks, Seth!)
If you are running [Docker](https://www.docker.com/), you can use the `start` command from the terminal to simply load the notebook without installing dependencies or python locally.

```sh
$ ./start
```

After the Docker images are set up, you will see a url listed at the end similar to this:

```
Copy/paste this URL into your browser when you connect for the first time,
    to login with a token:
        http://(acd90c62cec2 or 127.0.0.1):8888/?token=9647b38f8622f7f33ccf970ecee3a0177e37d3e42ccb2932
```

Your url is most likely:
`http://localhost:8888/?token=<that token above>`


### Syllabus

1. [Numbers and Operators](https://github.com/contently/math_class/blob/master/numbers_and_operators.ipynb)
2. [Basic Probability](https://github.com/contently/math_class/blob/master/basic_probability.ipynb)
3. [Functions](https://github.com/contently/math_class/blob/master/functions.ipynb)
4. [Calculus: Derivatives](https://github.com/contently/math_class/blob/master/calculus_derivatives.ipynb)
5. [Limits](https://github.com/contently/math_class/blob/master/limits.ipynb)
6. [Calculus: Integrals](https://github.com/contently/math_class/blob/master/calculus_integrals.ipynb)
7. [Basic Data Science](https://github.com/contently/math_class/blob/master/data_science_101.ipynb) (read: Data Science with Python)
