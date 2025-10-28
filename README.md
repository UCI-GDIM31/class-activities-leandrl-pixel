# in-class-activities
## Devlogs
### W1
Attached player script to the cat and allowed it to move.

### W2
W1 r,g, and b are float variables because the color depends on the decial because of the parameters that it was given that is why it is float. 
As the decimal increases the brightness increases 
W2 the ball is int because of the bounce a whole number since you can't have half a bounce. 
W3 it says error CS1002; expected 
## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 

### W3 
Response 1: Table # 17 
 Change how bright the room is and maybe we need to make the room darker, that sanity level goes 0 to 100. 
 The percent that we are trying to use. The most important part that doesn't have any input is that we are going to change the light level. 
  so we are not getting input type so its going to get void. 
Response 2: 
 A class is called headphones that define the structure and capabilities. 

When creating components the actual headphones form that class  and now we have something usable. 

Each pair has its own member variables which is the current battery to connection. 

The methods can perform the play pause charge.

3rd response:  The balls get extrmeemly bright because of how in unity your able to change the color constrast. but also within the code your able to tweak the settings a bit. by setting how much of a vlaue you want. For example each specfic color you want 


### W4 
Table 17 
Line 17 is defining the bool vairable and _isGrounded  with the value of true 

Line 28: if (Input.GetKeyDown(KeyCode.Space) && _isGrounded) 
This line calls the method GetKeyDown() with the parameter KeyCode.Space to see if the space key was clicked and it checks if the isGrounded member variable is true. This is an if statement and has an else if as well in case 

line 32:_isGrounded = false;
    This line changes the _isGrounded member variable to false
    Response 2 section : 
The solution I came up with for the collider activity was to make the SoccerBall detect when it went into the goal. I added a Ridgidbody 2D to the soccerBall so Unity could sense the collision and and I check the trigger part on the goal object. That way the ball can go through the goal without bouncing off although it would still count as scoring when it touched. 
Next part:
the solution I had to do to fix any of the mistakes was making sure the vfx was working with the code and I was getting the points in

### W5 
The  answer that I found intresting was the question if the vector was considered overkill? The response was never, no. The long answer is that as long as the game has to do with positioning 
then the game itself will need vectors, unless for whatever reason it does not need postioning, which is highly unlikely. 

    

   


