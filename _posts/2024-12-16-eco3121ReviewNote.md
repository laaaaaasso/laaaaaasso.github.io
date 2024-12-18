# Lecture notes

## Lecture 1: Introduction and Statistics Review

### 1. basic concepts

**Data** are the facts and figures collected, analyzed, and summarized for presentation and interpretation.

**Data set**: All the data collected in a particular study are referred to as the data set for the study.

**Elements** are the entities on which data are collected.

**A ****variable** is a characteristic of interest for the elements.

**observation**: The set of measurements obtained for a particular element is called an observation.

**RK:**

**A data set with n elements contains n observations.  **

**The total number of data values in a complete data set is the number of elements multiplied by the number of variable**

### 2. Different kinds of economic data sets

**• ****Cross-sectional data - CS data(截面数据):**

**definition:** Sample of individuals, households, firms, cities, states, countries, or other units of interest at a given point of time/in a given period.

**CS observations are often ****independent**.

**application**: Cross-sectional data typically encountered in applied microeconomics

**example**: Class attendance and final exam score

**CS data set:**

**In this course, we will assume that a cross-sectional data set represents a ****random sample**. Random sampling generates observations that are independent and identically distributed. Intuitively, a random sample is representative of the population of  interest, and gives us the best chance of learning about the  population.

**• Time series data - TS data(时间序列数据):**

**definition:**  Observations of a variable or several variables over time.

**Time series observations are typically ****serially correlated**. Typical features of time series: **trends and seasonality**.

**applications**: applied macroeconomics and finance

**example**: daily stock price

**• Pooled cross sections(集合截面数据)**:

**definition:** Two or more cross sections are combined in one data set, these sections are drawn independently of each other.

**example**: Evaluate effect of change in property taxes on house prices

![image-20241216153603296](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216153603296.png?lastModify=1734369653)

**• Panel/Longitudinal data(面板/纵向数据):**

**definition:** The same cross-sectional units are followed over time.

**Panel data have a cross-sectional and a time series dimension.**

**example**: City crime statistics; each city is observed in two years

![image-20241216153844657](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216153844657.png?lastModify=1734369653)

### 3. Causality and the notion of CP (ceteris paribus)

**Definition** of causal effect of on: “How does variable y change if variable x is changed **but all other relevant factors are held constant**”

**example:** ** **studying effect of law enforcement on city crime level:

**“If a city is randomly chosen and given ten additional police officers, by  how much would its crime rate fall?” **

**Alternatively: “If two cities are the same in all respects, except that city A  has ten more police officers than city B, by how much would the two  cities‘ crime rates differ?”**

**What are the potential ‘‘confounding factors‘‘?**

**• Experiment: **

**• Randomly assign number of police officers to a large number of cities **

**• In reality, number of police officers will be determined by crime rate  (simultaneous determination of crime and number of police)**

## Lecture 2: Math Review

### 1. What is Econometrics?

#### The Fundamental Question: What is the relationship between *Y* and *X*?

**If we are studying the relation of Unemployment and minimum wage:**

**given observation:**

![image-20241216162159210](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216162159210.png?lastModify=1734369653)

**how can we draw the line:**

![image-20241216162322234](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216162322234.png?lastModify=1734369653)

**we need ****Regression**

**definition:** [Noun] A return to a former or less developed state. [Statistics] A measure of the relation between the mean value of one variable and corresponding values of other variables.

**our goal is to find a way to summarize the key message from the data distribution while minimizing the information we miss.**

**There is a long tradition of using the expectation/average/mean to describe random data. Maybe it’s just intuition and we have never seriously justified this approach. It turns out the expectation can “minimize the missing information”.**

![image-20241216163031003](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216163031003.png?lastModify=1734369653)

![image-20241216163053420](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216163053420.png?lastModify=1734369653)

### 2. Steps in Empirical Economic Analysis

### 3. The Structure of Economic Data

### 4. Causality and the notion of CP in Econometric Analysis

### 5. Math Review

**The natural logarithm Example**:

![image-20241216163821460](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216163821460.png?lastModify=1734369653)

**When ***x* changes 1%, *y* changes *𝛽*1%. This log-log formulation is widely used in macroeconomics.

**(In)dependence:**

*X* and *Y* are **independent** if and only if ![image-20241216163948804](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216163948804.png?lastModify=1734369653)

**If ***X* and *Y* are independent:

**E[***X*|*Y*] = E[*X*]*,*E[*Y*|*X*] = E[*Y*]

**E[***XY*] = E[*X*]E[*Y*]

**Cov(***X**,**Y*) = 0

**Var(***X* +*Y*) = Var(*X*) +Var(*Y*)

**Expectation:**

**The expectation / expected value of a random variable is defined as**![image-20241216164144317](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216164144317.png?lastModify=1734369653)

![image-20241216164236735](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216164236735.png?lastModify=1734369653)

**Variance and standard deviation:**

**The variance measures the “spread” of a random variable from its expected value. It is defined as:**![image-20241216164320465](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216164320465.png?lastModify=1734369653)

**To compute the variance, let ***𝜇* = E [*X*].

![image-20241216164349993](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216164349993.png?lastModify=1734369653)

**Properties:**

* **Var (***X*) = 0 if and only if Pr (*X* = constant) = 1.
* **For any constants ***a* and *b*, ![image-20241216164451296](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216164451296.png?lastModify=1734369653)

**Standard deviation is the (positive) square root of the variance**

**Covariance and correlation:**

**Covariance** measures the magnitudes and directions in which two random variables move together.

**definition:**![image-20241216164604610](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216164604610.png?lastModify=1734369653)

**properties:**

* **A positive value means that ***X* and *Y* tend to increase / decrease at the same time;vice versa
* **If ***X* and *Y* are independent, then Cov (*X**,**Y* ) = 0. But the converse is generally not true.
* **The magnitude of covariance is hard to interpret. A big covariance could either mean that ***X* and *Y* are closely related, or that at least one of them
  **has a big variance.**

**The ****correlation** normalizes the coviance so that a larger absolute value means stronger comovement.

**definition: **![image-20241216164824341](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216164824341.png?lastModify=1734369653)

**Properties:**

* **By Hölder’s inequality: −1 ≤ Corr (***X**,**Y* ) ≤ 1*.*

![image-20241216165058731](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216165058731.png?lastModify=1734369653)

**Conditional expectation:**

**Denoted as E [***Y* |*X*]. It is a function of *X*. When *X* takes specific values, the conditional expectation E [*Y* |*X*] changes values accordingly.

**Properties: **

![image-20241216165235564](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216165235564.png?lastModify=1734369653)

* **Conditional expectation has similar properties as unconditional expectation, such as linearity and Jensen’s Inequality.**
* **One big difference: conditional expectation is a random variable, whereas unconditional expectation is a constant.**

**The Normal Distribution:**

**standard normal pdf:**![image-20241216165355932](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216165355932.png?lastModify=1734369653)

*Y* = *𝜎X* + *𝜇* also has a normal distribution with mean *𝜇* and variance *𝜎* ^2 :![image-20241216165449971](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216165449971.png?lastModify=1734369653)

## Lecture 3: The Simple Regression model:

### outline:

1. **Definition of Simple Regression Model:**
2. **Deriving the Ordinary Least Squares Estimates:**
3. **Properties of OLS on any Sample of Data:**
4. **Units Measurement and Functional Form:**
5. **Testing**
6. **Confidence Interval**

### Definition of Simple regression Model:

**“Explains variable y in terms of variable x”:**

![image-20241216170718885](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216170718885.png?lastModify=1734369653)

**All other factors that affect are in u. We want to know how y changes when x  changes, holding u fixed. **

![image-20241216230845357](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216230845357.png?lastModify=1734369653)

**example:**

** **![image-20241216230944380](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216230944380.png?lastModify=1734369653)

**can we conclude causal interpretation? No! because we don't know whether u and x are correlated or not.**

![image-20241216231231368](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216231231368.png?lastModify=1734369653)

**the four SLR(Standard assumptions for the Linear Regression) assumptions:**

![image-20241216233241095](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216233241095.png?lastModify=1734369653)

assumption SLR.1:![image-20241216233621980](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216233621980.png?lastModify=1734369653)

assumption SLR.2:

![image-20241216233727063](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216233727063.png?lastModify=1734369653)

**assumption SLR.3:**

![image-20241216235001192](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216235001192.png?lastModify=1734369653)

**assumption SLR.4:**

![image-20241216235304570](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241216235304570.png?lastModify=1734369653)

**RK: assumption SLR.4 is actually two parts:**

![image-20241217011835612](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241217011835612.png?lastModify=1734369653)

**Population regression function (PFR)**

**The conditional mean independence assumption implies that:**

![image-20241217011956856](file:///C:/Users/hzh/AppData/Roaming/Typora/typora-user-images/image-20241217011956856.png?lastModify=1734369653)

This means that the average value of the dependent variable can be expressed as a linear function of the explanatory variable:
![1734369711302](images/2024-12-16-eco3121ReviewNote/1734369711302.png)

### Deriving the Ordinary Least Squares Estimates:

To estimate regression model we need data, suppose we have a random sampleof n observations:
![1734369959517](images/2024-12-16-eco3121ReviewNote/1734369959517.png)

![1734370003437](images/2024-12-16-eco3121ReviewNote/1734370003437.png)

yi(hat) estimate E(yi|xi)

we need to minimize residuals to obtain the best estimates(b0hat, b1hat)
![1734370113701](images/2024-12-16-eco3121ReviewNote/1734370113701.png)
two equations come from taking derivatives of b0hat,b1hat respectively

![1734370171218](images/2024-12-16-eco3121ReviewNote/1734370171218.png)

![1734370181036](images/2024-12-16-eco3121ReviewNote/1734370181036.png)

![1734370194172](images/2024-12-16-eco3121ReviewNote/1734370194172.png)

<u>b0hat and b1hat get</u>

![1734370282417](images/2024-12-16-eco3121ReviewNote/1734370282417.png)

![1734370419220](images/2024-12-16-eco3121ReviewNote/1734370419220.png)

### Properties of OLS on any sample of data

For fitted values and residuals:

![1734370486626](images/2024-12-16-eco3121ReviewNote/1734370486626.png)

For Algebraic properties of OLS regression:

![1734370515915](images/2024-12-16-eco3121ReviewNote/1734370515915.png)

**Expected value of the OLS estimators**

![1734370588073](images/2024-12-16-eco3121ReviewNote/1734370588073.png)

![1734370678729](images/2024-12-16-eco3121ReviewNote/1734370678729.png)

#### E(b1hat) = b1 (unbiasedness of OLS)

and here the expected value means averaging across different random samples.

Proof:

![1734370841475](images/2024-12-16-eco3121ReviewNote/1734370841475.png)

SSTx != 0 so b1hat exits

![1734370881903](images/2024-12-16-eco3121ReviewNote/1734370881903.png)

so:

![1734370960685](images/2024-12-16-eco3121ReviewNote/1734370960685.png)

![1734370985812](images/2024-12-16-eco3121ReviewNote/1734370985812.png)

RK:

![1734371007727](images/2024-12-16-eco3121ReviewNote/1734371007727.png)

![1734371099153](images/2024-12-16-eco3121ReviewNote/1734371099153.png)

Theorem 2.1: Unbiasedness of OLS:

![1734371547986](images/2024-12-16-eco3121ReviewNote/1734371547986.png)

Interpretention of unbiaseness:

* The estimated coefficients may be smaller or bigger, depending on the sample which is from random draw.
* However, ON AVERAGE, they will be equal to the values that depicts true relationship between y and x in population. Here "ON AVERAGE" means sampling and estimating are repeated many times
* In a given sample, estimates may differ a lot from the true values.

#### Variances of the OLS estimators:

![1734371996930](images/2024-12-16-eco3121ReviewNote/1734371996930.png)

here we introduce SLR.5:

![1734372020981](images/2024-12-16-eco3121ReviewNote/1734372020981.png)

Homoskedasticity(同方差性)

![1734372258610](images/2024-12-16-eco3121ReviewNote/1734372258610.png)

E(u^2|x) = Var(ui|xi) + (E(u|x))^2 = Var(ui|xi)

![1734372364414](images/2024-12-16-eco3121ReviewNote/1734372364414.png)

![1734372411578](images/2024-12-16-eco3121ReviewNote/1734372411578.png)

三个相同分布形状

![1734372447735](images/2024-12-16-eco3121ReviewNote/1734372447735.png)

this is Heteroskedasticity(异方差性)!  in the Wage and Education example

Theorem2.2: Sampling variances of OLS estimators:

![1734372623495](images/2024-12-16-eco3121ReviewNote/1734372623495.png)

compute Var(b1hat)

![1734407844486](images/2024-12-16-eco3121ReviewNote/1734407844486.png)

![1734408036724](images/2024-12-16-eco3121ReviewNote/1734408036724.png)

![1734408122479](images/2024-12-16-eco3121ReviewNote/1734408122479.png)

#### Estimating the error variance:

![1734408258432](images/2024-12-16-eco3121ReviewNote/1734408258432.png)

what if we try to take OLS residuals(uihat) as the estimate of ui? Is this biased?  Yes! it's biased

![1734408397059](images/2024-12-16-eco3121ReviewNote/1734408397059.png)

![1734408419047](images/2024-12-16-eco3121ReviewNote/1734408419047.png)

![1734413027579](images/2024-12-16-eco3121ReviewNote/1734413027579.png)

Theorem 2.3: unbiased estimator of σ^2:

![1734413214524](images/2024-12-16-eco3121ReviewNote/1734413214524.png)

σhat is called the standard error of the regression, it is an estimate of the standard deviation of the error in the regression

![1734413381811](images/2024-12-16-eco3121ReviewNote/1734413381811.png)

(se(b1hat) )^2= Var(b1hat)

R^2 measurement:

![1734415650978](images/2024-12-16-eco3121ReviewNote/1734415650978.png)

SST: total variation in yi

SSE: total variation captured by regression

SSR: total variation in error

![1734415668205](images/2024-12-16-eco3121ReviewNote/1734415668205.png)

![1734415685703](images/2024-12-16-eco3121ReviewNote/1734415685703.png)

RK:

* R^2 = 0 means no linear relationship between yi and xi, R^2 = 1 means perfect linear relationship
* As R^2 increases, the yi are closer an closerr to falling on the OLS regression line
* R^2 is a useful summary measuree but tells us nothing about causality(而是仅仅反应统计关联性).Having a high R^2 is neither necessary nor sufficient to thier causality

#### Summary of Simple Regression Model:

![1734413489326](images/2024-12-16-eco3121ReviewNote/1734413489326.png)

![1734413503164](images/2024-12-16-eco3121ReviewNote/1734413503164.png)

![1734413527904](images/2024-12-16-eco3121ReviewNote/1734413527904.png)

![1734413567400](images/2024-12-16-eco3121ReviewNote/1734413567400.png)

### Units of Measurement and Functional Form

![1734416069381](images/2024-12-16-eco3121ReviewNote/1734416069381.png)

### Testing

assumption SLR.6:(Normality of error terms)

![1734415496557](images/2024-12-16-eco3121ReviewNote/1734415496557.png)

more in following lectures

## Lecture 4 Multivariate Regression Model

### outline

* Motivation for mutiple Regression
* Mechanics and interpretation of OLS
* The expected value of the OLS Estimators
* The variances of OLS estimators

### Motivation for MLR

#### let's explain by example:Final exam score and missed classes

In the simple linear regression model:

![1734416332634](images/2024-12-16-eco3121ReviewNote/1734416332634.png)

part of the error term would be student's ability. priGPA is primary GPA, we use it as a proxy for student's ability.

In simple regression, priGPA(explanatory variable) would be included in u(error term) which would be correlated with missed (another explanatory variable) causing the b1hat to be biased.

#### advantage of MLR:

![1734416812303](images/2024-12-16-eco3121ReviewNote/1734416812303.png)

example:

![1734416862470](images/2024-12-16-eco3121ReviewNote/1734416862470.png)

#### definition of MLR:

![1734417042751](images/2024-12-16-eco3121ReviewNote/1734417042751.png)

example:

![1734417133144](images/2024-12-16-eco3121ReviewNote/1734417133144.png)

#### OLS estimation of MLR:

![1734417171353](images/2024-12-16-eco3121ReviewNote/1734417171353.png)

### Mechanics and interpretation of OLS

let's consider sample regression function with two independent variables:![1734417252983](images/2024-12-16-eco3121ReviewNote/1734417252983.png)

to obtain OLS estimates, we need data:

![1734417316431](images/2024-12-16-eco3121ReviewNote/1734417316431.png)

#### Deriving the OLS estimate

choose b0hat , b1hat and b2hat to minimize the sum of squared residuals:

![1734417399030](images/2024-12-16-eco3121ReviewNote/1734417399030.png)

![1734417420592](images/2024-12-16-eco3121ReviewNote/1734417420592.png)

![1734417437619](images/2024-12-16-eco3121ReviewNote/1734417437619.png)

#### Interpreting the OLS Regression Line

the slope coefficients now explictly have partial effect, or ceteris paibus(CP) interpretations. Consider:

![1734417530499](images/2024-12-16-eco3121ReviewNote/1734417530499.png)

then:

![1734417545241](images/2024-12-16-eco3121ReviewNote/1734417545241.png)

![1734417562444](images/2024-12-16-eco3121ReviewNote/1734417562444.png)

![1734417579274](images/2024-12-16-eco3121ReviewNote/1734417579274.png)

example:

![1734417603120](images/2024-12-16-eco3121ReviewNote/1734417603120.png)

important:
the coefficient on *priGPA* means that one more point on prior GPA predicts a final exam score that is 3.24 points higher, holding *missed* fixed

#### A "Parialling out" intepretation

![1734417887302](images/2024-12-16-eco3121ReviewNote/1734417887302.png)

![1734417938014](images/2024-12-16-eco3121ReviewNote/1734417938014.png)

![1734418004998](images/2024-12-16-eco3121ReviewNote/1734418004998.png)

#### properties of OLS pn any sample of data

![1734418132598](images/2024-12-16-eco3121ReviewNote/1734418132598.png)

![1734418159148](images/2024-12-16-eco3121ReviewNote/1734418159148.png)

RK:

add one explanatory variable to the regression , the R^2 MUST increase

example:

![1734418325457](images/2024-12-16-eco3121ReviewNote/1734418325457.png)

![1734418350959](images/2024-12-16-eco3121ReviewNote/1734418350959.png)

General RK on R^2:

even if R^2 is small, regression may still provide good estimates of ceteris parobus effects.

### Expected value of the OLS estimators

![1734418508270](images/2024-12-16-eco3121ReviewNote/1734418508270.png)

![1734418541569](images/2024-12-16-eco3121ReviewNote/1734418541569.png)

RK on MLR.3:

* MLR.3 only forbid perfect collinearity/correlation between explanatory variables, imperfect correlation is allowed(Cov(x1,x2) != 1)
* no constant explanatory variable

example of violating MLR.3:

![1734418762582](images/2024-12-16-eco3121ReviewNote/1734418762582.png)

![1734418781007](images/2024-12-16-eco3121ReviewNote/1734418781007.png)

example of MLR.4:

![1734418814521](images/2024-12-16-eco3121ReviewNote/1734418814521.png)

two more terms: endogenous and exogenous:

* Explanatory variables that are correlated with the error term are called endogenous; endogeneity is a violation of assumption MLR.4
* Explanatory variables that are uncorrelated with the error term are called exogenous; MLR.4 holds if all explanatory variables are exogenous

RK:

Exogeneity is the key assumption for a causal interpretation of the regression, and for unbiasedness of the OLS estimators

Theorem 3.1:

![1734424244102](images/2024-12-16-eco3121ReviewNote/1734424244102.png)

to estimate bjhat:

![1734424304315](images/2024-12-16-eco3121ReviewNote/1734424304315.png)

#### oversprcifying

includign irrelevant variables in a regression model:

![1734424424030](images/2024-12-16-eco3121ReviewNote/1734424424030.png)

#### underspecofying

omitting relevant variable:

![1734424478379](images/2024-12-16-eco3121ReviewNote/1734424478379.png)

this leads to bias:

![1734424561072](images/2024-12-16-eco3121ReviewNote/1734424561072.png)

![1734424592779](images/2024-12-16-eco3121ReviewNote/1734424592779.png)

![1734424632677](images/2024-12-16-eco3121ReviewNote/1734424632677.png)

eg:

![1734424837389](images/2024-12-16-eco3121ReviewNote/1734424837389.png)

![1734425122681](images/2024-12-16-eco3121ReviewNote/1734425122681.png)

#### summary

![1734425209897](images/2024-12-16-eco3121ReviewNote/1734425209897.png)

### Variances of the OLS estimators

assumption MLR.5(Homoskedasticity)

e.g.

![1734425868387](images/2024-12-16-eco3121ReviewNote/1734425868387.png)

short notation:

Var(ui|xi) = σ^2 here xi is a vector

we have 5 MLR now, they are called Gauss Markov assumptions in MLR:

![1734425941448](images/2024-12-16-eco3121ReviewNote/1734425941448.png)

![1734425993939](images/2024-12-16-eco3121ReviewNote/1734425993939.png)

#### Theorem 3.2(Sampling variances of the OLS slo[e estimators)

![1734426068213](images/2024-12-16-eco3121ReviewNote/1734426068213.png)

induction:

![1734426116987](images/2024-12-16-eco3121ReviewNote/1734426116987.png)

#### Components of OLS Variances

the error variance:
![1734426301572](images/2024-12-16-eco3121ReviewNote/1734426301572.png)

the total sample variation in the explanatory variable:

![1734426355864](images/2024-12-16-eco3121ReviewNote/1734426355864.png)

linear relationship among the independent variables

![1734426396315](images/2024-12-16-eco3121ReviewNote/1734426396315.png)

example:

![1734426664568](images/2024-12-16-eco3121ReviewNote/1734426664568.png)

maybe because *avgmin* and *points* are correlated, so Rj^2 increase, Var(bjhat) increase

#### About  multicollinearity:

![1734426832718](images/2024-12-16-eco3121ReviewNote/1734426832718.png)

but we can detect multicollinearity by **variance inflation factors:**(VIF)

![1734426922560](images/2024-12-16-eco3121ReviewNote/1734426922560.png)

## Lecture 5: Inference in Regression Model

## Lecture 6: Dummy Variables:

### outline

* A Single Dummy Variable
* Dummy Variables for Multiple Categories
* Interactions Involvinig Dummy Variables
* The Linear Probility Model

### A single dummy variable

To incorporate qualitative information(定性信息)

e.g. :

![1734427394867](images/2024-12-16-eco3121ReviewNote/1734427394867.png)

graph illustration(appeared in Mid)

![1734427454612](images/2024-12-16-eco3121ReviewNote/1734427454612.png)

e.g. of explaining the coefficiency of dummy variable:

![1734427628983](images/2024-12-16-eco3121ReviewNote/1734427628983.png)

### Dummy variables for multiple categories

#### processes of using dummy variables for multiple categories

1): define membership in each category by a dummy variable

2): leave out one category (which becomes the base)

e.g.

![1734428727516](images/2024-12-16-eco3121ReviewNote/1734428727516.png)

#### using dummy variable to handle ordinal information

eg:

![1734428988829](images/2024-12-16-eco3121ReviewNote/1734428988829.png)

not appropriate because *CR* is an ordinal infromation

should be:

![1734429033298](images/2024-12-16-eco3121ReviewNote/1734429033298.png)

RK:

All effects are measured comparing the worst case(CR=0 in this case)

how about too many values of ordinal variables? We break it down to catrgories:

e.g.

![1734429153592](images/2024-12-16-eco3121ReviewNote/1734429153592.png)

### Interactions involving dummy variables

We don't need to list all categories facing multiple dummy variables(sometimes too many!) we can use interaction between variables instead.

e.g.

![1734429324549](images/2024-12-16-eco3121ReviewNote/1734429324549.png)

interactions allow different slopes:

![1734429456588](images/2024-12-16-eco3121ReviewNote/1734429456588.png)

![1734429473572](images/2024-12-16-eco3121ReviewNote/1734429473572.png)

Hypothesis:

![1734429632473](images/2024-12-16-eco3121ReviewNote/1734429632473.png)

graphical illustration:(appeared in Mid)

![1734429670254](images/2024-12-16-eco3121ReviewNote/1734429670254.png)

e.g. for testing

![1734429871234](images/2024-12-16-eco3121ReviewNote/1734429871234.png)

![1734429891004](images/2024-12-16-eco3121ReviewNote/1734429891004.png)

![1734429909242](images/2024-12-16-eco3121ReviewNote/1734429909242.png)

![1734429952014](images/2024-12-16-eco3121ReviewNote/1734429952014.png)
