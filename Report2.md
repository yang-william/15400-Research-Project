
# January 29th, 2019

## Major Changes
Professor Murphy questioned the feasibility of creating a generative model for translating a single fluorescence microscopy image to a single electron microscopy image. This is because the amount of information present in a florescence microscopy image is significantly less than in a electron microscopy image. We propose 2 alternate goals to workaround this limitation. The first goal is to use multiple fluorescence microscopy images to reconstruct transmitted-light microscopy images, because we do not have electron microscopy images paired with multiple fluorescences microscopy images. The other goal is, instead of attempting to reconstruct a high resolution electron microscopy images, we predict the parameters for a spline model that outlines the cell boundaries.

## Accomplishments
I completed the training and gained access to CBD’s cluster. I also gained familiarity with PyTorch by implementing a couple of baseline models.

## Meeting Milestones
I was unable to meet the milestone because I have not received the data needed. I also failed to account for the delay due to training needed for the cluster. 

## Surprises
I was surprised on how difficult it is to get started, especially retrieving the data.

## Milestones Revisions

#### February 15th
• Determine whether the existing model is invertible

• Start implementing Conditional Adversarial Network for light-transmitted microscope images

• Retrieve the CLEM data

## Resources Needed
I am currently waiting for the light-transmitted microscopy images to be copied to the cluster. I am also waiting on Professor Murphy for more CLEM data. 
