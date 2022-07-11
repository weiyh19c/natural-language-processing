# Hashing and Machine Translation
Total points 10

## Question 1

A​ssume that your objective is to minimize the transformation of X as similar to Y as possible, what would you optimize to get R? (XR≈Y (XR \approx Y(XR≈Y)
1 / 1 point

`M​inimize the distance between XR and Y `

Maximize the distance between XR and Y 

M​inimize the dot product between XR and Y 

Maximize the dot product between XR and Y 


## Question 2

W​hen solving for RRR, which of the following is true? 
1 / 1 point

C​reate a forloop, inside the forloop: (initialize R, compute the gradient, update the loss

C​reate a forloop, inside the forloop: (initialize R, update the loss, compute the gradient.

`Initialize R, create a forloop, inside the forloop:  (compute the gradient, update the loss)`

Initialize R, compute the gradient, create a forloop, inside the forloop:  (update the loss)


## Question 3

T​he Frobenius norm of A = (1 3 4 5) is
1 / 1 point
`7.14`


## Question 4

A​ssume X∈Rm×n,R∈Rn×n,Y∈Rm×nX \in R^{m \times n}, R \in R^{n \times n}, Y \in R^{m \times n}  X∈Rm×n,R∈Rn×n,Y∈Rm×n which of the following is the gradient of ∥XR−Y∥F2\|XR - Y\|_F^2∥XR−Y∥F2​?
1 / 1 point

`2mXT(XR−Y)\frac{2}{m}  X^T (XR-Y)m2​XT(XR−Y)`

2mX(XR−Y)\frac{2}{m}   X (XR-Y)m2​X(XR−Y)

2m(XR−Y)X\frac{2}{m}    (XR-Y)Xm2​(XR−Y)X

2m(XR−Y)XT\frac{2}{m}  (XR-Y)X^Tm2​(XR−Y)XT


## Question 5

I​magine that you are visiting a city in the US. If you search for friends that are living in the US, would you be able to determine the 2 closest of ALL your friends around the world?
1 / 1 point

Y​es, because I am already in the country and that implies that my closest friends are also going to be in the same country. 

`N​o`


## Question 6

W​hat is the purpose of using a function to hash vectors into values?
1 / 1 point

`T​o speed up the time it takes when comparing similar vectors.`


`T​o not have to spend time comparing vectors with other vectors that are completely different. `


T​o make the search for other similar vectors more accurate. 

It helps us create vectors. 

## Question 7

Given the following vectors, determine the true statements. 

P: 
11

V1V_1 V1​ :
11

V2V_2 V2​: 
22

V3V_3 V3​ :
−1−1

1 / 1 point

`PV1TP V_1^TPV1T​ and PV2TP V_2^TPV2T​ have the same sign.`

PV1TP V_1^TPV1T​ and PV2TP V_2^TPV2T​ are equal in magnitude.

PV1TP V_1^TPV1T​ and PV3TP V_3^TPV3T​ have the same sign.


## Question 8

W​e define H to be the number of planes and hih_ihi​ to be 1 or 0 depending on the sign of the dot product with plane i. Which of the following is the equation used to calculate the hash for several planes. 
1 / 1 point

`∑iH2ihi\sum_{i}^H 2^i h_i∑iH​2ihi​`

∑iH2ihii\sum_{i}^H 2^i h_i^i∑iH​2ihii​

∑iH2ihi\sum_{i}^H 2i h_i∑iH​2ihi​

∑iH2hii\sum_{i}^H 2^{h_i} i∑iH​2hi​i


## Question 9

H​ow can you speed up the look up for similar documents.
1 / 1 point

P​CA

`A​pproximate Nearest Neighbors`


K​-Means

`L​ocality sensitive hashing`


## Question 10

H​ash tables are useful because
1 / 1 point

`a​llow us to divide vector space to regions. `


`s​peed up look up`


c​lassify with higher accuracy

`c​an always be reproduced`
