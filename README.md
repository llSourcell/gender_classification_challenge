# gender_classification_challenge

##Overview

This is the code for the gender classification challenge for 'Learn Python for Data Science #1' by @Sirajology on [YouTube](https://youtu.be/T5pRlIbr6gg). The code uses the [scikit-learn](http://scikit-learn.org/) machine learning library to train a [decision tree](https://en.wikipedia.org/wiki/Decision_tree) on a small dataset of body metrics (height, width, and shoe size) labeled male or female. Then we can predict the gender of someone given a novel set of body metrics. 

##Dependencies

* Scikit-learn (http://scikit-learn.org/stable/install.html)
* numpy (pip install numpy)
* scipy (pip install scipy)

Install missing dependencies using [pip](https://pip.pypa.io/en/stable/installing/)

##Usage

Once you have your dependencies installed via pip, run the script in terminal via

```
python demo.py
```

##Challenge

Find 3 more classifiers from the sci-kit learn [documentation](http://scikit-learn.org/stable/auto_examples/classification/plot_classifier_comparison.html) and add them to the demo.py code. Train them on the same dataset and [compare their results](http://scikit-learn.org/stable/modules/generated/sklearn.metrics.accuracy_score.html). You can determine accuracy by trying to predict testing you trained classifier on samples from the training data and see if it correctly classifies it. Push your code repository to [github](https://help.github.com/articles/set-up-git/) then post it in the comments. I'll give the winner a shoutout a week from now!

##Credits

Credits for some of the code go to [chribsen](https://github.com/chribsen). I've merely created a wrapper to get people started easily.
