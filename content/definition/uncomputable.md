---
title: "uncomputable"
date: 2022-12-06
draft: false
tags:
- definition
---

Due to [Cantor's diagonal argument](concept/Cantor's%20diagonal%20argument.md), we know that the set of [arithmetic function](definition/arithmetic%20function.md)s that have a range on positive integers is not an [enumerable set](definition/enumerable%20set.md). But the set of [Turing machine](concept/Turing%20machine.md)s is an [enumerable set](definition/enumerable%20set.md) because they can be expressed as quadruplets. There are functions are not computable by a [Turing machine](concept/Turing%20machine.md). Assuming [Church-Turing thesis](concept/Church-Turing%20thesis.md), they are functions that are not [effectively computable](definition/effectively%20computable.md). For instance, solving the [halting problem](concept/halting%20problem.md) requires the introduction of the halting function (that takes as argument a Turing machine and a binary string) that is not Turing-computable. 

