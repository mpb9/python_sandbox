# Python Sandbox

## Set-up :gear:

### Create Environment

1. `mkdir python_sandbox`
2. `cd python_sandbox`
3. `pip install virtualenv`
4. `virtualenv sandbox_env`

### Start/Stop

Start: `source sandbox_env/bin/activate`
Stop: `deactivate`

### Install Packages

#### Via command line

`pip install [package]`

#### Via requirements.txt

1. Create file based on current packages

    `pip freeze > requirements.txt`

2. Add packages to requirements.txt using syntax `PACKAGE_NAME==VERSION_NUMBER`

    ex:

    ```txt
    requests==2.32.3
    scipy==1.14.1
    ...
    ```

3. Add/update packages in virtual environment

    `pip install -r requirements.txt`

## Packages :toolbox:

***italics* = no first-hand experience**

### Essentials

- **[pandas](https://github.com/pandas-dev/pandas)** - `dataframe` and `series` types
- **[numpy](https://github.com/numpy/numpy)** - `array` type
- **[requests](https://github.com/psf/requests)** - simplified HTTPS requests, functions for interacting with web APIs and managing HTTP responses
- **[scipy](https://github.com/scipy/scipy)** - functions focused on mathematical computing with features around optimization, signal processing, and interpolation

### Web Applications

- **[flask](https://flask.palletsprojects.com/)** - micro web framework
- *[taipy](https://github.com/Avaiga/taipy)* - simplest app builder for front-end (GUI) and ML/Data pipeline(s)
- *[streamlit](https://github.com/streamlit/streamlit)* - quickly transform scripts into web apps

### Data Visualization

- **[matplotlib](https://github.com/matplotlib/matplotlib)** - main widget library, allows the plotting of 2D graphs with a wide range of chart types and also allows for significant customization
- *[bokeh](https://github.com/bokeh/bokeh)* - focuses on interactive charts
- **[seaborn](https://github.com/mwaskom/seaborn)** - while matplotlib has an emphasis on preciseness and simplicity, seaborn has real added value in their sleek visuals while creating complex statistical visualizations

### Web Scraping

- **[beautifulsoup4](https://www.crummy.com/software/BeautifulSoup/#Download)** - parsing HTML and XML documents *(beginner)*
- *[selenium](https://selenium-python.readthedocs.io/)* - when you need to handle user interactions and JavaScript-heavy websites *(intermediate)*
- **[scrapy](https://github.com/scrapy/scrapy)** - large-scale, concurrent data extraction *(advanced)*

### Machine Learning

- **[scikit-learn](https://github.com/scikit-learn/scikit-learn)** - algorithms from clustering to classification, includes functions for everything from data validation to data selection
- **[xgboost](https://github.com/dmlc/xgboost)** - efficient results for regression and classification algorithms
- *[catboost](https://github.com/catboost/catboost)* - deals with datasets displaying mostly categorical data
- *[tensorflow](https://github.com/tensorflow/tensorflow)* - deep-learning library specializing in Natural Language Processing and image classification
- *[pytorch](https://github.com/pytorch/pytorch)* - deep-learning with a more significant focus on Natural Language Processing and a more Pythonic feel, reducing the learning curve known to be steep for TensorFlow
- *[keras](https://pypi.org/project/keras/)* - simplifies the creation and training of deep learning models with a high-level, user-friendly API

### Dates and Times

- **[datetime](https://docs.python.org/3/library/datetime.html)** - essential for dealing with any DateTime format
- *[pendulum](https://github.com/sdispater/pendulum)* - features necessary for more advanced date and time handling, improved time zone support

### Imaging

- *[pillow](https://pypi.org/project/Pillow/)* - several standard procedures for image manipulation
- *[opencv](https://github.com/opencv/opencv)* - various algorithms around real-time computer vision

### Testing

- *[pytest](https://github.com/pytest-dev/pytest)* - framework that simplifies test writing and execution
- *[unitest](https://docs.python.org/3/library/unittest.html)* - Python’s built-in testing framework, featuring: test discovery, support for fixtures, effortless organization, and management of test suites

### Code Analysis

- *[ruff](https://github.com/astral-sh/ruff)* - fastest option to equivalent linters

## Resources :link:

- [awesome-python](https://github.com/vinta/awesome-python)
- [Top 42 Python Libraries](https://dev.to/taipy/top-42-python-libraries-you-need-to-know-1omo)
- [Python requirements.txt Explained](https://www.freecodecamp.org/news/python-requirementstxt-explained/)
