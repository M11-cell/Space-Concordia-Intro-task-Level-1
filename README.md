# Space-Concordia-Intro-task-Level-1
All the files for the python and C++ nodes are included 

Here are the publisher and subscriber files for both python and C++. 

Starting off with the python files; 
1. run a terminal with turtlesim 
2. in another terminal: colcon build --packages-select sc_py_pkg 
3. run the program using "ros2 run sc_py_pkg listener" and the turtle will begin to continuously move around in a circle 
4. in another terminal, run the pose subscriber with the command "ros2 run sc_py_pkg listener" 

Now for the C++ files;
1. colcon build --packages-select sc_cpp_pkg
2. in one terminal run the publisher with the command "ros2 run sc_cpp_pkg talker"
3. in another terminal run the subscriber with the command "ros2 run sc_cpp_pkg listener" 
