# Traffic_congestion_using_image_processing

This is a project in which a pretrained detection model is used to detect bikes and cars in a frame. A video fraame is siezed first and then using these models detect the starting and ending bounding box coordinates.

bikes.py - This file will only detect two-whellers in an video.


cars.py - This detects four or more whellers from video.

main.py - This is a combined file to generate cars and bikes bounding box coordinates. It also gives the total number of cars or bikes that had been passed.


![cars and bikes](https://github.com/ARPITJAIN0999/Traffic_congestion_using_image_processing/blob/main/combinedpassing.PNG)
