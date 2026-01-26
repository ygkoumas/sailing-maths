---
layout: page
title:  "Navalapp Sailing Yacht Design - Course Assignment"
author: Γιάννης Γκούμας
--- 

<style>
.question {
  padding: 20px 10px 30px;
  margin: 50px 0 30px;
  color: #080863;
  background-image: linear-gradient(180deg,#cae3ff,#def6ff,#f3faff, #fff, #fff);
  border-bottom: 3px solid #d4d7ff;
  border-top: 3px solid #0652e1;
}

th, td {
  border: 1px solid black;
  padding: 10px;
}
table {
  border-collapse: collapse
}
div.note {
  font-style: italic;
  color: gray;
}
</style>
<p class="question">
    <strong>a)</strong> Have a look at the notes of the course and look for the mathematical expression used to compute
    BM. Obtain the BM of a prismatic barge, whose dimensions are L = 7m and B = 1,8m, with a displacement of 2 tons. The
    barge is intended to navigate in rivers.
</p>
The mathematical expression to compute BM is the following:


\begin{equation}
BM = \frac{I_{wl}}{\nabla} 
\end{equation}


If the barge navigates in rivers with fresh water the displacement volume of 2 tons will be:


\begin{equation}
\nabla=2m^3
\end{equation}

Let us calculate the Second moment of the flotation area:

\\[I_{wl} = \int_0^7\int_{-1.8/2}^{1.8/2}y^2dydx \\]
or
\\[I_{wl} = \int_0^7\int_{-0.9}^{0.9}y^2dydx \\]
or
\\[I_{wl} = 7 \cdot \int_{-0.9}^{0.9}y^2dy \\]
or
\\[I_{wl} = 7 \cdot [ \frac{y^3}{3} ]_{-0.9}^{0.9} \\]

Thus:
\begin{equation}
I_{wl} = 3.402 m^4
\end{equation}

Combining (1), (2) and (3)
\\[ BM = \frac{3.402 m^4}{2 m^3} \\]
> Thus
> \\[ BM = 1.701 m \\]


<!---
Following up on the forum conversation about the stability:<br>
It was mentioned that "Displacement itself is a factor contributing to stability

\( M_R(heeling) = Displacement \cdot GZ(heeling) \)" <br>

In our example when the displacement increases from the BM formula we see that BM decreases.
As a result GM decreases (after a minor investigation because of small change of center of buoyancy).

It seems that a heavier vessel we can be more tender according to the osculation formula. 
-->


<p class="question">
    <strong>b)</strong> Look up on the internet the yacht “Camper and Nicholson 45” (see, for instance, Sailboatdata,
    <a href="https://sailboatdata.com/" target="_blank" rel="noopener">https://sailboatdata.com/</a>). Have a look at
    the plans. What could you say with respect to her keel and rudder, regarding maneuverability?
</p>
It is semi-full keel sailing yacht with separated rudder. It has a good balance between course stability and maneuberability.
 




<p class="question">
    <strong>c)</strong> Look up on the internet the yachts “Baba 30” and “Cigale 16”. Using the available data (see, for
    instance, (<a href="https://sailboatdata.com/sailboat/baba-30" target="_blank" rel="noopener"
        >https://sailboatdata.com/sailboat/baba-30</a
    >,
    <a href="http://www.finot.com/bateaux/batproduction/alubat/cigale16/cigal16_angl.htm" target="_blank" rel="noopener"
        >http://www.finot.com/bateaux/batproduction/alubat/cigale16/cigal16_angl.htm</a
    >), compare them in terms of velocity, stability, maneuverability, and movements (rolling and pitching).
</p>

|Aspect          | Baba 30                                                        | Cigale 16 |
| -------        | -----                                                          | -------   |
|velocity        |    heavy, smaller LWL, smaller SA/Displ, big wetted area       |    ✓        |
|stability       |    weight                                                      | form          |
|maneuverability |    directional stability                                       | good maneuberability      |
|movements       |    tender                                                      | stiff        |




<p class="question">
    <strong>d)</strong> Eric Tabarly was an important sailor who introduced many of the innovations that are nowadays
    familiar for us in sailing yachts. He also pushed in improving the performance of racing boats. Look up on the
    internet the yacht “Pen Duick V”. What is the innovation that he introduced regarding stability? Explain it in a few
    words.
</p>
Pen Duick V could take on 500 liters of ballast seawater into side tanks.
This way it could increase effectively the righting moment when needed.


<p class="question">
    <strong>e)</strong> Regarding the ability to sail close-hauled there is an angle that is key in the side force
    generation. Which one is it? Explain why in a few sentences.
</p>
The leeway angle is the key in the side force generation.
As a result of the leeway we have an angle of attack to the keel. Thus the keel produces a hydrodynamic lift.
Hull also produces hydrodynamic lift. A certain heel increases the hydrodynamic lift of the hull.

<div class='note'>
Note:<br>

In the end of the "ability to sail close-hauled" section you mention the effect of the rudder in sailing close hauled. Based on what we have been taught when the boat has tendency to turn into wind the rudder can add hydrodynamic lift which helps counteracting leeway. In the notes you state the opposite.
<br>
<br>
For your reference I add the paragraph I am talking about:
<br>
There is another aspect to analyse regarding the ability to sail close-hauled. Sailing boats can be
divided into two groups: burning yachts and soft yachts. The first category contains those exhibiting
a natural tendency to lu↵, that is, to move closer to the wind if you release the rudder while sailing.
Moreover, soft boats are those that tend to turn against the wind when leaving the rudder free. The first
characteristic is considered better, as it is more secure. Imagine that you su↵er an accident on board, if
the yacht turns towards the wind after losing control over the rudder, the power in the sails will reduce,
reducing thus both the speed and the heeling angle. On the other hand, if the yacht turns against the
wind, the sail will gain some angle, increasing its power, velocity and heeling angle. This situation
may cause difficulties, and it is considered unsafer for obvious reasons.
Therefore, a burning yacht is preferable. This implies that the rudder must be acting continuously
when sailing close-hauled in order to take the yacht out of the wind direction, maintaining a close-
hauled course. In this situation, the rudder generates lift that adds up to the lateral force of the sails,
forcing to increase the lift generated by the keel and rudder. In any case, as always in the field of the
science of navigation, a very burning yacht is not a good solution. If the boat has an extreme tendency
to lu↵, the required action of the rudder will increase the hydrodynamic drag, leading to a reduction in
the velocity. By contrast, if the boat is soft, the rudder will be generating a lift force that helps the keel
to counteract the sway by the sails, but we would never be able to get rid of the possible loss of control
of the yacht.
</div>


<p class="question">
    <strong>f)</strong> With the parameters from the hull that has been designed, obtain the residuary resistance
    according to the expression given in the course.
</p>


The expression given in the course is Delft Series III.

With the designed hull data we obtain the following data. The residuary resistance is the fourth column.

Speed kn | Froude No LWL | Froud No Vol | Delft III resist. kN | Delft III power kW |
---- | ---- | ---- | ---- | ----|
0 | 0 | 0 | -- | --|
0.5 | 0.02 | 0.046 | -- | --|
1 | 0.041 | 0.092 | -- | --|
1.5 | 0.061 | 0.138 | 0 | 0.006|
2 | 0.081 | 0.184 | 0.1 | 0.082|
2.5 | 0.102 | 0.23 | 0.2 | 0.208|
3 | 0.122 | 0.277 | 0.3 | 0.392|
3.5 | 0.142 | 0.323 | 0.4 | 0.655|
4 | 0.162 | 0.369 | 0.5 | 1.023|
4.5 | 0.183 | 0.415 | 0.7 | 1.508|
5 | 0.203 | 0.461 | 0.8 | 2.128|
5.5 | 0.223 | 0.507 | 1.1 | 2.974|
6 | 0.244 | 0.553 | 1.3 | 4.086|
6.5 | 0.264 | 0.599 | 1.6 | 5.509|
7 | 0.284 | 0.645 | 2 | 7.294|
7.5 | 0.305 | 0.691 | 2.5 | 9.488|
8 | 0.325 | 0.737 | 3 | 12.142|
8.5 | 0.345 | 0.784 | 3.7 | 16.215|
9 | 0.366 | 0.83 | 4.9 | 22.745|
9.5 | 0.386 | 0.876 | 6.8 | 33.193|
10 | 0.406 | 0.922 | 9.4 | 48.605|
10.5 | 0.426 | 0.968 | 12.9 | 69.505|
11 | 0.447 | 1.014 | 17 | 96.194|
11.5 | 0.467 | 1.06 | 20.1 | 118.647|
12 | 0.487 | 1.106 | 23.5 | 145.102|
12.5 | 0.508 | 1.152 | 27 | 173.683|
13 | 0.528 | 1.198 | 29.9 | 200.153|
13.5 | 0.548 | 1.244 | 32.6 | 226.087|
14 | 0.569 | 1.291 | 34.7 | 249.774|
14.5 | 0.589 | 1.337 | 36.7 | 273.437|
15 | 0.609 | 1.383 | 38.1 | 293.672|
15.5 | 0.63 | 1.429 | 38.9 | 310.43|
16 | 0.65 | 1.475 | 40.2 | 330.668|
16.5 | 0.67 | 1.521 | 41.8 | 354.419|
17 | 0.69 | 1.567 | 43.3 | 378.769|
17.5 | 0.711 | 1.613 | 44.3 | 398.39|
18 | 0.731 | 1.659 | 45.3 | 419.318|
18.5 | 0.751 | 1.705 | -- | --|
19 | 0.772 | 1.751 | -- | --|
19.5 | 0.792 | 1.798 | -- | --|
20 | 0.812 | 1.844 | -- | --|



<p class="question">
    <strong>g)</strong> Regarding keel design, mention at least three possible alternatives to lower the center of
    gravity of the ballast (two of them have been explicitly mentioned in the course). Explain the pros and cons of each
    of them.
</p>
1. Add a bulb in the bottom of the keel.
 - Pros: Reduces the induced resistance via plate effect. 
 - Cons: Increases the wetted surface.
2. Increase the draft.
 - Pros: Reduces the induced resistance.
 - Cons: Increases the draft of the yacht. Increases the wetted surface.
3. Increase the tapper ratio.
 - Pros: Increases the value of the added moment of inertia which reduces the rolling movements.
 - Cons: Increases induced resistance. Increases the wetted surface.
4. Maintain the thickness of the keel from root to tip.
 - Pros: Small increase to the wetted surface.
 - Cons: Makes the hydrodynamic profile less effective.
5. Thicken the lower part of the keel.
 - Pros: Small increase to the wetted surface.
 - Cons: Makes the hydrodynamic profile less effective.
6. Maintain taper ratio and draft. Reduce aspect ratio.
 - Pros: Increasing the value of the added moment of inertia which reduces the rolling movements.
 - Cons: Increases the wetted surface.



<p class="question">
    <strong>h)</strong> Have a look at the notes about VPP and force balance. Given that the total aerodynamic forces in
    the O<sub>x</sub> and O<sub>y</sub> axes are A<sub>x</sub> = 573.1 N and A<sub>y</sub> = 2,541.8 N respectively, and
    that the horizontal projection of the aerodynamic lift and drag are, respectively, L<sup>̴</sup><sub>A</sub> = 2,500
    N and D<sub>A</sub> = 300 N, obtain the apparent wind angle.
<br>
    Given that the leeway angle is γ = 10◦ and that the aerodynamic lift itself is LA = 2,537.4 N (Note that this is the
    total lift force, not the horizontal projection, which value is different and given above), what is the value of the
    heeling angle θ? Provide the value of the heeling angle in degrees.
</p>

Following Pythagorean theorem:

\\[ {A_x}^2 + {A_y}^2 = {\tilde{L}_A}^2 + {D_A}^2 \\]
or 
\\[ {573.1}^2 + {2,541.8}^2 = {2500}^2 + {300}^2 \\]
Ohh no. The last is not equal.

I progress with the exercise ignoring the contradiction above.

![name of the image]({{site.baseurl}}/images/sail-forces.png)


We make a coordinates transformation:

\\[ A_x = \tilde{L}_A \cdot sin(β)  - D_A \cdot cos(β) \\]
\\[ A_y = \tilde{L}_A \cdot cos(β) + D_A \cdot sin(β) \\]

Substituting with the given values:

\\[ 573.1 = 2,500 \cdot sin(β)  - 300 \cdot cos(β) \\]
\\[ 2,541.8 = 2,500 \cdot cos(β) + 300 \cdot sin(β) \\]

or

\\[ 7315.723 =  21125 \cdot sin(β) \\]
\\[ 2,541.8 = 2,500 \cdot cos(β) + 300 \cdot sin(β) \\]

or

\\[ sin(β) = 0.3463064142011834 \\]
\\[ 2,541.8 = 2,500 \cdot cos(β) + 300 \cdot sin(β) \\]

or

\\[ β = 0.3536310131408761 \\]
\\[ 2,541.8 = 2,500 \cdot 0.9381214566798471 + 300 \cdot  0.3463064142011834  \\]

or

\\[ β = 0.3536310131408761 \\]
\\[ 2,541.8 = 2,449.195565959973 \\]

Converting to degrees:
\\[ β = 20.26^o \\]

> Apparent wind angle with respect to X axis is \\( β = 20.26^o \\)
> 
> Apparent wind angle with respect to X' axis is \\( β-γ = 10.26^o \\)

Let's calculate the heeling angle \\(θ\\).

We start by calculating the heeling angle on the plane which is perpendicular to the apparent wind direction.
\\[  L_A \cdot cos(θ^Α) = \tilde{L}_A   \\]
or

\\[ cos(θ^Α) = \frac{ \tilde{L}_A }{ L_A }   \\]
or

\\[ θ^Α = cos^{-1}(\frac{ \tilde{L}_A }{ L_A } )  \\]
or
\\[ θ^Α = cos^{-1}(\frac{ 2,500 }{ 2,537.4 } )  \\]
or
\\[ θ^Α = cos^{-1}(0.98526 )  \\]
or
\\[ θ^Α = 9.849^o  \\]

We take the projection of the boat heeling to the plane which is perpendicular to the apparent wind.

\\[ θ^Α = θ \cdot cos(β-γ)   \\]

or
\\[ 9.849^o = θ \cdot  cos(20.26^o-10^o)   \\]

or
\\[ 9.849^o = θ \cdot  cos(10.26^o)   \\]

> Thus the heeling angle is:
> \\[ θ = 10.01^o   \\]

**Thank you for the nice journey in the wonderful world of sailing yacht design!!**
