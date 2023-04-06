
---
title: "Intuitive departure from physics and introduction of the principle of variations"
date: 2023-04-04
draft: false
showthedate: true
enabletoc: true
draft: true
tags:
- literature-note
---

### On theoretical gaps and changes of perspectives

" a way to understand"

When we face a problem that we struggle to solve, it is common to say that we need to change perspective. 
Roughly, this means starting from a "kludged" new set of acceptable axioms from which we can solve our problem more easily.
When the problem is solved, you usually see the logical path that we could have taken from our first perspective. 
Our problem was that we did not find the pathway in the first case, but it existed.
In fact, there is a lot of chance that your "kludged" new set of acceptable axioms and your initial ones are actually reducible to a common set of axioms. 

However, for more conceptually involved questions, such as scientific ones, you may not find such a pathway when you have solved you problem from a new perspective.
In fact, in mathematics, there are always undecidable statement for a given coherent set of axioms. This means that you need to posit new axioms to find new things. 
Therefore, mathematicians agree on accepting new axioms judging on what they are capable of producing.

This also same happens in physics. You cannot deduce quantum mechanics from the principles and laws of Galileo and Newton. 
It is only a posteriori that you can look at both framework and discuss the nature of their frontiere: are they reducible are not? 
In some cases, theories are not reducible to one another, they do not share the same principles.
Therefore, the frontier shows what I will call a *theoretical gap*.
There are some things that are in-between theoretical frameworks and that you cannot explain at all or solely in two incompatible ways. 
For instance, surfaces between materials are clear-cut in one framework and atomically rough in another. 

Now, this does not mean that we have an incoherent representation of reality, rather incomplete actually.
Reality exists without us, but it will always appear to us, and therefore to our understanding. 
If we agree on having some thin theoretical gaps between our theories, it means that we cannot always continuously advance by gathering data for instance. 
For science to progress, we need to have scientists ready to jump into the unknown to go on the over side and explore. 

Why am saying that ? Because I will now come close to the frontier of the physical continent to contemplate the gap.
This is for not putting axioms that are too far-reached to be conceivved at first. 
This is to avoid **incommensurability**.


### From purely physical perspectives



#### Old

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

A seemingly more challenging question would be to ask if the biological system is ergodic on the time scale of biological evolution $\tau_{\mathrm{bio}}\sim 10^9$ years. This requires going beyong our single organism picture to include reproduction, but this is not difficult. We consider that before dying, an organism give rise to a new life form somewhere in the biological space. Where? Well, dogs don't make cats. Based on our observations regarding heredity, we can posit, that the offspring's trajectory, at least during a some portion of its trajectory, will get close to the one of its parent. 
If we consider that all organisms are independent so we can represent all trajectories on the same picture (Fig.). 

Have all possibilities of living organisms been explored since the first living beings appeared on Earth? Darwin first understood that the myriad of life forms we can observe nowadays were not created at once, but had a common origin. Their unbounded diversification on the time scale of $\tau_{\mathrm{bio}}$  comes from the phenomenon of "descent with modification". In other words, the idea of an *open-ended evolution* —that all observations support for the past and that we have all reasons to believe that it is still occuring— is equivalent to saying that our biological system is not ergodic on the time scale of $\tau_{\mathrm{bio}}$ .


Genericity, specificity, historicity, unpredictability.


How does all organisms span on this region?
Is the natural history of evolution on the unnivser also non-ergodic ?K



Need to explain closure.
Now, according to Boltzmann reasonning, the larger the volume of the most probable macrostate, the faster you get to it. 
An estimation for the bacteria *E.coli*:   $2^{4.6\times 10^{10}}$[Morowitz1955a](reference/Morowitz1955a.md)
So how fast can we expect an organism to go to it? We will come back to this. 


[^1]: Of course, we face major difficulties in practice to define such a macrostate because we do not *understand* the living attribute of an organism based on its atomic positons and velocities. However, it can define in principle, at least as the states in the phase space that points to configurations of atoms that a human would recognize as alive. 








This 
However, in principle, we can do such a partition by defining an appropriate coarse-graining as usual.
We have seen that all living being will be dead at some point because of entropy. 


Of course, the entropy of the organism may not increase if the one of its environement does. However, in our global phase space that follows an unpredictable trajectory for epistemic reasons—we are not Laplacian deamons— 
Why are you still alive? Is the second law not valid for organisms? ([Schrodinger1944](reference/Schrodinger1944.md)). Is this due to the special initial condition at the beginning of the universe that is unpacked by this chaotic dynamics? 
Is the futur worth living if it is already determined? Does consciouness, which must not relate to atoms, capable of agency to change this future? 

A lot of philosophical questions are actually linked to this apparent paradox. But the latter is not one to us because we are limited beings. We will let those questions to the Laplacian demiurge because we cannot measure all position and velocities. Trying is not an option because we would not be able to measure them precisely enough to make predictions for this chaotic system. Although there is a reality without us, it will always be the question of how we understand it. In science, we need a fallibilist rationale and experimental observations. It seems like we need to adopt a new perspective. 

However, before changing viewpoint, we need to know in which direction to go, at least on an informal basis. From this paradox, we understand that organims resist remarkably well to entropy. In other words, they manage to maintain themselves in a highly peculiar macrostate of the phase space. In turn, this means that from a mechanistic point of view atoms are positionned in singular positions, which means that we can observe some order or regularities. However, the central idea is not to be ordered but to remain so. Therefore, the current state of the particles of an organism makes them fulfill some goal, the one of self-maintaining the organism. In this sense, an organism is organized (it has an intrinsic telos). The first question we will be interested in is therefore: how to explain such an organization from a mechanistic point of view? We will soon answer this question in a lot of details. 

Intuitively, for the organism to remain in the viable macrostate despite the continuous variation of the state of its particles, there should some restoring force due to the initial variation, like a negative feedback loop in cybernetics. In fact, we will indeed see that there is a circularity at play. When structure are relatively stable, we can build physico-mathematical structures because we have drastically limited the area of the phase. In those space, once the phase space has been redesigned with pertinent observables, we can make model that can be controlled more easily, like in biophysics for parts of organisms.

However, organisms do evolve and develop such that they cannot be describe with the same circular organization in time. To be more precise, the viable macrostate can be divided in different parts, for all stage of development and ageing of a life time for instance. Indeed the size of your bones is not the same at 1 or  30 years so that you need to change the mechanistics models and therefore the organizational model when time flows. However, because the dimensionality of the underlying physico-mathematical phase space is tremedous, the dynamic is highly non-ergodic, and the system has no chance to go two times to the same microstate or to *go back to a macrostate it has left.* The dynamic is for us upnredictable so that each organism is a unique history of unpredictable variations. 



Now we can adopt of better view point. 
Out-of-equilibrium thermodynamics and look on the organism. 