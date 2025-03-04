# Air-Drawing



This is a simple computer vision based project which tracks a target and uses the said target to draw on air. The motion of the target is captured by a webcam. The video from the webcam is processed by the computer to get an AR like image overlay on top of the live footage.

This project make use of a web cam to track the motion of the target.
	    
Each frame in the video is blurred using Gaussian blur to get a smooth image. The blurred image is then analysed to get the location of the pointing target.
The image is then masked and centroid of target is found. Then a line is drawn from current frame to the previous frame.

## Requirements

- Python 3
- OpenCV (`cv2`)
- NumPy (`numpy`)

## Usage

Run the script with Python:

```bash
python airDraw.py
```

Press the 'q' key to quit the application.

