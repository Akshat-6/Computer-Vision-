# Computer-Vision-

Implementation of SIFT, RANSAC, and Harris Corner Detection using OpenCV to detect keypoints, filter matches, and identify strong corners in images.


🔍 Computer Vision – Feature Detection & Matching


This repository showcases the implementation of three foundational algorithms in Computer Vision using OpenCV:


SIFT (Scale-Invariant Feature Transform)


RANSAC (Random Sample Consensus)


Harris Corner Detection


Each module is implemented in a separate Jupyter Notebook, and tested on classic benchmark images.



📌 Project Structure


Computer-Vision-/
├── SIFT_Keypoint_Matching.ipynb
├── RANSAC_Outlier_Removal.ipynb
├── Harris_Corner_Detection.ipynb
├── images/
│   ├── box.png
│   ├── box_in_scene.png
│   ├── graf1.png
│   ├── graf3.png
│   ├── left01.jpg
│   ├── left02.jpg
│   └── building.jpg
├── README.md



🧠 Modules Implemented


🔹 1. SIFT – Keypoint Detection & Matching

Implementation of  SIFT algorithm to detect and match key points between two images.

Detects scale-invariant keypoints using SIFT.

Matches keypoints between:

box.png and box_in_scene.png

graf1.png and graf3.png


Visualizes top matches using cv2.drawMatches().

🧪 Result: Reliable matching even with rotation/scale change.



🔹 2. RANSAC – Outlier Removal from Matches


Using RANSAC to remove outlier key point matches and fit a transformation model between two images.


Applies RANSAC to filter outlier correspondences.

Fits a homography transformation model.


Images used: left01.jpg and left02.jpg

🧪 Result: Only inlier matches used to estimate image transformation robustly.


🔹 3. Harris Corner Detection


Implementation of  Harris corner detector to find and visualize corners in a grayscale image.


Applies Harris detector to grayscale image building.jpg.

Displays corner locations overlaid on the image.

🧪 Result: Identifies strong corners with sub-pixel accuracy.



💻 Technologies Used
