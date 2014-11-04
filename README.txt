This is the template for assignment 1 of UCLA CS 174A, taught by professor
Manuela (Alex) Vasilescu.

For enviroment setup, follow the same instruction as assignment 0;

In addition, you need to specify the path to find the two shader files fshader.glsl and vshader.glsl by:
(i )for mac user,
    (1) click "Product" in the middle of your menu bar on the top of your window
    (2) select Scheme -> Edit Scheme
    (3) select "Run [your project name]" tab on the left panel and 
        "option" tag on the right panel
    (4) In the working directory, select the "using custom working directory" and 
        in the text box below, search/input the path of the folder where you put the 
        two shader files.
(ii)for windows user
    (1) right click your project, select "Properties" (same place you specify the including path and library path)
    (2) on the left panel, select "Debugging" under the "Configuration Properties"
    (3) in the text box next to the working directory, search/input the path of the folder where you put the two shader files

The Angel folder contain the necessary math functions such as vector and matrix 
types and functions. 

The Ball* files are for mouse arcball control. 
The FrameSaver files are for recording into frames, which will be used later in second project for movie generation.

the glsl files are shaders, for now, you do not need to understand them. 

The majority of your coding should happen within anim.cpp.

The first step is to successfully run this template code. 
Second step is to study the display() function inside anim.cpp and  try to play with it by adding now objects.
Third step is to add code for animation in the idle() function

For this assignment, you also need to implement the rotateXYZ() function in Angel/mat.h to perform composite transformation, 
and fix vertices[8] and colorcube() in shape.cpp to draw a cube