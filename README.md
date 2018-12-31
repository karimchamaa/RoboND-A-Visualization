[![Udacity - Robotics NanoDegree Program](https://s3-us-west-1.amazonaws.com/udacity-robotics/Extra+Images/RoboND_flag.png)](https://www.udacity.com/robotics)

# RoboND-A-Visualization
You will visualize the shortest path for the robot to travel through the generated image

### Compiling
```sh
$ cd /home/workspace/
$ git clone https://github.com/karimchamaa/RoboND-A-Visualization
$ cd /RoboND-A-Visualization/
$ rm -rf Images/* #Delete the folder content and not the folder itself!
$ mkdir build/
$ cd src/
$ g++ main.cpp -o ../build/app -std=c++11 -I/usr/include/python2.7 -lpython2.7
```

### Running
```sh
$ ../build/app
```

Now, wait for the program to generate the path!

### Generated Path

![alt text](images/path.png)

