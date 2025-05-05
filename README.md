# 360-246-assignment-1---surface-representations-solved
**TO GET THIS SOLUTION VISIT:** [360.246 Assignment 1 – Surface Representations Solved](https://www.ankitcodinghub.com/product/360-246-assignment-1-surface-representations-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100601&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;360.246&nbsp;Assignment 1 - Surface Representations Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
Dense Grid Signed Distance Function

</div>
</div>
<div class="layoutArea">
<div class="column">
• •

</div>
<div class="column">
You may use any compiler of your liking, however we recommend additional warning output. When using GCC, at least the following flags should be used: -std=c++11 -Wall -Wextra -pedantic

Make sure you structure your programs in a readable fashion. It will make you more efficient and help us identify possible errors easily, i.e.: save you marks if there are problems.

</div>
</div>
<div class="layoutArea">
<div class="column">
The signed distance function Φ(⃗x) is a method by which a surface can be defined implicitly. It gives the shortest distance of the point ⃗x to the surface it describes. The sign of the distance relates to the point being outside or inside the surface. Although there is no strict convention, most simulation frameworks use negative values to describe points inside the surface, which is the convention you should follow.

1.1 Task

Implement a dense rectangular grid on which to store the signed distance function of a surface. The grid should fulfil the following:

<ul>
<li>The grid extent in each dimension, as well as the grid spacing(∆x), should be variable</li>
<li>Both reflective and periodic boundary conditions should be imple- mented (see Fig. 2)</li>
<li>Block allocated memory should be used for your data structures</li>
</ul>
</div>
<div class="column">
Figure 1: Dense grid with highlighted boundary points.

</div>
</div>
<div class="layoutArea">
<div class="column">
Represent the following surfaces defined by parameters shown in parentheses, by filling your grid with the respective signed distance function:

• Sphere (centre, radius)

• Axis-parallel rectangle (minimum Corner, maximum Corner)

In your report, describe how you generated each surface and how the grid resolution of the implicit representation as a level set influences the accuracy of the surface description. Your program should be callable using:

<pre>   ./grid x-size y-size spacing [Sphere | Rectangle] [parameters]
</pre>
Hint: Use helper functions to translate neighbour points outside of the grid to indices inside your grid according to the chosen boundary condition. If the boundary condition is reflective, a point at xmax + d should be mapped to xmax − (d − spacing). If it is periodic, the same point should be mapped to xmin + (d − spacing).

Hint: In order to analyse your results, you may use the provided vtkOutput.hpp file to generate a VTK Rectilinear Grid. The data can then be visualised using ParaView, which also provides functionality for analysing the data, e.g.: generating the explicit surface (zero level set) under Filters− &gt; Alphabetical− &gt; Contour using the contour value 0.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Reflective Periodic

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 2: The centre rectangle with white background is the simulation domain, where a signed distance function is stored with the surface (the zero level set) shown in red. The grey rectangles are the neighbourhood of the simulation domain for reflective and periodic boundary conditions. The neighbourhood is here only shown to visualise the boundary conditions and will not be represented in your grid, which only consists of the centre rectangle.

2 Geometric Variables of a Signed Distance Function

During physical simulations, the geometric parameters of a surface, such as the surface normal or the curvature, are often required. In implicit surface representations, these need to be generated from the signed distance function.

</div>
</div>
<div class="layoutArea">
<div class="column">
2.1 Numerical Derivatives

Due to the properties of signed distance functions, geometric variables can be approximated using its derivatives. Numerically, they are calculated using the forward Di+ and backward Di− differences

Di± (Φ(⃗x)) = ± Φ(⃗x ± ⃗ei ) − Φ(⃗x) , (1) ∆x

where Φ(⃗x) is the signed distance function at ⃗x, ⃗ei the vector to the next grid point in direction i and ∆x the grid spacing. The numerical derivative is then given by the central difference, which is the average of the two:

</div>
<div class="column">
Figure 3: Next neighbours of point at ⃗x in a dense grid.

</div>
</div>
<div class="layoutArea">
<div class="column">
Di(Φ(⃗x)) = Di+(Φ(⃗x)) + Di−(Φ(⃗x)) = Φ(⃗x + ⃗ei) − Φ(⃗x − ⃗ei) . (2) 2 2∆x

2.2 Surface Normal

Since the signed distance function increases linearly away from the surface, the direction of maximum change(i.e. the derivative) gives the normal vector to the level set:

⃗n(⃗x)=∇Φ . (3) | ∇Φ |

</div>
</div>
<div class="layoutArea">
<div class="column">
Therefore, the i-th component of the normal vector can be approximated numerically using central differences: Di (Φ(⃗x))

</div>
</div>
<div class="layoutArea">
<div class="column">
ni(⃗x) ≈ 􏰄􏰂D , (4) j=1 Dj(Φ(⃗x))2

</div>
</div>
<div class="layoutArea">
<div class="column">
where D is the number of dimensions used in the simulation, in our case D = 2. 2.3 Curvature

Since the curvature is essentially the second derivative, it is given by

κ(⃗x) = ∇ · ∇Φ(⃗x) = ∇ · ⃗n(⃗x) . (5)

| ∇Φ(⃗x) | 2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Therefore, the simplest approximation to the curvature is the sum of central differences of the normal vectors around the current point:

</div>
</div>
<div class="layoutArea">
<div class="column">
2.4 Task

</div>
</div>
<div class="layoutArea">
<div class="column">
D D κ(⃗x) ≈ 􏰃 Di(⃗ni(⃗x)) = 􏰃

ii

</div>
<div class="column">
n i ( ⃗x + ⃗e i ) − n i ( ⃗x − ⃗e i ) 2∆x

</div>
<div class="column">
(6)

</div>
</div>
<div class="layoutArea">
<div class="column">
Implement functions to calculate the normal vector and curvature for any given point in the dense signed distance grid described earlier. The program should output the normal vector and the curvature at point (x,y) when invoked as follows:

./grid x-size y-size spacing [Sphere | Rectangle] [parameters] x y

3 Moving the Zero Level Set to Advance a Surface

Since the explicit surface is defined by the zero level set, the surface can be moved by changing the signed distance function. In microelectronic process simulations this would correspond to the passage of time during a fabrication step which etches or deposits on a surface. The simplest way to do this is by adding a constant value to the signed distance function, which will simply shift the interface along the surface normals. Therefore, the time evolution is given by

∂Φ(⃗x) = −V (⃗x) , (7) ∂t

where V (⃗x) is a scalar velocity field describing the movement of the surface at any point in the domain. However, for curved surfaces this would lead to the signed distance function losing its normalisation, which

is why the scalar field has to be normalised using the gradient of the signed distance function:

∂Φ(⃗x) = −V (⃗x) | ∇Φ(⃗x) | . (8)

∂t

Therefore, the change of the values in the signed distance function in one time step is

∆Φ(⃗x) = −V (⃗x) | ∇Φ(⃗x) | ∆t . (9)

Since the right-hand side of Eq. (8) is a Hamiltonian, many numerical schemes exist to solve it, the simplest being the Engquist-Osher scheme

􏰄

</div>
</div>
<div class="layoutArea">
<div class="column">
 f or V (⃗x) &lt; 0 : | ∇Φ(⃗x) |=

</div>
<div class="column">
􏰂Di=1 [max(−Di− (Φ), 0)]2 + [min(−Di+ (Φ), 0)]2

􏰄 , (10)

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰂Di=1 [max(Di− (Φ), 0)]2 + [min(Di+ (Φ), 0)]2 steps taken are small enough to satisfy the Courant-Friedrichs-Lewy (CFL) condition

max|V(⃗x)| ≤ ∆x . (11) ∆t

Therefore, in order to advance the simulation time by t, equation Eq. (10) has to be solved t/∆t times to guarantee a stable movement of the surface.

3.1 Task

Investigate how advancing the surface changes the signed distance function. Compare the following ways of advancing the surface:

• Simply subtracting a velocity value from every grid point as in Eq. (7)

• Several steps of the Engquist-Osher scheme Eq. (8) – Eq. (11)

Compare the results for V (⃗x) = const for a positive velocity greater than several grid spacings for the following

shapes:

• Sphere (radius of 10) for V = 10 at the resolutions ∆x = (1, 0.25) for the times t = (0.1, 1)

• Rectangle (with side lengths 5, 20) for V = 10 at the resolutions ∆x = (1, 0.25) for the times t = (0.1, 1)

</div>
</div>
<div class="layoutArea">
<div class="column">
 f or V (⃗x) &gt; 0 :

which will result in a properly normalised signed distance function in the whole domain, as long as the time

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Describe what effect different advection schemes have on the result and how the grid spacing influences the results of each scheme.

Use the normal vectors at each point to introduce a vector velocity function V⃗ (⃗x), which can move the surface directionally. The scalar velocity value used in all algorithms, V (⃗x), can be generated easily by taking the dot product of the vector velocity and the normal vector at that point:

V (⃗x) = V⃗ (⃗x) · ⃗n(⃗x) (12) Use the normal vectors and curvatures generated earlier to investigate the following, using the Engquist-Osher

scheme:

• How does the rectangle behave over many time steps when it is moved by the vector velocity function

V⃗ (⃗x) = (1, 0) ?

• Investigate what happens when the curvature is used as the velocity,

i.e. V (⃗x) = −κ(⃗x). What could this be used for?

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
