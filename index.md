[My Github Repository](https://github.com/williamsaj1/williamsaj1.github.io)  
  
**Project 4: December 9:**  
For this project I rigged skinned and animated an advanced model.
  
![Image](https://williamsaj1.github.io/siteImages/ex14/project4pic1.png)  
  
I found a model of a spider on made by. I snapped the joints in the legs to the centerpoint of vertices at the bends in the model by snapping to the cluster created by them. This was useful when rigging a model I had not made myself. After getting a good skeleton for the spider, I just needed to paint the skin weights and animate. I looked at videos of spiders walking to see how their legs ussually move. I took some creative liberties when it came to how the spider attacked the blockman.  
![Image](https://williamsaj1.github.io/siteImages/ex14/project4pic2.png)  
![Image](https://williamsaj1.github.io/siteImages/ex14/project4pic3.png)  
    
[![The Video](http://i.imgur.com/Ot5DWAW.png)](https://youtu.be/AvB13nUi-_k "Everything Is AWESOME")  
  
[The maya 2019 project file](https://github.com/williamsaj1/williamsaj1.github.io/blob/master/mayaProjects/WilliamsA%20p4%20maya.mb)  
I have placed a link to download the [video](https://github.com/williamsaj1/williamsaj1.github.io/blob/master/renders/WilliamsA%20p4%20vid.mp4).  
  
**Exercise 14: Watch a video November 16:**  
Watch a tutorial on rigging or animation in Maya.  
  
I watched a video on Youtube by Raph Crimson on 3D character rigging in Maya 2020.
[Video](https://www.youtube.com/watch?v=gUqqm3e4SfM)  
  
Mirror Joint: It saves time rigging multiple limbs to mirror across an axis instead of manually adding joints. This only works if there is symmetry to exploit.  
![Image](https://williamsaj1.github.io/siteImages/ex14/exercise14pic1.png)  
  
Clusters: When creating controllers with nurbs curves, I can snap the center of the controller to the centerpoint of vertices in a model by snapping to the cluster created by them. I think this could be useful if an animation includes scaling. This will ensure any scaling is from the center to prevent shearing effects as well as provide places to snap a joint.  
![Image](https://williamsaj1.github.io/siteImages/ex14/exercise14pic2.png)  
  
Set driven keys: These can be used to set animations that repeat by binding actions to the animations of other objects in a project. Here, the toes on the AT-ST's feet are set to rotate downward as the foot goes up.  
![Image](https://williamsaj1.github.io/siteImages/ex14/exercise14pic3.png)  
  
**Project 3: Bringing a Unicycle to Life November 11:**  
Texture, rig, and animate a unicycle to make a 10-20 second animation.  
  
I used an IK handle to control the position of the seat relative to the wheel. It seemed more intuitive with leaning than doing it manually. I made a ramp to have something interesting happen in the animation. A controller with an expression was used to animate the spinning of the wheel as the unicycle moves.
  
![Image](https://williamsaj1.github.io/siteImages/proj3/project3pic1.png)  
![Image](https://williamsaj1.github.io/siteImages/proj3/project3pic2.png)  
![Image](https://williamsaj1.github.io/siteImages/proj3/project3pic3.png)  
  
[The maya 2019 project file](https://github.com/williamsaj1/williamsaj1.github.io/blob/master/mayaProjects/WilliamsA%20p3unicycle%20maya.mb)  
I have placed a link to download the [video](https://github.com/williamsaj1/williamsaj1.github.io/blob/master/renders/WilliamsA%20p3unicycle%20vid.mp4).  
  
**Exercise 13: Stylized Walk Cycle November 4:**  
Create one alteration of a walkcycle. I chose to do one that showed fear or discomfort.  
  
![Image](https://williamsaj1.github.io/siteImages/ex13/exercise13pic1.png)  
I included eratic movements of the head to signify looking around for threats and self comfort motions with the arms. I tried to keep the step size small to keep the movement timid. I also figured reducing the sway of walking would show discomfort.  
  
I have placed a link to download the [video](https://github.com/williamsaj1/williamsaj1.github.io/blob/master/renders/walkManBlock.mp4).  
  
**Project 2: Replicating a Scene October 21:**  
For this project, I was tasked with rendering a real scene with maya modeling. I chose to take a picture of my guitar and surrounding doors using natural light, candle light, colored led lights, and a lamp.  
![Image](https://williamsaj1.github.io/siteImages/proj2/guitarOriginalPicture.jpg)  
![Image](https://williamsaj1.github.io/siteImages/proj2/guitarRender.png)  
  
I started by modeling the doors, guitar and floor using polygons.
The guitar body is textured with the Arnold standard surface with a water texture after I learned the wood 3-d texture I started with did not work well with the Arnold renderer.
The candle is comprised of cones that have a glow by default and also mesh lights to match. The candle wax also has a mesh light in it to mimic the glow seen in liquid wax. 
There are also uses of Arnold's texture setting, mettalic. This was used to make the rose gold of the guitar capo and the door knobs.
The floor has a fractal with the frequency turned up to get more random-looking spotting like the original picture.  
  
The glass around the candle is translucent and transparent, allowing both light and other objects to be seen through them but apply a bluish tint.
After messing with the intensity of the sky dome I decided I should keep it bright but block the light coming from the sides and top with some cubes.  
![Image](https://williamsaj1.github.io/siteImages/proj2/project2pic2.png)  
I found the best way to edit the effect of the lights is to change both the intensity and exposure. For shaping, I scaled the area light or changed the spread and roundness. The only light colors I used were a light yellow to mimic sunlight and candle, white for the lamp, and blue-green for the led light.  
![Image](https://williamsaj1.github.io/siteImages/proj2/guitarPerspective1.png)  
![Image](https://williamsaj1.github.io/siteImages/proj2/guitarPerspective2.png)  
![Image](https://williamsaj1.github.io/siteImages/proj2/guitarPerspective3.png)  
[The maya 2019 project file](https://github.com/williamsaj1/williamsaj1.github.io/blob/master/mayaProjects/WilliamsA%20p2%20maya.mb)  
  
**Exercise 11: Principles of Animation October 19:**  
Find three examples of the Principles of Animation within a movie.  
  
I chose to take a look at the movie, Spirited Away. The scene is of a pig-man falling out of a chair while eating.  
![Image](https://williamsaj1.github.io/siteImages/ex11/exercise11pic1.png)  
Anticipation:  
The slow build of the chair tilting before the fall is a use of anticipation. Using timing by having more frames in this area accentuates the quick fall afterward.  
  
Secondary Action:  
There is a lot of background movement of smoke and a few characters. Im focusing on the animaition of the pig-man's arm brushing food from the counter and the saliva dripping from his mouth as he begins to fall. I have never noticed it before but I see that it adds to the sense of a sloppy mess.  
  
Moving Hold:  
Before the fall, the girl appears to be shaking the way she is drawn. This is just a moving hold to keep her from being stagnant.  

  
**Exercise 10: High Quality Render October 12:**  
Make your model from project 1 look as great as you can, with
shading, lighting, and rendering.  
Place it on a table or on a floor or in front of a background.  
Create a moving camera that shows your scene  
  
I used phong shaders for everything except the matte gray peices of the toy car. For those I used a lambert shader. The floor is a phong material with the specularity turned down.  
I lit the scene using arnold area lights, varying their intensities and roundness. I went for a dark but polished look that is visible but might help hide some imperfections in the model.
  
![Image](https://williamsaj1.github.io/siteImages/ex10/exercise10pic1.png)  
Because I can't put a playable video here, this is a frame from the 4 second video. I have also placed a link to download the [video](https://github.com/williamsaj1/williamsaj1.github.io/blob/master/renders/WilliamsA_carRender.mp4).  
![Image](https://williamsaj1.github.io/siteImages/ex10/exercise10pic2.png)  
**Exercise 9: Shading and Lighing October 7:**  
Shade and light two spheres to make them look like the pictures.

The orange was made by applying a blinn texture to the sphere with a leather bump map. Spotlights were used to get specularity around certain areas of it.  
![Image](https://williamsaj1.github.io/siteImages/ex9/exercise9pic1.png)  
![Image](https://williamsaj1.github.io/siteImages/ex9/exercise9pic2.png)  
Jupiter was made using a ramp texture with the directional lights above and below it as inputs.  
![Image](https://williamsaj1.github.io/siteImages/ex9/exercise9pic3.png)  
![Image](https://williamsaj1.github.io/siteImages/ex9/exercise9pic4.png)  

**Exercise 7: Nurbs Shoe September 28:**  
Model a high-heel shoe using nurbs tools.  

While my first attempt involved drawing curves for every piece of the shoe with the cv and ep tools, curves were only drawn for the foot shape and heel on this one. I then used the birail tool to make the surfaces over the curves. I revolved a curve to make the heel and scaled some of the control vertices to make it look better. I used nurbs cubes for every other piece of the shoe. They were scaled and then rotated and translated with soft selection to flow easily.  
![Image](https://williamsaj1.github.io/siteImages/ex7/exercise7pic1.png)  
![Image](https://williamsaj1.github.io/siteImages/ex7/exercise7pic2.png)  
  
**Project 1: Car Model September 23:**  
Model a toy car I have taken pictures of as a reference.
![Image](https://williamsaj1.github.io/siteImages/proj1/project1pic1.png)  

This toy car started as a cube. Adding edge loops where needed, I made new faces to extrude to get the general shape of the car using reference images in the available orthagraphic views. Because I was using symetry across the middle, lengthwise, of the car, I only had to focus on one side during the process. For the finer shapes around the hood edges and outlines for the door, I translated edges and vertices. At one point, to keep a smooth look on the front bumper and hood, I used soft selection to model.  

After extruding a spoiler, I deleted faces to make a hole to match the toy's spoiler. I then used the bridge tool close the shape. The tire wells were made by placing cylinders intersecting the car and then doing the boolean difference of the objects. I then used the edge cut tool to make sure there were no n-gons. The main body of the car was then smoothened. The grey pieces of the model were made seperatley. All started as cubes that were scaled and creased by scaling edge loops if needed. The tires are cylinders with some faces extruded inward to match the shapes on the toy.
![Image](https://williamsaj1.github.io/siteImages/proj1/project1pic2.png)  
![Image](https://williamsaj1.github.io/siteImages/proj1/project1pic3.png)  
![Image](https://williamsaj1.github.io/siteImages/proj1/project1pic4.png)  
![Image](https://williamsaj1.github.io/siteImages/proj1/project1pic5.png)  
[The maya 2019 project file](https://github.com/williamsaj1/williamsaj1.github.io/blob/master/mayaProjects/WilliamsA%20p1%20car.mb)  

**Exercise 6: Watch how to Model a More Complex Object:**  

I watched a YouTube video series, made by 8fifty2torials, of modeling a Lamborghini. I have taken notes over the course of the series.  
  
[Video 1](https://www.youtube.com/watch?v=J64qYhdmP54)  
  
Starting with the edge of a tire well with a tube keeps you from having to cut into the model. It should be able to be done by extruding from each tire section and meeting in the middle of the car.  
  
Edit points in every view to ensure correct spacing of model details in comparison to reference images.  
  
Limit edges to to only have as many as needed for shape.  
  
[Video 2](https://www.youtube.com/watch?v=Jbpu5Oh9u98)  
  
Be sure of the position of points in a scene that will have points behind them before you begin to place points behind them to avoid more confusion.  
  
[Video 5](https://www.youtube.com/watch?v=0qSSI_t8-K4)  
  
Placing an edge loop near an edge will make the bend on that edge more angular even when it is smoothened.  
  
Get a broad shape of sections and then add edges within it to conform to the body of the car instead of extruding every small detail.  
  
Leaving objects with low polygons makes them easier to attach to other shapes.  
  
[Video 6](https://www.youtube.com/watch?v=VKePpdbSpsE)  
  
Snapping to vertex and then merging is more precise and manageable than using the weld tool.  
  
You definitely need more than just the front, side, back, and ¾ reference images. There are many more details that will take having multiple viewing angles to notice.  
  
[Video 7](https://www.youtube.com/watch?v=pTvRBsiQJxM)  
  
Although more involved, moving vertices manually is better than soft select when using references.  

**Exercise 5: Lamp September 21:**  
Model this lamp using nurbs tools.
![Image](https://williamsaj1.github.io/siteImages/ex5/exercise5pic3.png)  

Using the cv curve tool, I drew the orthagonal shape of one edge of the lamp. I then used revolve to make it a full object. The base was squared by scaling 4 of the vertices to make a sharper angle. The shade was made by making one line and revolving it around the center of the lamp base.  
![Image](https://williamsaj1.github.io/siteImages/ex5/exercise5pic1.png)  
![Image](https://williamsaj1.github.io/siteImages/ex5/exercise5pic2.png)  

**Exercise 4: Desk September 9:**  
Model this desk. Was also given the option to model it with the keboard drawer closed.  
![Image](https://williamsaj1.github.io/siteImages/ex4/exercise4pic1.png)  

This desk started as a cube. Using symmetry over the X, or Z axis at times, I added edge loops that could be used to make more faces to extrude. Because of the symmetry, I only had to focus on making one side of the desk. Fine changes in the shapes were made by scaling edges. The legs were created separately by using the same methods of the desk. The knobs are cubes that I used the smooth tube on after shaping them as handles.  
![Image](https://williamsaj1.github.io/siteImages/ex4/exercise4pic2.png)  
![Image](https://williamsaj1.github.io/siteImages/ex4/exercise4pic3.png)  
![Image](https://williamsaj1.github.io/siteImages/ex4/exercise4pic4.png)  

**Exercise 3: Lemon Squeezer August 31:**  
Create detailed model of a lemon squeezer.  
  
I started with a cylinder with a radius of 7 cm as I figured it to be a reasonable size for a lemon squeezer.  
I added extra segment rings to allow more places for me to edit the shape. The first change I made to the cylynder was pulling the middle up.  
I then pulled every other vertex in for the grinder utilizing an extra ring to smooth the angle of the grinder.  
  
An orthographic view of the grinder
![Image](https://williamsaj1.github.io/siteImages/ex3/exercise3pic2.png)  

All that was left was to raise the outer edge and add a lip.  

![Image](https://williamsaj1.github.io/siteImages/ex3/exercise3pic3.png)   
![Image](https://williamsaj1.github.io/siteImages/ex3/exercise3pic4.png)  
  
  
**Exercise 2: Solar System August 31:**  
Animate and shade all planets and moons in the solar system. Include orbits and rotations for all objects. Use shapes that allow the rotations of objects to be seen.  
  
![Image](https://williamsaj1.github.io/siteImages/ex2/exercise2pic1.png)   
I started by placing every planet. In order to let each planet rotate while orbiting the sun, I placed a small object in each planet's center that rotates about the sun. That center would be the planet's parent. Any rotation the planet does at that point will only be a spin about its axis. The moons are children of their own center parent object. The moon centers rotate about the planet's center. The relationships ended up looking like this.  

![Image](https://williamsaj1.github.io/siteImages/ex2/exercise2pic3.png)
![Image](https://williamsaj1.github.io/siteImages/ex2/exercise2pic2.png)   

Using keyframe animation, I gave every planet a unique orbit that is somewhat realistic in that the further away the planet is, the longer it takes to complete a cycle.
If the .avi is supported here, it will be below.  
[The maya 2019 project file](https://github.com/williamsaj1/williamsaj1.github.io/blob/master/mayaProjects/exercise2SolarSystem.mb)  

  
  
**Exercise 1: Robot August 24:**  
Build a robot, only based on primitives, limited to scaling, translating, and rotating.  
Use each primitive at least once.  
  
Its a robot that takes pictures.  
![Image](https://williamsaj1.github.io/siteImages/ex1/exercise1pic1.png)  
![Image](https://williamsaj1.github.io/siteImages/ex1/exercise1pic2.png)   
![Image](https://williamsaj1.github.io/siteImages/ex1/exercise1pic3.png)  
