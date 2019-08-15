# ROS 설치 명령어 모음

    sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list' <br>

    sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654 <br>

    sudo apt-get update <br>

    sudo apt-get install ros-kinetic-desktop-full <br>

    sudo rosdep init <br>

    rosdep update <br>

    echo "source /opt/ros/kinetic/setup.bash" >> ~/.bashrc <br>

    source ~/.bashrc <br>

    source /opt/ros/kinetic/setup.bash <br>

    sudo apt install python-rosinstall python-rosinstall-generator python-wstool build-essential <br>

# ~/.bashrc 파일 넣을 명령어
    alias cw='cd ~/catkin_ws'
    alias cs='cd ~/catkin_ws/src'
    alias cm='cd ~/catkin_ws && catkin_make'
    source /opt/ros/kinetic/setup.bash
    source ~/catkin_ws/devel/setup.bash
    export ROS_LOCALIP=xxx.xxx.xxx.xxx
    export ROS_MASTER_URI=http://${ROS_LOCALIP}:11311
