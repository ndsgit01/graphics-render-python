# python-graphics-render
Render a stationary 3D object (polygon meshes) using Python, Matplotlib

This project
- Generates the 3D object coordinates (control points) of a droplet aka the wireframe from 2D base control points and then generates the polygon surface patches onto a file (droplet.txt) [Key concepts: Bezier curve, 3D rotation]
- Performs the 3D rendering taking in a file containing polygon surface patches (eg: droplet.txt) [Key concepts: Bresenham's line drawing, 3D to 2D perspective projection]

Future tasks
- enhance speed by performing clipping of polygon patches
- hidden surface removal
- illumination
