# Horse Automata,Prototype

[Horse automata](https://www.youtube.com/watch?v=dtO8aX2QzzY)

#### The author of this mechanism is Greg Zumwalt.  He posted the mechanism on the [site](https://www.instructables.com/Horse-Prototype/)

#### I used Fusion 360 to design and render the mechanism.

## Why this mechanism?
#### I chose this mechanism because I like horses and also because it involves a lot of attention and it is very cute.

 
![horse](https://user-images.githubusercontent.com/79594745/118943038-f051fe80-b95b-11eb-9969-98aa213c3c0c.jpg)

## Description and how it works

 ### The project that I chose is Horse Automata which shows the way a horse can move.

 ### To work, this mechanism uses a 6vdc 300rpm gear motor (33x12mm 300RPM Metal Mini DC 6V Gearbox Gearwheel Motor Mini Reduce Speed Geared Electric Motor), a 6vdc wall mount power supply, and a phono jack for the power supply to power Horse, Prototype.

 ### When it is started, the wheels are moved by the gear worm and in this way the horse moves.
 ##### Below I attached a video made by me with the movement made by the horse

https://user-images.githubusercontent.com/79594745/118943265-21caca00-b95c-11eb-88ff-d9c3dfd8315d.mp4


## Main components 
### I chose to divide the mechanism into the following components :

- ### Head
	
 #### To make the head I made a canvas based on the stl from the main mechanism.

 #### I created the sketch based on the canvas and I extruded it.

 #### The head is located in front on a spacer body and it moves together with the support of the front legs.

- ### Tail
 #### To make the tail I made a canvas based on the stl from the main mechanism.

 #### I created the sketch based on the canvas and I extruded it.

 #### The tail is located in the back on a spacer body and it moves together with the support of the rear legs.

- ### Screw first tipe
 #### I imported the screw from McMaster and copied it to put it in several places.

- ### Screw second type
 #### I imported the screw from McMaster and changed the size and appearance of the end of the screw with a transversal plane.
 
 #### I also copied it to put it in more places.
 
- ### Screw for legs
 #### I imported the screw from McMaster and changed the appearance of it. 
 #### I changed the way the screw looks by replacing the spiral area over a certain distance with a smooth area. (I used construction planes)
 
 #### I also copied it to put it in more places.

- ### Spacer body
 #### I made a sketch for each spacer and extruded it.

- ### Body:
		        
			- body front
		        
			- body behind
		        
			- cam front
		        
			- cam froont behind
		        
			- cam rear face
		       
		        - cam rear behind
		        
			- gear idler- circle-shaped middle 
		        
			- gear idler- circle-shaped middle L 
		        
			- gear idler- hexagon-shaped middle
		        
			- gear idler- hexagon-shaped middle L
		        
			- gear worm
		        
 
 
 #### To make the body front I made measurements on the component from the initial mechanism and I created the sketch, after which I extruded it. Before extruding it, I made a copy of the component to have the body behind it.
  #### To make the front cams, I made three sketches as follows: one of the hexagon type that I extruded, one circular on the surface of the hexagon and the third one is the outer circle. Cam front differs from cam rear by the size of the outer circle.
  #### To make the wheels I measured the component from the initial mechanism and I made a canvas based on it. I made the sketch and copied the component several times and then I extruded them, and for the wheels with hexagon form in the middle I made an additional sketch.
  #### To make the gear worm I made the measurements on the initial component and I made the sketch that I extruded. To make the spiral I made two planes to delimit the area where the spiral will be.

- ### Front legs:
		         
      		         
			 - support upper leg front right
		         
			 - hoof front
		         
			 - leg front lower rear
		         
			 - leg front upper rear
		         
			 - leg front upper front
		         
			 - leg front lower front

  #### For all these components I measured the components from the initial mechanism and I made a canvas based on the measurements. I made the sketch and extruded the elements that I aligned suitable
  #### After extruding all of them I copied the large component and made the front leg on the other side.

- ### Rear legs:
		         
		         
			 - support upper leg rear right
		         
			 - leg rear lower front
		         
			 - leg rear upper front
		         
			 - leg rear lower rear
		         
			 - leg rear upper rear right
		         
			 - hoof rear

  
  #### For all these components I measured the components from the initial mechanism and I made a canvas based on the measurements. I made the sketch and extruded the elements that I aligned suitable
  #### After extruding all of them I copied the large component and made the rear leg on the other side.

- ### Holder
		         
			 - base
		         
			 - housing motor

   #### To make the base I measured the component from the initial mechanism and I made a sketch that I extruded. In the same way I worked on the motor housing.

- ### Motor 
 #### I imported a [motor](https://grabcad.com/library/n20-brushed-dc-gearmotor-single-shaft-1) and I change the size of the top of the motor to be the same with the one in the mechanism description.
 #### Also, I transform the motor up part of the motor into a component.


## Joints

### For this mechanism I made several joints, like:
 - #### revolute joint for the tail
 
 - #### revolute joint for the head
 
 - #### revolute joint for the gears
 
 - #### revolute joint for the legs components
 
 - #### rigid group for screws and legs components
 
 - #### rigid group for the base, bodies and motor house
 
### I grounded the holder, bodies and the motor (without the motor up component)

### The joints that are participating in the motion are:
 - #### revolute joint for the tail
 
 - #### revolute joint for the head
 
 - #### revolute joint for gear

### To see how the mechanism works you need to play the horse walk motion study.
### If you  just want to see how the legs move you can press on the revolute joint for the gear warm.
 

	
