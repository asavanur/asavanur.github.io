---
title: "Dividing Up Fields"
layout: post
---

Given that many of the Babylonians were farmers, and that there were many of them competing for a limited amount of land, they had to figure out ways of giving out land fairly. The problem of dividing a given parcel of land into equal parts was thus very common. <!--more--> For simple cases, like dividing a square into equal parts, it is obvious: divide the square into rectangular parts of equal size. But what about dividing trapezoids into equal parts? Those are slightly more complicated, and very common as field shapes (e.g. suppose your rectangular field has one or two corners cut off by rivers).

Let us consider the simplest example of this: dividing a trapezoid in half. We know the total area of the trapezoid, and we want to find out where we should cut (or place a rope) such that the areas on either side of the cut are equal. We can draw a diagram:

{% maincolumn "assets/img/blog5/trapezoid.png" " " %}

Now you could object: but why can't we just eyeball it? Why do we have to do anything more complicated? The answer to that is: in simple cases, like the one we are doing, you can, but in more complicated cases you can't. The method has to work for both simple and more complicated cases. In addition, land was scarce and valuable, so to make sure that everybody was being given a fair shake, they had to be precise.
So, without further ado, we have a trapezoid whose bases are 12 and 8, and whose height (not marked on the diagram) is 6. We can find the total area of the trapezoid as follows: imagine drawing a line from the corner of the lower base to the top of the trapezoid. That is the height, and we know it has a value of 6. The rectangle formed by the height and the lower base has an area of $$6 \times 8=48.$$ We now add to it the area of the two triangles that are formed, which both have bases of 2. They combine to form a rectangle of base 2 and height of 6, so their total area is 12 and then the total area of the trapezoid is $$48+12=60$$ cubits. We want to divide this trapezoid into two trapezoids, each having 30 cubits of area.

{% maincolumn "assets/img/blog5/trapezoidarea.png" " " %}

We now need to introduce a new concept: how steep a line is. The Babylonians used this concept extensively (e.g. in making slanted parts of buildings), and they captured it mathematically by calculating the ratio of how far a line extends in the horizontal direction to how far it extends in the vertical direction (the "run" divided by the "rise"){%sidenote 'One' 'This is the opposite of our current definition of slope. A line with a Babylonian steepness of 3 would have a slope of 1/3.' %}.

Now we can divide the top trapezoid into a rectangle and two triangles, as in the following diagram.
We can label the height of the triangles (which is the thing we want to solve for) "u". Now if the steepness of the slanted sides of the trapezoid is "f", they travel a horizontal distance of f units for every vertical rise of 1 unit. Since the rise in this case is u, the run is $$f \times u $$ (which can also be notated as $$f \cdot u$$). For our example, the difference between the top and bottom sides (the run) is $$12-8=4,$$ this difference is shared equally between the two sides so the run we need to consider is 2, and the rise is 6, so our value for f will be 2/6 or equivalently 1/3 (0.333). Now everything is set up. To be continued...

{% maincolumn "assets/img/blog5/trapezoidsetup.png" " " %}
