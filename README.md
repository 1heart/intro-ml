# An introduction to machine learning

This is the repo for a presentation and associated code on **an introduction to machine learning**, as well as some resources for further information.

## Where to begin

The presentation is located [here](http://yixinlin.net/intro-ml/intro-ml.pdf), which introduces some high-level concepts of machine learning and then introduces the idea of deep learning. Some good supplements include [Udacity's friendly intro to ML](https://www.youtube.com/watch?v=IpGxLWOIZy4), as well as the highly popular [Coursera course](https://www.coursera.org/learn/machine-learning) and [associated course](http://cs229.stanford.edu/materials.html).

## Code

Just run the Jupyter notebooks in order to go through a basic introduction to building deep models in TensorFlow and Keras. The last notebook is an exercise/fun project to finetune your own image classifier for whatever dataset you want. Each of the notebooks heavily borrows on other tutorials and blogposts which are referenced throughout; all the credit to them!

### Dependencies

A basic understanding of navigating using terminal is recommended; if you don't have that, try reading [this tutorial](http://www.dummies.com/computers/macs/mac-operating-systems/how-to-use-basic-unix-commands-to-work-in-terminal-on-your-mac/).

First, clone or download this repository from Github.

After installing Python 3, you can simply do a `pip install -r requirements.txt` for the dependencies. It'll install [Python 3](https://www.python.org/), [Jupyter](http://jupyter.org/), [NumPy](https://www.scipy.org/), [TensorFlow](https://www.tensorflow.org/), and [Keras](https://keras.io/), which are the dependencies in the attached Jupyter notebooks. [Scikit-learn](http://scikit-learn.org/) is optional but also recommended for experimenting with non-deep models.

Afterwards, just run `jupyter notebook` and get started with the notebooks!

### Training in the cloud

Often, you don't want to use your personal machine to train your models. Sometimes you don't have a GPU, or don't want to keep your personal computer running. In that case, Github Education partners with Amazon Web Services to provide $100 of credit for you to run a GPU machine on Amazon's cloud. If you're a student, sign up with your edu account at [Github Student Developer Pack](https://education.github.com/pack) and choose the Amazon Educate package. Try [this tutorial](https://chrisalbon.com/jupyter/run_project_jupyter_on_amazon_ec2.html) to get Jupyter set up with AWS.

## Next steps

Try completing the last notebook's problem for an interesting problem! At the end, you'll learn how to finetune a pretrained model to classify whatever dataset you want.

Some more resources on machine learning are located [here](https://docs.google.com/document/d/1BuYUH0w-hjZJHZr9POp0KileNE8CVzc1JUi4tuPs6O8/edit#), originally written as a list of resources for Duke's Machine Learning and Data Science (MLADS) club.

