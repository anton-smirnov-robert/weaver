---
title: "computability"
date: 2022-12-07
draft: false
showthedate: true
enabletoc: false
tags:
- concept
---

Three notions of computability are equivalent: 
- The existence of a [Turing machine](concept/Turing%20machine.md) for computing the function.
- The [abacus](definition/abacus.md)-computability.
- A [recursive function](definition/recursive%20function.md).

*A function is computable on a [Turing machine](concept/Turing%20machine.md) if and only if it is a [recursive function](definition/recursive%20function.md).*

Some functions are not computable. 
Indeed, with [Cantor's diagonal argument](concept/Cantor's%20diagonal%20argument.md), we know that the set of [arithmetic function](definition/arithmetic%20function.md)s that have a range on positive integers is not an [enumerable set](definition/enumerable%20set.md). But the set of [Turing machine](concept/Turing%20machine.md)s is an [enumerable set](definition/enumerable%20set.md) (because they can be expressed as quadruplets). Therefore, there are functions that are not computable. 
For instance, solving the [halting problem](concept/halting%20problem.md) requires the introduction of the halting function that is not computable. 

#### Sources 

[Boolos2007](reference/Boolos2007.md)
