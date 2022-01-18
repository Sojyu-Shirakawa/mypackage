# mypackage
2021年後期ロボットシステム学の課題２用のrosを用いたpackageです。 <br>
rosを用いて1秒間にカウントが10進むプログラムと数値が2の倍数になるpackageです。 <br>

# system requirement
Raspberry Pi4 <br>
OS : ubuntu 20.04 <br>

# how to use
This package use 4 terminal
## how to install
This repository  uses ROS. <br>
If you haven't finished installing ROS, go ahead and install it. <br>
<br>
$ cd ~/catkin_ws/src <br>
$ git clone git@github.com:Sojyu-Shirakawa/mypackage.git <br>
$ source ~/.bashrc <br>


## roscore (terminal 1)
$ roscore <br>

## launch count.py (terminal 2)
$ cd catkin_ws <br>
$ rosrun mypkg count.py <br>

## launch twice.py (terminal 3)
$ cd catkin_ws <br>
$ rosrun mypkg twice.py <br>

## confirmation for count.py & twice.py
$ rosnode list //rosのnodeが確認できる <br>
$ rostopic list //rosのtopic確認 <br>
$ rostopic echo /count_up //count.pyの数値確認 <br>
$ rostopic echo /twice //twice.pyの数値確認 <br>

# end task
Ctrl + C //動作確認の終了 <br>

# reference
https://github.com/ryuichiueda/ros_setup_scripts_Ubuntu20.04_server

# Author
Sojyu-Shirakawa & Ryuichi Ueda <br>

# belonging
Chiba Institute of Technology

# LICENSE
GNU General Public License v3.0

