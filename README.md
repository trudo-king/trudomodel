# Trudo
## Table of Contents
1.    Philosophy
2.    Threejs
3.    About Trudo
4.    Application
5.    Technology
6.    User Interface
7.    UI Architecture
8.    Hosting
9. Contribution
## Philosophy
In the fast-growing field of software engineering and development, and even more rapidly growing sector of game development the future is hard to predict. We are working with this game as our assignment.
In general software, the project is focusing on the creation of software. Consequently, Success can be measured by taking a look at the resulting software.
In a game project, the product is a game. But here comes the point. A game is much more than just its software. It has to provide content to become enjoyable. Just like a web server, without content it is useless and the quality cannot be measured. This has an important effect on the game project as a whole. The software part of the project is not the only one, and it must be considered in connection to all other parts. 


## Threejs
Threejs is cross-browser JavaScript library and Application Programming Interface used to create display animated 3D computer graphics in a web browser.
Three.js includes the following features 
*    Effects: Anaglyph, cross-eyed and parallax barrier.
*    Scenes: add and remove objects at run-time; fog
*    Cameras: perspective and orthographic; controllers: trackball, FPS, path and more
*    Animation: armatures, frame, kinematics, morph, and keyframe 
*    Lights: ambient, direction, point and spotlights; shadows: cast and receive
*    Shaders: access to full OpenGL Shading Language (GLSL) capabilities: lens flare, depth pass, and extensive post-processing library
*    Objects: meshes, particles, sprites, lines, ribbons, bones and more - all with Level of Detail 
*    Geometry: plane, cube, sphere, torus, 3D text and more; modifiers: lathe, extrude and tube
*    Data loaders: binary, image, JSON and scene
 ## About Trudo
Trudo is a 3D game which sounds like ludo but it has different functionalities and feels. As the name suggests it can be played by at most three players. It has a triangular plane in which each player have their house from where they have to start their game. It is a variant of the traditional Ludo game.
### Key features of Trudo:
a.    3 players can play together.<br>
b.    A player can come out of the house if dice shows the value ‘1’.<br>
c.    On value ‘6’, no subsequent chance will be provided i.e. each player will have only one chance in all conditions and then it will shift to the next person even if the player rolls 6 or kill any other player.<br>
d.    Place with the house color will be a safe point and for others, it will be killed i.e. no one can kill the token if it is in the house color and if token lands on the other house color, the player need to start from the beginning.<br>
e.    The first player to complete the triangle and back to home will be the winner.<br>


## Application
The game is developed using threejs and it has various applications. In our game, we used threejs as a major part and created most of the things using threejs.
1. Creating the scene – To be able to display anything with three.js, we need three things: scene, camera, and renderer, so that we can render the scene with a camera. 
2. Creating the geometry - To create a cube, we used a BoxBufferGeometry.To create a triangle, we used Triangular Geometry. In addition to the geometry, we need material to color it. We used MeshBasicMaterial, all materials take an object of properties which will be applied to them.
The next thing we did is creating a Mesh. A mesh is an object that takes geometry and applies a material to it, which we then can insert to our scene, and move freely around.
3. Texture Loader – Class for loading a texture. This uses the ImageLoader internally for loading files. Begin loading from the given URL and pass the fully loaded texture to onLoad.The method also returns a new texture object which can directly be used for material creation. If you do it this way, the texture may pop up in your scene once the respective loading is finished.
4. GLTF Loader – glTF (GL Transmission Format) is an open format specification for efficient delivery and loading of 3D content. Assets may be provided either in JSON(.gltf) or binary(.glb)format.A glTF asset may deliver one or more scenes,including meshes,materials,textures,skins,skeletons,morph targets,animations,lights,and/or cameras.
5. OBJ Loader – A Loader for loading a .obj resource. The OBJ file format is a simple data-format that represents 3D geometry in a human-readable format as the position of each vertex, the UV position of each texture coordinate vertex, vertex normals, and the faces that make each polygon defines as a list of vertices, and texture vertices.
6. Sky Box – Static background is not usually what we want in a 3D scene. Instead, we usually want some kind of skybox. A skybox is just that, a box with sky drawn on it. We put the camera inside the box and it looks like there is a sky in the background.
7. Orbit Control – Orbit Controls allow the camera to orbit around a target. To use this, as with all files in the directory, we included the file separately in our HTML.


## Technology
1.    JavaScript   -  Client-side Scripting
2.    Threejs       -   3D Animations    
3.    HTML          -   Front End
4.    CSS              -   Front End
5.    Bootstrap   -   For making it Responsive

 

## User Interface
The user interface of the app is important because that is how people interact with your product to achieve their needs and goals. Functionality and good visuals are important in establishing your brand and relationship with customers. A good UI makes it easier for your target audience to see what your product is.<br>
In our project, we did the following things to make our UI better.<br>
Firstly we created a 3D plane then with the use of BoxBufferGeometry we made a triangular shape on a triangular plane. Then added it to the scene. For making the background more attractive we put skybox in it to make it look like a sky. We integrated a 3D dice in it.<br>
We had 3 Avatars that work as players in this game so to make them look more attractive we set different colors of them and different positions. The camera plays a very important role in this so to make it exact we set different camera coordinates. We also used LookAt which rotates the object to face a point in world space. All the coordinates of dice, avatar, box, scene, camera, and triangle are fixed because they all are dependent on each other.<br>


## UI Architecture
Our game consists of two pages
1.    Front Page
2.    Main Page
![image](https://user-images.githubusercontent.com/51993963/62038537-89f26e00-b213-11e9-8908-a3c1a608e6b1.png)
<img width="933" alt="Untitled" src="https://user-images.githubusercontent.com/51993963/62039080-9925eb80-b214-11e9-814a-279f4ab9cdd4.png">


## Hosting
Web Hosting is a service that stores website’s data on the internet. We used 000webhost to host our game.<br />
 First, we signed in on 000webhost.In our case, we uploaded all the files and folder to the server to get the URL for our game.

 
## Contributors
1. Ankita Tripathi (Team Lead)
2. Manali Sethi
3. Garima Khandelwal
4. Shreya Desai
5. Harshit Mourya
6. Nilesh Verma

## Modified by
1. Aditya Jain

## Changelog
1. Removed unwanted files.
2. Removed Unused code.
3. Added New Background.
4. Fixed bugs.
5. Rearranged Files.