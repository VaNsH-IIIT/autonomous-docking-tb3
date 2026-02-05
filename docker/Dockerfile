FROM osrf/ros:humble-desktop

SHELL ["/bin/bash", "-c"]

RUN echo "source /opt/ros/humble/setup.bash" >> ~/.bashrc

WORKDIR /root/ros2_ws

RUN apt-get update && apt-get install -y \
    python3-colcon-common-extensions \
    vim \
    && rm -rf /var/lib/apt/lists/*

CMD ["bash"]

