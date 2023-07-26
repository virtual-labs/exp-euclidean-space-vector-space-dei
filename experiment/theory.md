### Theory

Let N and R denote the natural numbers and real numbers respectively.

**1. Euclidean Space (2-dimensional):**
 The system ( R<sup>2</sup> ,+ , . ) together with R is the 2-dimensional Euclidean space, where

**(i)** R<sup>2</sup> = { (x , y) | (x , y) ∈ R} <br>
**(ii)** + , called addition, is defined as <br>
&emsp; (a , b) + (c , d) = ( a+c , b+d ) where a, b, c, d ∈ R <br>
**(iii)** . , called scalar multiplication, is defined as <br> 
&emsp; α . (a , b) = (α . a , α . b) where α is the scalar and a , b ∈ R . <br>

Note that,

**a.** In (ii), "+" on the left side is the addition of R<sup>2</sup> and on the right side it is the addition of R.<br>
**b.** In (iii), "." on the left side is the scalar multiplication of R<sup>2</sup> and on the right side it is the multiplication of R.

**2. Geometric Visualization:**
It is well known that there is a one-to-one correspondence between the plane and R<sup>2</sup>. That is, for each point on the plane there corresponds an element of R<sup>2</sup> and conversely, to each point in the plane there is an element of R<sup>2</sup>. **It may be noted** that this association between points in the plane and the elements in R<sup>2</sup> is with respect to a given pair of axes. Thus given a point on the plane, if we change the chosen axes, the element in R<sup>2</sup> may be changed. Similarly, given an element in R<sup>2</sup>, if we change the chosen axes, a different point on the plane may be obtained.<br>
In the same manner, R and R<sup>3</sup> can be identified with the line and space respectively. Such a visualization is not possible for R<sup>n</sup> , for n>3.

**3. Math Model of Line, Plane and Space:**
The one-to-one correspondence between the plane and R<sup>2</sup>, described above provides an identification of plane with R<sup>2</sup>. Therefore R<sup>2</sup> serves as a mathematical model for the study of the plane. Similarly, R and R<sup>3</sup> serve as mathematical models for the study of the line and the space respectively.

**4. Vector Representation:**
 Let P be a point on the plane and (u , v) be the corresponding ordered pair. The line segment joining the origin and the point directed towards the point is called the vector at the origin associated with the point P. Please see the diagram given below.

 ![Vector Representation](images/theoryimage.jpeg "Vector Represntation")

**5. n-dimensional Euclidean Space:**
 It is the system ( R<sup>n</sup> , + , . ) together with R, where R<sup>n</sup> = {(x<sub>1</sub>, x<sub>2</sub>, x<sub>3</sub>, ... , x<sub>n</sub>) | x<sub>1</sub>, x<sub>2</sub>, x<sub>3</sub>, ... , x<sub>n</sub> ∈ R} and operations + and . called addition and scalar multiplication respectively are defined as:

**(i)** {(x<sub>1</sub>, x<sub>2</sub>, x<sub>3</sub>, ... , x<sub>n</sub>) + (y<sub>1</sub>, y<sub>2</sub>, y<sub>3</sub>, ... , y<sub>n</sub>) = (x<sub>1</sub>+y<sub>1</sub> , x<sub>2</sub>+y<sub>2</sub> , ... , x<sub>n</sub>+y<sub>n</sub>)}, where x<sub>1</sub>, x<sub>2</sub>, x<sub>3</sub>, ... , x<sub>n</sub>, y<sub>1</sub>, y<sub>2</sub>, y<sub>3</sub>, ... , y<sub>n</sub> ∈ R <br>
**(ii)** α . (x<sub>1</sub>, x<sub>2</sub>, x<sub>3</sub>, ... , x<sub>n</sub>) = (α.x<sub>1</sub>, α.x<sub>2</sub>, α.x<sub>3</sub>, ... , α.x<sub>n</sub>) where α, x<sub>1</sub>, x<sub>2</sub>, x<sub>3</sub>, ... , x<sub>n</sub> ∈ R

It can be geometrically visualised for 1≤n≤3 only. 

**6. Vector Space:**
 Let F=R or C, where C is the field of complex numbers. Given a non-empty set V and operations "+" **(called addition)** and "." **(called scalar multiplication)**, the system (V , + , .) together with F is called a **vector space** over F, if the following conditions hold:

**For Addition:** <br>
&emsp; **i.** For each pair of elements x, y ∈ V, there is a unique element x + y ∈ V <br> 
&emsp; **ii.** Commutativity: x + y = y + x for all x, y ∈ V <br>
&emsp; **iii.** Associativity: (x + y) + z = x + (y + z) for all x, y, z ∈ V <br>
&emsp; **iv.** Additive identity: There exists an element O ∈ V s.t. x + O = x, for all x ∈ V.<br>
&emsp;  &emsp; This O which is the additive identity of (V, +), is called the zero of V and is denoted by 0.<br>
&emsp; **v.** Additive inverse: For every x ∈ V, there exists an element y ∈ V s.t. x + y = 0. This y is called the additive inverse of x and is denoted by -x.

**For Scalar Multiplication:** <br>
&emsp; **i.** For each x ∈ V and a ∈ F, there is a unique element a.x ∈ V <br>
&emsp; **ii.** Associativity: (ab).x = a.(bx) = x.(ab) for all x ∈ V, for all a, b ∈ F. <br>
&emsp; **iii.** 1.x = x.1 for all x ∈ V, where 1 ∈ F.

**For Addition and Scalar Multiplication:** <br>
&emsp; **i.** Distributive: a.(x+y) = a.x + a.y for all x, y ∈ V, for all a ∈ F. <br> 
&emsp; **ii.** Distributive: (a+b).x = a.x + b.x for all x ∈ V, for all a, b ∈ F. 

**NOTE:** The elements of F are called **scalars** and the elements of V are **vectors**. A vector space over F will be denoted by V.

**7. Example**
(R<sup>n</sup>, + , .) is a vector space over R, where n ∈ N. It will be denoted by R<sup>n</sup>. The zero of this vector space is 0 ≡ (0, 0, ..., 0). Thus elements of R<sup>n</sup> are vectors and elements of R are scalars. In the particular case when n=1, elements of R are both vectors and scalars.

**8. Properties**
For v, w ∈ V and α ∈ F,

&emsp; **A.** 0.v = 0 <br>
&emsp;&emsp;   (0 on the left side is the zero of F and on the right side it is the zero of V) <br>
&emsp; **B.** α.v = 0 implies α = 0 or v = 0<br>
&emsp;&emsp;   (-1).x = -x, x ∈ V, -1 ∈ F<br> 
&emsp; **C.** α.v = α.w and α ≠ 0 implies v = w.

**9. Significance**
The study of n-dimensional Euclidean space has enlightened research in many broad areas of science over the period of time. n-dimensional spaces have since become one of the foundations for formally expressing modern mathematics and physics.

*NOTE: Even if you are familiar with any of the notions explained here, you should not skip those steps, as these are necessary for the desired understanding.*
