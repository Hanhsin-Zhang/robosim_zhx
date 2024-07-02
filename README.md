### ROS noetic 机器人建图&路径规划实验代码  

本仓库含一个ros包，参照 http://www.autolabor.com.cn/book/ROSTutorials/ 的教程内容实现了两轮差速小车的xacro模型，并编写了launch文件（src/planning_sim/launch路径下）实现了小车的运动控制，建图和路径规划。


gazebo_test.launch——gazebo导入测试  
locate_test———建图&定位。使用getmap.launch存图,teleop_twist_keyboard控制运动   
planning.launch——定位+全局/局部路径规划（使用现有map）  
