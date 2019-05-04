2018年8月

该文件夹包含与“现代机器人：力学，计划和控制”一书相关的V-REP模拟场景，Kevin Lynch和Frank Park，剑桥大学出版社，2017年。

要了解有关本书，相关软件，V-REP模拟，书籍视频，Coursera课程等的更多信息，请参阅
 
http://modernrobotics.org

有关V-REP演示场景的更详细说明，请参阅

http://hades.mech.northwestern.edu/index.php/V-REP_Introduction

=====
 
以下是文件的简要说明。 V-REP场景都以.ttt结尾。

Scene1_UR5.ttt：用于交互式操纵UR5六关节机器人的V-REP场景。

Scene2_UR5_csv.ttt：V-REP场景，动画UR5遵循文件中指定的路径。

Scene2_example.csv：Scene2_UR5_csv.ttt的示例输入文件。

Scene3_youBot.ttt：用于交互式操作youBot移动机械手的V-REP场景，由全向麦克纳姆轮移动底座和五关节机器人手臂组成。

Scene4_youBot_csv.ttt：V-REP场景，动画youBot跟随文件中指定的apath。

Scene4_example.csv：Scene4_youBot_csv.ttt的示例输入文件。

Scene4_base_motions：包含Scene4_youBot_csv.ttt的输入文件的文件夹，仅移动移动基座，以在移动基座经历某些基本运动时演示麦克纳姆轮的运动：
  yb1.csv：移动基座以恒定速度旋转到位。
  yb2.csv：移动基站以恒定速度向前移动。
  yb3.csv：移动基站以恒定速度横向移动。
  yb4.csv：移动基座以恒定速度对角移动。
  yb5.csv：移动基座以恒定速度沿另一个对角线移动。

Scene5_motion_planning.ttt：V-REP场景，动画平面移动机器人沿着杂乱的平面C空间的图形表示移动。

Scene5_example：包含Scene5_motion_planning.ttt所需的示例输入文件的文件夹：
  nodes.csv：图中的节点。
  edges.csv：图中的边。
  path.csv：解决方案路径。
  barriers.csv：圆形障碍物。

Scene6_youBot_cube.ttt：V-REP场景动画解决youBot操作立方体的解决方案。

Scene6_example.csv：Scene6_youBot_cube.ttt的示例输入文件。

Scene7_MTB_csv.ttt：V-REP场景，为四关节RRPR机器人设置动画。

Scene7_example.csv：Scene7_MTB_csv.ttt的示例输入文件。

Scene8_gripper_csv.ttt：V-REP场景，为youBot的末端效应器（抓手）设置动画。这用于验证youBot末端执行器参考轨迹，而不需要youBot的完整运动。

Scene8_example.csv：Scene8_gripper_csv.ttt的示例输入文件。

=====
 
作者：
Huan Weng，Jarvis Schultz和Kevin Lynch