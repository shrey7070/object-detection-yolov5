# Object Detection with YOLOv5

This repository contains a Python application that demonstrates object detection using the YOLOv5 model. The project uses PyTorch to run YOLOv5 for detecting objects in both images and real-time video streams. This is ideal for anyone interested in computer vision applications, from educational purposes to practical implementations in security systems or automated monitoring.

## Features

- Real-time object detection with webcam support.

- Image object detection by processing static images from a directory.

- Utilizes the ultralytics YOLOv5 model, pre-trained on the COCO dataset.

- Simple command line interface for easy interaction.

## Getting Started

Follow these instructions to get the project up and running on your local machine for development and testing purposes.

### Prerequisites

You'll need Python 3.8 or later, and pip installed on your system. Optionally, if you plan to use GPU acceleration, ensure your system has a compatible NVIDIA GPU with CUDA installed.

### Installation

#### 1. **Clone the repository**

```bash

git  clone  https://github.com/yourusername/object-detection-yolov5.git

cd  object-detection-yolov5

```

#### 2. **Set up a Python virtual environment (recommended)**

```bash

python  -m  venv  venv

source  venv/bin/activate  # On Windows use `venv\Scripts\activate`

```

#### 3. **Install dependencies**

```bash

pip  install  -r  requirements.txt

```

#### 4. **Running the Application**

```bash

python  main.py

```

# **Technologies Used**

• [PyTorch](https://pytorch.org/) - The framework used for handling the YOLOv5 model.

• [OpenCV](https://opencv.org/) - Used for image and video manipulation.

# **Authors**

• **Shrey Soni** - [Link](https://github.com/shrey7070)

# **Acknowledgments**

• Ultralytics for the awesome YOLOv5 model

• The PyTorch team for providing such a powerful tool
