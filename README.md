# Self-Balancing-Robot
To make a robot which can balance itself on two wheels. There will be only one axle connecting the two wheels and a platform will be mounted on that. There will be another platform above it. The platform will not remain stable itself. Our job will be to balance the platform and to maintain it horizontal. At first, we have decided to just balance the robot on its two wheels. If the platform inclines, then microcontroller (in this case it’s Arduino) will send signals to motors such that motors would move forward or backward depending on the inclination direction and extent. So, if the platform tilts forward then motors will run forward and vice versa to keep the platform horizontal.
For this first we make a simulation on MATLAB using Simulink, and when the simulation is ready the we move to code the Arduino in order to perform job according to this. Technique used in making the selfbalancing robot is same as the principle used in balancing of the Inverted Pendulum. Balancing of the inverted pendulum is a classic problem in dynamics and control theory and is widely used as a benchmark for testing control algorithms (PID controllers, neural networks, fuzzy control, genetic algorithms, etc.).
Variations on this problem include multiple links, allowing the motion of the cart to be commanded while maintaining the pendulum, and balancing the cart-pendulum system on a see-saw. The inverted pendulum is related to rocket or missile guidance, where the centre of gravity is located behind the centre of drag causing aerodynamic instability. The understanding of a similar problem can be shown by simple robotics in the form of a balancing cart. Balancing an upturned broomstick on the end of one's finger is a simple demonstration, and the problem is solved in the technology of the Segway PT, a selfbalancing transportation device. Making a self-balancing robot is essentially solving the classic inverted pendulum problem. The goal of the control loop is to adjust the wheels’ position so that the inclination angle remains stable at a pre-determined value (e.g., the angle when the robot is balanced).![image](https://user-images.githubusercontent.com/84041595/172048234-3b2ef0b4-793d-4c74-8120-4ab540b590a2.png)
