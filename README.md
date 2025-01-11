# Rekise_Marine
Problem Statement:
We want you create an application using react and open layers(to render the map) with the
following features:
a. Draw Linestring:
i. The Ability draw line string and stop the drawing of linestring through the enter
key
b. Draw Polygon:
i. The Ability to draw Polygons in the Map
c. Implement a modal:
i. Mission Modal: A modal to visualise the waypoints(coordinates) which are
created for the linestring.
ii. Polygon Modal: A modal to visualise the waypoints(coordinates) which are
created for the polygon.

d. A Button named Draw on the Map to start the drawing Mode
Behaviour:
As a user when i click on the draw button i am presented with this initial Modal

![image](https://github.com/user-attachments/assets/764d9bdc-a50e-4872-8b09-0857b5f22b59)

As i start drawing linestrings, the modal should be populated with the coordinates of the
linestring as illustrated below
![image](https://github.com/user-attachments/assets/740d3e59-f786-4139-b57b-4cc4c4a29f95)

Legends:
WP(00): waypoint number, can start with 00 or 01 its up to your discretion
Coordinates(12.97169189, 12.97169189): The coordinates of the Linestring in Longitude,
latitude format
Distance: The distance between one coordinate to the other in meters
You can add as many coordinates as possible, You can complete drawing your linestring by
pressing the enter key.
Insertion of Polygon:
When you click over the three dots in any of the coordinate rows you need to render a
dropdown(any component which would serve the purpose) with two options: Insert Polygon
Before and Insert polygon after. On Clicking of the either options you need to do two thing
1. Let the user draw polygon anywhere on the map
2. Change the view to Polygon creation view
![image](https://github.com/user-attachments/assets/b6677fa3-e148-4d0f-a6dc-8ac885efd8d7)

And consecutively you should render the coordinates and the distance once you start drawing
the polygon as below
![image](https://github.com/user-attachments/assets/3e06e899-e760-43e8-a859-344ed421768e)

You should be able to end or complete drawing the polygon by pressing the enter key. Once that
is done, you can import the polygon to the mission planner modal by clicking the Import Points
option.
![image](https://github.com/user-attachments/assets/5e578543-8212-4f9c-ba31-fa710b663f90)

The polygon and linestring should be connected, the connection would be with the starting point
of the polygon to the point where it is getting inserted in the linestring, similarly the same applies
with the insertion of polygon anywhere in between the linestring.


