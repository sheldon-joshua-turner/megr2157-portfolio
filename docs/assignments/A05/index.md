# A5 – [Topic]

## Objective
The objectives of this assignment are:
- Conduct stress analysis to determine appropriate dimensions for structural features.
- Generate free body diagrams (FBDs) to visualize forces and constraints for each feature.\
- Identify and document known and unknown variables, assumptions, and algebraic models for stress calculations.
- Perform stiffness analysis to establish minimum required dimensions based on deflection constraints.
- Compare stress and stiffness analyses to ensure structural integrity and compliance with given constraints.
- Create detailed multiview sketches illustrating dimensions derived from both stress and stiffness analyses.
- Reflect on and document key engineering lessons learned throughout the process.
## Analyze
# Initial Design
For this Assignment, I was tasked with creating a mounting bracket for this piece. 
First, I reviewed the basic guidelines for the assignment and determined some of the initial values. 
My chosen force is 650lbf, so my p value would be325lbf (since p = l/2).I also chose a safety factor of 3.5, which  I used to calculate the allowed stress. 
I also took necessary assumptions into account, such as ignoring any direct shear stress considerations. 

For this assignment I am choosing to use Grade 5 Titanium
E(Elastic Modulus) = 65000 Ksi
σy(Yield Strength) = 160 ksi / 3.5 gives the allowablle stress (σ_allowble) of 45 ksi.

https://github.com/sheldon-joshua-turner/megr2157-portfolio/blob/3a0dc7e56f4311b46bb4e9ce5f349696f76b012f/docs/assignments/A05/Screenshot%202026-09-24%20081212.png

#Feature A
Initial Information:

I started by listing my knowns and unknowns to organize my calculations. 
A-Stress & Stiffness Analysis

After gathering all of my information I calculated a stress and stiffness analysis on feature A using provided equations. 
A-Conclusion

After solving both algebraically and numerically, I found that the stress value was larger than the stiffness value so we could go with that one. 1.20in would be my nominal dimension for this diameter. 

docs/assignments/A05/Screenshot 2026-09-24 081145.png

#Feature B
Initial Information:

I started by listing my knowns and unknowns to organize my calculations, and repeated the same process for Feature B. 
A-Stress & Stiffness Analysis

After gathering all of my information I calculated a stress and stiffness analysis on feature B using provided equations. 
A-Conclusion

After solving both algebraically and numerically, I found that the stress value was larger than the stiffness value so we could go with that one. 0.005in would be my nominal dimension for this length.
docs/assignments/A05/Screenshot 2026-09-24 081150.png

#Feature C
Initial Information:

I started by listing my knowns and unknowns to organize my calculations, and repeated the same process for Feature B. 
A-Stress & Stiffness Analysis

After gathering all of my information I calculated a stress and stiffness analysis on feature B using provided equations. 
A-Conclusion

After solving both algebraically and numerically, I found that the stress value was larger than the stiffness value so we could go with that one. 0.005in would be my nominal dimension for this length.
docs/assignments/A05/Screenshot 2026-09-24 081155.png
#Feature D
Initial Information:

I started by listing my knowns and unknowns to organize my calculations, and repeated the same process for Feature B. 
A-Stress & Stiffness Analysis

After gathering all of my information I calculated a stress and stiffness analysis on feature B using provided equations. 
A-Conclusion

After solving both algebraically and numerically, I found that the stress value was larger than the stiffness value so we could go with that one. 0.005in would be my nominal dimension for this length.
docs/assignments/A05/Screenshot 2026-09-24 081200.png
#Feature E
Initial Information:

I started by listing my knowns and unknowns to organize my calculations, and repeated the same process for Feature B. 
A-Stress & Stiffness Analysis

After gathering all of my information I calculated a stress and stiffness analysis on feature B using provided equations. 
A-Conclusion
docs/assignments/A05/Screenshot 2026-09-24 081204.png
After solving both algebraically and numerically, I found that the stress value was larger than the stiffness value so we could go with that one. 0.005in would be my nominal dimension for this length.

## Conclusion

Lessons Learned

For this assignment I learned how to apply solid mechanics knowledge to analyze the stress and stiffness of a metal fixture.
Governing Failure Mode:
For every single feature, stress governed the dimensions. Shear was ignored. 
Error propagation:

The forces became loading forces for all of the other features, they just built on one another. 
Assumption Sensitivity:

For the material assumption, one important consideration is the surrounding environment conditions. For the sake of this assignment they were left out to keep it simple. 
Metals are more conductive to heat, so considering things like thermal expansion or live loads caused by external weather. 



