# Homework 1 Task 3

---

Answer the following questions based on exercises from *An Introduction to Statistical Learning with Applications in Python*.

## Chapter 2.4 Exercises

---

### Exercise 1 (ISLP exercise 2)

Explain whether each scenario is a **classification or regression** problem, and indicate whether we are most interested in **inference or prediction**. Finally, provide **n** (size of observation dataset) and **p** (number of predictors).

**(a)**  We collect data on 200 protected marine reserves worldwide. For each reserve we record species richness, reserve size, years since establishment, enforcement budget, and proximity to human settlements. We are interested in understanding which factors affect species richness.

> n = 200, p = 4
This is a regression problem and we are most interested in inference. 

---

**(b)** A conservation agency wants to know whether a proposed habitat corridor will successfully support wildlife movement or fail to do so. They collect data on 30 previously established corridors. For each corridor they have recorded whether wildlife movement was successful or unsuccessful, corridor width, length, surrounding land use type, and eight other variables.

> n = 30, p = 11
This is a classification problem and we are most interested in prediction.

---

**(c)** We are interested in predicting weekly average ground-level ozone concentration in a coastal city. We collect weekly data for all of 2019. For each week we record average ozone concentration, sea surface temperature, wind speed, solar radiation, and atmospheric

> n = 52, p = 4
This is a regression problem, and were are most interested in prediction.

---

### Exercise 2 (ISLP exercise 5)

What are the advantages and disadvantages of a very flexible (versus a a less flexible) approach for regression? Under what circumstances might a more flexible approach be preferred to a less flexible approach? When might a less flexible approach be preferred?

> A flexible model can capture more complex relationships. If there are multiple variables which have large amounts of data associated with them, then a more flexible system may work better, and could potentially provide better predictions. However, a less flexible approach would be better suited when you have fewer predictive variables, smaller datasets, or are constrained by computational limitations. So really, the circumstances of your data, variables, and their relationships are what will guide how flexible of an approach you want with regression. 

---

### Exercise 3 (ISLP exercise 6)

Describe the differences between a **parametric** and a **non-parametric** statistical learning approach. What are the **advantages** of a parametric approach to regression or classification (as opposed to a non-parametric approach)? What are its **disadvantages**?

> the parametric approach estimates in two steps. It starts with a functional form for F, and then fits to the model with training data. Since you are constructing the approach around a functional form, you can more easily infer and interpret relationships between the different variables. However, this simpler approach may mean that the predicted F is actually quite different from the "true" F, and thus you are left with poor model fit. On the other hand, the non-parametric does not assume a functional form for F, and instead lets the data determine its form. 