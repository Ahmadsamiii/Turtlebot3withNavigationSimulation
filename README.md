# Turtlebot3 with Navigation Simulation

Steps of Use Turtlebot3 with Navigation Simulation:

- Step-1: Launch Simulation World



 <!-->

         export TURTLEBOT3_MODEL=burger

![image](https://user-images.githubusercontent.com/85820553/128580841-b54a2153-0a67-45f1-9aa4-ebce5db2a6c2.png)


 <!-->

         roslaunch turtlebot3_gazebo turtlebot3_world.launch

![image](https://user-images.githubusercontent.com/85820553/128581102-a2b1516c-0bc0-47c6-b362-d03e95f22506.png)


![image](https://user-images.githubusercontent.com/85820553/128581122-aae4cf18-23c9-4e56-b87a-cf7f9ea4f374.png)






- Step-2: Run Navigation Node



 <!-->

         export TURTLEBOT3_MODEL=burger

![image](https://user-images.githubusercontent.com/85820553/128580841-b54a2153-0a67-45f1-9aa4-ebce5db2a6c2.png)



 <!-->

         roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml

![image](https://user-images.githubusercontent.com/85820553/128581207-bee7adeb-45b6-478d-b5ef-c7c350b7dbc0.png)


![image](https://user-images.githubusercontent.com/85820553/128581279-0db96b2d-2330-4f12-bdd3-c6ed55caf66a.png)






- Step-3: Estimate Initial Pose



 <!-->

         export TURTLEBOT3_MODEL=burger

![image](https://user-images.githubusercontent.com/85820553/128580841-b54a2153-0a67-45f1-9aa4-ebce5db2a6c2.png)



 <!-->

         roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml

![image](https://user-images.githubusercontent.com/85820553/128581561-81227289-d223-471a-89f8-2095601e1075.png)





- Step-4: Launch keyboard teleoperation node to precisely locate the robot on the map




 <!-->

         roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=$HOME/map.yaml

![image](https://user-images.githubusercontent.com/85820553/128581615-501f8a75-de49-483d-96d3-6bfb4e068683.png)




- Step-5: Click the 2D Nav Goal button in the RViz menu:

![image](https://user-images.githubusercontent.com/85820553/128581768-2917ad77-2f0a-470c-b038-ec7d5cfba06f.png)














