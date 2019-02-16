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

  // The -10 sets the starting point at -10 so that the blades of grass are coming out from the dirt, and not the bottom of     the canvas.
 
Assignment 6:
  // The point of an object is so that a simple variable in the function can reference an entire shape, simplifying the code      in the function if the shape is used multiple times.
 
Assignment 7:
  color = map(mouseX, 0, 255, 0, 400)
  // This would map a range of 0 and 255, to a range of 0 and 400
  
Assignment 8:
  year = random(1919, 2019)
  // This would provide a random year over the last century
