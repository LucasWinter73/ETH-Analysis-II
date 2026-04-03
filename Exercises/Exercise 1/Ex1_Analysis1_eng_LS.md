# Exercise Sheet 1 LSG:

## 1.1 Recap Questions

1. No, it can just jump all over the interval [1, 2] without converging. There exists however a converging subsequence.

2. ```math
   f(x) = ln(x) + C => f'(x) = 1 / x
   ```

3. Substitution $t = cos(x)$ gives $dt = -sin(x) dx = -\sqrt{1-t^2}dx$ hence 
   $$
   \int{f(cos(x))dx = \int{\frac{f(t)}{\sqrt{1-t^2}}}}
   $$

4. if $f''(x)>0$, $f$ is strictly convex, so it **cannot** have a global maximum at an interior point $x>0$. But it can have a global maximum at the boundary $x=0$.
   $$
   f(x) = -x + e^{-x}
   $$

   $$
   f''(x) = e^{-x} > 0
   $$

   so $f$ decreases on $[0,\infin)$ and the global maximum is at $x=0$

5. given $ϕ$ is a linera map defined on $\R^2$, if we now take $ϕ(Q)$ where as $Q := [0,1] * [0,1]$ we get that that  must also be a linear function, thus it basically has to be a line.

6. Yes, $D:V→V$ is a linear map.

   for any polynomials $p,q ∈ V$ and scalars $a,b ∈ \R$ we get:
   $$
   D(ap + bq) = (ap + bq)' = ap' + bq' = a D(p) + b D(q)
   $$
   so $D$ satisfies lineraity



## 1.3 From drawings to equations.

1) We take a vector that points to $(-1,1)$ from the origin, and now we have to periodically scale it between 0 and 1.
   

$$
f(t) = \frac{1 + sin(t)}{2}(-1,1)
$$

2) 

3) Take a ball defined by $x^2+y^2+z^2 ≤1$ (Ball with radius $r=1$)

   Interesect it with the plane:
   $$
   \set{(x,y,z):x+y+z = 0 \and x^2+y^2+z^2 ≤ 1}
   $$

4) Take a circle in the plane $x^2+y^2 ≤ 1$

   Remove the quarter where $x≥0 \and y≥0$

   Take intersection fo circle and compliment of the cutout:
   $$
   \set{x,y \in \R:x^2+y^2 ≤1 \and x<0 \or y<0}
   $$

5) 

## 1.4 Young's inequality.



