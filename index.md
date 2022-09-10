
# Deep Learning with R

## Main Idea of the course
In this short course on deep learning (DL) with R we focus on practical aspects of DL. We understand DL models as probabilistic models which model a (conditional) distribution for the outcome and not only a point estimation. Often this is achieved by modeling the parameters of a probability distribution and the distribution parameters are controlled by a neural network. The DL approach has the advantage, that the input to these neural networks can be all kind of data: tabular (structured) data, but also unstructured raw data like images or text. From this prespective DL models are just a complex generalisation of statistical models like linear regression. The parameters of the involved neural networks itself (often called weights) can be determined by the maximum likelihood principle. The basic idea can be sketched as:

<img src="https://github.com/tensorchiefs/dl_rcourse_2022/raw/main/ch05_00_opener.jpg" width="40%">

## Technicalities
This course is done in R. The used DL libraries are keras, tensorflow, and tensorflow probability. For doing the hands-on part we recommend to use colab (you need a google account) and an internet connections. An empty notebook for R can be started by clicking the following link 

[https://colab.research.google.com/notebook#create=true&language=r](https://colab.research.google.com/notebook#create=true&language=r) (starts a colab notebook with R) 

An example notebook, which installs the required DL-Liberies is  [00_R_Keras_TF_TFP](https://colab.research.google.com/github/tensorchiefs/dl_rcourse_2022/blob/main/notebooks/00_R_Keras_TF_TFP.ipynb). If you want to do it without internet connection, on your own computer you can try to install tensorflow, keras, and (for the latter lessons) tfprobability as done in the notebook [00_R_Keras_TF_TFP](https://colab.research.google.com/github/tensorchiefs/dl_rcourse_2022/blob/main/notebooks/00_R_Keras_TF_TFP.ipynb).   


## Other resources 
We took inspiration (and sometimes slides / figures) from the following resources.

* Probabilistic Deep Learning (DL-Book) [Probabilistic Deep Learning](https://www.manning.com/books/probabilistic-deep-learning?a_aid=probabilistic_deep_learning&a_bid=78e55885). This book is by us, the tensorchiefs, and covers the probabilistic approach to deep learning unsing Python, Keras, and TensorFlow. We will not cover all aspects of this book during the course.  

* Deep Learning with R [https://tensorflow.rstudio.com/](https://tensorflow.rstudio.com/). Nice resource with DL tutorials in R.

* R Markdown Scripts for DL in R [https://github.com/fmmattioni/deep-learning-with-r-notebooks](https://github.com/fmmattioni/deep-learning-with-r-notebooks) from the author of the Book [Deep Learning with R](https://www.manning.com/books/deep-learning-with-r)

* Deep Learning Book (DL-Book) [http://www.deeplearningbook.org/](http://www.deeplearningbook.org/). This is a quite comprehensive book which goes far beyond the scope of this course. 

* Convolutional Neural Networks for Visual Recognition [http://cs231n.stanford.edu/](http://cs231n.stanford.edu/), has additional material and [youtube videos of the lectures](https://www.youtube.com/playlist?list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC). While the focus is on computer vision, it also treats other topics such as optimization, backpropagation and RNNs. Lecture notes can be found at [http://cs231n.github.io/](http://cs231n.github.io/).

* Another applied course in DL: [TensorFlow and Deep Learning without a PhD](https://cloud.google.com/blog/big-data/2017/01/learn-tensorflow-and-deep-learning-without-a-phd)

* A further more applied course in python can be found at [https://tensorchiefs.github.io/dl_course_2022/](https://tensorchiefs.github.io/dl_course_2022/). 

## Dates 
The course is split in 5 lectures, which excercises. You will also work on a project with data of your own choosing. 

| Date     |      Lectures
|:--------:|:--------------|
|  12.09.2022| Lecture 1 (10:15-12:00), Lecture 2 (14:15-16:00) and Exercises (16:15-18:00)
|  19.09.2022| Lecture 3 (14:15-16:00) and Exercises (16:15-18:00)
|  26.09.2022| Lecture 4 (14:15-16:00) and Exercises (16:15-18:00)
|  03.10.2022| Hands-on DL: This day is reserved to work on your projects on site
|  10.10.2022| Lecture 5 and presentatation of the projects


## Syllabus (might change during course) 

| Lecture  |      Topic and Slides    |      Additional Material    |		Exercises and homework  |
|:----------------:|:-----------------------|:----------------------------|:--------------------------------------|
| 1        | Introduction, Fully Connected Networks, Keras [slides](https://github.com/tensorchiefs/dl_rcourse_2022/blob/main/slides/01_Introduction.pdf) |[Network Playground](https://playground.tensorflow.org/) |[Banknoteexample(01_nb_ch02_01.ipynb)](https://colab.research.google.com/github/tensorchiefs/dl_rcourse_2022/blob/main/notebooks/01_nb_ch02_01.ipynb) <br>[MNISTwithsimpleFCNN(02_nb_ch02_02a.ipynb)](https://colab.research.google.com/github/tensorchiefs/dl_rcourse_2022/blob/main/notebooks/02_nb_ch02_02a.ipynb) <br>[ArtLover_CNN(03_nb_ch02_03.ipynb)](https://github.com/tensorchiefs/dl_rcourse_2022/blob/main/notebooks/03_nb_ch02_03.ipynb) <br> [CIFAR10_CNN(04_nb_ch02_03.ipynb)](https://github.com/tensorchiefs/dl_rcourse_2022/blob/main/notebooks/04_nb_ch02_03.ipynb)
| 2        |Working with loss curves, convolutional neural networks [slides](https://github.com/tensorchiefs/dl_course_2022/blob/master/slides/02_fcNN_CNN.pdf) |[Understanding convolution](https://towardsdatascience.com/intuitively-understanding-convolutions-for-deep-learning-1f6f42faee1)|[03_fcnn_mnist]
|


