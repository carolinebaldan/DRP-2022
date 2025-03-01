# Applications of Elliptic Curves to Fermat's Last Theorem
**Directed Reading Program 2022, by Elise Alvarez-Salazar, Caroline Baldan, and Kelly Stump**  
**Mentored by Marcos Reyes**

For our project, we studied methods of finding rational solutions on elliptic curves. We then used the rich group structure observed over the curve to show a special case of Fermat's Last Theorem, proving that there are no non-trivial solutions to a<sup>4</sup>+b<sup>4</sup>=c<sup>4</sup>.

You can view our poster [here](https://github.com/carolinebaldan/UCSB-DRP-2022/files/8788098/DRP_2022.pdf).
### Algorithm
Click [here](https://replit.com/@MarcosReyes6/Elliptic-Curve-Fun?outputonly=1&lite=true#main.py) to input your own non-singular elliptic curve. Our algorithm will compute the set of torsion points and tell you the group structure of the torsion set for the elliptic curve you submitted.

This algorithm relys primarily on the Nagell-Lutz Theorem, as well as Mazur's Theorem and the operation defined to create the abelian group.
### Additional Images
<p align="center">
    <img width="500" alt="Graph of 2P" src="https://user-images.githubusercontent.com/103796027/170742774-a62eb7e0-3b77-46a7-8933-f14622d43ad1.png">
  </p>
This image shows the operation defined on our poster when used to add a point to itself, rather than adding two points together. All the steps of the operation remain the same, however the tangent line at the point P is used, instead of the secant line intersecting the points P and Q.

<p align="center">
  <img width="500" alt="Graph of FLT Special Case" src="https://user-images.githubusercontent.com/103796027/170742986-0a2b3e94-fd7e-410d-a21d-a0d0bd72701a.png">
  </p>
This image displays the graph of a<sup>4</sup>+b<sup>4</sup>=c<sup>4</sup>, the elliptic curve used in Fermat's Last Theorem for n=4. The equation that you see in the top right corner of the graph is that same curve in Weierstrass form. To see how the group structure of this curve can be used to show that it has no non-trivial solutions, see our poster (linked above).


### References

Á. Lozano-Robledo, Elliptic Curves, Modular Forms and their L-functions, American Mathematical Soc., 2011  
J. Silverman, J. Tate, Rational Points on Elliptic Curves, Springer-Verlag, New York, 2015  
All images generated by Geogebra
