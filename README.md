# The Simpsons Character Recognizer

This project was developed during the 2020 Vision and Percpetion course held by [Prof. Pirri](http://www.diag.uniroma1.it//pirri/).

The notebook is divided in two sections: the first contains experiments with a custom neural network, the second contains transfer learning experiments with the VGG16 net.

The dataset used in this project is free and [available on Kaggle](https://www.kaggle.com/alexattia/the-simpsons-characters-dataset).

## Summary

  - [Getting Started](#getting-started)
  - [Results](#results)
  - [Authors](#authors)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

## Getting Started

The project contains only a Jupyter Notebook file. Meet the prerequisite and use it. 
[Google Colaboratory](https://colab.research.google.com/) is recommended.

### Prerequisites

You have two ways of meeting the prerequisites:

- First (recommended, online)
	- Use [Google Colaboratory](https://colab.research.google.com/)
	- Done.
	
- Second (offline)
	- Python3
	- Jupyter ``` pip install jupyterlab ```
	- Tensorflow (via conda or pip)
		- ``` conda install tensorflow-gpu ```
		- ``` pip install tensorflow-gpu ```
	- Numpy ``` pip install numpy ```
	- Pandas ``` pip install pandas ```
	- Matplotlib ``` pip install matplotlib ```
	- Seaborn ``` pip install seaborn ```
	- Scikit-image ``` pip install scikit-image ```
	- Scikit-learn ``` pip install scikit-learn ```

## Results

|                          | precision | recall | f1-score | support |
|:------------------------:|:---------:|:------:|:--------:|:-------:|
|  abraham_grampa_simpson  |    1.00   |  0.96  |   0.98   |    48   |
|  apu_nahasapeemapetilon  |    0.96   |  1.00  |   0.98   |    50   |
|       bart_simpson       |    0.91   |  1.00  |   0.95   |    50   |
| charles_montgomery_burns |    0.92   |  0.94  |   0.93   |    48   |
|       chief_wiggum       |    0.98   |  1.00  |   0.99   |    50   |
|      comic_book_guy      |    0.98   |  1.00  |   0.99   |    49   |
|      edna_krabappel      |    1.00   |  0.96  |   0.98   |    50   |
|       homer_simpson      |    0.94   |  1.00  |   0.97   |    50   |
|       kent_brockman      |    0.98   |  0.98  |   0.98   |    50   |
|     krusty_the_clown     |    0.98   |  0.94  |   0.96   |    50   |
|       lenny_leonard      |    1.00   |  0.90  |   0.95   |    50   |
|       lisa_simpson       |    0.98   |  0.98  |   0.98   |    50   |
|       marge_simpson      |    1.00   |  0.98  |   0.99   |    50   |
|    milhouse_van_houten   |    1.00   |  0.98  |   0.99   |    49   |
|        moe_szyslak       |    0.94   |  0.96  |   0.95   |    50   |
|       ned_flanders       |    1.00   |  0.96  |   0.98   |    49   |
|       nelson_muntz       |    0.98   |  0.98  |   0.98   |    50   |
|     principal_skinner    |    0.96   |  0.98  |   0.97   |    50   |
|       sideshow_bob       |    1.00   |  1.00  |   1.00   |    47   |
|       **accuracy**       |           |        |   0.97   |   940   |
|       **macro avg**      |    0.97   |  0.97  |   0.97   |   940   |
|     **weighted avg**     |    0.97   |  0.97  |   0.97   |   940   |

## Authors

- **Giovanbattista Abbate** - [giabb](https://github.com/giabb)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

- **Billie Thompson** - *Provided README Template* - [PurpleBooth](https://github.com/PurpleBooth)
