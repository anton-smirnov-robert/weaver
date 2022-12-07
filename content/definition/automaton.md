---
title: "automaton"
date: 2022-12-07
draft: false
showthedate: false
enabletoc: false
tags:
- definition
---

Formally, a finite automaton can be defined as 
$$\begin{array}{l}\text { A finite automaton (or machine) is a } 5 \text {-tuple } M=\left(Q, \Sigma, \delta, q_{0}, F\right) \text {, where } \\ \text { 1. } Q \text { is a finite set called the states, } \\ \text { 2. } \Sigma \text { is a finite set called the alphabet, } \\ \text { 3. } \delta: Q \times \Sigma \longrightarrow Q \text { is the transition function, } \\ \text { 4. } q_{0} \in Q \text { is the start state, and } \\ \text { 5. } F \subseteq Q \text { is the set of accept states. }{ }\end{array}$$
It takes as input an binary *string* to gives the states $q_i$ . Some input strings are accepted (because you reach the final state or "accepted state"), some are rejected. All the input strings form the *language* of the machine $L(M)$. 


#### Sources 
[Sipser2013](reference/Sipser2013.md)    
[MIT Open cour. es](https://ocw.mit.edu/courses/18-404j-theory-of-computation-fall-2020/pages/syllabus/)