# Logistic Regression
Total points 10
### Question 1

When performing logistic regression on sentiment analysis, you represented each tweet as a vector of ones and zeros. However your model did not work well. Your training cost was reasonable, but your testing cost was just not acceptable. What could be a possible reason?
1 / 1 point

The vector representations are sparse and therefore it is much harder for your model to learn anything that could generalize well to the test set.

You probably need to increase your vocabulary size because it seems like you have very little features.

Logistic regression does not work for sentiment analysis, and therefore you should be looking at other models.

`Sparse representations require a good amount of training time so you should train your model for longer`
Correct


### Question 2

Which of the following are examples of text preprocessing?
1 / 1 point

`Stemming, or the process of reducing a word to its word stem.`
Correct

`Lowercasing, which is the process of removing changing all capital letter to lower case.`
Correct

`Removing stopwords, punctuation, handles and URLs`
Correct


Adding new words to make sure all the sentences make sense

### Question 3

The sigmoid function is defined as h(x(i),θ)=11+e−θTx(i)h( x^{(i)}, \theta) =
\frac{1}{1+e^{-\theta^Tx^{(i)}}}h(x(i),θ)=1+e−θTx(i)1​. Which of the following is true.
1 / 1 point

Large positive values of θTx(i)\theta^Tx^{(i)}θTx(i) will make h(x(i),θ)h( x^{(i)}, \theta)h(x(i),θ) closer to 1 and large negative values of θTx(i)\theta^Tx^{(i)}θTx(i) will make h(x(i),θ)h(
x^{(i)},\theta)h(x(i),θ) close to -1.

Large positive values of θTx(i)\theta^Tx^{(i)}θTx(i) will make h(x(i),θ)h( x^{(i)}, \theta)h(x(i),θ) closer to 1 and large negative values of θTx(i)\theta^Tx^{(i)}θTx(i) will make h(x(i),θ)h(
x^{(i)},\theta)h(x(i),θ) close to 0.

Small positive values of θTx(i)\theta^Tx^{(i)}θTx(i) will make h(x(i),θ)h( x^{(i)}, \theta)h(x(i),θ) closer to 1 and large positive values of θTx(i)\theta^Tx^{(i)}θTx(i) will make h(x(i),θ)h(
x^{(i)},\theta)h(x(i),θ) close to 0.

`Small positive values of θTx(i)\theta^Tx^{(i)}θTx(i) will make h(x(i),θ)h( x^{(i)}, \theta)h(x(i),θ) closer to 0 and large negative values of θTx(i)\theta^Tx^{(i)}θTx(i) will make h(x(i),θ)h(
x^{(i)},\theta)h(x(i),θ) close to -1.`
Correct

### Question 4

The cost function for logistic regression is defined as J(θ)=−1m∑i=1m[y(i)log⁡h(x(i),θ)+(1−y(i))log⁡(1−h(x(i),θ))]J(\theta)=-\frac{1}{m} \sum_{i=1}^{m}\left[y^{(i)} \log h\left(x^{(i)},
\theta\right)+\left(1-y^{(i)}\right) \log \left(1-h\left(x^{(i)},
\theta\right)\right)\right]J(θ)=−m1​∑i=1m​[y(i)logh(x(i),θ)+(1−y(i))log(1−h(x(i),θ))]. Which of the following is true about the cost function above. Mark all the correct ones.
1 / 1 point

`When y(i)=1y^{(i)} = 1y(i)=1, as h(x(i),θ)h(x^{(i)},\theta)h(x(i),θ) goes close to 0, the cost function approaches ∞\infty∞.`
Correct


When y(i)=1y^{(i)} = 1y(i)=1, as h(x(i),θ)h(x^{(i)},\theta)h(x(i),θ) goes close to 0, the cost function approaches 000.

`When y(i)=0y^{(i)} = 0y(i)=0, as h(x(i),θ)h(x^{(i)},\theta)h(x(i),θ) goes close to 0, the cost function approaches 000.`
Correct


When y(i)=0y^{(i)} = 0y(i)=0, as h(x(i),θ)h(x^{(i)},\theta)h(x(i),θ) goes close to 0, the cost function approaches ∞\infty∞.

### Question 5

For what value of θTx\theta^TxθTx in the sigmoid function does h(x(i),θ)=0.5h(x^{(i)},\theta) = 0.5h(x(i),θ)=0.5.
1 / 1 point

`0`
Correct

### Question 6

Select all that apply. When performing logistic regression for sentiment analysis using the method taught in this week's lecture, you have to:
1 / 1 point

`Performing data processing.`
Correct



`Create a dictionary that maps the word and the class that word is found in to the number of times that word is found in the class.`
Correct



Create a dictionary that maps the word and the class that word is found in to see if that word shows up in the class.

`For each tweet, you have to create a  positive feature with the sum of positive counts of each word in that tweet. You also have to create a negative feature with the sum of negative counts of each word in that tweet.`
Correct


### Question 7

When training logistic regression, you have to perform the following operations in the desired order.
1 / 1 point

Initialize parameters, get gradient, classify/predict, update, get loss, repeat

Initialize parameters, classify/predict, get gradient, update, get loss, repeat

Initialize parameters, get gradient, update, classify/predict, get loss, repeat

`Initialize parameters, get gradient, update, get loss, classify/predict, repeat`
Correct


### Question 8

Assuming we got the classification correct, where y(i)=1y^{(i)} = 1y(i)=1 for some specific example i. This means that h(x(i),θ)>0.5h(x^{(i)}, \theta) > 0.5h(x(i),θ)>0.5. Which of the following has to hold:
1 / 1 point

Our prediction, h(x(i),θ)h(x^{(i)}, \theta)h(x(i),θ) for this specific training example is exactly equal to its corresponding label y(i)y^{(i)}y(i).

Our prediction, h(x(i),θ)h(x^{(i)}, \theta)h(x(i),θ) for this specific training example is less than (1−y(i)1 - y^{(i)}1−y(i)).

Our prediction, h(x(i),θ)h(x^{(i)}, \theta)h(x(i),θ) for this specific training example is less than (1−h(x(i),θ))(1 - h(x^{(i)}, \theta))(1−h(x(i),θ)).

`Our prediction, h(x(i),θ)h(x^{(i)}, \theta)h(x(i),θ) for this specific training example is greater than (1−h(x(i),θ))(1 - h(x^{(i)}, \theta))(1−h(x(i),θ)).`
Correct


### Question 9

What is the purpose of gradient descent? Select all that apply.
1 / 1 point

`Gradient descent allows us to learn the parameters θ\thetaθ in logistic regression as to minimize the loss function J.`
Correct


Gradient descent allows us to learn the parameters θ\thetaθ in logistic regression as to maximize the loss function J.

`Gradient descent,  grad_theta allows us to update the parameters θ\thetaθ by computing θ=θ−α∗grad_theta\theta = \theta - \alpha * grad\_thetaθ=θ−α∗grad_theta`
Correct


Gradient descent,  grad_theta allows us to update the parameters θ\thetaθ by computing θ=θ+α∗grad_theta\theta = \theta + \alpha * grad\_thetaθ=θ+α∗grad_theta

### Question 10

What is a good metric that allows you to decide when to stop training/trying to get a good model? Select all that apply.
1 / 1 point

`When your accuracy is good enough on the test set.`
Correct

When your accuracy is good enough on the train set.

`When you plot the cost versus (# of iterations) and you see that your the loss is converging (i.e. no longer changes as much).`
Correct

When α\alphaα, your step size is neither too small nor too large.
