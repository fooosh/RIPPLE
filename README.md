# RIPPLE: Repository for Image Post-Processing Large Entities

![ripple logo](https://user-images.githubusercontent.com/80370952/178155076-ed81e114-0903-4345-aca1-17aca98467cb.PNG)

## Photogrammetry Background 

Photogrammetry is an imaging technique used to create three-dimensional models from a stack of overlapping two-dimensional images. Requiring only a 360˚ series of photos and one measurement to develop an accurately scaled 3D model, photogrammetry is a quick, low-cost data collection technique. Using these images and photogrammetry software, such as Meshroom (https://alicevision.org/) or Photomodeler (https://www.photomodeler.com/), users are able to recreate individual 3D models of objects of interest as well as fully scaled environments. Photogrammetry has become a commonly used method for developing three-dimensional models for fluid dynamics and biomechanics analyses as well as a useful tool for the science outreach community. The user-friendly steps of photogrammetry have recently gained appeal in the virtual reality world as developing accurate models and immersive realities from real world environments is possible with very fine tuned photogrammetry images. 

While the data collection and software is quick and user-friendly, the quality of the 3D models created from photogrammetry techniques are dependent on the imaging environment. This is because photogrammetry was originally developed for imaging small, moveable objects in a photolab under controlled parameters with unlimited imaging time. This presents an issue for creating photogrammetric models of large entites in the field where the quality of the images are dependent on location, time of day, and weather. As photogrammetry relies solely on the 360˚ stack of photos to reconstruct a 3D model, these imaging variables largely effect the accuracy of the 3D model.

## Why use RIPPLE? 

RIPPLE is a toolbox of pre-sets that can remove glare, haze, shadows, and background noise from photogrammetry photos. Removing these imperfections from photos before importing the images into photogrammetry software reduces processing time as the software is not trying to create models of the background noise. RIPPLE also aids in creating a more dense point cloud since all features of the entity have enhanced clarity. This results in a higher-quality photogrammetric model. 

Here we present downloadable action files to import into Adobe Photoshop to edit out image imperfections that hinder the quality of photogrammetric 3D models.

## Requirements 

* Adobe Photoshop

## Workflow

* Download the desired pre-set action file from RIPPLE git
* Import the action file into Photoshop
* Batch edit photogrammetry photos with RIPPLE pre-set


![ripple workflow](https://user-images.githubusercontent.com/80370952/178154870-de9df17d-3d44-4af9-953d-284e7cf49cfb.PNG)

## Video Tutorial

(youtube link here)

## Examples

Here we present the results of 3D models created from image stacks that used RIPPLE to remove background noise, glare, shadows, and haze compared to 3D models created from the raw, un-edited images. 

(insert before and after photos from poster)

For a better look at the textured North Atlantic Right Whale 3D model, please view the model on Sketchfab: https://sketchfab.com/3d-models/north-atlantic-right-whale-textured-model-1d083b2adb2b44f1aba1e3477c3be3f3

## Stay Tuned

We are always working on ways to make RIPPLE more accesible! We are currently developing pre-sets for free imaging software such as ImageJ, Gimp, and PhotoP. 

## Team

RIPPLE was developed by Audrey Biondi Kellogg and Dr. Christin Murphy 
