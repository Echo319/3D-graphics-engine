# 3D graphics engine

The engine currently draws many triangles to the screen and fills them with a perfect white {255,255,255}. This is then shaded by the normal to the direction of the camera, providing some rudimental lighting effects.

The .obj file includes a list of vertices with x,y,z coordinates then a list of triangles with the index of each vertex these triangles are defined counter clockwise. This is important as the normal of the triangle is what determines the illumination, if it were clockwise then the normal would be inversed.

## Example pictures of the program working:

### Mountains
https://i.gyazo.com/9cfd28b915a060fc212b0c8caaa73436.png

### Utah Teapot: Aspect ratio was not too kind to the teapot.
https://i.gyazo.com/50d602acfff4b0a57b7ed1143cd4505d.png

TODO: Texture mapping, Z-Buffer, Multiple objects, refactor into a OOP solution to use as a component of future projects.
