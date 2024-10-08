## Project: GCP (Ground Control Point) Detection

### Summary

- Created the dataset for detecting Ground Control Points (GCPs). Subsequently, developed a novel statistical algorithm to identify GCPs from large orthomosaic images. Following this, implemented a two-model approach, employing two different YOLOv5 models. The first model detects the bounding box around the GCPs in large images, while the second model is trained specifically on this bounding box data to accurately pinpoint the center of each GCP. Finally, assembled the full pipeline into a complete product, optimizing performance by implementing multithreading and multiprocessing processes.

- In the industry, finding center of GCP with a great accuracy is still a crucial task. My technique has both great accuracy and precision which is very helpful for the industy. `mAP@50 ~ 95.2%` and `mAP@50-90 ~ 95.4%`

### Source Code Link

- (Code is not available to public, since code is part of the company)

### Some Images of GCP Detection

![GCP1](https://github.com/RustyGrackle/top_projects/blob/main/Images/DJI_20240405161044_0146-5-7.jpg)
![GCP2](https://github.com/RustyGrackle/top_projects/blob/main/Images/DJI_20240405162324_0654-2-4.jpg)
![GCP3](https://github.com/RustyGrackle/top_projects/blob/main/Images/DJI_20240405162421_0692-4-7.jpg)
![GCP4](https://github.com/RustyGrackle/top_projects/blob/main/Images/DJI_20240405162610_0764-1-1.jpg)
