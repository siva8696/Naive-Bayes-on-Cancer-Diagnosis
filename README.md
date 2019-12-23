<h2>Naive Bayes:</h2>
Naive Bayes in a Supervised algorithm technique. It’s derived from Bayes theorem. In Naive Bayes, “Naive” means unsophisticated and simplistic. Where it assumes that features are independent on each other and Bayes came from Bayes theorem.

![Img](https://miro.medium.com/max/492/1*saXJNgouo6rzGeyQaheq-w.png)
 

Naïve Bayes mostly used in text classification techniques along with that we can use it as SPAM filter. 
But there is one cache in the Naive Bayes that is if we have a new word in text and that word doesn’t have the probability value in train data then it will assign the word count as “0” and to overcome this problem we have Laplace Smoothing it will take care of less frequency words. Along with that the alpha value in Laplace Smoothing is a hyperparameter and it would take of overfitting and underfitting. Moreover that, if we have more words i.e., if we have more dimensional data then we must multiply the more probabilities, but python had double precision 16 significant values. To overcome this, we are using log probabilities so that the probability will lies in the range of 0 to 1. 
<h3>Types of Naive Bayes Model:</h1>
<h4>Gaussian model:</h4> It is used in simple classification with normal distributed data.
<h4>Multinomial model:</h4> It is mostly used in text classification problems. With the help of Bernoulli trials, we can find “how often a word occurs in the given text”.
<h4>Bernoulli model:</h4> The binomial model is useful if your feature vectors are binary. Used for simply two discrete variables.
<h4>Reference : </h4>https://medium.com/analytics-vidhya/naive-bayes-classifier-a-beginners-guide-to-master-the-fastest-and-simplest-classification-d6a368e6b737

