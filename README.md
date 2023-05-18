# Road-lane-detection
Road Lane detection using machine learning and computer vision for autonomous driving.
A working ml pipeline for analyzing both video and image streams for automatically detecting lane lines for constant reference for steering for autonomous vehicles.
The methods used  are color selection, region of interest selection, grayscaling, Gaussian smoothing, Canny Edge Detection and Hough Tranform line detection. Our goal is piece together a pipeline to detect the line segments in the image, then average/extrapolate them and draw them onto the image for display. Once we have a working pipeline, it used on the video stream and analyzed frame by frame.
