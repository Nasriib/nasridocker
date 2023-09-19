# Simple docker container for echo server
# Installation: first open a terminal window 
```
git clone https://github.com/Nasriib/nasridocker
```
# You may need to install docker first, so run:

```
sudo apt install docker-compose -y
```
```
docker-compose build
```
# Proceed to execute the following commands:
```
mkdir -p ros2_ws/src
cd ros2_ws/src
git clone -b humble https://github.com/ros2/demos/  humbledemos
cd ..
colcon build --allow-overriding demo_nodes_py
colcon build --sym
```
