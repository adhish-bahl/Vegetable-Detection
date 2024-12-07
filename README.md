
# DeepFriedNeurons

## Overview

DeepFriedNeurons is a project utilizing the YOLO (You Only Look Once) model for object detection and analysis. This notebook walks through the steps of setting up the environment, importing the necessary libraries, and using a pretrained YOLO model for tasks such as detection and visualization.

## Developers

- **Adhish Bahl** (2347203)
- **PAVITHARANI G P** (2347244)

## Requirements

To run this project, you need the following software and libraries installed:

- Python 3.10 or later
- ultralytics (Version: 8.3.19)
- numpy
- matplotlib
- OpenCV
- supervision

## Installation

1. Clone the repository or download the notebook.
2. Install the required libraries using the commands provided in the notebook:

```bash
pip install ultralytics==8.3.19
pip install supervision[assets]==0.24.0
```

## Steps to Run the Project

1. **Download and Install Libraries**
   The notebook begins with installing the required Python libraries, as shown in the `pip install` commands above.

2. **Import Packages**
   After the libraries are installed, the notebook imports necessary packages, such as `YOLO` from the ultralytics library, `numpy`, `matplotlib`, and `cv2` for computer vision operations.

3. **Load the Pretrained Model**
   Use the YOLO model pretrained on a dataset for object detection tasks. The model and its configuration are loaded using the ultralytics library.

4. **Run Object Detection**
   Follow the steps in the notebook to perform object detection on images or videos, visualize the results, and analyze the outputs.

5. **Visualize and Save Results**
   The notebook includes code snippets to visualize the detections and save results to the desired location.

## How to Use

1. Open the notebook in Jupyter Notebook, JupyterLab, or Google Colab.
2. Follow the cells step-by-step to install dependencies, load the model, and perform detection tasks.
3. Modify the input paths or parameters as needed to analyze your dataset.

## Contributing

If you'd like to contribute, feel free to submit a pull request or report issues. Please ensure compatibility with the existing library versions.

---

Happy coding!
