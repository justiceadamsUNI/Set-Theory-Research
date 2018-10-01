# Week Of 9/24 Research Update
I finally got my textbook this week, so I was finally able to actually start my research. I spent most of this weeks time reading the first chapter of the textbook, taking notes, and comparing them with how the current set theory class is going. Below, I'll try to document my notes, the current structure of the class, questions I need to be answered, and what I'm going to work on for next week.

## Chapter 1 of Modern Set Theory
I decided to read the first chapter of the book so that I have a good understanding of what's happening in the class, and so I can compare and contrast the dynamic of the book to the current curriculum. There were numerous theorems and definitions included in the first chapter which I'll outline below. We may use all of them, we may use some of them in our final packet. There are some things to note, first, I omitted special cases that I felt would have already been covered by a prerequisite (for example, mathematical induction). I also stopped recording notes at what I considered the deviation point of the class. ie. there is a point where Dr. Stanley deviated from the book, so I'll only record the book's definitions up until that point of chapter one. You'll have to forgive my lack of LateX on this page. Unfortunately, this is entirely markdown syntax, but for next week I *should* have a LateX document started for recording these definitions.

**Partial Order**
```
r is a partial order on the set X if and only if for all x, y, z in X the following axioms hols
  - Reflexive Axiom: x r x
  - Antisymmetric Axiom: if x r x and y r x, then x r y
  - Transitive axiom: if x r y and y r z, then z r z
```
Thoughts: It would be good to define relation first (and maybe equivalence relation) so that students can recall just what a relation is, in case they have forgotten. It's somewhat essential to the definition of a partial order. Also, It's worth pointing out that there can be many different partial orders on a set. I think this is worth stating explicitly, or through examples.

**Comparable and Incomparable**
```
Let P_o be a partial order on a set X. Two elements x and y of X are comparable if and only if x P_o y or y P_o x; otherwise they are incomparable. They are compatible if and only if there is some z so z P_o x and z P_o y; otherwise they are incompatible.
```
Thoughts: It may be worth defining Lexicographical ordering / linear ordering first here, being that they build from the definition of partial order.

**Chain and Antichain**
```
A subset B of a partially ordered set is a chain if and only if two elements of B are comparable. B is an antichain if and only if no two elements of B are compatible. B is linked if and only if it is pairwise compatible.
```

**Linear Order**
```
A partial order r on a set X is linear if and only if X is a chain. If r is a linear order on X, we often say X is linearly ordered, or linear, and suppress r
```

**Minimal/Minimum and Maximal/Maximum
```
Let X be a partially ordered set. Let x in X. We define
- x is minimal if and only if, for all y in X, if y <= x, then y = x
- x is maximal if and only if, for all y In X, if y >= x, then y = x
- x is a minimum if and oly if, for all y in X, y >= x
- x is a maximum if and only if, for all y in X, y <= x.
```
Thoughts: This may need to be broken into several definitions? Not sure if one question is enough to capture what's all being laid out here. A question that highlights the differences seems necessary.

**Unbounded**
```
Given X partially ordered by <= and S subset X, we say that S is unbounded if and only if there is no x in X with x >= s for all s in S.
```

**Dominating**
```
Given X partially ordered by <= and S subset X, we say that S is dominating if and only if for all x in X there is s in S with x <= s
```

**Equivalence Relations**
```
An equivalence relation is almost like a partial order, with one key exception: instead of antisymmetry, we have symmetry. The axioms for an equivalence relation = on a set X are: For all x,y,z in Z,
  - Relflexive axiom: x=x
  - Symmetric axiom: x = y if and only if y = x
  - Transitive axiom: If x = y and y = z, then x = z
```

**Equivalence classes**
```
NA: Not going to try and write this without LateX and not sure if we need it yet?
```

**Partition**
```
A partition P of a set X is a collection of subsets of X so that every element of X belongs to exactly one element of P
```
Thoughts: This definitely needs an example or a question to accompany it. For those who have never thought this way, it can be tough. I remember trying to understand the notion of open sets in Topology. It was hard.

**Linear Order**
```
A well-ordered set X is a linearly ordered set for which every nonempty subset has a minimum 
```

**Proposition: Every subset of a well-ordered set is well-ordered**
```
NA. Not including proof
```
Thoughts: If we decide to include this, it would make a really good question. It's relatively easy to prove but requires some thought about just what the question is even asking. Could prove useful to help students grasp the concept.

This is all the information from the first chapter of the book before the class deviates to chapter 3: Axioms. I've reviewed Dr. Stanleys and Jake Weber's notes and here's the current outline of the class (for the first 1.5 weeks).


## Class content for roughly 1.5 weeks
- Set builder notation was defined with an example
- Defined relation
- Defined partial order
- Defined linear ordering
- Defined lexicographical ordering
- Defined {comparable, compatible, linear order, chain, anti-chain, minimal/minimum, maximal/maximum}
    ** Note: Not sure if this actually happened. Need to touch base with Dr. Stanley **
- Jump straight into Axioms (I still need to read chapter 3).


## Questions for Dr. Stanley
- How much of the book's definitions as listed above do we want to include before jumping into Axioms. There's a fine line between including too much and not enough.
- What is FIN(X). Is it important? It's referenced on page 6 theorem 13. If it's important to our study of set theory, we should include it. I didn't know what it was, and I've taken more math courses than the average student (I think?).
- Should we define power set at some point? It may fall under the "They should already know this camp".
- Should we define a family of functions? Maybe you did that, but I missed it if so. 
- Specific question about her notes which will not be documented publicly.

# For next week
So for next week, I'm going to develop a LateX document which I will continuously update throughout this project. It will hopefully serve as our final deliverable at the end of the year. Things will become much easier to reason about with proper mathematical documentation. After touching base with Dr. Stanley, I'm going to include the definitions we decide to include (before jumping to axioms) and then some example problems. After that, I'll have Dr. Stanley (and maybe some others) review the work before I add anything from axioms onto the page. I'll also actually read Chapter 3 before diving into the notes from both Stanley and Jake. Ideally, by the end of next week, the first 1.5 (ish) weeks of class is included in the packet. It's a small win, but that's why I'm spending all year on this project! If anything else comes up after e-mailing Dr. Stanley, I will adjust my plans accordingly and document it in the next post.
