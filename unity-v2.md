# Unity

<br><hr><br>
### Rigid body

The rigid body is a component that can be added to any GameObject, and that indicates that this GameObject can use the built in physics system.

<br><hr><br>
### Physics

The unity's built in physics system, is used to make our life easier when we want to implement a physics based game, any object that has the Rigid Body component  
will be subject to Gravity.

<br><hr><br>
### Movement

In unity, we can use the input manager to recieve input from the user in the form of vector3,  
using the Input.GetAxis("Horizontal"); or Input.GetAxis("Vertical");

We can then transform this input by multiplying it by a speed value & normalizing it and passing it into the transform.Translate() method to process our movement.

<br><hr><br>
### Collisions

Collider is a built in component in unity that basically allows an object to process collisions (in addition to rigid bodies),  
It creates bounds for the GameObject that are shaped like its outer surface.
