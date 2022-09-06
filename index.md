
# Deep Learning with R

## Main Idea of the course
This course in deep learning (DL) focuses on practical aspects of DL. In this course, we understand DL models as probabilistic models. I.e. the parameters of a probability distribution are controlled by a neural network. From this prespective DL models are a complex generalisation of statistical models like linear regression. The parameters can be determined by the maximum likelihood principle, we also briefly touch a Bayesian extensions on neural networks.    
![This is an image](https://github.com/tensorchiefs/dl_rcourse_2022/blob/main/ch05_00_opener.pdf)

## Technicalities
This course is done in R. The used DL libraries are keras, tensorflow, and tensorflow probability. For doing the hands-on part we recommend to use colab (you need a google account) and an internet connections. A simple notebook is given in XXX. If you want to do it without internet connection, on your own computer you can try to install tensorflow, keras, and (for the latter lessons) tfprobability.   


### Local installation
XXX

## Other resources 
We took inspiration (and sometimes slides / figures) from the following resources.

* Probabilistic Deep Learning (DL-Book) [Probabilistic Deep Learning](https://www.manning.com/books/probabilistic-deep-learning?a_aid=probabilistic_deep_learning&a_bid=78e55885). This book is by us the tensorchiefs and cover the probabilistic approach to deep learning. We will not cover all aspects of this book during the course. The examples in the book are in python. 

* Deep Learning Book (DL-Book) [http://www.deeplearningbook.org/](http://www.deeplearningbook.org/). This is a quite comprehensive book which goes far beyond the scope of this course. 

* Convolutional Neural Networks for Visual Recognition [http://cs231n.stanford.edu/](http://cs231n.stanford.edu/), has additional material and [youtube videos of the lectures](https://www.youtube.com/playlist?list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC). While the focus is on computer vision, it also treats other topics such as optimization, backpropagation and RNNs. Lecture notes can be found at [http://cs231n.github.io/](http://cs231n.github.io/).

* Another applied course in DL: [TensorFlow and Deep Learning without a PhD](https://cloud.google.com/blog/big-data/2017/01/learn-tensorflow-and-deep-learning-without-a-phd)

* A further more applied course in python can be found at [https://tensorchiefs.github.io/dl_course_2022/](https://tensorchiefs.github.io/dl_course_2022/). 

## Dates 
The course is split in 8 sessions, each 4 lectures long. 

| Day  |      Date    |      Time    |
|:--------:|:--------------|:---------------|
| 1        | 23.02.2022|9:00-12:30
| 2        | 02.03.2022|9:00-12:30
| 3        | 09.03.2022|9:00-12:30
| 4        | 16.03.2022|9:00-12:30
| 5        | 23.03.2022|9:00-12:30
| 6        | 30.03.2022|9:00-12:30
| 7        | 06.04.2022|9:00-12:30
| 8        | 13.04.2022|9:00-12:30

## Syllabus (might change during course) 

| Day  |      Topic and Slides    |      Additional Material    |		Exercises and homework  |
|:----------------:|:-----------------------|:----------------------------|:--------------------------------------|
| 1        | Introduction, Fully Connected Networks, Keras [slides](https://github.com/tensorchiefs/dl_course_2022/blob/master/slides/01_Introduction.pdf) |[Network Playground](https://playground.tensorflow.org/) |[01_simple_forward_pass](https://github.com/tensorchiefs/dl_course_2022/blob/master/notebooks/01_simple_forward_pass.ipynb) [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2022/blob/master/notebooks/01_simple_forward_pass.ipynb)<br>[02_fcnn_with_banknote](https://github.com/tensorchiefs/dl_course_2022/blob/master/notebooks/02_fcnn_with_banknote.ipynb) [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2022/blob/master/notebooks/02_fcnn_with_banknote.ipynb)
| 2        |Looking back at fcNN, working with loss curves, convolutional neural networks [slides](https://github.com/tensorchiefs/dl_course_2022/blob/master/slides/02_fcNN_CNN.pdf), [records](https://ethz.zoom.us/rec/share/cpj7wsPPI2iuupN7StHlsphFKhmyBJxtaPzNn42yPsq1stcE60YOdyvkCkzIRWnf.Mi1FOdnhj-n0TjME) |[Understanding convolution](https://towardsdatascience.com/intuitively-understanding-convolutions-for-deep-learning-1f6f42faee1)|[03_fcnn_mnist](https://github.com/tensorchiefs/dl_course_2022/blob/master/notebooks/03_fcnn_mnist.ipynb)  [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2022/blob/master/notebooks/03_fcnn_mnist.ipynb)<br>[04_fcnn_mnist_shuffled](https://github.com/tensorchiefs/dl_course_2022/blob/master/notebooks/04_fcnn_mnist_shuffled.ipynb) [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2022/blob/master/notebooks/04_fcnn_mnist_shuffled.ipynb) <br> [05_cnn_edge_lover](https://github.com/tensorchiefs/dl_course_2022/blob/master/notebooks/05_cnn_edge_lover.ipynb) [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2022/blob/master/notebooks/05_cnn_edge_lover.ipynb) <br>[06_cnn_mnist_shuffled](https://github.com/tensorchiefs/dl_course_2022/blob/master/notebooks/06_cnn_mnist_shuffled.ipynb) [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2022/blob/master/notebooks/06_cnn_mnist_shuffled.ipynb) <br>[07_cifar10_norm](https://github.com/tensorchiefs/dl_course_2022/blob/master/notebooks/07_cifar10_norm.ipynb) [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2022/blob/master/notebooks/07_cifar10_norm.ipynb)
| 3        |Tricks of the trade in CNNs [slides](https://github.com/tensorchiefs/dl_course_2022/blob/master/slides/03_CNN.pdf) , [records](https://ethz.zoom.us/rec/share/H8YXdaDPFkZ8hU_yxBPcRSc32h91XyZZRwuaoEo-B7bFaa7AU3UkW2F53vB_zkHq.ChmBbdx4uAx9WN3L)|[Understanding CNNs](http://cs231n.github.io/understanding-cnn)|[08_cifar10_tricks](https://github.com/tensorchiefs/dl_course_2022/blob/master/notebooks/08_cifar10_tricks.ipynb) [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2022/blob/master/notebooks/08_cifar10_tricks.ipynb) <br>[08b_transferlearning](https://github.com/tensorchiefs/dl_course_2022/blob/master/notebooks/08b_classification_few_labels.ipynb) [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2022/blob/master/notebooks/08b_classification_few_labels.ipynb) <br> [09_1DConv](https://github.com/tensorchiefs/dl_course_2022/blob/master/notebooks/09_1DConv.ipynb)  [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2022/blob/master/notebooks/09_1DConv.ipynb)
| 4        |Details: Backpropagation in DL, MaxLike-Principle [slides](https://github.com/tensorchiefs/dl_course_2020/blob/master/slides/04_Details.pdf) , [records](https://ethz.zoom.us/rec/share/gtrhhNdVuGoCkMK-Z4vtZHZqL3GwJQBhjZT5iSn8NabTy692Y-5n1MyG8l7e8wTf.5pRAwUws6TszlYL-)| |[10_linreg_tensorflow](https://github.com/tensorchiefs/dl_course_2022/blob/master/notebooks/10_linreg_tensorflow.ipynb) [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2022/blob/master/notebooks/10_linreg_tensorflow.ipynb) <br>[11_backpropagation](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/11_backpropagation.ipynb) [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2022/blob/master/notebooks/11_backpropagation.ipynb) <br>[12_maxlike](https://github.com/tensorchiefs/dl_book/blob/master/chapter_04/nb_ch04_01.ipynb) [colab](https://colab.research.google.com/github/tensorchiefs/dl_book/blob/master/chapter_04/nb_ch04_01.ipynb)<br>[12b_mnist_loglike](https://github.com/tensorchiefs/dl_course_2022/blob/master/notebooks/12b_mnist_loglike.ipynb) [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2022/blob/master/notebooks/12b_mnist_loglike.ipynb)
|5     |Probabilistic Models [slides_part_1](https://github.com/tensorchiefs/dl_course_2022/blob/master/slides/05_Probabilistic_Modeling_part1.pdf)  [slides_part_2](https://github.com/tensorchiefs/dl_course_2022/blob/master/slides/05_Probabilistic_Modeling_part2.pdf) , [records](https://ethz.zoom.us/rec/share/stfHK60W4omYeBN77ZpawrKvSgavnZ4E28swdEartEI-Oi7TXrOZ8xE6CA_59uS0.K34gTX9D77O4xtBr)| |[13_linreg_with_tfp](https://github.com/tensorchiefs/dl_course_2022/blob/master/notebooks/13_linreg_with_tfp.ipynb)  [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2022/blob/master/notebooks/13_linreg_with_tfp.ipynb) <br>[14_poisreg_with_tfp](https://github.com/tensorchiefs/dl_course_2022/blob/master/notebooks/14_poisreg_with_tfp.ipynb) [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2022/blob/master/notebooks/14_poisreg_with_tfp.ipynb)
| 6        |Probabilistic models in the wild [slides_part_1](https://github.com/tensorchiefs/dl_course_2022/blob/master/slides/06_flexible_CPDs_part1.pdf) [slides_part_2](https://github.com/tensorchiefs/dl_course_2022/blob/master/slides/06_mixtures_and_bayes_part2.pdf) , [records](https://ethz.zoom.us/rec/share/ApEXhgQtyXU8h4Hnp-GxAT8c3-yozgRfa0d80D9Oyhmuumf2O_9yVwNA3hAstGVJ.oButVNLuyMYlSqkt) ||<br>[17_faces_regression](https://github.com/tensorchiefs/dl_course_2022/blob/master/notebooks/17_faces_regression.ipynb) [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2022/blob/master/notebooks/17_faces_regression.ipynb) <br>[18_elephant_in_the_room](https://github.com/tensorchiefs/dl_course_2022/blob/master/notebooks/18_elephant_in_the_room.ipynb)  [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2022/blob/master/notebooks/18_elephant_in_the_room.ipynb)
| 7        | Bayesian Deep Learning [slides_part_1](https://github.com/tensorchiefs/dl_course_2022/blob/master/slides/07_bayes_part1.pdf) [slides_part_2](https://github.com/tensorchiefs/dl_course_2022/blob/master/slides/07_bayes_part2.pdf),  [records](https://ethz.zoom.us/rec/share/7s6nsNQ4CzP37fUKPl0p4w1p1b4Ro4CTD7uRiPpKLPXZFEfwpX8msy6QYLfJpzzH.J5MVD6zWFsAKWrq_ )| |[20_cifar10_classification_mc_and_vi](https://github.com/tensorchiefs/dl_course_2020/blob/master/notebooks/20_cifar10_classification_mc_and_vi.ipynb) [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2022/blob/master/notebooks/20_cifar10_classification_mc_and_vi.ipynb)|
| 8        | Fun with Normalizing Flows [slides_part_1](https://github.com/tensorchiefs/dl_course_2022/blob/master/slides/08_NF.pdf), [records](https://ethz.zoom.us/rec/share/EyZCHeSP1ROjf090sD6RZAfuLFrJAlPHkUTZmQgZOvaGy__WF31lp6p_7dutNmQ.rCPhRH-7E7JKoUqL  ) | team projects |[fun with glow](https://github.com/tensorchiefs/dl_course_2022/blob/master/notebooks/fun_with_glow.ipynb) [colab](https://colab.research.google.com/github/tensorchiefs/dl_course_2022/blob/master/notebooks/fun_with_glow.ipynb)|


