# python-graphics-render
Render a stationary 3D object (polygon meshes) using Python, Matplotlib

Contents
-
- Generates the 3D object coordinates (control points) of a droplet aka the wireframe from 2D base control points and then generates the polygon surface patches onto a file (droplet.txt) [Key concepts: Bezier curve, 3D rotation]
- Performs the 3D rendering taking in a file containing polygon surface patches from the perspective of a user (represented by spherical coordinates) looking at the object (origin of the object coordinate system) (eg: droplet.txt) [Key concepts: Bresenham's line drawing, 3D to 2D perspective projection]

Animations of renderings:
-
![m](https://github.com/ndsgit01/python-graphics-render/assets/51270897/e264e161-89a7-483c-adbc-05f2e0ddc6ae)
![h](https://github.com/ndsgit01/python-graphics-render/assets/51270897/9a81530d-5d94-4bc8-8e2d-ed6395dd4cdf)
![v](https://github.com/ndsgit01/python-graphics-render/assets/51270897/419741a8-800b-497f-ac87-fbc82b686d5f)


Future tasks
-
- enhance speed by performing clipping of polygon patches
- hidden surface removal
- illumination
- perform rendering in the general setting world coordinate system and arbitrary user view direction
