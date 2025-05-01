# Installation
```
cd ~/ros2_ws/src/ && git clone git@github.com:Ofurosuki/joy_to_vel_for_whill.git
```
# Build
```
cd ~/ros2_ws && colcon build --packages-select joy_to_twist
```

# Run
```
cd ~/ros2_ws/ && source install/setup.bash
ros2 run joy_to_twist joy_to_twist_node
```
