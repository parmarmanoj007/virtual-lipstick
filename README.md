# virtual-lipstick
This notebook is containing step by step complete process of applying lipstick on an input face image with given R,G,B input.

1) This notebook is containing step by step complete process of applying lipstick on an input face image with given R,G,B input.

2) Task is completed using OpenCv and Dlib.

3) First I am detecting face in image using dlib.get_frontal_face_detector.

4) For deticting lips's landmark i'm using "shape_predictor_68_face_landmarks.dat" file from dlib.

5) using those lip's point generated a contour around lips.

6) Filled that contour with given rgb value.

7) to maintain the skin texture applied transparancy in color with alpha value of 0.5

Download shape_predictor_68_face_landmarks.dat from dlib.

Image source: google search
