---
title: "The Babylonian Pythagorean Theorem"
layout: post
---

The Babylonians knew some proto-trigonometry. In addition to knowing the area of a triangle, they also knew the Pythagorean theorem. <!--more-->
They likely discovered the theorem in the course of surveying fields or parcels of land around 1875 BC (more than a thousand years before Pythagoras), and then used their knowledge to produce right angles in future surveys. They knew that right triangles can only be produced if the sides satisfy the theorem, and then essentially "inverted" it, using sides of known length that satisfied the theorem and then extending them, to produce very accurate right angles without actually needing to measure angles{%sidenote 'One' '[Mansfield, D. Perpendicular Lines and Diagonal Triples in Old Babylonian Surveying. Journal of Cuneiform Studies 2020. 72:87-99.](https://www.journals.uchicago.edu/doi/abs/10.1086/709309?journalCode=jcs) '%}.

There is also evidence that they knew what similar triangles were{%sidenote 'Two' '[Mansfield, D; Wildberger, N.J. Plimpton 322 is Babylonian exact sexagesimal trigonometry. Historia Mathematica 44 (2017) 395–419.](https://www.sciencedirect.com/science/article/pii/S0315086017300691)' %}. Similar triangles have different sizes but their sides are in the same proportions. A triangle whose sides are 3-4-5 is similar to one whose sides are 6-8-10. (These are actually right triangles and their sides satisfy the theorem.)

Therefore, here is a very simple demonstration/proof of the Pythagorean theorem that could have been available to the Babylonians. There is evidence that they knew how to prove the theorem a different way{%sidenote 'Three' 'Britton, J.P.; Proust, C.; Shnider, S. (2011). "Plimpton 322: a review and a different perspective". Archive for History of Exact Sciences. 65 (5): 519–566.'%}.

Note: it is not known whether the Babylonians came up with the following proof/demonstration. But it is one of the simplest, similar proofs are known to date back to the Greeks{%sidenote 'Four' 'The Pythagorean Theorem is Proposition 47 of Book 1 of the Elements, the most famous work of Greek math. The proof there is not the one I am referencing. See instead Propositions 19 and 31, Book 6. The edition is 
Euclid, The Thirteen Books of the Elements (trans. with introduction and commentary by T. L. Heath), Dover, 1956, cited in Givental, ["The Pythagorean Theorem: What is it About?"](https://math.berkeley.edu/~giventh/papers/eu.pdf)' %}, and the Babylonians knew of all the concepts used{%sidenote 'Five' 'There is a common thread running through the scholarly literature on this topic, including some of the sources I used, that the Babylonians did not really "prove" anything, even though they knew the mathematical facts, and the Greeks were the first to give proofs. Math is essentially about empirical discovery and reducing problems to simpler ones, which is universal. Different groups of people prove things slightly differently, (see e.g. Chemla, The History of Mathematical Proof in Ancient Traditions, 2012) so this thread is just meaningless pedantry, in my opinion.' %}.

Without further ado: 
The area of a right triangle increases in proportion to the square of its longest side. For example, multiply the longest side by 3, and the area increases by a factor of 9. You can try this (increasing the longer side) for any rectangular array, and it will work. Make sure to keep the proportions the same. 

{% maincolumn "assets/img/blog3/scaling.png" " " %}

A right triangle is simply half of a rectangle, as we know, so the same thing should work for it.  
This rule actually holds for all sides. Take the same initial rectangle and, keeping the proportions the same, increase the small side by a factor of 3. The area still increases by a factor of 9, because this is the same process, stated in a different way.

Next, any right triangle can be divided into two similar right triangles by drawing a perpendicular line from the longest side to the right angled corner:

{% maincolumn "assets/img/blog3/area sum.png" " " %}

This was probably discovered empirically too. It doesn't work for non-right triangles.
So the area of a right triangle can be obtained by adding up the areas of the smaller right triangles that make it up. Each of those areas is proportional to the square of the longest side of the triangle it corresponds to, from earlier. We can call the proportionality constant "k." Now we can state

$$\text{Area of A} + \text{Area of B} = \text{Area of C}$$ 

so 

$$ k \times a^2+k \times b^2=k \times c^2. $$

Since the sides have the same ratio, the proportionality constant is the same. Therefore, 

$$a^2+b^2=c^2.$$
