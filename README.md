# PRO-C166


download and run ngrok




ngrok http 5500


open the global url 

----------------------------------------

VR
virtual reality is a 3D artificial environment in which a person can interact with the virtual objects in the scene with the help of some goggles or headsets devices.THAT
means you can totally immerse in a very different environment with the help of these devices.
These devices help you experience a completely different environment which is very similar to a real environment.


Ar

Imagin a tiger pet in your living room and you could play with him?
This can be done using augmented reality. In short we call it AR.

augmented reality is adding digital objects in the real world generally using the camera of the smartphone, but in virtual reality, the physical world is completely replaced by the virtual environment with the help of VR headset devices.


we will be learning how to make web based and mobile based augmented reality applications.

Augmented reality applications help to enhance the real world by adding virtual objects into that.

___________________________________

Today we will be learning how to create a web based Augmented reality application.


AR.js 
to make augmented reality, we have to use a library which can help us to create augmented reality scenes.


With the help of this library, we can make three types of web-based AR application:
● Marker tracking based AR.
● Image tracking based AR.
● Location tracking based AR.



----------------------------------

We will be learning how to make marker tracking based AR in today's class.

start working with TA1

The first step would be adding the aframe-ar.js library.
Let’s add the library src link in the <head>.
Link:
https://raw.githack.com/AR-js-org/AR.j s/master/aframe/build/aframe-ar.js
  
  
-----------------------
  
  attach embedded arjs to the scene element to initialise ar.js and set its properties for the camera and tracking permissions.
  
  <a-scene...
              
              
              >
    
    
    </a-scene>
  ----------------
  
 include the 3D gLTF models src file in the Asset Management.
  
  -----------------
  
  Now to display any object in our surrounding, we will have to tell A-Frame to use ar.js camera. This can be done with the help of <a-marker> tag.
  
  why we need markers to display objects in our surroundings.
Since we are going to display the object in our real physical world, we need something to tell the computer program where it needs to start displaying.
  
  the marker is nothing but the starting point of the coordinate system where the object can be displayed.
You can understand it as a reference point to create the coordinate system in the real physical world where the object can be displayed.
That means wherever we will place the marker that will become the origin(0,0,0), that will be the starting point of the coordinate system.

  

There are two most popular markers available: hiro and kanji markers
  
  to tell which type of marker to use, we will be using preset property.
Let's add the <a-marker> tag and create a gltf-model entity as a child of the <a-marker> and test the output.
  
  
  ------------------
  o see the output:
● Use ngrok to run the
application.
● Open HTTPS URL in your smartphone/laptop and give permission to use the camera.
● Open the hiro marker image and point the camera towards it.
  -------------------------------
  which component we use to add the animation which is present in the model itself?

This component is part of the A-Frame extras library which we have used already.
  
  
  
  
  
  
