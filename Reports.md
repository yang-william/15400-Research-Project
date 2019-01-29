# Milestone Reports

## December 16th, 2018

### Major Changes
While the overall goal of my project didn’t change, I was unable to find any correlated light electron microscopy (CLEM) datasets from the Internet. This is probably due to the expensive nature of obtaining such data. My advisor professor Robert Murphy is currently attempting to gather CLEM datasets from one of his collaborators. My current project’s goal is build a machine learning model that convert electron microscopy images to fluorescence microscopy images and vice versa. From my current literature research and discussion with professor Murphy, I will most likely be using a deep neural network model to accomplish to task. If we are unable to locate any CLEM datasets, then my project’s goal has to change significantly. In particular, I will only be analyzing just florescence microscopy images instead of electron microscopy images. The new goal for the project will be building graphical models for the probability distribution of cellular structures in order characterize the relationships and interactions between different cellular components. To accomplish this new task, I will mostly likely rely on combinatorial models instead of neural network models. In addition, this change of project will also affect the milestones. The first 2 weeks of 15-400 will be conducting new literature research as the previous literature research have little relevance to this new problem. I definitely will receive a status on my current project and the retrieval of CLEM datasets from professor Murphy by the beginning of next semester. 

### Accomplishments
I have conducted sufficient literature research that will give me a very good starting point once I receive the CLEM datasets. There are 2 popular approaches in solving this problem. The first idea is to use a convolutional neural network (CNN). The particular CNN architecture of interest that solves this class of problem like image restoration is called U-net. The second idea is to use a conditional generative adversarial network (CGAN). This approach is very similar to the one used previously in professor Murphy’s lab. Once I have obtained the CLEM datasets, I will implement these 2 neural network architecture in either TensorFlow or PyTorch and use the better model as a baseline to build off of. 

### Meeting Milestones
I have conducted the appropriate literature research as well as installing the necessary software. However, I failed to find any CLEM datasets from the Internet.

### Surprises
I was really surprised on how difficult to find and scarce CLEM datasets are. Hopefully, professor Murphy will be able to obtain some CLEM datasets from his collaborators. If this fails, the work around would be to switch the project using only fluorescence images. I explained the workaround in detail in the major changes section.  

### Milestones Revisions

February 1st
• Implement or use the existing GAN to do some analysis on electron microscope (EM) images
• Implement a method to segment fluorescent microscope (FM) images into individual organelles / structures

February 15th
• Develop or implement a method that can either (1) directly register fluorescence distributions in FM images with electron density distributions in EM images or (2) register segmented FM images with texture descriptors in EM images

March 1st
• Finish up the registration algorithm
• Measure or compare the effectiveness of the registration algorithm
• Investigate methods of developing a classifier that can distinguish different probes in FM and EM image

### Resources Needed
As I mentioned previously, progress on my project is currently stopped due to the unavailability of CLEM datasets. Professor Murphy has reached out to one of his collaborator, and he will have a decision on the availability by the start of 15-400. 
