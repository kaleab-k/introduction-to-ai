class: middle, center, title-slide

# Introduction to Artificial Intelligence

Lecture 1: Machine Learning

<br><br>
Kaleab A. Kinfu<br>
[kinfu@jhu.edu](mailto:kinfu@jhu.edu)

???

R: develop linear regression / OLS  further ---> up to the analytical solution

---

# Today

.center.width-50[![](figures/lec1/sl-cartoon.png)]

Make our agents capable of self-improvement through a **learning** mechanism.
- Machine Learning Problems 
- Machine Learning Process
- Machine Learning Tools 
- Machine Learning Mathematics 
- Machine Learning Resources

.footnote[Image credits: [CS188](https://inst.eecs.berkeley.edu/~cs188/), UC Berkeley.]

---

class: middle

# Machine learning

---

class: middle

.center[
.width-40[![](figures/lec1/cat.jpg)] &nbsp; &nbsp;
.width-40[![](figures/lec1/dog.jpg)]
]

.exercise[How would you write a computer program that recognizes cats from dogs?]

---

class: middle

.center.width-60[![](figures/lec1/cat1.png)]

---


class: black-slide, middle

.center.width-50[![](figures/lec1/cat2.png)]

.center[The good old-fashioned approach.]

---


class: black-slide, middle

.center.width-80[![](figures/lec1/cat3.png)]

---


class: black-slide, middle

.center.width-80[![](figures/lec1/cat4.png)]

---

class: middle

.center.width-100[![](figures/lec1/catordog-flow.gif)]

.center[The deep learning approach.]

---

class: middle
# What is Machine Learning 
<br/>
.slide_left.width-110[![](figures/lec1/ML_Def.png)]
---
# What is Machine Learning
<br/> 
.slide_left.width-110[![](figures/lec1/ML_Def_2.png)]
---
# What is Machine Learning 
<br/>
.slide_left.width-110[![](figures/lec1/ML_Def_3.png)]
---
# Machine Learning: Why?
<br/>
<br/>
.slide_left.width-110[![](figures/lec1/ML_Why.png)]
---
# Programming vs ML
.slide_left.width-110[![](figures/lec1/ProgVsML.png)]
---

# What is Machine Learning

## ML: What is it good for?

- *Problems with longs lists of rules* 
    - when the traditional approach fails, machine learning may help.
- *Continually changing environments* 
    - machine learning can learn and adapt to new scenarios. 
- *Discovering insights within large collections of data* 
    - can you imagine trying to go through every transaction your (large) company has ever had by hand?

---

# What is Machine Learning

## ML: Terminology

- *Algorithms:* 
    - A set of rules and statistical techniques used to learn patters from data.
- *Model:* 
    - A model is what is trained using an ML algorithm.
- *Predictor Variable:* 
    - It is a feature(s) of the data that can be used to predict the output. 
- *Response Variable:* 
    - It is the output variable that needs to be predicted by using the predictor variables.
- *Training Data:* 
    - The data that is used to build the ML model. 
- *Testing Data:* 
    - The data that is used to evaluate the generalization of the trained ML model.   
