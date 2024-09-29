```bash
echo "deb [trusted=yes] https://github.com/JafarAbdi/moveit-builder/raw/stable-2024-08-28/ ./" | sudo tee /etc/apt/sources.list.d/JafarAbdi_moveit-builder.list
echo "yaml https://github.com/JafarAbdi/moveit-builder/raw/stable-2024-08-28/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-JafarAbdi_moveit-builder.list
```
