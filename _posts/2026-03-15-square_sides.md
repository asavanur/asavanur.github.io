---
title: "Square Sides"
layout: post
---

We will now return to Babylon, and to geometry. Suppose you are a Babylonian surveyor who wants to draw the boundaries of a field being distributed to farmers. An easy way to make a rectangular field is to use the Pythagorean theorem to find the lengths required to make a triangle with a square corner, and go from there. But what if you are in a situation where you can't make the sides of the triangle simple numbers like 3,4, and 5? You need a way to find the longest side of a triangle given the two perpendicular sides, for any number that you may meet. This makes it necessary to find a square root. <!--more--> 
The Babylonians invented a very accurate procedure to do this{%sidenote 'One' 'A. Flores. [The Babylonian Method for Approximating Square Roots: Why is it so Efficient? The Mathematics Teacher, Vol. 108, No.3 (2014).](https://www.jstor.org/stable/10.5951/mathteacher.108.3.0230)' %}.
They called the square root a "square-side", suggesting they first found it in the context of finding the side of a square whose area was known (this is very close to our application above, remembering that the Pythagorean theorem is intimately related to the area of squares and rectangles).
We will take a simple example, finding the side of a square of area 5 square cubits, and then apply the lessons learned to the more complicated triangle problem. 
The first step, just like the first step of the false position method, is to make a guess. We will make the initial guess of 2. Now we can imagine dividing the total area into a square with area 4 and a rectangle of area 1 as follows, with the rectangle's long side being the same as the square's side:

{% maincolumn "assets/img/blog4/sqrt1.png" " " %}

Let us now cut and paste the shapes and try to turn this into a square whose side we know. Let's divide the rectangle in half top-to-bottom, then we can paste it onto the square: 

{% maincolumn "assets/img/blog4/sqrt2.png" " " %}

Now, this is not exactly a square anymore, but it is very close to one, and we expect the area of the tiny missing square to be very small compared to the total area. We get an answer of 2.25. The missing area is $$(1/4)^2,$$ as you can see from the diagram, so the total area is $$5 + (1/4)^2,$$ or 5.0625, meaning this is a quite accurate approximation. 
Now, in this example, the guess, 2, was smaller than the real square root, because squaring it gives 4, not 5. We can also make a guess that is bigger than the real square root, and then do a similar procedure, but subtracting rectangles instead of adding them.  
Doing this procedure for several numbers, you can also convince yourself that it is equivalent to the following procedure:

$$
begin{enumerate}
    \item \text{Make a guess for the square root (call it a).}
    \item \text{Divide the number you want to take the square root of (call it c) by a.}
    \item \text{Average these two numbers together (add them up and divide by 2). That is, calculate} \frac{a+c/a}{2}.
\end{enumerate}
$$

(This also gives 2.25 for the example above.)
We can imagine doing this procedure over and over again repeatedly, taking the result of the previous step as the input. The answer gets better and better at each step. (There is no written procedure that explicitly tells you to do this repeatedly, but there are several examples of tablets that they take square roots on, and the pattern of numbers on these tablets can be explained by doing this procedure repeatedly, and there are no plausible alternative explanations, so it is highly likely that they did in fact do it repeatedly.)
Now, when you want to find the longest side of the triangle you need, you can simply use this procedure as well as the Pythagorean theorem to do so.
