### 🏪 OpenCV
OpenCV is a popular open-source computer vision library that enables developers to perform various tasks like image processing, object detection, and video analysis in their applications.

### 👇 Kaggle Link :
https://www.kaggle.com/code/shiblinomani/opencv-fundamental-with-python

### 🌵 Nature of objects in Computer Vision
`Static Computer Vision:`

Static computer vision deals with objects or scenes that are not changing over time. Example: Image-based object recognition

`Dynamic Computer Vision:`

Dynamic computer vision involves objects in real-time or scenes that are changing or moving over time. Example: Video-based tracking of moving objects, vehicles in traffic surveillance, tracking a person's motion in a sports game.

### 🌵 Some Important Understanding of OpenCV

* **Images:** An image is a 2-D/3-D array of pixels that can be either grayscale or color (BGR or RGB).

**`GrayScale Array Shape(2D):`** 32x32 (height, width)

**`RGB or BGR Array Shape(3D):`** 32x32x3 ((height, width, channels)

**note:** Red, Green, Blue (3channels) 

* **Images Loading:** Loading the images and preprocessed.

* **Channels:** In color images, each color (e.g., red, green, and blue) is represented as a separate channel. OpenCV allows you to manipulate these channels individually.

* **Grayscale:** A Grayscale images have a single channel, representing pixel intensities, and lack color information.

* **ROI (Region of Interest):** A region of interest is a specific area within an image where you want to perform a particular operation or analysis

![image](https://github.com/Shibli-Nomani/Deep-Learning-and-AI-Work/assets/101654553/9eb351c5-6893-4028-8ccd-188baa834d9c)



* **Histogram:** A histogram is a graphical representation of the distribution of pixel values in an image. And also provide us color intensity

**`Example:`** Pixel Intensity for Tumor Detection

![image](https://github.com/Shibli-Nomani/Deep-Learning-and-AI-Work/assets/101654553/d470ec3e-0989-47ce-b37c-35e055d07739)


* **Thresholding:** Thresholding is a technique used to segment an image by separating pixels into two groups based on their intensity values. It's commonly used for object detection and image segmentation.


**`Example:`** Pixel Intensity for Tumor Detection

![image](https://github.com/Shibli-Nomani/Deep-Learning-and-AI-Work/assets/101654553/a7ae9a65-0e01-4103-8ae7-d3a8b38e7267)


* **Contour:** A contour is a curve that connects continuous points along the boundary of an object in an image. Contours are used for object detection and shape analysis.
**Outer contours** define the outermost boundaries, while **inner contours** represent boundaries within larger objects or holes.

![image](https://github.com/Shibli-Nomani/Deep-Learning-and-AI-Work/assets/101654553/bed96cbb-a024-470c-b511-ecde07581445)


* **Morphological Operations:** Morphological operations in image processing serve to manipulate object shapes, reduce noise, enhance features, and aid in object segmentation by applying dilation, erosion, closing, and opening operations on binary or grayscale images.

**`Dilation:`** Increases the size of objects in a binary image by adding pixels to their boundaries. It's useful for joining nearby objects or filling gaps in the objects.

**`Erosion:`** Reduces the size of objects by removing pixels from their boundaries. It's helpful for noise reduction, object separation, or simplifying object shapes in a binary image.

**`Opening:`** Opening is performed by applying erosion followed by dilation on an image.

**`Closing:`** Closing is the reverse process, involving dilation followed by erosion.

![image](https://github.com/Shibli-Nomani/Deep-Learning-and-AI-Work/assets/101654553/3202db8b-45e9-4fd4-8427-3110b394e689)



* **Filter/Kernel:** In image processing, filters (or kernels) are small matrices used to perform operations like blurring, sharpening, edge detection, and more.

![image](https://github.com/Shibli-Nomani/Deep-Learning-and-AI-Work/assets/101654553/e17768e8-c801-4195-9e72-89b8e0abd77a)


* **Detection:** Detect and locate objects or features of interest within the image, often based on their characteristics or shapes.

* **Localization:** Determine the precise location and coordinates of detected objects or features. **Object Position in an Image**

In image processing, the choice of distance measure, whether **Manhattan (L1)** or **Euclidean (L2)** distance

`Manhattan Distance:` 1. vertical and horizontal movements in localization. 2. Nonlinear Distance.

`Eucliidea Distance:` 1. diagonal movements in localization. 2. Point to Point / Straight Line.

![image](https://github.com/Shibli-Nomani/Deep-Learning-and-AI-Work/assets/101654553/b42551c1-0057-48cc-832d-b05536256725)



* **Classification:** If needed, classify or **label objects** based on specific criteria or characteristics.

* **Recognition:** Recognize or identify objects or patterns in the image, often using **machine learning or pattern recognition** techniques.

