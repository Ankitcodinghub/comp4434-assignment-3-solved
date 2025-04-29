# comp4434-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [COMP4434 Assignment #3 Solved](https://www.ankitcodinghub.com/product/assignment-3-comp4434-big-data-analytics-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115075&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP4434  Assignment #3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Q1. Regularization

[15 points] We use polynomial regression for the prediction task of a dataset. The given dataset includes a train set (train.csv) and a test set (test.csv). To illustrate the effect of regularization, please first implement the following regression models using python language (third-party packages are allowed). Then, plot the data points of the train set and the regression lines of the trained models. Finally, compute the RMSE of the trained models using the test set and make a comparative discussion about underfitting and overfitting.

• Polynomial regression without regularization (polynomial to 5th power)

• L1 Regularized polynomial regression: 𝜆 = 1 and 𝜆 = 100 • L2 Regularized polynomial regression: 𝜆 = 1 and 𝜆 = 100

The given datasets can be downloaded at:

https://drive.google.com/drive/folders/1LSZNIEWf6XKnQtRw8L01tS6yAB67Aad2?usp=sharing

• The initial values for parameters 𝑥 = [0.77 0.48 0.19 0.43 0.31] and 𝜃𝑇 = [0.68

0.44 0.51 0.18

0.36 0.62

0.78]

0.08

0.92

Q2. Recommender System

Build up a collaborative filtering-based recommender system to provide effective hotel recommendation. The training dataset as shown in the table below contains the ratings from 4 users to 3 hotels. The ratings range from 1 point to 5 points.

Hotel 1 Hotel 2 Hotel 3

User 1 5 1 ?

User 2 4 ? 3

User 3 ? 4 5

User 4 3 3 4

We use the gradient descent algorithm to solve cost minimization in the collaborative filtering model. Some settings are as follows.

• The constant learning rate 𝛼 = 0.0002

• The regularization parameter 𝜆 = 0.02

• The dimension for user/item feature vectors 𝐾 = 2

a) [5 points] If we finally obtain 𝑥(1) = [1.268 0.994]𝑇 and 𝜃(3) = [0.271 0.694]𝑇 after the training procedure, what is the rating of user 3 on hotel 1?

b) [10 points] Calculate the values of 𝑥1(1) (i.e., the first element in the item feature vector of hotel 1) and 𝜃1(2) (i.e., the first element in the user feature vector of user 2) after the first iteration.

c) [5 point] Implement the gradient descent algorithm to update the parameters 𝑥 and 𝜃 using python language. Please calculate the ratings of user 2 on hotel 2 after 50 rounds and upload the source code file.

ps. For a) and b), the detailed calculation process is required and the intermediate and final results should be rounded to 3 decimal places.

Q3. Neural Network

[10 points] Consider the following neural network:

Where 𝑎𝑖 = ∑𝑗 𝑤𝑗𝑖𝑧𝑗 𝑧𝑖 = 𝑓𝑖(𝑎𝑖) for 𝑖 = 1,2,3,4 𝑧0 = 𝑎0 (an input neuron) 𝑓3(𝑥) = relu(𝑥) and 𝑓1(𝑥) = 𝑓2(𝑥) = 𝑓4(𝑥) = sigmoid(𝑥). relu(𝑥) corresponds to a rectifier linear unit transfer function defined as: relu(𝑥) = max {0,𝑥}. The cost function is defined as 𝐽(𝑤) = 12 (𝑧4 − 𝑦)2.

(a) Write a function 𝐹 to simulate the neural network.

𝜕𝐽

(b) Assume that we are given a training data 𝑥 = 1.0,𝑦 = 0.1 what is the value of 𝜕𝑤34?
