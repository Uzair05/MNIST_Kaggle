# MNIST CNN

## CNN through Tensorflow

Made By Uzair Bin Asim

### What it is:

I plan on making a Machine Learning model that implements CNN. I will be using the MNIST dataset to make predictions on handwritten characters.  
To do so I will implement CNN using the [tensorflow](https://www.tensorflow.org/) library. Datasets imported from [kaggle](https://www.kaggle.com/c/digit-recognizer).

### How to use it:

1. Dowload the data using command from [Kaggle](https://github.com/Kaggle/kaggle-api):

```bash
kaggle competitions download -c digit-recognizer
```

2. Uncompress data and move them to folder `data/` using [7-zip](https://www.7-zip.org/):

```bash
7z x digit-recognizer.zip; mkdir data/; ls *.csv | xargs -I% mv % data/
```

3. Open in jupter notebook:

```bash
jupyter notebook .
```
