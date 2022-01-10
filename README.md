# multi_skeletontracker

Task: With a video stream input, identify people in it and track the skeleton in real time using ML. And extend this to multiple people skeleton detection, should be able to be running on a mobile device.

Required Libraries : numpy, tensorflow 2.4.1, tensorflow-hub, opencv-python, matplotlib
If you are using GPU (optional) : tensorflow-gpu 2.4.1

Description : As this task was to track the skeleton in an input video, which is a streamed video input so, we are going to access our mobile camera through IP address and stream it to our model and we can see the output in our System/Laptop  

Prequistence: 1. Install the app from Googleplaystore in mobile to stream video input (https://play.google.com/store/apps/details?id=com.pas.webcam)
              2. Go to Video preferences -> Video resolution -> 640x480 (for better view)
              3. Click Start server, now copy the below anyone of the Ipv4 Link and keep it streaming

STEP 1: Install & import the libraries
STEP 2: Run the GPU code to make the model to run on GPU (optional if you are using GPU)
STEP 3: Load the MoveNet model
STEP 4: Run all the defined Functions ( loop_through_people, draw_keypoints, EDGES, draw_connections )
STEP 5: Paste the ipv4 link in < cap = cv2.VideoCapture('**paste_the_link_here**/video') >
STEP 6: Run the cell
