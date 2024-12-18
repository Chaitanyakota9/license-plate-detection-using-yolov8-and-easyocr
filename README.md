# License-plate-detection-using-Yolov8-and-Easyocr

This repository contains a pipeline for detecting license plates in images and videos using YOLOv8 and recognizing the text on the detected license plates using EasyOCR. The project demonstrates an end-to-end workflow for real-time license plate detection and recognition.



## Overview

This project utilizes YOLOv8 for license plate detection and EasyOCR for text recognition. A pre-trained YOLOv8 model was fine-tuned using the [License Plate Dataset](https://universe.roboflow.com/mochoye/license-plate-detector-ogxxg/dataset/2). EasyOCR extracts the text from detected license plates, making it suitable for applications like automated parking systems or traffic monitoring.

---

## Features

- **YOLOv8:** Accurate and fast object detection for license plates.
- **EasyOCR:** Robust text recognition from license plates.
- **Video Support:** Process videos frame-by-frame for detection and recognition.
- **Customizable:** Fine-tune the YOLOv8 model for specific datasets.

---

## Dataset

The dataset used for this project is publicly available on [Roboflow License Plate Dataset](https://universe.roboflow.com/mochoye/license-plate-detector-ogxxg/dataset/2). The dataset contains annotated images of license plates from different vehicles.

---
### Example Output:  
**Input:**  

![input](https://github.com/user-attachments/assets/599823b5-bddd-4eb5-bb1d-3d82c414f26e)


**Output:**  

![output](https://github.com/user-attachments/assets/5dc7c355-af84-46a2-93cc-2054680848e7)




This project is licensed under the MIT License - see the LICENSE file for more details.

