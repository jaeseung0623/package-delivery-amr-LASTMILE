# Package-Delivery-Amr-LASTMILE

SLAM, 객체 인식 등을 통해 자율 주행 네비게이션 및 안전한 배송 경로를 확보한다.

---

## 프로젝트 개요
### **프로젝트 주제 및 선정 배경**
택배기사와 주민간의 갈등으로 인한 문제 상황 사례 
amr를 활용하여 효율적인 택배 배송 시스템 구축

## 사용 장비 및 기술 스택
- **로봇**: turtlebot4
<img width="374" height="386" alt="image" src="https://github.com/user-attachments/assets/ada00766-07dd-4039-ab5b-f6b2f39d3342" />

**소프트웨어**
  ROS2 Humble (Ubuntu 22.04)
  Python3
  Flask
  SQlite
  
---

## 프로젝트 트리 구조

---

## 사전 요구 사항
### ROS2 및 필수 패키지 설치

Ubuntu 22.04 + ROS2 Humble 환경에서 개발되었습니다. 다음 패키지를 설치해 주세요:

```bash
sudo apt-get update
sudo apt-get install -y \
  libpoco-dev libyaml-cpp-dev wget \
  ros-humble-control-msgs ros-humble-realtime-tools ros-humble-xacro \
  ros-humble-joint-state-publisher-gui ros-humble-ros2-control \
  ros-humble-ros2-controllers ros-humble-gazebo-msgs ros-humble-moveit-msgs \
  dbus-x11 ros-humble-moveit-configs-utils ros-humble-moveit-ros-move-group \
  ros-humble-gazebo-ros-pkgs ros-humble-ros-gz-sim ros-humble-ign-ros2-control
```

## Gazebo 시뮬레이터 설치
```
sudo sh -c 'echo "deb http://packages.osrfoundation.org/gazebo/ubuntu-stable $(lsb_release -cs) main" > /etc/apt/sources.list.d/gazebo-stable.list'
wget http://packages.osrfoundation.org/gazebo.key -O - | sudo apt-key add -
sudo apt-get update
sudo apt-get install -y \
  libignition-gazebo6-dev \
  ros-humble-gazebo-ros-pkgs \
  ros-humble-ros-gz-sim \
  ros-humble-ros-gz
```

## Process Diagram
robot8
<img width="2059" height="1023" alt="image" src="https://github.com/user-attachments/assets/a8cd6556-f492-4ce5-9d50-56306f6df9a4" />

robot8
<img width="1769" height="713" alt="image" src="https://github.com/user-attachments/assets/8f5b62a8-62ec-44d0-a665-d40a6a34cbcb" />

---
## Flask 및 SQLite

Flask
<img width="2077" height="753" alt="image" src="https://github.com/user-attachments/assets/0c6dd04a-8f56-40a4-8cd0-1a82b25cff1e" />

SQLite
<img width="2129" height="863" alt="image" src="https://github.com/user-attachments/assets/a678577e-3a92-4f13-a48f-b43ca0af1a28" />

---
