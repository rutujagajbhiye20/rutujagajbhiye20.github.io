
Objective:
The objective was to apply computer vision techniques based on Artificial Intelligence for human pose detection that gives real-time feedback. The system assesses a yoga pose being performed and gives real time feedback in the form of error indicators along with a score to measure the accuracy of the pose being performed.

Motivation:
Recent advancements in Deep Learning has added a huge boost to the already rapidly developing field of computer vision. Pose estimation is a subset of computer vision that refers to computer vision techniques that detect human figures in images and video, so that one could determine, for example, where someone’s ankle shows up in an image. The motivation behind this project was to detect movement and posture errors in performing yoga poses. The idea was to build an effective yoga programme for each user to help them improve their posture and health.

Approach:
Building a human pose detection system with the PoseNet model entailed dividing the process into 3 steps: Data Collection, Model Training and Model Testing. Capture Capture

Data Collection: Using PoseNet, when a pose would be detected, the 14-(x,y) inputs and target data would be fed into the neural network defined object. A setTimeout() function was used to record the poses for 5 seconds.

Model Training: The existing data would be loaded into the JavaScript environment. Once the downloaded json file was attached to the model training file, the neural network was then trained across 50 epochs.



Model Testing: The model was trained by determining a better way to collect the angles based on specified points as well as a scoring system. For the scoring system, two comparisons were run. Firstly, the model compared the user’s chosen pose with the pose being performed on camera. The second comparison was dependant upon the first. The model then compared each incoming angle against some target angle determined as the average of all individual angles computed for each pose.
