
---
title: "note on Rovelli2017"
date: 2023-01-18
draft: true
showthedate: true
enabletoc: true
tags:
- literature-note
---

#### **Is time’s arrow perspectival?**     
by Rovelli C. (2017)         

Reference: [Rovelli2017](reference/Rovelli2017.md)


Boltzmann's [entropy](definition/entropy.md) (but also Gibb's) resorts to coarse-graining of the phase space into several macrostates. 
Given a trajectory, there is a coarse graining that makes entropy decrease.
We usually do not access the system we are interested in. Rather, the system is coupled to another one, and this defines the coarse-graining. 

> [!quote] 
>
>The “choice” of macroscopic observables is dictated by the ways the system under consideration couples. The macroscopic observables of the system are those coupled to the exterior (in thermodynamics, those that can be manipulated and measured). The thermodynamics and the statistical mechanics of a system defined by a set of macroscopic observables $A_n$ describes (objectively) the way the system interacts when coupled to another system via these observables, and the way these observables behave. —  (Rovelli, 2017, p. 3) 

This specific coarse graining makes entropy increase to us. 

> [!quote] 
>
>The subsystem to which we belong interacts with the universe via a relatively small number of quantities, which define a coarse graining. Entropy happens to depends on coarse-graining. Therefore the entropy we ascribe to the universe depends on the peculiar coupling between us and the rest of the universe. Low past entropy may be due to the fact that this coupling (rather than microstate of the universe) is non-generic. —  (Rovelli, 2017, p. 1) 


#### Autre: 

mail M.M. 21/01 :

L'entropie se réfère à un couplage avec un autre sous-système qui définit un coarse-graining, c'est-à-dire un choix d'observables.
Pour le même trajectoire on peut trouver un choix d'observble de sorte que l'entropie diminue.
Le fait que l'univers vienne d'un état de basse entropie n'est-il qu'une question de perspective ?
Nos couplages (instruments de mesures) pour ces système nous amène à voir de l'accrroissement d'entropie.

En pratique, on partitionne toujours l'espace des phases en fonction de critères qui détermine au moins partiellement la trajectoire.   
Par exemple, on cartographie un espace des phases en fonction de l'énergie potentielle des micro-états.  
Les "vallées" sont des états relativement stables, les "cols" sont des états intermédiaires, instables.  
Or l'énergie potentielle du système détermine en grande partie la trajectoire.  
Comment peut-on avoir *d'abord* une trajectoire puis *ensuite* une partition, comme si ces deux choses étaient indépendantes ?  
  
Algorithme de Rovelli:   
1) Prenez une trajectoire qui termine dans la partie la plus grande d'un espace des phases partitioné.  
2) Prenez cette plus grand partie et coupez là en deux  
3) Réitérer sur les fragments jusqu'à qu'aucun d'entre eux ne soit la plus grande partie du système.  
4) Reconsidérer la trajectoire en observant que l'entropie du système a diminué dans cette nouvelle partition.  
