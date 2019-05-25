cmake_minimum_required(VERSION 3.5)
project(ros_rosdeps NONE)

find_package(ament_cmake_core REQUIRED)

# Set environment hooks for default environment.
ament_environment_hooks(env_hook/setup.bat)

ament_package()
ament_generate_environment()
