Detection of Bus Number in Bus Panel - Project by Wenna Loo

Within the bus_number_detector_datasets.zip file, you will be able to find the following folders:
- videos: The videos here are YouTube videos of public buses arriving at a bus stop in Singapore.
	├── Video1.mp4 (downloaded from: https://www.youtube.com/watch?v=gvw2IUFpjvQ&t=2s)
	└── Video2.mp4 (downloaded from: https://www.youtube.com/watch?v=FoJRvKlVTEA&t=332s)
- images: The images here are individual frames extracted from the video files. 
- annotations: The annotations of bus panels are saved here. The saved annotations are in YOLO format.
- data.zip: This zip folder stores the correctly formatted dataset that have already been split into train, validation, and test set.

Note: Due to time constraint, I've only managed to label 500 images. Hence, feel free to label more images if required. 
Will recommend to train the object detection model on images of buses at night since the current model is largely trained on images of buses in the day.