```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/jspricke/ros-one-packages/bookworm-debian/ ./" | sudo tee /etc/apt/sources.list.d/jspricke_ros-one-packages.list
echo "yaml https://raw.githubusercontent.com/jspricke/ros-one-packages/bookworm-debian/local.yaml debian" | sudo tee /etc/ros/rosdep/sources.list.d/1-jspricke_ros-one-packages.list
```
