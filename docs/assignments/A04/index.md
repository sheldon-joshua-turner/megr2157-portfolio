# A4 – [Topic]

## Objective
For this assignment, I was tasked with designing a mount to support a motor. Design specifications for the motor itself were provided in the assignment's instructions, and will influence the final dimensions for the motor heavily. 
The deliverables for this assignments are:
	- Feature 1: Design a feature of the mount that is attached to the motor, assuming the deflection of the feature attached to the wall is zero and the derivative with respect to x is also zero. 
	- Feature 2: Design a feature of the mount to be attached to the wall assuming the rigid wall A can support bolts. 
    - Sketch the motor mount design as an isometric view.
    - Generate a 3D CAD model of the motor mount.
    - Design features on the motor mount to minimize deflection.
	- Create clearance holes for the shaft and bolts (3.4 mm clearance holes for bolts).
## Initial Setup/Considerations
I used the dimensions and picture of this motor as a reference to adjust my dimensions when needed. 
https://www.omc-stepperonline.com/brushed-24v-dc-gear-motor-3-6kg-cm-46rpm-w-99-5-1-planetary-gearbox-pa28-28245800-g100 
1.png

![Motor Picture](https://github.com/sheldon-joshua-turner/megr2157-portfolio/blob/dad1d754d9327bb818809526782bdb6dc15bdfb7/docs/assignments/A04/PA28-28245800-G100-500x500.jpg)

Initially, before I started the assignment, I took the time to decide which material would be the most applicable to the mount's usecase. I ended up choosing ABS because it has a high rigidity, high strain resistance, and can remain stable for long periods of time. Next, I used the linked websites to find
the Young's Modulus and yield strength of ABS to begin calculations. 

![Motor Picture](https://github.com/sheldon-joshua-turner/megr2157-portfolio/blob/dad1d754d9327bb818809526782bdb6dc15bdfb7/docs/assignments/A04/1.png)
![Motor Picture](https://github.com/sheldon-joshua-turner/megr2157-portfolio/blob/dad1d754d9327bb818809526782bdb6dc15bdfb7/docs/assignments/A04/2.png)


## FEATURE 1
- For feature one, I started by drawing out a free body diagram of the entire system so I would be able to understand how the stress placed on the mount by the motor would affect it. Once I established what forces and moments were present in the system, I defined my known and unknown 
variables. From there I sketched an FBD of feature 1, and solved for the moment based on the derivations provided to us in class. Lastly, I evaluated the beam by comparing the bases's strength (deformation under stress) to its stiffness (elongation under deflection); Whichever produced the larger deformation (in mm)
would be an appropriate minimum to design around. 

Listed knowns & unknowns:

![Motor Picture](https://github.com/sheldon-joshua-turner/megr2157-portfolio/blob/dad1d754d9327bb818809526782bdb6dc15bdfb7/docs/assignments/A04/3.png)


For the first feature, the strength value I calculated was larger, so I selected it as the final value for the base: 2.051 mm.

![Motor Picture](https://github.com/sheldon-joshua-turner/megr2157-portfolio/blob/dad1d754d9327bb818809526782bdb6dc15bdfb7/docs/assignments/A04/4.png)


## FEATURE 2
I then repeated the same process for feature 2: listed knowns and unknowns, Next, I drew my FBD.
 I noted that the bottom end was free to bend. I also decided to place a 3mm offset for each hole from the bottom and side walls to position in a way that would make the design easy to edit later if changes needed to be made.


 When solving the moment, I disregarded the diameters of the holes. From there, I solved for strength and stiffness, assuming that max normal stress remains the same. 
 
 
 
 Once I solved for both strength and stiffness,  I compared my values and found that my strength value was larger than my stiffness value. So, my final B2 value is 1.763mm. 
 
 
 
 
 ![Motor Picture](https://github.com/sheldon-joshua-turner/megr2157-portfolio/blob/dad1d754d9327bb818809526782bdb6dc15bdfb7/docs/assignments/A04/5.png)
 
 
 
 I completed a sketch to describe the design's dimensions. 
 
  ![Motor Picture](https://github.com/sheldon-joshua-turner/megr2157-portfolio/blob/dad1d754d9327bb818809526782bdb6dc15bdfb7/docs/assignments/A04/5b.png)
 
 ## SOLIDWORKS
 I began by defining each of my calculated and pre-determined values as equations prior to the parametric modeling process. 
![Motor Picture](https://github.com/sheldon-joshua-turner/megr2157-portfolio/blob/dad1d754d9327bb818809526782bdb6dc15bdfb7/docs/assignments/A04/eqs.png)
 

First, I designed Feature 2, and added constraints as necessary. 

![Motor Picture](https://github.com/sheldon-joshua-turner/megr2157-portfolio/blob/dad1d754d9327bb818809526782bdb6dc15bdfb7/docs/assignments/A04/6.png)

Next, I extruded, ensuring my sketch definitions portrayed the holes properly. 

![Motor Picture](https://github.com/sheldon-joshua-turner/megr2157-portfolio/blob/dad1d754d9327bb818809526782bdb6dc15bdfb7/docs/assignments/A04/7.png)


[Extruded Part 1]

Next, I did the same for Feature 1. 

![Motor Picture](https://github.com/sheldon-joshua-turner/megr2157-portfolio/blob/dad1d754d9327bb818809526782bdb6dc15bdfb7/docs/assignments/A04/8.png)

I added the hole, the countersink, and the hole that travels through the part. 

![Motor Picture](https://github.com/sheldon-joshua-turner/megr2157-portfolio/blob/dad1d754d9327bb818809526782bdb6dc15bdfb7/docs/assignments/A04/9.png)
![Motor Picture](https://github.com/sheldon-joshua-turner/megr2157-portfolio/blob/dad1d754d9327bb818809526782bdb6dc15bdfb7/docs/assignments/A04/10.png)

Final View of Part:

![Motor Picture](https://github.com/sheldon-joshua-turner/megr2157-portfolio/blob/dad1d754d9327bb818809526782bdb6dc15bdfb7/docs/assignments/A04/11.png)

##2157 Students Only: Drawing of Part

![Motor Picture](https://github.com/sheldon-joshua-turner/megr2157-portfolio/blob/dad1d754d9327bb818809526782bdb6dc15bdfb7/docs/assignments/A04//12.png)

## Reflection and Lessons Learned

For this assignment, I learned how to take scale and proportion into account when designing dimensions. I had to adjust dimensions multiple times during the first section of this assignment, which
added a decent amount to the time I spent on the assignment overall. I also got to put solid mechanics principles into practice, which helped me understand strength and stiffness of materials and how they relate to the implementation and analysis of a design.
Overall the assignment took me 5 hours. 


