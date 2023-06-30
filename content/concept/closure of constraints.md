---
title: "closure of constraints"
date: 2023-01-18
draft: true
showthedate: true
enabletoc: false
tags:
- concept
---

Closure requires a fast and a slow [dependence between constraints](definition/dependence%20between%20constraints.md).  
It also requires *direct* dependences between constraints. 
$$ \begin{array}{l}\text { Definition } 4 \text { (Closure) A set of constraints } \mathcal{C} \text { realises overall closure if, for each con- } \\ \text { straint } C_{i} \text { belonging to } \mathcal{C} \text { : } \\ \text { 1. } C_{i} \text { depends directly on at least one other constraint belonging to } \mathcal{C}\left(C_{i}\right. \text { is depen- } \\ \text { dent); } \\ \text { 2. There is at least one other constraint } C_{j} \text { belonging to } \mathcal{C} \text { which depends on } C_{i}\left(C_{i}\right. \\ \quad \text { is generative). } \\ \text { A set } \mathcal{C} \text { which realises overall closure also realises strict closure if it meets the following } \\ \text { additional condition: } \\ \text { 3. } \mathcal{C} \text { cannot be split into two closed sets. }\end{array} $$ 

![](images/Pasted%20image%2020230118122326.png)

Sources:

[Montevil2015](reference/Montevil2015.md)
