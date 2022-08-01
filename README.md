# Mariokart3d
Pseudo 3d Render Engine for 2d Planes 

> *Requires internet*

> Internet is used to grab images from Imgur (Imgur passes CORS Policy allowing me to run getImageData on canvas)

- Controls: Arrow keys to move/turn
- Q : increases "near edge" of vision thrustrum
- A : decreases "near edge" of vision thrustrum
- W : increases "far edge" of vision thrustrum
- S : decreases "far edge" of vision thrustrum
- Z : increases angle of vision thrustrum (FOV)
- X : decreases angle of vision thrustrum (FOV)

![image](https://user-images.githubusercontent.com/26506402/182131954-5c6056be-e132-4fd5-bf60-02a72a912ef9.png)

Effectively, I track the user's position on the 2d plane, and draw a trapeziod of vision (Thrustrum). This acts as a sample area for drawing on the canvas. Some conversion is needed to properly map this data with perspective + a vanishing point

