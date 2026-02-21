---
title: "Babylonian Geometry"
layout: post
---

We will start our journey at the very beginning of science and math: ancient Babylon. 
People have been doing math for tens of thousands of years (e.g. the "Ishango" bone, from 26,000 years ago in Southern Africa, with uneven groups of tally marks on it). But, to our knowledge, it really started to take off in ancient Egypt and Babylon around 3000 BC, and their math influenced modern math heavily. 

Numerals were invented and used to make the administration of the kingdom easier. As a kingdom grows, there is  a greater need to tally bigger and bigger numbers of tax receipts and other such things, so this naturally results in a need to invent a simpler way of keeping track of amounts {%sidenote 'One' 'E. Robson. *Mathematics in Iraq: A Social History,* p. 34-40.'%}. In addition, you can't tax a farmer correctly if you don't know how big his field is. This resulted  in both the invention of written numerals and area formulas. 

The Babylonians used a numeral system like ours but with a base of 60 instead of 10 (i.e moving one place to the left increases the number by a factor of 60 instead of 10. They would write 100 as 1*60+40, or "1;40"). The 60 came from the need to flexibly combine different systems of units, as different commodities were measured in different units{%sidenote 'Two' 'E. Robson. *Mathematics in Iraq: A Social History,* p. 77.'%}. The key idea in the invention of area formulas is a standardized unit of length, and a unit of area. The idea is to figure out how big any given length is in terms of a convenient unit. The Babylonians used a cubit, essentially a standardized arm length (the American foot is a standardized foot length, supposedly). When you have a field to measure, you can measure both of its sides in terms of cubits, and then once you figure that out you can find the area in terms of squares, each of whose sides has a length of one cubit. 

From there, you can actually figure out the rules for multiplication. If you have 5 rows of 5 squares each, you can count each one individually, or you can count up by steps of 5 and write the results in a table to use for reference, and repeat the process for different sizes of fields. Many of these base 60 multiplication tables have been found, and one reason 60 was useful is that because 60 is divisible by a lot of numbers, you do not have to make a 60x60 table in order to quickly find the results of any multiplication, you can use the relationships between the factors{%sidenote 'Three' 'E. Robson. *Mathematics in Iraq: A Social History,* p. 87.'%}.

The Babylonians went further, however. Before 3000 BC, they had figured out the area of a trapezoid{%sidenote 'Four' 'E. Robson. *Mathematics in Iraq: A Social History,* p. 30.'%}.

Take a trapezoid with one slanted side, like so:

{% maincolumn "assets/img/trapezoid.png" " " %}

You can divide it into a rectangle and a triangle:

{% maincolumn "assets/img/trapezoid2.png" " " %}

A triangle, by the way, can always be thought of as half a rectangle:

{% maincolumn "assets/img/rectangle.png" " " %}

With these two facts in mind, we can simply find the areas and add them:

$$ \text {Area of trapezoid} = \text{Area of rectangle} + \text{Area of triangle} = 2 \times 1 + \frac{2 \times 1}{2}=3.$$

The Babylonians likely discovered empirically, with diagrams drawn in the sand or with small fields, that adding the two previous areas results in the same value as simply averaging the parallel horizontal sides and then multiplying that value by the vertical side, i.e. that $$ \frac{1+2}{2} \times 2=3. $$ The same procedure applies to the case where two sides are slanted, you simply have to add the area of two triangles to the rectangle. 
