# Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)

# Installation

## Installing pysdf
```
# The path should be to your specific workspace
cd ~/catkin_ws/src
git clone https://github.com/ufrj-nautilus/pysdf.git
cd ..
caktin_make
source devel/setup.bash
```

# Usage
## Conversion Process
To convert a .sdf model to a .urdf model, the usage is:
```
rosrun pysdf sdf2urdf.py <sdf_path> <urdf_path> [-h] [--meshes-path MESHES_PATH] [-p PLOT] [--no-prefix]

# Use --meshes-path MESHES_PATH to add a path to sdf2urdf find your meshes.
```
