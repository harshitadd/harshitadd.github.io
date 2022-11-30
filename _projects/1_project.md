---
layout: page
title: Thirsty Crow (Line Following Robot for Pebble Pick-Up)
description: Line Following Robot for Honeycomb Traversal and Aruco Processing for identifying pebbles on map. 
img: assets/img/eyrc.jpg
importance: 1
category: work
---
Winner of eYRC 2018 Theme Thirsty Crow

This project included work in -

1.Path Planning Algorithm used : Modified version of Breadth first search Algorithm. Modification : Saving the predecessor nodes in order to backtrack to source node.

Blender Animation : Specified within the final python file. Threading was used to run the path planning algorithm in background and the animation triggers in the foreground.Textures were overlayed separately on the blender objects to enhance the quality of the animation.Key Frame animation was used to order to overlay animated objects on the aruco markers.

Bot Traversal : Interrupts were used to recieve the path (being sent by the python script as an list of characters). Each character specified a particular movement by the bot.For the ADC interfacing - A relative approach was followed rather than using a thresholding value for the white line sensor calliberation.
    
