# ee25745-1--exercise-5-solved
**TO GET THIS SOLUTION VISIT:** [EE25745-1 -Exercise 5 Solved](https://www.ankitcodinghub.com/product/ee25745-1-solved-5/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112808&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE25745-1 -Exercise 5  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
• Reports should include answers to the questions, diagrams, charts, and explanation of your methods.

• MATLAB codes should be attached to your reports. Codes are also considered to be well-written with appropriate comments.

• It is suggested to use MATLAB Live Script for preparing your reports more conveniently.

• Reports should be uploaded to courseware.

• Naming Format: HW6_StudentNumber

1. Since

𝜋

One can compute an approximate value for 𝜋 using numerical integration of the given function.

(a) Use symbolic math toolbox to verify this integration.

(b) Use the Midpoint, Trapezoid, Simpson, and Gauss methods to compute an approximate value for this integral.

Use 5 different values for h: 0.1, 0.2, 0.3, 0.4, and 0.5. It’s highly recommended to write a function with appropriate arguments for numerical integration.

(c) Plot error of each method versus h and compare them.

(d) Is there any point beyond which decreasing h yields no further improvement? Why?

2. In this exercise we will experiment with numerical differentiation using the table below:

t 0.0 1.0 2.0 3.0 4.0 5.0

y 1.0 2.7 5.8 6.6 7.5 9.9

For each of the following methods for estimating the derivative, compute the derivative of the original data and also experiment with randomly perturbing the y values to determine the sensitivity of the resulting derivative estimates. For each method, comment on both the reasonableness of the derivative estimates and their sensitivity to perturbations. Note that the data are monotonically increasing, so one might expect the derivative always to be positive.

(a) 2, 3, 4 points, symmetric at each of the given t values.

(b) 2, 3, 4 points, backward at each of the given t values.

(c) 2, 3, 4 points forward at each of the given t values.

(d) (Optional) For n=0,1,…,5 fit a polynomial of degree n by least square to the data, then differentiate the resulting polynomial and evaluate the derivative at each of the given t values.

3. The population of two species, a prey denoted by 𝑦1 and predator denoted by 𝑦2, can be modeled by a system of ODEs

𝑦1′ = 𝑏𝑦1 − 𝑐𝑦1𝑦2

𝑦2′ = −𝑑𝑦2 + 𝑐𝑦1𝑦2

The parameters b and d govern the birth rate of prey and death rate of predators, respectively, and the parameter c governs the interaction of two populations. Assume the parameter values to be b=1, d=10, and c=1, and initial conditions 𝑦1(0) = 0.5 and 𝑦2(0) = 1 (the populations are normalized, and we treat them as continuous variables)

(a) Write a MATLAB function for solving a system of ODEs with second-order Runge-Kutta method and fourth-order RungeKutta method, your function should have the structure shown below:

𝑦1′ = 𝑓1(𝑡, 𝑦1, 𝑦2)

{𝑦2′ = 𝑓2(𝑡, 𝑦1, 𝑦2)

𝑦1(0),𝑦2(0)

[𝑦1(𝑡), 𝑦2(𝑡)] = 𝑓𝑢𝑛𝑐𝑡𝑖𝑜𝑛(𝑓1, 𝑓2, 𝑦1(0),𝑦2(0),ℎ, 𝑡, 𝑀𝑒𝑡ℎ𝑜𝑑)

(b) Use your function to solve the system of prey and predator with both methods, integrating to t=10.

(c) Plot each of the two populations as a function of time and on a separate graph plot the trajectory of the point (𝑦1(𝑡),𝑦2(𝑡)) in the plane as a function of time. The latter is sometimes called a “phase portrait”.

4. (Optional) We want to approximate

𝑑𝑥

(a) Use symbolic math toolbox for computing the integral.

(b) Which of methods between Trapezoid, Midpoint, and Simpson is applicable for this integration? Why?

(c) Now use the appropriate method with ℎ = 0.01,ℎ = 0.001 for approximating the integral and compare the results.

(d) Suggest a strategy for improving accuracy but without the expense of increasing computation intensity.

Justify your strategy and compare the error with part c.
