# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

 ![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:
1.Open the roboanalyzer software.
2.Select the robot and the degrees of freedom.
3.Change the values with the link length wherever necessary.
4.Simulate the model for forward kinematics.
5.Plot the graph between the link and the joints.
6.Update the DH parameters of the link configuration and end effector configuration.




### SIMULATION :
4 DOF
 ![robo exp-1](https://user-images.githubusercontent.com/93427224/174299442-fcd05b91-e1c0-4d2f-8f59-7773b3d556f4.png)


 6 DOF
 ![ex-3](https://user-images.githubusercontent.com/93427224/174300995-90cc7b06-f6f4-4015-a23a-7d90fbe9fda0.png)

 
 4 DOF
 
 ![robo exp-2](https://user-images.githubusercontent.com/93427224/174300802-fdbe766b-afd4-4577-988d-6e34942f2f99.png)


 ### PLOT 
 
 ![exp-4](https://user-images.githubusercontent.com/93427224/174299474-364e0d47-bd3e-4e39-af77-2d747b07572e.png)

### RESULTS :  
Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted..
