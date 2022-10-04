# Mathematica
1) Represent real world objects in the form of coordinate curves
Determine the unknown given function of the curve of any object as well as their volume.
a) First, we placed the bottle on the graph paper, and traced its curve on the graph. Next we marked the points along
the curve and plotted the points
b) Then we plotted the points of the curve ‘L’ in Mathematica using ListCurvePathPlot command and the output
was similar to the curve of the graph paper. Then we obtained the function of the curve using FindFit command
and got the coefficients as output. So we put the values of coefficients in the function and plotted it.
c) Afterwards we integrated the function to find its volume (Pi*r^2*h) where r = function P, using NIintegrate
command.
d) Then we revolved the function around x axis in 3D to visualize its figure. For this we have used the command
RevolutionPlot3D to revolve and RevolutionAxis to revolve around x axis.

2) Tautochrones and Brachistochrones curves
a) A tautochrone curve is the curve for which the time taken by an object sliding without friction in uniform gravity to its lowest point is independent of its starting point on the curve. The curve is a cycloid, and the time is equal to π times the square root of the radius (of the circle which generates the cycloid) over the acceleration of gravity.
b) A brachistochrone curve or curve of fastest descent, is the one lying on the plane between a point A and a lower point B, where B is not directly below A, on which a bead slides frictionlessly under the influence of a uniform gravitational field to a given end point in the shortest time.
c) While the Brachistochrone is the path between two points that takes shortest to traverse given only constant gravitational force, the Tautochrone is the curve where, no matter at what height you start, any mass will reach the lowest point in equal time, again given constant gravity.
