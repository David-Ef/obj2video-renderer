# .obj to video renderer


Script to render rotating views of a .obj 3D object.
The camera is dynamically set at a certain elevation to encapsulate most of the object, then rotates around it.
The script captures 100 pictures as the camera rotates, then generates a video from the images at 24 fps (~4s) using FFmpeg (video example [here](/outdata/example.webm)).

![example](/outdata/example.jpg)

Render size is specified in Renderer.py (`RENDER_SIZE` var)

## Requirements

```
pip install moderngl-window
pip install PyOpenGL

pip install pywavefront
pip install ffmpeg-python

pip install pyrr
```
