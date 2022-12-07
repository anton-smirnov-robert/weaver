---
title: "Cantor's diagonal argument"
date: 2022-12-06
draft: false
tags:
- concept
---

One of Cantor's theorem is that the set of all sets of natural numbers is not enumerable. 
The set of real numbers is the set of all set of natural numbers because you form a real number by precising its decimals. It is therefore not an [enumerable set](definition/enumerable%20set.md).

#### Proof: 
We consider the set of all sets of natural numbers $SS=\{S_1,S_2,...\}$ and there characteristic functions $s_1,s_2, ...$ . $s_n(m)=1 \ if \  m\in S_n$  and $0$ if not. We can construct a matrix with $M_{nm}=s_n(m)$. We want to show that there is a set that is not in $SS$. 

Consider the *antidiagonal* sequence  $\{1-s_n(n)\}_n$. If this set is already in $SS$ it means that $\exists n , \forall m , s_n(m)=1-s_m(m)$ . For $m=n$  it would mean that $s_n(n)=1-s_n(n)$. Such $n$  does not exist and therefore, this set is missing from $SS$: is does not contain all sets of natural numbers.
 

#### Sources 

[Boolos2007](reference/Boolos2007.md)

