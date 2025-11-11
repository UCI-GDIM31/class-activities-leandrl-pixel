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
Response 1: The  answer that I found intresting was the question if the vector was considered overkill? The response was never, no. The long answer is that as long as the game has to do with positioning 
then the game itself will need vectors, unless for whatever reason it does not need postioning, which is highly unlikely. 
Response 2: 
This class needs two member variables one being the type transform and the other being the type Navmesh 
Response 3: 
It needs two methods the start() method and update() method 
Response 4: 
It needs two methods the start()  method to where you store the NavMesh component of the gameObject to the navMesh variable by using GetComponent<>. The other method being Update() should access the SetDestination method from the navmesh variable and use the targets transform position as the parameter, so that the gamer object will actually go towards the target. 
### W6 
Response 1: my category assingment was the other tools section and my link is this  ([https://docs.google.com/document/d/1v9abHr0z2I_ynx3ik8Slda9mncvm8eCeKY5KIBUfL-c/edit?usp=sharing])
Response 2:
 
   The BatW6 class needs a float variable for how fast the bat moves and a Transform variable for the player. 
   It could also have a bool variable to check if the bat is chasing or not.
   The class should have two methods: EnableChase(Transform player) to start chasing and StopChase() to stop I think it could have different names in variation but all serve the same purpose. 
   The movement itself happens in Unity’s Update() method which makes the bat move toward the player each frame using Vector3.MoveTowards with Time.deltaTime for smooth motion.

   ### W7: 
   Response 1: My role was ui and the link to the google doc is https://docs.google.com/document/d/1FI6_2kwBTTaRBxAmNkWfBAGIedIvuOI0K7P5KUZhsA8/edit?tab=t.0  
   Response 2: Generally what was wrong with the transform.posisiton is its for direct positioning which doesn't work with what we want with movement. That's where transform.translate as it helps for moving in the local space of the scene. It works on object space and will actually apply with whatever movement you wanna apply relative to the space. WHile the transform position part does not care 

