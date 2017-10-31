---
layout: post
title: "The Jargons of Probability Theory"
date: 2017-10-25
category: math 
tag: probability
---

<div style="text-align: justify;">
There are some jargons in probability that are worth knowing for they keep recurring in many fields of science.
The idea of a function in relation to a probability is widespread used in complex systems, statistical mechanics, quantum mechanics, electromagnetism, and many more. So it is just logical to learn the jargons of probability so that next time it will not appear as wild beasts.
</div>

### Random Variable:
a variable that is subject to variations due to random chance. It is a result of a random experiment, a sampling. 
Since the variable is random you expect to get different values as you obtain multiple samples. 

### Distribution Function:
a function over a general set of values, also called as cumulative distribution function (CDF), or it may be referred to as a probability mass function (PMF). A probability distribution is a function that describes how likely you will obtain the different possible values of the random variable.

### Probability Density Function: 

Density of a continuous random variable, is a function whose value at any given sample (or point) in the sample space (the set of possible values taken by the random variable) can be interpreted as providing a relative likelihood that the value of the random variable would equal that sample. 

PDF is used to specify the probability of the random variable falling within a particular range of values, as opposed to taking on any one value. 

1. Continuous Distribution: <br>
$$ Pr[a \leq X \leq b] = \int_a^b f_{X}(x) dx $$<br>

"What is the probability that X falls between a and b?"

2. Discrete Distribution:<br>
$$  f(t) = \sum p_i \delta (t - x_i) $$



### Entropy:
The entropy of a random variable is a function which attempts to characterize the "unpredictability" of a random variable. Its not about the number of possible outcome, it is also about their frequency. Thought, it sounds like a vague concept, it has a precise mathematical definition.

Take for example a random variable X with values $$ X = \{x_1, x_2, ..., x_n\} $$ and is defined by a probability distribution P(X), the entropy of the random variable is:

$$ H(X) = -\sum P(x) \log P(x) $$


### Joint Entropy:
The entropy of a joint probability distribution, or a multi-valued random variable. 
$$ \eq H(P(X,Y)) = - \sum P(x) log P(x) $$

### Mutual Information:





{% raw %}
  $$a^2 + b^2 = c^2$$ --> note that all equations between these tags will not need escaping! 
 {% endraw %}



When $$a \ne 0$$, there are two solutions to and they are
$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

Test a display math:
$$
   |\psi_1\rangle = a|0\rangle + b|1\rangle
$$
Is it O.K.?
