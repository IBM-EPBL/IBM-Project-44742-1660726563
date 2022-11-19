# IBM-Project-44742-1660726563


NATURAL DISASTERS INTENSITY ANALYSIS AND CLASSIFICATION USING ARTIFICIAL INTELLIGENCE 

The project mainly classifies the type of Natural Disaster and the intensity by giving an image through the webcam. Natural disasters not only disturb the human ecological system but also destroy the properties and critical infrastructures of human societies and even lead to permanent change in the ecosystem.

Disaster can be caused by naturally occurring events such as earthquakes, cyclones, floods, and wildfires. Many deep learning techniques have been applied by various researchers to detect and classify natural disasters to overcome losses in ecosystems, but detection of natural disasters still faces issues due to the complex and imbalanced structures of images.

To tackle this problem, we developed a multilayered deep convolutional neural network model that classifies the natural disaster and tells the intensity of disaster of natural The model uses an integrated webcam to capture the video frame and the video frame is compared with the Pre-trained model and the type of disaster is identified and showcased on the OpenCV window.


INTRODUCTION :
* Natural disasters are inevitable, and the occurrence of disasters drastically affects the economy, ecosystem and human life. Buildings collapse, ailments spread and sometimes natural disasters such as tsunamis, earthquakes, and forest fires can devastate nations. When earthquakes occur, millions of buildings collapse due to seismological effects.
* Many machine learning approaches have been used for wildfire predictions since the 1990s. A recent study used a machine learning approach in Italy. Floods are the most devastating natural disaster, damaging properties, human lives and infrastructures.
* To map flood susceptibility, an assembled machine learning technique based on random forest (RF), random subspace (RS) and support vector machine (SVM) was used. As the population is growing rapidly, people need to acquire land to live on, and as a result the ecosystem is disturbed horrifically, which causes global warming and increases the number of natural disasters.
* Populations in underdeveloped countries cannot afford damages disasters cause to infrastructures. The aftermath of disasters leaves the humans in miserable situations, and sometimes the devastating effects cannot be detected; additionally, rescue operations cannot take place in most of the places and victims are unable to be identified due to geographical factors of the different areas.
* Disasters such as forest fires spread rapidly in dense areas, so firefighting is difficult to carry out; in this case, development of the strategy to predict such circumstances is crucial so that such disasters can be prevented beforehand.

 Project Objectives:

    ° Know fundamental concepts and techniques of the Artificial Neural Network and Convolution Neural Networks. 
   
    ° Gain a broad understanding of image data.
    
    ° Work with Sequential type of modeling.
    
    ° Work with Keras capabilities.
    
    ° Work with image processing techniques.
    
    ° Work with OpenCV.

Project Flow :
The user interacts with the UI (User Interface) to open the integrated webcam.

The video frames are captured and analyzed by the model which is integrated with flask application.

Once model analyses the video frames, the prediction is showcased on the UI and OpenCV window.


To accomplish the above task you must complete the below activities and tasks;

1.Data Collection.

-Collect the dataset or Create the dataset
2.Data Preprocessing.

-Import the ImageDataGenerator library

-Configure ImageDataGenerator class

-ApplyImageDataGenerator functionality to Trainset and Testset
3.Model Building

-Import the model building Libraries

 Prerequisites :
Anaconda Navigator :
Anaconda Navigator is a free and open-source distribution of the Python and R programming languages for data science and machine learning-related applications. It can be installed on Windows, Linux, and macOS. Conda is an open-source, cross-platform, package management system. Anaconda comes with so very nice tools like JupyterLab, Jupyter Notebook,QtConsole, Spyder, Glueviz, Orange, Rstudio, Visual Studio Code. For this project, we will be using Jupiter notebook and spyder.To install Anaconda navigator and to know how to use Jupyter Notebook a Spyder using Anaconda watch the video given here. [https://youtu.be/5mDYijMfSzs]
To build Deep learning models you must require the following packages :
Tensor flow: TensorFlow is an end-to-end open-source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries, and community resources that lets researchers push the state-of-the-art in ML and developers can easily build and deploy ML powered applications.

Keras : Keras leverages various optimization techniques to make high level neural network API easier and more performant. It supports the following features.

1. Consistent, simple and extensible API.

2. Minimal structure - easy to achieve the result without any frills.

3. It supports multiple platforms and backends.

4. It is user-friendly framework that runs on both CPU and GPU.

5. Highly scalability of computation.
Flask: Web framework used for building Web applications.Watch the given below video to Install the necessary Packages.
