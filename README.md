
# Building Customizable Image Classifier
#### **Teachable Machine with OpenCV**

This article is shared on:
* [Medium](https://medium.com/@meqdad.dev)
* [Dev.to](https://dev.to/meqdad_dev)

## Opening...

Image classification plays a significant role within the field of computer vision, contributing to the resolution of numerous real-world problems. Its applications span various fields and disciplines, as we will explore in the following sections.

BUT...

### What is Image Classification?


<p align="center">
<img src="assets/image classification data labeling.webp" width=70% height=80%>

<i><a href="https://www.superannotate.com/blog/image-classification-basics">Source</a></i>
</p>

Image classification involves categorizing images -an entire image- based on their types or classes, and it serves as a fundamental task in the field of computer vision. This process finds wide-ranging applications in various domains, including object detection, medical diagnosis, security, agriculture, and entertainment.


### Steps for Building Image Classifier
#### (In our case)

To build an image classifier, you need to walkthrough the following steps:
- Collecting the data (images for each class)
- Training your model (Teachable Machine from Google)
- Testing your results in browser
- Exporting trained model into Python environment
- Classifying images with trained model by using [OpenCV](https://pypi.org/project/opencv-python/) and [Teachable Machine](https://pypi.org/project/teachable-machine/) packages
- Improving and repeat if needed

## What We Are Going To Build?

We will create an image classifier that can distinguish between Arabic and English books.

We will create an image classifier that can distinguish between Arabic and English books. To collect, train, and test data, we will use [Teachable Machine](https://teachablemachine.withgoogle.com/) from Google.

After training the model, we will export it with a `.h5` extension and use it with OpenCV and Teachable Machine Python packages.

### What is Teachable Machine?

From the [official website](https://teachablemachine.withgoogle.com/):
> Teachable Machine is a web-based tool that makes creating machine learning models fast, easy, and accessible to everyone.

With Teachable Machine, you can classify images, sounds, and poses. Our focus will be on using the image classification tool within the platform.

<p align="center">
<img src="assets/tm_tools.png" width=60% height=40%>
</p>

Using Teachable Machine, we will tackle the first three steps: collect data, train the model, and evaluate the results directly in the browser.

### Collecting Data (Images)

