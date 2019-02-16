# hw3
Assignment 2:

// This code draws the blades of grass

stroke(random(60, 70), 100, 90);
  line(x, height-10, x+random(-10, 10), height-10-random(h));
  noStroke();
  
// This code makes the lawn mower go by. It comes by at random time. 

if (random() > 0.999) {
    fill(255);
    rect(0, 0, width, height-15);
    h = 10;
    
// The point of the h variable is to raise the height of the blades of grass after each pass. 

// The -10 sets the starting point at -10 so that the blades of grass are coming out from the dirt, and not the bottom of the canvas.
