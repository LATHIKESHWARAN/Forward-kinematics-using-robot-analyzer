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
1.open the roboanalyzer software.

2.select the robot and its degrees of freedom.

3.change the values with the link lenght wherever necessary.

4.simulate the model for forward kinematics.

5.plot the graph between the link and the joints.

6.update the DH parameters of the link configuration and end effector configuration




### SIMULATION 
#### 4 DOF:
![o8](https://github.com/LATHIKESHWARAN/Forward-kinematics-using-robot-analyzer/assets/119393556/6f5fc812-b32b-4a9b-8092-c13c9f6c902a)
### 6 DOF:
![o9](https://github.com/LATHIKESHWARAN/Forward-kinematics-using-robot-analyzer/assets/119393556/b3316529-9d60-46ed-bb01-775139baeb0c)

 
 
 
 
 
 ### PLOT 
 #### 4 DOF:
 ![o10](https://github.com/LATHIKESHWARAN/Forward-kinematics-using-robot-analyzer/assets/119393556/8b22b89c-9105-4322-93d8-ed9622e5cb77)
#### 6 DOF:
![o11](https://github.com/LATHIKESHWARAN/Forward-kinematics-using-robot-analyzer/assets/119393556/c82fe979-ab7d-40d3-8e51-8755e94fd8c5)

 
 
 
 
 
 
 
 
 
 

 
 














### RESULTS :  
Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.
