[My Github Repository](https://github.com/williamsaj1/williamsaj1.github.io)  

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
