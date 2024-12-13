## 14. Equations of lines on a plane

* The line passes through points $A(1, 2)$ and $B(3, 4)$. Find the equation of the line.

To find the equation of the line passing through two points $A(x_1, y_1)$ and $B(x_2, y_2)$, we first calculate the slope $m$ using the formula:

$$
m = \frac{y_2 - y_1}{x_2 - x_1}
$$

Substituting the coordinates of $A(1, 2)$ and $B(3, 4)$:

$$
m = \frac{4 - 2}{3 - 1} = \frac{2}{2} = 1
$$

Now that we have the slope, the equation of the line in point-slope form is:

$$
y - y_1 = m(x - x_1)
$$

Substituting $m = 1$ and $A(1, 2)$:

$$
y - 2 = 1(x - 1)
$$

Simplifying:

$$
y = x + 1
$$

Thus, the equation of the line is:

$$
y = x + 1
$$

---
* The line passes through point $A(1, 2)$ and is parallel to the line $y = 2x + 3$. Find the equation of the line.
For a line parallel to $y = 2x + 3$, the slope is the same as the given line, $m = 2$.

Using the point-slope form:

$$
y - y_1 = m(x - x_1)
$$

Substituting $m = 2$ and $A(1, 2)$:

$$
y - 2 = 2(x - 1)
$$

Simplifying:

$$
y - 2 = 2x - 2
$$

$$
y = 2x
$$

Thus, the equation of the line is:

$$
y = 2x
$$

---

* The line passes through point $A(1, 2)$ and is perpendicular to the line $y = 2x + 3$. Find the equation of the line.
For a line perpendicular to $y = 2x + 3$, the slope is the negative reciprocal of the given slope. If $m = 2$, the perpendicular slope is $m = -\frac{1}{2}$.

Using the point-slope form:

$$
y - y_1 = m(x - x_1)
$$

Substituting $m = -\frac{1}{2}$ and $A(1, 2)$:

$$
y - 2 = -\frac{1}{2}(x - 1)
$$

Simplifying:

$$
y - 2 = -\frac{1}{2}x + \frac{1}{2}
$$

$$
y = -\frac{1}{2}x + \frac{5}{2}
$$

Thus, the equation of the line is:

$$
y = -\frac{1}{2}x + \frac{5}{2}
$$
---

* We have two lines $y = 2x + 3$ and $y = 3x + 2$. Find the intersection point of these lines and calculate the angle between them.
### Intersection Point:
To find the intersection, solve the system of equations:

$$
y = 2x + 3 \quad \text{and} \quad y = 3x + 2
$$

Equating the two equations:

$$
2x + 3 = 3x + 2
$$

Simplify:

$$
x = 1
$$

Substitute $x = 1$ into either equation (e.g., $y = 2x + 3$):

$$
y = 2(1) + 3 = 5
$$

Thus, the intersection point is:

$$
(1, 5)
$$

### Angle Between the Lines:
The slopes of the lines are $m_1 = 2$ and $m_2 = 3$. The angle $\theta$ between the lines is given by:

$$
\tan\theta = \left| \frac{m_2 - m_1}{1 + m_1 m_2} \right|
$$

Substitute the values:

$$
\tan\theta = \left| \frac{3 - 2}{1 + 2 \cdot 3} \right| = \left| \frac{1}{7} \right|
$$

The angle is:

$$
\theta = \arctan\left(\frac{1}{7}\right)
$$
---

* Write the equation of the line passing through point $A(1, 2)$ and parallel to the vector $\mathbf{v} = [2, 3]$.
The direction vector $\mathbf{v} = [2, 3]$ has a slope $m = \frac{3}{2}$.

Using the point-slope form:

$$
y - y_1 = m(x - x_1)
$$

Substitute $m = \frac{3}{2}$ and $A(1, 2)$:

$$
y - 2 = \frac{3}{2}(x - 1)
$$

Simplify:

$$
y - 2 = \frac{3}{2}x - \frac{3}{2}
$$

$$
y = \frac{3}{2}x + \frac{1}{2}
$$

Thus, the equation of the line is:

$$
y = \frac{3}{2}x + \frac{1}{2}
$$

---
* We have the line $y = 2x + 3$. Find an example of a line perpendicular and parallel to it.
### Parallel Line:
A line parallel to $y = 2x + 3$ has the same slope $m = 2$. For example:

$$
y = 2x + 5
$$

### Perpendicular Line:
A line perpendicular to $y = 2x + 3$ has slope $m = -\frac{1}{2}$. For example:

$$
y = -\frac{1}{2}x + 4
$$

---
* We have the line $y = 2x + 3$ and point $A(1, 2)$. Find the distance from point $A$ to the line.
The distance $d$ from a point $(x_1, y_1)$ to a line $ax + by + c = 0$ is:

$$
d = \frac{|ax_1 + by_1 + c|}{\sqrt{a^2 + b^2}}
$$

Rewriting $y = 2x + 3$ in standard form:

$$
-2x + y - 3 = 0
$$

Substitute $a = -2$, $b = 1$, $c = -3$, and $(x_1, y_1) = (1, 2)$:

$$
d = \frac{|-2(1) + 1(2) - 3|}{\sqrt{(-2)^2 + 1^2}}
$$

$$
d = \frac{| -2 + 2 - 3 |}{\sqrt{4 + 1}} = \frac{| -3 |}{\sqrt{5}} = \frac{3}{\sqrt{5}}
$$

Thus, the distance is:

$$
\frac{3}{\sqrt{5}} \quad \text{or approximately } 1.34
$$

---
* The line intersects the coordinate axes at points $A(2, 0)$ and $B(0, 3)$. Find the equation of the line.
Using the two points $A(2, 0)$ and $B(0, 3)$, calculate the slope $m$:

$$
m = \frac{3 - 0}{0 - 2} = -\frac{3}{2}
$$

Using point-slope form with $A(2, 0)$:

$$
y - 0 = -\frac{3}{2}(x - 2)
$$

Simplify:

$$
y = -\frac{3}{2}x + 3
$$

Thus, the equation of the line is:

$$
y = -\frac{3}{2}x + 3
$$

---
* Calculate the angle between the line $y = x + 3$ and the $Ox$ axis.
The slope of the line is $m = 1$. The angle $\theta$ with the $Ox$ axis is:

$$
\theta = \arctan(m) = \arctan(1)
$$

Thus, the angle is:

$$
\theta = 45^\circ
$$

---
* Provide a vector perpendicular to the line $x + y + 1 = 0$.
Rewriting $x + y + 1 = 0$ as $y = -x - 1$, the slope is $m = -1$.

A vector perpendicular to this line has a slope that is the negative reciprocal of $-1$, which is $1$. A perpendicular vector is:

$$
\mathbf{v} = [1, -1]
$$
---
# 15. Equations of second-order curves (conic sections)

* Find the equation of a circle with center at point $A(1,2)$ and radius $r=3$.
The general equation of a circle is:

$$
(x - h)^2 + (y - k)^2 = r^2
$$

Where $(h, k)$ is the center, and $r$ is the radius. Substituting $A(1, 2)$ and $r = 3$:

$$
(x - 1)^2 + (y - 2)^2 = 9
$$

Thus, the equation of the circle is:

$$
(x - 1)^2 + (y - 2)^2 = 9
$$

* Find the equation of a parabola intersecting the $Ox$ axis at points $x=2$, $x=4$, and passing through point $y(3)=1$.
The general equation of a parabola with roots at $x_1$ and $x_2$ is:

$$
y = a(x - x_1)(x - x_2)
$$

Substitute $x_1 = 2$, $x_2 = 4$, and the given point $(3, 1)$:

$$
y = a(x - 2)(x - 4)
$$

Substitute $(3, 1)$:

$$
1 = a(3 - 2)(3 - 4)
$$

$$
1 = a(1)(-1) \quad \Rightarrow \quad a = -1
$$

Thus, the equation of the parabola is:

$$
y = -(x - 2)(x - 4)
$$

Simplify:

$$
y = -(x^2 - 6x + 8)
$$

$$
y = -x^2 + 6x - 8
$$

---
* Find the center of the ellipse with the equation $x^2 + 4y^2 - 4x - 16y + 16 = 0$.
### Step 1: Rearrange terms to group $x$ and $y$:

$$
(x^2 - 4x) + (4y^2 - 16y) = -16
$$

### Step 2: Complete the square for $x$ and $y$:

- For $x$: $x^2 - 4x \rightarrow (x - 2)^2 - 4$
- For $y$: $4y^2 - 16y \rightarrow 4((y - 2)^2 - 4) \rightarrow 4(y - 2)^2 - 16$

Substitute back:

$$
(x - 2)^2 - 4 + 4(y - 2)^2 - 16 = -16
$$

Simplify:

$$
(x - 2)^2 + 4(y - 2)^2 = 4
$$

### Step 3: Identify the center:

The center of the ellipse is:

$$
(2, 2)
$$
* Find the slope ($m>0$) of the line $y=mx-5$ that is tangent to the circle with the equation $x^2 + y^2=1$.
### Step 1: Substitute $y = mx - 5$ into the circle equation:

$$
x^2 + (mx - 5)^2 = 1
$$

Expand:

$$
x^2 + m^2x^2 - 10mx + 25 = 1
$$

Combine terms:

$$
(1 + m^2)x^2 - 10mx + 24 = 0
$$

### Step 2: For tangency, the discriminant $\Delta$ must be zero:

$$
\Delta = b^2 - 4ac
$$

Here, $a = 1 + m^2$, $b = -10m$, $c = 24$. Substituting:

$$
\Delta = (-10m)^2 - 4(1 + m^2)(24)
$$

$$
\Delta = 100m^2 - 96 - 96m^2
$$

$$
\Delta = 4m^2 - 96
$$

Set $\Delta = 0$:

$$
4m^2 = 96 \quad \Rightarrow \quad m^2 = 24 \quad \Rightarrow \quad m = \sqrt{24} = 2\sqrt{6}
$$

Thus, the slope is:

$$
m = 2\sqrt{6}
$$

---
* Find the intersection points of the hyperbola $x^2 - y^2 = 1$ with the ellipse's line $x^2 + 4y^2 = 6$.
### Step 1: Solve the system of equations:

1. $x^2 - y^2 = 1$
2. $x^2 + 4y^2 = 6$

From (1), express $x^2$ in terms of $y^2$:

$$
x^2 = y^2 + 1
$$

Substitute into (2):

$$
(y^2 + 1) + 4y^2 = 6
$$

Simplify:

$$
5y^2 + 1 = 6
$$

$$
5y^2 = 5 \quad \Rightarrow \quad y^2 = 1
$$

Thus, $y = \pm 1$. Substitute $y^2 = 1$ into $x^2 = y^2 + 1$:

$$
x^2 = 1 + 1 = 2 \quad \Rightarrow \quad x = \pm \sqrt{2}
$$

### Step 2: Write the intersection points:

The intersection points are:

$$
(\sqrt{2}, 1), \, (-\sqrt{2}, 1), \, (\sqrt{2}, -1), \, (-\sqrt{2}, -1)
$$

---

* For the given hyperbola $x^2 - y^2 = 1$, find the distance between its branches.
The standard form of the hyperbola is:

$$
\frac{x^2}{a^2} - \frac{y^2}{b^2} = 1
$$

Here, $a = 1$, so the transverse axis is $2a = 2$. The branches are separated by the distance of the transverse axis, which is:

$$
2a = 2
$$

Thus, the distance between the branches is:

$$
2
$$
---
# 16. Equations of Planes in Space

---

## 1. The plane passes through points $A(1, 2, 3)$, $B(3, 4, 5)$, and $C(2, 1, 4)$. Find the equation of the plane.

The equation of a plane passing through three points can be determined by finding two vectors lying on the plane and their cross product to get the normal vector.

### Step 1: Find two vectors on the plane.
$$
\vec{AB} = [3 - 1, 4 - 2, 5 - 3] = [2, 2, 2]
$$
$$
\vec{AC} = [2 - 1, 1 - 2, 4 - 3] = [1, -1, 1]
$$

### Step 2: Compute the cross product $\vec{AB} \times \vec{AC}$ to find the normal vector $\mathbf{n}$.
$$
\mathbf{n} = \vec{AB} \times \vec{AC} = \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
2 & 2 & 2 \\
1 & -1 & 1
\end{vmatrix}
$$
$$
\mathbf{n} = \mathbf{i}(2 - (-2)) - \mathbf{j}(2 - 2) + \mathbf{k}(-2 - 2)
$$
$$
\mathbf{n} = [4, 0, -4]
$$

### Step 3: Write the plane equation.
The equation of the plane is:
$$
4(x - 1) + 0(y - 2) - 4(z - 3) = 0
$$
Simplify:
$$
4x - 4z = -8
$$
$$
x - z = -2
$$

Thus, the equation of the plane is:
$$
x - z = -2
$$

---

## 2. The plane passes through point $A(1, 2, 3)$ and is parallel to the plane $2x + 3y + 4z = 5$. Find the equation of the plane.

For a parallel plane, the normal vector is the same: $\mathbf{n} = [2, 3, 4]$. Use the point-normal form:

$$
2(x - 1) + 3(y - 2) + 4(z - 3) = 0
$$

Simplify:
$$
2x + 3y + 4z - 2 - 6 - 12 = 0
$$
$$
2x + 3y + 4z = 20
$$

Thus, the equation of the plane is:
$$
2x + 3y + 4z = 20
$$

---

## 3. The plane passes through point $A(1, 2, 3)$ and is perpendicular to the normal vector $\mathbf{n} = [2, 3, 4]$. Find the equation of the plane.

The normal vector $\mathbf{n} = [2, 3, 4]$ defines the plane's orientation. Use the point-normal form:

$$
2(x - 1) + 3(y - 2) + 4(z - 3) = 0
$$

Simplify:
$$
2x + 3y + 4z - 2 - 6 - 12 = 0
$$
$$
2x + 3y + 4z = 20
$$

Thus, the equation of the plane is:
$$
2x + 3y + 4z = 20
$$

---

## 4. Find the line of intersection of the planes $2x + 3y + 4z = 5$ and $3x + 4y + 2z = 6$.

To find the line of intersection, solve the system of equations. Represent the solution parametrically:

1. Eliminate one variable (e.g., $z$) by subtracting scaled equations.

Multiply the first equation by 2 and the second by 4:
$$
4x + 6y + 8z = 10 \quad \text{(1)}
$$
$$
12x + 16y + 8z = 24 \quad \text{(2)}
$$

Subtract:
$$
-8x - 10y = -14
$$
$$
x = \frac{-10y - 14}{-8} = \frac{5y}{4} + \frac{7}{4}
$$

Let $z = t$ (parameter). Substitute $x$ and $z$ into one of the plane equations to find $y$. Final parametric equation:

$$
\vec{r}(t) = \begin{bmatrix} x \\ y \\ z \end{bmatrix} = \begin{bmatrix} \frac{5y}{4} + \frac{7}{4} \\ y \\ t \end{bmatrix}
$$

(You can continue simplifying or rewriting as needed.)

---

## 5. Write the equation of the plane passing through point $A(1, 2, 3)$ and parallel to vectors $\vec{v_1} = [1, 0, 1]$ and $\vec{v_2} = [0, 1, -1]$.

The normal vector is the cross product $\vec{v_1} \times \vec{v_2}$:
$$
\mathbf{n} = \begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
1 & 0 & 1 \\
0 & 1 & -1
\end{vmatrix}
$$
$$
\mathbf{n} = [(-1) - (1)]\mathbf{i} - [(1) - (0)]\mathbf{j} + [(1) - (0)]\mathbf{k}
$$
$$
\mathbf{n} = [-2, -1, 1]
$$

The plane equation is:
$$
-2(x - 1) - (y - 2) + (z - 3) = 0
$$
Simplify:
$$
-2x - y + z = -8
$$

---

## 6. Example of a plane parallel and perpendicular to $2x + 3y + 4z = 5$.

### Parallel:
A parallel plane has the same normal vector:
$$
2x + 3y + 4z = 10
$$

### Perpendicular:
A perpendicular plane requires a normal vector orthogonal to $[2, 3, 4]$. For example, $[3, -2, 0]$. Equation:
$$
3x - 2y = 5
$$

---

## 7. Distance from point $A(1, 2, 3)$ to the plane $2x + 3y + 4z = 5$.

The distance formula is:
$$
d = \frac{|2(1) + 3(2) + 4(3) - 5|}{\sqrt{2^2 + 3^2 + 4^2}}
$$

Calculate:
$$
d = \frac{|2 + 6 + 12 - 5|}{\sqrt{4 + 9 + 16}}
$$
$$
d = \frac{|15|}{\sqrt{29}} = \frac{15}{\sqrt{29}}
$$

---

## 8. The plane intersects the coordinate axes at points $A(2, 0, 0)$, $B(0, 3, 0)$, and $C(0, 0, 4)$. Find the equation of the plane.

The general form is:
$$
\frac{x}{2} + \frac{y}{3} + \frac{z}{4} = 1
$$

Multiply through:
$$
6x + 4y + 3z = 12
$$

---

## 9. Calculate the angle between the plane $x + y + z = 1$ and the plane $x = 0$.

The angle $\theta$ between two planes is given by:
$$
\cos\theta = \frac{\mathbf{n_1} \cdot \mathbf{n_2}}{|\mathbf{n_1}| |\mathbf{n_2}|}
$$

For $x + y + z = 1$, $\mathbf{n_1} = [1, 1, 1]$.
For $x = 0$, $\mathbf{n_2} = [1, 0, 0]$.

Compute:
$$
\cos\theta = \frac{1(1) + 1(0) + 1(0)}{\sqrt{1^2 + 1^2 + 1^2} \cdot \sqrt{1^2}}
$$
$$
\cos\theta = \frac{1}{\sqrt{3}}
$$
$$
\theta = \arccos\left(\frac{1}{\sqrt{3}}\right)
$$

---

## 10. Find the vector perpendicular to the plane $x + y + z = 1$.

The normal vector $\mathbf{n} = [1, 1, 1]$ is perpendicular to the plane.
# 17.  Equations of Second-Order Surfaces

---

## 1. Write the equation of a sphere with center at point $P = (1, 2, 3)$ and radius $r = 3$.

**Solution:**

The general equation of a sphere is:

$$
(x - x_0)^2 + (y - y_0)^2 + (z - z_0)^2 = r^2
$$

Substitute $P = (1, 2, 3)$ and $r = 3$:

$$
(x - 1)^2 + (y - 2)^2 + (z - 3)^2 = 3^2
$$

Simplify:

$$
(x - 1)^2 + (y - 2)^2 + (z - 3)^2 = 9
$$

**Answer:**

$$
(x - 1)^2 + (y - 2)^2 + (z - 3)^2 = 9
$$

---

## 2. Do the spheres with equations $x^2 + y^2 + z^2 = 1$ and $x^2 + y^2 + z^2 = 2$ have any common points?

**Solution:**

The spheres are concentric (center at origin).  
The first sphere has radius $r_1 = \sqrt{1} = 1$, and the second has radius $r_2 = \sqrt{2}$.  

Since their radii are different and they share the same center, the spheres do **not** intersect.

**Answer:**

No, the spheres do not have any common points.

---

## 3. What curve in space is formed by the intersection of the sphere $x^2 + y^2 + z^2 = 1$ with the sphere $(x - 1)^2 + y^2 + z^2 = 1$? Find the equation of this curve.

**Solution:**

### Step 1: Write the equations of the spheres

1. Sphere 1:  
   $$
   x^2 + y^2 + z^2 = 1
   $$

2. Sphere 2:  
   $$
   (x - 1)^2 + y^2 + z^2 = 1
   $$

Expand sphere 2:

$$
x^2 - 2x + 1 + y^2 + z^2 = 1
$$

Simplify:

$$
x^2 + y^2 + z^2 - 2x + 1 = 1
$$

Subtract sphere 1 from sphere 2:

$$
-2x + 1 = 0
$$

Solve for $x$:

$$
x = \frac{1}{2}
$$

### Step 2: Substitute $x = \frac{1}{2}$ into sphere 1

$$
\left(\frac{1}{2}\right)^2 + y^2 + z^2 = 1
$$

Simplify:

$$
\frac{1}{4} + y^2 + z^2 = 1
$$

$$
y^2 + z^2 = \frac{3}{4}
$$

### Step 3: Write the equation of the curve

The intersection is a circle in the plane $x = \frac{1}{2}$ with radius $r = \sqrt{\frac{3}{4}} = \frac{\sqrt{3}}{2}$.

**Answer:**

The curve is a circle given by:

$$
x = \frac{1}{2}, \quad y^2 + z^2 = \frac{3}{4}
$$

---

## 4. Write the equation of the tangent plane to the paraboloid $z = (x - 1)^2 + y^2 + 1$ at point $P(1, 0, 1)$.

**Solution:**

### Step 1: Find partial derivatives of the paraboloid

The equation of the paraboloid is:

$$
z = (x - 1)^2 + y^2 + 1
$$

Compute partial derivatives:

$$
\frac{\partial z}{\partial x} = 2(x - 1), \quad \frac{\partial z}{\partial y} = 2y
$$

At $P(1, 0, 1)$:

$$
\frac{\partial z}{\partial x} = 2(1 - 1) = 0, \quad \frac{\partial z}{\partial y} = 2(0) = 0
$$

### Step 2: Write the tangent plane equation

The general form of the tangent plane is:

$$
z - z_0 = \frac{\partial z}{\partial x}(x - x_0) + \frac{\partial z}{\partial y}(y - y_0)
$$

Substitute $P(1, 0, 1)$ and partial derivatives:

$$
z - 1 = 0(x - 1) + 0(y - 0)
$$

Simplify:

$$
z = 1
$$

**Answer:**

The equation of the tangent plane is:

$$
z = 1
$$
