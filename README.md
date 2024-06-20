##  Human-Detection-and-Crowd-Management
- A tensorflow based `Faster RCNN inception v2` python model to detect and count humans in real time images, videos & camera.
- Used pre-trained `frozen_inference_graph.pb` frozen graph to handle the detection.
- Visualize the data using `Enumeration Plot` and `Avg. Accuracy Plot`.

<!--

![GitHub language count](https://img.shields.io/github/languages/count/akash-rajak/Real-Time-Human-Detection-Counting)
![GitHub top language](https://img.shields.io/github/languages/top/akash-rajak/Real-Time-Human-Detection-Counting)
![GitHub repo file count](https://img.shields.io/github/directory-file-count/akash-rajak/Real-Time-Human-Detection-Counting)
![GitHub repo size](https://img.shields.io/github/repo-size/akash-rajak/Real-Time-Human-Detection-Counting)

![GitHub issues](https://img.shields.io/github/issues/akash-rajak/Real-Time-Human-Detection-Counting)
![GitHub closed issues](https://img.shields.io/github/issues-closed/akash-rajak/Real-Time-Human-Detection-Counting)
![GitHub pull requests](https://img.shields.io/github/issues-pr/akash-rajak/Real-Time-Human-Detection-Counting)
![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/akash-rajak/Real-Time-Human-Detection-Counting)

![GitHub Repo stars](https://img.shields.io/github/stars/akash-rajak/Real-Time-Human-Detection-Counting)
![GitHub Repo forks](https://img.shields.io/github/forks/akash-rajak/Real-Time-Human-Detection-Counting?style=social)
![GitHub Repo watchers](https://img.shields.io/github/watchers/akash-rajak/Real-Time-Human-Detection-Counting?style=social)
![GitHub contributors](https://img.shields.io/github/contributors/akash-rajak/Real-Time-Human-Detection-Counting)

![GitHub commit activity](https://img.shields.io/github/commit-activity/t/akash-rajak/Real-Time-Human-Detection-Counting)
![GitHub commit activity/year](https://img.shields.io/github/commit-activity/y/akash-rajak/Real-Time-Human-Detection-Counting)
![GitHub commit activity/month](https://img.shields.io/github/commit-activity/m/akash-rajak/Real-Time-Human-Detection-Counting)
![GitHub commit activity/week](https://img.shields.io/github/commit-activity/w/akash-rajak/Real-Time-Human-Detection-Counting)
![GitHub last commit](https://img.shields.io/github/last-commit/akash-rajak/Real-Time-Human-Detection-Counting)
![GitHub Discussions](https://img.shields.io/github/discussions/akash-rajak/PyVolSuggester)

![GitHub](https://img.shields.io/github/license/akash-rajak/Real-Time-Human-Detection-Counting)

This can be added as paragraph, and inside it pasting the html copied text, and making the paragraph center aligned

![GitHub issues](https://img.shields.io/github/issues-raw/akash-rajak/Real-Time-Human-Detection-Counting)
![GitHub closed issues](https://img.shields.io/github/issues-closed-raw/akash-rajak/Real-Time-Human-Detection-Counting)
![GitHub pull requests](https://img.shields.io/github/issues-pr-raw/akash-rajak/Real-Time-Human-Detection-Counting)
![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed-raw/akash-rajak/Real-Time-Human-Detection-Counting)
-->

****

### REQUIREMENTS : 
- python 3
- tkinter
- messagebox
- PIL
- cv2
- argparse
- matplotlib.pyplot
- numpy
- time
- os
- tensorflow
- fpdf

****

### How this Script works :
- User just need to download the file and run the main.py on their local system.
- On the starting window of the application, user will be able to see START and EXIT option, using which user can start the application or exit from the application.
- When user starts the application using START button, a new window will open, which allows user with options like, DETECT FROM IMAGE, DETECT FROM VIDEO or DETECT FROM CAMERA.
- When user selects any of the first two option, he/she needs to select the respective files using SELECT button.
- User can preview the selected file using PREVIEW button, and detect and count the humans using DETECT button.
- And when user selects, the last option of detecting through camera, user need to open the Camera, using OPEN CAMERA button, As soon as camera opens, detection process will start.
- After detection process gets completed or user manually completes it, two graph get plotted, 
	- 1.) Enumeration Plot(Human Count Vs. time) and 
	- 2.) Avg. Accuracy Plot(Avg. Accuracy Vs. time).
- Along with this two plots, an option to generate crowd report also appears, On clicking on it, a crowd report in form of PDF is generated ans saved autmatically at the project file location.
- In the crowd report genrated, there will be information like, What is Max Human Count, Max Accuracy, Max Avg. Accuracy, and also a two line status about crowd.

### Purrpose :
- This scripts helps user to easily get the count of human through real time image, video or camera, and thereafter also analysis of crowd through crowd report.

### Compilation Steps :
- Install all the required libraries.
- After that download the code file, and run main.py on local system.
- Then the script will start running and user can explore it by detecting the human and also getting the count of it.

****

****


