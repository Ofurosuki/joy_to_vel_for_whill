# What is this?
Whill subscribes to `/whill/controller/cmd_vel` to control its motors. This package converts inputs from a game controller, published on `/joy`, enabling flexible operation of Whill through customizable key bindings.
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
