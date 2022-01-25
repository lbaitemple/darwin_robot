# darwin_robot
```
git clone https://github.com/lbaitemple/darwin_robot/
cd darwin_robot/src/darwin_gazebo
sudo python3 setup.py install
cd ../../
rosdep install --from-paths src --ignore-src -r -y
colcon build
source ./install/local_setup.sh 
roslaunch darwin_gazebo darwin_gazebo.launch
```

In another terminal
```
cd darwin_robot
source ./install/local_setup.sh 
rosrun darwin_gazebo walker_demo.py

```
