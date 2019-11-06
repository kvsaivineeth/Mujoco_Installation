# Mujoco_Installation


1. First apply for an account number from the mujoco website either the 30 day trial or the 1 year student license (if applicable)

2. Once the activation number is obtained (a lengthy string), and the system id is generated, an activation will be provided which will be used during the installation of mujoco software




Changes needed in the .bashrc file:

export LD_LIBRARY_PATH="$HOME/.mujoco/mujoco200/bin:$LD_LIBRARY_PATH"
export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/usr/lib/nvidia-<driverversion>
export LD_PRELOAD=/usr/lib/x86_64-linux-gnu/libGLEW.so
