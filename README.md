# Unreal-Engine-5.1.1-bug-report

Hi, I'm reporting a bug concerning the "Is hovered?" function for widgets in unreal engine 5.1.1
I noticed that when the mouse buttons; Left click, right click, middle mouse click are pressed, then the function no longer detects the cursor, and this behavior has been very consistent from testing

The Testproject-1.mp4 video shows the issue with the function "Is hovered?" showing a widget with a timer of 0.5s which loops a print function showing if the widget is currently hovered 

 The image W_Widget-EventGraph.png shows the timer and what runs every 0.5s  

Action Input.png shows the input configuration I have 

BP_ThirdPersonCharacter-EventGraph.png shows the code and print that appear from the input events
