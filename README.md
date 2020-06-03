### Social Distancing Project
Idea Credits: Landing AI
![alt text](https://github.com/Ceviche98/Social-Distancing-Project/blob/master/Final%20presentation.jpg?raw=true)

### Description
The objective of the project is to have a visual representation of which people are fulfilling the social distancing as a measure to prevent COVID-19. The information for the bounding boxes is in the file "TownCentre-groundtruth_top.csv". To measure the distance between people it is necessary to make a bird eye view. People that are not fulfilling the minimum social distance of 2 meters have a red bounding box. In addition, a red line is drawn between irresponsible people. Finally, an index of irresponsible people is shown in the presentation video. 

#### Distance reference
![alt text](https://github.com/Ceviche98/Social-Distancing-Project/blob/master/rectangle.png?raw=true)

Four points of the track were taken as reference to make the perspective transform.The width of the track is approximately 5.4 meters. With this information, I chose two paralel points on the track to have a reference for distance.

It is important to take into account that the perspective transform is like a ground plane. Hence, I used the center bottom point of the bounding box as the location of a person.
