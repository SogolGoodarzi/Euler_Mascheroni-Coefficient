# Euler_Mascheroni-Coefficient
<p align="justify"> Consider an integer like n. If we divide n by the smaller and equal integer r and round the result to the nearest larger integer, during the rounding process we have made an error of $\epsilon_{r}$ for every r. At first glance, it seems that, on average, the mathematical expectation $\epsilon_{r}$ is equal to half, but in 1898, Charles and Possinders proved that the limit value of this error converges to the Weiler-Mascheroni constant. This constant is defined as the limit distance of the nth harmonic number and the logarithm of n. </p>

![image](https://github.com/SogolGoodarzi/Euler_Mascheroni-Coefficient/assets/125180530/bf37470f-0a47-4929-8ae2-1a6f07bad0c5)

### Part a.
<p align="justify"> We are going to calculate the mathematical expectation of error. In the given relationship, it can be seen that the random variable here is the r parameter, because for every r, the obtained error value is equal to $\epsilon_{r}$. Also, because we intend to calculate the mathematical expectation of the error, for this reason, we can understand that the random variable here is the parameter r, whose values ​​change from 1 to n, which is a constant number. </p>

### Part b.
<p align="justify"> According to the mentioned materials, for several different values ​​for large n, we find the result of rounded numbers for dividing the number n by r and calculate their mathematical expectation. According to the diagram, it is clear that these values ​​converge to the Euler-Mascheroni constant. We get the error through the following relationship. </p>

![image](https://github.com/SogolGoodarzi/Euler_Mascheroni-Coefficient/assets/125180530/cec5d67d-8708-421d-a6ab-be692fb67bfb)

<p align="justify"> To calculate the mathematical expectation of the error, as it is known in the program code, we find the desired mathematical expectation by averaging the errors for different n. </p>

![image](https://github.com/SogolGoodarzi/Euler_Mascheroni-Coefficient/assets/125180530/52d44e14-39ba-4172-8640-a22f0c3b5803)

The diagram of the first part, which is related to the convergence of the mathematical expectation of error, is as follows:

![image](https://github.com/SogolGoodarzi/Euler_Mascheroni-Coefficient/assets/125180530/beac855b-27a3-4e28-ab18-7dbdc19b4da3)

As it is clear from the graph, the convergence value of mathematical expectation is 0.5772, which is the Euler-Mascheroni constant.

The graph of the defined value for $\delta_{n}$ is also as follows:

![image](https://github.com/SogolGoodarzi/Euler_Mascheroni-Coefficient/assets/125180530/cb4b8bee-3aa8-4de2-b640-6fb8f7523eb1)

![image](https://github.com/SogolGoodarzi/Euler_Mascheroni-Coefficient/assets/125180530/0a9ec23e-c406-4d95-8ffa-f479553d427f)

<p align="justify"> The convergence value of this graph is almost equal to zero because we subtracted the value of the mathematical expectation from the value of Landa and we saw in the previous graph that the value of the error expectation converged to the same number. </p>
