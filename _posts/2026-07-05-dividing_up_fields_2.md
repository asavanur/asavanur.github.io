---
title: "Dividing Up Fields part 2"
layout: post
---

Last time we set up the problem of dividing a trapezoid in half, the simplest example of a "field division problem". Now we can finish solving it.<!--more--> 
We can focus on the top half of the trapezoid and ignore the bottom half. The strategy is to, by cutting and pasting, turn it into a square whose side we know, similar to the strategy that we used to take the square root{%sidenote 'One' 'This type of problem is in e.g. figure 3.3 of [J. Friberg,  Geometric division problems, quadratic equations, and recursive geometric algorithms in Mesopotamian mathematics, Archive for History of Exact Sciences, Vol. 68, No. 1 (January 2014), pp. 1-34](https://www.jstor.org/stable/24569611). Real-world situations in which this type of problem is solved can be found there as well.'%}.

First make the trapezoid into a rectangle by adding triangles of the right base and height:
{% maincolumn "assets/img/blog6/addingtriangles.png" " " %}
The area of the rectangle is now 30 plus the area of the two triangles, but the triangles can be rearranged into a rectangle, so the area is 30 plus the area of a rectangle with height $$u$$ and length $$u/3.$$ This area is also $$12 \cdot u.$$
Now stretch the big rectangle horizontally by a factor of 3, so the length of the small rectangle goes from $$u/3$$ to $$u$$ and it becomes a square (this is easier to deal with){%sidenote 'Two' 'The solution method used here is inspired by the one in [The Algebra of Mohammed Ben Musa, tr. Friedrich Rosen, London: Oriental Translation Fund (1831)](https://legacy-www.math.harvard.edu/~knill/teaching/summer2019/exhibits/algebra/AlgebraMohammedBenMusa.pdf), p.18, cited in ["Completing the Square, a prehistory of the quadratic formula"](https://www.ams.org/publicoutreach/feature-column/fc-2020-11). An equivalent method is in [J. Friberg, A Geometric Algorithm with Solutions to Quadratic Equations in a Sumerian Juridical Document from Ur III Umma, Cuneiform Digital Library Journal (2009), No.3.](https://cdli.earth/articles/cdlj/2009-3)' %}. The total area is now 90 plus the area of a square whose sides are $$u.$$ The new length is 36, and the total area is also $$36 \cdot u.$$
{% maincolumn "assets/img/blog6/stretchedrectangle.png" " " %}
Now we want to make a square of known area. The sides should be equal, so let's cut the whole rectangle in half. $$36/2=18,$$ which suggests that our square will have sides of length 18. Remember that the square of unknown side $$u$$ is still there, and the remaining rectangle will have a length of $$18-u.$$
{% maincolumn "assets/img/blog6/cutstretchedrectangle.png" " " %}
Now let us start rearranging: take the rectangle of length $$18-u,$$ rotate it 90 degrees, and put it on top of the rectangle of length 18. The height of the resulting figure is still 18, since the width of the rectangle is $$u,$$ and we are essentially just putting back the $$u$$ that was taken away from 18 in the previous step. The area of the figure is still 90.
{% maincolumn "assets/img/blog6/rotatedrectangle.png" " " %}
Now we can "complete the square": add a square in the space created, such that the new area is also a square. The area of the whole square is $$18^2=18 \times 18 = 324.$$ The area of the original figure was 90. The square we had to add thus has an area of $$324-90=234.$$
{% maincolumn "assets/img/blog6/squaredrectangle.png" " " %}
We can now find the side of the square using our [method from before](https://asavanur.github.io/articles/26/square_sides). Since $$15^2=225$$ and $$16^2=256,$$ it is between 15 and 16, and since 234 is closer to 225 than it is to 256, it is closer to 15 than 16. I won't repeat the details here. We get 15.3. 
Now, looking at the diagram, we can see that the side length we got plus $$u$$ equals 18. So we can just subtract the value we got from 18 and we have our answer: 2.7. So if we measure out a length of 2.7 cubits, and cut there, we will divide our trapezoid in half.
This value is close to the value we got from just eyeballing it, so it makes sense. Again, this is just a simple case to illustrate the method. The Babylonians were also able to solve far more complicated field division problems that cannot be eyeballed, but the same principles apply.
We just solved a quadratic equation. We can first write out the sentence corresponding to the original equation in English and then we can translate that sentence into a mathematical one: 

The area of a rectangle of sides 12 and u is equal to 30 plus the area of a rectangle of sides u and u/3. 

Equivalently, $$12u=30+u^2/3.$$

The algebraic steps used to solve this are actually equivalent to the geometric ones we used at each step. But it's much easier to deal with as a geometric figure, don't you think?
