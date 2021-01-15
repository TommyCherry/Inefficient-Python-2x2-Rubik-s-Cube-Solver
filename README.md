# Inefficient-Python-2x2-Rubiks-Cube-Solver
It's exactly what the title says.
To be more specific:
- This is a program that you can use to solve a 2x2 Rubik's Cube.
- For me to tell you how to solve your cube, I need you to tell me the colors of each sticker on your cube in a certain order.
- Hold the cube however you want, but keep it like this the whole time (i.e. don't rotate the whole cube. Only turn individual layers as the program instructs).
- The first four stickers will be the ones on the top side of the cube, starting with the one in the back left and going around clockwise.
- Next are the ones on the left side, starting with the one on top in the back and going around clockwise.
- Next are the ones on the front side, staring with the one on the top left and going around clockwise.
- Next are the ones on the right side, starting with the one in the front on the top and going around clockwise.
- Next are the ones on the back side, starting with the one on the top right (keep in mind that you are still holding the cube the same way as before) and going around clockwise (based on the perspective you would have if you were facing the back side rather than the front side).
- Last are the ones on the bottom side, starting with the one in the front left and going around clockwise.
- You will enter a string of 24 characters based on the first letters of the colors of each sticker.
- For example, W corresponds to white, O corresponds to orange, G corresponds to green, R corresponds to red, B corresponds to blue, and Y corresponds to yellow. This means that if your cube is solved, the string you enter would look like WWWWOOOOGGGGRRRRBBBBYYYY.
- Now go to solver.py and enter your string!
