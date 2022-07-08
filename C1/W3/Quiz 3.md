# Vector Space Models
Total points 10

## Question 1

G​iven a corpus A, encoded as (123) 
123
⎝⎜⎛​123​⎠⎟⎞​ and corpus B encoded as (472) 
472
⎝⎜⎛​472​⎠⎟⎞​, What is the euclidean distance between the two documents?
1 / 1 point

`5.91608`

3​5

2​.43

N​one of the above


## Question 2

G​iven the previous problem, a user now came up with a corpus C defined as  (314) 
314
⎝⎜⎛​314​⎠⎟⎞​ and you want to recommend a document that is similar to it. Would you recommend document A or document B?
1 / 1 point

`Document A​`

Document B​


## Question 3

W​hich of the following is true about euclidean distance?
1 / 1 point

 `W​hen comparing similarity between two corpuses, it does not work well when the documents are of different sizes. `


`I​t is the norm of the difference between two vectors.`


I​t is a method that makes use of the angle between two vectors

I​t is the norm squared of the difference between two vectors. 

## Question 4

W​hat is the range of a cosine similarity score, namely s,  in the case of information retrieval where the vectors are positive?
1 / 1 point

$​$ -1 \leq s \leq 1 $$

$​$-\infty \leq s \leq \infty $$

`$​$0 \leq s \leq 1 $$`


 $​$-1 \leq s \leq 0 $$

## Question 5

T​he cosine similarity score of corpus A = (10−1) 
10−1
⎝⎜⎛​10−1​⎠⎟⎞​  and corpus B = (281) 
281
⎝⎜⎛​281​⎠⎟⎞​ is equal to ?
1 / 1 point

 `0.08512565307587486`

0​

1​.251903

-​0.3418283

## Question 6

W​e will define the following vectors, USA = (56)
56
 (56​), Washington = (105)
105
 (105​), Turkey = (31)
31
 (31​), Ankara = (91)
91
 (91​), Russian = (55)
55
 (55​), and Japan = (43)
43
 (43​). Using only the following vectors, Ankara is the capital of what country?
1 / 1 point

J​apan

R​ussia

Morocco

`T​urkey`


## Question 7

P​lease select all that apply. PCA is 
1 / 1 point

`u​sed to reduce the dimension of your data.`


`v​isualize word vectors`

m​ake predictions

l​abel data

## Question 8

P​lease select all that apply. Which is correct about PCA?
1 / 1 point

`Y​ou can think of an eigenvector as an uncorrelated feature for your data.`

`T​he eigenvalues tell you the amount of information retained by each feature.`

I​f working with features in different scales, you do not have to mean normalize. 

`C​omputing the covariance matrix is critical when performing PCA`


## Question 9

I​n which order do you perform the following operations when computing PCA?
1 / 1 point

`m​ean normalize, get Σ\SigmaΣ the covariance matrix, perform SVD, then dot product the data, namely X, with a subset of the columns of U to get the reconstruction of your data. `

m​ean normalize, perform SVD, get Σ\SigmaΣ the covariance matrix, then dot product the data, namely X, with a subset of the columns of U to get the reconstruction of your data. 

get Σ\SigmaΣ the covariance matrix, perform SVD, then dot product the data, namely X, with a subset of the columns of U to get the reconstruction of your data, m​ean normalize.

get Σ\SigmaΣ the covariance matrix, m​ean normalize, perform SVD, then dot product the data, namely X, with a subset of the columns of U to get the reconstruction of your data. 


## Question 10

V​ector space models allow us to 
1 / 1 point

`T​o represent words and documents as vectors. `


`b​uild useful applications including and not limited to, information extraction, machine translation, and chatbots. `
 

`c​reate representations that capture similar meaning. `

b​uild faster training algorithms
