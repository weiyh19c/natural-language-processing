# Naive Bayes
Total points 10

## Question 1

Assume that there are 2 happy people and 2 unhappy people in a room. Concretely, persons A and B are happy and persons C and D are unhappy. If you were to randomly pick a person from the room, what is the probability that the person is happy.
1 / 1 point

`1/2`

1/4

3/4

0


## Question 2

Assume that there are 2 happy people and 2 unhappy people in a room. Concretely, persons A and B are happy and persons C and D are unhappy. If a friend showed you the part of the room where the two happy people are, what is the probability that you choose person B?
1 / 1 point

`1/2`

1/4

3/4



## Question 3

From the equations presented below, express the probability of a tweet being positive given that it contains the word happy in terms of the probability of a tweet containing the word happy given that it is positive
 

P( Positive ∣ "happy" )=P( Positive ∩ "happy" )P( "happy" ) P(\text { Positive } \mid \text { "happy" })=\frac{P(\text { Positive } \cap
\text { "happy" })}{P(\text { "happy" })} P( Positive ∣ "happy" )=P( "happy" )P( Positive ∩ "happy" )​
 

P( "happy"  Positive )=P( "happy" ∩ Positive )P( Positive ) P(\text { "happy" } \text { Positive })=\frac{P(\text { "happy" } \cap \text
{ Positive })}{P(\text { Positive })} P( "happy"  Positive )=P( Positive )P( "happy" ∩ Positive )​
1 / 1 point

`P( Positive ∣ happy )=P( happy ∣ Positive )×P( Positive )P( happy)P(\text { Positive } \mid \text { happy })=P(\text { happy } \mid \text {
Positive }) \times \frac{P(\text { Positive })}{P(\text { happy})}P( Positive ∣ happy )=P( happy ∣ Positive )×P( happy)P( Positive )​`

P( Positive ∣ happy )=P( "happy" ∣ Positive )×P( happy )P( Positive ) P(\text { Positive } \mid \text { happy })=P(\text { "happy" } \mid \text {
Positive }) \times \frac{P(\text { happy })}{P(\text { Positive })}P( Positive ∣ happy )=P( "happy" ∣ Positive )×P( Positive )P( happy )​

P( Positive ⋂ happy )=P( happy ∣ Positive )×P( Positive )P( happy)P(\text { Positive } \bigcap \text { happy })=P(\text { happy } \mid \text {
Positive }) \times \frac{P(\text { Positive })}{P(\text { happy})}P( Positive ⋂ happy )=P( happy ∣ Positive )×P( happy)P( Positive )​

P( Positive ⋂ happy )=P( "happy" ∣ Positive )×P( happy )P( Positive ) P(\text { Positive } \bigcap \text { happy })=P(\text { "happy" } \mid \text
{ Positive }) \times \frac{P(\text { happy })}{P(\text { Positive })}P( Positive ⋂ happy )=P( "happy" ∣ Positive )×P( Positive )P( happy )​
Correct


## Question 4

Bayes rule is defined as
1 / 1 point

`P(X∣Y)=P(Y∣X)×P(X)P(Y)P(X \mid Y)=P(Y \mid X) \times \frac{P(X)}{P(Y)}P(X∣Y)=P(Y∣X)×P(Y)P(X)​`

P(X∣Y)=P(Y∣X)×P(Y)P(X)P(X \mid Y)=P(Y \mid X) \times \frac{P(Y)} {P(X)}P(X∣Y)=P(Y∣X)×P(X)P(Y)​

P(X∣Y)=P(X∣Y)×P(X)P(Y)P(X \mid Y)=P(X \mid Y) \times \frac{P(X)}{P(Y)}P(X∣Y)=P(X∣Y)×P(Y)P(X)​

P(X∣Y)=P(Y∣X)×P(X)P(Y∣X)P(X \mid Y)=P(Y \mid X) \times \frac{P(X)}{P(Y|X)}P(X∣Y)=P(Y∣X)×P(Y∣X)P(X)​




## Question 5

Suppose that in your dataset, 25% of the positive tweets contain the word ‘happy’. You also know that a total of 13% of the tweets in your dataset contain the word 'happy', and that 40% of the total number of tweets are positive. You observe the tweet: ''happy to learn NLP'. What is the probability that this tweet is positive?
1 / 1 point
`0.77`


**** That’s right. You just applied Bayes’ rule.
6.
Question 6

The log likelihood for a certain word wiw_iwi​ is defined as:
 

log⁡(P(wi∣pos)P(wi∣neg))\log (\frac{P(w_i | pos)}{P(w_i | neg)}) log(P(wi​∣neg)P(wi​∣pos)​).
1 / 1 point

`Positive numbers imply that the word is positive.`


Positive numbers imply that the word is negative.

`Negative numbers imply that the word is negative.`

Negative numbers imply that the word is positive.

## Question 7

The log likelihood mentioned in lecture, which is the log of the ratio between two probabilities is bounded between
1 / 1 point

-1 and 1

`−∞ - \infty−∞ and ∞\infty∞`

0 and ∞\infty∞

0 and 1




## Question 8

When implementing naive Bayes, in which order should the following steps be implemented.
1 / 1 point

**-Get or annotate a dataset with positive and negative tweets**
     

 **Preprocess the tweets: process_tweet(tweet)**
     

 **Compute freq(w, class)**
     

 **Get P(w | pos), P(w | neg)**
     

 **Get λ(w)**
     

 **Compute logprior = log(P(pos) / P(neg))**

-Get or annotate a dataset with positive and negative tweets
     

 Preprocess the tweets: process_tweet(tweet) ➞ 
     

 Compute freq(w, class)
     

 Get λ(w)
     

 Get P(w | pos), P(w | neg)
     

 Compute logprior = log(P(pos) / P(neg))

-Get or annotate a dataset with positive and negative tweets
     

 Compute freq(w, class)
 
 Preprocess the tweets: process_tweet(tweet) ➞ 
     

 Get P(w | pos), P(w | neg)
     

 Get λ(w)
     

 Compute logprior = log(P(pos) / P(neg))

-Get or annotate a dataset with positive and negative tweets
     

 Compute freq(w, class)
     

 Preprocess the tweets: process_tweet(tweet) ➞ 
     

 Compute logprior = log(P(pos) / P(neg)
     

 Get P(w | pos), P(w | neg)
     

 Get λ(w)



## Question 9

To test naive bayes model, which of the following are required?
1 / 1 point

`Xval,Yval,λ,logpriorX_{\text val}, Y_{\text val}, \lambda, logpriorXval​,Yval​,λ,logprior`

Xval,Yval,logpriorX_{\text val}, Y_{\text val}, logpriorXval​,Yval​,logprior

Xval,λ,logpriorX_{\text val}, \lambda, logpriorXval​,λ,logprior

Yval,λ,logpriorY_{\text val}, \lambda, logpriorYval​,λ,logprior


## Question 10

Which of the following is NOT an application of naive Bayes?
1 / 1 point

Sentiment Analysis

Author identification

Information retrieval

Word disambiguation

`Numerical predictions`
