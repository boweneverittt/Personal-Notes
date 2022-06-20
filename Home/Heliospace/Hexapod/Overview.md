# Hexapod

### Kinematics
Euler Angles (XYZ convention)

![[Pasted image 20220613153142.png]]

L = linear actuator vector
L magnitude = LA command
![[Pasted image 20220613153120.png]]
Transformations
![[Pasted image 20220613153100.png]]

### Matlab Model:
High Level:
![[Pasted image 20220614151436.png]]

Trajectory Planning:
![[Pasted image 20220614151806.png]]
Red is linear, translational movement
Blue is rotational movement
Outputting desired position and velocity from the linear and rotational components

Simple integration block (dot product, offset add)
![[Pasted image 20220614151956.png]]

Hexapod High Level Controller Block:
![[Pasted image 20220614152054.png]]

Inverse Kinematic Module:
![[Pasted image 20220614152128.png]]



### Hardware
![[Pasted image 20220616151235.png]]
![[Pasted image 20220615104311.png]]
Bracket Strut Assembly
*Shank bolt

### Electronics
[Actuator Sheet: ](https://docs.google.com/spreadsheets/d/1LS9uEVO5EtuQBhVg0dPXJ_UPG0Uo-g5likpxzpcqrxs/edit?usp=sharing)
![[Pasted image 20220616113659.png]]
Using Hall Effect Sensor ([Firgelli Video](https://www.youtube.com/watch?v=nBexm2UM84k&ab_channel=FIRGELLIAutomations))

### Resources
- https://www.youtube.com/watch?v=veMNrmTGlnE&ab_channel=Robotogie
- https://core.ac.uk/download/pdf/322824733.pdf
- https://www.osti.gov/servlets/purl/751001
- https://www.mecademic.com/en/how-is-orientation-in-space-represented-with-euler-angles#:~:text=In%20the%20case%20of%20the,will%20define%20the%20same%20orientation
- https://www.ccs.neu.edu/home/rplatt/cs5335_fall2016/slides/euler_quaternions.pdf


![[Pasted image 20220617132153.png]]
0.1 skew

![[Pasted image 20220617132254.png]]
-0.16 skew