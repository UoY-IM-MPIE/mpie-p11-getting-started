# Practical 1.1: Getting Started With Unity

In this module, you will learn to create Interactive Environments using the Unity platform. In the last lecture you learned the basics of how environments are created and represented within the Unity platform in detail. In this practical class, you are going to get acquainted with Unity by ‘jumping into the deep end’ and exploring a finished project.
By the end of this practical you will:

- Have become familiar with the main parts of the Unity user interface
- Be able to manipulate the properties of pre-existing game objects
- Be able to create a simple ‘physics enabled’ game object from scratch

## Task 1: Opening a Unity Project

In this practical, you will explore and manipulate a pre-existing Unity scene called ‘Robot Lab’. 

To get started, make a copy of this repository on your GitHub account and clone it onto your local computer. You can do this by:

- Signing into GitHub
- Clicking the "Use this template" button at the top-right on the page
- Following the instructions in the introduction section of the VLE to clone a repository onto your local computer

The repository contains a complete Unity project. Look inside the folder. You will see that it contains a hierarchy of files and folders, which each store information about different aspects of an Interactive Environment. 

To complete this task, open the project in Unity. To do this:

1. Open the ‘Unity Hub’ application (try searching for it using spotlight if you can't find it)
2. Login to your Unity ID account or create one if you don't have it
3. Click the ‘Open’ button in the window that appears
4. Navigate to and select the root folder of the project repository you’ve downloaded
5. The project should now appear in Unity (it may take some time to load the first time)

** It is okay to change the version number of the project ** 

## Task 2: Running a Unity Scene

After the project has finished loading, a warehouse-like environment containing multiple robots should appear in the Scene View. If the scene does not appear, navigate to the ‘Scenes’ folder in the project browser at the bottom of the UI and double-click on the file named ‘RobotLab’.

Press the ‘Play’ (black right-facing triangle) icon above the Scene View to run the scene. The scene will load in the ‘Game View’. You can now walk around the scene with standard ‘first-person shooter controls’ (i.e. mouse to look and W, S, A and D keys to walk).

To complete this task, walk around to explore the environment. While walking around, try to find some simple things that you might like to change about the scene. When you’ve finished exploring, press the play button again to stop the scene from running and return to the Scene View.

## Task 3: Translate, Rotating and Scaling Game Objects

You can translate (i.e. move), rotate and scale Game Objects in a Unity scene by clicking and dragging on them within the Scene View. When you click on a Game Object, a transform manipulator (like the one from Blender) will appear. This manipulator will allow you to translate, rotate or scale the object depending on the transform mode selected (using the widget at the top left of the Scene View).

![Image showing transform manipulators](https://github.com/UoY-IM-MPIE/mpie-p11-getting-started/blob/main/Instructions/transform-manipulator6.png)

Using these transform manipulators, experiment with moving, rotating and scaling some of the game objects in the scene. To complete the task:

-	Move the character in the orange suit onto the balcony
-	Make the large fan smaller
-	Change the direction that the ‘battering ram’ robot is facing
-	Alter the start position of one of the two large robots to be down the stairs
-	An additional change to the environment of your choice

## Task 4: Manipulating Parameters Using the Inspector

Game Objects typically have parameters that can be manipulated to change their behavior and/or appearance. When a Game Object is selected in the Scene View, you can see and edit its parameters in the Inspector window, to the right of the UI.
Make the following changes to the Game Objects in the scene, using the inspector.

-	Make the robot arm rotate twice as fast
-	Decrease the acceleration and turning speed of one of the large robots
-	Change the image used to texture a part of the floor
-	An additional change to the environment of your choice

To finish the task, try and edit the parameters of some Game Objects while the scene is running (you may need to switch from the ‘Game View’ tab to the ‘Scene View’ tab to do this) and observe what happens.

## Task 5: Adding a Bouncing Sphere to the Scene
In the lecture, you saw how to add components to a Game Object. To complete this practical, follow the steps below to create a Bouncy Ball:

1. Create a new game object using a sphere primitive (Game Object → 3D Object → Sphere)
2. Rename the new object to be called ‘Bouncy Ball’
3. Add a ‘Rigidbody’ physics component to the object, so that it obeys the laws of physics (Add Component → Physics → Rigidbody)
4. Create a new ‘Physics Material’ (Assets → Create → Physics Material) and set its bounciness to 1
5. Assign your physics material to your sphere’s ‘Sphere Collider’

Press play, and observe whether your sphere interacts with the environment as expected. Does the ball keep bouncing or come to a stop? Can the physic material be altered to make the ball bounce forever?

## Task 6: Getting a Head Start with C#
This module uses C# as its main programming language, because this is what Unity requires. If you're not familiar with C# we have created [this tutorial](https://github.com/UoY-IM-MPIE/mpie-cs-tutorial/) to help you make the transition. We'll be covering some of the differences between the two languages in the next lecture. However, we recommend that you get a head start (and some hands-on experience) by completing the tutorial in this class.



