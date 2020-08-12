# Hyperparameter-tuning-deep-learning-text-classification-model-using-Talos
Taken from Talos's GitHub: "Talos is made for data scientists and data engineers that want to remain in complete control of their Keras models, but are tired of mindless parameter hopping and confusing optimization solutions that add complexity instead of reducing it. Within minutes, without learning any new syntax, Talos allows you to configure, perform, and evaluate hyperparameter optimization experiments that yield state-of-the-art results across a wide range of prediction tasks. Talos provides the simplest and yet most powerful available method for hyperparameter optimization with Keras."


# **Motivation**:
Not sure if this is the most efficient way to do this but I have very much enjoyed using the Talos scanner to sift through some hyperparameters for my NLP project.
What I’ve been doing is outputting at least 2000 algos and uploading it into Tableau to visually understand which hyperparameters have the greatest impact on testing accuracy. I’ll take that analysis, tweak the scanner based on what I see in Tableau(and a correlation matrix), and run another 2000 algos and start the process all over again.
It is tedious but starting simple and slow is better when trying to understand your problem at hand. In the photos below I am taking a look at the least overfitted models with the highest accuracy, a correlation matrix, and other Tableau tabs where I can also see what happens to the accuracy for 

ex. when the convolutional neural network is deep but the LSTM layer isn’t and vice versa.
I can compare Epochs, learning rates, dropout rates, and other Dense layers to pin point what works for my corpus and what doesn’t
Finding the best model might be more luck than skill when you’re new to this, but at the very least, I’m taking an analytical approach to a problem and soon will come out on top!


# **Install**:
``` python
!pip install talos
```


###  Resources I used:

[Example](https://towardsdatascience.com/hyperparameter-optimization-with-keras-b82e6364ca53)  

[Documentation](https://autonomio.github.io/talos/)

# **Tableau Viz Example**:
![alt text](0 (1).jpg?raw=true "Title")

![alt text](0 (2).jpg?raw=true "Title")

![alt text](0 (4).jpg?raw=true "Title")

# **Correlation heat map Viz Example**:
![alt text](0.jpg?raw=true "Title")

