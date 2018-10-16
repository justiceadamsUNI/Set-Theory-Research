# Week Of 10/1 and 10/8 update Research Update
I decided to combine the last two weeks into one update. In part, because I had a relatively light week of research on the week of 10/1 but a rather heavy week of research on the week of 10/8. To me, it didn't make much sense to split this up into two separate posts. Here I'll try to outline what I've been up to as well as what's coming in the next week(s).

# Initial documentation
Finally, I went ahead and created a LateX document which contains the first portion of the class laid out with definitions/theorems/problems etc. This should cover roughly 1-1.5 weeks worth of content and I've devised a PDF file which is housed in this repository at the following [link](https://github.com/justiceadamsUNI/Set-Theory-Research/blob/master/pdf/Set_Theory_Doc_10-15.pdf)

<p align="center">
  <img src ="https://i.imgur.com/P80mLoz.png?1" />
</p>

Almost all of this content came from my recap of chapter 1 from the textbook and working with Dr. Stanley to sift through what was important/should be included. This managed to consume most of my time over the last couple weeks as I continued to fine-tune the document and make the LateX look nice.

Some notes that I need to be answered/considered by Dr. Stanley regarding the first section of the document:

## Things to note: ##
- I marked Instructor notes with "Potential instructor note" below any definitions/theorems I felt needed some clarification. In the end we are hoping two have two forms of the document. One for instructors and one for students.
- I still don't know whether to number the problems with the same scheme as the definitions, meaning we don't have problem 1, problem 2, definition 1. It would become problem 1, problem 2, definition 3. Thus, 1-2->3. It always bugged me how the other packets did it, but my life is considerably easier doing it the ugly way in latex.

## Questions regarding content: ##
- Should we define lexicographical ordering? I'm not sure if this is common knowledge. Maybe before problem 3?
- Are extending functions necessary to the course? Are they imperative?
- Is my definition of linear order correct?
- Below are the things I skipped from the first chapter, we may include these topics at a later date (later portion of the packet)
      - chain and antichain
      - comparable and incomparable
      - compatible and incompatible
      - maximal/maximum
      - minimal/minimum
      - Well ordering
      - Unbounded
      - Dominating
      - Equivalence classes
      - Partitions
      
After creating this initial document and documenting what I need to circle back to, I moved on to reading chapter 3. I made it about halfway through chapter 3 and documented what I consider to be the important aspects of the chapter thus far. Chapter 3 is about axioms.
```
Definitions of a subset, proper subset, union, intersection, set complement, and the empty set
```
Thoughts: This would probably have been covered by a pre-requisite course (DAM) so I'm making the conscious decision to omit them from the packet (for now...) Forgive my lack of LateX in GH markdown.

```
Axiom 1: Extensionality - two sets are equal if and only if they have the same elements: For all x, for all y, x == y iff for all z (z in x iff z in y)
```

```
Related theorem to axiom 1: For all x, for all y x == y iff x subset y and y subset x
```

```
The book explains demorgan's laws and the associativity and commutativity of set union and intersection
```
Thoughts: Once again I feel this is presumed knowledge.

```
Axiom 2: Pairing axiom - For all x, for all y, there exists z such that x == {x,y}
```

```
Definition of an ordered pair in terms of sets - (x,y) = {{x}, {x,y}}
```

```
Definition - (x,y) = (z,w) iff x==z and y==w
```

```
Definition of n-tuple: (x,.....,X_n+1) = {(x1,...,Xn), X_n+1}
```
Thoughts: This definition of an ordered pair is new to me, and very interesting. I would like to have a question where you simply write out an ordered pair in set notation. I did this myself and found it to be very helpful. For example, write out some random 4-tuple in set notation. This could be a class exercise as it doesn't take super long...

```
A relation is a set of ordered pairs. They go on to define range, field, domain
```
Thoughts: It might be the case that the definition of the field is the only thing worth focusing on. I tend to think of the definition from modern algebra so this is somewhat new to me. Range and domain are two old friends obviously.

```
Definition of equivalence relation in terms of sets and ordered pairs
```

```
Axiom 3: Union axiom - For all x, there exists Y such that y = Union of all x's
```

```
Axiom 4: Separation Axiom - Let theta be a formula with free variables x0,...,xn. Then for all x, for all x0... for all x_n-1 there exists y such that y = {z in x: theta(x0,...x_n-1, z)}
```


## For next week
Now that I have a lateX document I want to keep adding to it and refining it. What this means: For next week I'm going to finish reading chapter 3, aggregate my notes, cross compare with Dr. Stanley's class notes, and add the axioms to the sheet along with useful problems as I did for the first section.

My main goal: Be all the way through with the first 2-3 weeks worth of content (my current stockpile of Jake's and Dr. Stanley's notes). At this point, I'll reach out to both of them and stock up on some more notes.

I also need to circle back to "section 1" and fix anything provided that Dr. Stanley has comments (currently waiting on her feedback). So again, this next week should be filled with dissecting the course curriculum and moving useful theorems/problems to the course sheet. I suspect this will be the average workflow moving forward. In the end, we will have a nice presentable document we can work with!

Sources for this week
- The great Dr. Stanley
- [Judith Roitman's third edition of Introduction to Modern Set Theory](https://www.amazon.com/Introduction-Modern-Theory-Judith-Roitman/dp/0989897516)
