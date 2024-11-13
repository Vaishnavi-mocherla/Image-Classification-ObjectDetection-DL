# Image Classification and Object Detection 

This project consists of multiple notebooks demonstrating machine learning and computer vision techniques, using PyTorch, YOLO from Ultralytics, and the Kaggle API for dataset access. Each notebook covers specific tasks such as model training, evaluation, and object detection in images and videos.

## Setup Instructions

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Kaggle API (if you intend to download datasets from Kaggle)

### Installation

1. Clone this repository and navigate to the project directory:

    ```bash
    git clone https://github.com/Vaishnavi-mocherla/Image-Classification-ObjectDetection-DL
    cd Image-Classification-ObjectDetection-DL
    ```

2. Install the required packages:

    ```bash
    pip install -r equirements.txt
    ```

### Kaggle API Setup (Optional)

1. Download your Kaggle API token (`kaggle.json`) from [Kaggle Account](https://www.kaggle.com/account).
2. Place the `kaggle.json` file in the root of the project folder.
3. Configure Kaggle in your environment by running:

    ```python
    import os
    os.system('mkdir -p ~/.kaggle')
    os.system('cp kaggle.json ~/.kaggle/')
    os.system('chmod 600 ~/.kaggle/kaggle.json')
    ```

### Usage

#### code-file.ipynb
Open the Jupyter Notebook and run all cells to train the model and evaluate it. Make sure Kaggle setup is complete if using Kaggle datasets.
This notebook demonstrates object detection on video files. Ensure the following files are in place before running the notebook:
- **Source video** (`Source.mp4`), located in the project directory.

The notebook will process each frame in the video, draw bounding boxes, and save the final output as `processed_video.mp4`.

### Files
- **requirements.txt**: Python package dependencies for both notebooks.
- **README.md**: Project overview and setup instructions.
- **.gitignore**: Excludes unnecessary files from the repository.

"""

