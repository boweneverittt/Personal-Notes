Resources:
https://quaternions.online/
https://en.wikipedia.org/wiki/Conversion_between_quaternions_and_Euler_angles
https://stanford.edu/class/ee267/lectures/lecture10.pdf
Reference Frames:
https://ocw.mit.edu/courses/mechanical-engineering/2-017j-design-of-electromechanical-robotic-systems-fall-2009/course-text/MIT2_017JF09_ch09.pdf
https://www.youtube.com/watch?v=WzLJDjfm2Xo&ab_channel=RossDynamicsLab

Formula:
a + bi + cj + dk* * *

Unit Quat:
Uq = q/||q||

Quick Notes:
axis angle representation of the gyros is the first order derivative of the orientation
quaternion is describing some rotation between where you're orientated, and where you where when you began (for orientation using gyros only) or from     North East South West and up and down (if doing absolute orientation with mags and accs)
axis angle representation is just a quaternion that represents the rotation that your gyros are measuring
all unit quaternions are are axis angle with the axis being normalized
![clipboard.png](inkdrop://file:7ecrDT4im)
euler angles is rotation in deg around x y z
axis angle is rotation w around vector x y z
