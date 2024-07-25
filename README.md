# Football Player Detection using YOLOv8

This project aims to detect football players in video footage using the YOLOv8 (You Only Look Once version 8) model. YOLOv8 is a state-of-the-art, real-time object detection system. This repository includes a Jupyter Notebook for model implementation and an example output video demonstrating the detection.

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Model Details](#model-details)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This repository contains the code to detect football players in videos using the YOLOv8 object detection model. The YOLO model is known for its speed and accuracy, making it suitable for real-time applications like sports analytics.

## Technologies Used

- **YOLOv8**: An advanced version of the YOLO object detection algorithm.
- **Python**: The main programming language used.
- **Jupyter Notebook**: For interactive coding and visualization.
- **OpenCV**: For video processing.
- **Numpy**: For numerical operations.
- **Pandas**: For data manipulation and analysis.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/dasdebanna/Football-Player-Detection-YOLOv8.git
    ```
2. Change the directory:
    ```bash
    cd Football-Player-Detection-YOLOv8
    ```
3. Create a virtual environment:
    ```bash
    python -m venv venv
    ```
4. Activate the virtual environment:
    - For Windows:
        ```bash
        .\venv\Scripts\activate
        ```
    - For macOS/Linux:
        ```bash
        source venv/bin/activate
        ```
5. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Open the `football-player-detection-yolov8.ipynb` Jupyter Notebook to see the implementation details and run the model. The notebook includes steps to:

1. Load and preprocess the data.
2. Initialize and load the YOLOv8 model.
3. Perform player detection on sample videos.
4. Visualize and save the output.

To run the notebook, use the following command:
```bash
jupyter notebook football-player-detection-yolov8.ipynb
```
## Model Details
YOLOv8 (You Only Look Once version 8) is a real-time object detection model known for its speed and accuracy. It processes images in a single pass, making it efficient for tasks requiring real-time performance.

Key Features of YOLOv8:
Real-time processing: Capable of processing images at high frame rates.
High accuracy: Improved object detection accuracy compared to previous versions.
Versatility: Can be used for various object detection tasks.
## Results
The output video (output.mp4) in the repository demonstrates the player detection capabilities of the YOLOv8 model. The notebook provides a detailed walkthrough of the detection process and visualization of results.

## Contributing
Contributions are welcome! Please fork this repository and submit pull requests for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
