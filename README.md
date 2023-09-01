# flowfield

# attributes of the flowfield:
 1.height of spawn location
 2.width of spawn location
 3.how many particles

# particle class

  attributes:
  
  1.x position
  2.y position
  3.speed
  4.direction
  5.color
  6.radius
  7.acceleration
  8.xeffect
  9.yeffect
  
# particle function
  //set color and speed to input from setup
  //move x to center of screen, move x right/left by up to half of spawn width
  //same thing with y
  //give each particle random direction based on an angle on the unit circle

#display function
  //fill circle and display circle at x and y position

#update functoin
  void update(){
   //check if particle is still on screen
   //change xeffect based on mouse position
   //same for y
   //update acceleration using noise based on x/y position and frame count
   //update direction using 98% previous direction and 2% new direction
   //update x position
   //update y position 
   //if not on screen,
   //reset position to spawn area
   //reset direction

# main:
  //set particles = to a list of Particles
  //add particles to the list of particles
  //set one third of the particles to a red color and 0.4 speed
  //one third to a green color and 0.6 speed
  //set one third+1 of the particles to a white color and 0.8 speed


# draw:
  //at each frame, display and update each particle

# mouse clicked
 //when mouse clicked, clear screen and reset particles
