```bash
echo "deb [trusted=yes] https://github.com/jspricke/ros-one-packages/raw/bookworm-debian-amd64/ ./" | sudo tee /etc/apt/sources.list.d/jspricke_ros-one-packages.list
echo "yaml https://github.com/jspricke/ros-one-packages/raw/bookworm-debian-amd64/local.yaml debian" | sudo tee /etc/ros/rosdep/sources.list.d/1-jspricke_ros-one-packages.list
```
