## Logistic Regression(LR)

In this article, different from other blogs, we will talk about LR algorithm in a reverse order. We will start from the high level concept to the detailed equation.  
LR is a very basic machine learning classification algorithm. We could not only get the classification result by this algorithm, but also the confidence of the classification result.  
Firstly, let's start from the samples. A sample x has m features in total. The training process is attaching a coefficient to each of the feature. Thus, when predicting a new sample belongs to which class, we could extract the feature and calculate the z value by the coefficient. After getting the z value, we could pass z to the predicting function to see which class it belongs to and the confidence is the result of prediction function. So, the goal of LR is training the coefficients.


blogs:  
[1](http://lib.csdn.net/article/machinelearning/3398)  
[2](https://www.leiphone.com/news/201608/WosBbsYqyfwcDNa4.html)  
[3](http://blog.csdn.net/suipingsp/article/details/41822313)  
[4](http://blog.csdn.net/dinosoft/article/details/46493845)
