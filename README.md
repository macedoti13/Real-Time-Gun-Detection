# Gun Detection in Video Frames using YOLO Models

This project aims at the detection of guns in video frames using multiple versions of the YOLO (You Only Look Once) object detection models. Specifically, we have used the small, medium, and large models of YOLOv5 and YOLOv8. These models were trained on the [FiDaSS dataset](https://github.com/fidass/fidass_dataset), a dataset consisting of robbery frames from security cameras.

## Dataset

The [FiDaSS dataset](https://github.com/fidass/fidass_dataset) consists of frames from security cameras capturing robberies. The dataset contains three types of labels: gun, armed person, and unarmed person.

## Models

We trained the following six YOLO models on the FiDaSS dataset:

- YOLOv5 Small
- YOLOv5 Medium
- YOLOv5 Large
- YOLOv8 Small
- YOLOv8 Medium
- YOLOv8 Large

Each of these models has been evaluated based on several metrics to compare their performance in detecting guns in video frames.

## Application

Post-training, these models were applied to video frames from the John Wick franchise and another video of robberies. The objective was to detect guns in these videos and measure the performance of the trained models.

## Paper

We have documented the comparison of the YOLO models' performance and the results in a scientific paper. The link to the paper is available in the `Links` section below.

## Links

- [FiDaSS dataset](https://github.com/fidass/fidass_dataset)

## Conclusion

Through this project, we achieved significant insight into the performance of various YOLO models in the detection of guns in video frames. This research can be further extended to real-time gun detection in surveillance systems to help law enforcement authorities.

## Contact

For any queries or suggestions, please feel free to reach out to us at [Email](thialmacedo@gmail.com)
