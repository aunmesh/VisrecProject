## (Asim)

### Hypothesis: 
Depth Perception and Segmentation aid each other. 
For dense segmentation depth cues are important.
For dense hierarchical segmentation, depth cues may help to generate segmentation mask for segmenation at the next level.

### Aim: 
Try to design a cooperative procedure between depth prediction and image segmentation. End goal should be that predicted
depth should have high local variations(predicted depth should not be smooth at a location, if an object at that location is not 
smooth). The segmentation should be dense hierarchical segmentation.

### Approach:
1. Use multi scale windows in RGB image to enhance the depth prediction at a particular image patch.
Use cooperation between neighnouring windows for global continuity and smoothness. Using the changed depth prediction, for a 
particular foreground object, construct a hierarchical segmentation mask for the next level.




## (Ninad)
