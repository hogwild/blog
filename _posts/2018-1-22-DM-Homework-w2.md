---
layout: post
title: Discrete math Homework week 2
mathjax: true
---

# Discrete_math: the Exercises

## Week 2:
#### Chapter 1.5
###### Exercises 2 (p64):
(a)  
For any real number $y$, there is a real number $x$ such that $xy = y$ holds.

(b)  
For any real number pair: $x$ and $y$, if $x\ge 0$ and $y< 0$, then $x-y>0$.

(c)  
$x$ and $y$ are any real numbers, there is a real number $z$ such that $x = y + z$ holds.

###### Exercises 6
(a)  
A student in your school, named, Randy Goldberg is enrolled in class CS252.

(b)  
There is a student who is enrolled in class Math695.

(c)
There is a class in your school that Carol Sitea is enrolled in.

(d)  
There is a student who is enrolled in Math 222 and CS 252.

(e)  
For all the classes, there are two different students, say, $x$ and $y$, for whom it holds that if $x$ is enrolled in that class, then $y$ is also enrolled in that class.

(f)  
For all the classes, there are two different students, for whom it holds that if one of them is enrolled in that class, then the other one is also enrolled in that class.

###### Exercises 11
求解思路：将基本单元写出来，然后再组合  
(a)  
$A(Lois, Michaels)$

(b)  
$\forall x(S(x)\rightarrow A(x, Gross))$

(c)  
$\forall x(F(x)\rightarrow A(x, Miller)\vee A(Miller, x))$

(d)  
$\neg\forall x\exists y(S(x)\rightarrow F(y)\wedge A(x, y))$

(e)  
$\neg\forall x\exists y(S(y)\wedge F(x)\wedge A(y, x))$

(f)  
$\exists x\forall y(F(y)\rightarrow S(x)\wedge A(x, y))$

(g)  
$\exists x\forall y(F(y)\rightarrow F(x)\wedge A(x, y))$

(h)  
$\neg\forall x\exists y(F(y)\rightarrow S(x)\wedge A(y, x))$

###### Exercises 12
(a)  
$\neg I(Jerry)$

(b)  
$\neg C(Rachel, Chelsea)$

(c)  
$\neg C(Jan, Sharon)$

(d)  
$\neg\exists x(C(x, Bob))$

(e)  
$\forall x((x\neq Joseph)\rightarrow C(Sanjay, x))$

(f)  
$\exists x(\neg I(x))$

(g)  
$\neg\forall xI(x)$

(h)  
Exactly one student in your class has an Internet connnection.  
$\forall x \forall y(I(x)\wedge (x \neq y)\rightarrow \neg I(y))$  
alternative: $\forall x\exists!y I(x)\wedge I(y)\wedge (x = y)$

(i)  
$\forall x\forall y(I(x)\rightarrow \neg I(y)\wedge (x \neq y)))$

(j)  
$\forall x\exists y(I(x)\rightarrow C(x, y))$

(k)  
$\neg\forall x\exists y(I(x)\wedge C(x, y))$

(l)  
$\exists x\exists y((x\neq y)\wedge C(x, y))$

(m)  
$\exists x\forall y(C(x,y))$

(n)  
$\exists x\exists y\forall u\forall v(C(x, u)\wedge C(y, v)\rightarrow u\neq v)$

(o)  
$\exists x\exists y\forall u\forall v(C(x, u)\wedge C(y, v)\wedge(x\neq v)\wedge(y\neq u))$

###### Exercises 13
(a)  
$\neg M(Chou, Koto)$

(b)  
$\neg M(Arlene, Sarah)\wedge \neg T(Arlene, Sarah) \equiv \neg (M(Arlene, Sarah)\vee T(Arlene, Sarah))$

(c)  
$\neg M(Deborah, Jose)$

(d)  
$\forall xM(x, Ken)$

(e)  
$\neg\exists xT(x, Nina)$

(f)  
$\forall x(T(x, Avi)\vee M(x, Avi))$

(g)  
$\exists x\forall y(M(x, y)\wedge (x\neq y))$

(h)  
$\exists x\forall y((M(x, y)\vee T(x, y))\wedge(x\neq y))$

(i)  
$\exists x\exists y(M(x, y)\wedge M(y, x)\wedge (x\neq y))$

(j)  
$\exists xM(x,x)$

(k)  
$\exists x\forall y((\neg M(y, x))\vee (\neg T(y, x))\wedge(x\neq y)$

alternatively:  
$\neg\forall x\exists yM(y, x)\vee T(y, x)\wedge (x\neq y)$


(l)  
$\forall x\exists yM(y,x)\vee T(y, x)$

(m)  
$\exists x\exists yM(x, y)\rightarrow T(y, x)$

(n)  
$\exists x\exists y \forall z(x\neq y)\wedge(M(x,z)\vee T(x, z)\vee M(y, z)\vee T(y, z))$ 
