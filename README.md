# Marker_detection_-_tracking-
This Python project implements marker detection and tracking using OpenCV and an Euclidean Distance Tracker. It processes a video (Sample.mp4) to detect and track moving markers, typically used in biomechanics and gait analysis.

Key Features:

🔹 **Background Subtraction** – Removes static elements to isolate moving markers.

🔹 **Region of Interest (ROI)** – Focuses on a specific area for accurate detection.

🔹 **Contour Detection & Filtering** – Identifies markers based on size and movement.

🔹 **Euclidean Distance Tracker** – Tracks markers across frames using distance-based tracking.

🔹 **Real-time Visualization** – Displays the detected and tracked markers on the video.


This project is particularly useful for motion capture analysis, gait studies, and object tracking applications. 🚀

➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖

1. **Install Required Libraries**
   
Ensure you have the necessary Python libraries installed. 

2. **Prepare the Necessary Files**
   
Make sure you have: 

✅ Python script (tracker.py) – This should contain the Euclidean Distance Tracker class.

✅ Main script (main.py) – The code you provided (or the updated version).

✅ Input video (Sample.mp4) – Ensure the video file is in the same directory.


3. **Run the Code**

✅Execute the script using Python:

4. **Understanding the Output**

⚠️A window will open showing the video with tracked markers.

⚠️Detected objects will have bounding boxes with unique IDs.

⚠️The "Mask" window will display the processed binary image.

⚠️The "ROI" window will focus on the region of interest.




https://github.com/user-attachments/assets/002536ba-6370-4f71-adb3-87e399797abe




https://github.com/user-attachments/assets/c729c9f7-fb38-4bec-b7b0-d5254f164a47




Console Output – (x, y) Pixel Coordinates

The script prints detected object coordinates (top-left corner of bounding box) along with the ID. Example output in PyCharm console:

yaml

Copy

Edit

Marker ID: 1 | Coordinates: (x=120, y=250)

Marker ID: 2 | Coordinates: (x=300, y=400)

Marker ID: 3 | Coordinates: (x=550, y=600)



Applications of (x, y) Coordinates

The extracted (x, y) pixel coordinates can be used for:

✅ Gait Analysis – Tracking joint movements in biomechanical studies.

✅ Motion Analysis – Detecting marker displacement over time.

✅ Data Visualization – Plotting trajectories of markers.







