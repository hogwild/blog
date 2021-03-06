---
layout: post
title: Discrete math homework 3
mathjax: true
---
## Chapter 1.7
2.We must show that whenever we have two even integers, their sum is even. Suppose that a and b are
two even integers. Then there exist integers s and t such that $a = 2s$ and $b = 2t$ . Adding, we obtain
$a + b = 2s + 2t = 2(s + t)$. Since this represents $a + b$ as 2 times the integer $s + t$ , we conclude that $a + b$ is even, as desired.

4.We must show that whenever we have an even integer, its negative is even. Suppose that a is an even integer.
Then there exists an integer s such that $a = 2s$. Its additive inverse is $−2s$, which by rules of arithmetic and
algebra (see Appendix 1) equals $2(−s)$. Since this is 2 times the integer $−s$, it is even, as desired.

6.An odd number is one of the form $2n + 1$, where n is an integer. We are given two odd numbers, say $2a + 1$ and $2b + 1$. Their product is $(2a + 1)(2b + 1) = 4ab + 2a + 2b + 1 = 2(2ab + a + b) + 1$. This last expression shows that the product is odd, since it is of the form $2n + 1$, with $n = 2ab + a + b$.

## Chapter 1.8
2.The cubes that might go into the sum are 1, 8, 27, 64, 125, 216, 343, 512, and 729. We must show that
no two of these sum to a number on this list. If we try the 45 combinations $(1+1, 1+8, \cdots, 1+729, 8+8,
8 + 27, \cdots 8 + 729, \cdots, 729 + 729)$, we see that none of them works. Having exhausted the possibilities, we
conclude that no cube less than 1000 is the sum of two cubes.

6.Because $x$ and $y$ are of opposite parities, we can assume, without loss of generality, that $x$ is even and
$y$ is odd. This tells us that $x = 2m$ for some integer $m$ and $y = 2n + 1$ for some integer $n$. Then
$5x+5y = 5(2m)+5(2n+1) = 10m+10n+1 = 10(m+n)+1 = 2\cdot 5(m+n)+1$, which satisfies the definition
of being an odd number.

8.The number 1 has this property, since the only positive integer not exceeding 1 is 1 itself, and therefore the sum is 1. This is a constructive proof.

10.The only perfect squares that differ by 1 are 0 and 1. Therefore these two consecutive integers cannot both be perfect squares. This is a nonconstructive proof -- we do not know which of them meets the requirement.
(In fact, a computer algebra system will tell us that neither of them is a perfect square.)

12.Of these three numbers, at least two must have the same sign (both positive or both negative), since there are only two signs. (It is conceivable that some of them are zero, but we view zero as positive for the purposes of
this problem.) The product of two with the same sign is nonnegative. This was a nonconstructive proof, since we have not identified which product is nonnegative. (In fact, a computer algebra system will tell us that all
three are positive, so all three products are positive.)

15.a) This statement asserts the existence of $x$ with a certain property. If we let $y = x$, then we see that $P(x)$ is true. If $y$ is anything other than $x$, then $P(x)$ is not true. Thus, $x$ is the unique element that makes $P$ true.

b) The first clause here says that there is an element that makes $P$ true. The second clause says that whenever two elements both make $P$ true, they are in fact the same element. Together these say that $P$ is satisfied by exactly one element.

c) This statement asserts the existence of an $x$ that makes $P$ true and has the further property that whenever we find an element that makes $P$ true, that element is $x$. In other words, $x$ is the unique element that makes $P$ true.

Alternatively: This statement asserts that there exists an element $x$ that makes $P(x)\wedge \forall y(P(y)\rightarrow x=y)$ true which means there is an $x$ for whom $P(x)$ is true and for every $y$ if $P(y)$ is true, then $y = x$ holds. Therefore, $x$ is unique.

16.Show that if $a$, $b$, and $c$ are real numbers and $a\neq 0$, then there is a unique solution of the equation $ax+b = c$.

solution: We know from algebra that the following equations are equivalent: $ax + b = c$, $ax = c − b. x = (c − b)/a$.
This shows, constructively, what the unique solution of the given equation is.

Alternative solution.  
First, we proof the existence of the solution. Let $x_1=\frac{b-c}{a}$, it is easy to verify $x_1$ is a solution of the equation. Second, we proof the uniqueness of $x_1$. Assume that there exists $x_2$ that also a solution of the equation. So, we have $ax_1 + b = c$ and $ax_2 + b = c$ and $ax_1 + b = ax_2 + b$. Then, $x_1 = x_2$ since $a\neq 0$ which is conflict with $x_1 \neq x_2$. Therefore, $x_1$ is unique.



## Chapter 2.1
10.a) true b) true c) false — see part (a) d) true e) true — the one element in the set on the left is an element of the set on the right, and the sets are not equal f) true — similar to part (e) g) false — the two sets are equal

11.a) True b) True c) False d) True e) True f) False

14.We put the subsets inside the supersets. Thus the answer is as shown.
![ls](ls.png)

20.The cardinality of a set is the number of elements it has.
a) The empty set has no elements, so its cardinality is 0.
b) This set has one element (the empty set), so its cardinality is 1.
c) This set has two elements, so its cardinality is 2.
d) This set has three elements, so its cardinality is 3.

30.We can conclude that $A = \emptyset$ or $B = \emptyset$. To prove this, suppose that neither $A$ nor $B$ were empty. Then
there would be elements $a \in A$ and $b \in B$. This would give at last one element, namely $(a, b)$, in $A \times B$, so $A \times B$ would not be the empty set. This contradiction shows that either $A$ or $B$ (or both, it goes without saying) is empty.

32 In each case the answer is a set of 3-tuples.
a) $\{(a, x, 0), (a, x, 1), (a, y, 0), (a, y, 1), (b, x, 0), (b, x, 1), (b, y, 0), (b, y, 1), (c, x, 0), (c, x, 1), (c, y, 0), (c, y, 1)\}$
b) $\{(0, x, a), (0, x, b), (0, x, c), (0, y, a), (0, y, b), (0, y, c), (1, x, a), (1, x, b), (1, x, c), (1, y, a), (1, y, b), (1, y, c)\}$
c) $\{(0, a, x), (0, a, y), (0, b, x), (0, b, y), (0, c, x), (0, c, y), (1, a, x), (1, a, y), (1, b, x), (1, b, y), (1, c, x), (1, c, y)\}$
d) $\{(x, x, x), (x, x, y), (x, y, x), (x, y, y), (y, x, x), (y, x, y), (y, y, x), (y, y, y)\}$

35.$mn$

38.Suppose $A\neq B$ and neither $A$ nor $B$ is empty. We must prove that $A\times B \neq B\times A$. Since $A \neq B$, either
we can find an element $x$ that is in $A$ but not $B$, or vice versa. The two cases are similar, so without loss of
generality, let us assume that $x$ is in $A$ but not $B$. Also, since $B$ is not empty, there is some element $y \in B$.
Then $(x, y)$ is in $A\times B$ by definition, but it is not in $B \times A$ since $x \notin B$. Therefore $A \times B \neq B \times A$.

46.a) If $S \in S$ , then by the defining condition for S we conclude that $S \notin S$ , a contradiction.

b) If $S\notin S$ , then by the defining condition for S we conclude that it is not the case that $S \notin S$ (otherwise $S$ would be an element of $S$), again a contradiction.

## Chapter 2.2

11.a) $A\cup B =\{x|x \in A\vee x \in B\} = \{x| x\in B\vee x \in A\}= B\cup A$

b) $A\cap B =\{x|x\in A\wedge x\in B\}=\{x|x \in B \wedge x \in A\}= B\cap A$

18.a) Suppose that $x \in A\cup B$. Then either $x \in A$ or $x \in B$. In either case, certainly $x \in A \cup B \cup C$. This establishes the desired inclusion.

b) Suppose that $x \in A \cap B \cap C$. Then $x$ is in all three of these sets. In particular, it is in both $A$ and $B$ and therefore in $A\cap B$, as desired

c) Suppose that $x\in(A−B)−C$. Then $x$ is in $A−B$ but not in $C$. Since $x\in A−B$, we know that $x \in A$
(we also know that $x\notin B$, but that won’t be used here). Since we have established that $x \in A$ but $x\notin C$, we have proved that $x\in A − C$.

d) To show that the set given on the left-hand side is empty, it suffices to assume that $x$ is some element in that set and derive a contradiction, thereby showing that no such $x$ exists. So suppose that $x\in (A−C)\cap(C −B)$.
Then $x \in A − C$ and $x \in C − B$. The first of these statements implies by definition that $x \notin C$, while the second implies that $x \in C$. This is impossible, so our proof by contradiction is complete.

e) To establish the equality, we need to prove inclusion in both directions. To prove that $(B −A)\cup(C −A)\subseteq
(B\cup C)−A$, suppose that $x \in (B −A)\cup (C −A)$. Then either $x\in (B −A)$ or $x \in (C −A)$. Without loss of generality, assume the former (the proof in the latter case is exactly parallel.) Then $x \in B$ and $x \notin A$. From the first of these assertions, it follows that $x \in B\cup C$. Thus we can conclude that $x \in (B\cup C)−A$, as desired. For the converse, that is, to show that $(B \cup C) − A \subseteq (B − A) \cup (C − A)$, suppose that $x \in (B \cup C) − A$.
This means that $x \in (B \cup C)$ and $x \notin A$. The first of these assertions tells us that either $x \in B$ or $x \in C$. Thus either $x \in B − A$ or $x \in C − A$. In either case, $x \in (B − A) \cup (C − A)$. (An alternative proof could be given by using Venn diagrams, showing that both sides represent the same region.)

Alternative 1:

The left-hand side can be rewritten as $\{x|x\in (B-A)\vee x\in (C-A)\}=\{x|(x\in B\wedge x\notin A)\vee(x\in C\wedge x\notin A)\}$, then by the distributive laws and absorption laws of logical equivalence, we have $\{x|x\in B \vee x\in C\wedge x\notin A\} = (B\cup C) -A$.

Alternative 2:  
$(B\cup C) - A = (B\cup C)\cap \bar A = (B\cap \bar A)\cup (C\cap \bar A) = (B-A)\cup (C-A)$


30.Can you conclude that $A=B$ if $A$, $B$, and $C$ are sets such that  
(a) $A\cup C = B\cup C$ ?  
(b) $A\cap C = B\cap C$ ?  
(c) $A\cup C = B\cup C$ and $A\cap C = B\cap C$ ?

Solutions:  
a) We cannot conclude that $A = B$. For instance, if $A$ and $B$ are both subsets of $C$, then this equation will
always hold, and $A$ need not equal $B$.

b) We cannot conclude that $A = B$; let $C = \emptyset$, for example.

c) By putting the two conditions together, we can now conclude that $A = B$. It needs to prove that $A \subseteq B$ and $B\subseteq B$. Suppose that $x \in A$. There are two cases. If $x \in C$, then $x \in A \cap C = B \cap C$, which forces $x \in B$. On the other hand, if $x \notin C$, then because $x \in A \cup C = B \cup C$, we must have $x\in B$. Note that the both sides of the equation are in the same form, i.e., it is symmetric. So, we can get $B\subseteq A$ by switching $A$ and $B$ in the former proof. Therefore, $A=B$.

40.Using the membership table is also tractable here.

48.We note that these sets are increasing, that is, $A1\subseteq A2\subseteq A3 \subseteq \cdots$. Therefore, the union of any collection
of these sets is just the one with the largest subscript, and the intersection is just the one with the smallest subscript.

a) $A_n = \{\cdots ,−2,−1, 0, 1, \cdots , n\}$

b) $A_1 = \{\cdots,−2,−1, 0, 1\}$
