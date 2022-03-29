Reference Frames:
https://ocw.mit.edu/courses/mechanical-engineering/2-017j-design-of-electromechanical-robotic-systems-fall-2009/course-text/MIT2_017JF09_ch09.pdf
https://www.youtube.com/watch?v=WzLJDjfm2Xo&ab_channel=RossDynamicsLab
*STAR* https://cglearn.codelight.eu/pub/computer-graphics/frames-of-reference-and-projection
https://marctenbosch.com/quaternions/

2d Rigid Body Kinematics:
Problem setup
![clipboard.png](inkdrop://file:dvCnQuYsj)
ex: pid runs in the global frame and the control outputs are put through the unroller code:
```cpp
float cosRoll = cos(-roll);
float sinRoll = sin(-roll);

yServoAngle = yPIDAngle * cosRoll - zPIDAngle * sinRoll;
zServoAngle = yPIDAngle * sinRoll + zPIDAngle * cosRoll;

```
