opengl_repo
code for opengl dependencies

run these before in the server for dependencies to check and install opengl pre requsites

##sudo apt-get update   
mandate "sudo apt-get install freeglut3-dev"

#sudo apt-get install cmake pkg-config

#sudo apt-get install mesa-utils libglu1-mesa-dev freeglut3-dev mesa-common-dev

#sudo apt-get install libglew-dev libglfw3-dev libglm-dev

#sudo apt-get install libao-dev libmpg123-dev


##################
execution steps 
gcc opengl_test_circle.c -lGL -lGLU -lglut -lm 
./a.out
