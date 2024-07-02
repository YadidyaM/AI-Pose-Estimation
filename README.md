Pose Detection and Curl Counter using Mediapipe
This Python script uses Mediapipe and OpenCV to detect human poses in real-time from a webcam feed. It calculates angles between key joints and implements a curl counter based on these angles.

Dependencies
mediapipe
opencv-python
Install dependencies using pip:

bash
Copy code
pip install mediapipe opencv-python
Usage
Run the Script:

Open a terminal or command prompt.

Navigate to the directory containing the script.

Run the script using Python:

bash
Copy code
python your_script_name.py
Key Controls:

Press 'Q' to quit the application.
Functionality:

Pose Detection: Tracks and visualizes keypoints (landmarks) representing various body parts.
Angle Calculation: Computes the angle between specified joints (e.g., shoulder, elbow, wrist).
Curl Counter: Counts the number of curls based on specific angle thresholds.
Notes
Ensure proper lighting and camera placement for accurate pose detection.
This script assumes a single person in the frame for optimal performance.
Adjust min_detection_confidence and min_tracking_confidence parameters in mp_pose.Pose for desired accuracy.
Credits
Mediapipe: Developed by Google Research. GitHub Repository
OpenCV: Computer vision library. OpenCV
