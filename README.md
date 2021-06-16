# Project-Mapmyworld
Map my world

## Follow the following Steps to launch the project 

 * ### Clone the repository
    
    ```git clone https://github.com/manjotsinghsuri/Project-Mapmyworld.git```

* ### Then build the packages 

    ```catkin_make```

* ### Then source it
    ```source devel/setup.bash```

* ### Launching the world
    ```roslaunch my_robot my_world```

* ### Launching mapping launch file
    ```roslaunch my_robot mapping.launch```

* ### [Optional] For doing localization with mapping
    ```roslaunch my_robot localization.launch```

* ### For moving robot in the world for doing mapping 
    ```rosrun teleop_twist_keyboard teleop_twist_keyboard.py```
    
    or 
    
    ```rosrun my_robot teleop_twist_keyboard.py```

### So after mapping the environment, viewing the database file, run

```rtabmap-databaseViewer ~/.ros/rtabmap.db```

## Link of my database file that I ran 

[Link to Database File](https://drive.google.com/drive/u/1/folders/1iM0sXSG0xASxOTIygKWvLfBA_mYBxYY_)

## Images of my database file that I ran

## Map in Database Review

![alt text](https://github.com/manjotsinghsuri/Project-Mapmyworld/blob/main/ImageFiles/DatabaseReviewer.png "DatabaseReview")


## Database review with Graph view, Constraints view and Occupancy grid

![alt text](https://github.com/manjotsinghsuri/Project-Mapmyworld/blob/main/ImageFiles/DatabaseReviewerWithOccupancyGrid.png "Database Reviewer with views")

## 3-D View of the Map created

![alt text](https://github.com/manjotsinghsuri/Project-Mapmyworld/blob/main/ImageFiles/3DView.png "3D View")

