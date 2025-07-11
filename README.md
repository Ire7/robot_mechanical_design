# robot_mechanical_design
Robot for Transferring Items
Robot for Transferring Items – Mechanical Design  
Track: Mechanical – Week 3  
Software Used: Cinema 4D

 Steps of Work:

1. Launching the Software:
I opened Cinema 4D and created a new project to design a robot that transfers items from one warehouse to another.

2. Base Design:
I added a Cube object to represent the robot’s base.

Dimensions of the base:
  X = 60 cm  
  Y = 10 cm  
  Z = 80 cm
 
3. Adding the Wheels:
I created a Cylinder to represent each wheel.

Wheel dimensions:
Radius = 10 cm  
Height = 5 cm  
Rotation (P axis) = 90

We added 4 wheels:
 Two on the right (front and back)
 Two on the left (front and back)

4. Robot Arm Design:
I used two Cubes to build the robotic arm.

Lower Arm:
X = 10 cm  
Y = 40 cm  
Z = 10 cm  
Positioned vertically on top of the base.

Upper Arm:
X = 8 cm  
Y = 30 cm  
Z = 8 cm  
 Placed on top of the lower arm.
  
5. Gripper (Optional – Not Included):
A small gripper can be added at the end of the upper arm to grab and release items.

Execution Algorithm:
1. The robot starts inside the first warehouse.
2. It detects an item in front.
3. The arm picks up the item using the gripper.
4. The robot moves to the second warehouse.
5. The arm places the item in the drop zone.
6. The robot returns to the starting point.
7. The process repeats.

   | Element                 | Value                       |
| ----------------------- | --------------------------- |
| Horizontal Reach Radius | 50 cm                       |
| Vertical Arm Reach      | \~70 cm                     |
| Arm Rotation Angle      | Up to 180°                  |
| Lifting Capacity        | 2–3 kg                      |
| Workspace Coverage      | Between two warehouse zones |

This mechanical design shows a robot that transfers items from one warehouse to another without human involvement.
All components were designed using Cinema 4D with realistic dimensions and movement behavior.
