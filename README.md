Project Overview

We utilize image recognition to identify a type of object and a designated location, then secure the object on a robot to transport it from its original location to the destination. 
The robot will scan around for the object using AI and find the best route to its destination. 
In our project, this is used to push a bin to a refuse collection point.


Proposed Approach

Labour is a very precious resource, one of the four factors of production, and because of a constant shortage in labour supply, we decided to create a robot in order to reduce the demand of labour in some particular industries. For example, we suggest using this robot to transport rubbish to refuse collection points. 
As we use image recognition as a base for the project, users can personalise the project by training the model themselves.
By changing to pictures supplied to change the model, the object and destination can be changed easily.

insert plain pic of bin

insert pic of marked bin

insert pic of bin with frame and percentage similar to bin listed

Using a camera attached to the robot, the surroundings can be scanned to find whether there is a bin nearby. 
This will be repeated until the bin is found and located at the front of the car. 
Then, the bin will be pushed to a refuse collection point.



To start creating a model, open notebooks in the jetracer file, then open interactive_regression.ipynb.
Follow the instructions and run the code with the heading ‘Camera’.
Then, change the dataset name here to what you prefer.
![image](https://github.com/user-attachments/assets/7cc42b93-6ac1-4bb4-a790-f321852e9dc6)
Run the Data Collection code and you should see a sqaure with the contents of the camera inside.
Click on the object you wish for the AI to recognise, move the camera and proceed to the next image.
Collect sufficient data by taking about 20-30 photos in various angles and directions.

Operation explanation!
The robot senses for trash bins via the camera with AI. When a bin is detected, the robot finds the most direct path to the bin calculates the best way to approach.
It first locks in on an item, proceeds forward and then rotates at the anchor to further reach the destination.
When the robot arrives, it utilises the magnets installed to attract and secure the bin onto the robot itself.
The robot then moves away, back to its original position to charge or to bring another bin back to its location.

pictures of blah blah here


```
aaaa
```
![results](https://github.com/user-attachments/assets/add53096-0fa9-4269-8cae-d490d03f3586)
![original](https://github.com/user-attachments/assets/b6165f39-ac29-4d0c-a7c3-5ee3230bb0db)
