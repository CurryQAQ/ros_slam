# 地面无人机动平台大作业
## 通过gazebo和rviz以及slam功能包完成
操作流程
1、启动gazebo-------ros2 launch benz_descripition gazebo_sim.launch.py
2、启动SLAM功能包--------ros2 launch slam_toolbox online_async_launch.py use_sim_time:=True
3、启动rviz2------rviz2
4、启动键盘节点---ros2 run teleop_twist_keyboard teleop_twist_keyboard 

保存建完的图
1、新建map文件夹
2、在map目录下运行-------ros2 run nev2_map_server map_server_cli -f room

录制rosbag包
1、新建rosbag文件
2、录制-----rosbag record -a
3、播放-----rosbag play <bagname> 

