This project is a Python-based CCTV surveillance application that uses OpenCV for live video streaming and recording. The application allows users to capture video from a webcam, adjust the resolution, and record video footage.

Key Features:

Adjustable Resolution: The camera resolution can be customized for optimal video quality.
Dynamic Video Recording: Records live video and saves it automatically with a timestamp in the filename.
Timestamp Overlay: The current date and time are displayed on the live feed.
User Controls:
Press 'ESC' to exit the app.
Press 's' to stop recording.
Press 'm' to minimize the window.
Installation:

Clone or download the repository.
Install the necessary libraries using:
bash
Copy code
pip install opencv-python pywin32
Usage:
Run the cctv.py script. You will be prompted to start the CCTV surveillance. The live feed will display, and you can control the app with the specified keys. The recorded video is saved in the footages directory.

This project demonstrates Python and OpenCV's potential for creating practical surveillance systems. It can be expanded with additional features, such as motion detection or remote access.
