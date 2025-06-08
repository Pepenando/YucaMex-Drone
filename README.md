# YucaMex-Drone

Dataset of images and object detection annotation labels taken by a drone from different street intersections in the cities of Valladolid and Uman in Yucatan, Mexico. 

![Street samples](/ref/videos_exp.png)

## Description
S1 and S1US2 images and labels datasets:
- Dataset used for the development of a system that detects, tracks, and counts different types of vehicles, as well as pedestrians, at selected street intersections in these cities.  
- Labeling done in Yolo Label.
- One label file per image. Follows YOLO formatting with normalized measurements (id, x_center, y_center, width, height).
- Drone flying at 50 meter altitude. Zenithal view.
- +4400 images. 4K quality.

Object types (from left to right see image below):
- Top row: car, truck, bus, combi. 
- Bottom row: motorcycle, bike, mototaxi, pedestrian.

![Vehicle samples](/ref/vehicle_types.jpg)

Result videos and reports for experimentation of automatic count system.  
Report contains counts per object per experimentation video.  
Videos show visually the tracking and the counting of objects.
Comparison of tracking methods:
- Intersection over Union (IOU)
- Intersection over Union + Template Matching (IOU + TM)
- deepSORT (DS)

## Content
- [S1 images and labels dataset (train / test)](https://github.com/MemoJmz/YucaMex-MOCS/tree/main/segments)
- S1US2 images and labels dataset (train / test)
- [Result videos and reports](https://drive.google.com/drive/folders/1NhuE__enX_hjnyoj6N2A6AKsl2pqZyX3?usp=sharing)
- [Experimentation videos](https://drive.google.com/drive/folders/1eFsC2K28lvg37kcL7VFsSu1wcP-vYA5r?usp=sharing)

## Notes
The manuscript has been submitted to the journal Multimedia Tools and Applications for peer review.  
The S1US2 set will be available after the paper is accepted.  
