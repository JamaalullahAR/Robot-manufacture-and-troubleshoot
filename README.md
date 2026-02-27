# Robot prototype manufacture and troubleshoot

## 📌 Overview
This was a group project which simulated a warman competition. We worked in groups of 4 and had to complete tasks set out by the lecturers and the tutors. We had to design, build and troubleshoot the robot prototype on our own. 

## 🎯 Objectives
- Make a working robot
- Robot prototype has to pick up and contain 2 balls at different heights
- Robot prototype must drop balls into a hole


## 🛠 Tools & Concepts Used
- Inventor
- Arduino
- Soldering
- Laer cutting
- wiring and Electronics knowledge
- Detailed designing

## 🔍 Methodology
Our individual tasks were to come up with multiple design concepts with in depth notes and details on how they could be manufactured using 3D modelling software. Our group decided to implement 2 different ideas to make one working robot prototype. Our first prototype idea was to have a robot with one arm to pick up the 2 balls. The robot would then drop the balls into a cavity to hold the balls within the body. It would hold the balls until it reached the hole and then drop it off with a backdoor mechanism and get us the full points. 
<br>

In our teams, we split the workload. For the first protorype, my roles were : <br>
- 3D modelling assistance
- Laser cutting
- Manufacturing
<br>

The second prototype idea changed where instead of the robot holding the balls within the body, it would just be held by the arm. Once it reached the hole, the robots arm would lift over the body and release the ball down the robots back (see figure 13). The ball would roll down the robot and into the hole. This concept also meant that the robot could only work with one ball at a time, and would require more electronic components for precision. 
<br>

For the second prototype, my roles were : 
- Soldering
- Wiring and organisation of wires
- troubleshooting
<br>

My role changed as we realised where our groups strengths were after the first prototype.

## 📊 Results

### Prototype 1
Prototype 1 did not go well. We overestimated the capabilities of the design, materials we used and the electronic components. The prototype failed both the objectives and our graded rubrics. The main reasons prototype 1 failed were : <br>
- Improper design of components
- Messy wiring techniques
- Weak solder joints
- Insufficient planning of potential issues

The key components which failed were the wheels, the arm, and the back door. The wheels did not have enough traction to move forward, due to their large size and the inability for O-rings to be attached. The wheels were designed to be large in order for the back door to function. With smaller wheels, the mechanism for the back door raised the prototype off the ground due to insufficient clearance. The arm could not be raised with the initial plan of one servo while holding a ball. Although the claw mechanism could open and close well, the claw was too large and the ball fell through.  Considering that none of our group members had worked with electronics components, this was a huge learning curve and a turning point in the designing of the second prototype. 

### Prototype 2
Our team also had an imbalance in work load split in the first prototype due to different strengths and weaknesses. Before starting the second prototype, we discussed and adjusted our job roles to ensure a better delegation of tasks. With these new changes, the protoype worked, but not perfectly. The main reasons prototype 2 failed were: <br>

- broken components
- battery drainage
- time constraints

The second prototype worked in the end. But it did not get the full points. The design and manufacturing imrpovements of the second prototype were:<br> 
- Omni wheels for better maneuverability
- Prototype body to DC motors in a stable manner
- Wider bottom panel to house all electronic components comfortably
- Removed backdoor so ball gets held in claw and passively rolls down robot back
- Redesign of claw to grip ball efficiently
- Better understanding of DC motors, Servos, voltage regulators, so we know how to use them for better results
- Shorter arm length for less bending forces acting on the servo
- 2 servos used to lift arm up with ball
- New and improved attachments on electronic components onto bottom board.
- Better accessibility, labelling and organisation of wires
- Batery pack easily removable and switch implemented.
- SONAR included for accurate stoppage of prototype to a certain distance

These updated designs and manufacturing differences immensely helped with the build quality and the trouble shooting of the protoype. With the implementation of new panel designs, assembling and troubleshooting the prototype improved. However, some components still failed closer to the deadline and had to be changed , which resulted in less time for testing. Furthermore, on the day of our grading, we realised that the arm could not hold the ball in a static position. This meant that our core idea of the prototype's function was a failure as the prototype had to hold the ball up until it reached the hole. However, our team mate in charge of the algorithim wrote up a run to get one of the balls into the hole. During grading, the prototype managed to get a ball into the hole, which got our team a good score.

## 📸 Project Images
### Prototype 1
#### Laser Cutting process
This image shows the process of laser cutting of the panels of the first prototype. The process of laser cutting was the same for the 2 protypes, just with different design changes between iterations.<br>

<p align="center">
  <img src="images/laserCutting.PNG" width="400">
</p>

<p align="center">
  <em>Figure 1: Prototype 1 laser cutting process</em>
</p>

#### Claw mechanism
The claw mechanism which worked, but could not pick up the ball.<br>

<p align="center">
  <img src="images/robot1_claw.PNG" width="400">
</p>

<p align="center">
  <i>Figure 2: First iteration of claw concept</i>
</p>
<!-- -->

#### Initial body assembly
The initial skeleton and body of the robot, without wheels.<br>


<p align="center">
  <img src="images/robot1_prototype.jpeg" width="400">
</p>

<p align="center">
  <i>Figure 3: Body assembled without wheels</i>
</p>
<!-- -->

#### Backdoor 
Backdoor design to hold the balls up. Servo would activate the door to move downwards and release the balls into the hole.<br>

<p align="center">
  <img src="images/robot1_backdoor.jpeg" width="400">
</p>

<p align="center">
  <i>Figure 4: Backdoor mechanism</i>
</p>
<!-- -->

#### Electronics
![]()

<p align="center">
  <img src="images/robot1_electronics.jpeg" width="400">
</p>

<p align="center">
  <i>Figure 5: Main electronic comoponent of first prototype</i>
</p>
<!-- -->

#### Prototype 1 complete
![]()

<p align="center">
  <img src="images/robot1_complete.jpeg" width="400">
</p>

<p align="center">
  <i>Figure 5: Completed prototype 1 </i>
</p>
<!-- -->

### Prototype 2
#### Adding SONAR
![]()

<p align="center">
  <img src="images/robot2_addingSONAR.jpeg" width="400">
</p>

<p align="center">
  <i>Figure 6: Location of SONAR on prototype 2</i>
</p>
<!-- -->

#### Omni wheels
![]()
<p align="center">
  <img src="images/robot2_wheels_test.jpeg" width="400">
</p>

<p align="center">
  <i>Figure 7: Implementation and orientation check of omni wheels</i>
</p>
<!-- -->

#### Soldering and troubleshooting
![]()
![]()

<p align="center">
  <img src="images/robot2_soldering.jpeg" width="400">
</p>

<p align="center">
  <i>Figure 8: Team mate soldering component onto prototype</i>
</p>
<!-- -->

<p align="center">
  <img src="images/robot2_troubleshoot.jpeg" width="400">
</p>

<p align="center">
  <i>Figure 9: Team mate and I troubleshooting the prototype</i>
</p>
<!-- -->


#### Electronics
![]()
![]()

<p align="center">
  <img src="images/robot2_electonicsSetup.jpeg" width="400">
</p>

<p align="center">
  <i>Figure 10: Layout of electronics</i>
</p>
<!-- -->

<p align="center">
  <img src="images/robot2_electronics.JPG" width="400">
</p>

<p align="center">
  <i>Figure 11: Completed electronics setup for prototype </i>
</p>
<!-- -->



#### Arm and slope cover
![]()
![]()

<p align="center">
  <img src="images/robot2_arm.PNG" width="400">
</p>

<p align="center">
  <i>Figure 12: Arm raised up</i>
</p>
<!-- -->

<p align="center">
  <img src="images/robot2_coverOn.jpeg" width="400">
</p>

<p align="center">
  <i>Figure 13: Slope and cover for ball to roll down while protecting wires</i>
</p>
<!-- -->

#### Robot route
![]()

<p align="center">
  <img src="images/robot_route.png" width="400">
</p>

<p align="center">
  <i>Figure 14: Planned route for the prototype to perform the task and get full points</i>
</p>
<!-- -->


#### Completed robot
![]()


<p align="center">
  <img src="images/TeamPhoto.jpeg" width="400">
</p>

<p align="center">
  <i>Figure 15: Team photo with completed prototype</i>
</p>
<!-- -->

## 📚 What I Learned
- Communication with team and understanding our strengths and weaknesses early on is extremely important
- Working with electronic components and how soldering and wiring must be robust for optimal performance
- Designing for manufacturing requires time and planning ahead
- Simple but functional designs reduces challenges in manufacturing and troubleshooting
- Improved my report writing and learnt different ways to convey ideas through team mates
