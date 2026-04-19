---
title: "The Babylonian Pythagorean Theorem"
layout: post
---

The Babylonians knew some trigonometry. In addition to knowing the area of a triangle, they knew the "Pythagorean" theorem, among other things. <!--more-->
They likely discovered the theorem in the course of surveying fields or parcels of land more than a thousand years before Pythagoras{%sidenote 'One' '[J. Hoyrup, Pythagorean "Rule" and "Theorem"--Mirror of the Relation between Babylonian and Greek Mathematics (1999)](https://forskning.ruc.dk/en/publications/pythagorean-rule-and-theorem-mirror-of-the-relation-between-babyl)' %} and then used their knowledge to produce right triangles in future surveys. They knew that right triangles can only be produced if the sides satisfy the theorem, and then essentially "inverted" it, using sides of known length that satisfied the theorem and then extending them, to produce very accurate right angles without actually needing to measure angles{%sidenote 'Two' '[D. Mansfield, Perpendicular Lines and Diagonal Triples in Old Babylonian Surveying. Journal of Cuneiform Studies 72:87-99 (2020).](https://www.journals.uchicago.edu/doi/abs/10.1086/709309?journalCode=jcs)' %}.

There is also evidence that they knew what similar triangles were{%sidenote 'Two' '[D. Mansfield and N. J. Wildberger, Plimpton 322 is Babylonian exact sexagesimal trigonometry. Historia Mathematica 44, 395–419 (2012).](https://www.sciencedirect.com/science/article/pii/S0315086017300691)' %}. Similar triangles have different sizes but their sides are in the same proportions. A triangle whose sides are 3-4-5 is similar to one whose sides are 6-8-10. (These are actually right triangles and their sides satisfy the theorem.)

Therefore, here is a very simple demonstration/proof of the Pythagorean theorem that could have been available to the Babylonians. There is evidence that they knew how to prove the theorem a different way{%sidenote 'Three' 'See figure 5 and the surrounding text in J.P Britton, C. Proust, S. Shnider, Plimpton 322: a review and a different perspective. Archive for History of Exact Sciences. 65 (5): 519–566 (2011).'%}.

Note: it is not known whether the Babylonians came up with the following proof/demonstration. But it is one of the simplest, similar proofs are known to date back to the Greeks{%sidenote 'Four' 'The Pythagorean Theorem is Proposition 47 of Book 1 of the Elements, the most famous work of Greek math. The proof there is not the one I am referencing. See instead Propositions 19 and 31, Book 6. The edition is 
Euclid, The Thirteen Books of the Elements (trans. with introduction and commentary by T. L. Heath) (Dover, 1956), cited in Givental, ["The Pythagorean Theorem: What is it About?"](https://math.berkeley.edu/~giventh/papers/eu.pdf)' %}, and the Babylonians knew of all the concepts used{%sidenote 'Five' 'There is a common thread running through the scholarly literature on this topic, including some of the sources I used, that the Babylonians did not really "prove" anything, even though they knew the mathematical facts, and the Greeks were the first to give proofs (so they call it the "Pythagorean Rule" or something). Math is essentially about empirical discovery and reducing problems to simpler ones, which is universal. Different groups of people prove things slightly differently, and the Babylonians knew how to prove their procedures were correct (see e.g. K. Chemla, *The History of Mathematical Proof in Ancient Traditions* (Cambridge University Press, 2012)) so this thread is just meaningless pedantry, in my opinion.' %}. In addition, as shown by the articles cited in notes 2 and 3 above, they had a much more sophisticated understanding of trigonometry than is generally assumed, so it is highly likely that they knew of the following proof.

Without further ado: 
Scale down all the sides of the triangle. The relevant aspect is the relationship between the sides. As long as we keep the proportions the same, this relationship will not change. So scale down the longest side so it is 1, and scale the other sides appropriately. 

Next, any right triangle can be divided into two similar right triangles by drawing a perpendicular line from the longest side to the right angled corner:

{% maincolumn "assets/img/blog3/area sum.png" " " %}

This was probably discovered empirically too. It doesn't work for non-right triangles.
All the sides of a similar triangle are in the same proportion as the sides of the original triangle. The lengths have simply been scaled down. So since the medium-length side is a factor of $$b$$ smaller than the longest side, and the smallest side is a factor of $$a$$ smaller, that is also true for the two triangles that the original triangle has been split into. So the smallest side of the smallest triangle has a length of $$a^2,$$ for example.
All the sides have been marked in the diagram. 

We can now read off the lengths that make up the longest side (length 1) and thus read off the Pythagorean theorem: 

$$a^2+b^2=1.$$

In words:  
The sum of the squares of the two smaller sides of a triangle is equal to the square of the largest side. 
