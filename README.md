# Opencv-motion-detector
This is a project created in fulfilment of the requirements of the CSC 317 course unit under the Bachelor of Science in Computer Science program at the University of Nairobi, Kenya.

## Project Description
In the past, there have been several robberies and a lot of valuable items have been stolen
in museums, banks and even people’s homes across the globe. This has led to loss of
property and information while also leading to security personnel to be sacked because of
incompetency.
It has been established that the main cause of the success of these break-ins was poor
security. This fact creates an opportunity for the creation of a system that will make it easy
to detect unusual activity via motion detection and act on the data obtained

## Project Algorithm
1. Read some kind of vision through camera or CV
2. Detect difference between static and moving objects
3. Convert the difference (movement) to a specific colour; adding a conversion colour.
4. Convert converted colour to a blurred image.
5. Remove the noise via threshold to get the interested image.
6. Dilate to scale the interested image.
7. Add contours to border items to highlight detected movement; to visually see what’s
moving and what’s static.
8. Distinguish smaller movements to larger movements by improving contour to ignore
small movements and instead focus on the larger movements.
9. Provide an interface (winsound) to add an alert.
10. Provide an interface to send an alert to the owner.
