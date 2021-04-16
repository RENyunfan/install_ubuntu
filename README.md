# ROS-melodic



```bash
sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'

sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654

sudo apt update

sudo apt install ros-melodic-desktop-full

echo "source /opt/ros/melodic/setup.zsh" >> ~/.zshrc
source ~/.zshrc

sudo apt install python-rosdep python-rosinstall python-rosinstall-generator python-wstool build-essential
```



# Eigen

```bash
sudo apt-get install libeigen3-dev
sudo ln -s /usr/include/eigen3/Eigen /usr/include/Eigen
```



# PCL

```bash
 sudo apt-get install ros-melodic-pcl-*

```



# mavros

```bash
 sudo apt-get install ros-melodic-mavros-*
```



# ssh

```bash
ssh-keygen -t rsa -C "renyunfan@outlook.com" 
```



# git



```bash
  git config --global user.email "renyunfan@outlook.com"
  git config --global user.name "RENyunfan"

```



# OOQP

https://github.com/RENyunfan/ooqp_group

