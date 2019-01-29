# Developing a robust model for electron microscope (EM) images and fluorescence microscope (FM) images 

## [Milestone Reports](Reports.md)

## Project Description

Fluorescence microscopy is one of the most popular imaging methods in biological research today. The basic intuition behind fluorescence microscopy is attaching fluorescent molecules called fluorophores to a biological structure of interest. The biological specimen is then bombarded with a specific wavelength of light. The fluorophores will absorb the light and remit the light at a different wavelength. Thus, the images captured from the biological specimen will reveal the locations of the fluorophores, and therefore, the location of the biological structure of interest. Because the fluorophores remit light at a different wavelength, locating the biological structure of interest within a fluorescent microscope image is a very easy task and does not require advanced computational techniques or advanced human expertise. 

One key limitation of fluorescent microscopy is the resolution of the images. Since fluorescent microscopy measures visible light, the resolution is limited by the wavelength of the visible light. Regular fluorescent microscopy has a resolution of about 250 nanometers per pixel, while super resolution methods can achieve a resolution of about 20-50 nanometers per pixel. This limitation of fluorescent microscopy limits the biological research that can be conducted with fluorescent microscopy, as some biological structures would be too small for the resolution of fluorescence microscopes.

Electron microscopy overcomes this limitation of fluorescent microscopy by using accelerated electrons as illumination instead of visible light. This allows electron microscope images to achieve a resolution of 0.1-1 nanometers per pixel. However, electron microscopy does have some drawbacks when compared to fluorescent microscopy. One such drawback from the added resolution is that the signal to noise ratio is lower. The biggest drawback, however, for electron microscopy when compared to fluorescent microscopy is the lack of labels, since one can no longer use fluorophores to label the area of interest in the image.  This means that analysis of electron microscope images is a very hard and time consuming process. Thus, our research will focus on developing novel computational techniques to overcome this drawback in electron microscopy.

I will be working with professor Robert Murphy, the head of computational biology department at Carnegie Mellon University. Professor Murphy previously collaborated with professor Deva Ramanan from the Robotics Institute and Ligong Han, a masters student who has now left Carnegie Mellon University. Their previous work focused on developing a generative adversarial network that can generate realistic electron microscope images of cells with their corresponding labels. 

Instead of generating realistic looking EM images, this research project will focus on bridging the gap between electron microscopy and fluorescence microscopy. This is particularly challenging because images from the electron microscope are very different than images from the fluorescence microscope. However, robust computational techniques that can bridge the gap between electron microscopy and fluorescence microscopy would allow biological researchers to apply FM imaging techniques with the resolution of EM imaging. This will improve the results of previous research as well as create new directions in biological research. 


## Project Goals

In order to bridge the gap between electron microscopy and fluorescent microscopy, we will develop a model that can convert EM images to FM images as well as FM images to EM images.

In particular, the key difference between electron microscopy and fluorescence microscopy we like to explore is probes like fluorophores within the image. Therefore, for our 75% goal, we like to build a classifier that can distinguish the different types of probes within an EM image. The end goal of the project is to build a robust bidirectional model for EM and FM images. Thus, for our 100% goal, we like to build a statistical/machine learning model that can convert EM images to FM images and vice versa with at least 2 probes. If time permits, we would like to make our model more robust. For our 125% goal, we like to improve the robustness of our model and increase its conversion accuracy.


## Milestones

By the end of 15-300 (December 17th), I will have conducted the appropriate literature search needed for the project as well as set up all the software I need for the project.  

By February 1st, I will have implemented the existing GAN from professor Murphy’s previous work and have conducted some analysis on the data. I also will have investigated some potential methods that I can use for feature matching between images. 

By February 15th, I will have started developing or implementing a method that can match locations of probes from fluorescent microscope images to electron microscope images.

By March 1st, I will have completed the probe matching algorithm and measured the performance of the algorithm. I also will have investigated methods of classifying different probes within an electron microscope image. 

By March 22nd, I will have finished building the classifier for probes within an electron microscope image, and I will have measured and compared the effectiveness of the classifier. In addition, I will have investigated potential models that can convert electron microscope images to fluorescent microscope images and vice versa. 

By April 5th, I will have started to implement our model that can convert electron microscope images to fluorescent microscope images and vice versa. 

By April 19th, I will be mostly done with the model implementation, and I will be tuning our final model.

By May 3rd, I will have measured the performance and effectiveness of our final model.

## Literature Search:	

I have already reviewed the previous research paper from Professor Murphy, Professor Ramanan, and Ligong Han on the subject matter. I need to conduct more literature search for the project. In particular, I would like to investigate effective methods of image matching, EM image classification, and statistical or machine learning models for FM/EM imaging.

## Resource Needed:

We need correlated light microscopy and electron microscopy (CLEM) datasets for our research project. I will be looking for some public CLEM datasets on the Internet while professor Murphy will be searching for some private CLEM within Carnegie Mellon University. In addition, a graphics processing unit (GPU) may be needed, depending on the model we choose, as training the model could be computationally intensive. 
