---
title: "Turing machine"
date: 2022-12-07
draft: false
showthedate: true
enabletoc: false
tags:
- concept
---
In 1936, Turing introduces the idea of a “computing machine”, latter called “Turing machine”. He pictures not a mecanism but a person — “Turing's architect” according to ([Schrodinger1944](reference/Schrodinger1944.md)) Turing introduced ([Turing1936](reference/Turing1936.md)) this machine trying to answer questions regarding decidability. A Turing machine is an [automaton](definition/automaton.md) with an unlimited and unrestricted memory. It is a model of everything that can do today's computers. It requires a (readable, writtable, and movable) infinite 1D bit register — a tape. Turing has shown that those elementary instructions are enough to do elaborate any sophisticated program that are themselves encoded on the tape. The Turing machine allocates a data space to make the computation and another one where the programs are encoded. The operating system read the instructions as it computes the program and change the input binary string. Increasing the complexity of the machine (e.g. alphabet, dimensions) does not change the class of functions it can computes ([recursive function](definition/recursive%20function.md)s). 


#### Details 

**What is the formal definition of a Turing machine ?** 
The alphabet of the tape $\Gamma$ can be thought to be 0's and 1's and blank's. 

$$\begin{array}{l}\text { A Turing machine is a 7-tuple, }\left(Q, \Sigma, \Gamma, \delta, q_{0}, q_{\text {accept }}, q_{\text {reject }}\right) \text {, where } \\ Q, \Sigma, \Gamma \text { are all finite sets and } \\ \text { 1. } Q \text { is the set of states, } \\ \text { 2. } \Sigma \text { is the input alphabet not containing the blank symbol } \sqcup \text {, } \\ \text { 3. } \Gamma \text { is the tape alphabet, where } \sqcup \in \Gamma \text { and } \Sigma \subseteq \Gamma \text {, } \\ \text { 4. } \delta: Q \times \Gamma \longrightarrow Q \times \Gamma \times\{\mathrm{L}, \mathrm{R}\} \text { is the transition function, } \\ \text { 5. } q_{0} \in Q \text { is the start state, } \\ \text { 6. } q_{\text {accept }} \in Q \text { is the accept state, and } \\ \text { 7. } q_{\text {reject }} \in Q \text { is the reject state, where } q_{\text {reject }} \neq q_{\text {accept }}\end{array}$$

**How to write the program (or diagram or table of instructions) in the machine ?**

We write $S_0=blank$ , $S_1=0$ and $S_2=1$, $R=move \ right$, $L= move \ left$ . 
An instruction can be written $q_i S_i S_j R q_m$  or  $q_i S_i S_j L q_m$. We encode all instructions that define the Turing machine, as follows $$q_1 S_0 S_0 L q_2 ; q_2 S_1 S_2 L q_3 ; ... $$We write $q_i=DAAAA...A$ ($i$  times), $S_i=DCCC...C$ ($i$  times) and give a integer to each letter (A=1, C=2, D=3,...,;=7). Therefore, it gives a description number for the Turing machine $$313325117 ...$$There is a unique integer for a given machine, but we can always add unecessary programs (that change the number but that give the same result). This integer gets a binary decomposition$$01000101011010$$With the help of an additional small and instantaneous "workspace", it uses a [simple mecanism](https://www.youtube.com/watch?v=P66h8D5Lkwk) to read the programs and compute at the same time.


#### Sources 
[Stanford Encyclopedia of Philosophy](https://plato.stanford.edu/entries/turing-machine/#TuriDefi)   
[MIT Open courses](https://ocw.mit.edu/courses/18-404j-theory-of-computation-fall-2020/pages/syllabus/)     
[Sipser2013](reference/Sipser2013.md)
note [literature note of Longo2012](note/literature%20note%20of%20Longo2012.md)     
[Youtube](https://www.youtube.com/watch?v=P66h8D5Lkwk)         
[Wikipedia](https://en.wikipedia.org/wiki/Turing_machine)       
[Turing1936](reference/Turing1936.md)
