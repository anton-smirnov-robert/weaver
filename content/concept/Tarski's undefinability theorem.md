---
title: "Tarski's undefinability theorem"
date: 2022-12-12
draft: false
showthedate: true
enabletoc: false
tags:
- concept
---


A [formal system](definition/formal%20system.md)'s truth cannot be defined within the system. Tarksi showed this theorem in 1933. 

#### Proof

- Use [Gödel's numbering](concept/Gödel's%20numbering.md) to encode all possible sentences. We note $[A]$ the code of $A$.
- We suppose $\exists \ V$ a function such that   $$\forall \ A, A\iff V( [A] )$$
- Use the diagonalization lemma (difficult, not explained here) for $\neg V$. It reads $$\exists A, \ A\iff \neg V( [A] )$$
- There is a contradiction. $V$ does not exists. 


#### Sources 
[Standford Encyclopedia ](https://plato.stanford.edu/entries/tarski-truth/) 
[Wikipedia](https://en.wikipedia.org/wiki/Tarski%27s_undefinability_theorem#:~:text=Tarski's%20undefinability%20theorem%2C%20stated%20and,cannot%20be%20defined%20in%20arithmetic.)
[Youtube](https://www.youtube.com/watch?v=wiYdEDDRQzE)

