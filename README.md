# dataset_lidar2D_legs 

![tag:lib:ROS](https://raw.githubusercontent.com/PouceHeure/markdown_tags/v1.0/tags/lib/ROS/ROS_blue.png)
![tag:category:robotic](https://raw.githubusercontent.com/PouceHeure/markdown_tags/v1.0/tags/category/robotic/robotic_blue.png)
![tag:language:cpp](https://raw.githubusercontent.com/PouceHeure/markdown_tags/v1.0/tags/language/cpp/cpp_blue.png)

Labeled data from lidar2D, locating legs inside lidar points. 
lidar: ydlidar X4

## Acquisition 

- acquisition pipeline 

![dataset_lidar2D_legs-pipeline](.doc/dataset_lidar2D_legs-pipeline.png)

- example data extract  

![dataset_lidar2D_legs-example](.doc/dataset_lidar2D_legs-example.png)

## Description

- folder name discribes the height in cm 
- each csv descibes one acquisition like this: 
    | theta (rad)         | r (m)             | selected (bool) |
    | ------------------- | ----------------- | --------------- |
    | -3.1415900000000003 | 0.0               | 0               |
    | ...                 | ...               | ...             |
    | -2.47745            | .6629999999999999 | 1               |
    | -2.4687099999999997 | 0.645             | 1               |
    | -2.45997            | 0.629             | 1               |
    | -2.45123            | 0.607             | 1               |

