# Canadian-Banks-Stock-Market-Analysis

<br/>
<p align="center">
  <h3 align="center">Tokyo stock exchange analysis and prediction.</h3>

  <p align="center">
   EDA and feature engineering along with Machine Learning modelling using LightGBM for predicting the returns on different stocks.
    <br/>
    <br/>
    <a href="https://github.com/yashcoder007/Canadian-Banks-Stock-Market-Analysis"><strong>Explore the docs »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/yashcoder007/Canadian-Banks-Stock-Market-Analysis

">View Demo</a>
    .
    <a href="https://github.com/yashcoder007/Canadian-Banks-Stock-Market-Analysis/issues"> Report Bug</a>
    .
  </p>
</p>

![Downloads](https://img.shields.io/github/downloads/yashcoder007/Canadian-Banks-Stock-Market-Analysis/total) ![Contributors](https://img.shields.io/github/contributors/yashcoder007/Canadian-Banks-Stock-Market-Analysis?color=dark-green) ![Forks](https://img.shields.io/github/forks/yashcoder007/Canadian-Banks-Stock-Market-Analysis?style=social) ![Stargazers](https://img.shields.io/github/stars/yashcoder007/Canadian-Banks-Stock-Market-Analysis?style=social) ![Issues](https://img.shields.io/github/issues/yashcoder007/Canadian-Banks-Stock-Market-Analysis) ![License](https://img.shields.io/github/license/yashcoder007/Canadian-Banks-Stock-Market-Analysis) 

## Table Of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)
* [Authors](#authors)
* [Acknowledgements](#acknowledgements)

## About The Project

![Screen Shot](down1.png)
![Screen Shot](down2.png)

The project's motivation was to predict the returns of around 2000 stocks. This experiment was performed on the realtime that was provided by the stock exchange company Japan Exchange Group.  I designed an end-to-end data science modelling pipepline, starting from data cleaning, visualization, feature engineering to predictive modelling all combined in a jupyter notebook for ease of use. 

Firstly, I did extensive data cleaning and visualizations using libraries like Pandas, Matplotlib, Seaborn and NumPy. I created a lot of count plots, point plots, and other graphs.

Secondly, I did some Feature Engineering using library called TA. The features were generated synthetically using all the 42 indicators based on volume, votality, trend, momentum etc. These features helped in increasing the accuracy of the model.

Thirdly, LightGBM model was trained using the generated features with minimal error.

Lastly, Data Visualizations were drawn for analysis.





## Built With

Python

* [jupyter ](https://jupyter.org/)
* [scikit-learn](https://scikit-learn.org/stable/)
* [Numpy](https://numpy.org/)
* [pandas](https://pandas.pydata.org/)
* [SciPy](https://scipy.org/)
* [Matplotlib](https://matplotlib.org/)
* [XGBoost](https://xgboost.readthedocs.io/en/stable/parameter.html)


## Getting Started

Create a new virtual environment and install all the required packages.

### Prerequisites

The python libraries mentioned in Built With

### Installation

1. Download the dataset
```sh
https://www.kaggle.com/competitions/jpx-tokyo-stock-exchange-prediction```

2. Clone the repo

```sh
https://github.com/yashcoder007/Canadian-Banks-Stock-Market-Analysis.git
```
3. Install packages using  conda or pip.
For example:  "pip install -U scikit-learn" or "conda install -c conda-forge scikit-learn"

            jupyter
            scikit-learn
            Numpy
            pandas
            SciPy
            Matplotlib
            LightGBM
            SARIMA
            XGBoostRegressor

## Usage

1. Download the dataset from the link given.
2. Clone the repo
3. Download and use the .ipynb with jupyter notebooks.



## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.
* If you have suggestions for adding or removing projects, feel free to [open an issue](https://github.com/yashcoder007/Canadian-Banks-Stock-Market-Analysis
/issues) to discuss it, or directly create a pull request after you edit the *README.md* file with necessary changes.
* Please make sure you check your spelling and grammar.
* Create individual PR for each suggestion.
* Please also read through the [Code Of Conduct](https://github.com/yashcoder007/Canadian-Banks-Stock-Market-Analysis.git/blob/main/CODE_OF_CONDUCT.md) before posting your first idea as well.

### Creating A Pull Request

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See [LICENSE](https://github.com/yashcoder007/Canadian-Banks-Stock-Market-Analysis.git/blob/main/LICENSE.md) for more information.

## Authors

* **Yash Trivedi** - *Data Scientist/ Machine Learning Researcher* - [Yash Trivedi](https://github.com/yashcoder007)
