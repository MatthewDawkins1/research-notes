---
created: 2024-11-29 10:35
---
**Tags:** #Resources #Discovery #Bayesian-Methods #Predictive-Modelling #Bayesian-Nonparametrics  #Dirichlet-Process #Generalised-Linear-Model

**Link:** https://proceedings.mlr.press/v9/hannah10a.html

**Year:** 2024

Dirichlet Process Mixtures of GLMs to capture both non-linearity and non-constant variance in small sized datasets. 

---
### Whats the Key Finding/ Takeaway:

That Dirichlet Process Mixtures of simple estimators can provide power and flexible models with limited or at least less assumptions than other types of models over both continuous and discrete variables. 
### Interesting Extracts:

The general specification for the models presented in this paper is as follows:
$$
\begin{align*} 
	P &\sim DP(\alpha G_0), \\ 
	\theta = (\theta_{i,x}, \theta_{i,y}) \mid P &\sim P, \\ 
	X_i \mid \theta_{i,x} &\sim f_x(\cdot \mid \theta_{i,x}), \\ 
	Y_i \mid X_i, \theta_{i,y} &\sim GLM(\cdot \mid X_i, \theta_{i,y}). 
\end{align*}
$$

Resulting model fit on dataset presented in the paper:

![[Hannah et.al. result.png]]

### What don't I Currently Understand:

- Bayesian Nonparametrics generally 
- The Dirichlet process on a deep fundamental level
- The sections of the paper on posterior constancy

---
### Notes:

TODO....

---
### Google Scholar Searches

- Insert a list of key google scholar searches which relate to this resource 
- ...

