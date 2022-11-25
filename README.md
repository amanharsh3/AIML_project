INTRODUCTION:

Controlling appliances and electronics through hand gestures is an important and still developing technology. Being able to completely detach from electronics to control appliances is very difficult to achieve as there are many ways an appliance may receive wrong commands. It is important that the system of control is robust enough to not let the appliance accept wrong/ false commands and still achieve the goal of communication. This project is the first step to detach the need of touch to control an appliance. There are many ways of achieving this, the most common is the use of a smaller appliance attached to the user that can detect the movement and communicate the information further as per requirement. Some other ways are detection of gestures through a camera, detection of the motion through a camera. This detection involves subdomains of computer vision such as object tracking and recognition of text.

Object tracking is one of the important applications in computer vision. Object tracking helps in understanding the environment and helps the computers or machines respond to the stimulus of movement appropriately. Writing text on air to control the applications in the machines involves object tracking, then it further involves the prediction of the instruction i.e. the recognition of the 
text. 

Recognition of the text written is also an important application in computer vision. Recognition of the text in natural images with the help of sliding windows and connected component analysis are mainstream in this domain. Recognition of text is particularly difficult as it involves the high variation in font, size, orientation and the complicated backgrounds.

Our project involves the recognition of one single digit that is written on the air. To achieve this we have adopted a deep learning based approach. The model adopted is convolutional neural network (CNN) which is most commonly used in the analyses of visual imagery. They are robust to shift and space variance based on their shared weights architecture and translation invariance. CNNs structure helps in avoiding overfitting in the model. The model needs to be trained on a dataset so that the trained model can be used in the prediction or recognition of the written text. The dataset used for this purpose is MNIST dataset. The Dataset consists of 60,000 training images of handwritten digits from 0-9. Recognition/ prediction can be achieved through this pre trained network. 

LITERATURE SURVEY:

We surveyed a few methods which would help in the tracking. One of them is taking the histogram of the object that is to be tracked and then subtracting the background environment in real time. 


1)	Akash Kumar Chaudhary et al. 

AIR CANVAS APPLICATION USING OPENCV AND NUMPY IN PYTHON. 

In Akash Kumar Chaudhary , Bharat Phogat ," Air Canvas Application Using OpenCV and Numpy In Python", International Journal of Research in  Engineering and Innovation. 8. 2395-0056. This Project focuses around change of Motion to Art . This framework utilizes A camera Device also, Computer Vision Software to follow the way of our Finger Tip . A powerful specialized technique decreases mobile and PC usage by taking out the need to write
 

2)	Pranavi Srungavarapu et all . 

VIRTUAL SKETCH USING OPENCV 

Srungavarapu, Pranavi and Maganti, Eswar Srilekkha (2021). "Virtual Sketch utilizing Open CV." International Journal of Inventive Technology and Exploring Engineering.10.107108.10.35940/ijitee.H9262.0610821. In this task we are playing out the morphological tasks are a bunch of tasks that processes pictures based on shapes. These apply a structuring component to an info picture and produce a output Image. Developing a connection point between human hand and the framework utilizing open cv strategies and python language to pick the colour and draw utilizing hand on the created drawing region.
 
3)	Harneet Kaur et all . 

A COMPREHENSIVE OVERVIEW OF AR/VR BY WRITING IN AIR

Sai, Guna and Raj, Akula. (2021) "A Comprehensive overview of AR/VR by Writing in Air" , International Journal of Logical Research in Computer Science, Engineering and Data Technology. 477-482. 10.32628/CSEIT217294. In this they expressed that Every stroke is comprised of series of points from which the machine programming chooses the primary focuses that will mirror the stroke. They performed three preliminaries to survey the satisfactory tolerance for slope n in getting the significant points to be viewed as in the study . The slope equation is then applied to the two back to back central points, which are comprised of x and y coordinates. The worth of progress in x co-ordinates and change in y-co-ordinates decides the slope of a Line .


4)	Priyanshu Mishra et al. Virtual Ink Using Python .

VIRTUAL LINK USING PYTHON

Creators in Akash Uniyal and all, ‘’ Virtual Ink Using Python (No. 5707). Easychair , 2021” , We use python as our essential language and its packages OpenCV and NumPy. Basically, OpenCV is a library of programming functions mainly aimed at PC vision. Initially created by Intel, it was later upheld by Willow Garage. And NumPy is basically, a library for the Python programming language, adding support for enormous, multi-dimensional arrays and lattices, along with an enormous collection of high-level numerical capacities to work on these arrays. The Project was fundamentally a PC vision application which utilizes the webcam of your gadget. By opening the webcam of your gadget all you want is to simply hold the pencil or some pen in our grasp, then, at that point, drag the pen or pencil in air if front of your gadget camera (approx.1530 cm).
 
SOFTWARES AND LIBRARIES USED:

ANACONDA: It is python pre-packaged distribution of python which contains python modules and packages, including JUPYTER.
TENSORFLOW: It is most popular framework in Deep Learning. Tensorflow is an open platform for machine learning. It is flexible ecosystem of tools, libraries and other resources that provide workflow with a high level API.
OPENCV: It is open-source computer vision and machine learning software library.

IMPLEMENTATION:

## Network Architecture
In neural networks, convolutional neural networks is one of the main categories to do image recognition, image classification. Object detections, recognition of faces are some of the areas where CNNs are widely used. A CNN is a deep learning algorithm which can take in an image as input, assign importance to various aspects/ objects in the image and categories the images. We prefer CNNs over feed forward neural networks because for image analysis feed forward neural networks can be overfitting and hence result in wrong outputs. Whereas CNNs can successfully capture the spatial and temporal dependencies in an image through the application of relevant filters or kernels.

## Lucas–Kanade method for Optical Flow
Lucas-Kanade method is used for optical flow estimation which assumes that the flow is essentially constant in a local neighbourhood of the pixel under consideration, and solves the basic optical flow equations for all the pixels in that neighbourhood, by the least square criterion.

CONCLUSION AND FUTURE WORK:

The project can be further improved by tracking finger without colour-specific detection. Data sets used in CNNs can be configured with augmented data to increase the accuracy of test cases. By implementing Optical Character Recognition (OCR), we can achieve recognition of multiple numbers/alphabet characters.
