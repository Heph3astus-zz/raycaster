# raycaster
A line collision system built for python

it is currently set up to have 16 rays going out from a point
  This can be changed by adding to the slope list at the top. These are all the slopes of the rays
    Please note if you add or remove rays, you will have to update the i < 8 and i >= 8 near the bottom
    These are for differentiating the sides because on either side there are 2 lines with the same slope
    the m in the display section at the very botom should also be changed, however if you are not using pygame
    then simply remove it along with the screen parameter.
 
To use simply call the function and put in a list of a tuple of tuples as the objects, and give an entity
  The tuples should be start and end points of a line, and the entity must have a y and x attribute
 
