---
title: "Shannon's theory of information transmission"
date: 2022-12-07
draft: false
showthedate: true
enabletoc: false
tags:
- concept
---
Be $X$  a random variable with $X\in\{x_1,x_2,...,x_n\}$ and $p_i=\mathbb{P}(X=x_i)$. Shannon relates the amount of information of one string to the amount of surprise of seeing it. The information is defined as $$I(X) = - \log(P(X))$$and the expected value gives the amount of  "**information, choice or uncertainty**" — [Shannon1948](reference/Shannon1948.md) as follows  $$H(X)=E(I(X))=-\sum_i p_i \log(p_i)$$This formula happens to be the same as the one for Gibbs [entropy](definition/entropy.md) (with an additional Boltzmann constant) in the framework of the [second principe of thermodynamics](concept/second%20principe%20of%20thermodynamics.md). Therefore, Shannon makes the link between information and positive entropy (see [Brillouin's relation between entropy and information](concept/Brillouin's%20relation%20between%20entropy%20and%20information.md)). This is peculiar because as entropy (and disorder) increases, information is lost. It is now preferred to give the name **entropy** to $H(X)$.  We use the meaning of **uncertainty** in this case. 

#### Exemple(s)
A series of fair coin tosses have a maximal entropy $H$ since all throw are equiprobable (maximal uncertainty). 

#### Sources 
[Shannon1948](reference/Shannon1948.md)
note [on Longo2012](note/on%20Longo2012.md)
