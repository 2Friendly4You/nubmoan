![nubmoan banner](nubmoanBanner.png)

# nubmoan

Source code for nubmoan, the program that makes your ThinkPad TrackPoint (the red nub) moan when you press it.

Record your own moans and include them in the `/moanswav` folder in increasing intensity from 0-10 as `file1.wav` `file2.wav` and so on.

Compile with `gcc -o mouse_tracker_2 mouse_tracker_2.c -lwinmm -lgdi32` iirc.