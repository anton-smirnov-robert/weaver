
---
title: "principle of variation from physics"
date: 2023-04-06
draft: false
showthedate: true
enabletoc: true
draft: true
tags:
- literature-note
---

For classical mechanics or thermodynamics, a generic organism and its environment constitute a large enough closed system. 
Here we consider only one organism, but the discussion is the same for multiple independent ones.
We consider the phase space as the position and momenta of all atoms in this enormous global system. 
An equation governs the trajectory of the system's state, starting from a state corresponding to living organism and an appropriate environnement state. 
The trajectory is deterministic but unpredictable to us for epistemic reasons—we are not Laplacian deamons— or for practical reasons, if it is chaotic. 
Propagating the trajectory of the time scale of some minutes, hours, or even years would most probably not kill our generic organism. 
This is actually what we can observe for most organisms on a daily basis.

However, in the phase space, the volume of microstate configurations in which the organism under scrutiny lives is extremly small with respect to the one where it is dead. 
Indeed, there are a lot more atomic configurations that makes your dead, for instance when your atoms are scattered. The most probable macrostate being "death", an organism would eventually die, according to the second law of thermodynamics. This is indeed what we observe. 

We have established the system takes a *lifetime* to access for the first time the largest macrostate of the system that we can label "death". Everyday observations tells us that we usually don't come back from this first incursion in the "death" macrostate. Similarly, particles in a box initially placed in one corner spread rapidly in the entire box, but do not go back in the corner even if they can, in principle. This is a matter of probabilities given a *physically relevant time of observation* $\tau_{\mathrm{phys}}$, which is central to our understanding of most systems in physics. $\tau_{\mathrm{phys}}$ corresponds to the time the system takes so that the duration of its visit of the different macrostates of the phase space is roughly proportional to their volume. For particles in a box, the volume of the macrostate corresponding to all of them being in one corner is so small that we even don't need the system to go there to describe the system very well. In general, we cannot know $\tau_{\mathrm{phys}}$ in advance, so that when we investigate a physical systems of particles, we have to make this as an hypothesis: the *ergodic hypothesis*. Another way yo put it is to say that if you scrutinize the system for a time larger than  $\tau_{\mathrm{phys}}$ , the measure of your observable —that are time-averaged quantities— won't change. 

Coming back to our biological system, we have seen that if we wait long enough to be able to argue that our system might be ergodic on the basis that it has visited the two macrostates of our coarse-graining, the organism is dead. Together with the fact that the "death" macrostate is at least extremely larger than the "alive" one, we can conclude that for a *organismal relevant time of observation*  $\tau_{\mathrm{org}}$ —a lifetime—, the physical system under scrutiny is highly non-ergodic: $\tau_{\mathrm{org}} \ll  \tau_{\mathrm{phys}}.$ Accordingly, what is biologically interesting in physics happens *out-of-equilibrium*, that is outside the "equilibrium" or "death" macrostate. 


We now zoom in the "alive" macrostate and call it the biological system, in contrast to the physical one that contains it.  
We can ascribe a physico-mathematical structure to it, notably by predefining all possibilities for the states of the system (phase space) where the organisms lives[^1]. 
We now have two ways to *perceive* the system. 
On the one hand, we have the global physical system described by an immense phase space, and where we know that a living organism will eventually enter the preponderant macrostate labelled "death". 
On the other hand, we have the local biological system caracterized by a more practical and smaller phase space. However, defining this physico-mathematical structure requires predefining possibilities in which the dead state cannot be accomodated, by construction. 
Chosing one of both physico-mathematical comes at a price. 
The biological one seems inevitable to reduce the immense and useless (from a biological perspective) "death" macrostate of physical system. 
However, the latter cannot accomodate the last but important stage of life, because we exclude this possibility by construction of the biological space. 
In sum, *if we give up on trying to understand the deterministic but unpredictable trajectory of an organism in the huge and highly non-ergodic physical system, we need to adopt the physico-mathematical structure of the biological system while knowing that it will no longer be valid on the time scale of a lifetime $\tau_{\mathrm{org}}$.*
It looks like if choose this perspective, our describtion becomes fragile, because we cannot rely on an invariant mathematical apparatus to describe the evolution of an organism. Then, how to know when it breaks down? For how long is it valid? 
It seems that we encounter a new strong sense of randomness because what is not predefined can happen from this perspective. 
However, we do not face the stronger sort of unpredictability here because, even if we cannot say how or when (that is by following which trajectory), we know *for sure* that death will happen.

We now evaluate the ergodicity of the biological system for the trajectory of our generic organism during it lifetime $\tau_{\mathrm{org}}$.
Let's make a coarse-graining of this system by labelling regions corresponding to species.
We will agree on the fact that an organism does not go through all living macrostates during its lifetime $\tau_{\mathrm{org}}$. 
For instance, an elephant does not become a cornflower, then a rat, then a diplodocus, and finally an *E.coli* bacteria before dying.
In other words, on the time scale of $\tau_{\mathrm{org}}$, the biological system is also highly non-ergodic.

A seemingly more challenging question would be to ask if the biological system is ergodic on the time scale of biological evolution $\tau_{\mathrm{bio}}\sim 10^9$ years. This requires going beyong our single organism picture to include reproduction. We consider that before dying, an organism give rise to a new life form somewhere in the biological space. Where? Well, dogs don't make cats. Based on our observations regarding heredity, we can posit that the offspring's trajectory is close —let's say within the same specie macrostate— to the one of its parent. If we consider that all organisms are independent, we can say that the system is ergodic if the trajectories of all organisms cover all possible species.  

Have all possibilities of living organisms been explored since the first living beings appeared on Earth? Darwin first understood that the myriad of life forms we can observe nowadays were not created at once, but had a common origin. Their unbounded diversification on the time scale of $\tau_{\mathrm{bio}}$  comes from the phenomenon of "descent with modification". In other words, the idea of an *open-ended evolution* —that all observations support for the past and that we have all reasons to believe that it is still occuring— is equivalent to saying that our biological system is not ergodic on the time scale of $\tau_{\mathrm{bio}}$. 

Because life forms are continuously exploring new part of the immense biological phase space at the time scale of $\tau_{\mathrm{bio}}$, some organisms must do the same at the time scale $\tau_{\mathrm{org}}$. This has a crucial consequence regarding the physico-mathematical description of organisms. Let's detail this central point. 

Following to the above-mentionned strategy for describing an organism, we may want to zoom in the biological system and create physico-mathematical apparatuses dedicated to describe all *taxa*, keeping in mind that they would be valid on a time scale of $\tau_{\mathrm{org}}$. We call those smaller systems the *taxon system*. In fact, a macrostate defining a taxon can be again splitted into several stages of development. We would then build a *predefined succession* of $N$ physico-mathematical structures, respectively valid on a time scale $\tau_i$ for $1\leq i\leq N$ and $\sum_i\tau_i\simeq \tau_{\mathrm{org}}$, to describe the lifetime of an organism that belong to this taxon. However, this would not be compatible with the emergence of new life forms during evolution because organisms would not explore zones that are not part of the set of *taxon system*s, however rich the description may be.  

In sum, the observation of the open-ended evolution at the time scale $\tau_{\mathrm{bio}}$  requires that organisms cannot be described by predefined physico-mathematical structures at the time scale $\tau_{\mathrm{org}}$. *Mutadis mutandis*, developmental stages of organisms cannot be described by a succession of predefined physico-mathematical structures. If we want to get a better understanding of an organism and reduce the dimensionality of the phase space in which we describe its state, we are compelled to acknowledge that the validity of the physico-mathematical structure we use is limited in time *and* that we cannot predict the one that we shall adopt next. Here, we face a strongest form of randomness: we do not know when our description is no longer valid and we cannot prestate what comes next, by principle. Of course, there is an apparent directionality, and most organisms follow similar stages of development. But predefining a sequence of stages to describe an organism contradicts the observation of a an open-ended evolution. Directionality must be explained, and not posited. More generally, we will describe parts of an organism by mathematical structures that are valid on a given timescale $\tau$. This decomposition allows us to change parts of the organism one by one instead of the entire description. 

Let's conclude, the physico-mathematical structure to describe an organism is not stable with respect to the flow of time, and change in an unpredictable way. An organism results from a history of unpredictable changes of physico-mathematical structures. Because, of this strong randomness, organisms all differ *qualitatively* by principle. ==Organisms are specific objects.==


- Genealogy is a precious reference point! (identity of organisms)


- Need to explain closure.([Schrodinger1944](reference/Schrodinger1944.md)).
Now, according to Boltzmann reasonning, the larger the volume of the most probable macrostate, the faster you get to it. 
An estimation for the bacteria *E.coli*:   $2^{4.6\times 10^{10}}$[Morowitz1955a](reference/Morowitz1955a.md)
So how fast can we expect an organism to go to it? We will come back to this. 






[^1]: Of course, we face major difficulties in practice to define such a macrostate because we do not *understand* the living attribute of an organism based on its atomic positons and velocities. However, it can define in principle, at least as the states in the phase space that points to configurations of atoms that a human would recognize as alive. 

