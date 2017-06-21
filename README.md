# excel-train-simulator
Simple 2d train simulator in Excel

2D Track and Train Display is rendered by an Excel Scatter X Y graph

Start and Stop buttons activate/deactivate simulation

Speed column defines speed/direaction of a car

Place cursor on Speed cell and then use Ctrl-Shift-D or A to increase or decrease car speed

Two tracks setup
Three Cars/Trains set up - Car 3 has a train of four more cars behind it

Track X tabs hold definition of each segment of track
Car X tabs hold definition of each car and computed path for it
_CarTemplate is used by the Add Car button
Cars can be daisy chained together to make trains
Cells C2 and D2 define which car the current car trails behind

Bugs:
Cars/Trains cannot run off the end of Tracks
Even though Tracks appear to be joined together they are not
