# License-plate-detection-using-Yolov8-and-Easyocr

This repository contains a pipeline for detecting license plates in images and videos using YOLOv8 and recognizing the text on the detected license plates using EasyOCR. The project demonstrates an end-to-end workflow for real-time license plate detection and recognition.

---

## Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Dataset](#dataset)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Output](#output)
7. [Acknowledgments](#acknowledgments)

---

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

## Installation

### 1. Clone the Repository
Clone this repository to your local machine:

