# Laser_Imaging_Crater
We use a single laser line to scan over craters generated by low velocity impacts in granular media (sands). The idea is to use laser triangulation method to access the crater morphology profile within some resolution limites set by the density of laser lines we scan. Here are some specifics:

- Camera is positioned at an angle of 45 degree to the level surface in order to present depressions and curvatures.
- We image the laser line one frame each time and scan over the whole crater/ near-crater region. 
- Currently, we approximate the parallex error for the depression depth by Sqrt(2) and in the future versions we will give a detailed correction. 
- Tilting of laser lines due to camera placement is corrected by checking the tilting of laser baselines outside of the crater.
- We are currently working on create an algorithm to calculate the mean of several measureement
- This is a static analysis now and we hope to apply it for investigating the process of crater excavation. 

`Raw_images` contains raw images we took for analysis.\
`Laser_Triangulation_static_v1.ipynb` contains the latest version. 

